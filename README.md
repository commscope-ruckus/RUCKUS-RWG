# RUCKUS-RWG-Templates
Config Templates for the RUCKUS WAN Gateway.

You may need to edit the templates to match the parameters in your environment, such as:
- interface: change to match the LAN interface on your RWG.
- cidr: make sure the subnet does not conflict with your network.
- switch_ports: change to match the ports used by your ICX switch.
- infrastructure_device_id: change to match the id used by your ICX switch.
- infrastructure_device: change to match your SmartZone name.
- access_point_zone: change to match your zone.

# basic_microsegmentation.yml
One RADIUS realm, one WLAN, one VLAN pool and one network address. One open wlan.

# dpsk_using_same_vlans.yml
Three RADIUS realms, three account groups, three VLANs and three network addresses. Six accounts. One wlan using DPSK.

# dpsk_using_vlan_pool.yaml
One RADIUS realm, one account groups, one VLANs and one network addresses. Two accounts. One wlan using DPSK.

# microsegmentation.yml
One RADIUS realm, one WLAN, one policy, one IP group, one VLAN pool and one network address. One open wlan.

# portals.yml
One policy, one splash portal, one landing portal, one survery question, one bandwidth queue and one shared credential.

# plans.yml
One account group, one free usage plan using a quota plan and a time plan, portal modifications. 

# billing.yml
One account group, one premium usage plan using unlimited quota and time plans, one merchant.

# pms_integration.yml
Integration with the RWG's MICRO FIAS simulator with DPSK mangling. You need to initialize the FIAS simulator in RWG.

The remove configuration folder contains templates to remove each of the config templates above.
