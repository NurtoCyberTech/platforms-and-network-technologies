# 📡 Packet Tracer Part 4: Wireless Configuration

---

## 📌 Purpose of the Lab

This lab focused on configuring wireless infrastructure within an existing network.

The objective was to:

- Create a new VLAN for guest wireless access
- Configure wireless SSIDs
- Set encryption and authentication methods
- Adjust access point power levels
- Verify proper VLAN trunking between switches

---

## 🔧 What I Configured

### ➤ Guest Wireless VLAN

Created VLAN 240 named GUEST_WIFI and allowed it across trunk ports to ensure proper network segmentation.

---

### ➤ Access Point Configuration

Configured four access points with:

- Unique 5 GHz channels
- Proper coverage ranges
- Separate SSIDs for guest and internal use

Guest Network:
- SSID: Canyon_Guest
- No authentication

Internal Network:
- SSID: Canyon
- WPA2-PSK encryption
- Secure passphrase configured

---

## 🔐 Security Implementation

WPA2-PSK encryption was applied to internal devices, ensuring:

- Encrypted wireless communication
- Restricted access to authorized users

The guest network remained isolated in its own VLAN.

---

## ✅ Verification

To verify proper configuration:

- Ran CLI commands on switches
- Confirmed trunk VLANs
- Verified wireless device association
- Confirmed correct SSID and authentication settings

---

## 💭 Reflection

This lab demonstrated how wireless networking integrates with switching, VLAN segmentation, and security protocols.

It reinforced that wireless infrastructure is not separate from wired networking — it builds directly upon it.

