
# Wi-Fi + IPv4/IPv6 + NAT_ITA

## Obiettivo
Configurare due reti distinte (PYME e CASA) con più servizi integrati:  
- rete wireless con **WPA2-PSK**,  
- **DHCP** per l’assegnazione automatica,  
- **NAT/PAT** per l’accesso a Internet,  
- **IPv4/IPv6** su parte della topologia,  
- regole di **port forwarding** verso un server interno.

## Topologia
Router domestici collegati a Internet e client Wi-Fi.  

## Attività svolte
- Configurazione SSID e sicurezza WPA2, con broadcast SSID disattivato nella rete CASA.  
- Setup DHCP con pool e indirizzi esclusi.  
- Indirizzamento IPv4/IPv6 su PYME e PC-ipv6.  
- NAT/PAT per l’accesso esterno.  
- Port forwarding verso il server interno.  

## Risultati
- Ping IPv4 e IPv6 corretti.  
- Server interno raggiungibile via HTTP/HTTPS dall’esterno.  
- DHCP funzionante e connessione Wi-Fi stabile.


## Versioni del progetto
- **pt4.zip**: archivio con la topologia iniziale.  
- **pt4_FV.pkt**: versione finale completata.


# Wi-Fi + IPv4/IPv6 + NAT_ENG

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
