# Example Configs

This folder contains sanitized example configuration files for Pi-hole and WireGuard.  
These files are templates to help you set up your own system without exposing any sensitive data.

## Folder Structure

- `wireguard/` → Example WireGuard client/server configs  
- `pihole/` → Example Pi-hole config files:
  - `custom.list.example` → Custom DNS / blocked domains
  - `adlists.list.example` → Additional blocklists
  - `setupVars.conf.example` → Pi-hole setup variables

## How to Use

1. Copy the `.example` files to your system.  
2. Replace placeholders (`<...>`) with your real values.  
3. Keep sanitized files in the repo as reference. **Do not commit real keys or passwords.**

> Always sanitize sensitive information before committing or sharing configuration files.
