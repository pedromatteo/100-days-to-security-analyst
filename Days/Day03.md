# Day 03 — OSI Model & Encapsulation

## Objectives

- Understand the OSI Model.
- Learn how data is encapsulated through the OSI layers.
- Understand the relationship between ICMP, IP, Ethernet Frames and ARP.
- Improve technical English.

---

## Study

Today I studied the OSI Model and how data travels across a network.

Topics covered:

- OSI Model
- Layer 2 (Data Link)
- Layer 3 (Network)
- Ethernet Frames
- IP Packets
- Encapsulation
- ARP
- Default Gateway
- Switch vs Router

---

## Practical Lab

Reviewed my Cisco Packet Tracer topology while analyzing the communication process through the OSI Model.

Activities performed:

- Identified the role of the Switch (Layer 2).
- Identified the role of the Router (Layer 3).
- Followed the packet path during a ping.
- Predicted what would happen if the destination belonged to another subnet.
- Understood why the computer drops the packet when no Default Gateway is configured.
- Learned that ARP only resolves MAC addresses inside the local network.

---

## English

Technical sentences practiced:

- The switch forwards Ethernet frames using MAC addresses.
- The router forwards packets between different networks.
- ARP resolves an IP address into a MAC address.
- The default gateway allows devices to communicate with other networks.
- An IP packet is encapsulated inside an Ethernet frame.

---

## Reflection

Today was the first day that the communication flow actually made sense to me.

Instead of memorizing protocols, I understood how they work together.

One of the biggest insights was realizing that ARP never searches for the destination device if it belongs to another network. Instead, it resolves the MAC address of the Default Gateway, allowing the router to forward the packet to the correct destination.

---

## Time

2 hours

---

## Status

- [x] Study
- [x] Practical Lab
- [x] English
- [x] Documentation