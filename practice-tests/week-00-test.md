# NPTEL Ethical Hacking — Week 0 Practice Exam

**Course**: NPTEL Ethical Hacking (Prof. Indranil Sen Gupta, IIT Kharagpur)  
**Exam Module**: Week 0 — Course Prerequisites, Networking Fundamentals & Introduction to Ethical Hacking  
**Target File**: `week-00-test.md`  
**Total Questions**: 20  
**Difficulty Distribution**: 5 Easy | 10 Moderate | 5 Difficult  
**Question Formats**: Single-correct MCQ, Multiple-correct MCQ, True/False, Scenario-Based  

---

# Part 1: Questions Only (No Answers)

> **Instructions**: Read each question carefully. Pay close attention to difficulty tags, question type tags, and whether questions specify **Single-correct** or **Multiple-correct**. Do not scroll down to Part 2 until you have completed your initial attempt.

---

### Question 1
- **Difficulty**: [Easy]
- **Type**: [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

Which of the following defines the fundamental boundary that distinguishes an ethical hacker from a malicious black-hat hacker?

- **A.** Ethical hackers only use automated open-source reconnaissance tools, whereas malicious hackers write custom binary exploitation payloads.
- **B.** Ethical hackers possess explicit, prior written authorization from the system owner and operate strictly within a defined scope of engagement.
- **C.** Ethical hackers limit their penetration testing strictly to external perimeter IP addresses and are legally forbidden from inspecting internal network segments.
- **D.** Ethical hackers modify system logs and disable audit daemon processes during an assessment to prevent accidental alerts.

---

### Question 2
- **Difficulty**: [Easy]
- **Type**: [True-False]
- **Selection**: Exactly ONE option is correct

State whether the following statement is True or False:

*"An IPv6 address comprises 128 bits, organized into 8 groups of 16-bit hexadecimal values separated by colons, yielding an address space of $2^{128}$ unique identifiers."*

- **A.** True
- **B.** False

---

### Question 3
- **Difficulty**: [Easy]
- **Type**: [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

A network security administrator is configuring a boundary firewall to permit standard, unencrypted Hypertext Transfer Protocol (HTTP) web browsing traffic from intranet hosts to public web servers. Which default destination port number must be allowed through the firewall rule?

- **A.** Port 21
- **B.** Port 25
- **C.** Port 80
- **D.** Port 443

---

### Question 4
- **Difficulty**: [Easy]
- **Type**: [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

Which of the following are categorized as defensive security applications or mechanisms designed to protect workstations and enterprise infrastructure from unauthorized activity or compromise? *(Select ALL that apply)*

- **A.** Stateful Packet Inspection Firewall
- **B.** Trojan Horse
- **C.** Signature-based Antivirus Software
- **D.** Host-based Intrusion Prevention System (HIPS)
- **E.** Ransomware

---

### Question 5
- **Difficulty**: [Easy]
- **Type**: [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

A cybersecurity analyst operating an Ubuntu Linux workstation needs to inspect the current network interface configurations, including IP addresses, netmasks, broadcast addresses, and hardware (MAC) addresses. Which traditional Linux command-line utility provides this information?

- **A.** `ipconfig /all`
- **B.** `ifconfig -a`
- **C.** `netstat -rn`
- **D.** `tracert 127.0.0.1`

---

### Question 6
- **Difficulty**: [Moderate]
- **Type**: [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

An enterprise network engineer connects 16 employee desktop computers to an unmanaged 16-port Layer-2 Ethernet switch. Assuming no Virtual LANs (VLANs) or routers are configured, how many **collision domains** and how many **broadcast domains** exist across this local network setup?

- **A.** 1 collision domain, 16 broadcast domains
- **B.** 16 collision domains, 1 broadcast domain
- **C.** 1 collision domain, 1 broadcast domain
- **D.** 16 collision domains, 16 broadcast domains

---

### Question 7
- **Difficulty**: [Moderate]
- **Type**: [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

Which of the following statements accurately compare the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP) at the Transport Layer? *(Select ALL that apply)*

- **A.** TCP provides reliable, ordered data delivery using sequence numbers, acknowledgments, and automatic retransmissions of lost packets.
- **B.** UDP establishes a three-way handshake before transmitting user data to negotiate buffer window sizes.
- **C.** UDP is a connectionless protocol that sends independent datagrams without establishing a connection or maintaining connection state.
- **D.** TCP is an unacknowledged protocol designed for lightweight queries such as DNS lookups, where connection overhead must be minimized.
- **E.** TCP implements end-to-end flow control and congestion avoidance mechanisms to prevent a fast sender from overwhelming a slow receiver or congested network links.

---

### Question 8
- **Difficulty**: [Moderate]
- **Type**: [Scenario-Based] [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

**Scenario**: A financial corporation hires an external cybersecurity firm. Under the contract, the consultants not only simulate attacks to legally break into the company's internal and external network systems to discover exploitable vulnerabilities, but they also review the company's written security policies, evaluate employee procedures, and provide concrete remediation recommendations and architectural solutions to secure the network.

According to NPTEL course definitions (distinguishing testing methodologies), this engagement is most precisely classified as:

- **A.** A Penetration Test
- **B.** A Security Test
- **C.** A Black Box Model
- **D.** Port Scanning

---

### Question 9
- **Difficulty**: [Moderate]
- **Type**: [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

In standard IPv4 dotted-decimal notation, each address consists of four decimal octets separated by periods. Which of the following IP addresses are **INVALID** IPv4 addresses? *(Select ALL that apply)*

- **A.** `172.16.254.1`
- **B.** `192.168.1.256`
- **C.** `10.200.315.44`
- **D.** `198.51.100.8.2`
- **E.** `224.0.0.1`

---

### Question 10
- **Difficulty**: [Moderate]
- **Type**: [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

Both the Data Link Layer (Layer 2) and the Transport Layer (Layer 4) of the OSI model can perform error detection, flow control, and retransmission. What is the fundamental conceptual difference between their reliability responsibilities?

- **A.** The Data Link Layer provides end-to-end message delivery between source and destination applications, whereas the Transport Layer operates only over a single physical cable hop.
- **B.** The Data Link Layer ensures error-controlled frame transmission over a single point-to-point physical link between adjacent nodes, whereas the Transport Layer guarantees end-to-end reliable message delivery across multiple intermediate network hops.
- **C.** The Data Link Layer relies exclusively on software sockets, whereas the Transport Layer is implemented strictly in hardware network interface cards (NICs).
- **D.** The Data Link Layer reorders out-of-order packets traveling across the Internet, while the Transport Layer converts bits into electrical signals.

---

### Question 11
- **Difficulty**: [Moderate]
- **Type**: [True-False]
- **Selection**: Exactly ONE option is correct

State whether the following statement is True or False:

*"In the Datagram approach to packet switching, intermediate network routers establish a dedicated physical circuit before any packets are transmitted, guaranteeing that all packets traverse the exact same path and arrive strictly in sequential order without carrying full destination addresses."*

- **A.** True
- **B.** False

---

### Question 12
- **Difficulty**: [Moderate]
- **Type**: [Scenario-Based] [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

**Scenario**: A healthcare company engages an ethical hacker to conduct a realistic adversary simulation. The client provides the tester with only the company's public domain name (`healthcorp-example.com`). The tester is given **no** internal network diagrams, **no** IP address ranges, **no** system architecture documentation, and **no** user credentials. The burden of identifying target hosts, network topology, and software versions rests entirely on the tester.

Which penetration-testing model does this scenario describe?

- **A.** White Box Model
- **B.** Gray Box Model
- **C.** Black Box Model
- **D.** Clear Box Model

---

### Question 13
- **Difficulty**: [Moderate]
- **Type**: [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

Which of the following statements regarding Internet electronic mail protocols are technically correct? *(Select ALL that apply)*

- **A.** Simple Mail Transfer Protocol (SMTP) is a "push" protocol primarily used to transfer emails from a client to a mail server, and to relay emails between intermediate Mail Transfer Agents (MTAs).
- **B.** Post Office Protocol version 3 (POP3) is a server-to-server routing protocol that runs on TCP port 25 to deliver outgoing email across WAN boundaries.
- **C.** Internet Message Access Protocol (IMAP) is a "pull" protocol that permits client applications to access, organize, and manage email folders residing directly on the remote mail server.
- **D.** Standard unencrypted SMTP servers typically listen on default well-known TCP port 25.
- **E.** POP3 allows simultaneous two-way folder synchronization across multiple user devices without downloading message copies.

---

### Question 14
- **Difficulty**: [Moderate]
- **Type**: [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

During data transmission across a TCP/IP network, application data is encapsulated with protocol headers as it travels down the hierarchy from the application process to the physical transmission medium. Which sequence correctly reflects the Protocol Data Unit (PDU) naming hierarchy from Layer 4 down to Layer 1?

- **A.** Packet (Datagram) $\rightarrow$ Frame $\rightarrow$ Segment $\rightarrow$ Bits
- **B.** Segment $\rightarrow$ Packet (Datagram) $\rightarrow$ Frame $\rightarrow$ Bits
- **C.** Frame $\rightarrow$ Segment $\rightarrow$ Packet $\rightarrow$ Bits
- **D.** Data $\rightarrow$ Frame $\rightarrow$ Datagram $\rightarrow$ Bits

---

### Question 15
- **Difficulty**: [Moderate]
- **Type**: [Scenario-Based] [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

**Scenario**: An IT director compares two networks operated by the company:
1. **Network Alpha**: Connects 500 servers and workstations located within three adjacent buildings on an academic campus over privately owned high-speed fiber-optic cabling spanning 800 meters.
2. **Network Beta**: Connects the corporate headquarters in Mumbai to a subsidiary research center in Frankfurt through leased telecommunications links across international public carrier backbones.

Which of the following comparative statements regarding Network Alpha (a LAN) and Network Beta (a WAN) is correct?

- **A.** Network Alpha spans a broader geographic area and suffers from significantly higher propagation delay than Network Beta.
- **B.** Network Alpha typically delivers substantially higher data transmission rates, lower communication latency, and lower bit-error rates than Network Beta.
- **C.** Network Beta requires no Layer-3 routing devices, operating entirely on Layer-1 physical repeaters across intercontinental oceans.
- **D.** Network Alpha incurs recurring long-distance telecommunications leasing fees, while Network Beta requires only one-time private cabling costs.

---

### Question 16
- **Difficulty**: [Difficult]
- **Type**: [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

A security analyst evaluates a raw IPv4 packet header captured using Wireshark during a network scan investigation. Which of the following statements regarding IPv4 header fields and their operational mechanics are technically accurate? *(Select ALL that apply)*

- **A.** The Header Length (HLEN) field is 4 bits wide and expresses the header length in 32-bit (4-byte) words; thus, the minimum valid HLEN value for an IPv4 packet without optional fields is `5` (representing 20 bytes).
- **B.** The 16-bit Header Checksum field calculates an error detection checksum that protects both the IPv4 header and the entire higher-layer payload.
- **C.** The 8-bit Time to Live (TTL) field is decremented by at least 1 by each intermediate router forwarding the packet; if TTL reaches 0 before reaching the destination, the packet is discarded and an ICMP Time Exceeded message is returned to the source.
- **D.** The 16-bit Total Length field defines the size of the higher-layer user payload alone, excluding the length of the IPv4 header.
- **E.** The 8-bit Protocol field identifies the encapsulated Transport Layer protocol, where a value of `6` denotes TCP and a value of `17` denotes UDP.

---

### Question 17
- **Difficulty**: [Difficult]
- **Type**: [Scenario-Based] [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

**Scenario**: During a security audit of a Linux web server, a penetration tester discovers that the server can successfully communicate with local workstations on the `192.168.1.0/24` subnet, but all attempts to ping an external DNS resolver at `8.8.8.8` or reach external security repository servers fail with the message `connect: Network is unreachable`.

Which of the following Linux commands will display the kernel routing table, allowing the tester to immediately verify whether an active default gateway route (`0.0.0.0` or `default`) is configured?

- **A.** `ifconfig eth0 promisc`
- **B.** `route -n` (or `ip route show`)
- **C.** `arp -d 8.8.8.8`
- **D.** `hostname -I`

---

### Question 18
- **Difficulty**: [Difficult]
- **Type**: [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

When evaluating switching methodologies and performance trade-offs in computer networking, which of the following statements are **TRUE**? *(Select ALL that apply)*

- **A.** In circuit switching, dedicated channel capacity is reserved along a fixed sequence of intermediate links for the full duration of communication, resulting in poor link utilization for bursty computer data traffic.
- **B.** Datagram packet switching requires an end-to-end Call Request and Call Accept handshake before user data packets can be transmitted, causing an initial connection setup delay.
- **C.** In Virtual Circuit packet switching, a route is predetermined during call setup, allowing intermediate nodes to forward packets using short Virtual Circuit numbers without dedicating the physical links to that single connection.
- **D.** Packet switching systems utilize store-and-forward switching, wherein intermediate routing nodes buffer the entire incoming packet, inspect headers, and make dynamic forwarding decisions based on internal routing tables.
- **E.** Circuit switching dynamically splits packets across alternate paths upon detecting intermediate link congestion, ensuring out-of-order reassembly at the receiver.

---

### Question 19
- **Difficulty**: [Difficult]
- **Type**: [Scenario-Based] [Single-correct MCQ]
- **Selection**: Exactly ONE option is correct

**Scenario**: An ethical hacker connects a testing laptop to an unmanaged access switch inside a corporate LAN. To test endpoint vulnerability against Man-in-the-Middle (MitM) attacks, the tester sends gratuitous Address Resolution Protocol (ARP) reply frames associating the corporate default gateway's IP address (`10.0.5.1`) with the tester's own MAC address (`AA:BB:CC:DD:EE:FF`).

Why does this ARP poisoning attack succeed within the local subnet, and which network device naturally establishes a boundary that prevents these spoofed Layer-2 ARP broadcast frames from directly propagating into adjacent departmental subnets?

- **A.** ARP inherently authenticates frame origins via digital certificates; a Layer-2 Hub filters unauthorized MAC tables.
- **B.** ARP is a trust-based, stateless protocol lacking cryptographic authentication; a Layer-3 Router bounds the broadcast domain and does not forward local Layer-2 ARP broadcast frames to other subnets.
- **C.** ARP packets carry encrypted 128-bit hashes; a Layer-1 Repeater isolates ARP broadcasts between subnets.
- **D.** ARP works strictly over intercontinental WAN links; a Layer-2 Bridge converts ARP packets into TCP packets to prevent spoofing.

---

### Question 20
- **Difficulty**: [Difficult]
- **Type**: [Scenario-Based] [Multiple-correct MCQ]
- **Selection**: ONE OR MORE options are correct (Select ALL that apply)

**Scenario**: An ethical hacking consultancy is contracted to conduct an authorized penetration test against an enterprise client ("TargetCorp"). The lead tester carries a "Tiger box" (a dedicated testing laptop containing multiple operating systems and vulnerability assessment suites). The Rules of Engagement (RoE) specify that testing must occur between 20:00 and 04:00 against the IP range `198.51.100.0/26`.

Which of the following actions performed by the tester would represent a **breach of ethical/legal boundaries** and violate standard cybersecurity testing laws (e.g., Section 43/66 of the Information Technology Act)? *(Select ALL that apply)*

- **A.** Scanning open TCP/UDP ports on target server `198.51.100.15` at 22:30 using tools from the Tiger box within the contracted window.
- **B.** Executing an uncoordinated, high-volume Distributed Denial of Service (DDoS) flood against TargetCorp's e-commerce payment server, disrupting active paying customers and knocking the business offline.
- **C.** Upon discovering a trust relationship to a third-party partner logistics network (`203.0.113.0/24`), pivoting into the partner's network to test their internal databases without prior authorization or written consent from the partner company.
- **D.** Identifying a remote code execution vulnerability on an in-scope server, taking non-destructive proof-of-concept evidence, documenting the vulnerability, and presenting remediation advice in the confidential post-engagement report.
- **E.** Accessing an unencrypted database containing customer credit card details, copying the customer data onto an unauthorized personal USB drive, and modifying server system audit logs to conceal the tester's personal identity.

---

---

# Part 2: Answer Key with Detailed Explanations

---

## Detailed Solution: Question 1

### A. Original Question
Which of the following defines the fundamental boundary that distinguishes an ethical hacker from a malicious black-hat hacker?
- A. Ethical hackers only use automated open-source reconnaissance tools, whereas malicious hackers write custom binary exploitation payloads.
- B. Ethical hackers possess explicit, prior written authorization from the system owner and operate strictly within a defined scope of engagement.
- C. Ethical hackers limit their penetration testing strictly to external perimeter IP addresses and are legally forbidden from inspecting internal network segments.
- D. Ethical hackers modify system logs and disable audit daemon processes during an assessment to prevent accidental alerts.

### B. Correct Answer
- **Correct Option**: **B** [Ethical hackers possess explicit, prior written authorization from the system owner and operate strictly within a defined scope of engagement.]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Ethical hacking is legally and operationally defined by authorized consent (formal permission from the asset owner) and adherence to a defined scope (Rules of Engagement). The technical tools and methods used often mirror those of malicious hackers.

### C. Concepts Required to Solve the Question
1. **Simple Definition**: An ethical hacker is a security professional authorized by an organization to find security vulnerabilities before malicious hackers can exploit them.
2. **Technically Precise Definition**: Ethical hacking refers to the authorized practice of locating weaknesses and vulnerabilities in computer systems and information networks by systematically replicating the intent, techniques, and actions of malicious adversaries under contractual permission and legal authorization.
3. **Why the Concept Exists**: Defensive audits without active adversarial testing fail to identify real-world vulnerabilities. However, attempting to break into computer systems without authorization is a serious criminal offense under cybercrime statutes (e.g., Indian IT Act, US CFAA).
4. **How It Works Internally**:
   - Organization establishes a legal contract (Rules of Engagement, Non-Disclosure Agreement).
   - Scope is defined (IP ranges, testing windows, forbidden actions like DoS).
   - Ethical hacker conducts tests (reconnaissance, scanning, exploitation, post-exploitation assessment).
   - Findings are documented in a confidential report with remediation steps.
5. **Key Distinctions**:
   - *Hacking*: Exhibiting computer expertise or exploring systems.
   - *Cracking / Black-Hat Hacking*: Breaching security without authorization for malicious gain, theft, disruption, or vanity.
   - *Ethical Hacking (White-Hat)*: Legal, authorized penetration testing to find weak links on behalf of the owner.
6. **Common Misconceptions**: Thinking that ethical hackers use different software/tools than malicious hackers, or that ethical hacking means "only scanning without attempting access."

### D. Detailed Option-by-Option Analysis

- **Option A is INCORRECT**:
  - *Claim*: Ethical hackers only use open-source reconnaissance tools, while malicious hackers write custom payloads.
  - *Technical Fact*: Ethical hackers routinely develop custom exploit scripts (using Python, C/C++, Perl, Go) and leverage both open-source and commercial suites (Metasploit Pro, Burp Suite Professional, Cobalt Strike). Malicious hackers ("script kiddies") frequently use public automated tools. The tool does not determine legality.
  - *Smallest Change to Make it Correct*: "Ethical hackers and malicious hackers may use identical tools and programming languages, but ethical hackers do so with authorization."
  - *Common Trap*: Assuming skill level or software provenance distinguishes ethical from unethical actions.

- **Option B is CORRECT**:
  - *Claim*: Ethical hackers possess explicit, prior written authorization from the system owner and operate strictly within a defined scope of engagement.
  - *Technical Fact*: Written authorization (permission) and scope compliance are the absolute legal criteria that distinguish lawful security testing from criminal unauthorized computer access under cyber laws.

- **Option C is INCORRECT**:
  - *Claim*: Ethical hackers are legally forbidden from inspecting internal network segments.
  - *Technical Fact*: Ethical hacking frequently includes internal penetration testing (assessing the impact of an insider threat or an attacker who has bypassed perimeter firewalls). Scope is determined by the client contract, not by an arbitrary perimeter-only restriction.
  - *Smallest Change to Make it Correct*: "Ethical hackers can inspect external or internal network segments depending on the agreed scope."

- **Option D is INCORRECT**:
  - *Claim*: Ethical hackers modify system logs and disable audit daemons.
  - *Technical Fact*: Modifying logs or tampering with audit mechanisms to hide actions from the client is a malicious behavior typical of unauthorized attackers seeking to evade forensic detection. Ethical hackers preserve audit trails for forensic verification and client accountability.
  - *Smallest Change to Make it Correct*: "Ethical hackers document their activity so clients can correlate security alerts with testing timestamps."

### E. Why the Other Answers Are Not Correct
Options A, C, and D describe false technical restrictions or malicious behaviors. Option B captures the definitive criteria: **written consent** and **defined scope of engagement**.

### F. Step-by-Step Solving Strategy
1. Identify the core differentiator: What legally separates ethical hacking from cybercrime?
2. Recall Prof. Indranil Sen Gupta's definition: "Legal attempt to break into the company's network... on behalf of its owner."
3. Eliminate tools (A), network boundaries (C), and malicious log tampering (D).
4. Select B.

---

## Detailed Solution: Question 2

### A. Original Question
State whether the following statement is True or False:
*"An IPv6 address comprises 128 bits, organized into 8 groups of 16-bit hexadecimal values separated by colons, yielding an address space of $2^{128}$ unique identifiers."*
- A. True
- B. False

### B. Correct Answer
- **Correct Option**: **A** [True]
- **Selection Type**: True-False (Single-correct)
- **Confidence Level**: High
- **Brief Summary**: IPv6 was engineered by the IETF to resolve IPv4 address exhaustion. It expands the address length from 32 bits (IPv4) to 128 bits, written as 8 hextets of 4 hexadecimal characters each separated by colons.

### C. Concepts Required to Solve the Question
1. **Simple Definition**: IPv6 is the modern version of the Internet Protocol that provides an astronomically large pool of IP addresses.
2. **Technically Precise Definition**: IPv6 (Internet Protocol version 6, RFC 8200) uses a 128-bit (16-byte) address structure represented in hexadecimal notation as 8 blocks of 16 bits (e.g., `2001:0db8:85a3:0000:0000:8a2e:0370:7334`).
3. **Mathematical Comparison**:
   $$\text{IPv4 address space} = 2^{32} \approx 4.29 \times 10^9 \text{ addresses}$$
   $$\text{IPv6 address space} = 2^{128} \approx 3.40 \times 10^{38} \text{ addresses}$$
4. **Hexadecimal Representation Rules**:
   - Each group contains 16 bits = 4 hexadecimal digits ($16 \times 8 = 128$ bits).
   - Leading zeros within a hextet can be omitted (`0db8` $\rightarrow$ `db8`).
   - One contiguous block of all-zero hextets can be compressed to `::` (allowed only once per address to prevent ambiguity).

```
+---------------------------------------------------------------+
|                      IPv6 Address (128 bits)                  |
| 16 bits | 16 bits | 16 bits | 16 bits | 16 bits | 16 bits | 16 bits | 16 bits |
| Hextet1 : Hextet2 : Hextet3 : Hextet4 : Hextet5 : Hextet6 : Hextet7 : Hextet8 |
+---------------------------------------------------------------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is CORRECT**: The statement accurately states all four critical technical parameters of IPv6: (1) 128 bits total length, (2) 8 groups, (3) 16-bit hexadecimal blocks separated by colons, and (4) $2^{128}$ total theoretical addresses.
- **Option B is INCORRECT**: Marking this statement false is incorrect because there are no technical inaccuracies in the proposition.

### E. Exam Traps & Misconceptions
- **Trap**: Confusing bits and bytes. IPv6 has 128 bits = 16 bytes. IPv4 has 32 bits = 4 bytes.
- **Trap**: Confusing decimal and hexadecimal. IPv4 is written in dotted decimal (4 octets of 8 bits each). IPv6 is written in colon hexadecimal (8 groups of 16 bits each).

---

## Detailed Solution: Question 3

### A. Original Question
A network security administrator is configuring a boundary firewall to permit standard, unencrypted Hypertext Transfer Protocol (HTTP) web browsing traffic from intranet hosts to public web servers. Which default destination port number must be allowed through the firewall rule?
- A. Port 21
- B. Port 25
- C. Port 80
- D. Port 443

### B. Correct Answer
- **Correct Option**: **C** [Port 80]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Unencrypted HTTP uses well-known TCP port 80. Port 21 is FTP control, Port 25 is SMTP, and Port 443 is encrypted HTTPS.

### C. Concepts Required to Solve the Question
1. **Port Numbers in TCP/IP**: Ports are 16-bit unsigned integers ($0$ to $65535$) used at Layer 4 (Transport Layer) to direct incoming and outgoing packets to specific application processes.
2. **Port Categories (IANA)**:
   - *Well-Known Ports*: $0 - 1023$ (assigned to standard server system services).
   - *Registered Ports*: $1024 - 49151$ (assigned to vendor applications).
   - *Dynamic / Private / Ephemeral Ports*: $49152 - 65535$ (used dynamically by client operating systems as source ports).

| Protocol | Default Port | Transport | Purpose |
| :--- | :--- | :--- | :--- |
| **FTP (Data / Control)** | 20 / 21 | TCP | File Transfer Protocol |
| **SSH** | 22 | TCP | Secure Shell Remote Access |
| **Telnet** | 23 | TCP | Insecure Remote Terminal |
| **SMTP** | 25 | TCP | Simple Mail Transfer Protocol |
| **DNS** | 53 | UDP / TCP | Domain Name System |
| **DHCP** | 67 / 68 | UDP | Dynamic Host Configuration |
| **HTTP** | **80** | **TCP** | **Hypertext Transfer Protocol** |
| **POP3** | 110 | TCP | Post Office Protocol v3 |
| **IMAP** | 143 | TCP | Internet Message Access Protocol |
| **SNMP** | 161 | UDP | Simple Network Management Protocol |
| **HTTPS** | 443 | TCP | HTTP over TLS/SSL |

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: Port 21 is used for File Transfer Protocol (FTP) control connection signaling, not web traffic.
- **Option B is INCORRECT**: Port 25 is assigned to Simple Mail Transfer Protocol (SMTP) for email transmission.
- **Option C is CORRECT**: TCP Port 80 is the universally standardized well-known port for unencrypted HTTP traffic.
- **Option D is INCORRECT**: Port 443 is used for HTTPS (HTTP Secure over TLS/SSL). The question explicitly specified *unencrypted* HTTP.

### E. Why the Other Answers Are Not Correct
All other ports correspond to entirely different application-layer services (FTP=21, SMTP=25) or the encrypted variant (HTTPS=443).

### F. Step-by-Step Solving Strategy
1. Identify keyword: "unencrypted Hypertext Transfer Protocol (HTTP)".
2. Match with IANA well-known port list: HTTP = 80.
3. Check distractors: 21 (FTP), 25 (SMTP), 443 (HTTPS).
4. Confirm answer is C.

---

## Detailed Solution: Question 4

### A. Original Question
Which of the following are categorized as defensive security applications or mechanisms designed to protect workstations and enterprise infrastructure from unauthorized activity or compromise? *(Select ALL that apply)*
- A. Stateful Packet Inspection Firewall
- B. Trojan Horse
- C. Signature-based Antivirus Software
- D. Host-based Intrusion Prevention System (HIPS)
- E. Ransomware

### B. Correct Answer
- **Correct Options**: **A, C, D**
  - **A**: Stateful Packet Inspection Firewall
  - **C**: Signature-based Antivirus Software
  - **D**: Host-based Intrusion Prevention System (HIPS)
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Firewalls, antivirus programs, and intrusion prevention systems are defensive security controls. Trojan horses and ransomware are malicious software (malware) threats.

### C. Concepts Required to Solve the Question
1. **Defensive Controls (Security Applications)**:
   - *Firewall*: A security application/device that filters incoming and outgoing network traffic based on established security rules (state table, IP addresses, ports).
   - *Antivirus / Antimalware*: Software designed to detect, quarantine, and eliminate malicious code by scanning files against known signature databases and behavioral heuristics.
   - *HIPS / NIPS (Intrusion Prevention System)*: System that monitors operating system calls and network traffic in real time to block malicious behavior.
2. **Threats / Attacks (Malware)**:
   - *Trojan Horse*: Malware masquerading as legitimate, benign software that conceals malicious functionality (such as installing a backdoor).
   - *Ransomware*: Malicious software that encrypts user files and demands extortion payments for decryption keys.
   - *Virus*: Self-replicating code attached to a legitimate host executable.
   - *Worm*: Standalone self-propagating malware that replicates across networks without requiring user interaction.

```
       +--------------------------------------------------------+
       |               Workstation Security Context             |
       +--------------------------------------------------------+
              |                                        |
     DEFENSIVE CONTROLS                         MALWARE THREATS
  [Protective Applications]                 [Malicious Code / Vectors]
  - Antivirus Engine                        - Trojan Horse
  - Stateful Firewall                       - Ransomware
  - Host IPS (HIPS)                         - Viruses / Worms
```

### D. Detailed Option-by-Option Analysis
- **Option A is CORRECT**: A stateful packet inspection firewall actively tracks TCP/UDP connection states to block unauthorized inbound traffic. It is a fundamental defensive application.
- **Option B is INCORRECT**: A Trojan Horse is a malicious payload (threat), not a security application.
- **Option C is CORRECT**: Antivirus engines are defensive applications that scan files and memory to detect and neutralize malware.
- **Option D is CORRECT**: HIPS monitors system activities for malicious behavior and terminates offending processes to defend the host.
- **Option E is INCORRECT**: Ransomware is extortionist malicious software (a cyber threat).

### E. Exam Traps & Misconceptions
- **Trap**: Conflating security concepts. In Week 0 Assignment Q2, the question asked which applications are used to secure personal computers (Antivirus, Firewall). Distractors like Virus and Malware represent the threats being defended against.

---

## Detailed Solution: Question 5

### A. Original Question
A cybersecurity analyst operating an Ubuntu Linux workstation needs to inspect the current network interface configurations, including IP addresses, netmasks, broadcast addresses, and hardware (MAC) addresses. Which traditional Linux command-line utility provides this information?
- A. `ipconfig /all`
- B. `ifconfig -a`
- C. `netstat -rn`
- D. `tracert 127.0.0.1`

### B. Correct Answer
- **Correct Option**: **B** [`ifconfig -a`]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: `ifconfig` (interface configuration) is the traditional Unix/Linux command used to view and configure network interfaces. `ipconfig` is the Windows command.

### C. Concepts Required to Solve the Question
1. **Linux vs Windows Command Equivalents**:

| Task | Linux Utility | Windows Utility |
| :--- | :--- | :--- |
| **Interface Configuration** | `ifconfig` / `ip addr` | `ipconfig` / `ipconfig /all` |
| **Routing Table** | `route -n` / `ip route` | `route print` |
| **Active Sockets & Connections** | `netstat` / `ss` | `netstat -ano` |
| **Path Route Tracing** | `traceroute` | `tracert` |
| **ICMP Echo Ping** | `ping -c <count>` | `ping -n <count>` |
| **DNS Resolution Query** | `dig` / `nslookup` | `nslookup` |

2. **`ifconfig` Usage**:
   - Running `ifconfig` displays all currently active network interfaces (e.g., `eth0`, `wlan0`, `lo`).
   - Flag `-a` instructs `ifconfig` to display all interfaces, including those that are currently administratively down or inactive.

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: `ipconfig /all` is a Windows command. On Linux, executing `ipconfig` returns `command not found`.
- **Option B is CORRECT**: `ifconfig -a` is the standard traditional Linux/Unix command for inspecting all network interface configurations.
- **Option C is INCORRECT**: `netstat -rn` displays kernel routing tables numerically without resolving hostnames. It does not display interface MAC addresses, netmasks, or assigned broadcast addresses in interface configuration view.
- **Option D is INCORRECT**: `tracert` is the Windows path-tracing utility (Linux uses `traceroute`). Furthermore, tracing the loopback interface (`127.0.0.1`) does not display network interface properties.

### E. Why the Other Answers Are Not Correct
`ipconfig` and `tracert` belong to the Windows operating system family. `netstat -rn` targets routes, not interface link parameters. Only `ifconfig` is the correct Linux command.

---

## Detailed Solution: Question 6

### A. Original Question
An enterprise network engineer connects 16 employee desktop computers to an unmanaged 16-port Layer-2 Ethernet switch. Assuming no Virtual LANs (VLANs) or routers are configured, how many **collision domains** and how many **broadcast domains** exist across this local network setup?
- A. 1 collision domain, 16 broadcast domains
- B. 16 collision domains, 1 broadcast domain
- C. 1 collision domain, 1 broadcast domain
- D. 16 collision domains, 16 broadcast domains

### B. Correct Answer
- **Correct Option**: **B** [16 collision domains, 1 broadcast domain]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Each physical port on a Layer-2 switch creates an independent collision domain (16 collision domains for 16 active ports). However, all ports on an unmanaged switch belong to a single, shared broadcast domain (1 broadcast domain).

### C. Concepts Required to Solve the Question
1. **Collision Domain**: A network segment where data packets can collide with one another when sent simultaneously.
   - *Hub (Layer 1)*: Multi-port repeater. Does not inspect MAC addresses. All ports belong to **1 single collision domain**.
   - *Switch / Bridge (Layer 2)*: Buffers frames and inspects MAC addresses. **Every individual switch port is a separate collision domain**.
2. **Broadcast Domain**: The set of all network nodes that receive a Layer-2 broadcast frame (destination MAC `FF:FF:FF:FF:FF:FF`).
   - Switches forward broadcast frames out of all ports (except the ingress port).
   - Therefore, a default switch comprises **1 single broadcast domain**.
   - Only a **Router (Layer 3)** or VLAN boundary breaks up broadcast domains.

```
       +----------------------------------------------------+
       |          Layer-2 Switch (16 Ports)                 |
       +----------------------------------------------------+
         |   |   |   |   |   |   |   |   |   |   |   | ... |
        [D1][D2][D3][D4].................................[D16]
         |<->| Each port = 1 independent Collision Domain  |
         |                                                 |
         +=========== 1 Single Broadcast Domain ===========+
```

| Device | OSI Layer | Collision Domains | Broadcast Domains |
| :--- | :--- | :--- | :--- |
| **Hub / Repeater** | Layer 1 | 1 (shared across all ports) | 1 (shared) |
| **Switch / Bridge** | Layer 2 | 1 per port | 1 (per switch/VLAN) |
| **Router** | Layer 3 | 1 per port | 1 per port (breaks broadcasts) |

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: It inverts the technical roles of Layer 2 switches. A hub has 1 collision domain, whereas a router separates broadcast domains.
- **Option B is CORRECT**: With 16 connected ports on a Layer-2 switch, microsegmentation provides 16 separate collision domains. Because switches flood broadcast frames, there is exactly 1 broadcast domain.
- **Option C is INCORRECT**: A single collision domain and single broadcast domain describes a Layer-1 Hub, not a Layer-2 Switch.
- **Option D is INCORRECT**: 16 broadcast domains would require 16 separate physical routers or 16 distinct VLANs, not a single unmanaged switch.

### E. Exam Traps & Misconceptions
- **Trap**: Forgetting that switches break up collision domains but **do not** break up broadcast domains. Only routers break up broadcast domains.

---

## Detailed Solution: Question 7

### A. Original Question
Which of the following statements accurately compare the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP) at the Transport Layer? *(Select ALL that apply)*
- A. TCP provides reliable, ordered data delivery using sequence numbers, acknowledgments, and automatic retransmissions of lost packets.
- B. UDP establishes a three-way handshake before transmitting user data to negotiate buffer window sizes.
- C. UDP is a connectionless protocol that sends independent datagrams without establishing a connection or maintaining connection state.
- D. TCP is an unacknowledged protocol designed for lightweight queries such as DNS lookups, where connection overhead must be minimized.
- E. TCP implements end-to-end flow control and congestion avoidance mechanisms to prevent a fast sender from overwhelming a slow receiver or congested network links.

### B. Correct Answer
- **Correct Options**: **A, C, E**
  - **A**: TCP provides reliable, ordered data delivery using sequence numbers, acknowledgments, and automatic retransmissions of lost packets.
  - **C**: UDP is a connectionless protocol that sends independent datagrams without establishing a connection or maintaining connection state.
  - **E**: TCP implements end-to-end flow control and congestion avoidance mechanisms to prevent a fast sender from overwhelming a slow receiver or congested network links.
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: TCP is connection-oriented, reliable, acknowledged, and features flow/congestion control. UDP is connectionless, unreliable (best-effort), lightweight, and operates without handshakes.

### C. Concepts Required to Solve the Question
1. **TCP (Transmission Control Protocol - RFC 793)**:
   - Connection-oriented: Requires SYN $\rightarrow$ SYN-ACK $\rightarrow$ ACK 3-way handshake.
   - Reliable: Sequence numbers track data bytes; missing packets trigger retransmission.
   - Flow Control: Sliding window mechanism ensures receiver buffers are not overrun.
   - Heavyweight: 20-byte minimum header.
2. **UDP (User Datagram Protocol - RFC 768)**:
   - Connectionless: No handshake, no state maintained.
   - Unreliable (Best-effort): Packets can be lost, duplicated, or arrive out of order with no transport-layer recovery.
   - Atomic datagrams: Messages small enough to fit inside a single packet are sent without splitting.
   - Lightweight: 8-byte fixed header, low latency. Ideal for DNS queries, VoIP, live streaming.

```
       TCP Handshake (Connection-Oriented)        UDP Transmission (Connectionless)
       Client                  Server             Client                  Server
         | --- SYN (seq=x) ----> |                  | --- UDP Datagram ---> |
         | <-- SYN-ACK (ack=x+1) |                  | (No connection setup) |
         | --- ACK (ack=y+1) --> |                  | (No acknowledgment)   |
         | ===== Data Flow ===== |                  |                       |
```

### D. Detailed Option-by-Option Analysis
- **Option A is CORRECT**: This is the textbook definition of TCP's reliability model.
- **Option B is INCORRECT**: UDP has no 3-way handshake and no windowing negotiation. The 3-way handshake belongs exclusively to TCP.
- **Option C is CORRECT**: UDP is strictly connectionless; each datagram is processed independently by intermediate nodes and endpoints.
- **Option D is INCORRECT**: TCP is acknowledged and reliable. It is UDP that is unacknowledged and used for typical lightweight DNS queries.
- **Option E is CORRECT**: TCP sliding windows and congestion algorithms (Slow Start, Congestion Avoidance) regulate sender transmission rates.

### E. Exam Traps & Misconceptions
- **Trap**: Believing UDP is "bad" because it is "unreliable." In networking, "unreliable" simply means the protocol does not guarantee delivery; it trades guarantees for minimal latency and simplicity.

---

## Detailed Solution: Question 8

### A. Original Question
**Scenario**: A financial corporation hires an external cybersecurity firm. Under the contract, the consultants not only simulate attacks to legally break into the company's internal and external network systems to discover exploitable vulnerabilities, but they also review the company's written security policies, evaluate employee procedures, and provide concrete remediation recommendations and architectural solutions to secure the network.

According to NPTEL course definitions (distinguishing testing methodologies), this engagement is most precisely classified as:
- A. A Penetration Test
- B. A Security Test
- C. A Black Box Model
- D. Port Scanning

### B. Correct Answer
- **Correct Option**: **B** [A Security Test]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: In Prof. Indranil Sen Gupta's lecture notes (Lecture 1, Slide 4), a strict distinction is drawn: in a **Penetration Test**, the tester only reports findings and does not provide solutions; in a **Security Test**, the assessment includes analyzing company security policies and procedures, and the tester actively offers solutions to secure or protect the network.

### C. Concepts Required to Solve the Question
1. **Prof. Indranil Sen Gupta's Core Distinction (Lecture 1)**:
   - **Penetration Test**:
     - Legal attempt to break into a company's network to find weak links.
     - *Crucial criterion*: Tester **only reports findings, does not provide solutions**.
   - **Security Test**:
     - Includes penetrating the network, but goes further.
     - Analyzes company's security policies and organizational procedures.
     - *Crucial criterion*: Tester **offers solutions to secure or protect the network**.

```
+-----------------------------------------------------------------------+
|  PENETRATION TEST                                                     |
|  - Attempt legal intrusion                                            |
|  - Find weak links / vulnerabilities                                  |
|  - Tester ONLY reports findings (NO solutions offered)                |
+-----------------------------------------------------------------------+
                                  VS
+-----------------------------------------------------------------------+
|  SECURITY TEST                                                        |
|  - Includes vulnerability discovery & intrusion attempts              |
|  - Analyzes company security POLICIES and PROCEDURES                  |
|  - Tester OFFERS SOLUTIONS to protect and secure the network          |
+-----------------------------------------------------------------------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: Under the specific NPTEL curriculum definitions, a pure penetration test restricts the tester to identifying and reporting vulnerabilities without formulating policy reviews or architectural solutions.
- **Option B is CORRECT**: The scenario explicitly states that the consultants analyzed security policies and delivered concrete remediation solutions, which directly matches the definition of a Security Test.
- **Option C is INCORRECT**: Black Box refers to the degree of prior knowledge provided to the tester (zero knowledge), not the broader engagement scope involving policy analysis and solution engineering.
- **Option D is INCORRECT**: Port scanning is merely a tactical reconnaissance technique used to locate open TCP/UDP listening ports, not a comprehensive audit engagement.

### E. Exam Traps & Misconceptions
- **Trap**: In general industry parlance, people often use "penetration testing" and "security testing" interchangeably. However, NPTEL exam questions test the specific distinctions taught by Prof. Indranil Sen Gupta in Lecture 1. Knowing that "providing solutions and analyzing policies = Security Test" is vital.

---

## Detailed Solution: Question 9

### A. Original Question
In standard IPv4 dotted-decimal notation, each address consists of four decimal octets separated by periods. Which of the following IP addresses are **INVALID** IPv4 addresses? *(Select ALL that apply)*
- A. `172.16.254.1`
- B. `192.168.1.256`
- C. `10.200.315.44`
- D. `198.51.100.8.2`
- E. `224.0.0.1`

### B. Correct Answer
- **Correct Options**: **B, C, D**
  - **B**: `192.168.1.256` (Fourth octet $256 > 255$)
  - **C**: `10.200.315.44` (Third octet $315 > 255$)
  - **D**: `198.51.100.8.2` (Contains five octets instead of four)
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: An IPv4 address is an exact 32-bit integer formatted as 4 octets. Each octet is 8 bits, meaning its numerical decimal value must strictly fall in the range $0$ to $255$ ($2^8 - 1$). Values greater than 255 or an incorrect number of octets violate IPv4 structure.

### C. Concepts Required to Solve the Question
1. **IPv4 Address Structure**:
   - Total length: 32 bits.
   - Format: $O_1.O_2.O_3.O_4$, where each $O_i$ is an 8-bit unsigned integer.
   - Numerical range per octet:
     $$00000000_2 = 0_{10} \le O_i \le 255_{10} = 11111111_2$$
2. **Criteria for an Invalid IPv4 Address**:
   - Any octet $> 255$ (e.g., $256, 315$).
   - Any octet $< 0$ (negative numbers).
   - More or fewer than 4 octets (e.g., 5 numbers separated by dots).
   - Non-numeric characters.

### D. Detailed Option-by-Option Analysis
- **Option A is VALID**: `172.16.254.1` is a valid private IPv4 address (Class B RFC 1918). All octets ($172, 16, 254, 1$) are between $0$ and $255$. (Not selected because the question asks for INVALID addresses).
- **Option B is INVALID**: `192.168.1.256` has a fourth octet of 256. Since 8 bits can only hold up to 255, 256 cannot be represented. **(CORRECT SELECTION)**.
- **Option C is INVALID**: `10.200.315.44` has a third octet of 315, which exceeds 255. **(CORRECT SELECTION)**.
- **Option D is INVALID**: `198.51.100.8.2` has 5 octets (40 bits). Standard IPv4 contains strictly 4 octets. **(CORRECT SELECTION)**.
- **Option E is VALID**: `224.0.0.1` is a valid IPv4 multicast address (Class D: `224.0.0.0` - `239.255.255.255`). All octets ($224, 0, 0, 1$) fall strictly between 0 and 255. (Not selected).

### E. Exam Traps & Misconceptions
- **Trap**: Negative phrasing! The question asks for addresses that are **INVALID**. Students frequently make the mistake of selecting valid addresses out of habit. Always underline the word **INVALID**.

---

## Detailed Solution: Question 10

### A. Original Question
Both the Data Link Layer (Layer 2) and the Transport Layer (Layer 4) of the OSI model can perform error detection, flow control, and retransmission. What is the fundamental conceptual difference between their reliability responsibilities?
- A. The Data Link Layer provides end-to-end message delivery between source and destination applications, whereas the Transport Layer operates only over a single physical cable hop.
- B. The Data Link Layer ensures error-controlled frame transmission over a single point-to-point physical link between adjacent nodes, whereas the Transport Layer guarantees end-to-end reliable message delivery across multiple intermediate network hops.
- C. The Data Link Layer relies exclusively on software sockets, whereas the Transport Layer is implemented strictly in hardware network interface cards (NICs).
- D. The Data Link Layer reorders out-of-order packets traveling across the Internet, while the Transport Layer converts bits into electrical signals.

### B. Correct Answer
- **Correct Option**: **B** [The Data Link Layer ensures error-controlled frame transmission over a single point-to-point physical link between adjacent nodes, whereas the Transport Layer guarantees end-to-end reliable message delivery across multiple intermediate network hops.]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Layer 2 (Data Link) provides hop-by-hop reliability across a single physical wire between adjacent network nodes. Layer 4 (Transport) provides true end-to-end reliability between the originating host process and the ultimate destination host process across any number of intermediate routers.

### C. Concepts Required to Solve the Question
1. **OSI Layer Scope Hierarchy (Lecture 3 & 4)**:
   - **Data Link Layer (Layer 2)**:
     - Scope: **Point-to-point (Hop-by-hop)**.
     - PDU: Frames.
     - Addresses: MAC addresses (physical addresses, 48-bit).
     - Function: Moves frames over one link from host to switch, or router to router.
   - **Network Layer (Layer 3)**:
     - Scope: **Host-to-host across internetworks**.
     - PDU: Packets / Datagrams.
     - Delivery is connectionless and *unreliable* (best-effort IP).
   - **Transport Layer (Layer 4)**:
     - Scope: **Process-to-process / End-to-end**.
     - PDU: Segments (TCP) / Datagrams (UDP).
     - Addresses: Port numbers (16-bit).
     - Function: Bridges the gap between unreliable network routers to provide **end-to-end reliability** (retransmission, reordering, duplicate suppression).

```
   Host A                                                       Host B
+-----------+                                                +-----------+
| Transport | <================ End-to-End =================>| Transport |
+-----------+            (Across the entire path)            +-----------+
|  Network  |                Router 1       Router 2         |  Network  |
+-----------+             +-----------+  +-----------+       +-----------+
| Data Link | <==Hop-by==>| Data Link |=>| Data Link |<=Hop=>| Data Link |
+-----------+   Hop Link  +-----------+  +-----------+  Link +-----------+
| Physical  |             | Physical  |  | Physical  |       | Physical  |
+-----------+             +-----------+  +-----------+       +-----------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: Inverts the layers entirely. End-to-end is Transport Layer; single hop is Data Link Layer.
- **Option B is CORRECT**: Perfectly articulates the distinction: Layer 2 is node-to-node (point-to-point link), Layer 4 is process-to-process (end-to-end across internetwork hops).
- **Option C is INCORRECT**: Data Link Layer framing and MAC operations are handled by the Network Interface Card (NIC) hardware, while the Transport Layer (TCP/UDP) is implemented in the operating system software kernel.
- **Option D is INCORRECT**: Layer 4 (TCP) reorders packets; Layer 1 (Physical) converts bits into electrical/optical signals.

### E. Why the Other Answers Are Not Correct
Options A, C, and D contain severe inverted concepts and erroneous mappings of protocol responsibilities.

---

## Detailed Solution: Question 11

### A. Original Question
State whether the following statement is True or False:
*"In the Datagram approach to packet switching, intermediate network routers establish a dedicated physical circuit before any packets are transmitted, guaranteeing that all packets traverse the exact same path and arrive strictly in sequential order without carrying full destination addresses."*
- A. True
- B. False

### B. Correct Answer
- **Correct Option**: **B** [False]
- **Selection Type**: True-False (Single-correct)
- **Confidence Level**: High
- **Brief Summary**: The statement describes Circuit Switching (and partially Virtual Circuit packet switching). In the **Datagram approach**, NO route is established beforehand; every packet is treated as an independent entity carrying full destination and source addresses, intermediate nodes route dynamically, and packets may arrive out of order.

### C. Concepts Required to Solve the Question
1. **Circuit Switching vs Datagram vs Virtual Circuit (Lecture 2 & 3)**:
   - **Circuit Switching**: Dedicated physical channel created for entire call duration (e.g., traditional telephone network).
   - **Virtual Circuit Packet Switching**: Logical path established prior to transmission using Call Request/Call Accept packets. Packets share physical links but follow the same path carrying a Virtual Circuit Identifier (VCI).
   - **Datagram Packet Switching (The Internet / IP Model)**:
     - No pre-established route or circuit.
     - Each datagram is an independent entity carrying source and destination IP addresses.
     - Dynamic routing at every intermediate hop.
     - Packets may take different paths, experience variable delays, and arrive out of order.

```
+---------------------+-----------------------+-------------------------+
| Feature             | Circuit Switching     | Datagram Packet Switch  |
+---------------------+-----------------------+-------------------------+
| Dedicated Path?     | Yes (Physical)        | No                      |
| Setup Phase?        | Required              | None (Immediate send)   |
| Packet Addressing   | None during transfer  | Full Source & Dest IP   |
| Packet Sequencing   | Guaranteed in-order   | Out-of-order possible   |
| Resource Waste      | High for bursty data  | Low (Shared links)      |
+---------------------+-----------------------+-------------------------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: The statement is fundamentally false.
- **Option B is CORRECT**: The statement falsely attributes dedicated path reservation, pre-established routes, in-order arrival, and missing destination addresses to the Datagram approach. All of these properties contradict the Datagram model.

### E. Exam Traps & Misconceptions
- **Trap**: Confusing Datagram Packet Switching with Virtual Circuit Packet Switching. Datagrams are like letters in the postal system—each envelope carries the full address and is routed independently.

---

## Detailed Solution: Question 12

### A. Original Question
**Scenario**: A healthcare company engages an ethical hacker to conduct a realistic adversary simulation. The client provides the tester with only the company's public domain name (`healthcorp-example.com`). The tester is given **no** internal network diagrams, **no** IP address ranges, **no** system architecture documentation, and **no** user credentials. The burden of identifying target hosts, network topology, and software versions rests entirely on the tester.

Which penetration-testing model does this scenario describe?
- A. White Box Model
- B. Gray Box Model
- C. Black Box Model
- D. Clear Box Model

### B. Correct Answer
- **Correct Option**: **C** [Black Box Model]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: In a **Black Box** assessment, the tester has zero prior internal knowledge about the target infrastructure. In a **White Box** assessment, the tester receives full disclosure (network diagrams, credentials, source code). In a **Gray Box** assessment, partial information is provided.

### C. Concepts Required to Solve the Question
1. **Penetration Testing Methodologies (Lecture 1, Slides 9-10)**:
   - **White Box Model (Clear/Crystal Box)**:
     - Full disclosure: Tester is given comprehensive information (network topology, IP maps, source code, credentials, architecture).
     - Tester is authorized to interview IT staff.
     - Goal: Thorough audit; simulates an insider with full access.
   - **Black Box Model**:
     - Zero disclosure: Tester is given no details about the internal network.
     - Burden is entirely on the tester to locate targets via reconnaissance and OSINT.
     - Simulates an external, unprivileged attacker.
   - **Gray Box Model**:
     - Hybrid: Tester is given partial information (e.g., standard low-privileged user account, limited subnet scope).
     - Simulates an ordinary customer, contractor, or insider with restricted privileges.

```
+-------------------------------------------------------------------------+
|                  PENETRATION TESTING MODELS                             |
+-------------------------------------------------------------------------+
|  MODEL     | KNOWLEDGE PROVIDED      | SIMULATED THREAT                 |
+------------+-------------------------+----------------------------------+
| White Box  | Full / Complete info    | Malicious Admin / Insider        |
| Gray Box   | Partial info / Accounts | Standard Employee / Partner      |
| Black Box  | Zero / Public domain    | External Malicious Hacker        |
+-------------------------------------------------------------------------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: White box testing involves complete transparency, architectural diagrams, and interviews with IT staff.
- **Option B is INCORRECT**: Gray box testing involves partial disclosure (such as test credentials or internal IP ranges).
- **Option C is CORRECT**: The scenario explicitly states that zero information was provided beyond a public domain name, placing the entire burden of discovery on the tester. This is the definition of Black Box testing.
- **Option D is INCORRECT**: "Clear Box" is a synonym for White Box testing.

### E. Why the Other Answers Are Not Correct
The amount of information provided (zero internal details) uniquely designates this assessment as Black Box testing.

---

## Detailed Solution: Question 13

### A. Original Question
Which of the following statements regarding Internet electronic mail protocols are technically correct? *(Select ALL that apply)*
- A. Simple Mail Transfer Protocol (SMTP) is a "push" protocol primarily used to transfer emails from a client to a mail server, and to relay emails between intermediate Mail Transfer Agents (MTAs).
- B. Post Office Protocol version 3 (POP3) is a server-to-server routing protocol that runs on TCP port 25 to deliver outgoing email across WAN boundaries.
- C. Internet Message Access Protocol (IMAP) is a "pull" protocol that permits client applications to access, organize, and manage email folders residing directly on the remote mail server.
- D. Standard unencrypted SMTP servers typically listen on default well-known TCP port 25.
- E. POP3 allows simultaneous two-way folder synchronization across multiple user devices without downloading message copies.

### B. Correct Answer
- **Correct Options**: **A, C, D**
  - **A**: Simple Mail Transfer Protocol (SMTP) is a "push" protocol primarily used to transfer emails from a client to a mail server, and to relay emails between intermediate Mail Transfer Agents (MTAs).
  - **C**: Internet Message Access Protocol (IMAP) is a "pull" protocol that permits client applications to access, organize, and manage email folders residing directly on the remote mail server.
  - **D**: Standard unencrypted SMTP servers typically listen on default well-known TCP port 25.
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: SMTP pushes/relays email across servers on TCP port 25. POP3 and IMAP are client mail retrieval ("pull") protocols. IMAP allows server-side folder management, while POP3 traditionally downloads and removes messages.

### C. Concepts Required to Solve the Question
1. **Email Architecture Components**:
   - **MUA (Mail User Agent)**: Email client software (e.g., Thunderbird, Outlook).
   - **MTA (Mail Transfer Agent)**: Server routing software (e.g., Postfix, Sendmail).
2. **Protocol Roles & Ports**:
   - **SMTP (Port 25, 587 submission)**:
     - Push protocol.
     - Used by MUA to send email to outgoing mail server.
     - Used between MTAs to relay messages across the Internet.
   - **POP3 (Port 110, 995 SSL)**:
     - Pull protocol.
     - Downloads emails from server inbox to local client drive; traditionally marks them for deletion on server.
     - Does not support multi-device synchronization.
   - **IMAP (Port 143, 993 SSL)**:
     - Pull protocol.
     - Stores messages and directory folders on the mail server; changes sync across all connected devices in real time.

```
 Sender                                                              Recipient
 [MUA] --- (SMTP:25/587) ---> [Sending MTA]                           [MUA]
                                   |                                    ^
                             (SMTP:25 Relay)               (IMAP:143 / POP3:110)
                                   v                                    |
                            [Receiving MTA] === (Local Mailbox) =======+
```

### D. Detailed Option-by-Option Analysis
- **Option A is CORRECT**: SMTP is a push protocol designed for client-to-server submission and inter-server relay.
- **Option B is INCORRECT**: POP3 is not a server-to-server routing protocol, nor does it run on port 25. It is a client retrieval protocol running on port 110.
- **Option C is CORRECT**: IMAP leaves mail on the server and provides folder management and synchronization.
- **Option D is CORRECT**: TCP port 25 is the official IANA standard port for unencrypted MTA-to-MTA SMTP transmission.
- **Option E is INCORRECT**: POP3 does not support folder synchronization across multiple devices. That is the primary design purpose of IMAP.

### E. Exam Traps & Misconceptions
- **Trap**: Confusing SMTP with POP3/IMAP. Remember: **SMTP sends** (pushes), **POP3 and IMAP retrieve** (pull).

---

## Detailed Solution: Question 14

### A. Original Question
During data transmission across a TCP/IP network, application data is encapsulated with protocol headers as it travels down the hierarchy from the application process to the physical transmission medium. Which sequence correctly reflects the Protocol Data Unit (PDU) naming hierarchy from Layer 4 down to Layer 1?
- A. Packet (Datagram) $\rightarrow$ Frame $\rightarrow$ Segment $\rightarrow$ Bits
- B. Segment $\rightarrow$ Packet (Datagram) $\rightarrow$ Frame $\rightarrow$ Bits
- C. Frame $\rightarrow$ Segment $\rightarrow$ Packet $\rightarrow$ Bits
- D. Data $\rightarrow$ Frame $\rightarrow$ Datagram $\rightarrow$ Bits

### B. Correct Answer
- **Correct Option**: **B** [Segment $\rightarrow$ Packet (Datagram) $\rightarrow$ Frame $\rightarrow$ Bits]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: As data moves down the stack: Transport Layer generates **Segments** (or user datagrams), Network Layer encapsulates them into **Packets** (or IP datagrams), Data Link Layer encapsulates packets into **Frames**, and Physical Layer encodes frames into raw **Bits**.

### C. Concepts Required to Solve the Question
1. **Data Encapsulation Hierarchy (Lecture 4, Slides 15-16)**:
   - **Layer 7, 6, 5 (Application/Presentation/Session)**: Data / Message.
   - **Layer 4 (Transport)**: Appends TCP/UDP header $\rightarrow$ **Segment** (TCP) or **Datagram** (UDP).
   - **Layer 3 (Network)**: Appends IP header $\rightarrow$ **Packet** (IP Datagram).
   - **Layer 2 (Data Link)**: Appends Ethernet header and trailer (CRC FCS) $\rightarrow$ **Frame**.
   - **Layer 1 (Physical)**: Encodes frame into signals $\rightarrow$ **Bits**.

```
+---------------------------------------------------------------+
| Layer 4 (Transport) | [TCP/UDP Header] [User Data] = SEGMENT  |
+---------------------+-----------------------------------------+
                          | Encapsulated into Layer 3
+---------------------+---v-------------------------------------+
| Layer 3 (Network)   | [IP Header] [   Segment    ] = PACKET   |
+---------------------+-----------------------------------------+
                          | Encapsulated into Layer 2
+---------------------+---v-------------------------------------+
| Layer 2 (Data Link) | [Eth Header] [ Packet ] [CRC] = FRAME   |
+---------------------+-----------------------------------------+
                          | Serialized into Layer 1
+---------------------+---v-------------------------------------+
| Layer 1 (Physical)  | 0 1 1 0 1 0 0 1 1 1 0 0 0 1 0 = BITS    |
+---------------------+-----------------------------------------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: Packets belong to Layer 3, not Layer 4. Segments belong to Layer 4, not Layer 2.
- **Option B is CORRECT**: Matches the exact OSI and TCP/IP PDU descending progression: Segment (L4) $\rightarrow$ Packet (L3) $\rightarrow$ Frame (L2) $\rightarrow$ Bits (L1).
- **Option C is INCORRECT**: Frames belong to Layer 2, which cannot precede Layer 4 or Layer 3.
- **Option D is INCORRECT**: Puts Frame above Datagram, which reverses Layers 2 and 3.

### E. Why the Other Answers Are Not Correct
Any sequence that fails to respect the strict descending order ($4 \rightarrow 3 \rightarrow 2 \rightarrow 1$: Segment $\rightarrow$ Packet $\rightarrow$ Frame $\rightarrow$ Bits) is incorrect.

---

## Detailed Solution: Question 15

### A. Original Question
**Scenario**: An IT director compares two networks operated by the company:
1. **Network Alpha**: Connects 500 servers and workstations located within three adjacent buildings on an academic campus over privately owned high-speed fiber-optic cabling spanning 800 meters.
2. **Network Beta**: Connects the corporate headquarters in Mumbai to a subsidiary research center in Frankfurt through leased telecommunications links across international public carrier backbones.

Which of the following comparative statements regarding Network Alpha (a LAN) and Network Beta (a WAN) is correct?
- A. Network Alpha spans a broader geographic area and suffers from significantly higher propagation delay than Network Beta.
- B. Network Alpha typically delivers substantially higher data transmission rates, lower communication latency, and lower bit-error rates than Network Beta.
- C. Network Beta requires no Layer-3 routing devices, operating entirely on Layer-1 physical repeaters across intercontinental oceans.
- D. Network Alpha incurs recurring long-distance telecommunications leasing fees, while Network Beta requires only one-time private cabling costs.

### B. Correct Answer
- **Correct Option**: **B** [Network Alpha typically delivers substantially higher data transmission rates, lower communication latency, and lower bit-error rates than Network Beta.]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Local Area Networks (LANs) cover small geographical boundaries (single room, building, or campus), offer much higher bandwidth (Gbps to 10+ Gbps), minimal latency, and negligible error rates. Wide Area Networks (WANs) span cities/continents, traverse third-party telecommunication providers, and incur higher latency, recurring costs, and higher error rates.

### C. Concepts Required to Solve the Question
1. **LAN vs WAN Comparison (Lecture 2, Slide 4)**:
   - **Local Area Network (LAN)**:
     - Geography: Small, restricted (room, building, campus).
     - Ownership: Owned privately by the organization.
     - Speed / Bandwidth: Very high (1 Gbps - 100 Gbps).
     - Latency / Propagation Delay: Extremely low (microseconds to a few milliseconds).
     - Error rate: Very low.
     - Cost: High initial hardware setup, low ongoing recurring transmission cost.
   - **Wide Area Network (WAN)**:
     - Geography: Dispersed across cities, countries, continents.
     - Ownership: Traverses public carriers, telecommunications providers, satellite links.
     - Speed / Bandwidth: Typically lower or much more expensive per Gbps.
     - Latency / Propagation Delay: High (hundreds of milliseconds due to physical distances and routing hops).
     - Error rate: Higher due to extensive telecommunication switching equipment.

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: Inverts the geographic scale. LANs are small; WANs are broad with higher propagation delays.
- **Option B is CORRECT**: Accurately summarizes the fundamental networking properties of a LAN compared to a WAN.
- **Option C is INCORRECT**: Intercontinental WAN communication requires complex Layer-3 routers, autonomous system peering (BGP), and undersea optical amplification, not simple Layer-1 repeaters.
- **Option D is INCORRECT**: Recurring leased-line fees apply to the WAN (Network Beta), while private cabling infrastructure applies to the on-campus LAN (Network Alpha).

### E. Why the Other Answers Are Not Correct
Options A, C, and D contain claims that directly contradict basic networking principles.

---

## Detailed Solution: Question 16

### A. Original Question
A security analyst evaluates a raw IPv4 packet header captured using Wireshark during a network scan investigation. Which of the following statements regarding IPv4 header fields and their operational mechanics are technically accurate? *(Select ALL that apply)*
- A. The Header Length (HLEN) field is 4 bits wide and expresses the header length in 32-bit (4-byte) words; thus, the minimum valid HLEN value for an IPv4 packet without optional fields is `5` (representing 20 bytes).
- B. The 16-bit Header Checksum field calculates an error detection checksum that protects both the IPv4 header and the entire higher-layer payload.
- C. The 8-bit Time to Live (TTL) field is decremented by at least 1 by each intermediate router forwarding the packet; if TTL reaches 0 before reaching the destination, the packet is discarded and an ICMP Time Exceeded message is returned to the source.
- D. The 16-bit Total Length field defines the size of the higher-layer user payload alone, excluding the length of the IPv4 header.
- E. The 8-bit Protocol field identifies the encapsulated Transport Layer protocol, where a value of `6` denotes TCP and a value of `17` denotes UDP.

### B. Correct Answer
- **Correct Options**: **A, C, E**
  - **A**: The Header Length (HLEN) field is 4 bits wide and expresses the header length in 32-bit (4-byte) words; thus, the minimum valid HLEN value for an IPv4 packet without optional fields is `5` (representing 20 bytes).
  - **C**: The 8-bit Time to Live (TTL) field is decremented by at least 1 by each intermediate router forwarding the packet; if TTL reaches 0 before reaching the destination, the packet is discarded and an ICMP Time Exceeded message is returned to the source.
  - **E**: The 8-bit Protocol field identifies the encapsulated Transport Layer protocol, where a value of `6` denotes TCP and a value of `17` denotes UDP.
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: IPv4 HLEN measures 32-bit words ($5 \times 4 = 20$ bytes minimum). TTL is decremented per hop to kill routing loops. Protocol 6 = TCP, 17 = UDP. The Header Checksum covers **ONLY** the IP header (not the payload), and Total Length includes **BOTH** the header and the payload.

### C. Concepts Required to Solve the Question
1. **IPv4 Datagram Header Architecture (Lecture 5, Slides 6-10)**:

```
 0                   1                   2                   3
 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|Version|  HLEN |Type of Service|          Total Length         |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|         Identification        |Flags|      Fragment Offset    |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|  Time to Live |    Protocol   |        Header Checksum        |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|                       Source IP Address                       |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|                    Destination IP Address                     |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|                    Options (if HLEN > 5)                      |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
|                             DATA                              |
+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+
```

2. **Crucial Field Details**:
   - `HLEN` (4 bits): Multiplied by 4 to get bytes. Minimum value is $5$ ($5 \times 4 = 20$ bytes). Maximum is $15$ ($15 \times 4 = 60$ bytes).
   - `Total Length` (16 bits): Includes header **plus** data. Maximum datagram size is $2^{16} - 1 = 65535$ bytes.
   - `Time to Live (TTL)` (8 bits): Decremented by 1 at each router. Prevents packets from circulating indefinitely in routing loops. When $\text{TTL} = 0$, router discards packet and sends ICMP Type 11 (Time Exceeded). Used by `traceroute`.
   - `Protocol` (8 bits): Indicates payload handler ($1 = \text{ICMP}, 6 = \text{TCP}, 17 = \text{UDP}$).
   - `Header Checksum` (16 bits): **Only covers the IPv4 header**. It does NOT protect the data payload! Higher-layer protocols (TCP/UDP) carry their own checksums.

### D. Detailed Option-by-Option Analysis
- **Option A is CORRECT**: HLEN is 4 bits; values range from 5 (20 bytes) to 15 (60 bytes).
- **Option B is INCORRECT**: The IP Header Checksum covers **only the IP header**, not the data payload. Recalculating checksums across gigabytes of payload at every router hop would create massive processing bottlenecks.
- **Option C is CORRECT**: Accurately describes TTL operation and ICMP Time Exceeded generation.
- **Option D is INCORRECT**: Total Length covers the entire datagram (IP header + data payload), not just the payload.
- **Option E is CORRECT**: In IANA protocol assignments, Protocol $6 = \text{TCP}$ and Protocol $17 = \text{UDP}$.

### E. Exam Traps & Misconceptions
- **Trap**: Believing the IP header checksum protects data. It does not! This is one of the most famous networking exam traps.

---

## Detailed Solution: Question 17

### A. Original Question
**Scenario**: During a security audit of a Linux web server, a penetration tester discovers that the server can successfully communicate with local workstations on the `192.168.1.0/24` subnet, but all attempts to ping an external DNS resolver at `8.8.8.8` or reach external security repository servers fail with the message `connect: Network is unreachable`.

Which of the following Linux commands will display the kernel routing table, allowing the tester to immediately verify whether an active default gateway route (`0.0.0.0` or `default`) is configured?
- A. `ifconfig eth0 promisc`
- B. `route -n` (or `ip route show`)
- C. `arp -d 8.8.8.8`
- D. `hostname -I`

### B. Correct Answer
- **Correct Option**: **B** [`route -n` (or `ip route show`)]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: When local subnet hosts are reachable but external IP destinations return "Network is unreachable", the operating system kernel lacks a default gateway route. In Linux, `route -n`, `netstat -rn`, or `ip route show` displays the active kernel routing table.

### C. Concepts Required to Solve the Question
1. **Network Routing Logic in Linux**:
   - When an application sends a packet to an IP address, the kernel checks its routing table.
   - If the destination IP matches a local subnet entry (e.g., `192.168.1.0/24`), the kernel uses ARP to send directly to that local host.
   - If the destination IP does NOT match any specific subnet route, the kernel routes the packet to the **default gateway** (`Destination: 0.0.0.0`, `Genmask: 0.0.0.0`).
   - If the default gateway entry is missing, the kernel cannot forward the packet and generates the error: `connect: Network is unreachable`.
2. **Commands**:
   - `route -n`: Displays kernel routing table with numerical IP addresses (no DNS lookup delays).
   - `ip route show`: Modern `iproute2` equivalent.
   - `ifconfig eth0 promisc`: Puts the interface into promiscuous mode (captures all frames regardless of destination MAC).
   - `arp -d`: Deletes an entry from the ARP cache.

```
$ route -n
Kernel IP routing table
Destination     Gateway         Genmask         Flags Metric Ref    Use Iface
0.0.0.0         192.168.1.1     0.0.0.0         UG    100    0        0 eth0
192.168.1.0     0.0.0.0         255.255.255.0   U     100    0        0 eth0
```
*(If the `0.0.0.0` line with the `UG` flag is missing, all external communication fails).*

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: `ifconfig eth0 promisc` enables promiscuous mode for packet sniffing. It does not inspect routing tables.
- **Option B is CORRECT**: `route -n` directly queries and outputs the kernel IP routing table, revealing whether `0.0.0.0` pointing to a gateway router exists.
- **Option C is INCORRECT**: `arp -d` manipulates the Layer-2 ARP table. Furthermore, `8.8.8.8` is an external IP; local hosts do not maintain ARP entries for external Internet IPs.
- **Option D is INCORRECT**: `hostname -I` simply prints the local host's configured IP addresses.

### E. Why the Other Answers Are Not Correct
Only Option B interacts with the Layer-3 routing subsystem.

---

## Detailed Solution: Question 18

### A. Original Question
When evaluating switching methodologies and performance trade-offs in computer networking, which of the following statements are **TRUE**? *(Select ALL that apply)*
- A. In circuit switching, dedicated channel capacity is reserved along a fixed sequence of intermediate links for the full duration of communication, resulting in poor link utilization for bursty computer data traffic.
- B. Datagram packet switching requires an end-to-end Call Request and Call Accept handshake before user data packets can be transmitted, causing an initial connection setup delay.
- C. In Virtual Circuit packet switching, a route is predetermined during call setup, allowing intermediate nodes to forward packets using short Virtual Circuit numbers without dedicating the physical links to that single connection.
- D. Packet switching systems utilize store-and-forward switching, wherein intermediate routing nodes buffer the entire incoming packet, inspect headers, and make dynamic forwarding decisions based on internal routing tables.
- E. Circuit switching dynamically splits packets across alternate paths upon detecting intermediate link congestion, ensuring out-of-order reassembly at the receiver.

### B. Correct Answer
- **Correct Options**: **A, C, D**
  - **A**: In circuit switching, dedicated channel capacity is reserved along a fixed sequence of intermediate links for the full duration of communication, resulting in poor link utilization for bursty computer data traffic.
  - **C**: In Virtual Circuit packet switching, a route is predetermined during call setup, allowing intermediate nodes to forward packets using short Virtual Circuit numbers without dedicating the physical links to that single connection.
  - **D**: Packet switching systems utilize store-and-forward switching, wherein intermediate routing nodes buffer the entire incoming packet, inspect headers, and make dynamic forwarding decisions based on internal routing tables.
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Circuit switching dedicates capacity and is inefficient for bursty traffic. Virtual circuit sets up a path upfront but shares links using VC numbers. Packet switches operate on store-and-forward. Datagram switching has **no** setup phase.

### C. Concepts Required to Solve the Question
1. **Network Switching Paradigms (Lecture 2 & 3)**:
   - **Circuit Switching**:
     - Three phases: (1) Connection establishment, (2) Data transfer, (3) Connection termination.
     - Bandwidth is reserved and guaranteed.
     - Idle transmission periods waste capacity.
   - **Virtual Circuit Packet Switching**:
     - Call Request packet reserves a logical path; Call Accept confirms it.
     - Packets carry a small Virtual Circuit Identifier (VCI).
     - Physical links remain shared (statistical multiplexing); bandwidth is not locked if idle.
   - **Datagram Packet Switching**:
     - No call setup. Immediate transmission.
     - Store-and-forward: Node receives whole packet, buffers it, looks up routing table, forwards it.
     - Robust against failures: If a node crashes or link fails, datagrams can dynamically take alternate routes.

```
Circuit Switching:       [Setup] -------------------> [Dedicated Stream] ---> [Teardown]
Virtual Circuit:         [Call Req/Accept] ---------> [Packets via VC#] ------> [Clear]
Datagram Packet Switch:  [Immediate Store-and-Forward of Independent Packets] -> (No setup)
```

### D. Detailed Option-by-Option Analysis
- **Option A is CORRECT**: This is a direct thesis from Lecture 2 (Slide 8): "Channel capacity is dedicated... Very inefficient for bursty traffic like data."
- **Option B is INCORRECT**: Datagram packet switching has **zero** initial connection setup delay. The Call Request/Accept handshake belongs to Virtual Circuit packet switching and Circuit Switching.
- **Option C is CORRECT**: Matches Lecture 2 (Slides 14-15): Virtual circuit routes are established a priori; intermediate nodes maintain a forwarding table and route by VC number, but links are not dedicated.
- **Option D is CORRECT**: Matches Lecture 2 (Slide 11): Packet switching is fundamentally based on the store-and-forward concept.
- **Option E is INCORRECT**: Circuit switching does not use packets, cannot split data over alternate paths dynamically, and has no out-of-order reassembly.

### E. Exam Traps & Misconceptions
- **Trap**: Forgetting that Virtual Circuits share physical links. People often confuse Virtual Circuits with physical Circuit Switching. The word "Virtual" denotes that the dedicated path is purely logical.

---

## Detailed Solution: Question 19

### A. Original Question
**Scenario**: An ethical hacker connects a testing laptop to an unmanaged access switch inside a corporate LAN. To test endpoint vulnerability against Man-in-the-Middle (MitM) attacks, the tester sends gratuitous Address Resolution Protocol (ARP) reply frames associating the corporate default gateway's IP address (`10.0.5.1`) with the tester's own MAC address (`AA:BB:CC:DD:EE:FF`).

Why does this ARP poisoning attack succeed within the local subnet, and which network device naturally establishes a boundary that prevents these spoofed Layer-2 ARP broadcast frames from directly propagating into adjacent departmental subnets?
- A. ARP inherently authenticates frame origins via digital certificates; a Layer-2 Hub filters unauthorized MAC tables.
- B. ARP is a trust-based, stateless protocol lacking cryptographic authentication; a Layer-3 Router bounds the broadcast domain and does not forward local Layer-2 ARP broadcast frames to other subnets.
- C. Switches inspect Layer-4 TCP headers to reject spoofed ARP; a Layer-1 Repeater isolates the broadcast domain.
- D. ARP operates exclusively over WAN links; a Layer-2 Bridge converts ARP packets into TCP packets to prevent spoofing.

### B. Correct Answer
- **Correct Option**: **B** [ARP is a trust-based, stateless protocol lacking cryptographic authentication; a Layer-3 Router bounds the broadcast domain and does not forward local Layer-2 ARP broadcast frames to other subnets.]
- **Selection Type**: Single-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: ARP operates at Layer 2/3 without authentication; hosts blindly update their ARP caches upon receiving ARP replies. Because ARP requests/announcements use Layer-2 broadcast frames, a Layer-3 Router stops them from crossing into other subnets.

### C. Concepts Required to Solve the Question
1. **Address Resolution Protocol (ARP - Lecture 4, Slide 9)**:
   - Maps 32-bit logical IPv4 addresses to 48-bit physical MAC addresses on a local broadcast network (e.g., Ethernet).
   - Inherent Flaw: ARP is completely stateless and unauthenticated. Any host can transmit an unsolicited ARP reply ("Gratuitous ARP"), and victim hosts will overwrite their ARP cache tables.
2. **ARP Spoofing / Poisoning**:
   - Attacker tells Victim: "I am the Gateway (`10.0.5.1` is at `AA:BB:CC:DD:EE:FF`)."
   - Attacker tells Gateway: "I am the Victim (`10.0.5.20` is at `AA:BB:CC:DD:EE:FF`)."
   - Result: All traffic between Victim and Gateway flows through the Attacker's machine (Man-in-the-Middle).
3. **Network Device Broadcast Boundaries**:
   - Switches forward broadcast frames to all ports in the VLAN/broadcast domain.
   - **Routers (Layer 3)** do **NOT** forward Layer-2 broadcast frames (`FF:FF:FF:FF:FF:FF`). Thus, ARP poisoning is strictly localized to the broadcast domain (subnet).

```
[Victim Host]               [Attacker (Tiger Box)]            [Default Gateway]
10.0.5.20 / MAC_V           10.0.5.99 / MAC_A                 10.0.5.1 / MAC_G
       |                             |                               |
       | <==== Spoofed ARP Reply ==== |                               |
       |   "10.0.5.1 is at MAC_A"     | === Spoofed ARP Reply ======> |
       |                              |   "10.0.5.20 is at MAC_A"    |
       v                              v                               v
 [Traffic from Victim] =====> [Attacker Sniffs/Modifies] ====> [Out to Internet]
                                      |
                       +-----------------------------+
                       | Layer-3 ROUTER BOUNDARY     |
                       | (Blocks ARP from crossing)  |
                       +-----------------------------+
```

### D. Detailed Option-by-Option Analysis
- **Option A is INCORRECT**: ARP has zero cryptographic authentication or digital certificates. Furthermore, hubs do not maintain MAC tables.
- **Option B is CORRECT**: Correctly identifies why ARP spoofing works (stateless, unauthenticated protocol) and identifies that a Layer-3 Router bounds the broadcast domain.
- **Option C is INCORRECT**: Switches do not inspect Layer-4 TCP headers to validate ARP (ARP is not even encapsulated in TCP/IP; it is encapsulated directly in Ethernet frames). Repeaters do not isolate broadcast domains.
- **Option D is INCORRECT**: ARP does not operate over WAN links (WAN serial or point-to-point links do not use Ethernet ARP). Bridges do not convert ARP into TCP.

### E. Why the Other Answers Are Not Correct
Only Option B correctly explains ARP's architectural vulnerability and router boundary behavior.

---

## Detailed Solution: Question 20

### A. Original Question
**Scenario**: An ethical hacking consultancy is contracted to conduct an authorized penetration test against an enterprise client ("TargetCorp"). The lead tester carries a "Tiger box" (a dedicated testing laptop containing multiple operating systems and vulnerability assessment suites). The Rules of Engagement (RoE) specify that testing must occur between 20:00 and 04:00 against the IP range `198.51.100.0/26`.

Which of the following actions performed by the tester would represent a **breach of ethical/legal boundaries** and violate standard cybersecurity testing laws (e.g., Section 43/66 of the Information Technology Act)? *(Select ALL that apply)*
- A. Scanning open TCP/UDP ports on target server `198.51.100.15` at 22:30 using tools from the Tiger box within the contracted window.
- B. Executing an uncoordinated, high-volume Distributed Denial of Service (DDoS) flood against TargetCorp's e-commerce payment server, disrupting active paying customers and knocking the business offline.
- C. Upon discovering a trust relationship to a third-party partner logistics network (`203.0.113.0/24`), pivoting into the partner's network to test their internal databases without prior authorization or written consent from the partner company.
- D. Identifying a remote code execution vulnerability on an in-scope server, taking non-destructive proof-of-concept evidence, documenting the vulnerability, and presenting remediation advice in the confidential post-engagement report.
- E. Accessing an unencrypted database containing customer credit card details, copying the customer data onto an unauthorized personal USB drive, and modifying server system audit logs to conceal the tester's personal identity.

### B. Correct Answer
- **Correct Options**: **B, C, E**
  - **B**: Executing an uncoordinated, high-volume Distributed Denial of Service (DDoS) flood against TargetCorp's e-commerce payment server, disrupting active paying customers and knocking the business offline.
  - **C**: Upon discovering a trust relationship to a third-party partner logistics network (`203.0.113.0/24`), pivoting into the partner's network to test their internal databases without prior authorization or written consent from the partner company.
  - **E**: Accessing an unencrypted database containing customer credit card details, copying the customer data onto an unauthorized personal USB drive, and modifying server system audit logs to conceal the tester's personal identity.
- **Selection Type**: Multiple-correct MCQ
- **Confidence Level**: High
- **Brief Summary**: Actions B, C, and E represent illegal actions under cyber law and ethical hacking codes of conduct: causing denial of service to operational systems, accessing unauthorized third-party networks without consent, stealing sensitive data, and tampering with audit logs. Actions A and D are standard, lawful penetration testing procedures.

### C. Concepts Required to Solve the Question
1. **Legal Constraints and Prohibited Actions (Lecture 1, Slides 11-13)**:
   - Prof. Indranil Sen Gupta emphasizes:
     - Accessing any computer without explicit permission is illegal.
     - Launching Denial of Service (DoS) attacks that prevent customers/users from doing their jobs is strictly prohibited.
     - Tampering with or modifying logs to cover tracks or cause mischief is a malicious hacker activity.
     - Possessing or deploying malware (viruses, worms, trojans) outside authorized research is illegal.
2. **Tiger Box Concept (Lecture 1, Slide 9)**:
   - A portable collection of operating systems and hacking tools (typically on a penetration tester's laptop).
   - Used to conduct vulnerability assessments and authorized exploits.
   - Having the tools is legal only when utilized under authorized contracts.
3. **Pivoting & Scope Creep**:
   - Finding a route to an unauthorized third-party network does **not** grant permission to attack it. Testing third parties without their explicit written consent constitutes criminal computer trespass.

### D. Detailed Option-by-Option Analysis
- **Option A is LAWFUL (Not a violation)**: Scanning in-scope targets (`198.51.100.15` falls within `198.51.100.0/26`) during the authorized testing window (22:30 is between 20:00 and 04:00) using Tiger box tools is fully permitted. (Do not select).
- **Option B is a VIOLATION**: Causing a denial of service and disrupting commercial customers directly violates professional ethical guidelines and computer crime statutes. **(CORRECT SELECTION)**.
- **Option C is a VIOLATION**: Pivoting into an unauthorized third party's systems without their written authorization is illegal computer intrusion, regardless of the primary client's relationship with that third party. **(CORRECT SELECTION)**.
- **Option D is LAWFUL (Not a violation)**: Documenting vulnerabilities with non-destructive proof-of-concept and delivering remediation advice is the textbook mandate of an ethical security assessment. (Do not select).
- **Option E is a VIOLATION**: Exfiltrating confidential data to personal devices and altering audit logs are criminal acts (theft of data and tampering with computer source documents under IT Act Sections 43 & 66). **(CORRECT SELECTION)**.

### E. Exam Traps & Misconceptions
- **Trap**: Assuming that because a tester has permission to test Company A, they can test any network connected to Company A. Each autonomous entity must provide independent written authorization.
- **Trap**: Believing ethical hackers alter server logs like malicious hackers. Ethical hackers must maintain complete integrity of the client's system logs.

---

## Quick Reference Summary Table

| Q# | Difficulty | Type | Correct Option(s) | Core Subject Tested |
| :---: | :---: | :---: | :---: | :--- |
| **Q1** | Easy | Single-correct | **B** | Ethical Hacking Definition & Written Authorization |
| **Q2** | Easy | True-False | **A (True)** | IPv6 Address Bit Length (128 bits) & Architecture |
| **Q3** | Easy | Single-correct | **C** | Application Layer Default Port Numbers (HTTP = 80) |
| **Q4** | Easy | Multiple-correct | **A, C, D** | Defensive Controls (Firewall/AV/HIPS) vs Threats (Trojan/Ransomware) |
| **Q5** | Easy | Single-correct | **B** | Linux Network Interface Command (`ifconfig -a`) |
| **Q6** | Moderate | Single-correct | **B** | Layer-2 Switch Collision vs Broadcast Domains |
| **Q7** | Moderate | Multiple-correct | **A, C, E** | Transport Layer Protocols (TCP vs UDP Characteristics) |
| **Q8** | Moderate | Scenario | **B** | Penetration Testing vs Security Testing Methodology |
| **Q9** | Moderate | Multiple-correct | **B, C, D** | IPv4 Dotted-Decimal Octet Range Validity ($0-255$) |
| **Q10** | Moderate | Single-correct | **B** | Reliable Data Transfer: Hop-by-Hop (L2) vs End-to-End (L4) |
| **Q11** | Moderate | True-False | **B (False)** | Datagram Packet Switching vs Circuit Switching Principles |
| **Q12** | Moderate | Scenario | **C** | Penetration Testing Information Models (Black Box) |
| **Q13** | Moderate | Multiple-correct | **A, C, D** | Email Protocol Suite (SMTP, POP3, IMAP Roles & Ports) |
| **Q14** | Moderate | Single-correct | **B** | Protocol Data Unit (PDU) Hierarchy (Segment $\rightarrow$ Packet $\rightarrow$ Frame $\rightarrow$ Bits) |
| **Q15** | Moderate | Scenario | **B** | LAN vs WAN Performance, Geographic Scope, and Latency |
| **Q16** | Difficult | Multiple-correct | **A, C, E** | IPv4 Header Field Mechanics (HLEN, TTL, Checksum, Protocol) |
| **Q17** | Difficult | Scenario | **B** | Linux Kernel Routing Table Inspection (`route -n`) |
| **Q18** | Difficult | Multiple-correct | **A, C, D** | Switching Trade-offs: Circuit Switching vs Packet Switching |
| **Q19** | Difficult | Scenario | **B** | Layer-2 ARP Spoofing Vulnerability & Router Broadcast Boundary |
| **Q20** | Difficult | Scenario | **B, C, E** | Tiger Box Usage, Scope of Engagement & Legal Boundaries |

---
*Created for NPTEL Ethical Hacking Preparation — Prof. Indranil Sen Gupta, CSE, IIT Kharagpur.*
