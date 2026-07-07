# Network-Traffic-Analysis-Task5
## Cyber Security Internship - Task 5: Comprehensive Live Network Traffic Ingestion, Protocol Dissection, and Forensics Analysis

## 🎯 1. Project Overview & Comprehensive Objective
The primary core objective of this engineering task is to deploy an administrative host-based network packet sniffer configuration to ingest, map, and log live Ethernet/Wireless data streams traversing the local network interface card (NIC). 

Through programmatic traffic simulation and logical syntax filtering, this project builds production-ready capabilities in network forensic analysis, frame encapsulation tracking, deep packet inspection (DPI), and protocol validation auditing to harden enterprise infrastructure landscapes.

---

## 🛠️ 2. Environmental Infrastructure & Tool Matrix
* **Network Protocol Dissector & Analyzer:** Wireshark (v4.x Engine) — Utilized for real-time tracking, packet extraction, byte parsing, and multi-layered hex/text frame dissections.
* **Administrative Shell Platform:** Windows Command Prompt (CMD Terminal) — Executed with system privileges to initiate manual host routing diagnostics.
* **Target Diagnostic Vector:** `chrome.com` — Employed as the destination web server target endpoint to force live Application and Transport layer network trace variables.

---

## 💻 3. Operational Roadmap & Technical Steps (Humne Kaise Kiya)

To successfully implement this structural assessment, the following sequential deployment phases were strictly executed:

### Phase A: Interface Binding and Packet Ingestion
1. Wireshark was initialized with administrative privileges to unlock raw socket monitoring capabilities across the local active Wi-Fi interface.
2. The capture engine was set to promiscuous mode to ensure the ingestion of all sequential network frames traveling across the local segment.

### Phase B: Controlled Traffic Injection
1. To generate high-visibility baseline network interactions without corrupting logging queues, an Internet Control Message Protocol (ICMP) echo diagnostic trace session was dispatched via the console terminal to the target server:
   ```bash
   ping chrome.com
   
### Phase C: Noise Reduction and Advanced Logical Filtering
1. Because modern workstations constantly run background cloud sync protocols, multicast device discovery services, and local telemetry pings, the default capture view contained massive amounts of unneeded packet noise.

2. To isolate the primary target communication variables, the following strict logical Boolean display filter was compiled and executed inside the display filter address bar: dns || icmp || tcp  

3. This criteria systematically dropped all external broadcast noise, focusing the entire Wireshark interactive workspace on analyzing standard protocol suites.
   
### Phase D: Forensics Export and Data Preservation
1. The validated trace buffers containing the exact filtered frames were permanently compiled and written out into a standardized capture file type to support future forensic reconstruction or threat intelligence compliance auditing.
---
## 4. Deep-Dive Artifact & Repository File Explanations
This repository hosts specific core forensic artifacts. Below is the full technical breakdown explaining what data layers are contained within each file:

### File 1: network_traffic_capture.pcap (The Raw Data Stream)
What it is: This is the exported raw binary packet capture file containing the exact payload strings, source/destination hardware parameters, and microsecond-level chronological timings of the entire active network session.

### File 2: wireshark_capture_dashboard.png (The System Verification Interface)
This visual workspace trace acts as administrative verification that the task was executed flawlessly. It captures the three primary interface panels of Wireshark detailing specific protocol actions:

#### Panel A: The Filter Expression Log — 
Proves the successful implementation of the logical dns || icmp || tcp condition statement, ensuring a streamlined environment setup.

#### Panel B: The Packet List Pane —
Showcases the chronological rows of the filtered protocols generated during the ping chrome.com runtime window:

### DNS (Domain Name System): 
Captures the critical Application Layer transactions where the local workstation queries global domain controllers to resolve the exact Public IP address of chrome.com, followed by the authoritative A-record response vectors.

### ICMP (Internet Control Message Protocol): 
Displays the exact diagnostic echo request (Type 8) frames exiting the machine and corresponding echo reply (Type 0) frames returning from the host server to trace network latency parameters.

### TCP (Transmission Control Protocol): 
Logs the connection-oriented Transport Layer metadata flags orchestrating stable virtual connection frameworks.

#### Panel C: The Packet Details & Hex Dissection Panes — 
Displays the layered protocol field breakdowns (Layer 2 Ethernet frames, Layer 3 IPv4 mappings, Layer 4 Transport segments), validating precise packet layout structures.
