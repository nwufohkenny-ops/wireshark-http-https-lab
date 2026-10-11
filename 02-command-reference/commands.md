# Commands and Expected Behavior

| Task | Command/filter | Expected behavior |
|---|---|---|
| List interfaces | `ip address` | Shows interfaces and addresses |
| Compact interface list | `ip -br address` | Shows interface names and address state |
| Start HTTP capture | `sudo tcpdump -i enp0s3 -s 0 -w httpdump.pcap` | tcpdump listens and writes packets to a file |
| Start HTTPS capture | `sudo tcpdump -i enp0s3 -s 0 -w httpsdump.pcap` | tcpdump listens and writes packets to a file |
| Stop capture | `Ctrl+C` | Stops capture and prints a packet summary |
| Filter HTTP in Wireshark | `http` | Displays packets Wireshark dissects as HTTP |
| Filter TCP port 443 | `tcp.port == 443` | Displays TCP packets using port 443 |

The interface and output vary by environment. Record what your system actually reports.
