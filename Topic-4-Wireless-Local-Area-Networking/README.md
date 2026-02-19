---

## 📡 Topic 4: Wireless LAN (WLAN)

- 📖 [Theory & Discussion](Topic-4-WLAN/README.md)
- 🏢 [Network Design Phase 1](Topic-4-WLAN/Network-Design-Phase-1.md)
- 📡 [Packet Tracer Wireless Lab](Topic-4-WLAN/Packet-Tracer-Wireless-Lab.md)

---

## 📌 Introduction

Wireless networking builds on everything learned from the OSI model and Ethernet-based communication.

Instead of replacing wired networking principles, wireless technologies extend them. The same ideas — IP addressing, routing, switching, and security — still apply. The difference is how devices physically connect and communicate over radio frequencies instead of cables.

This topic focused on understanding wireless performance, security protocols, and scalable network design.

---

## 🎯 Learning Objectives

By the end of this topic, I was able to:

- Identify factors that affect wireless performance
- Apply wireless security configurations
- Design scalable wireless network architectures
---

## 🏠 Wireless Router vs Wireless Access Point (SOHO Environment)

In a small office home office (SOHO) environment, both wireless routers and wireless access points provide wireless connectivity — but they serve different roles.

### 🔹 Wireless Router

A wireless router combines multiple networking functions into one device:
- Routing (connecting to the internet)
- Switching (connecting wired devices)
- DHCP server
- Wireless access point

It is essentially an “all-in-one” solution.

### 🔹 Wireless Access Point (AP)

A wireless access point only provides wireless connectivity.  
It connects back to a switch or router and extends the wireless network.

It does NOT perform routing or DHCP unless specifically configured.

---

### ⚖ Advantages of a Single Integrated Device

- Lower cost
- Easier setup
- Ideal for small networks
- Fewer devices to manage

### ⚖ Disadvantages

- Limited scalability
- Less fault tolerance
- Reduced performance under heavy load
- Harder to upgrade individual components

In larger networks, separating routing, switching, and wireless access allows better scalability and performance.
---

## 📶 Evolution of Wireless Standards

Wireless technology has significantly evolved from early standards like 802.11a and 802.11b to modern standards such as:

- **802.11ac (Wi-Fi 5)**
- **802.11ax (Wi-Fi 6)**

Earlier standards offered lower speeds and operated primarily in limited frequency ranges.

Modern standards provide:
- Higher data throughput
- Better range
- Improved efficiency
- Enhanced support for multiple devices

---

## 🚀 Example Advancement: OFDMA

One major advancement in Wi-Fi 6 is **OFDMA (Orthogonal Frequency Division Multiple Access).**

### What It Does:
Instead of one device using the entire channel at a time, OFDMA divides the channel into smaller sub-channels so multiple devices can transmit simultaneously.

### Why It Matters:
- Reduces latency
- Improves performance in high-density environments
- Increases overall network efficiency

This is especially important in environments like offices, campuses, or apartments where many devices connect at once.

