
# Topic 1: OSI Model (Platforms and Network Technologies)

## What this topic is about
The OSI Model is a framework used to understand how data moves across networks. It helps organize networking concepts into layers.

---

## Objective 1: Common elements in client/server networks
### Client/Server basics
- **Client:** device/app requesting something (browser, phone app)
- **Server:** device/app providing something (web server, DNS server)
- **Internet:** global network of networks
- **LAN:** Local Area Network (home/school/building)
- **Wireless (Wi-Fi):** a LAN connection using radio instead of cables

Common elements:
- Client device (PC/phone)
- Server (website/DNS/file server)
- Switch (connects devices in a LAN)
- Router (connects networks; LAN to internet)
- Access Point (Wi-Fi connection)
- Firewall (filters traffic)
---

## Objective 2: Parts of a networking model (OSI and TCP/IP)

## 🧱 The 7 OSI Layers (Top → Bottom)
+--------------------+
| 7. Application |
+--------------------+
| 6. Presentation |
+--------------------+
| 5. Session |
+--------------------+
| 4. Transport |
+--------------------+
| 3. Network |
+--------------------+
| 2. Data Link |
+--------------------+
| 1. Physical |
+--------------------+
---

## 📘 Layer Breakdown

| Layer | Name | Key Responsibility | Example |
|-------|------|-------------------|---------|
| 7 | Application | User-facing network services | HTTP, FTP |
| 6 | Presentation | Data formatting, encryption | SSL/TLS |
| 5 | Session | Manages sessions | API sessions |
| 4 | Transport | Reliable transmission | TCP, UDP |
| 3 | Network | Logical addressing & routing | IP |
| 2 | Data Link | MAC addressing | Ethernet |
| 1 | Physical | Physical transmission | Cables, Signals |  

### TCP/IP (4 layers)
- Application
- Transport
- Internet
- Network Access

### Simple mapping
- OSI 7–5 → TCP/IP Application
- OSI 4 → TCP/IP Transport
- OSI 3 → TCP/IP Internet
- OSI 2–1 → TCP/IP Network Access

---

## Objective 3: Hardware components and functions
- **NIC:** network card; connects a device to a network
- **Switch:** connects many devices inside a LAN
- **Router:** connects different networks
- **Modem:** connects your home network to your ISP
- **Access Point:** provides Wi-Fi
- **Firewall:** blocks/allows traffic based on rules

---

## Objective 4: Architectures and topologies
### Network sizes
- **PAN:** Personal Area Network (Bluetooth)
- **LAN:** Local Area Network (home, office)
- **CAN:** Campus Area Network (college campus)
- **MAN:** Metropolitan Area Network (city-wide)
- **WAN:** Wide Area Network (internet is the largest WAN)

### Topologies
- **Star:** most common (devices connect to a switch)
- **Bus:** older style
- **Ring:** older style
- **Mesh:** multiple paths (more reliable, more expensive)
- **Hybrid:** combination

---

## Objective 5: Apply protocols to OSI
Examples:
- **HTTP/HTTPS** → Application (OSI 7)
- **DNS** → Application (OSI 7)
- **TCP/UDP** → Transport (OSI 4)
- **IP** → Network (OSI 3)
- **Ethernet/Wi-Fi** → Data Link (OSI 2)
- **Cables/Radio signals** → Physical (OSI 1)

---

## Objective 6: Small business network design (basic)
Goal: separate important devices from guest Wi-Fi.

Example design:
- Staff computers on a Staff network
- Servers/printers on a Business network
- Guests on a Guest Wi-Fi network
- Firewall/router controls access between networks

---

## 🔗 Related Lab

- [Packet Tracer SOHO Lab](SOHO-Lab.md)

