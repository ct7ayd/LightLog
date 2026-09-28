# LightLog 2026 (V1.2)

**LightLog 2026** is an advanced application developed in Python (featuring a Tkinter graphical user interface) designed for the comprehensive management of amateur radio stations.

---

## 🚀 Features

* **Radio Control (CAT / RIG Control):** Support for serial port (COM) or TCP/IP connections, compatible with various manufacturers and protocols (FlexRadio / SmartSDR, Kenwood, Icom, and Yaesu), enabling real-time reading and writing of frequency, band, and operating mode.
* **QSO Management (Logging and Editing):** A comprehensive form for logging contacts with automatic timestamping in UTC, callsign, RST, band, mode, name, QTH, country, and grid locator, including automatic duplicate contact detection (DUPE).
* **QRZ.com Integration:** Direct search functionality within the QRZ.com XML database to automatically populate biographical and geographical data for the corresponding station, view operator photographs, and synchronize/submit pending logs using the QRZ Logbook API.
* **Real-Time DX Cluster:** Integrated Telnet client for connecting to DX Cluster servers with live spot monitoring, filters for active bands or modes (SSB, CW, Digital), visual alerts, and DXCC country flag indications.
* **Statistics and Charts:** Key Performance Indicator (KPI) dashboards and analytical charts generated using Matplotlib covering QSO distribution by band, by mode, monthly evolution (last 12 months), and the Top 20 countries/DXCC.
* **Mapping and Geographic Tools:** Integration with interactive maps (`tkintermapview`) for automatic calculation of bearing, distance in kilometers based on the Grid Locator, and geographic visualization of completed contacts.
* **Solar Propagation Monitor:** A dedicated module for tracking ionospheric and solar indices (SFI, K-index, A-index, and solar wind), along with a condition summary table for HF bands.
* **ADIF Import and Export:** Full capability to import and export contact databases in the universal ADIF format (`.adi`).
* **Customization and Multilingual Interface:** Native support for Portuguese and English, configurable settings stored in JSON format, quick keyboard shortcuts (such as `Ctrl+S` to save or `Ctrl+F` to search), and detailed callsign history.

---

## 🛠️ Tech Stack

* **Language:** Python
* **GUI Framework:** Tkinter & `tkintermapview`
* **Data Visualization:** Matplotlib
* **Data Formats:** ADIF, JSON

---

## ⚙️ Installation & Usage

```bash
# Clone the repository
git clone [https://github.com/your-username/lightlog-2026.git](https://github.com/your-username/lightlog-2026.git)

# Navigate to the project directory
cd lightlog-2026

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
