# What Happens When You Type https://www.google.com in Your Browser?

This repository contains resources, diagrams, and explanations detailing the comprehensive journey of a web request from the moment you type "https://www.google.com" in your browser until you see the Google homepage.

## Overview

The blog post in this repository breaks down the complex process that occurs in milliseconds when accessing a website. It explores the full web stack journey, providing insights into networking, security, web architecture, and browser rendering.

## Key Topics Covered

### 1. DNS Lookup
- How domain names are converted to IP addresses
- The hierarchical query process (browser cache, OS cache, router cache, ISP DNS server, root nameservers)
- The role of recursive and authoritative DNS servers

### 2. TCP/IP Handshake
- The three-way handshake process (SYN, SYN-ACK, ACK)
- How a reliable connection is established
- IP routing across the internet

### 3. Firewall Check
- Security checks performed on packets
- Network and host-based firewall operations
- How firewalls allow or block connection attempts

### 4. HTTPS and SSL/TLS Handshake
- Certificate verification and validation
- Encryption key exchange process
- Establishing a secure, encrypted connection
- The role of Certificate Authorities

### 5. Request Reaches Load Balancer
- Load distribution methods
- How traffic is directed to appropriate servers
- High availability and redundancy mechanisms

### 6. Web Server Handles the Request
- Static content serving
- Request parsing and routing
- HTTP header processing

### 7. Application Server Logic
- Dynamic content generation
- Business logic execution
- User session management

### 8. Database Access
- Query processing
- Data retrieval operations
- Caching mechanisms

### 9. Response Sent Back to Browser
- Response packaging and compression
- Return journey through the network
- Browser rendering and display process

## Additional Resources

This repository includes:
- Detailed diagrams visualizing each step

## Contributors

This explanation is maintained by Holberton School students and is open for contributions to expand and improve the technical accuracy and detail.