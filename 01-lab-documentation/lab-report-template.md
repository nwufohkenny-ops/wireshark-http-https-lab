# Lab Report: Wireshark HTTP and HTTPS

## 1. Overview
- **Date completed:** [YYYY-MM-DD]
- **Analyst:** [Your name or portfolio handle]
- **Environment:** [VM / OS]
- **Wireshark version:** [Version]
- **tcpdump version:** [Version]

## 2. Objectives
- [ ] Capture and inspect HTTP traffic
- [ ] Capture and inspect HTTPS traffic
- [ ] Compare visible HTTP data with encrypted HTTPS application data

## 3. Environment and interface
- Interface selected: [e.g., enp0s3 — verify on your VM]
- IP address (redact if needed): [Address]
- Why this interface was selected: [Explanation]

## 4. HTTP capture
- Capture filename (kept locally unless safely sanitized): `httpdump.pcap`
- Command used: [Paste command]
- Wireshark display filter: `http`
- Observed request type: [e.g., POST, if present]
- Fields visible in the request: [Describe only what you observed]
- Screenshot references: [Filenames in 03-screenshots]

## 5. HTTPS capture
- Capture filename (kept locally unless safely sanitized): `httpsdump.pcap`
- Command used: [Paste command]
- Wireshark display filter: `tcp.port == 443`
- Protocol/TLS details observed: [Describe]
- Was application data readable as plaintext? [Answer based on observation]
- Screenshot references: [Filenames in 03-screenshots]

## 6. Comparison
| Observation | HTTP capture | HTTPS capture |
|---|---|---|
| Display filter used | `http` | `tcp.port == 443` |
| Application content | [Your observation] | [Your observation] |
| Security implication | [Your analysis] | [Your analysis] |

## 7. Troubleshooting
- Issue: [What happened]
- Cause: [If known]
- Resolution: [What you tried]
- Evidence: [Screenshot or command output]

## 8. Conclusion
[Summarize what the captures demonstrated. Do not claim results that you did not observe.]

## 9. Evidence and privacy review
- [ ] Screenshots do not reveal real passwords, cookies, tokens, or personal data
- [ ] Raw PCAP files are not committed
- [ ] Findings match the evidence
