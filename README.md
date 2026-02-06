# 🔎 Python TCP Port Scanner

A basic TCP port scanner developed in Python for educational and cybersecurity learning purposes.

---

## 📖 Overview
This project is a simple TCP port scanner written in Python that scans a target host to identify open TCP ports.
It resolves hostnames into IPv4 addresses and attempts TCP connections using Python sockets.

This tool was developed as part of cybersecurity learning and networking fundamentals practice.

---

## 🛠 Technologies Used
- Python 3
- socket
- sys
- datetime

---

## ⚙️ How It Works
1. The user provides a target hostname or IP address as a command-line argument
2. The hostname is resolved to an IPv4 address
3. A TCP socket is created for each port in the scan range
4. The script attempts to connect to each port
5. Open ports are displayed in the terminal output

---

## ▶️ Requirements
- Linux system (tested on Kali Linux)
- Python 3 installed

Check Python version:
```bash
python3 --version
