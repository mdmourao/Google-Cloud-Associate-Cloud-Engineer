# VPC networks

Virtual private cloud (VPCs includes subnets with 4 default firewall rules with multiple Routes)    

Examples:

IP addresses
Firewall rules

VPC network peering / Shared VPC

Cloud VPC Network Peering lets you privately connect two VPC networks, which can reduce latency, cost, and increase security. 

We can VPC network peering & Shared VPC to share networks. Usefull for DB/Redis/etc (...) Shared VPC  

Also check Cloud Router...  

Ref:  https://cloud.google.com/vpc/docs   

# Network Services

Load Balancers
DNS
Domains
CDN (static files)

192.168.1.0/20 4096 addresses  
192.168.1.0/12 1046576 addresses  

We can create load balancers (we need a VM!)  Outsite request (eg: http/https) goes to the load balancer the load balancer routes to the selected member of the instance group (backend service)  

# Hybrid Connectivity

VPN

A virtual private network lets you securely connect your Google Compute Engine resources to your own private network. Google VPN uses IKEv1 or IKEv2 to establish the IPsec connectivity.


# DNS

We can create zones

