# Pi-hole + WireGuard Home Network

This project documents my setup for a home network with improved privacy and ad-blocking, both locally and remotely.  
It combines **Pi-hole** for network-wide DNS filtering, **Unbound** for recursive DNS resolution, and **WireGuard (via PiVPN)** for secure remote access, alongside basic firewall protections.  
The goal is to learn hands-on network management and privacy practices while maintaining a functional, home-scale network.

---

## Project Overview
This project documents my journey building a secure and private home network using:

- **Pi-hole**: DNS-level ad blocking
- **Unbound**: recursive DNS resolution for privacy
- **WireGuard (via PiVPN)**: secure remote access
- **UFW Firewall**: network hardening and traffic control

The goal is to block ads, protect privacy, and maintain secure remote access while learning hands-on network and security practices.

---

## Setup So Far
- Installed Raspberry Pi OS Lite
- Configured Pi-hole with Unbound on port 5335
- Set up UFW rules to restrict DNS and VPN traffic
- Installed PiVPN (WireGuard) and created client profiles
- Verified ad-blocking works both locally and remotely

---

## Lessons Learned
- Difference between recursive DNS and forwarders
- Importance of DNSSEC for integrity and trust
- How accurate NTP sync impacts DNS validation
- Network isolation strategies for IoT vs. private devices (Trusted/Untrusted devices)

---

## Future Plans
- Expand to a **managed network** with:  
  - Proper **network segmentation** using VLANs  
  - **Managed switches** and **access points** capable of VLAN tagging  
  - Advanced **firewall solutions** like **OPNsense**  
- Refine automated monitoring, alerts, and logging  
- Explore optional **Tor routing** for an additional privacy mode

---

## Tools and References
- [Pi-hole Documentation](https://docs.pi-hole.net)  
- [PiVPN Setup Guide](https://pivpn.io)  
- [Unbound Configuration Guide for Pi-hole](https://docs.pi-hole.net/guides/dns/unbound/)

