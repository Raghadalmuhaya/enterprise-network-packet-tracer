 

# Enterprise Network - Cisco Packet Tracer 

 

A practical enterprise network project designed and configured using Cisco Packet Tracer. 

 

## Project Overview 

 

This project simulates an enterprise network with a headquarters and branch network. It demonstrates network segmentation, routing, network services, access control, and connectivity between multiple networks. 

 

## Network Features 

 

- VLAN 10 - Admin 

- VLAN 20 - Tech 

- VLAN 30 - Servers 

- VLAN 40 - Wireless 

- Inter-VLAN Routing 

- DHCP and DNS 

- Static Routing 

- Access Control List (ACL) 

- HTTP Web Server 

- FTP Server 

- Branch Network Connectivity 

- Network Printer 

- Wireless Access Point 

 

## IP Addressing 

 

| Network | Subnet | 

| --- | --- | 

| VLAN 10 - Admin | 192.168.10.0/24 | 

| VLAN 20 - Tech | 192.168.20.0/24 | 

| VLAN 30 - Servers | 192.168.30.0/24 | 

| VLAN 40 - Wireless | 192.168.40.0/24 | 

| Branch Network | 192.168.50.0/24 | 

| WAN Link | 10.10.10.0/30 | 

 

## Servers 

 

### DHCP/DNS Server 

 

- IP Address: 192.168.30.10 

- Services: DHCP and DNS 

 

### Web/FTP Server 

 

- IP Address: 192.168.30.20 

- Services: HTTP and FTP 

 

## Security 

 

An extended ACL is configured to restrict traffic from VLAN 10 (Admin) to VLAN 20 (Tech), while allowing other permitted traffic. 

 

## Routing 

 

Router-on-a-stick is used for inter-VLAN routing at the headquarters. 

 

Static routing provides connectivity between the headquarters and branch networks. 

 

## Testing 

 

The network was tested using: 

 

- ICMP ping tests 

- Inter-VLAN connectivity 

- ACL verification 

- Headquarters-to-branch connectivity 

- HTTP web access 

- FTP authentication and directory listing 

- Network printer connectivity 

 

## Network Topology 

 

![Network Topology](network-topology.png) 

 

## Tools 

 

- Cisco Packet Tracer 

- Cisco IOS CLI 

 

## Project File 

 

The complete Cisco Packet Tracer `.pkt` project file is included in this repository. 

 
