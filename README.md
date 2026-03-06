# CyberConnect Fellowship — SOC Labs 🛡️

This repository is where I document everything I'm working through as part of the **CyberConnect SOC Fellowship**. It includes my personal notes, lab walkthroughs, and screenshots from hands-on tasks focused on the SOC (Security Operations Center) track.

The work here covers networking fundamentals, packet capture, and traffic analysis — skills that are at the core of threat monitoring and detection in a real SOC environment.

---

## 👤 About Me

| Field | Details |
|-------|---------|
| **Name** | Ain Ul Wara |
| **Track** | SOC (Security Operations Center) |
| **GitHub** | [@ainulwara](https://github.com/ainulwara) |
| **TryHackMe** | [tryhackme.com/p/ainulwarasultan](https://tryhackme.com/p/ainulwarasultan) |

---

## ✅ Completed Labs

### 1. Introductory Networking
An introduction to how networks function, covering key concepts like IP addressing, protocols, and how data travels across a network.

---

### 2. Network Traffic Basics — Wireshark Analysis

#### Task 2: Wireshark Packet Analysis

In this lab I used Wireshark to capture and analyze live network traffic. The focus was on understanding what happens at the packet level and how to extract meaningful information from a capture.

**What I practiced:**
- Capturing traffic from a live network interface
- Loading and navigating `.pcap` files
- Using display filters (`dns`, `http`, `tcp`) to isolate specific traffic
- Expanding packet layers to inspect Ethernet, IP, and application-level data
- Following TCP/UDP streams to reconstruct full conversations between devices
- Identifying DNS queries and responses, including transaction IDs, query names, and record types
- Spotting patterns that could indicate unusual or suspicious activity

**Key takeaway:** Wireshark gives you a full view into what is happening on a network in real time. Being able to filter, read, and interpret packets is a foundational skill for anyone working in a SOC.

📁 *Screenshots and notes from this task are included in the `Wireshark/` folder.*

---

## 📁 Repository Structure

```
CyberConnect-SOC-Fellowship/
│
├── Wireshark/               # Task 2 — Wireshark packet analysis
│   ├── screenshots/         # Annotated screenshots from the lab
│   └── notes.md             # Personal notes and observations
│
└── README.md
```

---

## 🔄 Progress

This is an ongoing repository. I will keep adding labs, notes, and walkthroughs as I move forward through the SOC track.

> *More tasks coming soon — stay tuned.*

---

*CyberConnect SOC Fellowship • 2026*
