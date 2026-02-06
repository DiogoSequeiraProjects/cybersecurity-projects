# cybersecurity-projects
Collection of cybersecurity tools and scripts developed in Python for educational and research purposes.

# 🔎 Python TCP Port Scanner

A basic TCP port scanner developed in Python for educational and cybersecurity learning purposes.

---

## 📖 Overview
This project implements a simple TCP port scanner using Python sockets.
It resolves a target hostname to an IPv4 address and scans a predefined range of ports to identify open services.

The goal of this project is to demonstrate:
- Network reconnaissance fundamentals
- Socket programming in Python
- Basic error handling in network applications

---

## 🛠 Technologies & Libraries
- Python 3
- socket
- sys
- datetime

---

## ⚙️ How It Works
1. The user provides a target hostname or IP address as a command-line argument
2. The script resolves the hostname to an IPv4 address
3. A TCP socket is created for each port in the defined range
4. The script attempts to connect to each port
5. Open ports are displayed in the terminal

---

## ▶️ Installation & Setup

### Requirements
- Linux (tested on Kali Linux)
- Python 3 installed

Check Python version:
```bash
python3 --version
