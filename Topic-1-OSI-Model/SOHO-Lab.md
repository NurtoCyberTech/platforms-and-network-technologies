# 🖥 Packet Tracer Lab: Building a SOHO Network

---

## 🏢 The Scenario

After learning how the OSI model structures network communication, I wanted to see what that looked like in practice.

In this lab, I stepped into the role of an IT consultant for a small startup called **Sonoran Timber Studio**, a custom woodworking business based in Phoenix, Arizona.

The company operates with fewer than ten employees but is preparing to grow. My task was to update and test their Small Office / Home Office (SOHO) network to support new devices and ensure reliable connectivity.

Instead of just reading about network layers, this lab required me to actually build and configure part of the network myself.

---

## 🛠 Stepping Into the Network

I began by exploring both views in Packet Tracer:

- **Physical View** – showing the office layout and device placement  
- **Logical View** – showing how devices are connected in the topology  

Switching between these views helped me understand how real-world placement relates to network structure.

---

### ➤ Removed an Existing Device

In the Logical layout view:

- Removed the previous Sales Laptop from the topology

This reinforced how network diagrams must reflect real-world changes in personnel and equipment.

---

### ➤ Configured Wireless Capability

For the new laptop:

- Powered the device off
- Removed the wired Ethernet interface
- Installed a wireless network adapter
- Powered the device back on
- Renamed the device to reflect a user workstation

This demonstrated how hardware configuration directly affects network connectivity.

---

### ➤ Connected the PC to the Router

The PC was connected using a copper straight-through cable to the Wi-Fi router.

This allowed the PC to communicate through the router and access network resources.

---

## 🌐 IP Configuration and Testing

To verify proper configuration:

- Enabled DHCP on the PC
- Confirmed automatic IP address assignment
- Opened the web browser
- Tested connectivity by accessing an external website

Successful page loading confirmed that:

- The router was functioning as a DHCP server
- Devices were properly connected
- Internet connectivity was operational

---

## 💡 Key Concepts Reinforced

This lab helped strengthen my understanding of:

- The difference between Physical and Logical network layouts
- DHCP and automatic IP addressing
- Wired vs wireless configurations
- Basic SOHO network structure
- Network verification and troubleshooting

This exercise connected the OSI model theory to real-world network implementation.

---

## 📷 Completed Network Topology

![SOHO Network Topology](images/soho-topology.png)

