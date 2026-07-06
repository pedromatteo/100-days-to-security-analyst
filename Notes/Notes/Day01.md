# Network Fundamentals

## What is Networking?

A computer network is a group of two or more devices connected together to exchange information and share resources. Networks allow computers, smartphones, servers, printers, and other devices to communicate using standard protocols.

---

## Internet

### What is it?

The Internet is a global network that connects millions of private and public networks around the world.

### World Wide Web (WWW)

The World Wide Web is a service that runs on the Internet and allows users to access websites through a web browser.

The WWW was invented by **Tim Berners-Lee** in 1989.

---

## IP Address

### What is it?

An IP (Internet Protocol) address is a unique numerical identifier assigned to a device on a network.

### Types

- Public IP Address
- Private IP Address

### IPv4

An IPv4 address is divided into **4 octets**.

Each octet ranges from 0 to 255.

Example:

192.168.1.10



---

## MAC Address

### What is it?

A MAC (Media Access Control) address is a unique physical address assigned to a network interface by the manufacturer.

Unlike an IP address, the MAC address normally does not change.

The first 3 bytes of a MAC address identify the manufacturer (Organizationally Unique Identifier - OUI), while the last 3 bytes uniquely identify the network interface.

It is represented in hexadecimal format (0-9 and A-F).

Example:

00:1A:2B:FF:09:AE

Where the **00:1A:2B** identifies the device manufacturer of the network interface (Apple, Dell, Intel, Cisco) and **FF:09:AE** is the unique address of the network interface.


---

## Ping

### What is it?

Ping is a command used to test connectivity between two devices on a network.

### Protocol

Ping uses the **ICMP (Internet Control Message Protocol)**.

Example:

```bash
ping 10.10.10.10
```

---

## Exercises Completed

- What does IP stand for?
- What is an octet?
- Difference between public and private IP addresses.
- What does MAC stand for?
- MAC spoofing exercise.
- What protocol does ping use?
- Ping command syntax.

---

## Key Terms

- Network
- Internet
- WWW
- IP Address
- IPv4
- Octet
- MAC Address
- ICMP
- Ping
- Host
- Packet
- Frame
- Broadcast