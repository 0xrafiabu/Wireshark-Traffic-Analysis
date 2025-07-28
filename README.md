# 🛡️ Wireshark Traffic Analysis: DoS & DDoS Attacks

This project presents an in-depth packet-level analysis of Denial-of-Service (DoS) and Distributed Denial-of-Service (DDoS) attacks using **Wireshark**. It was developed as part of my studies at **Ulster University**.

---

## 📘 Project Summary

Using real network traffic samples and Wireshark, I analyzed three types of attacks:

- **SYN Flood** – exploits the TCP 3-way handshake to exhaust server resources
- **HTTP Flood** – overwhelms web servers with excessive GET requests
- **Fragmentation Attack** – evades detection with oversized or split packets

Each attack was examined with custom Wireshark filters and visually documented with screenshots, I/O graphs, and packet dissections.

---

## 🔧 Tools & Techniques

- **Wireshark** for packet capture and analysis  
- **TCP/IP and UDP Protocols**  
- **Custom Filters**: SYN flag detection, HTTP GET patterns, fragment anomalies  
- **Attack IP identification** and behavior mapping  
- **Protocol hierarchy and flow tracking**

---

## 🛡️ Key Defenses Proposed

- SYN Cookies  
- Web Application Firewall (WAF)  
- Deep Packet Inspection (DPI)  
- Intrusion Detection/Prevention Systems (IDS/IPS)  
- Rate Limiting and IP Filtering

---

## 📄 Full Report

🔗 [Download the PDF Report](./Wireshark_DoS_DDoS_Analysis.pdf)

Includes diagrams, filtered packet views, technical explanations, and real mitigation recommendations.

---

## 👨‍💻 Author

**Shah Abu Kawsar Rafi**  
BSc (Hons) Computing Systems, Ulster University  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/0xrafiabu)

---

⭐ If you found this project useful, feel free to star the repo!
