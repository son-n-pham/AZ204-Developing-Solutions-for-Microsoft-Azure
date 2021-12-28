# AZ204-Developing-Solutions-for-Microsoft-Azure

## Azure Compute

Virtual Machine can be deployed by:
- Portal
- PowerShell
- Azure CLI
- ARM (Azure Resource Manager)

Secure and manage:
- Prevent intruder by hardening your network defenses
- Identify anyone or anything that wants to connect
- Fortify defenses by using encryption

Proper care and maintenance are important.
- Patching is important
- Keeping the programs and services up to date
- Scaling can be done automatically and manually

In critical applications, ensuring data always available is critical. This can be achieved by:
- Utilize virtual machine scale sets
- Backup data regularly
- Build with an expectation of failure

ARM templates: Preconfigured scrips used to deploy single VM or whole environment
- The template is in JSON
- The template can be a single file of multple "modularized" templates.
- The template can be deployed via: Azure portal, CLI, PowerShell, GitHub, Cloud Shell, REST API

ARM role in handling Azure requests

<img src="https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/media/overview/consistent-management-layer.png" alt="Resource Manager request model"/>![image](https://user-images.githubusercontent.com/79841341/147547891-ef8a9cc1-bbc5-40f7-8162-4a59da91a06f.png)


ARM overview:
https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/overview

