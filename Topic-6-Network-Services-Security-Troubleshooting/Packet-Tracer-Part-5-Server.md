# 🖥 Packet Tracer Part 5: Configuring Core Network Services

---

## 🏗 Lab Overview

With network hardware configured, the focus shifted to enabling core services that allow devices to function properly.

This lab required configuring:

- VLAN access ports on switches
- Static IP addresses for servers
- DHCP pools for internal and guest networks
- DNS records for internal name resolution
- Command-line verification testing

---

## 🔧 Switch Configuration

On the primary switch:

- Configured access ports for the server and IT laptop
- Assigned them to the correct VLAN
- Added interface descriptions
- Saved the running configuration

This reinforced VLAN segmentation and proper documentation practices.

---

## 🖥 Server Configuration

The server was assigned a static IP address to ensure consistency.

Then:

- DHCP service was enabled
- A primary pool was created for internal devices
- A guest Wi-Fi pool was created
- DNS service was activated
- A records were created for internal hostnames

This demonstrated how centralized services support the entire network.

---

## 💻 IT Laptop Configuration

The IT laptop received:

- A static IP address
- Default gateway
- Internal DNS server

This ensured stable administrative access.

---

## 🔎 Verification & Testing

Testing involved:

- show running-config
- show vlan brief
- ipconfig
- nslookup
- ping

These tools verified:

- Proper VLAN configuration
- Accurate IP assignment
- Functional DNS resolution
- Successful connectivity

---

## 💡 Reflection

This lab reinforced how DHCP and DNS are foundational to network operations. Without these services, devices cannot communicate effectively.

It also strengthened my understanding of structured troubleshooting using command-line tools.

