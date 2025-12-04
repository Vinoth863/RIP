# RIP
ROUTING INFORMATION POROTOCOL

RIPv2 routing was configured between two routers to enable dynamic routing between the 192.168.0.0/24 and 192.168.1.0/24 LAN networks. The routers were interconnected and RIPv2 was enabled on both devices to exchange route updates and establish connectivity between the two subnets.

# RIP CLI COMMANDS

Router# config terminal

Router(config)# router rip

Router(config-router)# network 192.168.0.0

Router(config-router)# network 192.168.1.0
