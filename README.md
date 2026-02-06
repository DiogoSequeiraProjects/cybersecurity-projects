# 🔎 Python TCP Port Scanner

Basic TCP port scanner developed in Python for educational and cybersecurity learning purposes.

---

## 📖 Overview
This project is a simple TCP port scanner written in Python that scans a target host to identify open TCP ports.
It resolves hostnames into IPv4 addresses and attempts to establish TCP connections using Python sockets.

The tool is designed to demonstrate fundamental networking and cybersecurity concepts such as:
- TCP connections
- Socket programming
- Network reconnaissance

---

## ⚙️ Features
- Hostname to IPv4 resolution
- TCP port scanning
- Custom timeout handling
- Clear and readable output
- Exception handling for common network errors

---

## 🛠 Technologies Used
- Python 3
- `socket`
- `sys`
- `datetime`

---

## ⚙️ How It Works
1. The user provides a target hostname or IP address as a command-line argument
2. The hostname is resolved to an IPv4 address
3. A TCP socket is created for each port in the scan range
4. The script attempts to connect to each port
5. Open ports are displayed in the terminal output

---

▶️ Usage

Run the script from the command line:

python3 scanner.py <target>

Example:
python3 scanner.py scanme.nmap.org

🔍 Default Port Range

The scanner checks ports from 50 to 84 by default.

This range can be modified directly in the source code:

for port in range(50, 85):

📄 Sample Output
--------------------------------------------------
Scanning target: 45.33.32.156
Time started: 2026-02-06 14:30:55.832145
--------------------------------------------------
Port 80 is open

⚠️ Legal Disclaimer

This project is intended strictly for educational purposes.

Do NOT use this tool to scan systems or networks that you do not own or have explicit permission to test.
Unauthorized port scanning may be illegal.


🚀 Future Improvements

Custom port range via command-line arguments

Multi-threaded scanning for better performance

Service detection

Output logging to file

Improved terminal formatting
## ▶️ Requirements
- Linux system (tested on Kali Linux)
- Python 3 installed



Check Python version:
```bash
python3 --version
