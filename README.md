# OSINT and DNS Reconnaissance Lab (Information Gathering)

This project demonstrates open-source intelligence (OSINT) techniques and DNS reconnaissance to gather public information about domains, historical web snapshots, and exposed documents using publicly accessible tools. Conducted as part of a cybersecurity lab at the University of Central Florida.

---

## 🎯 Objective

To develop hands-on experience in reconnaissance and footprinting techniques by:
- Investigating domain ownership and infrastructure
- Locating sensitive public documents through Google hacking
- Exploring archived websites via the Wayback Machine
- Scanning networks and resolving DNS entries

---

## 🛠️ Tools & Techniques Used

- `whois` command (domain registration lookup)
- Google Dorking (`filetype`, `inurl`, `site:`)
- Wayback Machine (web.archive.org)
- Nmap with `--script vuln`
- DNS reconnaissance (hostnames, subdomains, name servers)

---

## 🔍 Key Activities

1. **WHOIS Enumeration**
   - Gathered registrar, contact, and DNS information for domains like `brighthouse.com`.

2. **Google Hacking**
   - Used operators like `site:ece.ucf.edu filetype:doc ssn` to find sensitive files.

3. **Wayback Machine Lookup**
   - Searched for historical snapshots of `ucf.edu` and found information on past leadership and events.

4. **DNS Scanning**
   - Used `nmap --script vuln` to identify potential CVEs and open ports in simulated networks.

---

## 📸 Screenshots

> Upload your screenshots and replace these links

### WHOIS Lookup
![WHOIS Output](https://raw.githubusercontent.com/Aarushh19/osint-dns-recon-lab/main/Screenshot%202025-05-12%20184205.png)

### Google Dork Results
![Google Hacking](https://raw.githubusercontent.com/Aarushh19/osint-dns-recon-lab/main/Screenshot%202025-05-12%20184221.png)

### Wayback Machine Snapshot
![Wayback History](https://raw.githubusercontent.com/Aarushh19/osint-dns-recon-lab/main/Screenshot%202025-05-12%20184248.png)

### Nmap Vulnerability Scan
![Nmap Output](https://raw.githubusercontent.com/Aarushh19/osint-dns-recon-lab/main/Screenshot%202025-05-12%20184316.png)

---

## ✅ Learning Outcomes

- Gained practical skills in passive reconnaissance and intelligence gathering
- Understood the importance of web exposure and unsecured metadata
- Used publicly available tools to simulate attacker reconnaissance steps

---

## ⚠️ Disclaimer

All activities were conducted in a safe and ethical academic environment for educational purposes only. No real systems were harmed or compromised.

---

© Aarush Gupta | MS Cybersecurity & Privacy | University of Central Florida
