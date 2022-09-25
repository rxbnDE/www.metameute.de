---
title: "Tarratus"
description: "Tarratus ist das Herzstück unserer Infrastruktur"
date: "2022-05-15"
author: "MetaMeute"
categories:
  - Projekte
tags:
  - Projekte
draft: false
summary: Unser Server ist ein ausgemusterter HP DL380p G8, der quasi alles hostet, was die MetaMeute benötigt. Vom Türstatus bis hin zu eigenen Projekten.
---

Unser Server ist ein ausgemusterter HP DL380p G8. Auf diesem läuft ein Proxmox zur Verwaltung. Grundsätzlich können alle Meute-Mitglieder Zugriff erhalten, um eigene VMs zu erstellen.

## Hardware
- HP DL380p G8
- 128GB RAM
- 2x [Intel Xeon E5-2650v2](https://ark.intel.com/content/www/de/de/ark/products/75269/intel-xeon-processor-e52650-v2-20m-cache-2-60-ghz.html)
- p420i + BBU

## Festplatten
nur 2.5 Zoll-Festplatten/SSDs

| Port | Festplatten-ID | Zustand | Einbau |
| :---: | :---: | :---: | :---: |
| 1 | x | x | x |
| 2 | x | x | x |
| 3 | x | x | x |
| 4 | x | x | x |
| 5 | x | x | x |
| 6 | x | x | x |
| 7 | x | x | x |
| 8 | x | x | x |

## Netzwerkports
| Port | verbunden mit | Funktion |
| :---: | :---: | :---: |
| p0 | Switch | uplink |
| p1 | Switch | uplink |
| p2 | - | - |
| p3 | - | - |

## VMs

| VM-Name | produktiv | Beschreibung |
| :---: | :---: | :---: |
| testVM | nein | windows 11 |

## Container
| Container-Name | Typ | produktiv | Beschreibung |
| :---: | :---: | :---: | :---: |
| DHCP | lxc | ja | DHCP-Server für Meute-Netz |
| VPN | lxc | ja | VPN-Server für Meute-Netz |
| LDAP | lxc | nein | Beta-Phase |
| STATUS | lxc | ja | status.metameute.de |
| sharelatex | docker stack | ja | Share-Latex für Bachelor/Masterarbeiten |
| portainer | docker | ja | Docker-Mgmt |
| cadvisor | docker | ja | Monitoring |
