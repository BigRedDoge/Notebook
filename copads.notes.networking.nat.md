---
id: yNhWal1LaEYxpWjNdiAvP
title: Nat
desc: ''
updated: 1645457923713
created: 1645456515507
---

## NAT

[Coax In $\rightarrow$ Modem] $\rightarrow$ [Router => LAN]

Router takes WAN IP Address and runs LAN DHCP server, which distributes IP addresses to devices on the server

[[DHCP|https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol]] (Dynamic Host Configuration Protocol):  A network management protocol used on Internet Protocol (IP) networks for automatically assigning IP addresses and other communication parameters to devices connected to the network


Port Forwarding: Forwards traffic coming into network to a specific machine

Ephemeral Ports: anything over 1024 that's not in use

NAT: Reformats packet to map source LAN IP/Port to desination WAN IP/Port
192.168.1.10:54321 $\rightarrow$ 129.21.312.12:80
