# UniPay | Full-Stack Fintech Banking Platform [![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit-blue)](https://unipay-finance.vercel.app)

UniPay is a modern full-stack banking application that enables users to securely connect bank accounts, monitor balances, track transactions, and manage financial activities through a unified dashboard.

Built with Next.js, TypeScript, Appwrite, Plaid, and Dwolla, UniPay delivers a seamless digital banking experience with secure authentication, bank account aggregation, transaction insights, and money transfer capabilities.

---

## Table of Contents
- [Live Demo](#live-demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Installation](#installation)
- [Key Functionalities](#key-functionalities)
- [Future Enhancements](#future-enhancements)
- [Learning Outcomes](#learning-outcomes)
- [Author](#author)
- [License](#license)

---

## Live Demo

Check out the live website [here](https://unipay-finance.vercel.app).

---

## Features

### Secure Authentication

* User registration and login
* Session-based authentication using Appwrite
* Secure account management

### Bank Account Integration

* Connect multiple bank accounts using Plaid
* Retrieve account details and balances
* View linked institutions in a single dashboard

### Transaction Management

* View detailed transaction history
* Paginated transaction records
* Real-time account activity tracking

### Funds Transfer

* Transfer money between connected accounts
* Dwolla integration for payment processing
* Secure transaction workflows

### Financial Dashboard

* Aggregate account balances
* Account overview and insights
* Responsive and user-friendly interface

---

## Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS

### Backend & Services

* Appwrite
* Plaid API
* Dwolla API

### Development Tools

* ESLint
* PostCSS
* Git & GitHub

---

## Architecture

```text
User
 │
 ▼
Next.js Frontend
 │
 ├── Appwrite Authentication
 │
 ├── Plaid Integration
 │      └── Bank Accounts & Transactions
 │
 └── Dwolla Integration
        └── Money Transfers
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/JyotiAggarwal2/UniPay.git
cd UniPay
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file in the root directory.

### Run Development Server

```bash
npm run dev
```

---

## Key Functionalities

* Multi-bank account aggregation
* Secure user authentication
* Transaction analytics
* Account balance monitoring
* Fund transfer workflows
* Responsive UI across devices

---

## Future Enhancements

* AI-powered spending insights
* Budget planning and tracking
* Investment portfolio integration
* Credit score monitoring
* Financial goal management
* Fraud detection alerts

---

## Learning Outcomes

This project helped strengthen expertise in:

* Full-stack application development
* API integrations
* Authentication and authorization
* Financial technology systems
* State management and data flow
* TypeScript and scalable architecture

---

## Author

**Jyoti Aggarwal**

GitHub: https://github.com/JyotiAggarwal2

LinkedIn: [Jyoti Aggarwal](https://www.linkedin.com/in/jyotiaggarwalofficial/)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
