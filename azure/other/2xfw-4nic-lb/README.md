# Deploy Two Palo Alto Networks Firewalls with 4 NICs and LB

</br>


[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattmclimans%2FPaloAltoNetworks%2Fmaster%2Fazure%2Ftwo-firewalls%2FazureDeploy.json)

### Prerequisites
1.  Existing VNET with 4 subnets.  Load balancer can be placed in any subnet within the VNET.

### What is deployed?
1.  Two Palo Alto Networks VM-300 Series Firewalls with Managed Disks
      - Four network interfaces for each Firewall (management, untrust, trust) 
2.  Availability Set
3.  Internal Standard SKU Load Balancer
      - Three backend pools.
      - Three rules for each backend pool that use HA Ports.
4.  Public IP on ETH 0/1 and ETH 0/3
5.  NSG for Management Interfaces (ETH 0/1)
6.  NSG for Dataplane interfaces (ETH 1/1, 1/2, 1/3) 
