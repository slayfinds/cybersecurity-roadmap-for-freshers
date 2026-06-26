# Roadmap: Network Security Path

Estimated time: **6-9 months**. This path is a strong fit if you have or want to build genuine networking/infra interest - it's less about offense/defense theatrics and more about designing and maintaining systems that are secure by default.

Good fit if you: like infrastructure, enjoy configuring/troubleshooting devices, prefer "build it right" over "find what's broken" or "watch for attacks."

---

## Phase 0: Strong networking foundation (4–6 weeks - don't rush this one)

This path lives and dies on genuinely strong networking fundamentals, more so than the other two paths.

- [ ] OSI & TCP/IP model deeply, not just memorized layers
- [ ] Subnetting and VLSM - be able to actually calculate, not just recognize
- [ ] Routing basics: static routing, basic dynamic routing concepts (OSPF/BGP at a conceptual level)
- [ ] Switching basics: VLANs, trunking, STP concepts
- [ ] Consider **CCNA**-level material as your syllabus even if you don't sit the exam yet

---

## Phase 1: Core network security concepts (6–8 weeks)

- [ ] Firewalls - stateful vs stateless, rule design, common misconfigurations
- [ ] VPNs - site-to-site vs remote access, IPSec vs SSL VPN concepts
- [ ] Network segmentation & zero trust basics
- [ ] IDS/IPS - how detection/prevention systems sit in a network, signature vs anomaly-based detection
- [ ] DNS security basics, common DNS-based attacks (cache poisoning, tunneling)

**Portfolio item:** Design a simple secure network diagram for a hypothetical small company (segmented zones, firewall placement, VPN access) and explain your reasoning in a writeup. This is a classic, respected interview-style exercise.

---

## Phase 2: Hands-on lab work (8–10 weeks)

- [ ] Build a home lab using **GNS3** or **Packet Tracer** (both free) - simulate routers, switches, firewalls
- [ ] Configure a basic firewall ruleset on **pfSense** or **OPNsense** (free, install on a VM)
- [ ] Set up a basic VPN (site-to-site or remote access) in your lab
- [ ] Practice traffic capture and analysis with **Wireshark** specifically for spotting misconfigurations and suspicious patterns

**Portfolio item:** Document your home lab setup on GitHub with network diagrams, configs (sanitized), and what security decisions you made and why.

---

## Phase 3: Going deeper (8 weeks)

- [ ] Network Access Control (NAC) concepts
- [ ] Wireless security: WPA2/WPA3, common wireless attack vectors
- [ ] Cloud networking security basics (VPCs, security groups, NSGs) - increasingly required even in "pure" network security roles
- [ ] Logging/monitoring at the network layer - this is where it starts to overlap usefully with SOC skills

---

## Phase 4: Certification path

1. **CompTIA Network+** then **Security+** if you haven't done these - solid generalist foundation
2. **CCNA** - strong, globally recognized, genuinely useful even outside security
3. Later, vendor-specific: **Fortinet NSE**, **Palo Alto PCNSA**, or **Cisco CCNP Security** depending on what tools your target employer uses (check job postings in your area for this - Fortinet and Palo Alto are both very common in Indian enterprises)

---

## Phase 5: Applying

- [ ] Target roles: **Network Security Engineer (Junior)**, **Network Administrator with Security focus**, **Firewall Engineer (Junior/L1)**
- [ ] Build and document a solid home lab - this matters more here than a polished resume at entry level
- [ ] Internal mobility is common: many people move from networking/infra-adjacent roles into Network Security Engineer roles within the same company

## A realistic note

This path tends to have a clearer, more linear progression than VAPT, and slightly less "prove yourself via CTFs" pressure than VAPT - but it does demand that your core networking fundamentals are genuinely strong, not surface-level. If Phase 0 feels shaky, slow down there before moving on; everything else builds on it.
