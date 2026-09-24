What is LightLog 2026?

LightLog 2026 is a modern, lightweight, and high-performance amateur radio logging application designed to optimize shack operations. Featuring native CAT integration (supporting FlexRadio/SmartSDR, Icom, Kenwood, and Yaesu), Telnet connection to DX Cluster servers with a Raw Stream monitor, and full bidirectional synchronization with QRZ.com (including API keys and XML), LightLog ensures total real-time control of your radio operations.

Main Features
Integrated CAT and CI-V Control: Direct connection to the radio via serial port (pyserial) or TCP/IP (compatible with FlexRadio, Kenwood, Icom, and Yaesu). Automatically updates frequency (in Hertz), band, and operating mode in real-time.

DX Cluster & Raw Stream Monitor: Simultaneous connection to DX Cluster servers via Telnet with smart filters for active bands and specific modes (SSB, CW, DIGI), accompanied by an advanced diagnostic window (Raw Stream Monitor).

Full QRZ.com Integration:

Automatic callsign XML lookup for instant population of name, QTH, country, Grid Locator, and operator photo.

Support for operator photo downloading (with a full-size viewer) and automatic or batch uploading of pending QSOs to the QRZ.com logbook via API key.

Geographical Tools and Integrated Map: Automatic calculation of distance in kilometers and bearing based on the station's and correspondent's Grid Locator, complemented by an interactive map window (tkintermapview) for direct QTH visualization.

Advanced Statistics and Dynamic Charts: Integrated analytical dashboard (with matplotlib support) displaying real-time metrics for total QSOs, unique callsigns, worked bands, percentage distribution of modes, and monthly contact evolution.

Data Management and ADIF Compatibility: Simplified import and export of .adi files for total interoperability with other market software.

Optimized Interface and Keyboard Shortcuts: Multilingual support (Portuguese and English) and integrated quick commands to streamline workflows during contests or pile-ups:

Ctrl + S: Save QSO

Esc: Clear form / cancel

Ctrl + F: Quick search in history

Cross-Platform Architecture: Compatible with Windows, Linux, and macOS, running in a Python environment.

Technical Requirements
Operating System: Windows 10/11, Linux, or macOS.

Runtime Environment: Python 3.10 or higher.

Required Python Modules: tkinter, pyserial, requests, pillow, matplotlib, and tkintermapview.

Internet Connection: Required for QRZ.com XML lookups, DXCC flag downloads, and DX Cluster spot reception.

<img width="1319" height="766" alt="image" src="https://github.com/user-attachments/assets/ad2ec4b6-684e-4e53-b0fb-18f231aa8cdd" />

<img width="452" height="812" alt="image" src="https://github.com/user-attachments/assets/1dc289ea-60e2-4f9c-8a02-2854c21d2719" />

<img width="1334" height="457" alt="image" src="https://github.com/user-attachments/assets/ab9515e9-305d-44da-9ec4-46dad006de34" />


