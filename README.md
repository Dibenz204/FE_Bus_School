# Smart School Bus Management System — Frontend

> React-based web client for a real-time school bus tracking and management platform.

---

## Overview

A responsive web application serving **3 user roles** — Admin, Parent, and Driver — with real-time bus tracking via interactive map, student attendance visibility, and route/bus stop management.

**Live Demo:** [Do Railway đã hết hạn, nên việc kết nối với Backend đã không còn được] 
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

**Giao diện đặc trưng**
<img width="1420" height="812" alt="image" src="https://github.com/user-attachments/assets/9415389a-c408-4472-ab91-64336b468b97" />

**Giao diện quản trị viên**
(Thống kê)
<img width="1437" height="825" alt="image" src="https://github.com/user-attachments/assets/7e2e53b8-bd6f-48bd-8b7c-1ccdeeeedcfd" />

(Chi tiết số học sinh trên từng tuyến đường - đã đăng kí sử dụng dịch vụ)
<img width="1442" height="825" alt="image" src="https://github.com/user-attachments/assets/12a1a065-2d6f-40b1-b901-47bb47b51066" />

(Tạo điểm trạm, và tuyến đường trực tuyến trên map)
<img width="1534" height="873" alt="image" src="https://github.com/user-attachments/assets/ccbe8d85-1e2c-44da-b985-646fedf67045" />

(Quản lý lịch trình và xe bus)
<img width="1643" height="933" alt="image" src="https://github.com/user-attachments/assets/ccc98d63-961b-4510-9385-127a62973145" />

(Giám sát trực tiếp thông qua Socket.io - GPS)
<img width="1643" height="942" alt="image" src="https://github.com/user-attachments/assets/b9cd2bf4-737c-4d3c-a780-29dffaa45b55" />

**Giao diện phụ huynh theo dõi học sinh của mình**
<img width="1643" height="936" alt="image" src="https://github.com/user-attachments/assets/0ba854f7-eb57-4734-bb9e-715b04a93e43" />

**Giao diện tài xế**
(Nhận lịch trình)
<img width="1652" height="937" alt="image" src="https://github.com/user-attachments/assets/f0696c29-0d01-49ba-9de3-33c230ff7766" />

(Quản lý học sinh trên xe bằng QR - thẻ học sinh)
<img width="1661" height="939" alt="image" src="https://github.com/user-attachments/assets/0b1a42e1-9c6c-48b1-a210-7f005f66eabc" />

(Lịch trình được cập nhật khi tới giờ)
<img width="1658" height="953" alt="image" src="https://github.com/user-attachments/assets/122b0c83-b11e-4813-9434-e31298538c2b" />

---


## Team

| Role | Member |
|---|---|
| Backend & Frontend Leader | Nguyễn Đình Phong |
| Frontend | Trương Thị Ngọc Nhi |

---

## License

This project is for academic and portfolio purposes.
