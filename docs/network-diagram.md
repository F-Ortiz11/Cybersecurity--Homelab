# Network Diagram

## Current Homelab Architecture

```text
                    Internet
                       |
                       |
              VMware NAT Gateway
                 192.168.154.2
                       |
              -------------------
              |                 |
              |                 |
          QE-DC01          QE-WIN11-01
      192.168.154.10      192.168.154.20
       Windows Server       Windows 11 Pro
        AD DS + DNS         Domain Client
              |
              |
      quantumedge.local
