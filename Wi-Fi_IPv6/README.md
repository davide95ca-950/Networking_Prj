# Wi-Fi + IPv4/IPv6 + NAT

## Objective
Configure two separate networks (PYME and CASA) with multiple integrated services:  
- wireless network with **WPA2-PSK**,  
- **DHCP** for automatic addressing,  
- **NAT/PAT** for Internet access,  
- **IPv4/IPv6** enabled on part of the topology,  
- **port forwarding** rules to reach an internal server.  

## Topology
Home routers connected to the Internet with Wi-Fi clients.  

## Tasks performed
- SSID configuration and WPA2 security, with SSID broadcast disabled on the CASA network.  
- DHCP setup with pools and excluded addresses.  
- IPv4/IPv6 addressing on PYME and the IPv6-enabled PC.  
- NAT/PAT for external access.  
- Port forwarding towards the internal server.  

## Results
- Successful IPv4 and IPv6 pings.  
- Internal server reachable via HTTP/HTTPS from the outside.  
- DHCP working properly and stable Wi-Fi connection.  

## Project versions
- **pt4.zip**: archive with the initial topology.  
- **pt4_FV.pkt**: completed final version.

## Docs
- Topology Screenshot
