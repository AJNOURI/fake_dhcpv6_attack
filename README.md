Fake-DHCPv6 Attack
==================

Fake DHCPv6 attack : Small scapy script to launch DHCPv6 DoS attack againt Cisco DHCPv6 Server.

The purpose is to check whether your DHCPv6 server is vulnerable to CPU and memory resources exhaustion.
A DHCPv6 server in Rapid-Commit mode attributes IPv6 prefixes just by receiving unsollicited "SOLICIT" messages.

How to use the script:

1- Get the DHCPv6 sever MAC address by:
  - consulting the local neighbor table
  - pinging all DHCP agent multicast address FF02::1:2
2- Manually fill the script variable "macdst"

Please refer to the following deployment lab for more details:
http://cciethebeginning.wordpress.com/2012/01/27/dhcpv6-fake-attack/


![alt tag](https://cciethebeginning.files.wordpress.com/2012/01/012712_0920_dhcpv6fakea1.jpg)
