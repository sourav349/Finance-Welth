# 💸 AI Finance Platform  
### Full Stack Project using Next.js 15, React 19, Tailwind CSS, Supabase, Prisma, Clerk, Inngest, Arcjet & Shadcn UI  

This project is a **modern, AI-powered finance management platform** built using the latest **Next.js 15** and **React 19**.  
It enables users to manage their personal finances, track spending, analyze transactions, and receive AI-driven financial insights — all within a secure and automated environment.

---

## 🧠 Overview

The **AI Finance Platform** integrates authentication, real-time data handling, automation, and AI intelligence to deliver a seamless finance-tracking experience.  
It includes modules for **user account management**, **transaction analysis**, **AI receipt scanning**, **budget alerts**, and **monthly insights generation**.

This project is ideal for your **developer portfolio**, showcasing your ability to build and integrate **complete full-stack systems with automation and AI**.

---

## 🚀 Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Frontend** | React 19, Next.js 15, Tailwind CSS, Shadcn UI |
| **Backend** | Next.js API Routes, Prisma ORM, Supabase (PostgreSQL) |
| **Authentication** | Clerk |
| **Automation** | Inngest (Cron Jobs, Background Functions) |
| **Security & Rate Limiting** | Arcjet |
| **AI Integration** | AI Receipt Scanner & Monthly Insights Generator |
| **Deployment** | Vercel |

---

## ⚙️ System Workflow

### 🧩 1. **User Authentication (Clerk)**
- Secure login, signup, and session management using **Clerk**.
- Clerk handles user identity and access tokens.
- Once authenticated, users are redirected to their personal **dashboard**.

---

### 🗄️ 2. **Database & Models (Supabase + Prisma)**
- Supabase hosts the **PostgreSQL** database.
- Prisma manages schema and data access with models like:
  - **User** → basic user info linked with Clerk ID  
  - **Account** → manages multiple accounts per user  
  - **Transaction** → stores all transaction records  
  - **Budget** → handles spending limits and goals  
- Prisma migrations ensure the database stays consistent.

---

### 🧠 3. **AI Receipt Scanner**
- Allows users to upload images of receipts.  
- AI automatically extracts merchant, date, and amount details.  
- Adds them directly into the user’s transaction history — no manual entry needed.

---

### 📊 4. **Dashboard & Data Visualization**
- Built using **Shadcn UI** and **Tailwind CSS** for a clean and modern interface.  
- Displays:
  - Account balance summary  
  - Transaction table (sortable & filterable)  
  - Expense pie chart  
  - Monthly budget bar chart  
- Data is fetched dynamically using **custom React hooks**.

---

### 🔄 5. **Backend APIs (Next.js App Router)**
- Backend logic is handled by **Next.js API routes**.
- APIs handle:
  - CRUD operations for transactions and accounts  
  - Fetching filtered data  
  - Storing AI-processed data  
- Utilizes **server actions** for seamless frontend-backend communication.

---

### ⚙️ 6. **Automations with Inngest**
- **Inngest** enables background tasks and scheduled jobs, such as:
  - 📆 Monthly budget reminders  
  - 💌 Automated report emails  
  - 🔁 Recurring transaction handling  
  - 🤖 Monthly AI insights generation  
- All these tasks run automatically — no manual triggers needed.

---

### 🧾 7. **Budget Alerts & Email Notifications**
- When user spending exceeds set limits, an **automated email** is triggered.  
- Monthly **AI-generated reports** summarize user spending and trends.  
- Both alerts are powered by **Inngest** background workflows.

---

### 🧱 8. **Security & Rate Limiting (Arcjet)**
- **Arcjet** protects APIs by:
  - Limiting excessive API requests  
  - Blocking bot traffic  
  - Detecting suspicious activity in real time  
- Ensures system reliability and data security under heavy loads.

---

### 🌐 9. **Deployment (Vercel)**
- Deployed on **Vercel** for lightning-fast builds and global scalability.
- Environment variables are securely managed in Vercel’s dashboard.
- Automatic CI/CD pipeline for every commit.

---

## 📂 Folder Structure


---

## 🧰 Features Summary

| Feature | Description |
|----------|-------------|
| 🔐 **Authentication** | Secure login & signup via Clerk |
| 💳 **Account Management** | Manage multiple user accounts |
| 💰 **Transaction System** | Add, fetch, delete, and filter transactions |
| 🧾 **AI Receipt Scanner** | Auto-extract transaction data from receipts |
| 📈 **Data Visualization** | Real-time charts & dashboards |
| 💡 **AI Insights** | Smart recommendations for savings |
| 📧 **Email Notifications** | Budget alerts and monthly summaries |
| 🔁 **Recurring Transactions** | Automated handling with Inngest |
| 🛡️ **Rate Limiting** | Arcjet for bot protection and request control |
| 🚀 **Deployment** | Hosted seamlessly on Vercel |

---

## 🚀 Getting Started with Finance-Welth

Build and run your **AI-powered Finance Platform** in just a few steps!  
This project integrates **Next.js 15**, **React 19**, **Supabase**, **Clerk**, **Inngest**, and **Arcjet** to deliver a secure, automated, and intelligent financial experience. 💰

---

### 🧩 1️⃣ Clone the Repository
git clone https://github.com/sourav349/Finance-Welth.git
cd Finance-Welth
---

### ⚙️ 2️⃣ Install Dependencies
npm install
# or
yarn install
--- 
### 🔐 3️⃣ Setup Environment Variables
Create a .env.local file in the root directory and add:
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
INNGEST_API_KEY=
ARCJET_API_KEY=
SUPABASE_URL=
SUPABASE_ANON_KEY=
---
###🧠 4️⃣ Run the Development Server
npm run dev
# or
yarn dev
---
### 🖼️ Preview
<div align="center"> <img width="850" alt="Dashboard Screenshot 1" src="https://github.com/user-attachments/assets/a152f4f2-e9d9-4e4e-8ab1-42d13ee9edec" /> <br/><br/> <img width="850" alt="Dashboard Screenshot 2" src="https://github.com/user-attachments/assets/44beebc3-eb45-439b-b0ba-9fc771368a1c" />
</div>
---

🏁 Conclusion
This AI-driven finance app combines modern web technologies with real-time automation to provide users with a smarter, more secure financial experience.
You’ll find everything from authentication and dashboards to AI-based insights, background jobs, and automated reports — all in one platform. 🌟

💬 Tip: Deploy easily on Vercel
 for instant hosting!
⭐ Star this repo if you like the project!
