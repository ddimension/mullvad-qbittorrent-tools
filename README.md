mullvadd qBittorent tools

These tools allow you to create port forwarding on the mullvad anonymizing service
and set these as listening ports in qBittorrent.
If you have setup the mullvad wireguard VPN on the host with default route, complete
qBittorrent traffic inbound/outbound will be routed through the VPN. You will 
also be reachable for other bittorrent members.

Take care and run a tcpdump on your uplink interface. There should only be wireguard traffic.
