# 🛠 Packet Tracer Part 2: Network Infrastructure Upgrade

---

## 🏢 From SOHO to Small Business

Sonoran Timber Studio has grown rapidly and outgrown its original SOHO setup.

The temporary Wi-Fi router solution is no longer sufficient. The network now requires dedicated switches, patch panels, access points, servers, and a business-class router.

This lab simulated a real-world upgrade weekend where the old equipment is removed and replaced with structured infrastructure.

---

## 🔄 Decommissioning the Old Equipment

The first step was removing the consumer-grade Wi-Fi router from the server room (MDF).

Upgrading infrastructure often begins with removing outdated hardware before installing enterprise-level devices.

---

## 🔌 Patching the Network

Much of the cabling was already installed, but patching remained.

Using copper straight-through cables, I connected:

- Patch panel ports to the appropriate switch ports
- Access points to designated switch interfaces
- Inter-switch uplinks for internal communication
- Server connections to core switches
- IT workstation to the access switch
- Switch to router for upstream routing
- Router to DSL modem for WAN connectivity

This required careful navigation between the Physical and Logical views to ensure correct port mapping.

---

## 🔗 Inter-Switch Connectivity

Creating connections between switches allows traffic to flow across different segments of the network.

These uplinks are critical for maintaining internal communication across departments and devices.

---

## 🌐 Router and WAN Connection

The router was connected to the DSL modem, establishing the path to the internet.

This demonstrated how local networks connect to wide-area networks (WANs).

---

## ✅ Verification

After completing cabling:

- I inspected connections in both Logical and Physical views
- Enabled port labels for verification
- Confirmed all connections were active

This final check ensured that the infrastructure was correctly implemented.

---

## 💭 Reflection

This lab reinforced how structured cabling and proper patching are foundational to reliable networking.

It also highlighted the importance of physical organization in network design — something often overlooked when focusing only on logical configurations.

Upgrading from a SOHO environment to structured infrastructure showed how scalability and planning impact real-world network deployments.

