---
title: "The Server"
description: "Tarratus is the heart of our infrastructure"
date: "2022-09-24"
author: "MetaMeute"
categories:
  - projects
tags:
  - projects
draft: false
---


Our server is a decommissioned HP DL380p G8. A Proxmox runs on it for administration. Basically, all Meute members can get access to create their own VMs.

## Hardware
- HP DL380p G8
- 128GB RAM
- 2x [Intel Xeon E5-2650v2](https://ark.intel.com/content/www/de/de/ark/products/75269/intel-xeon-processor-e52650-v2-20m-cache-2-60-ghz.html)
- p420i + BBU

## Storage
only 2.5 inch-HDDs/SSDs

| port | Serial number | state | installion |
| :---: | :---: | :---: | :---: |
| 1 | x | x | x |
| 2 | x | x | x |
| 3 | x | x | x |
| 4 | x | x | x |
| 5 | x | x | x |
| 6 | x | x | x |
| 7 | x | x | x |
| 8 | x | x | x |

## Networkports
| port | connected with | used as |
| :---: | :---: | :---: |
| p0 | Switch | uplink |
| p1 | Switch | uplink |
| p2 | - | - |
| p3 | - | - |

## VMs

| VM-Name | production | description |
| :---: | :---: | :---: |
| testVM | no | windows 11 |

## Container
| Container-Name | type | production | description |
| :---: | :---: | :---: | :---: |
| DHCP | lxc | yes | DHCP-Server for local network |
| VPN | lxc | yes | VPN-Server to get into the network |
| LDAP | lxc | no | beta phase |
| STATUS | lxc | yes | status.metameute.de |
| sharelatex | docker stack | yes | Share-Latex for Bachelor/Masterthesis |
| portainer | docker | yes | Docker-Mgmt |
| cadvisor | docker | yes | Monitoring |
