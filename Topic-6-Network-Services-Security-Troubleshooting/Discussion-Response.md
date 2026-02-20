# 🧠 Discussion Responses

---

## 🔍 Using the OSI Model for Troubleshooting

The OSI model is often introduced as a theory, but its real power becomes clear during troubleshooting.

When a connectivity issue occurs, administrators need a structured way to isolate the problem. The OSI model provides that structure.

Instead of guessing, we analyze layer by layer:

- Layer 1 – Is the physical connection active?
- Layer 2 – Is the device in the correct VLAN?
- Layer 3 – Does it have the correct IP and gateway?
- Layer 7 – Is the application or service responding?

For example, if a user cannot access a website, the issue could be:
- A disconnected cable
- Incorrect IP configuration
- A DNS resolution failure

By moving through the layers logically, problems can be narrowed down efficiently.

In lab environments, applying the OSI model prevented random troubleshooting. It created a repeatable, systematic method.

---

## 🌐 Understanding DHCP and Static IP Addressing

### The DHCP Process (DORA)

When a device connects to a network, DHCP assigns it an IP address automatically through four steps:

1. Discover – The device broadcasts for an IP.
2. Offer – The DHCP server responds with an available address.
3. Request – The device requests that address.
4. Acknowledge – The server confirms and assigns it.

This process allows networks to scale efficiently.

---

### Static vs DHCP

Static IP addresses are manually configured and remain constant.

Best for:
- Servers
- Printers
- Network infrastructure devices

Advantages:
- Predictable
- Easier for DNS and service mapping

Disadvantages:
- Manual configuration required
- Less scalable

DHCP automates addressing.

Best for:
- Workstations
- Laptops
- Guest devices

Advantages:
- Easy to manage
- Reduces errors
- Scales efficiently

In real-world networks, both methods are used strategically.

