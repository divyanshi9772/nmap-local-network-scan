# Nmap Local Network Scan – Report

## Scanned Network Range:
`192.168.29.0/24`

## Devices Discovered and Ports:
- **192.168.29.1** (Router): Open ports: 80, 443, 7000, 7443, 8080, 8200, 8443
- **192.168.29.21** (Mobile): All ports closed ✅
- **192.168.29.24** (Smart Device): Open port 2869 (icslap)
- **192.168.29.153** (My PC): Risky ports found – 135, 139, 445, 1521, 8080, 903

## Actions Taken:
- Disabled File and Printer Sharing
- Blocked risky ports using Windows Firewall
- Confirmed using re-scan with Nmap

## Learnings:
- Used Nmap for basic reconnaissance
- Understood common services and associated risks
- Practiced network hardening to reduce exposure
