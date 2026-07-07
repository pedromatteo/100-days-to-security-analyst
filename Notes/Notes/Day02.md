# Cisco Packet Tracer - Basic Network Lab

## Objective

Build a simple LAN and understand how devices communicate on the same network.

---

## Network Topology

PC0 ---- Switch ---- PC1

Later:

            Switch
         /     |     \
      PC0    PC1    PC2

---

## Configuration

PC0

- IP Address: 192.168.1.10
- Subnet Mask: 255.255.255.0

PC1

- IP Address: 192.168.1.20
- Subnet Mask: 255.255.255.0

PC2

- IP Address: 192.168.1.30
- Subnet Mask: 255.255.255.0

---

## Tests

### Successful Ping

Command:

```bash
ping 192.168.1.20
```

Result:

- Packets Sent: 4
- Packets Received: 4
- Packet Loss: 0%

---

## Different Subnet Test

Changed PC2 IP:

192.168.2.30

Result:

The packet was dropped because the destination device was on another subnet and no Default Gateway was configured.

---

## Router vs Switch

### Switch

- Connects devices inside the same Local Area Network.
- Forwards Ethernet Frames based on MAC Addresses.

### Router

- Connects different networks.
- Routes packets using IP Addresses.
- Uses the Default Gateway to forward traffic outside the local network.

---

## ARP (Address Resolution Protocol)

ARP is responsible for discovering the MAC Address associated with an IP Address.

Example:

The computer wants to communicate with:

192.168.1.20

Before sending the packet, it checks its ARP Table.

If the MAC Address is already known:

- The Frame is created immediately.

If it is unknown:

- An ARP Request is broadcast.
- The destination device replies with its MAC Address.
- The mapping is stored in the ARP Table for future communication.

Example from the lab:

Internet Address      Physical Address      Type

192.168.1.20          000c.cf57.21d5        dynamic

192.168.1.30          0004.9aad.24c3        dynamic

The "dynamic" type means the entries were learned automatically by ARP.

---

## Ethernet Frame

A Frame is the data structure transmitted on an Ethernet network.

It contains:

- Source MAC Address
- Destination MAC Address
- Payload (IP Packet)
- Error checking information (FCS)

The IP packet is encapsulated inside the Ethernet Frame before being transmitted across the network.

---

## What I Learned

- Devices on the same subnet communicate directly through a switch.
- Devices on different subnets require a router (Default Gateway).
- Ping uses ICMP.
- ARP translates IP Addresses into MAC Addresses.
- Ethernet Frames carry IP packets across the local network.
- Packet Tracer Simulation Mode helps visualize how communication happens.