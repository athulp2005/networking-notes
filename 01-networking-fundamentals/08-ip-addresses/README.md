# IP Addresses

## Overview

An **IP address (Internet Protocol address)** is a logical address assigned to a device on a network.

It is used to identify a device and help deliver data to the correct destination.

---

## IPv4

**IPv4** stands for **Internet Protocol version 4**.

IPv4 addresses use **32 bits** and are written as four decimal numbers separated by dots.

### Example

    192.168.1.10

Each part can have a value from **0 to 255**.

---

## IPv6

**IPv6** stands for **Internet Protocol version 6**.

IPv6 was developed to provide a much larger number of addresses than IPv4.

IPv6 addresses use **128 bits** and are written using hexadecimal numbers separated by colons.

### Example

    2001:db8::1

---

## Public IP Address

A **public IP address** is an address used to identify a network or device on the Internet.

It must be globally unique within the public Internet.

### Example

    Internet
       |
    Public IP
       |
    Router / Network

---

## Private IP Address

A **private IP address** is used inside a private network such as a home, office, or internal organization network.

Private IP addresses are not directly routable across the public Internet.

### Common Private IPv4 Ranges

- 10.0.0.0 – 10.255.255.255
- 172.16.0.0 – 172.31.255.255
- 192.168.0.0 – 192.168.255.255

### Example

    192.168.1.10

---

## Static IP Address

A **static IP address** is an IP address that is manually configured or reserved so that it normally remains the same.

### Example

A server may use a static IP so other devices can consistently connect to it.

---

## Dynamic IP Address

A **dynamic IP address** is assigned automatically, commonly using **DHCP (Dynamic Host Configuration Protocol)**.

The address can change over time.

---

## Loopback Address

A **loopback address** refers to the local device itself.

For IPv4, the commonly used loopback address is:

    127.0.0.1

It is also commonly called **localhost**.

---

## IP Address Example

Consider:

    192.168.1.10

Here:

- `192.168.1.10` → IP address
- `192.168.1` → Network portion in a common /24 network
- `10` → Host portion in that example

The exact network and host portions depend on the **subnet mask or CIDR prefix**.

---

## Why IP Addresses Are Important in Cybersecurity

IP addresses are important in cybersecurity because security professionals use them to:

- Identify network hosts
- Understand network communication
- Investigate network traffic
- Perform network scanning
- Identify potential sources and destinations of traffic
- Configure firewalls and access controls

---

## Key Points

- An IP address identifies a device or network interface on an IP network.
- IPv4 uses 32-bit addresses.
- IPv6 uses 128-bit addresses.
- Public IP addresses are used on the Internet.
- Private IP addresses are used inside private networks.
- Static IP addresses normally remain unchanged.
- Dynamic IP addresses are assigned automatically and may change.
- `127.0.0.1` is the IPv4 loopback address.
- DHCP can automatically assign IP addresses.

---

## Summary

IP addresses are fundamental to network communication. IPv4 and IPv6 provide addressing systems for devices and networks, while public, private, static, and dynamic addressing are used in different networking situations.

Understanding IP addresses is essential for networking, penetration testing, network scanning, and cybersecurity.
