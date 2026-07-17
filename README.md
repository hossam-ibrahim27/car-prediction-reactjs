# 🚗 Car Price Prediction — Frontend UI Application

![React](https://img.shields.io/badge/React-19.0-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-1.6-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

An interactive, responsive single-page web application built with **React**, **TypeScript**, and **Tailwind CSS**. It provides an intuitive interface for users to enter car specifications and receive real-time price predictions powered by an asynchronous **FastAPI** Machine Learning backend.

---

## 🔗 Live Services & Links

* 🌐 **Frontend Live App:** [https://car-prediction-reactjs.vercel.app](https://car-prediction-reactjs.vercel.app/)
* ⚙️ **Connected Backend API Docs:** [Swagger Documentation](https://car-prediction-backend-production.up.railway.app/docs)
* 📦 **Full System Repository:** [Car Prediction Full Project](https://github.com/hossam-ibrahim27/car-prediction-full-project)

---

## 📁 Repository Structure

```text
predict-frontend/
├── 📁 public/              # Static assets & icons
├── 📁 src/
│   ├── 📁 components/      # Reusable UI components & form inputs
│   ├── 📁 services/        # Axios API client & endpoints setup
│   ├── 📁 types/           # TypeScript interfaces & type definitions
│   ├── App.tsx             # Main layout & form application state
│   └── main.tsx            # Application entry point
├── eslint.config.js        # Linting rules & code quality configuration
├── index.html              # HTML template
├── package.json            # Dependencies & scripts
├── tsconfig.json           # TypeScript configuration
└── vite.config.ts          # Vite build tools configuration

```

## 🛠️ Tech Stack & Architecture

```text
 ┌──────────────────────┐        ┌───────────────────────┐        ┌──────────────────────┐
 │   User Input Form    │ ────>  │  Axios Service Layer  │ ────>  │ FastAPI ML Backend   │
 │ (React 18 + Tailwind)│        │(Type-safe HTTP Client)│        │  (Cloud Prediction)  │
 └──────────────────────┘        └───────────────────────┘        └──────────────────────┘
 ```

### 1. User Interface & Styling
* **React 19:** Functional components with custom hooks for modular UI development and modern rendering features.
* **Tailwind CSS:** Modern, utility-first CSS framework for responsive layout design.

### 2. Type Safety & Tooling
* **TypeScript:** Strict type checks for form states, input validation, and API payload schemas.
* **Vite:** Next-generation frontend build tool providing lightning-fast Hot Module Replacement (HMR).

### 3. API Integration & State Management
* **Axios:** Handles real-time asynchronous HTTP requests to the FastAPI prediction endpoint.
* **Form State:** Manages vehicle parameters (Brand, Model, Year, Mileage, Fuel Type, etc.) before payload submission.

---


## 🔒 License & Intellectual Property

Copyright (c) 2026 Hossam Ibrahim. All Rights Reserved.

This repository and its source code are published for showcase, code review, and portfolio evaluation purposes only. No part of this software may be copied, modified, distributed, or used for commercial purposes without prior written permission from the owner.

 
