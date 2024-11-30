# Mini Loan App

The **Mini Loan App** is a full-stack application that allows customers to apply for loans and make repayments, while administrators can approve loans and manage the system. This application consists of a backend API built with **Node.js**, **Express.js**, **MongoDB**, and **JWT Authentication** for secure user access. The frontend is a minimal HTML5 interface with form validation.

## Features

### Customer Features:
- **Register/Login**: Secure registration and login using JWT authentication.
- **Loan Requests**: Submit loan requests with the amount and term.
- **View Loans**: View loans belonging to the logged-in customer.
- **Repayments**: Make repayments and track loan status.

### Admin Features:
- **Approve Loans**: Approve pending loan requests from customers.
- **Manage Loans**: Update loan statuses and manage customer repayments.

## Technology Stack

- **Frontend**: HTML5, CSS, JavaScript (Minimal UI)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT and bcrypt for secure user authentication
## Setup Instructions

### Prerequisites

- Node.js (v16 or higher)
- MongoDB (can use local or MongoDB Atlas)

## Installation

 Clone the project 

```bash
git clone https://github.com/yourusername/mini-loan-app.git
```

### Setup instruction  for Frontend

1. Move into the directory

```bash
cd frontend
```
2. install  dependenices

```bash
npm install
```
3.  run the server

```bash
npm run dev
```

### Setup instruction  for Backend

1. Move into the directory

```bash
cd server
```
2. install  dependenices

```bash
npm install
```
3.  run the server

```bash
npm run dev
```
4.  Set up environment variables:
   Create a `.env` file in the `server` directory and add the following:

```bash
