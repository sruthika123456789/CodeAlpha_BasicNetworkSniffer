Md
# 🕵️ Basic Network Sniffer

## 📌 Project Overview
The **Basic Network Sniffer** is a Python-based cybersecurity project that captures and analyzes live network packets.  
It helps in understanding how data flows across a network and how different protocols operate at the packet level.

This project is developed as part of the **CodeAlpha Cyber Security Internship**.

⚠ **For educational purposes only.**

---

## 🎯 Objectives
- Capture live network traffic
- Analyze packet structure and contents
- Identify network protocols (IP, TCP, UDP)
- Display useful packet information such as:
  - Source IP address
  - Destination IP address
  - Protocol type
  - Payload data

---

## 🛠 Tools & Technologies Used
- Python 3
- Scapy Library
- Windows / Linux OS (Administrator or Root access required)

---

## 📂 Project Structure
CodeAlpha_BasicNetworkSniffer/ │ ├── sniffer.py └── README.md
Copy code

---

## ⚙️ How It Works
1. Captures live network packets
2. Filters IP-based packets
3. Analyzes TCP and UDP traffic
4. Displays packet details in real time

---

## ▶️ How to Run
### Install Dependencies
```bash
pip install scapy
Run the Program
Copy code
Bash
python sniffer.py
📊 Sample Output
Copy code

Source IP: 192.168.1.5
Destination IP: 142.250.182.14
Protocol: TCP
Payload: b'GET / HTTP/1.1'
🚨 Ethical Disclaimer
This project is intended for educational purposes only.
Do not use this tool on networks without proper authorization.
👩‍💻 Author
Mittapally Sruthika
✅ Internship Task
CodeAlpha Cyber Security Internship
Task 1: Basic Network Sniffer# CodeAlpha_BasicNetworkSniffer
Basic network sniffer using python
