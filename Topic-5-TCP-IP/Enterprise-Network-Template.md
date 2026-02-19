# 🏢 Enterprise Network Diagram Template

---

## 🧱 Recommended Layout (Best Practice)

### Corporate Site (High-Level)
- **Edge / Internet**
  - ISP → NGFW (pair for redundancy if needed)
- **Core Layer**
  - Core switch(es) or L3 distribution (often redundant)
- **Access Layer**
  - Access switches feeding endpoints
- **Server Segment**
  - Servers connected near the core/distribution for performance and control

---

## 🗂 Suggested VLAN + Subnet Pattern (Example)

### Corporate VLANs
| VLAN | Purpose | Example Subnet |
|------|---------|----------------|
| 10 | DATA | 10.10.10.0/23 |
| 20 | VOIP | 10.10.20.0/24 |
| 30 | MGMT | 10.10.30.0/24 |
| 40 | WIFI | 10.10.40.0/23 |
| 50 | GUEST | 10.10.50.0/24 |

### Branch VLANs
| VLAN | Purpose | Example Subnet |
|------|---------|----------------|
| 10 | DATA | 10.20.10.0/24 |
| 50 | GUEST | 10.20.50.0/24 |

---

## 🔐 Simple Security Rules (Easy Wins)
- Guest WiFi cannot reach internal networks
- Management VLAN only accessible from admin devices
- Servers placed in a server VLAN/DMZ-style segment
- Inter-VLAN routing controlled by firewall or ACLs

