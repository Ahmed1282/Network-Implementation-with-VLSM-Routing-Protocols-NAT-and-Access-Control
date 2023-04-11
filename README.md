# Network-Implementation-with-VLSM-Routing-Protocols-NAT-and-Access-Control
Implemented in Cisco Packet Tracer

1. Used EIGRP in First Block for Routing, OSPF with area 1 in Second Block, Rip in Third Block, and OSPF with area 0 in the last block as mentioned on the top of each block.
2. Used Redistribution on Router6 and Router13 for connecting EIGRP with OSPF and OSPF with RIP.
3. All hosts in EIGRP, OSPF area 1, and RIP will get IP addresses from the "DHCP Server" present in the first block.
4. All hosts in OSPF area 0 will get hosts from the “DHCP Server” present in its own block. (named as web server in the picture)
5. Used VLSM in each network of the topology.
8. IMPLEMENT NAT in Router7 with the Network G. Use the Private IP Address given to you in the attached file for Natting.
9. One of the PCs of Network L will not be allowed to access the TFTP server. One of the PCs of Network E will not be allowed to access the Data server in the 1st block. All hosts connected in network A will not be allowed to access "Web Server".
10. The TFTP and Data servers do not need to have running services. They will simply be treated as hosts. You just need to block the access of those servers from respective networks. (Access List)
