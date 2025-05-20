### 🛡️ Networking Essentials

**Room:** [Networking Essentials — TryHackMe](https://tryhackme.com/room/networkingessentials)  
**Status:** ✅ Completed  
**Date:** *20 May 2025*  

### 🎯 Objective
This room explored essential networking protocols that enable automatic configuration, address resolution, and packet routing. The goal was to understand how devices communicate on networks through protocols like DHCP, ARP, ICMP, and NAT.

---

### 🗝️ Key Concepts  
- **DHCP (DORA Process)** — Automatic IP assignment via Discover, Offer, Request, Acknowledge  
- **ARP** — Resolves IP addresses to MAC addresses for local network communication  
- **ICMP Utilities** — `ping` for connectivity testing and `traceroute` for path discovery  
- **NAT** — Enables multiple devices to share a single public IP address  
- **Routing Protocols** — OSPF, EIGRP, BGP, and RIP for path determination  
- **Protocol Layers** — How these protocols operate across OSI model layers  

---

### 🛠️ Tools Used
- **Wireshark/tshark** — Analysing DHCP and ARP packet exchanges  
- **ping** — Testing network connectivity with ICMP Echo Requests  
- **traceroute** — Mapping network paths via TTL manipulation  
- **tcpdump** — Capturing and interpreting network traffic  

---

### ⚠️ Challenges Faced
- Understanding the four-step DHCP negotiation process  
- Differentiating between ARP (local) and DNS (remote) address resolution  
- Interpreting traceroute output with non-responsive hops  

---

### 🧠 What I Learned
- How devices automatically configure network settings via DHCP  
- The critical role of ARP in local network communications  
- How ICMP supports network troubleshooting tools  
- NAT's function in conserving IPv4 addresses  
- Differences between interior (OSPF/EIGRP) and exterior (BGP) routing protocols  
- Practical interpretation of network diagnostic tool outputs  

---

### 🌐 Real-World Application:
> These networking essentials are fundamental for:
> - **Network Administration**: Configuring and troubleshooting enterprise networks  
> - **Security Monitoring**: Detecting ARP spoofing or DHCP starvation attacks  
> - **Incident Response**: Using traceroute to identify attack paths  
> - **Cloud Engineering**: Understanding NAT for cloud resource management  
> The DHCP analysis demonstrated how forensic investigators can track device connections on a network.

---

### 💭 Reflections:
- Most valuable insight: Seeing how multiple protocols work together (DHCP→ARP→ICMP)  
- Biggest "aha" moment: Understanding NAT's port translation mechanism  
- Practical benefit: Ability to diagnose network issues methodically  
- Key takeaway: "Networking is like city infrastructure - DHCP assigns addresses, ARP finds local routes, and NAT manages shared exits"  
