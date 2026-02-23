# Networking

## What is a Network?

A network is a connection between devices that allows them to communicate with each other.

It enables systems to:

* exchange data
* access shared resources

### Examples from everyday life

* **Group of friends:** Connected through shared interests, hobbies, or skills
* **Supply chain:** Production → delivery → selling
* **Library:** Designed to store and retrieve information

### Real-world usage

Networking is used for:

* browsing websites
* sending messages
* streaming content

Networks are essential for modern digital communication.
Without them, services like Google or online messaging would not be possible.

---

## Types of Networks

Networks can be categorized based on:

* size
* connection type

### LAN (Local Area Network)

A LAN connects devices within a limited area such as:

* homes
* apartments
* schools

**Example:**
A computer connected to a printer in the same home network.

**Key characteristics:**

* high speed
* local communication

---

### WLAN (Wireless Local Area Network)

A WLAN is a type of LAN that uses wireless communication instead of cables.

**Example:**
A laptop connected to a home Wi-Fi network.

**Key characteristics:**

* no physical cables
* flexible device connection

---

### MAN (Metropolitan Area Network)

A MAN connects multiple LANs within a larger area such as a city.

**Example:**
A university with multiple buildings across a city connected to one network.

---

### WAN (Wide Area Network)

A WAN connects networks over very large distances, such as:

* across countries
* globally

**Example:**
A banking system connecting branches and ATMs.

The internet is the largest example of a WAN.

---

## OSI Model (Open Systems Interconnection)

The OSI model is a reference model that provides a standardized way to understand network communication.

It is divided into seven layers, each responsible for a specific part of the communication process.

---

### 7. Application Layer

* closest layer to the user
* includes applications like browsers or email clients

---

### 6. Presentation Layer

* ensures data is in a readable format
* handles formatting, encoding, encryption

---

### 5. Session Layer

* manages communication sessions
* establishes, maintains, and closes connections

---

### 4. Transport Layer

* delivers data between devices
* ensures reliable or efficient transmission (TCP / UDP)

---

### 3. Network Layer

* determines how data is routed
* selects the best path between networks

---

### 2. Data Link Layer

* handles communication within the same network
* ensures correct data transfer between devices

---

### 1. Physical Layer

* responsible for actual data transmission
* uses electrical signals, cables, or wireless signals


## TCP/IP Model

The TCP/IP model describes how data is transmitted across networks and is used in real-world communication.

It consists of four layers:

Application

Transport

Internet

Network Access

It is more practical than the OSI model and forms the foundation of modern networking.

### TCP vs UDP

TCP and UDP are two different ways to transmit data.

TCP: reliable, ensures data arrives correctly

UDP: faster, but no guarantee of delivery

Used depending on whether reliability or speed is more important.

## IP Addressing

An IP address is used to identify devices within a network.

It allows data to be sent from one device to another.

Key points:

each device needs a unique IP address

used for communication across networks

## Ports

Ports allow multiple services to run on a single device.

They act as communication endpoints for applications.

Examples:

web traffic

email services

## DNS

DNS translates domain names into IP addresses.

It allows users to access websites without remembering numerical addresses.

Example:

google.com → IP address

## Basic Network Communication

When accessing a website, multiple components work together:

DNS resolves the domain name

data is sent using TCP or UDP

IP addresses identify sender and receiver

data travels across networks to reach its destination

This process happens within milliseconds and forms the basis of internet communication.