# Ubuntu VM in Existing Net
Deploy new Ubuntu VM into existing VNet and subnet


### Deployed Resources
- Microsoft.Compute/virtualMachines


### Parameters
- `vmName`: The name and hostname of the VM 
- `vmSize`: Size of the VMs to deploy 
- `username`: User name for the VM admin account 
- `sshKey`: SSH rsa public key for the VM admin account 
- `ubuntuVersion`: The Ubuntu version for the VM 
- `vnetName`: Name of existing VNet
- `subnetName`: Name of existing subnet

### Quick Deploy
[![deploy](https://raw.githubusercontent.com/benc-uk/azure-arm/master/etc/azuredeploy.png)](https://portal.azure.com/#create/Microsoft.Template/uri/)

### Notes

