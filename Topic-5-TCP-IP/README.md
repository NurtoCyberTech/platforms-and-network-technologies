# 🌐 Topic 5: Understanding TCP/IP and Device Addressing

- 📖 [Theory & Concepts](Topic-5-TCP-IP/README.md)
- 🏢 [Network Design Phase 2](Topic-5-TCP-IP/Network-Design-Phase-2.md)
- 📊 [IPv4 Subnetting Reflection](Topic-5-TCP-IP/IPv4-Subnetting-Reflection.md)

---

## 📌 Why TCP/IP Matters

In this topic, I explored how devices communicate across networks using the TCP/IP model and IPv4 addressing.

One major takeaway is this:

Without proper addressing, data would have no idea where to go.

Just like mail needs a destination, network traffic depends on IP addresses to move efficiently and accurately between devices.

---

## 🎯 Learning Objectives

- Design a TCP/IP-based network
- Identify public vs. private IP addresses
- Understand subnet masks and default gateways
- Apply IPv4 subnetting concepts

---

# 🧭 Explaining IP Addresses in Simple Terms

One helpful way to understand an IP address is to compare it to a street address.

A street address has:
- A street name (identifies the neighborhood)
- A house number (identifies the specific home)

An IP address works in a similar way:

- The **network portion** identifies the network
- The **host portion** identifies the specific device

This analogy works well because it shows that an IP address is not random — it has structure.

Thinking of IP addresses this way helps clarify why two devices can only communicate directly if they are on the same “street” (network). Otherwise, they need help from a router.

Another way to think about it is like an apartment building:

- The building address = network
- The apartment number = host

This analogy works especially well in larger networks with many devices.

---

# 🌐 Subnet Masks and Default Gateways

## What Does a Subnet Mask Do?

A subnet mask separates the network portion of an IP address from the host portion.

It tells a device:
- Which part of the IP represents the network
- Which part represents the individual device

Without a subnet mask, a device wouldn’t know whether another IP address is local or remote.

---

## What Is a Default Gateway?

The default gateway is the router a device sends traffic to when it needs to reach a different network.

If two devices are on the same network, they can communicate directly.

If they are on different networks:
- The device sends the data to the default gateway
- The router forwards it toward its destination

The default gateway acts like an exit door from the local network.

---

## 💡 What I Learned

Understanding IP addressing made networking feel logical instead of confusing.

Everything depends on:
- Proper address structure
- Subnet masks
- Routing decisions

Once those pieces clicked, network communication started making sense.

---

## 🧩 OSI vs TCP/IP (How they match up)

### OSI Model (7 layers)
Application
Presentation
Session
Transport
Network
Data Link
Physical

### TCP/IP Model (4 layers)
Application
Transport
Internet
Network Access

### How they map
| OSI Layer | TCP/IP Layer |
|----------|--------------|
| Application + Presentation + Session | Application |
| Transport | Transport |
| Network | Internet |
| Data Link + Physical | Network Access |

---

## 🧮 Subnetting Practice (Worked Example)

### Example: Split 192.168.10.0/24 into 4 equal subnets

A `/24` network has 256 addresses total (0–255).
To create 4 subnets, I “borrow” 2 bits (because 2 bits = 4 subnets).

So the new prefix becomes:

- **/24 + 2 = /26**

Each `/26` subnet has:
- 64 total addresses (because 256 / 4 = 64)
- 62 usable host addresses (network + broadcast are reserved)

#### The 4 subnets:
1. **192.168.10.0/26**
   - Usable: 192.168.10.1 – 192.168.10.62
   - Broadcast: 192.168.10.63

2. **192.168.10.64/26**
   - Usable: 192.168.10.65 – 192.168.10.126
   - Broadcast: 192.168.10.127

3. **192.168.10.128/26**
   - Usable: 192.168.10.129 – 192.168.10.190
   - Broadcast: 192.168.10.191

4. **192.168.10.192/26**
   - Usable: 192.168.10.193 – 192.168.10.254
   - Broadcast: 192.168.10.255

✅ This example helped me see subnetting as a pattern, not something to memorize.

