# Roadmap: SOC Analyst Path

Estimated total time: **6-9 months** of consistent (not crazy) effort while still working or studying. Go slower if you need to - order matters more than speed.

---

## Phase 0: Foundations (2-3 weeks to solidify)

Before going further, make sure these basics are *solid*, not just "I've heard of it":

- [ ] Networking basics: OSI model, TCP/IP, DNS, DHCP, subnetting, ports/protocols
- [ ] OS basics: Windows file system & permissions, Linux basics (you don't need to be an expert, but be comfortable in a terminal)
- [ ] Basic scripting: pick **one** - Python or Bash - just enough to read and write small scripts

**Checkpoint:** Can you explain what happens when you type a URL into a browser, end to end? If not, that's your week-1 task.

---

## Phase 1: Security fundamentals (4–6 weeks)

- [ ] CIA triad, AAA, defense in depth, common attack types (phishing, malware, MITM, DoS)
- [ ] Security frameworks awareness: NIST CSF, MITRE ATT&CK (just know what they are and how to navigate them)
- [ ] Windows & Linux security basics: logs, event viewer, syslog, user/privilege management
- [ ] Free intro cert to aim for: **CompTIA Security+** content (you can self-study the syllabus for free even if you delay the paid exam)

**Portfolio item:** Write a short blog post or GitHub markdown explaining one attack type in your own words (e.g. "How phishing actually works, step by step"). Recruiters and interviewers like seeing you can explain things simply.

---

## Phase 2: Core SOC skills (8–10 weeks)

This is the heart of it - what a SOC Analyst L1 actually does day to day.

- [ ] **SIEM basics** - what a SIEM is, log ingestion, correlation rules. Practice on a free SIEM (Splunk Free tier or ELK stack)
- [ ] **Log analysis** - Windows Event Logs, Linux auth logs, firewall logs. Practice spotting anomalies
- [ ] **Network traffic analysis** - Wireshark fundamentals, spotting suspicious traffic patterns
- [ ] **Incident response basics** - the IR lifecycle (Prepare → Identify → Contain → Eradicate → Recover → Lessons Learned)
- [ ] **MITRE ATT&CK in practice** - map a sample incident to tactics/techniques

**Portfolio item:** Set up a home SOC lab (free, see RESOURCES.md) - ingest some sample logs into Splunk Free or ELK, write up 2–3 "investigations" you did, even on synthetic data. Put this on GitHub with screenshots.

---

## Phase 3: Hands-on practice & CTFs (ongoing, overlap with Phase 2)

- [ ] Start doing **beginner-friendly CTF-style labs** (TryHackMe SOC Level 1 path is built exactly for this)
- [ ] Try a few **blue-team specific challenges** - log analysis, malware triage basics, phishing email analysis
- [ ] Join 1–2 CTF/practice communities for accountability

**Portfolio item:** Document 5–10 labs you completed with short write-ups (what was the scenario, what did you find, how did you find it). This becomes your "proof of work" since you won't have job experience yet.

---

## Phase 4: Tools & ecosystem familiarity (4 weeks, parallel)

Get hands-on (not just theoretical) with:

- [ ] A SIEM (Splunk or ELK)
- [ ] An EDR concept (read about CrowdStrike/SentinelOne/Defender - free docs/demos)
- [ ] How SOC tools integrate with ticketing/SOAR platforms for case management
- [ ] Vulnerability scanning basics (Nessus Essentials free tier, OpenVAS)

---

## Phase 5: Certification (when you're ready, not before)

Certs matter for getting past HR filters, but **do them after** the hands-on phases, not instead of them. Recommended order:

1. **CompTIA Security+** - broadest recognition, good first cert
2. **Blue Team focused** (pick one): BTL1 (Blue Team Level 1) or eJPT for a slightly more offensive-adjacent angle
3. Later, once employed: SOC-specific or SIEM-vendor certs (Splunk, etc.), or move toward CySA+ / GCIH

Don't buy a cert before doing the labs above - you'll retain almost nothing and waste money.

---

## Phase 6: Resume, portfolio, and applying (start this in parallel from Phase 3 onward)

- [ ] Build a simple GitHub profile/portfolio with your lab write-ups
- [ ] Rewrite your resume to highlight transferable skills: problem-solving, attention to detail, communication, OS/network knowledge
- [ ] Target roles: **SOC Analyst L1**, **Security Analyst (Junior)**, **Cybersecurity Analyst Fresher**
- [ ] Apply broadly - your demonstrated lab work and any relevant prior experience together make a legitimate story for hiring managers

---

## A realistic note

You don't need to be "done" with this roadmap to start applying. Many people land an L1 SOC role partway through Phase 3, then keep learning on the job. Apply once you can talk confidently about logs, basic incident response, and have a couple of lab write-ups to show.
