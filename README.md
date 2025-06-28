# Nmap
Termux Terminal Android Command for Nmap.

To use `nmap` in Termux (the Android terminal emulator), you'll first need to install `nmap`, then you can run it just like on Linux.

1. Install nmap in Termux
```bash
pkg update && pkg install nmap

2. Example Usage Commands

**Scan a single IP address:**
```bash
nmap 192.168.1.1
```

**Scan a range of IPs:**
```bash
nmap 192.168.1.1-254
```

**Scan specific ports:**
```bash
nmap -p 80,443 192.168.1.1
```

**Aggressive scan (more detailed):**
```bash
nmap -A 192.168.1.1
```

**Scan your local network for live devices:**
```bash
nmap -sn 192.168.1.0/24
```

Replace `192.168.1.1` or the subnet with the IP/range you want to scan.
