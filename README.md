
# ⬢ m4c-ne | Infrastructure Archive

> "Your desire to remain what you are is what ultimately limits you"

Technical documentation of my home server + pentesting lab. This repo details the  architecture, deployment and protection of my infrastructure. 

## Project Origin

m4c-ne is a project born to fulfill my necessity of calm, for me to trust my system I need to break it and build it back again. The development of a home server that I can manually build, break and reinforce is what gave m4c-ne the opportunity to exist 

## Core Philosophy

- **Extreme isolation** : Each module, segment and component are separated either logically, physically or both. The server contains a lab that will be in constant attack so it has to be strict to keep out malicious traffic.
- **Reliability** : The system shall operate 24/7, regardless of hardware or software constraints. Every change is rigorously tested, and I do not leave the chair until I am 100% certain of the system's integrity.
- **Observability** : Each single bit that is being processed by the machine shall be easily monitored either by proxmox UI or directly into a server display.

## The components

- [Hardware](hardware/Hardware.md) - Physical specs & resource allocation.
- [Network](network/Network.md) - Topology, VLANs & Firewall rules.
- [Core](core/Core.md) - Hypervisor configuration & Hardening.
- [Provisioning](provisioning/Provisioning.md) - Automation & Deployment scripts.
- [Apps](apps/Apps.md) - Deployed services & containers.
- [PentestingLab](pentestingLab/PentestingLab.md) - Isolated arenas & target inventory.
- [Maintenance](maintenance/Maintenance.md) - Backup logs & health checks.

## The archive

─────────────────────────────────────────────────────────── ⬡

### Disclaimer 

**The documentation of some modules in the environment will contain strong hacking principles, I do not take responsibility of malicious use of whatever knowledge is acquired exploring the project**

|─────────────────────────────────────────────────────────── ⬡

## A sneak peek of Tech Stack 

### Hypervisor & OS

![Proxmox](https://img.shields.io/badge/Proxmox_VE-orange?style=flat-square&logo=proxmox&logoColor=white) 
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)
![Metasploitable](https://img.shields.io/badge/Lab-Metasploitable-red?style=flat-square)

### Networking & Security

![VLAN](https://img.shields.io/badge/VLAN_Tagging-802.1Q-green?style=flat-square) 
![WireGuard](https://img.shields.io/badge/WireGuard-881717?style=flat-square&logo=wireguard&logoColor=white)
![Firewall](https://img.shields.io/badge/Firewall-nftables-blue?style=flat-square)

### Development & Automation
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

## *[ STATUS: In maintenance ]──╼*
