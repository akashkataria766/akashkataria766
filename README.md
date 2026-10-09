<div align="center">

  # Akash Kataria

  <p align="center">
    <b>Building robust database-first architectures, desktop security utilities, intelligent AI systems, and modern mobile & web applications.</b>
  </p>

  <p align="center">
    <a href="https://github.com/akashkataria766">
      <img src="https://img.shields.io/github/followers/akashkataria766?label=Followers&style=flat-square&color=2563EB" alt="Followers" />
    </a>
    <img src="https://img.shields.io/badge/Focus-High_Performance_Systems-0EA5E9?style=flat-square" alt="Focus" />
    <img src="https://img.shields.io/badge/Architecture-Database--First_&_Clean_Code-10B981?style=flat-square" alt="Architecture" />
  </p>

</div>

---

### 🛠️ Core Technologies & Tools

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Databases & Systems** | Oracle Database, PL/SQL, Oracle APEX, SQL, Database-First Architecture, Data Modeling |
| **Mobile & Desktop** | Android (Kotlin, Jetpack Compose, Media3 / ExoPlayer), C# (.NET, Windows Desktop, Windows Hello) |
| **Web & Frameworks** | React, Next.js, TypeScript, JavaScript, Tailwind CSS, Vite |
| **Backend & Cloud** | Python (Flask, Streamlit), Node.js (Express), Firebase (Auth, Firestore), REST APIs |
| **Security & Analytics** | AES-256 Encryption, PBKDF2, Cryptographic Protocols, Google Safe Browsing API, Pandas, NumPy, Plotly |

---

### 📂 Featured Public Projects

#### 1. 🏛️ [Public Grievance Redressal System (PGRS)](https://github.com/akashkataria766/Public-Grievance-Redressal-System)
> **Database-First Municipal Governance & Complaint Lifecycle Management Platform**
* **Stack**: Oracle Database, PL/SQL, Oracle APEX
* **Highlights**:
  * **Database-First Governance**: Enforces business rules, role boundaries, and audit controls directly within Oracle Database and PL/SQL rather than client UI layers.
  * **Deterministic 7-Stage Lifecycle**: Manages complaints through a structured state machine (`SUBMITTED` ➔ `ASSIGNED` ➔ `IN_PROGRESS` ➔ `RESOLVED` ➔ `VERIFICATION_PENDING` ➔ `CLOSED`), with overdue SLA escalation routes.
  * **Automated Background Procedures**: Built-in routines for idempotent SLA breach escalation (`PGRS_AUTO_ESCALATE`), 7-day citizen auto-closure (`PGRS_AUTO_CLOSE_VERIFICATION`), and 5-year data archival (`PGRS_ARCHIVE_OLD_COMPLAINTS`).
  * **Integrity & Immutability**: Protected by database triggers (`TRG_PGRS_DUE_DATE_LOCK`, `TRG_PGRS_NO_UPDATE_CLOSED`, `TRG_PGRS_LOG_IMMUTABLE`).

---

#### 2. 🎵 [Sky-Wave](https://github.com/akashkataria766/Sky-Wave)
> **Modern Native Android Music & Audio Streaming Architecture**
* **Stack**: Kotlin, Jetpack Compose, Android Architecture Components, Media3 / ExoPlayer
* **Highlights**:
  * **Multi-Module Clean Architecture**: Decoupled feature-first Gradle structure with independent domain, UI, database, network, and playback modules (`:core:core-playback`, `:feature:feature-player`, `:feature:feature-library`).
  * **High-Fidelity Audio Playback**: Background audio service with system notification controls, playlist state synchronization, and offline cache management.

---

#### 3. 🤖 [Sky-Core](https://github.com/akashkataria766/Sky-Core)
> **Private AI Companion Progressive Web App (PWA)**
* **Stack**: React 19, TypeScript, Vite, Zustand, React Router v7, Firebase
* **Highlights**:
  * **Strict Gatekeeping State Machine**: 4-state user lifecycle verification (`PENDING_APPROVAL`, `APPROVED`, `REJECTED`, `BLOCKED`) controlling application access.
  * **State & Route Guards**: Access control enforced through Zustand state management and React Router v7 with server-side Firestore Security Rules.
  * **Structured Error Taxonomy**: Centralized error tracking architecture (`SS-401`, `SS-696`) with clear feedback mechanisms.

---

#### 4. 🔒 [Sky Secure Folders](https://github.com/akashkataria766/Sky-Secure-Folders)
> **Windows Desktop Security Utility for File & Folder Protection**
* **Stack**: C#, .NET, Windows Cryptography APIs
* **Highlights**:
  * **Robust File Encryption**: Protects local folders with AES-256 encryption and PBKDF2 key derivation.
  * **Biometric Verification**: Optional authentication via Windows Hello for fast, biometric-backed folder access.
  * **Filesystem Safety**: Atomic lock and restore pipelines preventing data corruption during cryptographic operations.

---

#### 5. 📊 [Consumer Transaction Data Analysis](https://github.com/akashkataria766/Consumer-Transaction-Data-Analysis)
> **Automated Financial Transaction Analytics & Business Intelligence Dashboard**
* **Stack**: Python 3.11, Streamlit, Pandas, NumPy, Plotly, openpyxl, Oracle SQL
* **Highlights**:
  * **Automated Data Hygiene**: Ingestion pipeline validating duplicate IDs, datetime formats, amount thresholds, and status consistency.
  * **Statistical Anomaly Detection**: Interquartile range (IQR) outlier detection surfacing high-value irregular transactions.
  * **Multi-Format Business Exports**: Interactive Plotly charts, static Matplotlib reports, automated multi-sheet openpyxl Excel exports, and Oracle SQL reporting queries.

---

#### 6. 🛡️ [Web Security Analyzer](https://github.com/akashkataria766/Web-Security-Analyzer)
> **Heuristic URL Threat Scanner & Safe Browsing Triage Tool**
* **Stack**: Python, Flask, Google Safe Browsing API, pytest
* **Highlights**:
  * **Multi-Vector Threat Detection**: Inspects homoglyphs/punycode impersonation (`go0gle.com`), suspicious subdomains, embedded credentials, and abnormal ports.
  * **Dual Verification**: Combines local heuristic risk scoring with Google Safe Browsing API cloud threat intelligence.
  * **Deterministic Test Suite**: Comprehensive offline unit testing suite built with `pytest`.

---

<div align="center">
  <p><b>Akash Kataria • <a href="https://github.com/akashkataria766">github.com/akashkataria766</a></b></p>
</div>
