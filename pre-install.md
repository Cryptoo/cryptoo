# Pre-installation instructions

## Home server

1. Download a [SystemRescueCd](http://www.sysresccd.org/Download) image, and burn it to an CD (if you have an optical drive in the server), or [copy it to a USB stick](http://www.sysresccd.org/Sysresccd-manual-en_How_to_install_SystemRescueCd_on_an_USB-stick) (if you don't).
1. Prepare another USB stick with:
  1. The most recent Gentoo [stage3-amd64-nomultilib](http://distfiles.gentoo.org/releases/amd64/autobuilds/current-stage3-amd64-nomultilib/) image
  1. The most recent [Portage snapshot](http://distfiles.gentoo.org/releases/snapshots/current/)
1. Sign up for a VPN account with a compatible provider.
  1. Compatible providers must:
    1. Use OpenVPN with certificate authentication (no password)
    1. Provide incoming port redirection
    1. Provide .ovpn configuration files with embedded certificates and resolved entry point IP addresses.
  1. Known-compatible VPN providers:
    * [AirVPN](https://airvpn.org/)
1. Sign up for a dynamic DNS account with a supported provider.
  1. Supported providers:
    * [No-IP](http://www.noip.com/)
