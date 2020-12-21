# IEEE 802.1Q Tunnel Ports in a Service-Provider Network

Customer A using the VLAN range from 12-17 to achieve their HUB and SPOKE connectivity in between Headquarter router (CE-A1) and other routers (CE-A2 to CE-A7) as follows. Customer run OSPF to advertise route in between customer routers.



[alt text](https://github.com/[VLTSankalpa]/[ Q-in-Q-VLAN-Tunnels]/blob/[master]/ Picture1.png?raw=true)


But customer A’s network geographically spread between site 1 and site 2 the way CE-A1, CE-A2, CE-A3 and CE-A4 located in site 1 and CE-A5, CE-A6 and CE-A7 located in site 2. Therefore, customer A get L2VPN service from service provider to achieve connectivity. From the other hand customer B also have some requirement and getting L2VPN service from SP to achieve connectivity. To fulfill the requirement of this both customer and allow both of them to use same VLAN range to achieve connectivity SP use Q-in-Q Tunnels and Layer 2 Protocol Tunneling according to following figure.


[alt text](https://github.com/[VLTSankalpa]/[ Q-in-Q-VLAN-Tunnels]/blob/[master]/ Picture2.png?raw=true)

