# 04 — PCAP Analysis Notes

Keep raw `.pcap` and `.pcapng` files locally. They are ignored by `.gitignore` because captures may contain sensitive information. Commit written analysis and sanitized screenshots instead.

## HTTP analysis
1. Open the HTTP capture in Wireshark.
2. Apply `http`.
3. Locate a request such as POST if one exists.
4. Expand the relevant form-encoded data section, if present.
5. Document the field names and what is visible, but do not publish actual credentials.

## HTTPS analysis
1. Open the HTTPS capture in Wireshark.
2. Apply `tcp.port == 443`.
3. Select a TLS Application Data packet if present.
4. Inspect the TLS details and note whether application content is readable.

## Analysis template
- Capture file: [Local filename]
- Display filter: [Filter]
- Packets examined: [Number or description]
- Protocol details: [Observed details]
- Application data visibility: [Observed details]
- Interpretation: [What the evidence supports]
