# RIP
ROUTING INFORMATION POROTOCOL
# DEFINITION
RIP is a distance-vector routing protocol used to dynamically exchange routing information within a network. It determines the best path to a destination based on the hop count, which is the number of routers a packet must pass through.
# PROJECT DEFNITION
RIPv2 routing was configured between two routers to enable dynamic routing between the 192.168.0.0/24 and 192.168.1.0/24 LAN networks. The routers were interconnected and RIPv2 was enabled on both devices to exchange route updates and establish connectivity between the two subnets.

# RIP CLI COMMANDS

Router# config terminal

Router(config)# router rip

Router(config-router)# network 192.168.0.0

Router(config-router)# network 192.168.1.0
