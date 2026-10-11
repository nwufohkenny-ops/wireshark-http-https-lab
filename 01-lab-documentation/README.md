# 01 — Lab Documentation

This folder contains the lab overview, step-by-step workflow, and report template.

## Source lab
**Lab - Using Wireshark to Examine HTTP and HTTPS Traffic**

## Objectives
1. Capture and view HTTP traffic.
2. Capture and view HTTPS traffic.
3. Compare what can be read in each capture.

## Requirements
- CyberOps Workstation VM (or an equivalent authorized Linux lab VM)
- Internet connection
- `tcpdump`
- Wireshark
- A browser

## Procedure summary
1. Identify the active interface with `ip address` or `ip -br address`.
2. Start an HTTP capture and generate HTTP traffic in the lab.
3. Stop the capture with `Ctrl+C`; open the resulting PCAP in Wireshark.
4. Apply the `http` display filter and inspect the POST request and form fields.
5. Start a separate HTTPS capture and visit a legitimate HTTPS website.
6. Stop the capture and open the PCAP in Wireshark.
7. Apply `tcp.port == 443` and inspect TLS/Application Data.
8. Record findings and add redacted screenshots to `03-screenshots/`.

Use only systems and accounts you are authorized to access. Do not submit real credentials to an HTTP site. If reproducing the source lab's HTTP demonstration, use only a controlled lab target and dummy credentials.

## Report
Complete `lab-report-template.md` with your actual environment, commands, screenshots, and observations.
