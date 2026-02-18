<div align="center">

# 🚀 ERP System

### Enterprise Resource Planning System

[![TypeScript](https://img.shields.io/badge/TypeScript-94.4%25-blue?style=for-the-badge&logo=typescript&logoColor=white&color=3178C6)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-5.5%25-yellow?style=for-the-badge&logo=javascript&logoColor=black&color=F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Next.js](https://img.shields.io/badge/Next.js-13.5-black?style=for-the-badge&logo=next.js&logoColor=white&color=000000)](https://nextjs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-ORM-white?style=for-the-badge&logo=prisma&logoColor=white&color=2D3748)](https://www.prisma.io/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb&logoColor=white&color=47A248)](https://www.mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-blue?style=for-the-badge&logo=tailwind-css&logoColor=white&color=06B6D4)](https://tailwindcss.com/)

</div>

---

## 🌟 Overview

This ERP system provides a centralized platform to manage business operations including user management, inventory, sales, finance, and workflow processes.

It is built using **Next.js, TypeScript, Prisma ORM, and MongoDB**, following a modular and scalable architecture.

> 🚧 Project is under active development.

---

## ✨ Features

### 📊 Dashboard
- Real-time business metrics
- Summary cards and data visualization
- Role-based data visibility

### 👥 User Management
- Role-based access control (Admin, Manager, Employee, Viewer)
- Authentication using NextAuth
- User activity tracking

### 🏢 Organization Management
- Multi-company structure
- Department and team management

### 📦 Inventory Management
- Add, update, delete inventory items
- Stock quantity tracking
- SKU & category management

### 💰 Sales Management
- Create new sales
- Automatic total calculation
- Inventory validation before sale
- Sales status tracking (Pending / Completed / Cancelled)

### 💵 Finance Module
- Transaction recording
- Financial reports
- Budget tracking

### 🔄 Workflow & Notifications
- Approval flows
- Task management
- Notification system

---

## 🛠️ Tech Stack

### Frontend
- Next.js 13
- React
- TypeScript
- Tailwind CSS
- Shadcn UI

### Backend
- Node.js
- Prisma ORM
- MongoDB
- NextAuth (Authentication)

### Deployment
- Vercel
- GitHub Actions
- Docker (optional)

---

## 🏗️ System Architecture

```mermaid
graph TD
    A[Client Browser] --> B[Next.js Frontend]
    B --> C[API Routes]
    C --> D[Business Logic Layer]
    D --> E[Prisma ORM]
    E --> F[(MongoDB Database)]
    G[Authentication - NextAuth] --> B
```

---

## 🚀 Installation

### Prerequisites
- Node.js v18+
- MongoDB instance

### Setup

```bash
git clone https://github.com/kajal801034-creator/ERP-AI
cd ERP-AI
npm install
```

### Configure Environment Variables

Create `.env` file:

```
DATABASE_URL="mongodb+srv://..."
NEXTAUTH_SECRET="your-secret"
NEXTAUTH_URL="http://localhost:3000"
```

### Setup Database

```bash
npx prisma generate
npx prisma db push
```

### Run Development Server

```bash
npm run dev
```

App runs on:

```
http://localhost:3000
```

---

## 🖥️ Usage

### Roles Supported

- **Administrator** – Full access
- **Manager** – Department-level access
- **Employee** – Limited access
- **Viewer** – Read-only access

---

## 📚 API

- RESTful API routes
- JWT-based authentication
- Inventory & Sales endpoints
- Role-based middleware protection

---

## 📄 License

MIT License

---

<div align="center">

Made with ❤️ by **Kajal Kumari**

</div>
