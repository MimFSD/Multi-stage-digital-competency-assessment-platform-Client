# ✅ Test_School Competency Assessment Platform

This is a full-stack digital competency assessment platform designed to evaluate users through a secure, multi-step testing process. The platform assigns a digital competency level (A1–C2) based on performance in progressively challenging tests, generates certification, and ensures exam integrity.

---


## 🧰 Tech Stack

### 🔹 Frontend

- React.js + TypeScript
- Redux + RTK Query + Axios
- Tailwind CSS
- Redux Persist

### 🔹 Backend

- Node.js + Express + TypeScript
- MongoDB + Mongoose
- JWT Authentication
- Nodemailer / Twilio (Email/SMS OTP)

---

## 🧾 Features

### 🎯 3-Step Competency Test

Each user progresses through 3 stages of tests:

#### Step 1 → A1 & A2

- Score <25% → ❌ Fail (no retake)
- 25–49.99% → ✅ A1 Certified
- 50–74.99% → ✅ A2 Certified
- ≥75% → ✅ A2 Certified + Go to Step 2

#### Step 2 → B1 & B2

- <25% → Stay at A2
- 25–49.99% → ✅ B1 Certified
- 50–74.99% → ✅ B2 Certified
- ≥75% → ✅ B2 Certified + Go to Step 3

#### Step 3 → C1 & C2

- <25% → Stay at B2
- 25–49.99% → ✅ C1 Certified
- ≥50% → ✅ C2 Certified

### ⏱ Timer System

- Configurable: default is 1 minute/question
- Auto-submit on time expiry

### 📚 Question Pool

- 132 total questions (22 competencies × 6 levels)
- 44 questions per step
- Categorized by competency and level

### 📜 Certification

- Auto-generated based on final score
- Downloadable PDF & optional email delivery

---

## 🔐 Authentication & Roles

### 👥 User Roles

- **Admin**: Manages platform
- **Supervisor**: Reviews & monitors
- **Student**: Takes the assessment

### 🔑 Auth Features

- JWT Access + Refresh Tokens
- Registration (with email verification)
- Secure password hashing (bcrypt)
- OTP (email/SMS) support for verification/reset

---

## 🛡 Secure Exam Environment (Bonus)

- Safe Exam Browser (SEB) integration
- Block external navigation/input
- Enable live video monitoring


