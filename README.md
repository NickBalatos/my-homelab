# My Cybersecurity Homelab

A hands-on lab where I learn network protocols, attacks and defenses by running
them myself, built alongside my MSc in Cybersecurity at Aalborg University.

Every lab follows the same cycle: **set it up → attack or generate traffic →
observe it (Wireshark, logs, caches) → explain what happened → defend against it.**

## Lab environment

Three VMs in VMware on an isolated subnet (`192.168.238.0/24`):

| Machine | Role | OS |
|---------|------|----|
| Kali | attacker | Kali Linux |
| ubuntua | victim / target | Ubuntu |
| ubuntub | victim / client | Ubuntu |

## Labs

| # | Lab | Topic | Status |
|---|-----|-------|--------|
| 01 | [ARP Spoofing (MITM)](lab01-arp-spoof/) | Layer 2 attack | ✅ Done |

Status: ✅ Done · 🔄 In progress · 📋 Planned

## Disclaimer

Everything here is done only against machines I own, inside an isolated lab
network, for learning purposes.
