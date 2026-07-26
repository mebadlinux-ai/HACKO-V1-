Markdown
# HACKO_v1 Framework

![Stars](https://img.shields.io/badge/STARS-95-yellow?style=for-the-badge&logo=github)
![Forks](https://img.shields.io/badge/FORKS-17-orange?style=for-the-badge&logo=github)
![Issues](https://img.shields.io/badge/ISSUES-0%20OPEN-red?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/LICENSE-MIT-brightgreen?style=for-the-badge)
![Python](https://img.shields.io/badge/PYTHON-3.X-blue?style=for-the-badge&logo=python)
![Tools](https://img.shields.io/badge/TOOLS-1000%2B-brightgreen?style=for-the-badge)

![Framework](https://img.shields.io/badge/FRAMEWORK-ADVANCED-00b4d8?style=for-the-badge)
![Platform](https://img.shields.io/badge/PLATFORM-TERMUX%20%7C%20LINUX%20%7C%20MAC%20%7C%20WINDOWS-449e48?style=for-the-badge)
![Maintained](https://img.shields.io/badge/MAINTAINED-ACTIVE-brightgreen?style=for-the-badge)

![Status](https://img.shields.io/badge/STATUS-STABLE-00f5d4?style=for-the-badge)

---

![About](https://img.shields.io/badge/ABOUT-HACKO__V1%20FRAMEWORK-ff6b00?style=for-the-badge)

**HACKO_v1** is a high-speed, lightweight recon and digital footprinting framework engineered specifically for mobile deployment on **Termux**. Built on top of the **RED_HAWK** engine with zero heavy dependencies, HACKO_v1 turns your Android terminal into an on-the-go OSINT and target-profiling suite.

---

### Core Dependencies

* **RED_HAWK Integration:** Powered by the RED_HAWK PHP/Python core engine for deep web server auditing, Cloudflare detection, and IP lookup capabilities.

---

### Key Modules & Features

*   **Footprint & Identity Aggregator:**
    *   **Alias Tracker:** Queries 300+ social platforms, forums, and developer nodes to trace handles across the web.
    *   **Breach & Mail Correlator:** Runs fast API-driven breach lookups, checks MX records, and maps target emails to linked profiles.
    *   **EXIF & Metadata Extractor:** Pulls hidden author details, camera hardware profiles, and GPS coordinates directly from target media uploads.

*   **Automated Target Reconnaissance:**
    *   **Subdomain & Asset Finder:** Combines RED_HAWK's DNS history queries with dictionary brute-forcing to reveal target infrastructure.
    *   **Port & Service Scanner:** Multi-threaded socket scanner built for Android environments to spot exposed admin panels, open ports, and running banners.
    *   **CMS & Stack Identifier:** Detects active Web frameworks, CMS builds, WordPress plugins, and server headers without high CPU overhead.

*   **Termux-Optimized Execution:**
    *   **One-Tap Scripting:** Simple command arguments allow running complete target profiling sequences with a single command.
    *   **Lightweight TUI:** A clean, color-coded terminal UI designed for compact mobile terminal screens.
    *   **Direct Local Export:** Dumps target dossiers in text, Markdown, or JSON directly to `/sdcard/` storage.

---

### Quick Installation (Termux)

```bash
# Update package repositories
pkg update && pkg upgrade -y

# Install required dependencies & PHP for RED_HAWK core
pkg install python php git -y

# Clone the repository
git clone [https://github.com/yourusername/HACKO-V1.git](https://github.com/yourusername/HACKO-V1.git)

# Navigate to directory and launch
cd HACKO-V1
php rhawk.php
