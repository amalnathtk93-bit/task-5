# Task 5: Network Traffic Capture & Analysis Using Wireshark

## 📘 Description
This project involves capturing live network traffic using Wireshark, analyzing packets, identifying key protocols (DNS, TCP, ICMP, TLS), and exporting the traffic as a .pcap file. Traffic was generated through web browsing and ping commands to observe real network behavior.

---

## 🎯 Objective
- Capture real-time network packets  
- Identify and analyze network protocols  
- Understand packet flow and communication patterns  
- Export captured data as a .pcap file  

---

## 🛠 Tools Used
- *Wireshark*
- *Npcap*
- *Windows 10/11*
- *Web Browser (Chrome/Edge)*
- *Command Prompt (ping command)*

---

## 📂 Deliverables
- task5_capture.pcap – Packet capture file  
- Short report summarizing findings  

---

## 📑 Steps Followed
1. Installed Wireshark and Npcap.  
2. Selected the active Wi-Fi interface for capture.  
3. Started live packet capture.  
4. Generated traffic by browsing websites and using ping google.com.  
5. Stopped the capture after one minute.  
6. Applied filters such as dns, tcp, icmp, and tls to analyze packets.  
7. Inspected sample packets to understand protocol behavior.  
8. Exported the capture as a .pcap file.

---

## 🔍 Protocols Identified
- *DNS:* Resolves domain names to IP addresses  
- *TCP:* Reliable, connection-oriented transport protocol  
- *ICMP:* Diagnostic protocol used in ping operations  
- *TLS/HTTPS:* Encrypted web traffic on port 443  

---

## 📊 Observations
- DNS queries occur before connecting to websites.  
- TCP three-way handshake was visible during communication.  
- ICMP packets showed echo request and reply for connectivity testing.  
- Most website traffic was encrypted using TLS.  
- Packet flow clearly showed communication between host and servers.

---

## ✔ Conclusion
This task demonstrated how network communication works at the packet level. Using Wireshark, I observed real-time traffic, applied protocol filters, and exported a detailed packet capture. It provided hands-on experience in practical network analysis and monitoring.

---
