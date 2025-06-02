# Task 5: Capture and Analyze Network Traffic Using Wireshark

## 📌 Objective
To capture live network packets and analyze different types of protocols using Wireshark.

## 🛠 Tools Used
- **Wireshark** (version 4.2.5 on Kali Linux)

## 🧪 Steps Performed
1. **Started Wireshark with root access** using:
   ```bash
   sudo wireshark
2.Selected the active network interface: wlan0.
3.Began packet capture, then generated network traffic by:

Visiting websites

Running ping google.com in terminal
4.Stopped the capture after about 1 minute.
5.Filtered packets by protocol:

http

dns

tcp

6.Saved the capture file as network_capture_task5.pcap.
