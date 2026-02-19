# 🖥 Packet Tracer Lab: Switching & VLAN Configuration

---

## 🏗 Scenario Overview

With the network cabling complete, the next phase of implementation focused on configuring the switches.

In this lab, I configured three switches using the Cisco Command Line Interface (CLI). The goal was to ensure proper communication between devices while implementing VLAN segmentation for better organization and security.

Switch configuration is critical because switches control how devices communicate inside a LAN.

---

## 🔧 Skills Practiced

During this lab, I configured:

- Hostnames
- Default gateways
- VLANs
- Access ports
- Trunk ports
- Management interfaces
- Verification using show commands

This lab reinforced how switching works at Layer 2 of the OSI model.

---

# 🖥 Switch Configuration Breakdown

## 1️⃣ Hostname & Basic Settings

Each switch was assigned:
- A unique hostname
- A default gateway
- Domain lookup disabled

This ensures easier management and prevents unnecessary delays when mistyping commands.

---

## 2️⃣ VLAN Creation

Two VLANs were created:

- VLAN 2 → DATA
- VLAN 4 → MANAGEMENT

VLAN 2 was used for general device communication.
VLAN 4 was reserved for management traffic.

This segmentation helps isolate sensitive management traffic from normal data traffic.

---

## 3️⃣ Management Interface Configuration

Each switch was given:
- An IP address on VLAN 4
- A subnet mask of 255.255.255.0

This allows remote management of the switch.

---

## 4️⃣ Access Ports

Certain FastEthernet ports were configured as:

- Access mode
- Assigned to VLAN 2

Access ports connect end devices like PCs.

---

## 5️⃣ Trunk Ports

Connections between switches were configured as trunk ports.

Trunk ports:
- Carry multiple VLANs
- Allowed only VLAN 2 and VLAN 4
- Included interface descriptions for clarity

Trunks are essential when VLAN traffic must travel between switches.
---

## 🔀 How Trunking Works

When multiple VLANs need to travel between switches, trunk ports are used.

    SWITCH 1                SWITCH 2
  +-----------+           +-----------+
  | VLAN 2    |-----------| VLAN 2    |
  | VLAN 4    |===========| VLAN 4    |
  +-----------+   TRUNK   +-----------+

A trunk port carries traffic for multiple VLANs over a single connection.

Without trunking:
- VLAN 2 devices on Switch 1 could not communicate with VLAN 2 devices on Switch 2.
- VLAN segmentation would break across switches.

Trunking keeps VLAN structure consistent across the network.

---

# 🧪 Verification Commands Used

To confirm the configuration, I used:

- `show ip interface brief`
- `show interfaces status`
- `show interfaces trunk`
- `show vlan brief`
- `show running-config`

These commands verify VLAN assignments, trunk configuration, and interface status.

---

## 💡 What This Lab Taught Me

This lab helped me understand:

- How switching works at Layer 2
- The importance of VLAN segmentation
- How trunking allows VLAN communication between switches
- How to verify configurations using CLI commands
- Why proper documentation and naming conventions matter

It also reinforced how theoretical concepts like broadcast domains and segmentation apply in real network environments.

