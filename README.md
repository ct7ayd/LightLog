# 📻 LightLog 2026 (V1.4) - Station Logbook & Radio Control

**LightLog 2026** is an advanced radio amateur contact logging (Logbook) and station control application developed in Python with a Tkinter graphical user interface. It combines CAT radio monitoring, real-time integration with DX Clusters, geolocation tools, and synchronization with QRZ.com.

---

## 🚀 Key Features

### 📝 QSO Logging & Log Management
* **Comprehensive Logging**: Support for callsigns, UTC date/time (with an option to freeze/unfreeze the clock), frequencies, bands (160m to 70cm), modes (SSB, CW, FT8, RTTY, etc.), sent and received RST, name, QTH, country, Grid Locator, and comments.
* **Duplicate Detection (DUPE)**: Immediate visual alert if the QSO has already been logged on the same band and mode.
* **DXCC Indicators (ATNO & New Band)**: Automatic identification of All Time New Entities (ATNO) and new contacts on specific bands.
* **Callsign History**: Quick view of previous contacts made with the same callsign directly on the panel.
* **ADIF Import & Export**: Full compatibility with `.adi` files to import and export logs to/from other software.

### 📻 Radio Control (CAT / SmartSDR / FlexRadio)
* **Flexible Connection**: Supports communication via Serial Port (CAT) and TCP/IP.
* **Supported Protocols**: Compatible with equipment and software using **FlexRadio, Kenwood, Yaesu, and Icom (CI-V)** protocols.
* **Automatic Synchronization**: Real-time reading of frequency, band, and mode directly from the radio, automatically filling out the QSO form.
* **Remote Frequency Control**: Ability to tune the radio directly from the DX Cluster or selected spots.

### 📡 DX Cluster & Real-Time Spots
* **Integrated Telnet Client**: Connection to DX Cluster servers (e.g., `dxc.nc7j.com`) with automatic reconnection and a raw stream monitor.
* **Advanced Filters**: Filter spots by "Active Band Only" and by mode (SSB, CW, Digital).
* **SmartSDR Integration**: Automatic forwarding of spots to the SmartSDR Panadapter via TCP API.
* **Spot Submission**: Dedicated panel to submit new DX Spots directly to the cluster.

### 🌐 Geolocation & Interactive Maps
* **Global Maps & Mini-Maps**: Integration with `tkintermapview` to visualize contact locations in the log and geographical positions.
* **Distance and Bearing Calculation**: Automatic calculation of distance in kilometers and azimuth based on Grid Locators.
* **Visual Flag Indicators**: Support for country identification and flag thumbnails based on the `cty.dat` file parser.

### 🔑 QRZ.com Integration
* **XML Search**: Instant lookup of callsign data on QRZ.com (Name, QTH, Country, Grid, and profile picture).
* **Logbook Synchronization**: Upload pending or individual QSOs directly to the QRZ.com Logbook using the API Key.

### 📊 Statistics & Advanced Charts
* Integrated analytical dashboard powered by **Matplotlib**, displaying:
  * Charts of QSOs by Band and Mode.
  * Monthly evolution (last 12 months).
  * Top 20 Countries / DXCC Entities.
  * Activity by UTC hour and continent distribution.
  * KPI cards with total QSOs, unique callsigns, Grid squares, and worked DXCCs.

### ☀️ Solar and Ionospheric Propagation Monitor
* Real-time solar and ionospheric indices consultation (**SFI - Solar Flux Index, K-Index, A-Index, and Solar Wind**).
* Table of estimated conditions for HF bands (Day and Night) and critical frequencies (MUF).

### 🌍 Multi-language Support
* Fully translated and adaptable interface for **7 languages**: Portuguese, English, Spanish, French, German, Italian, and Russian.
