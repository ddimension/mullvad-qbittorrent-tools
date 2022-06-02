# mullvadd qBittorent tools

These tools allow you to create a port forwarding on the mullvad.net anonymizing service
and set this as listening port in qBittorrent.
If you have setup the mullvad wireguard VPN on the host with default route, complete
qBittorrent traffic inbound/outbound will be routed through the VPN. You will 
also be reachable for other bittorrent members.

Take care and run a tcpdump on your uplink interface. There should only be wireguard traffic!

## Configuration

Set your account and VPN Public Key of your wireguard configuration in bin/mullvad-qBittorrent-start.

## Usage

After that, run
```
# bin/mullvad-qBittorrent-start
```
in a terminal and wait for qBittorrent to start up.
