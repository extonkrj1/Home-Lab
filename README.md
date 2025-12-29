# Home-Lab# My Homelab

Proxmox-based virtualization lab for learning Linux administration.

## Overview
- Proxmox host running VMs: Ubuntu01 (Ansible control), UServer (Twingate + Squid Proxy), NAS (FreeNAS/ZFS)
- Secure remote access via Twingate
- Goals: Practice automation, networking, storage

## Network Diagram


## Services
- Squid Proxy: Configured on UServer, tested from Windows client
- Ansible: Playbooks for package management

## Setup Notes
### Proxmox Installation
### Squid Config
```conf
