<div align="center">
  <a href="https://github.com/bhardwaj-snigdh/college-notice-broadcast-app">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/Town_Crier%2C_Provincetown%2C_MA.jpg" alt="Logo" width="100" />
  </a>
  
  <h3 align="center">Town Crier</h3>
  
  <p align="center">
    A notice app for everyone.
    <br />
    Send notices to everyone or select your audience.
  </p>
</div>

#### Built With

![Typescript](https://img.shields.io/badge/Typescript-20232A?style=for-the-badge&logo=typescript)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react)
![Express](https://img.shields.io/badge/Express-20232A?style=for-the-badge&logo=express)
![Passport](https://img.shields.io/badge/Passport-20232A?style=for-the-badge&logo=passport)
![Prisma](https://img.shields.io/badge/Prisma-20232A?style=for-the-badge&logo=prisma)
![Postgresql](https://img.shields.io/badge/Postgresql-20232A?style=for-the-badge&logo=postgresql)

## Features

- CRUD on Notices
- Role Based Authentication
- Rules for creating a message and selectiong audience
- Super User (Admin) support

## App Demo in 50 Seconds

https://user-images.githubusercontent.com/59894983/184187266-da53d247-8ea0-4114-8703-4b7c08230c45.mp4

## Installation and Setup Instructions

Clone down this repository. To run this repository you will need **node.js**, **npm**, **expo cli** and **postgresql** installed globally on your machine.

1. Install Dependencies:

```bash
cd frontend && npm install
cd ..
cd backend && npm install
```

2. Generate JWT Signing Keys:

```bash
# from /backend
ts-node generateRSAKeyPair.ts
```

3. Build Prisma Client and Seed DB

```bash
#from /backend
npx prisma generate
```

4. To Start Server:

```bash
# from /backend
npm start
```

5. Start App:

```bash
# from /frontend
API_BASE='put backend address' npm start
```

6. Scan the QR Code from [Expo Go](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en_IN&gl=US 'Expo Go') to run this app
