# cybersecurity-projects
Collection of cybersecurity tools and scripts developed in Python for educational and research purposes.

# 🔎 Python Port Scanner

Basic TCP port scanner developed in Python for educational purposes.

## 📌 Description
This project is a simple TCP port scanner that checks for open ports on a target host within a predefined port range.
It resolves hostnames to IPv4 addresses and attempts to establish TCP connections to identify open ports.

The tool is designed to demonstrate fundamental networking and cybersecurity concepts such as:
- TCP connections
- Socket programming
- Network reconnaissance

## ⚙️ Features
- Hostname to IPv4 resolution
- TCP port scanning
- Custom timeout handling
- Clear and readable output
- Exception handling for common network errors

## 🧠 Technologies Used
- Python 3
- `socket`
- `sys`
- `datetime`

## ▶️ Usage

Run the script from the command line:

```bash
python3 scanner.py <target>
