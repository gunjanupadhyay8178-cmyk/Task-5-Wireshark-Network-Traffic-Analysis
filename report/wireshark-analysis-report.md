# Wireshark Network Traffic Analysis Report

## 1. Objective
To capture live network traffic using Wireshark and identify basic network protocols.

## 2. Tool Used
- Wireshark

## 3. Protocols Identified

### DNS (Domain Name System)
Observed a DNS query for `google.com` and its response containing IP address information. DNS translates domain names into IP addresses.

### TCP (Transmission Control Protocol)
Observed TCP traffic involving port 443, including acknowledgements and other TCP communication. TCP provides reliable, connection-oriented data transmission.

### ICMP (Internet Control Message Protocol)
Observed ICMP Echo Request and Echo Reply packets generated during a ping test. These packets help verify network connectivity.

### TLS (Transport Layer Security)
Observed TLS-related traffic associated with encrypted web communication. The application data was encrypted and its contents were not readable in the capture.

## 4. Wireshark Display Filters
- `dns` — displays DNS packets
- `tcp` — displays TCP packets
- `icmp` — displays ICMP packets
- `tls` — displays TLS packets

## 5. Key Learnings
- Learned how to capture and inspect network packets.
- Practiced filtering traffic by protocol.
- Understood basic DNS queries, TCP communication, and ICMP ping packets.
- Learned how packet analysis supports network troubleshooting.

## 6. Conclusion
This task provided hands-on practice in network traffic capture and protocol analysis using Wireshark. It improved my understanding of how different protocols operate during network communication.

**Note:** Findings are based on the packets visible in the captured screenshots. The complete capture file can be used for further analysis.
