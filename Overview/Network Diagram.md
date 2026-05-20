# Network Diagram

## Layout
- AT&T Fiber Router → HP Slimline (pfSense) → TP-Link Switch → All machines

## IP Scheme
| Machine | Role | IP Address |
|---|---|---|
| HP Slimline | pfSense Gateway | 10.0.0.1 |
| HP ProDesk | Proxmox | 10.0.0.10 |
| Toshiba C55 | Kali Linux | 10.0.0.20 |
| ASUS X540S | Metasploitable | 10.0.0.30 |
| Toshiba L875D | Security Onion | 10.0.0.40 |

## Subnet
10.0.0.0/24