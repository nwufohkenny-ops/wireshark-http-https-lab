# 02 — Command Reference

Commands adapted to the supplied lab instructions. Confirm the interface name on your own VM before capturing traffic.

## Identify interfaces
```bash
ip address
ip -br address
```

## Capture HTTP traffic
```bash
sudo tcpdump -i enp0s3 -s 0 -w httpdump.pcap
```
Generate authorized test HTTP traffic in the lab, then press `Ctrl+C` to stop. The capture file is written to the terminal's current working directory.

## Capture HTTPS traffic
```bash
sudo tcpdump -i enp0s3 -s 0 -w httpsdump.pcap
```
Generate authorized HTTPS traffic, then press `Ctrl+C`.

## Wireshark display filters
```text
http
tcp.port == 443
```

## Helpful local checks
```bash
tcpdump --version
wireshark --version
ls -lh httpdump.pcap httpsdump.pcap
```

If your interface is not `enp0s3`, substitute the correct interface. Avoid publishing raw PCAP files because they may contain sensitive information.
