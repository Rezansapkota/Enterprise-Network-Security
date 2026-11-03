# Enterprise Network Security Project

### Cisco Packet Tracer

## About This Project

I created this enterprise network in Cisco Packet Tracer while learning networking through a Udemy course. I wanted to get more comfortable with how different network devices communicate and how networks are configured and secured.

Instead of only learning the theory, I followed the practical exercises and configured the routers, switches, VLANs, routing and security settings myself.

This project helped me understand how different parts of an enterprise network connect and how network traffic can be controlled.

## Network Topology

The network includes:

- 2 routers
- 6 switches
- 1 Cisco ASA firewall
- 4 servers
- 19 PCs
- Wireless devices

## What I Configured

### VLANs and Inter-VLAN Routing

I created VLANs to separate different parts of the network. I also configured trunk ports and inter-VLAN routing so devices in different VLANs could communicate when required.

### IP Addressing and Routing

I configured IP addresses, subnet masks and default gateways for the devices.

I also worked with RIP dynamic routing to allow communication between different networks.

### Network Security

I implemented different security features, including:

- Access Control Lists (ACLs)
- Switch port security
- Sticky MAC addresses
- Spanning Tree Protocol (STP)
- Cisco ASA firewall configurations

I used ACLs to control traffic between networks and tested whether the configured restrictions were working.

### Testing and Troubleshooting

After completing the configurations, I tested connectivity between devices using ping and other Cisco commands.

Some commands I used include:

```bash
show ip interface brief
show vlan brief
show interfaces trunk
show ip route
show access-lists
show port-security
show spanning-tree
```

I also used Packet Tracer to observe how packets travelled through the network.

## What I Learned

Working on this project helped me understand networking concepts more clearly, especially VLANs, routing, switching and ACLs.

I also became more comfortable using the Cisco CLI and checking configurations when something wasn't working as expected.

There are still areas I want to improve, particularly firewall configuration and more advanced network troubleshooting.



