# 05 — Findings

Summarize only findings supported by your captures and screenshots.

## Finding template
For each finding, record:
- **Title**
- **Evidence:** screenshot filename and packet number/filter, if applicable
- **Observation:** what Wireshark actually displayed
- **Security relevance:** why it matters
- **Limitations:** what this capture does not prove

## Expected topics to investigate
- Whether HTTP request details or form fields are readable in the captured traffic.
- Whether HTTPS application data appears as encrypted TLS Application Data.
- Why encryption protects content in transit but does not automatically make a website trustworthy.

Do not paste real passwords, cookies, or session tokens into findings.
