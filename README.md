# DHCP-DNS-Web-and-SMTP-Server-Setup-in-Packet-Tracer

A simple network project built in Cisco Packet Tracer. One router connects
three LANs: Office, Server Room and Lab. All servers sit in the Server Room.

## What it does
- DHCP server gives IP addresses automatically to all PCs
- DNS server resolves www.abc.com and mail.abc.com
- Web server shows a web page to every PC
- SMTP server lets users send and receive email (user1@abc.com, user2@abc.com)

## Network
| Place | Network | Gateway |
|---|---|---|
| Office | 192.168.10.0/24 | 192.168.10.1 |
| Server Room | 192.168.20.0/24 | 192.168.20.1 |
| Lab | 192.168.30.0/24 | 192.168.30.1 |

## Files
- `network.pkt`: the Packet Tracer file
- `report`: the full report with all configuration commands
