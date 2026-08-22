# Common Ports

## Overview

A **port** is a logical communication endpoint used by network services.

Ports help the operating system identify which application or service should receive network traffic.

Port numbers range from **0 to 65535**.

---

## Common Ports

| Port | Protocol / Service | Purpose |
|------|--------------------|---------|
| 20 | FTP | FTP data transfer |
| 21 | FTP | FTP control |
| 22 | SSH | Secure remote access |
| 23 | Telnet | Remote access |
| 25 | SMTP | Sending email |
| 53 | DNS | Domain name resolution |
| 67/68 | DHCP | Automatic IP configuration |
| 80 | HTTP | Web traffic |
| 110 | POP3 | Receiving email |
| 111 | RPCbind | RPC service mapping |
| 135 | MSRPC | Microsoft RPC |
| 139 | NetBIOS | Windows network communication |
| 143 | IMAP | Receiving email |
| 161 | SNMP | Network management |
| 389 | LDAP | Directory services |
| 443 | HTTPS | Secure web traffic |
| 445 | SMB | Windows file and printer sharing |
| 3389 | RDP | Windows remote desktop |

---

## Important Ports for Cybersecurity

### Port 21 — FTP

**FTP (File Transfer Protocol)** is used for transferring files between systems.

FTP is generally not encrypted by default.

---

### Port 22 — SSH

**SSH (Secure Shell)** provides secure remote access to systems.

It is commonly used to remotely administer Linux and other systems.

---

### Port 23 — Telnet

**Telnet** provides remote terminal access.

It is insecure because communication is generally sent without encryption.

---

### Port 25 — SMTP

**SMTP (Simple Mail Transfer Protocol)** is used for sending email.

---

### Port 53 — DNS

**DNS (Domain Name System)** translates domain names into IP addresses.

Example:

    example.com → IP address

---

### Port 80 — HTTP

**HTTP (Hypertext Transfer Protocol)** is commonly used for web communication.

HTTP does not provide encryption by itself.

---

### Port 443 — HTTPS

**HTTPS (HTTP Secure)** is used for secure web communication.

It uses encryption through TLS.

---

### Port 445 — SMB

**SMB (Server Message Block)** is commonly used for Windows file and printer sharing.

It is an important service to understand during network security assessments.

---

### Port 3389 — RDP

**RDP (Remote Desktop Protocol)** is used for remote access to Windows systems.

---

## TCP and UDP

Ports can be used with different transport protocols, mainly:

- TCP
- UDP

### TCP

TCP is connection-oriented and provides reliable data delivery.

### UDP

UDP is connectionless and does not provide the same reliability mechanisms as TCP.

---

## Why Ports Are Important in Cybersecurity

Security professionals use ports to identify services running on a host.

For example:

    192.168.1.10:22

This indicates communication with port **22**, commonly associated with SSH.

During network reconnaissance, tools such as **Nmap** can scan ports to discover open services.

---

## Example

Suppose a scan shows:

    22/tcp   open   ssh
    80/tcp   open   http
    443/tcp  open   https

This suggests that the host has services associated with:

- SSH
- HTTP
- HTTPS

A security professional can then investigate those services for vulnerabilities and misconfigurations.

---

## Key Points

- A port identifies a logical communication endpoint.
- Port numbers range from 0 to 65535.
- Port 22 is commonly used by SSH.
- Port 53 is commonly used by DNS.
- Port 80 is commonly used by HTTP.
- Port 443 is commonly used by HTTPS.
- Port 445 is commonly used by SMB.
- Port 3389 is commonly used by RDP.
- Port scanning helps identify services running on a host.
- Nmap is commonly used for port scanning and service enumeration.

---

## Quick Revision

| Port | Remember |
|------|----------|
| 21 | FTP |
| 22 | SSH |
| 23 | Telnet |
| 25 | SMTP |
| 53 | DNS |
| 80 | HTTP |
| 110 | POP3 |
| 143 | IMAP |
| 161 | SNMP |
| 389 | LDAP |
| 443 | HTTPS |
| 445 | SMB |
| 3389 | RDP |

---

## Summary

Understanding common ports is essential for networking and cybersecurity. Knowing which services commonly operate on specific ports helps security professionals understand network traffic, perform reconnaissance, identify exposed services, and investigate potential security weaknesses.
