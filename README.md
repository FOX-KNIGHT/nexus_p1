<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0a0a1f,40:0d0d2b,80:111133,100:0a0a1f&height=260&section=header&text=NEXUS&fontSize=110&fontColor=f0c040&animation=fadeIn&fontAlignY=50&desc=Smart%20Campus%20%26%20Library%20Management%20System&descSize=18&descAlignY=72&descColor=f5d980&stroke=c8960a&strokeWidth=1" width="100%" />

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Cinzel&weight=700&size=17&pause=1000&color=F0C040&center=true&vCenter=true&width=750&lines=Unified+campus+intelligence+for+students%2C+librarians+%26+admins;Multi-role+%7C+Cross-platform+%7C+AI-assisted;React+%7C+Node.js+%7C+Capacitor+%7C+Tailwind+CSS;One+system.+Every+role.+Every+device." />
</p>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-f0c040?style=for-the-badge&labelColor=0a0a1f" />
  &nbsp;
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Android%20%7C%20iOS-f0c040?style=for-the-badge&labelColor=0a0a1f" />
  &nbsp;
  <img src="https://img.shields.io/badge/License-Proprietary-f0c040?style=for-the-badge&labelColor=0a0a1f" />
  &nbsp;
  <img src="https://img.shields.io/badge/Made%20by-FOX--KNIGHT-f0c040?style=for-the-badge&labelColor=0a0a1f" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react&logoColor=white&labelColor=0a0a1f" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white&labelColor=0a0a1f" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white&labelColor=0a0a1f" />
  <img src="https://img.shields.io/badge/Node.js-18+-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white&labelColor=0a0a1f" />
  <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white&labelColor=0a0a1f" />
</p>

</div>

---

## What is Nexus?

Nexus is not just a library portal. It is a **unified intelligence layer for the entire campus**.

Traditional campus systems fragment students, librarians, and administrators into separate, disconnected tools. Nexus collapses that into a single platform — role-aware, cross-platform, and AI-assisted — so every actor in the institution operates from the same source of truth.

Write once. Deploy everywhere — **web, Android, and iOS** natively via Capacitor.

```
Student / Librarian / Admin
         │
         ▼
  React + Vite SPA  ──▶  Node.js REST API  ──▶  Database
         │
         ▼
  Capacitor Core
  ├── Android Native Build
  └── iOS Native Build
```

---

## Core Features

<table>
<tr>
<td width="50%">

### 🔐 Multi-Role Architecture
- Isolated dashboards for **Students**, **Librarians**, and **Admins**
- Protected routes — role verification at every layer
- Secure login via `AuthContext` global state
- No role can access another's environment

</td>
<td width="50%">

### 📱 True Cross-Platform
- React web app as the single source codebase
- **Capacitor** bridges web → native Android & iOS
- One build system, three deployment targets
- Mobile-native feel with web development speed

</td>
</tr>
<tr>
<td width="50%">

### 🤖 AI Assistant Integration
- Interactive `Chatbot` component built into the student view
- Instant answers for catalog queries & support
- Navigation assistance for first-time users
- Extensible to LLM backends

</td>
<td width="50%">

### 📊 Advanced Analytics
- Real-time telemetry across all roles
- Custom `BarChart`, `LineChart`, and `DonutChart` components
- Book circulation tracking
- Student metrics & transaction history dashboards

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### ✨ Hyper-Modern UI/UX
- Animated background layers: `NeuralBackground`, `SpotlightBackground`, `FlowBackground`
- `EnhancedStatCard` for premium metric displays
- Dark-first, futuristic aesthetic — built with Tailwind CSS
- Motion-rich UI without sacrificing performance

</td>
</tr>
</table>

---

## System Architecture

```mermaid
graph TD
    A[👨‍🎓 Student] --> B
    H[📚 Librarian] --> B
    I[🛡️ Admin] --> B
    B[⚡ React + Vite Frontend\nSPA — Web & Mobile Base] -- REST API --> C{🖧 Node.js Backend}
    C --> D[(🗄️ Database Engine)]
    B --> E[📲 Capacitor Core]
    E --> F[🤖 Android Native Build]
    E --> G[🍎 iOS Native Build]

    style A fill:#0d0d2b,stroke:#f0c040,color:#fff
    style H fill:#0d0d2b,stroke:#f0c040,color:#fff
    style I fill:#0d0d2b,stroke:#f0c040,color:#fff
    style B fill:#0d0d2b,stroke:#f0c040,color:#fff
    style C fill:#0d0d2b,stroke:#f0c040,color:#fff
    style D fill:#0d0d2b,stroke:#c8960a,color:#fff
    style E fill:#0d0d2b,stroke:#f0c040,color:#fff
    style F fill:#0d0d2b,stroke:#c8960a,color:#fff
    style G fill:#0d0d2b,stroke:#c8960a,color:#fff
```

---

## Role Modules

| Role | Dashboard | Capabilities |
|------|-----------|-------------|
| 👨‍🎓 **Student** | `StudentDashboard` | Browse catalog, view borrowed books, AI chatbot |
| 📚 **Librarian** | `LibrarianDashboard` | Manage inventory, approve requests, view circulation |
| 🛡️ **Admin** | `AdminDashboard` | System health, user management, global telemetry |

---

## Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | React 18 · Vite · Tailwind CSS | SPA, routing, UI system |
| **Mobile** | Ionic Capacitor | Native iOS & Android compilation |
| **Backend** | Node.js · Express | REST API, auth, business logic |
| **Auth** | React Context · Protected Routes | Role-based access control |
| **Charts** | Custom components | Bar, Line, Donut telemetry visuals |
| **AI** | Chatbot component | Student query resolution |

---

## Project Structure

```
nexus_p1/
│
├── 📁 Backend/                   # Node.js Server & API
│   ├── index.js                  # Core server entry point
│   ├── routes/                   # API route handlers
│   ├── .env.example              # Environment config template
│   └── package.json
│
└── 📁 Frontend/                  # React SPA (Web + Mobile base)
    ├── 📁 android/               # Capacitor Android Native Project
    ├── 📁 ios/                   # Capacitor iOS Native Project
    ├── 📁 src/
    │   ├── api/                  # Axios interceptors & API calls
    │   ├── components/           # BookCard, Chatbot, animated backgrounds
    │   │   └── charts/           # BarChart, LineChart, DonutChart
    │   ├── context/              # AuthContext — auth & role state
    │   ├── layouts/              # Dashboard layout wrappers
    │   └── pages/                # Admin, Librarian, Student, Login views
    ├── capacitor.config.json     # Mobile build configuration
    ├── tailwind.config.js        # Design system
    └── vite.config.js            # Frontend bundler
```

---

## Getting Started

> **Prerequisites:** Node.js v18+ (v20 recommended) · npm/yarn/pnpm
> **Mobile (optional):** Android Studio for Android · Xcode for iOS

### ⚡ 1. Start the Backend

```bash
cd Backend

npm install

# Copy env template and fill in your DB credentials + secrets
cp .env.example .env

npm start
# → API running on http://localhost:3000
```

### 🖥️ 2. Start the Frontend

Open a new terminal:

```bash
cd Frontend

npm install

npm run dev
# → Web app at http://localhost:5173
```

---

### 📱 Mobile Builds (Capacitor)

```bash
cd Frontend

# Build the web app first
npm run build

# Sync to native projects
npx cap sync

# Open in native IDEs
npx cap open android   # → Android Studio
npx cap open ios       # → Xcode
```

---

## Service Map

| Service | Port | Description |
|---------|------|-------------|
| `frontend` | `:5173` | React web app (Vite dev server) |
| `backend` | `:3000` | Node.js REST API |
| `android` | — | Native build via Android Studio |
| `ios` | — | Native build via Xcode |

---

## Roadmap

- [x] Multi-role protected dashboard architecture
- [x] AI chatbot for student assistance
- [x] Real-time analytics (Bar, Line, Donut charts)
- [x] Capacitor iOS & Android native builds
- [x] Animated UI layer (Neural, Spotlight, Flow backgrounds)
- [ ] Push notifications (mobile)
- [ ] Offline mode with local sync
- [ ] QR code book check-in / check-out
- [ ] Email/SMS overdue alerts
- [ ] Fine management & payment integration

---

## Author

<p align="center">
  <a href="https://github.com/FOX-KNIGHT">
    <img src="https://img.shields.io/badge/GitHub-FOX--KNIGHT-f0c040?style=for-the-badge&logo=github&logoColor=white&labelColor=0a0a1f" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/siddhant-jena-457350389">
    <img src="https://img.shields.io/badge/LinkedIn-Siddhant%20Jena-f0c040?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0a1f" />
  </a>
  &nbsp;
  <a href="mailto:worksiddhant18@gmail.com">
    <img src="https://img.shields.io/badge/Email-worksiddhant18-f0c040?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0a1f" />
  </a>
</p>

---

<div align="center">

> *"One system. Every role. Every device."*

<img src="https://capsule-render.vercel.app/api?type=cylinder&color=0:0a0a1f,50:111133,100:0a0a1f&height=100&section=footer&text=Built%20for%20institutions%20that%20think%20forward.&fontSize=16&fontColor=c8960a&animation=fadeIn" width="100%" />

</div>
