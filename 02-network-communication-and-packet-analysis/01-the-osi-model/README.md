# The OSI Model

## Overview

The **OSI Model** stands for **Open Systems Interconnection Model**.

It is a conceptual model used to understand how network communication works.

The OSI Model divides network communication into **7 layers**.

Each layer has a specific responsibility.

---

## The 7 Layers

The OSI Model consists of:

1. Application
2. Presentation
3. Session
4. Transport
5. Network
6. Data Link
7. Physical

```text
+------------------+
| 7. Application   |
+------------------+
| 6. Presentation  |
+------------------+
| 5. Session       |
+------------------+
| 4. Transport     |
+------------------+
| 3. Network       |
+------------------+
| 2. Data Link     |
+------------------+
| 1. Physical      |
+------------------+
```

---

## 7. Application Layer

The **Application Layer** is the layer closest to the user.

It provides network services to applications.

### Common Protocols

- HTTP
- HTTPS
- DNS
- FTP
- SMTP

### Examples

- Web browsers
- Email applications

---

## 6. Presentation Layer

The **Presentation Layer** is responsible for how data is formatted and presented.

### Main Functions

- Data formatting
- Encryption
- Decryption
- Compression

---

## 5. Session Layer

The **Session Layer** manages communication sessions between devices.

### Main Functions

- Establishing sessions
- Maintaining sessions
- Terminating sessions

---

## 4. Transport Layer

The **Transport Layer** manages communication between devices.

It is responsible for transporting data.

### Main Functions

- Segmentation
- Reliable delivery
- Flow control
- Error recovery

### Common Protocols

- TCP
- UDP

### TCP

TCP provides reliable communication.

### UDP

UDP provides faster communication but does not provide the same reliability as TCP.

---

## 3. Network Layer

The **Network Layer** is responsible for logical addressing and routing.

It determines how data travels between different networks.

### Common Protocols

- IP
- ICMP

### Common Device

- Router

---

## 2. Data Link Layer

The **Data Link Layer** handles communication within a local network.

It uses **MAC addresses**.

Data at this layer is called a **Frame**.

### Common Technologies

- Ethernet
- Wi-Fi

### Common Devices

- Switch
- Bridge
- NIC

---

## 1. Physical Layer

The **Physical Layer** is responsible for physically transmitting data.

It transmits data using:

- Electrical signals
- Light signals
- Radio waves

### Examples

- Network cables
- Fiber optic cables
- Wireless signals

### Common Devices

- Hub
- Repeater

---

## Data Flow

When a device sends data, the data travels from:

```text
Application
     ↓
Presentation
     ↓
Session
     ↓
Transport
     ↓
Network
     ↓
Data Link
     ↓
Physical
```

When the receiving device receives the data, the process happens in reverse:

```text
Physical
     ↓
Data Link
     ↓
Network
     ↓
Transport
     ↓
Session
     ↓
Presentation
     ↓
Application
```

---

## Encapsulation

When sending data, each OSI layer adds its own information.

This process is called **Encapsulation**.

---

## Decapsulation

When receiving data, each layer removes the information added by the corresponding layer.

This process is called **Decapsulation**.

---

## Example

When you open a website:

1. The application creates a request.
2. The data travels down through the OSI layers.
3. Each layer performs its function.
4. The data is transmitted through the network.
5. The receiving device processes the data through the layers in reverse order.

---

## Key Points

- The OSI Model has 7 layers.
- Each layer has a specific responsibility.
- The Application Layer is closest to the user.
- The Transport Layer uses TCP and UDP.
- The Network Layer handles IP addressing and routing.
- The Data Link Layer uses MAC addresses.
- The Physical Layer transmits actual signals.
- Sending data uses encapsulation.
- Receiving data uses decapsulation.

---

## Summary

The OSI Model is a framework used to understand network communication.

It divides communication into seven layers. Each layer performs a specific function to help data travel from one device to another.

Understanding the OSI Model is important for networking and cybersecurity because it helps us understand how devices, protocols, and network communication work.
