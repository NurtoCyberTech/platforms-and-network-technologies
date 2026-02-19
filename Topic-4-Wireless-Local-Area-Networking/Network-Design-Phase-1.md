# 🏢 Network Design Phase 1

---

## 📌 Scenario

As part of this assignment, I designed a scalable and secure network infrastructure for a growing company.

Instead of using the previous woodworking company scenario, I created a new fictional company:

**Desert Horizon Technologies**
Phoenix, Arizona

I served as the network engineer responsible for designing both:

- Corporate Headquarters (275 endpoints)
- Branch Office (75 endpoints)

---

## 🏗 Design Considerations

When designing the network, I accounted for:

- Current device count
- 10–30% projected growth
- Fault tolerance
- Wireless coverage
- Security segmentation

---

## 🖥 Endpoint Representation

The design includes:

- Desktop PCs
- Laptops
- VoIP phones
- Network printers
- Security cameras
- Wireless devices

---

## 🔌 Access Layer Planning

To support 275 endpoints at headquarters:

- Multiple 48-port Layer 2 switches were deployed
- Extra capacity included for growth
- Redundant uplinks implemented for fault tolerance

The branch office (75 endpoints) used:

- 24-port switches
- Centralized uplink to core network

---

## 📡 Wireless Integration

Wireless Access Points were:

- Strategically placed for coverage
- Connected to access layer switches
- Configured for secure authentication

---

## 🔐 Security Best Practices

The design incorporates:

- VLAN segmentation
- Secure wireless authentication
- Proper device placement
- Logical topology separation

---

## 📷 Network Diagram

![Network Diagram Phase 1](images/network-diagram-phase-1.png)



