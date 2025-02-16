# Library Management App

This is a simple fullstack web app for library management, built using the MERN stack.
<!-- ABOUT THE PROJECT -->

## 🔰 About the project

The system allows **Librarians** and **Members** to login to the web app (using accounts created by librarians)

Lbrarians can:
- Manage (CRUD)
  - Authors
  - Genres
  - Books
  - Borrowals
  - Users

Members can:
- View (R)
  - Authors
  - Genres
  - Books
  - Own borrowals
- Add (C)
  - Own borrowals
  

<!-- GETTING STARTED -->

## ⚡ Getting Started

### ❕ Prerequisites
You need a computing environment with an up to date version of Windows/Mac OS/Linux and a working internet connection

* Git
* Node.js
* NPM
* A web browser (Chrome/Edge recommended)



### 🚀 Installing and executing (dev)
1. cd to project folder (LibraryManagement)
2. Run the following commands in terminal:
  - To install NPM packages
```
npm run install
```
  - To start both server and client applications
```
npm start
```

3. Use the following demo accounts to login
- Librarian
```
Email address: testlibrarian@library.com
Password: librarian123
```

- Member
```
Email address: testmember@library.com
Password: member123
```
<!-- FILE STRUCTURE -->

###  📂 File Structure
```
.
├── client
│   ├── public
│   │   ├── assets
│   │   └── index.html
│   └── src
│       ├── hooks
│       ├── sections
│       │   ├── @dashboard
│       │   │   ├── app
│       │   │   ├── author
│       │   │   ├── book
│       │   │   ├── borrowal
│       │   │   ├── genre
│       │   │   └── user
|       │   └── auth
│       │       └── login
│       ├── utils
│       ├── App.jsx
│       ├── index.js
│       ├── constants.js
│       └── routes.js
│
├── server
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── index.js
│   └── passport-config.js
│
├── package.json
├── README.md
└── LICENSE.md
```
* Only the core files and directories are shown in the above tree

| No |       File Name      |             Details             |
|----|----------------------|---------------------------------|
| 1  | server/index.js      | Node.js server app entry point  |
| 2  | client/src/index.js  | Client react app entry point    |

