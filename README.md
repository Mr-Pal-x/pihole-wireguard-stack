# pihole-wireguard-stack
A Raspberry Pi-based DNS and VPN setup for network-wide ad-blocking and secure remote access.

# Pi-hole + WireGuard Home Network

A privacy-focused DNS and VPN stack for ad-blocking at home and on the go.

---

##Project Overview
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
- Network isolation strategies for IoT vs. private devices (Trusted/Untrusted networks)

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

