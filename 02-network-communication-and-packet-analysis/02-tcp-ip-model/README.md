# TCP/IP Model

## Overview

The **TCP/IP Model** is the practical model that the Internet actually uses.

It is a simplified version of the OSI Model with **4 layers**.

Every website, application, and Internet communication uses this model.

## TCP/IP Model Layers

The TCP/IP Model consists of:

1. Application Layer
2. Transport Layer
3. Internet Layer
4. Network Access Layer

    Application Layer
    HTTP, HTTPS, DNS, FTP
            ↓
    Transport Layer
    TCP, UDP
            ↓
    Internet Layer
    IP, ICMP
            ↓
    Network Access Layer
    Ethernet, MAC, Wi-Fi

## 1. Application Layer

The **Application Layer** is responsible for user-facing network protocols and application communication.

### Common Protocols

- HTTP
- HTTPS
- DNS
- SMTP
- FTP

### Examples

- Web browsers
- Email applications
- Network applications

## 2. Transport Layer

The **Transport Layer** provides communication between applications and handles the delivery of data.

The two main protocols are:

- TCP
- UDP

### TCP

**TCP (Transmission Control Protocol)** provides reliable data delivery.

It ensures that data is delivered reliably and in the correct order.

### UDP

**UDP (User Datagram Protocol)** provides faster communication with less overhead.

It does not provide the same reliability and ordering mechanisms as TCP.

### Examples

TCP:
- Web browsing
- Email
- File downloads
- SSH

UDP:
- Gaming
- Video calls
- Live streaming
- DNS

## 3. Internet Layer

The **Internet Layer** is responsible for IP addressing and routing.

It determines the path that data takes across networks.

### Common Protocols

- IP
- ICMP

### Main Functions

- Logical addressing
- Routing
- Moving packets between networks

## 4. Network Access Layer

The **Network Access Layer** handles communication over the local network and the physical network medium.

It is associated with technologies such as:

- Ethernet
- MAC addressing
- Wi-Fi

This layer deals with how data is transmitted over the network connection.

## TCP/IP Model vs OSI Model

The TCP/IP Model has **4 layers**, while the OSI Model has **7 layers**.

The relationship can be represented as:

    OSI Model                 TCP/IP Model

    Application       ┐
    Presentation      │
    Session           ├──→ Application
                      │
    Transport         ───→ Transport

    Network           ───→ Internet

    Data Link         ┐
    Physical          ┴──→ Network Access

The TCP/IP Application Layer combines the functions of the OSI Application, Presentation, and Session layers.

The TCP/IP Network Access Layer combines functions associated with the OSI Data Link and Physical layers.

## Example: Sending a WhatsApp Message

When sending a message through an application:

    Application
         ↓
    WhatsApp formats the data
         ↓
    Transport
         ↓
    TCP/UDP handles transport
         ↓
    Internet
         ↓
    IP handles addressing and routing
         ↓
    Network Access
         ↓
    Data is transmitted through Ethernet or Wi-Fi

The receiving device processes the communication through the corresponding layers.

## Key Points

- TCP/IP is the practical model used by the Internet.
- TCP/IP has 4 layers.
- The Application Layer contains user-facing protocols.
- The Transport Layer uses TCP and UDP.
- The Internet Layer handles IP addressing and routing.
- The Network Access Layer handles local network and physical transmission.
- TCP provides reliable delivery.
- UDP provides faster communication with less overhead.
- The TCP/IP Model is a simplified model compared with the 7-layer OSI Model.

## Summary

The TCP/IP Model provides a practical way to understand how Internet communication works.

The four layers are:

    Application
    Transport
    Internet
    Network Access

Each layer performs a specific function, from application-level communication to the transmission of data across the network.
