# Deploy Two Palo Alto Networks Firewalls with Managed Disks

**This template is not supported by Palo Alto Networks.** 
</br>


[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattmclimans%2FPaloAltoNetworks%2Fmaster%2Fazure%2Ftwo-firewalls%2FazureDeploy.json)

### What is deployed?
1.  Two Palo Alto Networks VM-300 Series Firewalls with Managed Disks
      - Three network interfaces for each Firewall (management, untrust, trust) 
2.  Availability Set
3.  (If creating new VNET)
      - Three subnets: Management, Untrust, and Trust
