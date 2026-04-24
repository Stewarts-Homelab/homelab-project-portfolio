# Secure Remote Access & Network Configuration

## Overview

This project focuses on securely accessing a home network remotely without exposing services directly to the internet. It includes VPN configuration, Cloudflare Tunnel setup, SSH access, and DNS/network troubleshooting.

---

## Objectives

* Enable secure remote access to internal services
* Avoid direct port forwarding where possible
* Improve network reliability and security
* Troubleshoot DNS and connectivity issues

---

## Technologies Used

* OpenVPN (TCP 443)
* Cloudflare Tunnel
* SSH
* ASUS Router (Asuswrt/Merlin)
* DNS (Cloudflare)
* Linux (Ubuntu)

---

## Key Implementations

### 1. OpenVPN Configuration

* Configured VPN over TCP 443 to bypass restricted networks
* Enabled secure remote access to internal network resources

### 2. Cloudflare Tunnel Setup

* Configured domain-based secure access without port forwarding
* Integrated with internal services for remote access

### 3. SSH Remote Access

* Established secure command-line access to internal systems
* Verified connectivity and authentication

### 4. DNS & Network Troubleshooting

* Diagnosed DNS resolution issues
* Tested Cloudflare DNS configurations
* Investigated router logs and time sync issues

---

## Challenges & Troubleshooting

* VPN connectivity issues in restricted environments
* DNS inconsistencies causing connection failures
* Router configuration conflicts (IPv6, DNS, NTP)

---

## Results

* Achieved secure remote access without exposing ports
* Improved reliability of network connectivity
* Developed hands-on experience with VPNs, DNS, and tunneling

---

## Skills Demonstrated

* Network configuration and troubleshooting
* Secure remote access implementation
* DNS configuration and analysis
* Log analysis and problem solving
