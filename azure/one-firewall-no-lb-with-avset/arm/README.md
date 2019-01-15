# Deploy 1 Palo Alto Networks Firewalls with AV Set

</br>


[<img src="http://azuredeploy.net/deploybutton.png"/>](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmattmclimans%2FPaloAltoNetworks%2Fmaster%2Fazure%2Fone-firewall-no-lb-with-avset%2F%2Farm%2FazureDeploy.json)

### What is deployed?
1.  Two Palo Alto Networks VM-300 Series Firewalls with Managed Disks
      - Three network interfaces for each Firewall (management, untrust, trust) 
2.  New Availability Set or use Existing Availability Set
3.  New VNET or use Existing VNET creating new VNET
      - Three subnets: Management, Untrust, and Trust
