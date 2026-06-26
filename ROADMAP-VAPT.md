# Roadmap: VAPT / Penetration Testing Path

Estimated time: **8–12 months** of consistent effort. This path generally takes longer than SOC to become job-ready because employers expect more hands-on proof (CTF rankings, writeups, a methodology you can explain) before hiring even at junior level.

Good fit if you: enjoy puzzles/CTFs, like understanding *how* something breaks rather than just *that* it broke, are comfortable with a lot of self-directed, unstructured problem solving.

---

## Phase 0: Foundations (3–4 weeks)

- [ ] Networking fundamentals: TCP/IP, common ports/services, HTTP/HTTPS deeply (you'll live in HTTP)
- [ ] Linux comfort: command line fluency, file permissions, basic scripting (Bash)
- [ ] Windows basics: AD concepts at a high level (you'll go deeper later)
- [ ] Pick up **Python** - pentesting tooling and scripting leans on it heavily

---

## Phase 1: Core security & web fundamentals (6–8 weeks)

- [ ] **OWASP Top 10** - know each vulnerability class cold: SQLi, XSS, CSRF, SSRF, broken auth, IDOR, etc.
- [ ] HTTP deep dive: methods, headers, cookies, sessions, status codes - you need to read raw requests/responses fluently
- [ ] Basic cryptography concepts: hashing vs encryption, common misconfigurations (not deep crypto math)

**Portfolio item:** Pick 3 OWASP Top 10 categories and write short explainers with a simple demo (use an intentionally vulnerable app, see Resources) showing the bug and the fix.

---

## Phase 2: Hands-on hacking - web (8–10 weeks)

- [ ] Practice on **deliberately vulnerable apps**: DVWA, bWAPP, Juice Shop
- [ ] Learn **Burp Suite** (Community edition is free) - proxy, repeater, intruder basics
- [ ] Learn to manually test for each OWASP Top 10 category, not just run a scanner
- [ ] Start **TryHackMe** or **HackTheBox** easy-rated web boxes

**Portfolio item:** Write 10+ structured writeups (not full walkthroughs of paid platforms if their rules disallow it - check ToS) describing your methodology: recon → enumeration → exploitation → impact.

---

## Phase 3: Hands-on hacking - network/infra (8–10 weeks)

- [ ] Nmap - scanning, service/version detection, scripting engine basics
- [ ] Privilege escalation basics on both Linux and Windows
- [ ] Active Directory attack basics (this is huge in real-world internal pentests): enumeration, common misconfig attacks
- [ ] Password attacks: hashcat/john basics, understanding wordlists vs brute force

**Portfolio item:** Complete a handful of "easy" and "medium" rated boxes on HackTheBox/TryHackMe focused on AD and privilege escalation; document your process.

---

## Phase 4: Tooling fluency (parallel, ongoing)

Get comfortable (not necessarily expert) with:

- [ ] Burp Suite, Nmap, Metasploit basics
- [ ] Wireshark for traffic analysis
- [ ] Basic scripting to automate repetitive recon (Python/Bash)
- [ ] Note-taking discipline - pentesters live and die by clear notes (Obsidian, CherryTree, or even structured markdown)

---

## Phase 5: Report writing (don't skip this - it's underrated)

A pentester who can't write a clear, client-readable report is not hireable, no matter how good the hacking is.

- [ ] Practice writing findings: vulnerability description, risk rating (CVSS basics), proof of concept, remediation advice
- [ ] Use a free sample pentest report template to structure your own lab writeups this way

**Portfolio item:** Take 3 of your lab findings and rewrite them as if for a real client report - this is genuinely one of the strongest things you can show in an interview.

---

## Phase 6: Certification (after hands-on, not before)

1. **eJPT (eLearnSecurity Junior Penetration Tester)** - affordable, practical, well-regarded as a first cert
2. **OSCP (Offensive Security Certified Professional)** - the gold-standard junior/mid pentest cert, but expensive and hard; aim for this after 6+ months of consistent HTB/THM practice, not as a first step
3. CEH is widely known in India/HR systems but is more theory-heavy and less respected technically - useful for passing HR keyword filters, not a substitute for OSCP/eJPT skill level

---

## Phase 7: Applying

- [ ] Target roles: **Junior Penetration Tester**, **VAPT Analyst**, **Security Consultant (Junior)**
- [ ] Build a simple portfolio site or GitHub repo of your (ToS-compliant) writeups
- [ ] Mention CTF rankings/profiles (TryHackMe, HackTheBox profile links) directly on your resume
- [ ] Be ready to explain your methodology clearly in interviews - companies care more about *process* than memorized payloads

## A realistic note

VAPT roles are competitive and CTF/lab proof genuinely matters more here than in SOC hiring. Budget for this taking longer, and don't be discouraged if SOC ends up being the faster entry point with a later internal move into VAPT - that's a very common and respected path in India specifically.
