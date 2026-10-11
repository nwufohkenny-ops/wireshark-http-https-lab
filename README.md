# Wireshark Lab: Examining HTTP and HTTPS Traffic

A GitHub portfolio project for documenting the lab **Using Wireshark to Examine HTTP and HTTPS Traffic**.

## Lab objectives
- Capture and inspect HTTP traffic.
- Capture and inspect HTTPS traffic.
- Compare readable HTTP form data with encrypted HTTPS application data.
- Document observations using screenshots, packet-capture analysis, and reflection answers.

## Repository structure
- `01-lab-documentation/` — lab overview, procedure, and report template.
- `02-command-reference/` — commands and Wireshark display filters.
- `03-screenshots/` — screenshots captured while completing the lab.
- `04-pcap-analysis/` — notes for analyzing HTTP and HTTPS packet captures.
- `05-findings/` — results and comparison of HTTP and HTTPS.
- `06-reflection/` — reflection questions and answers.

## Safety and privacy
Perform captures only in an authorized lab environment. HTTP captures may expose submitted form data. Do not commit real passwords, session cookies, tokens, private traffic, or sensitive PCAP files. The `.gitignore` excludes common capture files by default.

## Suggested workflow
1. Read `01-lab-documentation/README.md`.
2. Check your interface using `ip -br address`; the lab PDF uses `enp0s3` as an example.
3. Follow the command reference and capture HTTP and HTTPS traffic.
4. Open the captures locally in Wireshark and use the filters documented in `02-command-reference/`.
5. Add redacted screenshots to `03-screenshots/`.
6. Record evidence-based observations in `04-pcap-analysis/` and `05-findings/`.
7. Answer the questions in `06-reflection/`.
8. Review all files for sensitive information before committing and pushing to GitHub.

## Evidence status
This repository is a documentation template. Replace placeholders with your own results; do not claim a capture or finding unless you personally observed it.
