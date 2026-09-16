# IP Addressing

| Device | Role | IP Address | Subnet Mask | Gateway | DNS |
|---|---|---|---|---|---|
| QE-DC01 | Domain Controller / DNS | 192.168.154.10 | 255.255.255.0 | 192.168.154.2 | 192.168.154.10 |
| QE-WIN11-01 | Windows 11 Client | 192.168.154.20 | 255.255.255.0 | 192.168.154.2 | 192.168.154.10 |
| VMware NAT Gateway | Virtual Router | 192.168.154.2 | 255.255.255.0 | N/A | N/A |

## Network

- Subnet: `192.168.154.0/24`
- DHCP Pool: `192.168.154.128 - 192.168.154.254`
- Static addresses are assigned outside the DHCP pool.
