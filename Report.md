# Network Analysis report

## Key Goals
-  Capture network packets in real time.
-  Filter and analyze traffic to identify at least three distinct protocols.
-  Document findings in a short report with a saved packet capture (.pcap) file.

## Interface
-  Wi-Fi (Wireless Connection)
-  Ethernet ( Wired Connection
## Protocals Identified 
1. ** DNS **
   -  Purpose: Domain Name System protocol used to resolve google.com to an IP address
   -  Example: Packet #45 shows a DNS query for `www.example.com`.
2. ** HTTP **
   -  Purpose: Hypertext Transfer Protocol showing my request to example.com
   -  Example: Packet #120 contains a `GET /index.html` request.
3. ** TCP **
   -  Purpose:  Transmission Control Protocol establishing connections
   -  Example: Packet #3 shows a TCP 3-way handshake (SYN, SYN-ACK, ACK).

## Findings
-  Most traffic was TCP (about 60% of packets)
-  Observed both HTTP and HTTPS traffic
-  DNS queries occurred before each web request

  
