# Investigations

## Security Investigations Portfolio

This repository contains structured incident investigations and network forensic analyses conducted using packet capture data and related artifacts.

Each investigation follows a consistent methodology:

- Establish scope and timeline
- Identify anomalous behavior
- Extract indicators of compromise
- Correlate network activity
- Map to MITRE ATT&CK (where applicable)
- Provide remediation recommendations

---

## Investigations

### 1. Phishing-to-C2 Network Investigation (TA577 Infrastructure)
Analysis of a phishing-delivered payload leading to automated DNS resolution bursts and encrypted outbound command-and-control behavior.

Focus Areas:
- HTTP object extraction
- DNS-to-TLS correlation
- SNI analysis
- Indicator validation
- Threat intelligence enrichment

[View Investigation](https://github.com/joshoharaa/network-forensics-investigations/blob/main/README.md)

---

2. Brute-Force Authentication Investigation (MITRE T1110)

Analysis of high-volume authentication attempts targeting multiple accounts, leading to successful compromise of a privileged administrator account.

Focus Areas:

- Authentication event analysis
- Brute-force pattern identification
- Failed and successful login correlation
- Source IP and geolocation analysis
- Threat intelligence enrichment

[View Investigation](https://github.com/joshoharaa/brute-force-investigation/blob/main/README.md)

---

3. Fileless PowerShell Malware Investigation (Encoded Command & IEX Execution)

Analysis of suspicious PowerShell execution involving an encoded command and execution policy bypass, used to download and execute a remote payload in memory under SYSTEM context.

Focus Areas:

- PowerShell commmand-line analysis
- Encoded command (Base64) decoding and inspection
- Execution policy bypass identification
- In-memory execution techniques (Invoke-Expression / IEX)
- Process tree and parent-child relationship analysis
- Network activity and outbound connection identification
- Fileless malware behaviour analysis
- Threat intelligence enrichment (domain/IP reputation)

[View Investigation](https://github.com/joshoharaa/fileless-malware-powershell-investigation/blob/main/README.md)

--- 

More investigations coming soon.
