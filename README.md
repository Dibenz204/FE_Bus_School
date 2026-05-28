# Smart School Bus Management System — Frontend

> React-based web client for a real-time school bus tracking and management platform.

---

## Overview

A responsive web application serving **3 user roles** — Admin, Parent, and Driver — with real-time bus tracking via interactive map, student attendance visibility, and route/bus stop management.

**Live Demo:** [Vercel deployment link — điền vào đây]  
**Backend Repo:** [https://github.com/Dibenz204/BE_bus_school](https://github.com/Dibenz204/BE_bus_school)

---

## Key Features

- **Role-based UI** — Separate dashboards and navigation for Admin, Parent, Driver
- **Live Bus Tracking** — Interactive map showing real-time bus location via Socket.IO
- **Attendance Dashboard** — Parents can view daily student attendance records
- **Route & Stop Management** — Admin UI for creating and editing routes and bus stops
- **Driver Interface** — Driver-specific views for schedule and GPS emission

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React |
| Real-time | Socket.IO Client |
| Map | [Leaflet.js / Google Maps API] |
| HTTP Client | Axios |
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
# Điền REACT_APP_API_URL, REACT_APP_SOCKET_URL vào .env

# Start development server
npm start
```

---

## Screenshots



---


## Team

| Role | Member |
|---|---|
| Frontend Lead & Team Leader | Nguyễn Đình Phong |

---

## License

This project is for academic and portfolio purposes.