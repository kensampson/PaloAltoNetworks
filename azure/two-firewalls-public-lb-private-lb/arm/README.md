# Deploy 2 Palo Alto Networks Firewalls with Public LB & Private LB

</br>


[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattmclimans%2FPaloAltoNetworks%2Fmaster%2Fazure%2Ftwo-firewalls-public-lb-private-lb%2F%2Farm%2FazureDeploy.json)

### What is deployed?
1.  Two Palo Alto Networks VM-300 Series Firewalls with Managed Disks
      - Three network interfaces for each Firewall (management, untrust, trust) 
2.  New Availability Set
3.  Public Load Balancer (can specify a given number of ports to allow).
4.  Internal Load Balancer with HA Ports.
3.  New VNET
      - Three subnets: Management, Untrust, and Trust
