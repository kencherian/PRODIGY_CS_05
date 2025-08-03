# 🕵️‍♂️ Network Packet Analyzer (GUI Version)

A simple and educational **Packet Sniffer GUI tool** built using Python, Scapy, and Tkinter. It allows users to capture, analyze, and log network packets in real-time with a user-friendly graphical interface.

---

## 🚀 Features

- ✅ Start/Stop live packet capturing
- 📡 Displays Source IP, Destination IP, and Protocol
- 🧾 View raw payload (if present)
- 💾 Save logs to:
  - `.txt` (readable log)
  - `.pcap` (open in Wireshark)

---

## 📦 Requirements

- Python 3.x  
- Required Libraries:
bash:
  pip install scapy

🖥️ How to Use:
->Run the script with administrator/root privileges:

bash:
sudo python packet_sniffer_gui.py
Click Start Capture to begin sniffing packets.

Click Stop Capture to end the session.

Click Save Logs to export:

A human-readable .txt log

A .pcap file for use with Wireshark or other analyzers

📁 Output Files
packet_log.txt: Readable log with IPs, Protocols, and payloads

captured_packets.pcap: Raw packet dump viewable in Wireshark

