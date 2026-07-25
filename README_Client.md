# 🛡️ KSP Sentinel X – AI Investigation Operating System
> **Pragya Verse KSP Hackathon Flagship Edition**  
> *Next-Generation Crime Intelligence, Spatial GIS Analytics, Cross-Jurisdictional Knowledge Graph & Explainable AI Copilot for Karnataka State Police.*

---

## 📋 Executive Overview

**KSP Sentinel X** is an enterprise-grade AI-powered Crime Investigation Operating System engineered for the **Karnataka State Police (KSP)**. Built to modernize law enforcement telemetry, Sentinel X unifies FIR case management, spatial GIS crime mapping, graph neural network connection analysis, forensic evidence chain-of-custody tracking, and court-ready chargesheet generation.

---

## 🔥 Key Platform Capabilities

### 1. 🧠 Explainable AI (XAI) Copilot & File Generation Suite
- **Context-Aware LLM Engine**: Integrated with **OpenAI (`gpt-4o` / `gpt-3.5-turbo`)** and **Google Gemini**, pre-loaded with the complete active KSP case database.
- **Statutory Deadline Auditor**: Automatically audits active cases against **60-day and 90-day statutory Cr.P.C. Form 173 filing deadlines**.
- **Instant PDF Dossier Generator**: 1-click export of official KSP PDF intelligence reports complete with XAI reasoning traces, confidence ratings, and cryptographic signatures.
- **Permanent Chat Vault**: Officer chat history is saved permanently in `localStorage` until explicitly cleared.

### 2. 🗺️ Karnataka GIS Spatial Crime Map & Hotspot Visualizer
- **Multi-District Telemetry**: Interactive Leaflet maps rendering high-risk crime hotspots across **Bengaluru Urban, Mysuru, Mangaluru, Hubballi, and Belagavi**.
- **Real-Time Hotspot Synthesis**: Filters hotspots by crime type, district, and risk score directly from active FIR records.

### 3. 🕸️ Cross-Jurisdictional NetworkX Knowledge Graph
- **Graph Neural Network Visualizer**: Interactive canvas connecting suspect identities, bank accounts, SSH gateway IPs, cell tower CDR records, and FIR dossiers.
- **Node Highlight & Deep Linking**: Click any node to instantly jump to its corresponding investigation workspace or generate a targeted intelligence report.

### 4. 🔐 7 Role-Based Access Control (RBAC) Dashboards
Separate, tailored operational command desks strictly isolated by role-based permissions:
1. **System Administrator Desk**: Employee creation, station management, security matrices, database snapshots, and master password resets.
2. **Investigating Officer Desk (DySP Vikramaditya Hegde)**: FIR registry, digital evidence vault, timeline reconstruction, and chargesheet drafting.
3. **Supervisory Command Desk (DySP / SHO)**: FIR approval/rejection queue, chargesheet clearance, IO reassignment, and SLA tracking.
4. **Forensic Officer Desk (Dr. Srinivas)**: Evidence intake, digital/audio/video media attachments, tamper-seal verification, and FSL certificate generation.
5. **Crime Analyst Desk (Ananya Sharma)**: Spatial hotspot trends, ANPR vehicle tracking, and 30-day predictive crime forecasting.
6. **State Headquarters Chief / Commissioner Desk (DGP Dr. R. V. Deshmukh)**: Statewide crime overview, district performance matrix, and critical case alerts.
7. **Policy Maker Desk**: Statewide crime trends, resource allocation metrics, and policy recommendation matrices.

### 5. 🔑 Master Password Storage & Real-Time Sync
- **Persistent Password Vault**: Changes made to officer passwords immediately update the master vault (`ksp_officer_passwords`) in local database memory.
- **Eye Icon Toggle**: Reusable password visibility toggle across login screens and reset modals.
- **Dynamic Reset Modal Sync**: Opening the password reset modal automatically loads the officer's currently active password.

### 6. 🌐 Multi-Language Support (Kannada ಕನ್ನಡ & English)
- Header language toggle instantly translates navigation links, action buttons, FIR form fields, role titles, and voice assistant commands between **English** and **Kannada (ಕನ್ನಡ)**.

### 7. 🎨 Floating Corner Multi-Theme Color Switcher
- Floating corner widget in the bottom-right (`fixed bottom-4 right-4 z-50`) offering instant 1-click theme switching:
  - 🌙 **Dark Slate (Default Enterprise Police Theme)**
  - ☀️ **Light Mode (Clean High-Contrast White Theme)**
  - 🎨 **Midnight Blue**
  - 🟢 **Cyber Emerald**

---

## 👤 Official Officer & Credential Reference Directory

Use the following official credentials to log into any role dashboard:

| Role Title | Official Officer Name | Employee ID | Default Passcode | Dashboard Route |
| :--- | :--- | :--- | :--- | :--- |
| **System Administrator** | Admin Operations | `EMP-1001` | `admin123` | `/admin/dashboard` |
| **Investigating Officer** | DySP Vikramaditya Hegde | `EMP-1002` | `io123` | `/officer/dashboard` |
| **Crime Analyst** | Ananya Sharma | `EMP-1003` | `analyst123` | `/analyst/dashboard` |
| **Supervisor / DySP** | DySP K. V. Rao | `EMP-1004` | `dysp123` | `/supervisor/dashboard` |
| **Forensic Officer** | Dr. Srinivas | `EMP-1005` | `forensic123` | `/forensics/dashboard` |
| **DGP / State Commissioner** | Dr. R. V. Deshmukh | `EMP-1006` | `dgp123` | `/commissioner/dashboard` |
| **Policy Maker** | Principal Sec Home Dept | `EMP-1007` | `policy123` | `/policy/dashboard` |

---

## 🛠️ Technology Stack

- **Frontend Core**: React 18, TypeScript, Vite 5
- **Styling**: Vanilla CSS, TailwindCSS, CSS Variables (Multi-Theme System)
- **State Management**: Zustand, React Context API
- **Charts & Maps**: Recharts, Leaflet, React-Leaflet
- **Icons**: Lucide React
- **AI Integration**: OpenAI API (`gpt-4o` / `gpt-3.5-turbo`), Google Gemini API

---

## 🚀 Quickstart & Local Setup Guide

### 1. Prerequisites
Ensure you have **Node.js (v18.0 or higher)** installed on your machine.

### 2. Installation
Navigate to the `client` directory and install project dependencies:
```bash
cd client
npm install
```

### 3. Launch Development Server
Start the Vite local development server:
```bash
npm run dev
```
Open your browser and navigate to: **`http://localhost:5173`**

### 4. Build for Production
To test or deploy the production bundle:
```bash
npm run build
```
