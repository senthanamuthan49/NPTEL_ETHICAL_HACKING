# NPTEL Ethical Hacking — Weekly Progress Record

---

## Week 0 — Completed ✅

**Date Analyzed**: 2026-10-22

### Questions Covered
12 questions (Q1–Q12): 8 single-correct MCQs, 2 multiple-correct MCQs, 2 numerical fill-in-the-blank.

### Main Concepts
| Module | Topics |
|--------|--------|
| Ethical Hacking Foundations | Definition, authorization, pen testing vs security testing, White/Black/Gray box models, Tiger box, legal boundaries |
| Endpoint Security | Antivirus vs firewall (defensive tools) vs virus/malware (threats), detection pipelines, host defense architecture |
| Network Types & Switching | LAN/WAN, circuit switching vs packet switching, virtual circuit vs datagram, store-and-forward |
| Internetworking Devices | Hub (L1) vs Repeater (L1) vs Switch (L2) vs Router (L3), collision vs broadcast domains |
| OSI & TCP/IP Models | 7-layer OSI model, 4-layer TCP/IP model, layer functions, PDU names, encapsulation/decapsulation |
| Transport Layer | TCP (reliable, connection-oriented) vs UDP (unreliable, connectionless), port multiplexing |
| Application Protocols & Ports | SMTP (25), HTTP (80), FTP (20/21), POP3 (110), HTTPS (443), SNMP (161) |
| IP Addressing | IPv4 (32-bit, dotted-decimal, octet range 0–255), IPv6 (128-bit, hexadecimal), address validation |
| Linux Networking | ifconfig vs ipconfig, ip addr, netstat, traceroute, packet sniffers (Wireshark, tcpdump) |

### Key Facts to Remember
1. Ethical hacking requires **explicit authorization** from the system owner
2. OSI = **7 layers**, TCP/IP = **4 layers**
3. **Router** connects different networks (Layer 3); **Switch** operates within a network (Layer 2)
4. IPv4 = **32 bits** (4 octets, each 0–255); IPv6 = **128 bits** (8 hextets)
5. TCP = **reliable, connection-oriented** (3-way handshake); UDP = **unreliable, connectionless**
6. SMTP = **send** email (port 25/587); POP3 = **retrieve** email (port 110)
7. HTTP = port **80**; HTTPS = port **443**; FTP = ports **20** (data) / **21** (control)
8. Linux: `ifconfig` (network config); Windows: `ipconfig` — different commands!
9. Transport layer provides **end-to-end** reliability; Data Link provides **hop-to-hop** framing
10. An IP octet value of **256 or higher is always invalid** (exceeds 8-bit maximum of 255)

### Important Misconceptions to Avoid
- ❌ Virus and malware are NOT security tools — they are threats
- ❌ `ipconfig` is NOT a Linux command — it's Windows (`ifconfig` or `ip addr` on Linux)
- ❌ IP (Internet Protocol) is NOT a transport layer protocol — it's network layer (Layer 3)
- ❌ Ethernet is NOT a transport layer protocol — it's data link layer (Layer 2)
- ❌ 255 in an IP address is NOT automatically invalid — 255 is within the valid range 0–255
- ❌ Data Link layer does NOT provide end-to-end reliability — only hop-to-hop
- ❌ A switch does NOT connect different networks — a router does
- ❌ OSI model has 7 layers, NOT 4 — TCP/IP has 4 layers

### Topics to Revisit Before Final Exam
- [ ] IP header fields (VER, HLEN, TTL, Protocol, Checksum) — high exam frequency
- [ ] TCP 3-way handshake and SYN flood attacks
- [ ] Subnetting and CIDR notation (not yet covered but foundational)
- [ ] Email security (SPF, DKIM, DMARC)
- [ ] Encapsulation overhead calculation (TFTP example from lectures)

### Unresolved Ambiguities
- Q6: Modern Linux distributions deprecate `ifconfig` in favor of `ip addr show`. The course uses `ifconfig` which is still valid but from the older `net-tools` package.
- Q11: Option `b` (255.102.3.25) is technically valid but may confuse students who associate 255 with broadcast addresses. Context matters (255 is valid as an octet value, but 255.255.255.255 has special meaning as a broadcast).

### Suggested Revision Priorities
1. **HIGH**: OSI layers, TCP vs UDP, common port numbers, IP address validation
2. **MEDIUM**: Networking devices comparison, ethical hacking definitions, Linux commands
3. **LOW**: Circuit vs packet switching, virtual circuit vs datagram (foundational but less frequently tested)

---

*Next: Week 1 — awaiting assignment questions*
