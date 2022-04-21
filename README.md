# AZ-104
Plano de Estudos para Certificação AZ-104

## Manage Azure identities and governance (15–20%)

**Manage Azure Active Directory (Azure AD) objects**
- create users and groups 
[Doc1](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/add-users-azure-active-directory?context=/azure/active-directory/enterprise-users/context/ugr-context) 
[Doc2](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-groups-create-azure-portal?context=/azure/active-directory/enterprise-users/context/ugr-context)
[Lab1](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-groups-create-azure-portal?context=/azure/active-directory/enterprise-users/context/ugr-context)
- create administrative units
[Doc1](https://docs.microsoft.com/en-us/azure/active-directory/roles/admin-units-manage)
- manage user and group properties
[Doc1](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-users-profile-azure-portal?context=/azure/active-directory/enterprise-users/context/ugr-context)
[Doc2](https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/users-bulk-download)
[Doc3](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-manage-groups?context=/azure/active-directory/enterprise-users/context/ugr-context)
- manage device settings
[Doc1](https://docs.microsoft.com/en-us/azure/active-directory/devices/overview)
- perform bulk user updates
[Doc1](https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/users-bulk-add)
- manage guest accounts
[Doc1](https://docs.microsoft.com/pt-br/azure/active-directory/b2b/b2b-quickstart-add-guest-users-portal?WT.mc_id=AZ-MVP-5000031)
[Doc2](https://docs.microsoft.com/en-us/azure/active-directory/external-identities/what-is-b2b?context=/azure/active-directory/enterprise-users/context/ugr-context)
[Doc3](https://docs.microsoft.com/en-us/azure/active-directory/enterprise-users/users-restrict-guest-permissions)
- configure Azure AD join
[Doc1](https://docs.microsoft.com/pt-br/azure/active-directory/devices/concept-azure-ad-join?WT.mc_id=AZ-MVP-5000031)
- configure self-service password reset
[Doc1](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-deployment)
[Doc2](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-sspr-customization)

**Manage role-based access control (RBAC)**
- create a custom role
[Doc1](https://docs.microsoft.com/pt-br/azure/active-directory/roles/custom-create?WT.mc_id=AZ-MVP-5000031)
- provide access to Azure resources by assigning roles at different scopes
[Doc1](https://docs.microsoft.com/pt-br/azure/role-based-access-control/role-assignments-portal?WT.mc_id=AZ-MVP-5000031)
[Doc2](https://docs.microsoft.com/pt-br/azure/role-based-access-control/role-assignments-portal-subscription-admin)
[Doc3](https://docs.microsoft.com/pt-br/azure/active-directory/users-groups-roles/licensing-directory-independence?WT.mc_id=AZ-MVP-5000031)
- interpret access assignments
[Doc1](https://docs.microsoft.com/pt-br/azure/role-based-access-control/deny-assignments?WT.mc_id=AZ-MVP-5000031)

**Manage subscriptions and governance**
- configure Azure policies
[Doc1](https://docs.microsoft.com/pt-br/azure/governance/policy/overview?WT.mc_id=AZ-MVP-5000031)
- configure resource locks
[Doc1](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/management/lock-resources?WT.mc_id=AZ-MVP-5000031)
- apply and manage tags on resources
[Doc1](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/management/tag-resources?WT.mc_id=AZ-MVP-5000031)
- manage resource groups
[Doc1](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal)
[Doc2](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/management/move-resources-overview)
[Doc3](https://docs.microsoft.com/pt-br/azure/azure-resource-manager/management/delete-resource-group?tabs=azure-powershell)
- manage subscriptions
[Doc1](https://docs.microsoft.com/pt-br/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory?WT.mc_id=AZ-MVP-5000031)
- manage costs
[Doc1](https://docs.microsoft.com/pt-br/azure/cost-management-billing/?WT.mc_id=AZ-MVP-5000031)
- configure management groups
[Doc1](https://docs.microsoft.com/pt-br/azure/governance/management-groups/create?WT.mc_id=AZ-MVP-5000031)

## Implement and manage storage (15–20%)

**Secure storage**
- configure network access to storage accounts
- create and configure storage accounts
- generate shared access signature (SAS) tokens
- manage access keys
- configure Azure AD authentication for a storage account
- configure access to Azure Files

**Manage storage**
- export from Azure job
- import into Azure job
- install and use Azure Storage Explorer
- copy data by using AZCopy
- implement Azure Storage replication
- configure blob object replication

**Configure Azure files and Azure Blob Storage**
- create an Azure file share
- create and configure Azure File Sync service
- configure Azure Blob Storage
- configure storage tiers
- configure blob lifecycle management

## Deploy and manage Azure compute resources (20–25%)

**Automate deployment of virtual machines (VMs) by using Azure Resource Manager templates**
- modify an Azure Resource Manager template
- configure a virtual hard disk (VHD) template
- deploy from a template
- save a deployment as an Azure Resource Manager template
- deploy virtual machine extensions

**Configure VMs**
- configure Azure Disk Encryption
- move VMs from one resource group to another
- manage VM sizes
- add data disks
- configure networking
- redeploy VMs
- configure high availability
- deploy and configure virtual machine scale sets

**Create and configure containers**
- configure sizing and scaling for Azure Container Instances
- configure container groups for Azure Container Instances
- configure storage for Azure Kubernetes Service (AKS)
- configure scaling for AKS
- configure network connections for AKS
- upgrade an AKS cluster

**Create and configure Azure App Service**
- create an App Service plan
- configure scaling settings in an App Service plan
- create an App Service
- secure an App Service
- configure custom domain names
- configure backup for an App Service
- configure networking settings
- configure deployment settings

## Configure and manage virtual networking (25–30%)

**Implement and manage virtual networking**
- create and configure virtual networks, including peering
- configure private and public IP addresses
- configure user-defined network routes
- implement subnets
- configure endpoints on subnets
- configure private endpoints
- configure Azure DNS, including custom DNS settings and private or public DNS zones

**Secure access to virtual networks**
- create security rules
- associate a network security group (NSG) to a subnet or network interface
- evaluate effective security rules
- implement Azure Firewall
- implement Azure Bastion

**Configure load balancing**
- configure Azure Application Gateway
- configure an internal or public load balancer
- troubleshoot load balancing

**Monitor and troubleshoot virtual networking**
- monitor on-premises connectivity
- configure and use Azure Monitor for Networks
- use Azure Network Watcher
- troubleshoot external networking
- troubleshoot virtual network connectivity

**Integrate an on-premises network with an Azure virtual network**
- create and configure Azure VPN Gateway
- create and configure Azure ExpressRoute
- configure Azure Virtual WAN

## Monitor and back up Azure resources (10–15%)

**Monitor resources by using Azure Monitor**
- configure and interpret metrics
- configure Azure Monitor logs
- query and analyze logs
- set up alerts and actions
- configure Application Insights

**Monitor resources by using Azure Monitor**
- create a Recovery Services vault
- create a Backup vault
- create and configure backup policy
- perform backup and restore operations by using Azure Backup
- perform site-to-site recovery by using Azure Site Recovery
- configure and review backup reports
  


