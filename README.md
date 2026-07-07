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
