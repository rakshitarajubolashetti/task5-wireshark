# Task 5 – Network Traffic Analysis using Wireshark

**Tool Used:** Wireshark  
**Objective:** To capture and analyze real-time network traffic and identify different protocols and their roles.

---

## Steps Performed
1. Installed Wireshark (Windows x64 Installer) and Npcap.  
2. Opened Wireshark and selected the **Wi-Fi** interface for live packet capture.  
3. Browsed multiple websites (Google, Wikipedia, YouTube) to generate network traffic.  
4. Stopped the capture after 1 minute and saved it as `task5_capture_rakshita.pcapng`.  
5. Used **Statistics → Protocol Hierarchy** to view protocol distribution.  
6. Applied filters such as `dns`, `tcp`, and `tls` to analyze specific traffic types.

---

## Observations
- **DNS (Domain Name System):** Found queries translating domain names (e.g., `www.google.com`) to IP addresses.  
- **TCP (Transmission Control Protocol):** Showed reliable data transfer between source and destination.  
- **TLS (Transport Layer Security):** Indicated encrypted HTTPS sessions for secure communication.  
- **QUIC (Quick UDP Internet Connection):** Found modern web traffic from Chrome browsers.

---

## Results
| Protocol | Purpose | Example Found |
|-----------|----------|----------------|
| DNS | Resolves domain names | `www.google.com` |
| TCP | Data transfer | HTTP/HTTPS sessions |
| TLS | Secure encrypted connection | YouTube, Gmail traffic |
| QUIC | Encrypted UDP protocol for speed | Chrome web sessions |
| IPv4/IPv6 | Internet addressing | Network communication |

---

## Conclusion
Wireshark successfully captured real-time packets and helped visualize protocol layers used in modern network communication.  
This analysis provided insight into how devices communicate securely using DNS, TCP, TLS, and QUIC protocols.

---

## Screenshots
- `proto_hierarchy.png`
- `dns_filter.png`
- `tcp_filter.png`
- `tls_filter.png`
- `packet_detail.png`

---

**Report Prepared By:**  
Rakshita Bolashetti  
Date: *(write today’s date)*  
