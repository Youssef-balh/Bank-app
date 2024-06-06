# Bank-app
Bank Desktop app in C#
# Desktop Bank Application

## Overview

This project is a desktop banking application developed in C# with a MySQL database. The application enables users to manage their bank accounts, perform transactions, and access account information securely. The project includes features such as account verification via Gmail SMTP, session expiration, and secure password handling using hashing.

## Features

### 1. User Authentication and Security
- **Password Hashing**: User passwords are hashed before storing in the database to enhance security.
- **Email Verification**: A verification code is generated using GUID and sent to the user's registered email address using Gmail SMTP for account activation and transaction confirmation.
- **Session Management**: User sessions expire after a period of inactivity to ensure security.

### 2. Account Management
- **Account Creation**: Admins can create and activate new user accounts.
- **Account Viewing**: Users can view details of their accounts, including balance, account type, and transaction history.

### 3. Transactions
- **Funds Transfer**: Users can transfer funds between their accounts, subject to maximum transfer limits and overdraft protections.
- **Bill Payment**: Users can pay bills by selecting the account to debit and entering necessary payment details.

### 4. User Interface
- **Login Page**: Users log in using their email and password. A successful login redirects them to their account summary.
- **Account Summary**: Displays all accounts associated with the user and their respective balances.
- **Transaction History**: Lists all transactions made by the user, including transfers and payments.
- **Session Expiration**: Sessions automatically expire after a few minutes of inactivity to maintain security.

## Technical Details

### Technology Stack
- **Frontend**: C# (Bunifu framework)
- **Backend**: .NET Framework
- **Database**: MySQL
- **Email Service**: Gmail SMTP

### Security Implementations
- **Password Hashing**: Passwords are hashed using a secure algorithm before being stored in the database.
- **Verification Code**: Generated using GUID and sent via email for account verification and transaction approval.

### Email Configuration
- **SMTP Setup**: Configured to use Gmail SMTP for sending verification codes and notifications.
- **Verification Process**: Upon certain actions (e.g., account creation, fund transfer), a verification code is emailed to the user.

### Database Schema
The application uses a MySQL database with the following key entities:
- **Bank**: Bank details including ID and name.
- **Agency**: Details of bank branches including ID, name, and address.
- **Account**: User account details including account number, ID, and opening date.
- **Transaction**: Transaction details including amount, date, and transaction type.
- **Client**: Client details including ID, name, and address.

## Getting Started

### Prerequisites
- Visual Studio with .NET development tools
- MySQL server
- Gmail account for SMTP configuration

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/desktop-bank-app.git



# Desktop Bank Application Screenshots

<table>
  <tr>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/d217bd20-dccf-491e-8690-171b4ab1ecba" width="400"/></td>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/24023795-7eac-4996-9f77-cd82391e05a5" width="400"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/7c65f7d3-24b9-419e-9427-da273b6c018f" width="400"/></td>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/6a5f46c1-e19e-41f0-b69f-5e5674a0714d" width="400"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/6c6c45e1-7435-4548-a8de-898f746bd4c6" width="400"/></td>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/15d6d210-0825-40dd-9a65-58abe8656f6e" width="400"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/76c97b20-33a7-43a6-826b-0503608c84c4" width="400"/></td>
    <td><img src="https://github.com/Youssef-balh/Bank-app/assets/113738047/0eeac647-11b0-4e3e-977d-f24e8afbe75a" width="400"/></td>
  </tr>
</table>


