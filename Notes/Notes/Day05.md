# TCP & UDP Fundamentals

## Transport Layer

The Transport Layer is responsible for communication between applications.

It uses ports to identify which application should receive the data.

---

## TCP

### Characteristics

- Connection-Oriented
- Reliable
- Ordered delivery
- Retransmits lost segments
- Error checking

### Common Uses

- HTTP
- HTTPS
- SSH
- FTP
- Email

---

## UDP

### Characteristics

- Connectionless
- Faster
- No retransmission
- No delivery guarantee
- Lower overhead

### Common Uses

- DNS
- VoIP
- Video Streaming
- Online Games

---

## Three-Way Handshake

```text
Client                 Server

SYN  ----------------->

      <---------------  SYN + ACK

ACK  ----------------->
```

After this process, the TCP connection is established.

---

## Common Ports

| Port | Protocol |
|------|----------|
| 80 | HTTP |
| 443 | HTTPS |
| 53 | DNS |

---

## TCP vs UDP

| TCP | UDP |
|-----|-----|
| Reliable | Fast |
| Connection-Oriented | Connectionless |
| Retransmits lost segments | Does not retransmit |
| Ordered delivery | No ordering guarantee |

---

## Key Terms

- TCP
- UDP
- Port
- Segment
- Handshake
- Connection
- Reliability
- Retransmission
- Socket