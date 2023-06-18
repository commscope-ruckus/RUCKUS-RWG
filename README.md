# RUCKUS-RWG-Templates
Config Templates for the RUCKUS WAN Gateway.

# microsegmentation.yml
Edit the template to match the following parameters in your environment:
- interface: change to match the LAN interface on your RWG.
- cidr: make sure the subnet does not conflict with your network.
- switch_ports: change to match the ports used by your ICX switch.
- infrastructure_device: change to match your SmartZone name.
- access_point_zone: change to match your zone.
