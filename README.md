# RUCKUS-RWG-Templates
Config Templates for the RUCKUS WAN Gateway.

# basic_microsegmentation.yml
One RADIUS realm, one WLAN, one VLAN pool and one network address.
Edit the template to match the following parameters in your environment:
- interface: change to match the LAN interface on your RWG.
- cidr: make sure the subnet does not conflict with your network.
- switch_ports: change to match the ports and infrastructure_device_id used by your ICX switch.
- infrastructure_device: change to match your SmartZone name.
- access_point_zone: change to match your zone.
  
# microseg_vlan_pool.yml
One RADIUS realm, one WLAN, one policy, one IP group, one VLAN pool and one network address.
Edit the template to match the following parameters in your environment:
- interface: change to match the LAN interface on your RWG.
- cidr: make sure the subnet does not conflict with your network.
- switch_ports: change to match the ports and infrastructure_device_id used by your ICX switch.
- infrastructure_device: change to match your SmartZone name.
- access_point_zone: change to match your zone.

# portals.yml
One policy, one splash portal, one landing portal, one survery question, one bandwidth queue and one shared credential.

# plans.yml
One account group, one free usage plan using a quota plan and a time plan, portal modifications. 

# billing.yml
One account group, one premium usage plan using unlimited quota and time plans, one merchant.
