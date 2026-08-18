# SOC Simulation Lab

A hands-on Security Operations Center (SOC) lab focused on network reconnaissance, packet analysis, and Linux log investigation using Nmap, Wireshark, Kali Linux, and journalctl.

> **Project Type:** Cybersecurity / SOC / Blue Team  
> **Status:** Hands-on Lab Project

---

## 🎯 Objective

The goal of this lab was to simulate a basic SOC investigation workflow by generating network activity, capturing traffic, and analyzing system logs.

The lab demonstrates the following security workflow:

**Generate Activity → Capture Traffic → Analyze Logs → Identify Suspicious Activity → Document Findings**

---

## 🛠️ Tools Used

- **Kali Linux** — Security testing and analysis environment
- **Nmap** — Network discovery and port scanning
- **Wireshark** — Network packet capture and analysis
- **journalctl** — Linux system log investigation

---

## 🔬 Lab Activities

### 1. Network Reconnaissance

Used Nmap to generate network scanning activity and identify accessible services.

### 2. Packet Capture

Used Wireshark to capture and inspect network traffic generated during the scan.

### 3. Traffic Analysis

Analyzed captured packets to understand:

- Source and destination communication
- TCP connections
- Port activity
- Network scanning behavior

### 4. Log Investigation

Used `journalctl` to investigate Linux system events and correlate system activity with the network activity generated during the lab.

---

## 🔍 Key Findings

During the investigation, the following activity was observed:

- Network scanning activity generated using Nmap
- TCP communication between systems
- Port-level network activity
- Corresponding Linux system events
- Multiple data sources useful for SOC investigation

---

## 🏗️ SOC Investigation Workflow

```text
        Network Activity
               │
               ▼
          Nmap Scan
               │
               ▼
       Wireshark Capture
               │
               ▼
       Packet Analysis
               │
               ▼
       journalctl Logs
               │
               ▼
     Activity Correlation
               │
               ▼
        SOC Findings
