# Smart School Bus Management System — Frontend

> React-based web client for a real-time school bus tracking and management platform.

---

## Overview

A responsive web application serving **3 user roles** — Admin, Parent, and Driver — with real-time bus tracking via interactive map, student attendance visibility, and route/bus stop management.

**Live Demo:** https://bus-smart-school.vercel.app/

| Role | Email | Password |
|---|---|---|
| Admin | abc@gmail.com | 123456 |
| Driver | xeom@gmail.com | 123456 |
| Parent | lala@gmail.com | 123456 |

**Backend Repo:** [https://github.com/Dibenz204/BE_bus_school](https://github.com/Dibenz204/BE_bus_school)

---

## Key Features

- **Role-based UI** — Separate dashboards and navigation for Admin, Parent, and Driver
- **Live Bus Tracking** — Interactive map showing real-time bus location via Socket.IO
- **Attendance Dashboard** — Parents can view daily student attendance records
- **Route & Stop Management** — Admin UI for creating and editing routes and bus stops
- **Driver Interface** — Driver-specific views for schedule and GPS emission
- **QR Code Check-in** — Drivers manage student boarding via QR code scanning
- **i18n Support** — Multi-language interface via i18next

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React + Vite |
| Real-time | Socket.IO Client |
| Map | Leaflet.js |
| HTTP Client | Axios |
| Styling | Tailwind CSS |
| i18n | i18next |
| Deployment | Vercel |

---

## Project Structure

```
FE_Bus_School/
├── public/
├── src/
│   ├── assets/          # Static assets (images, icons)
│   ├── components/      # Reusable UI components
│   ├── config/          # App configuration constants
│   ├── lib/             # Third-party lib wrappers / utilities
│   ├── pages/           # Page-level components by role
│   ├── routes/          # React Router route definitions
│   ├── services/        # API call functions (axios)
│   ├── styles/          # Global and module CSS
│   └── translate/       # i18n translation files
├── App.css
├── App.jsx              # Root component
├── i18n.js              # i18n initialization
├── main.jsx             # App entry point
├── axios.js             # Axios instance & interceptors
├── config.js            # Global config (API base URL, etc.)
├── index.html
├── tailwind.config.js   # Tailwind CSS config
├── vite.config.js       # Vite production config
├── vite.config.dev.js   # Vite development config
├── vercel.json          # Vercel deployment config
├── .env.development
├── .env.production
└── .gitignore
```

---

## Getting Started

### Prerequisites

- Node.js >= 18.x

### Installation

```bash
# Clone repo
git clone https://github.com/Dibenz204/FE_Bus_School.git
cd FE_Bus_School

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env
# Fill in VITE_API_URL and VITE_SOCKET_URL in .env

# Start development server
npm run dev
```

---

## Screenshots

**Landing page**
<img width="1420" height="812" alt="image" src="https://github.com/user-attachments/assets/9415389a-c408-4472-ab91-64336b468b97" />

**Admin Dashboard**

Statistics overview
<img width="1437" height="825" alt="image" src="https://github.com/user-attachments/assets/7e2e53b8-bd6f-48bd-8b7c-1ccdeeeedcfd" />

Student count per route — registered service users
<img width="1442" height="825" alt="image" src="https://github.com/user-attachments/assets/12a1a065-2d6f-40b1-b901-47bb47b51066" />

Create bus stops and routes directly on interactive map
<img width="1534" height="873" alt="image" src="https://github.com/user-attachments/assets/ccbe8d85-1e2c-44da-b985-646fedf67045" />

Schedule and bus fleet management
<img width="1643" height="933" alt="image" src="https://github.com/user-attachments/assets/ccc98d63-961b-4510-9385-127a62973145" />

Live GPS monitoring via Socket.IO
<img width="1643" height="942" alt="image" src="https://github.com/user-attachments/assets/b9cd2bf4-737c-4d3c-a780-29dffaa45b55" />

**Parent Dashboard — Student tracking**
<img width="1643" height="936" alt="image" src="https://github.com/user-attachments/assets/0ba854f7-eb57-4734-bb9e-715b04a93e43" />

**Driver Dashboard**

Schedule overview
<img width="1652" height="937" alt="image" src="https://github.com/user-attachments/assets/f0696c29-0d01-49ba-9de3-33c230ff7766" />

Student boarding management via QR code scanning
<img width="1661" height="939" alt="image" src="https://github.com/user-attachments/assets/0b1a42e1-9c6c-48b1-a210-7f005f66eabc" />

Schedule auto-updates when departure time is reached
<img width="1658" height="953" alt="image" src="https://github.com/user-attachments/assets/122b0c83-b11e-4813-9434-e31298538c2b" />

---

## Team

| Role | Member |
|---|---|
| Backend Lead, Database Architect & Team Leader | Nguyễn Đình Phong |
| Frontend Developer | Trương Thị Ngọc Nhi |

---