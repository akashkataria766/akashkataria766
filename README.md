<div align="center">

  # Aakash Kataria

  <p align="center">
    <b>Building robust database-first architectures, aerospace intelligence platforms, desktop security utilities, native mobile applications, and intelligent data systems.</b>
  </p>

  <p align="center">
    <a href="https://github.com/akashkataria766">
      <img src="https://img.shields.io/github/followers/akashkataria766?label=Followers&style=flat-square&color=2563EB" alt="Followers" />
    </a>
    <img src="https://img.shields.io/badge/Catalog-Latest_to_Oldest-0EA5E9?style=flat-square" alt="Order" />
    <img src="https://img.shields.io/badge/Architecture-Clean_&_Modular-10B981?style=flat-square" alt="Architecture" />
  </p>

</div>

---

### 🛠️ Core Technologies & Tools

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Aerospace & Web Systems** | Next.js 16 (Turbopack), TypeScript, Tailwind CSS, Motion, Web Audio API |
| **Databases & Governance** | Oracle Database, PL/SQL, Oracle APEX, Database-First Architecture, Triggers & Constraints |
| **Mobile & Desktop** | Android (Kotlin, Jetpack Compose, Media3 / ExoPlayer), C# (.NET, AES-256, Windows Hello) |
| **Backend & Cloud** | Python (Flask, Streamlit), Node.js (Express), Firebase (Auth, Firestore), REST APIs |
| **Security & Analytics** | AES-256 Encryption, PBKDF2, Google Safe Browsing API, Pandas, NumPy, Plotly, pytest |

---

### 📂 Engineering Projects (Latest to Oldest)

#### 1. ✈️ [Indian Air Force — Tactical Aerospace Intelligence & National Tribute](https://indianairforce-sky.vercel.app)
> **High-Performance Defense Intelligence, Aircraft Telemetry Comparator & Permanent Digital Sanctuary**
* **Repository**: [`indianairforce-sky`](https://github.com/akashkataria766/indianairforce-sky) • **Live Platform**: [indianairforce-sky.vercel.app](https://indianairforce-sky.vercel.app)
* **Stack**: Next.js 16, TypeScript, Tailwind CSS, Motion, Web Audio API, Turbopack
* **Current Status**: **Production Live & Deployed** (100% Static Export, sub-40ms edge response)
* **Highlights**:
  * **Tactical Aircraft Comparator**: Side-by-side avionics, radar types (AESA/PESA), combat radius, and stand-off missile payload comparisons.
  * **Air Warrior Aspirant Hub**: 10-tier Commissioned Officer rank hierarchy in descending seniority (5★ Marshal to Flying Officer), commissioning branch pathways (AFCAT, NDA, CDS, NCC, WS), and interactive daily tactical quiz.
  * **Operational Air Commands Matrix**: All 7 IAF Commands mapped with frontline forward airbases (Ambala, Hasimara, Gwalior, Sulur, Leh AFS).
  * **Permanent Amar Jawan Memorial**: Web Audio API-synthesized ceremonial chime and citizen homage counter.
  * **95th IAF Day Mission Timer**: Ticking towards October 8, 2027.

---

#### 2. 📊 [Consumer Transaction Data Analysis](https://github.com/akashkataria766/Consumer-Transaction-Data-Analysis)
> **Automated Financial Transaction Analytics, Anomaly Detection & BI Dashboard**
* **Repository**: [`Consumer-Transaction-Data-Analysis`](https://github.com/akashkataria766/Consumer-Transaction-Data-Analysis)
* **Stack**: Python 3.11, Streamlit, Pandas, NumPy, Plotly, openpyxl, Oracle SQL
* **Current Status**: **Completed & Tested** (Includes test fixtures and deterministic data generator)
* **Highlights**:
  * **Automated Data Hygiene**: Ingestion pipeline validating duplicate IDs, datetime formats, amount thresholds, and status integrity.
  * **Statistical Anomaly Detection**: Interquartile range (IQR) outlier detection surfacing high-value irregular transactions.
  * **Multi-Format Business Exports**: Interactive Plotly charts, static Matplotlib reports, automated three-sheet openpyxl Excel workbooks, and production Oracle SQL reporting queries.

---

#### 3. 🎵 [Sky-Wave](https://github.com/akashkataria766/Sky-Wave)
> **Modern Native Android Music & Audio Streaming Architecture**
* **Repository**: [`Sky-Wave`](https://github.com/akashkataria766/Sky-Wave)
* **Stack**: Android Kotlin, Jetpack Compose, Media3 / ExoPlayer, Room Database, Multi-Module Gradle
* **Current Status**: **Modular Architecture Implemented** (Public repository open to contributors)
* **Highlights**:
  * **Multi-Module Clean Architecture**: Decoupled feature-first Gradle structure with independent domain, UI, database, network, and playback modules (`:core:core-playback`, `:feature:feature-player`, `:feature:feature-library`).
  * **High-Fidelity Audio Playback**: Background audio service with system notification transport controls, playlist state synchronization, and offline cache management.

---

#### 4. 🤖 [Sky-Core](https://github.com/akashkataria766/Sky-Core)
> **Curated Private AI Companion Progressive Web App (PWA)**
* **Repository**: [`Sky-Core`](https://github.com/akashkataria766/Sky-Core)
* **Stack**: React 19, TypeScript, Vite, Zustand, React Router v7, Firebase Firestore & Auth
* **Current Status**: **Task 1 Complete** (Authentication, User Management & Gatekeeping System)
* **Highlights**:
  * **Strict Gatekeeping State Machine**: 4-state user lifecycle verification (`PENDING_APPROVAL`, `APPROVED`, `REJECTED`, `BLOCKED`) controlling application access.
  * **State & Route Guards**: Access control enforced through Zustand state management and React Router v7 with server-side Firestore Security Rules.
  * **Structured Error Taxonomy**: Centralized error tracking architecture (`SS-401`, `SS-696`) with clear feedback mechanisms.

---

#### 5. 🏛️ [Public Grievance Redressal System (PGRS)](https://github.com/akashkataria766/Public-Grievance-Redressal-System)
> **Database-First Municipal Governance & Complaint Lifecycle Management Platform**
* **Repository**: [`Public-Grievance-Redressal-System`](https://github.com/akashkataria766/Public-Grievance-Redressal-System)
* **Stack**: Oracle Database, PL/SQL, Oracle APEX, Triggers & Constraints
* **Current Status**: **Active Development** (Core database engine, governance procedures & operational APEX pages validated)
* **Highlights**:
  * **Database-First Governance**: Enforces business rules, role boundaries, and audit controls directly within Oracle Database and PL/SQL rather than client UI layers.
  * **Deterministic 7-Stage Lifecycle**: Manages complaints through a structured state machine (`SUBMITTED` ➔ `ASSIGNED` ➔ `IN_PROGRESS` ➔ `RESOLVED` ➔ `VERIFICATION_PENDING` ➔ `CLOSED`), with overdue SLA escalation routes.
  * **Automated Background Procedures**: Built-in routines for idempotent SLA breach escalation (`PGRS_AUTO_ESCALATE`), 7-day citizen auto-closure (`PGRS_AUTO_CLOSE_VERIFICATION`), and 5-year data archival (`PGRS_ARCHIVE_OLD_COMPLAINTS`).
  * **Integrity & Immutability**: Protected by database triggers (`TRG_PGRS_DUE_DATE_LOCK`, `TRG_PGRS_NO_UPDATE_CLOSED`, `TRG_PGRS_LOG_IMMUTABLE`).

---

#### 6. 🔒 [Sky Secure Folders](https://github.com/akashkataria766/Sky-Secure-Folders)
> **Windows Desktop Security Utility for File & Folder Protection**
* **Repository**: [`Sky-Secure-Folders`](https://github.com/akashkataria766/Sky-Secure-Folders)
* **Stack**: C#, .NET, Windows Cryptography APIs, Windows Hello API
* **Current Status**: **Completed Utility** (Windows Desktop security application)
* **Highlights**:
  * **Robust File Encryption**: Protects local folders with AES-256 encryption and PBKDF2 high-iteration key derivation.
  * **Biometric Verification**: Optional authentication via Windows Hello for fast, biometric-backed folder access.
  * **Filesystem Safety**: Atomic lock and restore pipelines preventing data corruption during cryptographic operations.

---

#### 7. 🛡️ [Web Security Analyzer](https://github.com/akashkataria766/Web-Security-Analyzer)
> **Heuristic URL Threat Scanner & Google Safe Browsing Intelligence**
* **Repository**: [`Web-Security-Analyzer`](https://github.com/akashkataria766/Web-Security-Analyzer)
* **Stack**: Python, Flask, Google Safe Browsing API, pytest
* **Current Status**: **Completed & Tested** (MIT License, deterministic unit test suite)
* **Highlights**:
  * **Multi-Vector Threat Detection**: Inspects homoglyphs/punycode impersonation (`go0gle.com`), suspicious subdomains, embedded credentials, and abnormal ports.
  * **Dual Verification**: Combines local heuristic risk scoring with Google Safe Browsing API cloud threat intelligence.
  * **Deterministic Test Suite**: Comprehensive offline unit testing suite built with `pytest`.

---

<div align="center">
  <p><b>Akash Kataria • <a href="https://github.com/akashkataria766">github.com/akashkataria766</a></b></p>
</div>
