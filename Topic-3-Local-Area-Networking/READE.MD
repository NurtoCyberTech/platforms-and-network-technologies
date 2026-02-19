# 🌐 Topic 3: Local Area Networking (LAN)

---

## 📌 Introduction

In this topic, I learned how devices communicate within a small geographical area, such as an office building or campus. 

A Local Area Network (LAN) connects computers, printers, servers, and other devices so they can share data and resources efficiently.

Unlike wide-area networks (WANs), LANs are typically limited to one building or a small group of buildings.

---

## 🎯 Objectives

By the end of this topic, I was able to:

- Identify the essential components required for a LAN to function
- Install and configure a basic LAN
- Implement and manage VLANs
- Understand how data switching works within a network

---

# 🧩 Essential LAN Components

A functioning LAN typically includes:

- **End devices** (PCs, laptops, printers)
- **Switches** (connect devices within the LAN)
- **Routers** (connect the LAN to other networks)
- **Cabling or wireless access points**
- **Network Interface Cards (NICs)**

Each component plays a specific role in ensuring communication flows correctly.

---

# 📺 Reflection Questions (Class Discussion)

## 1️⃣ Besides using a wired NIC, how can a client connect to a switch?

A client can connect wirelessly using a wireless network adapter. This allows the device to connect through a wireless access point that is connected to the switch.

---

## 2️⃣ How can two switches be connected if they are far apart?

If switches are located far from each other, they can be connected using fiber optic cables. Fiber supports long distances and provides high-speed communication without signal degradation.

---

## 3️⃣ What does a router do in a network?

A router connects different networks together. It directs traffic between networks, such as connecting a LAN to the internet. It makes routing decisions based on IP addresses.

---

## 4️⃣ What is the purpose of a firewall?

A firewall protects the network by filtering traffic. It blocks unauthorized access and allows only approved traffic to pass through. It acts as a security barrier between trusted and untrusted networks.

---

# 🔀 Understanding VLANs

A VLAN (Virtual Local Area Network) allows a single physical switch to be logically divided into separate broadcast domains.

Instead of all devices being in one large network (a flat topology), VLANs separate devices into smaller logical groups.

For example:
- VLAN 2 → DATA
- VLAN 4 → MANAGEMENT

Even though the devices share the same physical switch, they behave as if they are on separate networks.

---

## 🔐 Why VLANs Improve Security

In a flat network:
- Every device can communicate with every other device.
- Broadcast traffic reaches all devices.

With VLANs:
- Traffic is isolated.
- Broadcast domains are segmented.
- Sensitive devices (like management systems) are separated.

This reduces security risks and improves network performance.

---

## 🏢 Business Example

Imagine a company with:
- Sales department
- HR department
- IT management

By placing each department into its own VLAN:
- Sensitive HR data is isolated.
- Broadcast traffic is reduced.
- Policies can be applied per department.

This improves both organization and security.

