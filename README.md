# LightLog 2026 (V1.2) - Amateur Radio Station Logbook

**LightLog 2026** is a modern, feature-rich Ham Radio station logbook and control software built with Python and Tkinter. Designed for radio amateurs, it integrates rig control, real-time DX Cluster monitoring, QRZ.com data lookup, propagation tracking, and advanced logging analytics into a single, clean desktop application.

---

## 🚀 Key Features

*   **📻 Radio Control (CAT & SmartSDR):** Real-time frequency, band, and mode tracking supporting major transceiver protocols (FlexRadio, Kenwood, Icom CI-V, Yaesu) via Serial (COM) ports or TCP/IP connections.
*   **🔍 QRZ.com Integration:** Automated XML API lookups to instantly fetch operator details (Name, QTH, Country, Grid Locator) and profile photos.
*   **📡 Live DX Cluster Monitor:** Built-in Telnet client for DX spots with real-time streaming, raw monitor debugging, and advanced filtering by active band and operating mode (CW, SSB, Digital).
*   **📊 Statistics & Analytics Dashboard:** Comprehensive Matplotlib integration displaying KPIs and interactive charts:
    *   QSOs by Band & Mode
    *   Monthly Evolution (Last 12 Months)
    *   Top 20 Countries / DXCC
*   **🗺️ Interactive Global Map:** Visual mapping of logged contacts and Maidenhead locator grids using `tkintermapview` and OpenStreetMap integration.
*   **☀️ Solar & Ionospheric Propagation Monitor:** Live tracking of Solar Flux Index (SFI), K-Index, A-Index, solar wind, and estimated HF band conditions.
*   **📂 ADIF Import & Export:** Full compatibility with standard `.adi` logbook files for seamless backup and synchronization with online logbooks (including QRZ.com Logbook).
*   **🌐 Multilingual Interface:** Fully localized support for Portuguese (`pt`) and English (`en`).

---

## 🛠️ Tech Stack

*   **Language:** Python 3.x
*   **GUI Framework:** Tkinter & TTK
*   **Mapping:** `tkintermapview`
*   **Charts:** Matplotlib (`FigureCanvasTkAgg`)
*   **Networking & Hardware:** `pyserial`, `requests`, Socket programming
*   **Data Storage:** SQLite3

---

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/ct7ayd/LightLog.git](https://github.com/ct7ayd/LightLog.git)
   cd LightLog

Install required dependencies:

pip install requests pyserial pillow matplotlib tkintermapview

Run the application:

python lightlog_2026_v1.2_14.py

📄 License
Distributed under the MIT License. See LICENSE for more information.

Developed with ⚡ by José Luís Albuquerque (CT7AYD)
