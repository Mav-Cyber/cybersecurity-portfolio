# Cybersecurity Portfolio — Maverick Franco

Welcome to my professional cybersecurity portfolio. This repository documents my competitive CTF experience, incident response methodology, and ongoing journey into cybersecurity. I'm currently pursuing my BACS degree with a specialization in cybersecurity, actively competing in National Cyber League, and building practical expertise in log analysis, network forensics, and incident response.

## 🎯 Core Competencies

**Log Analysis & Data Processing**
- Command-line text processing with `awk`, `grep`, `sed`, and specialized tools
- CSV and structured data analysis with pattern recognition
- Large-scale dataset aggregation and statistical analysis
- Investigation workflow optimization for rapid insights
- **Methodology**: Field-based filtering, conditional processing, and multi-stage data aggregation pipelines

**Windows Incident Response**
- Windows Event Log forensics and multi-stage attack timeline reconstruction
- Active Directory attack pattern identification and threat modeling
- PowerShell analysis, process tracking, and script forensics
- Lateral movement detection and compromise indicators
- **Methodology**: EventID mapping, cross-event correlation, temporal analysis

**Network Forensics & Protocol Analysis**
- Packet capture analysis and deep protocol inspection
- Covert channel detection and tunnel traffic analysis
- Wireshark/tshark for traffic investigation and anomaly detection
- TCP/IP fundamentals with practical threat hunting application
- **Methodology**: Multi-layer protocol reconstruction, payload extraction, carving

**Cryptanalysis & Authentication Security**
- Hash identification and password cracking strategy development
- Wordlist curation and targeted dictionary attack planning
- Encryption fundamentals and bitwise operation analysis
- Authentication mechanism evaluation (Kerberos vs NTLM)
- **Methodology**: Algorithm research, wordlist optimization, strategic rather than brute-force approaches

## 🏆 Competitive Experience

### National Cyber League (NCL) — Spring 2026

Actively participating in National Cyber League competitions across multiple domains:

**Practice Game**: Multi-domain CTF covering log analysis, network forensics, incident response, cryptanalysis, and more. Comprehensive testing of cybersecurity fundamentals across 9 competency areas.

**Individual Game**: April 10, 2026 — Solo competition testing specialized skills across all domains

**Team Game**: April 24, 2026 — Collaborative team-based competition emphasizing communication and coordinated problem-solving

📊 **Full Competition Reports**: See [NCL Spring 2026 Overview](./ncl-spring-2026/README.md) for detailed analysis and scouting reports

---

## 💼 Technical Skills Demonstrated

### Specialist Knowledge Areas

**Log Analysis & Data Investigation**
- Advanced awk programming for CSV processing
- Pattern matching with regex and specialized filters
- Aggregation and statistical analysis (sum, count, grouping)
- Multi-stage data pipelines and conditional logic
- Real-world application: Transaction data analysis, anomaly detection

**Windows Forensics & Incident Response**
- EventID interpretation (4624 successful logon, 4625 failed, 4662 object access, etc.)
- Attack timeline reconstruction from disparate log sources
- Lateral movement pattern recognition
- Credential compromise and privilege escalation identification
- Real-world application: AD compromise detection, attack chain analysis

**Network Traffic Analysis**
- Protocol-level traffic inspection and anomaly identification
- Custom protocol header detection and payload extraction
- Multi-layer packet analysis (ICMP tunneling, TCP stream recovery)
- Binary carving and embedded data extraction
- Real-world application: Covert channel detection, malware traffic analysis

**Cryptanalysis & Password Security**
- Hash type identification and algorithm research
- Wordlist effectiveness analysis and optimization
- Strategic attack planning (research before brute force)
- Bitwise operations and encoding scheme analysis
- Real-world application: Targeted password attacks, credential assessment

### Tools & Platforms
**Command-Line**: awk, grep, sed, cut, sort, uniq, find, strings, hexdump  
**Log Analysis**: Windows Event Viewer, PowerShell Get-WinEvent, jq  
**Network**: Wireshark, tshark, tcpdump, Scapy  
**Forensics**: binwalk, strings, hexdump, dd, file, carving tools  
**Password**: Hashcat, John the Ripper, wordlist curation  
**Scripting**: PowerShell, Bash, Python (forensics development)

### Frameworks & Methodologies
- **Structured Investigation**: Systematic hypothesis testing and evidence collection
- **Attack Analysis**: MITRE ATT&CK mapping and kill chain decomposition
- **Timeline Reconstruction**: Multi-source event correlation and chronological analysis
- **Threat Modeling**: Attacker perspective and compromise technique analysis
- **Incident Response**: Evidence preservation, chain of custody, and forensic rigor

---

## 📖 Case Studies & Methodology Documentation

### 1. **Log Analysis: Transaction Data Investigation**
Comprehensive CSV analysis demonstrating command-line data processing, field-based filtering, and aggregation techniques. Shows how systematic data analysis outperforms text searching for structured data.

**Key Lesson**: Standardized identifiers (MCC codes) are more reliable than text matching  
**Techniques**: Field-based filtering, conditional aggregation, header handling  
**Tools**: awk, grep, sort, uniq

→ [Detailed Write-Up](./ctf-writeups/ncl-mcc-easy-challenge.md)

---

### 2. **Incident Response: Multi-Stage Attack Analysis**
Complex Windows forensics case involving DCSync attack detection, unauthorized credential escalation, and lateral movement through Active Directory. Demonstrates attack timeline reconstruction and multi-stage threat analysis.

**Key Lesson**: Individual events are meaningful only in context; timeline analysis reveals intent  
**Techniques**: EventID correlation, IP analysis, temporal sequencing, lateral movement detection  
**Tools**: Windows Event Logs, PowerShell, grep patterns, XML parsing

→ [Detailed Write-Up](./ctf-writeups/ncl-adpocalypse-challenge.md)

---

### 3. **Network Forensics: Protocol Tunnel Detection**
Multi-layer protocol analysis extracting hidden data from tunnel traffic, reconstructing packets, and carving embedded files. Shows understanding of protocol stacks and covert channel mechanisms.

**Key Lesson**: Understanding protocol structure enables detection of channel abuse  
**Techniques**: Header analysis, payload extraction, packet reconstruction, binary carving  
**Tools**: tshark, Scapy, struct module, hexdump

→ [Write-Up Available upon Request](./ctf-writeups/)

---

### 4. **File Forensics: Format Recovery & Analysis**
Polyglot file analysis recovering embedded data from containers, demonstrating file format knowledge and carving techniques.

**Key Lesson**: File extensions are unreliable; actual content structures reveal truth  
**Techniques**: Hex analysis, chunk parsing, binary carving, format validation  
**Tools**: binwalk, hexdump, file, dd

→ [Write-Up Available upon Request](./ctf-writeups/)

---

## 📚 Learning Journey & Strategic Development

### Strongest Areas
✅ **Structured Problem-Solving**: Systematic approach to unknown challenges with hypothesis testing  
✅ **Methodology Over Tools**: Emphasizing understanding over memorization  
✅ **Research Skills**: Effective use of documentation and public resources  
✅ **Documentation**: Clear technical writing explaining complex processes  

### Current Focus Areas
🟡 **Advanced Cryptanalysis**: Building expertise with specialized tools and custom wordlist optimization  
🟡 **Network Protocol Mastery**: Deepening understanding of protocol-level threats and covert channels  
🟡 **Windows Memory Forensics**: Exploring memory analysis and advanced process forensics  
🟡 **Time Optimization**: Improving challenge completion speed while maintaining accuracy  

### Continuous Learning Strategy
📚 **Competitive Learning**: NCL competitions as structured learning environment  
📚 **Tool Expertise**: Deep dive into specialized security tools (Hashcat, Wireshark, etc.)  
📚 **Methodology Documentation**: Creating guides for future reference and knowledge sharing  
📚 **Hands-On Practice**: Regular CTF participation and home lab experimentation  

---

## 🗂️ Repository Navigation

- **[ncl-spring-2026/](./ncl-spring-2026/)** — NCL competition overview, methodology notes, and detailed analysis
- **[ctf-writeups/](./ctf-writeups/)** — Complete challenge documentation with methodology and lessons learned
- **[tools-and-techniques/](./tools-and-techniques/)** — Command reference guides, tool documentation, and technique analysis
- **[learning-resources/](./learning-resources/)** — Educational guides on Windows forensics, AD attacks, protocols, and forensic techniques
- **[about/](./about/)** — Personal context: my story, skills assessment, and career direction
- **[PORTFOLIO-STATUS.md](./PORTFOLIO-STATUS.md)** — Current projects, recent updates, and ongoing work

---

## 🔄 Key Principles

**Research Over Assumptions**  
Spending time understanding tools and techniques yields better results than guessing.

**Methodology Over Speed**  
Structured investigation produces reliable answers; rushing leads to errors.

**Honesty Over Perfection**  
Including learning experiences and challenges demonstrates real growth.

**Sharing Knowledge**  
Documentation helps others and reinforces personal understanding.

**Continuous Improvement**  
Each competition reveals new skills to develop and methodologies to refine.

---

## 🤝 Connect & Contact

**Professional Profiles**:
- 🔗 [GitHub](https://github.com/Mav-Cyber) — You are here
- 💼 LinkedIn: [Coming soon]
- 📧 Email: [Your email]

**Current Focus**: NCL Individual Game preparation and skill development

---

## 📝 Repository Status

**Last Updated**: May 26, 2026  
**Status**: 🟢 Active & Growing  
**Next Milestone**: Individual Game Competition (April 10, 2026)

This portfolio documents my cybersecurity learning journey. New case studies, tool guides, and methodology documentation are added as I progress through competitions and develop deeper expertise.

---

### 🎓 Educational Context

**Pursuing**: Bachelor of Applied Computer Science (BACS) with Cybersecurity Specialization  
**Current Course**: BACS 3001 Cybersecurity Fundamentals  
**Competition**: National Cyber League (NCL) Spring 2026  

---

**[Explore the portfolio →](./ncl-spring-2026/README.md)**
