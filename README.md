cloud
=====
0.Introduction:
-> free and open-source cloud computing software platform
->solution to infrastructure as a service (IaaS)
Diagram from http://www.openstack.org/software/
1.Open Stack Compute :(NOVA)
-> provisions for large networks of VMs.
->ideal for heterogeneous infrastructure 
->accessible via APIs /dashboard
->can scale horizontally.

ARCHITECTURE
->high flexibility
->works with all virtualization techniques(HPC)
->uses KVM,VMware hypervisor
USE CASE DIAGRAM :  Service providers, IT departments,Processing Big Data, Scaling compute,HPC
FEATURES AND BENEFITS:

->VM Image Caching on compute nodes
->Floating IP addresses
->Security Groups
->Dashboard with fully integrated support for self-service provisioning

2.OPEN STACK STORAGE (SWIFT)
Object storage
->scalable redundant storage system
->distributed storage system
->multiple disk drives
->scale horizontally 
Block Storage (CINDER)
->persistent block-level storage devices
->support for  storage platforms (Ceph,Cloud Byte,SolidFire)
->appropriate for database storage, expandable file systems
->Snapshot management

FEATURES AND BENEFITS:
->Unlimited storage
->Multi-dimensional scalability (scale out architecture)
->Elastic data scaling
->Expiring objects
->Restrict containers per account
3.OPEN STACK NETWORKING (NEUTRON)

->real self service
->provides flexible networking models(VLAN ,flat n/w)
->manages IP addresses(static/DHCP)
->pluggable backend architecture 
->SDN,IDS,VPN

4.OPEN STACK DASHBOARD (HORIZON)
->GUI to control compute, storage and networking resources.
->size and state of cloud
->self-service portal

5.attach SCREENSHOTS 
1)DashBoard
2) creating an instance
3) the thing-you-were-trying-at-lab (pinging server?)

OPENSTACK TOOLS : eb?

