# MediAssist – Modern Healthcare Management Platform

![MediAssist](https://mediassistdeb.netlify.app/)
<img width="1869" height="927" alt="image" src="https://github.com/user-attachments/assets/0d6c59fa-1d57-48f1-a3dd-3b115389b3fd" />

## Overview

MediAssist is a fully modernized healthcare management platform built with **React** and **TypeScript**, designed to provide seamless medical workflows for both **Patients** and **Doctors**.  
It features a professional UI, smooth animations, dual-role authentication, and production-ready architecture.

## 🚀 Features

- **✨ Modern Design System**
  - Responsive layout with glass-morphism and gradient backgrounds
  - Smooth animations powered by **Framer Motion**
  - Professional color schemes and clean typography

- **🔐 Dual-role Authentication**
  - Separate workflows for **Patients** and **Doctors**
  - Persistent login with `localStorage`
  - Real-time form validation with error feedback
  - Modal-based authentication UI

- **🏥 Patient Dashboard**
  - Health information submission
  - Medical history tracking
  - Appointment scheduling and management
  - Messaging system
  - Health statistics overview

- **👨‍⚕️ Doctor Dashboard**
  - Patient management interface
  - Appointment tracking and filtering
  - Quick action buttons for workflow efficiency
  - Activity monitoring and patient records access

- **💻 Technical Highlights**
  - Built with **React**, **TypeScript**, **Vite**
  - Component-based modular architecture
  - Responsive UI with **Tailwind CSS**
  - Animation with **Framer Motion**
  - State management with React hooks/context

---

## 🛠️ Tech Stack

- **Frontend:** React, TypeScript, Vite, Tailwind CSS, Framer Motion
- **State Management:** React Context, LocalStorage
- **Routing:** React Router
- **Authentication:** Modal-based Auth Flow (Role-based)

---

## 📂 Project Structure

src/
├── components/
│ ├── Navbar.tsx
│ ├── Hero.tsx
│ ├── Categories.tsx
│ ├── AuthModal.tsx
│ ├── PatientDashboard.tsx
│ └── DoctorDashboard.tsx
├── types/
│ └── User.ts
├── App.tsx
├── main.tsx
└── index.css

---

## 🖥️ Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/cooldeba-21/MediAssist.git
   cd MediAssist
   npm install
   npm run dev 
---

📃 License
This project is licensed under the MIT License.

💬 Feedback & Contributions
Feel free to open issues, submit PRs, or suggest features.
Let’s build a better healthcare platform together!

🔗 Live Demo : 
https://mediassistdeb.netlify.app/
