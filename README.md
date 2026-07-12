# Home Cybersecurity Lab

## Overview

This project documents the design and implementation of a virtual cybersecurity lab built using VirtualBox on an Apple Silicon (M1 Pro) Mac.

The environment simulates a small enterprise network for learning networking, Linux administration, Windows administration, penetration testing, and security monitoring.

---

## Objectives

- Build an isolated virtual network
- Configure static IP addressing
- Practice Linux and Windows administration
- Perform penetration testing in a safe environment
- Deploy a SIEM platform for monitoring

---

## Lab Architecture

| Machine | Operating System | Purpose | IP Address |
|----------|------------------|----------|------------|
| Kali | Kali Linux ARM64 | Attacker | 192.168.56.10 |
| Ubuntu | Ubuntu ARM64 | Linux Target | 192.168.56.30 |
| Windows | Windows 11 ARM | Windows Target | 192.168.56.20 |

---

## Network Design

Adapter 1
- NAT
- Internet access

Adapter 2
- Host-Only
- Internal lab communication

Subnet

192.168.56.0/24

---

## Project Status

- [x] Build VirtualBox Lab
- [x] Configure Host-Only Network
- [x] Install Kali Linux
- [x] Install Ubuntu
- [x] Install Windows
- [x] Verify Connectivity
- [x] Network Enumeration
- [x] Vulnerability Assessment
- [x] SIEM Deployment
