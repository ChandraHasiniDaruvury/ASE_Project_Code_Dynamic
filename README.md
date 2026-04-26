# 🛒 Intelligent Retail Management System (IRMS)

**AI-Driven Pricing & Coupon Automation for E-commerce**

---

## 📌 Overview

IRMS is a full-stack MERN application that automates pricing, coupon generation, and inventory analysis using AI.

It eliminates manual pricing work and enables data-driven decisions for small e-commerce stores.

---

## 🚀 Key Features

### 🔹 Dynamic Pricing Engine
- Calculates an **urgency score (0–1)** for every product
- Automatically applies discounts based on:
  - Product age (70%)
  - Stock level (30%)
- Ensures price never drops below **50% of base price**

---

### 🔹 Automated Coupon System
Four types of coupons:

| Type | Trigger | Scope |
|------|--------|------|
| Thank You | After every purchase | Personal |
| Loyalty | Milestone orders | Personal |
| Clearance | Low stock + high age | Global |
| Campaign | Admin-created | Global |

---

### 🔹 AI-Powered Insights
- Uses **Groq API (Llama 3.1)**
- Provides:
  - Inventory health status
  - Critical product alerts
  - Actionable recommendations

---

### 🔹 Analytics Dashboard
- Revenue & order tracking
- Coupon performance
- Top-selling products
- Inventory health monitoring

---

## 🛠️ Tech Stack

- **Frontend:** React (Vite), Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **AI:** Groq API (Llama 3.1)  
- **Auth:** JWT (role-based)  

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd irms

Start the Application

# Terminal 1 — Backend
cd backend
npm install
npm run dev

# Terminal 2 — Frontend
cd frontend
npm install
npm run dev

