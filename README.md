# ⚖️ Nyayasarthi (न्यायसारथी)
### *Next-Generation Unified Digital Justice & Legal Intelligence Infrastructure*

---

[![React](https://img.shields.io/badge/Frontend-React%2018%20%7C%20TypeScript%20%7C%20Vite-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind%20CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js%20%7C%20Express-339933?logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB%20%7C%20Mongoose-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Socket.io](https://img.shields.io/badge/Realtime-Socket.io-010101?logo=socket.io&logoColor=white)](https://socket.io/)
[![Google Gemini](https://img.shields.io/badge/AI%20Engine-Gemini%202.5%20Flash%20Lite-4285F4?logo=google&logoColor=white)](https://ai.google.dev/)

---

## 📌 Executive Overview

**Nyayasarthi** is an end-to-end digital justice ecosystem designed to bridge the gap between citizens, law enforcement, legal professionals, and the judiciary. Built on modern web architecture and powered by Google Gemini AI, Nyayasarthi digitizes case lifecycles, automates compliance with the **Bharatiya Nyaya Sanhita (BNS)** and **Bharatiya Nagarik Suraksha Sanhita (BNSS)**, secures digital evidence chains of custody, and provides transparent legal access to all stakeholders.

---

## 🏛️ The 4-Pillar Ecosystem

Nyayasarthi delivers dedicated, role-tailored dashboards and operational workflows:

```
                      ┌─────────────────────────────────────────┐
                      │          NYAYASARTHI CORE HUB           │
                      └────────────────────┬────────────────────┘
                                           │
         ┌──────────────────┬──────────────┴─────┬──────────────────┐
         │                  │                    │                  │
         ▼                  ▼                    ▼                  ▼
  ┌──────────────┐   ┌──────────────┐     ┌──────────────┐   ┌──────────────┐
  │   CITIZEN    │   │    POLICE    │     │    LAWYER    │   │    JUDGE     │
  │  DASHBOARD   │   │  DASHBOARD   │     │  DASHBOARD   │   │  DASHBOARD   │
  ├──────────────┤   ├──────────────┤     ├──────────────┤   ├──────────────┤
  │• E-File Case │   │• Case Diary  │     │• Case Claim  │     │• Case Review │
  │• AI Triage   │   │• Evid. Vault │     │• Client Chat │     │• Assign Role │
  │• SOS Patrol  │   │• ChargeSheet │     │• Court Filing│     │• Fast Verdict│
  │• Legal Notice│   │• Live Patrol │     │• PDF Notice  │     │• Analytics   │
  └──────────────┘   └──────────────┘     └──────────────┘   └──────────────┘
```

### 1. 👤 Citizens
- **Smart E-Filing**: Interactive case registration with automatic categorization (Criminal, Civil, Cyber, Corporate, Family).
- **AI Legal Assistant**: Multilingual AI conversational agent providing incident assessment, relevant BNS section identification, evidence checklists, and formal complaint drafting.
- **Visual Legal Triage & "Know Your Rights"**: Intuitive visual step-by-step guides and statutory awareness tools.
- **SOS Emergency Beacon & Live Patrol Tracker**: Real-time GPS emergency broadcasting to law enforcement with interactive Leaflet map tracking.
- **Legal Notice Generator**: Instant PDF generation and tracking for formal legal notices.

### 2. 🚓 Law Enforcement (Police)
- **Digital Case Diary & Investigation Notes**: Timestamped chronological logging of investigation progress.
- **Secure Evidence Vault**: Digital asset ingestion with SHA-256 cryptographic hashing to ensure chain of custody integrity and prevent tampering.
- **Charge Sheet Filing**: Streamlined submission to Court Registry aligned with BNSS statutory 60/90-day time limits.
- **Emergency Response & Dispatch**: Real-time live map tracking of citizen SOS alerts.

### 3. ⚖️ Legal Advocates (Lawyers)
- **Open Case Marketplace & Claims**: Discover and claim pending cases requiring defense counsel or legal representation.
- **Secure Consultation Channels**: Real-time end-to-end Socket.io chat rooms with clients.
- **Court Submission**: Formal case dossier verification and filing to Court Registry with statutory deadline calculation.
- **Hearing Scheduler**: Schedule, manage, and notify parties of upcoming court hearings.

### 4. 👨‍⚖️ Judiciary (Judges)
- **Centralized Case Management**: Comprehensive judicial review of case details, evidence verification status, and hearing logs.
- **Professional Assignment Engine**: Allocate investigating officers and defense counsel to cases.
- **Statutory Bottleneck & Compliance Audit**: Automated alerts for BNSS statutory deadlines.
- **Verdict & Closure Issuance**: Formal digital verdict delivery with automated real-time alerts dispatched to all associated parties.
- **Judicial Analytics**: Real-time case resolution metrics, clearance rates, and pendency analytics via interactive charts.

---

## 🚀 Key Features & Innovations

- 🧠 **Gemini-Powered Legal Intelligence Node**: Maps natural language complaint descriptions directly to BNS sections (e.g., *Cheating → BNS 318*, *Theft → BNS 303*), extracts key entities, and generates formal legal complaints.
- 🔒 **Cryptographic Chain of Custody**: Every piece of uploaded evidence generates a SHA-256 checksum and metadata signature, preventing post-upload alterations.
- ⏱️ **Automated Deadline & Statutory Tracking**: Scheduled background cron jobs continuously audit case aging against BNSS statutory limits (e.g., 60-day criminal, 90-day civil, 45-day cyber) and send automated warnings 3 days prior to expiration.
- 💬 **Real-time Bi-directional Communication**: WebSocket-powered live chat rooms with typing indicators and instantaneous broadcast notifications.
- 🗺️ **Geospatial Emergency Response**: Live Leaflet-based interactive map tracking for patrol and emergency response coordination.
- 📄 **Dynamic Legal PDF Engine**: Client-side and server-side PDF generation (`jsPDF`) for legal notices, court summons, and complaints.
- 🌓 **Adaptive Interface & Dark/Cyber Theme**: High-contrast, glassmorphism-enhanced, responsive UI supporting dynamic theme switching.

---

## 🛠️ Technology Stack

### **Frontend**
| Technology | Description |
|---|---|
| **React 18** | High-performance declarative component architecture |
| **TypeScript** | Type-safe development across all modules and APIs |
| **Vite** | Fast HMR build tool and dev server |
| **Tailwind CSS** | Utility-first responsive styling and custom animations |
| **React Router v6** | Client-side routing with role-based `ProtectedRoute` guards |
| **Lucide React** | Clean, modern iconography |
| **Recharts** | Interactive data visualization and case analytics |
| **Leaflet & React-Leaflet** | Interactive geospatial maps and patrol tracking |
| **jsPDF** | Dynamic legal notice and document PDF generation |
| **Socket.io Client** | Real-time WebSocket connection for live messaging and alerts |

### **Backend**
| Technology | Description |
|---|---|
| **Node.js & Express.js** | Modular RESTful API and WebSocket server |
| **MongoDB & Mongoose** | NoSQL document database for schema-driven case lifecycle data |
| **Socket.io** | Event-driven WebSocket server for rooms, chats, and emergency feeds |
| **Google Gemini API** | Multimodal LLM integration for legal analysis and complaint drafting |
| **Node-Cron** | Automated daily background jobs for deadline auditing |
| **JWT & Bcrypt.js** | Stateless token authentication and password hashing |
| **Multer** | Multipart form data handling for document ingestion |

---

## 📂 Project Architecture

```
NayaySarthi/
├── backend/
│   ├── index.js                      # Express & Socket.io server entry point
│   ├── middleware/
│   │   └── auth.js                   # JWT verification & RBAC checkRole middleware
│   ├── models/
│   │   ├── Analytics.js              # System-wide metrics model
│   │   ├── Case.js                   # Comprehensive case, evidence & hearing schema
│   │   ├── Chat.js                   # Message history schema
│   │   ├── LegalNotice.js            # Legal notices schema
│   │   ├── Notification.js           # Real-time notification schema
│   │   └── User.js                   # User identity & role management schema
│   ├── routes/
│   │   ├── analytics.js              # Case statistics & aggregate analytics
│   │   ├── auth.js                   # Registration, login, profile management
│   │   ├── cases.js                  # Full CRUD, claim, assign, evidence, verdict routes
│   │   ├── chat.js                   # Room-based messaging endpoints
│   │   ├── chatbot.js                # Google Gemini AI legal intelligence integration
│   │   ├── legalNotice.js            # Notice drafting, issuance & listing
│   │   ├── notifications.js          # In-app notifications
│   │   └── users.js                  # User queries and professional listings
│   └── utils/
│       └── notificationSystem.js     # Multi-party notification dispatchers
│
├── frontend/
│   ├── index.html                    # Single-page application template
│   ├── src/
│   │   ├── App.tsx                   # Master routing & provider setup
│   │   ├── main.tsx                  # React entry point
│   │   ├── context/
│   │   │   ├── AuthContext.tsx       # Auth state, token & user session management
│   │   │   └── ThemeContext.tsx      # Theme context (dark/light/high-contrast)
│   │   ├── components/
│   │   │   ├── AssignModal.tsx       # Judicial advocate/officer assignment modal
│   │   │   ├── Chatbot.tsx           # Floating AI legal counselor drawer
│   │   │   ├── KnowYourRights.tsx    # Citizen rights legal reference cards
│   │   │   ├── Layout.tsx            # Main shell with sidebar, navbar, notifications
│   │   │   ├── LivePatrolTracker.tsx # Leaflet GPS emergency patrol radar
│   │   │   ├── Notifications.tsx     # Notification dropdown & alert listener
│   │   │   ├── ProfileModel.tsx      # User profile edit & credentials modal
│   │   │   ├── ProtectedRoute.tsx    # RBAC route guard
│   │   │   ├── VisualTriage.tsx      # Step-by-step interactive legal triage
│   │   │   └── dashboards/
│   │   │       ├── CitizenDashboard.tsx
│   │   │       ├── PoliceDashboard.tsx
│   │   │       ├── LawyerDashboard.tsx
│   │   │       └── JudgeDashboard.tsx
│   │   ├── pages/
│   │   │   ├── Landing.tsx           # High-impact landing page
│   │   │   ├── Login.tsx / Register.tsx
│   │   │   ├── Dashboard.tsx         # Dynamic dashboard switcher by role
│   │   │   ├── FileCase.tsx          # Multi-step case filing wizard
│   │   │   ├── Cases.tsx             # Case listing, filters, search
│   │   │   ├── CaseDetails.tsx       # Timeline, evidence vault, hearings, actions
│   │   │   ├── LegalNotice.tsx       # Legal notice generator & tracking
│   │   │   ├── Chat.tsx              # Encrypted real-time messaging interface
│   │   │   ├── Analytics.tsx         # Graphical stats and judicial insights
│   │   │   ├── FAQ.tsx & Contact.tsx
│   │   └── utils/
│   │       └── generatePDF.ts        # jsPDF utility for court & notice export
│   └── tailwind.config.js
└── improvisation.md                  # Roadmap & engineering enhancements
```

---

## ⚡ Getting Started

### Prerequisites
- **Node.js**: `v18.x` or higher
- **npm** or **yarn**
- **MongoDB**: Local instance running or MongoDB Atlas connection URI
- **Google Gemini API Key**: Obtain from [Google AI Studio](https://aistudio.google.com/)

---

### 1. Backend Setup

1. Open a terminal and navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the `backend/` root:
   ```env
   PORT=5000
   MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/nyayasarthi?retryWrites=true&w=majority
   JWT_SECRET=your_super_secure_jwt_secret_key_here
   GEMINI_API_KEY=your_google_gemini_api_key_here
   FRONTEND_URL=http://localhost:5173
   ```

4. Start the backend development server:
   ```bash
   npm run dev
   # Server runs on http://localhost:5000
   ```

---

### 2. Frontend Setup

1. Open a second terminal and navigate to the `frontend` directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. (Optional) Configure environment variables if required in `frontend/.env`:
   ```env
   VITE_API_URL=http://localhost:5000/api
   VITE_SOCKET_URL=http://localhost:5000
   ```

4. Start the Vite development server:
   ```bash
   npm run dev
   # Application opens at http://localhost:5173
   ```

---

## 🔐 Role-Based Access Control (RBAC)

| Role | Access Permissions |
|---|---|
| **Citizen** | Create cases, generate legal notices, upload personal evidence, access AI triage, trigger SOS emergency alerts, chat with assigned lawyer. |
| **Police** | Claim unassigned cases, manage digital case diary, upload & verify evidence with cryptographic hashes, file chargesheets moving cases to trial, receive live SOS beacons. |
| **Lawyer** | Claim pending cases, consult clients via secure chat, verify case documents, submit cases to court registry, schedule hearings, generate legal notices. |
| **Judge** | Review complete case dossiers, assign police investigators and defense attorneys, issue final verdicts/closures, review clearance analytics. |

---

## 📡 API Reference Overview

### **Auth (`/api/auth`)**
- `POST /register` — Register a new user with specific role.
- `POST /login` — Authenticate and receive JWT token.
- `GET /me` — Get current user profile and session info.

### **Cases (`/api/cases`)**
- `GET /` — Fetch cases accessible to the authenticated role.
- `POST /` — File a new case complaint.
- `GET /:id` — Retrieve detailed case timeline, evidence, and hearings.
- `PUT /:id/assign` — Assign police officer and defense lawyer *(Judges only)*.
- `PUT /:caseId/claim` / `PUT /:caseId/claim-lawyer` — Claim case *(Police/Lawyers)*.
- `POST /:id/evidence` — Ingest evidence with hash and metadata.
- `POST /:id/hearings` — Schedule court hearing.
- `PUT /:id/submit-to-court` — File case to court registry *(Lawyers)*.
- `PUT /:id/charge-sheet` — Submit police chargesheet to trial *(Police)*.
- `PUT /:id/verdict` — Issue judicial judgment and close case *(Judges)*.

### **AI Chatbot (`/api/chatbot`)**
- `POST /ask` — AI legal intelligence query with context-aware role directives.

### **Legal Notices (`/api/legal-notice`)**
- `POST /file` — Create and issue official legal notice.
- `GET /` — List notices issued by the user.
- `GET /citizen/matching` / `GET /lawyer/for-assigned-cases` — List relevant notices.

### **Analytics (`/api/analytics`)**
- `GET /dashboard` — High-level case distribution, resolution times, and pending metrics.

---

## 🗺️ Roadmap & Future Enhancements

- [ ] **Decentralized Evidence Ledger**: Integrate immutable ledger / blockchain hashing for forensic chain of custody.
- [ ] **DigiLocker & Aadhaar eSign**: Government identity verification for verified case filing.
- [ ] **PWA & Offline-First SOS**: Progressive web application with SMS-fallback for zero-connectivity emergency beacons.
- [ ] **S3 / Cloud Storage Migration**: Automated multi-part document streaming via AWS S3 / Cloud Storage.
- [ ] **Geo-Sharded WebSockets**: District and precinct-level room partitioning for large-scale police dispatch.

---

## 👥 Contributors & License

Developed with ❤️ for legal transparency and digital empowerment.  
Licensed under the [ISC License](LICENSE).
