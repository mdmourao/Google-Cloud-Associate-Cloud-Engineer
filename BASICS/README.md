# Compute Engine

Create Virtual Machines

Example:

1. Create Instance (Select Region / Zone / Machine Configuration)  

We can deploy container inside of the VM  

We can creare instance templates (very useful)  

Snapshots can be created on VMs  

Prices - Standard (2cpu/8RAM) - 50$/mon

Preemptible Virtual Machines - Preemptible VM instances are available at much lower price—a 60-91% discount—compared to the price of standard VMs. However, Compute Engine might stop (preempt) these instances if it needs to reclaim the compute capacity for allocation to other VMs. Preemptible instances use excess Compute Engine capacity, so their availability varies with usage.  

https://console.cloud.google.com/compute/instanceGroups  - Managed instance groups (MIGs) let you operate apps on multiple identical VMs. You can make your workloads scalable and highly available by taking advantage of automated MIG services, including: autoscaling, autohealing, regional (multiple zone) deployment, and automatic updating. Use MULTIPLE ZONES - Like a kubernetes for VMs (interesting) Can do health checks and start a new VM if needed!

# App Engine

Build scalable apps in any language

# Kubernetes Engine

Containers!

Auto Pilot Mode - https://cloud.google.com/kubernetes-engine/docs/concepts/autopilot-overview?_gl=1*8zt0jw*_ga*MTAzODcyMjYuMTY3NjU4NjAzNw..*_ga_WH2QY8WWF5*MTY3NjY3MjY0NS4yLjEuMTY3NjY3NDA1OS4wLjAuMA..&_ga=2.203308817.-10387226.1676586037&_gac=1.128922878.1676672804.Cj0KCQiA6LyfBhC3ARIsAG4gkF-CfqJW3WdWUqBAiuaMntwo_HUjEet7seaZWnorDUPc_dEltXtHXoUaAhDCEALw_wcB  
 

# Cloud Functions

Run functions

Diference from App Engine - Cloud functions responds to events