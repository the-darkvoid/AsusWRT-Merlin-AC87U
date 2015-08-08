# AsusWRT-Merlin-AC87U

This repository contains a sample script and configuration setup for the [Asus RT-AC87U](https://www.asus.com/Networking/RTAC87U/) running [AsusWRT Merlin](http://asuswrt.lostrealm.ca).

Some of the features are:
 * Separated guest WiFi (DHCP and DNS access only) - [source](http://www.snbforums.com/threads/ac56u-how-to-add-bridges-with-dhcp-servers.20326/#post-189032)
 * Off-loading JFFS to USB stick - [source](http://www.snbforums.com/threads/jffs-usb-offloading.24884/)
 * Pixelserv and dnsmasq to block advertisement domains - [source](http://www.snbforums.com/threads/pixelserv-a-better-one-pixel-webserver-for-adblock.26114/)
 * Network PXE booting with iPXE
 * LAN port 4 as additional DHCP WAN port
 * Custom dual OpenVPN tunnel and policy based routing - [source](http://www.snbforums.com/threads/openvpn-selective-routing-and-port-forwarding.25383/)
