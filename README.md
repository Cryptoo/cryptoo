# cryptoo

Cryptoo is privacy-focused version of Gentoo Linux which targets home servers and virtualized desktops.

It is currently under development and should be ready to use by summer of 2015.

Documentation and installation instructions will appear in this repository at that time.

## About

A Cryptoo server acts as a firewall and router for a home network as well as running various network services. Each service is isolated by running in a dedicated virtual machine (VM).

Cryptoo acts as an OpenVPN client (for routing all lan traffic through a VPN) and a OpenVPN server (to allow remote access to the lan). 

The server simulates several independent network zone, connected by firewall VMs. The network access of each VM is controlled by zone to which it is connected. The zones are:

  * DMZ (ISP-facing)
  * Tor
  * I2P
  * DMZ (VPN provider-facing)
  * Lan

Devices running in the lan zone can access Tor hidden services and I2P eepsites via transparent proxying, without requiring any any special configuration.

By running a Cryptoo home server, you can achieve the following:

* Participate in the Bitcoin, Namecoin, Bitmessage, Freenet, Tor, and I2P networks as a full peer
* Collect email from multiple accounts into a single collection point. Automatically and transparently send and receive email, bitmessages, Freenet mail, and I2P mail via any standard mail client.
* Secure web browsing and local network access when you're away from home via a personal VPN
* A central file/media server accessible to every device on your lan or VPN
* Run server-hosted Bittorrent (Deluge) which will download files on the server and automatically make them accessible via the local file server.

By running a Cryptoo workstation, you can achive the following:

* Spread your web browsing across multiple virtual machiens, so that if a single web browser is compromised the attacker will not gain access to everything.
  * This also improves your privacy because each web browser has its own unique fingerprint, therefore it's more difficult to correlate all your web activity to the same identity
* Keep services like instant messaging and mail reading in seperate virtual machines for improved security isolation and privacy
* Access your desktops from multiple devices. Virtualized desktops are accessed via SPICE protocol, so you can connect to them from a desktop PC or a remote laptop with equal ease.

## Installation

1. [Hardware requirements](hardware.md)
2. [Pre-installation](pre-install.md)
3. Installation instructions (coming soon)
