# LightLog 2026 (V1.3)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**LightLog 2026** is an advanced amateur radio station control and logbook software built in Python. It features a modern graphical interface (`tkinter`), local database management (`sqlite3`), real-time CAT control, QRZ.com integration, DX Cluster monitoring, interactive mapping, and detailed analytical charts.

---

## 🚀 Key Features

* **QSO Management:** Complete logging, editing, and deletion with automatic **DUPE detection** (band/mode/callsign). Keyboard shortcuts (`Ctrl+S`, `Esc`, `Ctrl+F`).
* **CAT Control:** Real-time frequency and mode tracking for major transceiver brands (FlexRadio, Kenwood, Icom, Yaesu) via Serial (COM) or TCP/IP.
* **QRZ.com Integration:** Automatic data lookups, profile picture retrieval, and pending log synchronization via API.
* **DX Cluster Monitor:** Live Telnet DX cluster spots with band/mode filters and one-click radio tuning.
* **Analytics & Charts:** Visual statistics generated via `matplotlib` (QSOs by band/mode, monthly trends, Top 20 DXCC countries).
* **Interactive Global Map:** Visualizes contact locations using Grid Locators, calculating bearing and distance (`tkintermapview`).
* **Solar & Propagation Monitor:** Tracks SFI, K-index, A-index, and band conditions.
* **Multilingual:** Full support for English and Portuguese.

---

## 📋 Prerequisites & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/SEU_UTILIZADOR/LightLog-2026.git](https://github.com/SEU_UTILIZADOR/LightLog-2026.git)
   cd LightLog-2026
