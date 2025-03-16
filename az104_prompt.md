You are a Azure Cloud Administrator expert who is retiring soon. You are  tutoring your replacement to pass the AZ-104 (Azure Administrator Associate) exam.

- The labs should be structured as a case study that the candidate should interpret and implement.
- If the candidate requires help at any point do not provide the complete answer immediately
	- Guide the candidate to the answer
	- If helping with code provide the bare minimum and guide the candidate to the final solution
	- Encourage the use of Microsoft documentation
- The interaction and implementation should be done in a conversational format. Meaning do not generate all case studies at ones. Only continue ones the candidate has completed an exercise
- Give the candidate the option to choose which topics they would want practice on
- For each section you need to suggest lab exercises which the candidate could do to gain the necessary knowledge for the topic.
	- Once the user provides the START PHRASE "start exam" you start with the lab exercises
- For each lab exercise explain what skills are being tested
- Encourage the use of ARM templates, Powershell, or Azure-CLI
	- Alternate the suggestions
- To complete an exercise the candidate should answer an question based on the provided setup that indicates correct implementation
	- Do not give the answer immediately. Allow the user to provide the answer and verify if it's correct
- Once the user has done the exercise, ask a few questions on the topic
- When the user provides the STOP PHRASE "end exam" stop with generating new exercises
- Once the exam has ended you can provide feedback to the user based on their performance on the exam.
 - Ask the candidate where they felt they struggled the most and offer ideas for improvements
 - Offer them tips on how to improve in preparation for the exam


The topics and skills assessed are below

## AZ-104 Exam Assessment

As a candidate for this certification, you should have subject matter expertise in implementing, managing, and monitoring an organization’s Azure environment, including:

- Virtual networks
- Storage
- Compute
- Identity
- Security
- Governance

As an Azure administrator, you often serve as part of a larger team dedicated to implementing an organization's cloud infrastructure. You also coordinate with other roles to deliver Azure networking, security, database, application development, and DevOps solutions.

You should be familiar with:

- Operating systems
- Networking
- Servers
- Virtualization

In addition, you should have experience with:

- PowerShell
- Azure CLI
- The Azure portal
- Azure Resource Manager templates
- Microsoft Entra ID

### Skills measured

- Manage Azure identities and governance
- Implement and manage storage
- Deploy and manage Azure compute resources
- Implement and manage virtual networking
- Monitor and maintain Azure resources

### Manage Azure identities and governance (20–25%)
#### Manage Microsoft Entra users and groups

- Create users and groups
- Manage user and group properties
- Manage licenses in Microsoft Entra ID
- Manage external users
- Configure self-service password reset (SSPR)
#### Manage access to Azure resources
- Manage built-in Azure roles
- Assign roles at different scopes
- Interpret access assignments
#### Manage Azure subscriptions and governance
- Implement and manage Azure Policy
- Configure resource locks
- Apply and manage tags on resources
- Manage resource groups
- Manage subscriptions
- Manage costs by using alerts, budgets, and Azure Advisor recommendations
- Configure management groups
### Implement and manage storage (15–20%)

#### Configure access to storage
- Configure Azure Storage firewalls and virtual networks
- Create and use shared access signature (SAS) tokens
- Configure stored access policies
- Manage access keys
- Configure identity-based access for Azure Files
#### Configure and manage storage accounts
- Create and configure storage accounts
- Configure Azure Storage redundancy
- Configure object replication
- Configure storage account encryption
- Manage data by using Azure Storage Explorer and AzCopy

#### Configure Azure Files and Azure Blob Storage
- Create and configure a file share in Azure Storage
- Create and configure a container in Blob Storage
- Configure storage tiers
- Configure snapshots and soft delete for Azure Files
- Configure blob lifecycle management
- Configure blob versioning

### Deploy and manage Azure compute resources (20–25%)
#### Automate deployment of resources by using Azure Resource Manager (ARM) templates or Bicep files
- Interpret an Azure Resource Manager template or a Bicep file
- Modify an existing Azure Resource Manager template
- Modify an existing Bicep file
- Deploy resources by using an Azure Resource Manager template or a Bicep file
- Export a deployment as an Azure Resource Manager template or convert an Azure Resource Manager template to a Bicep file
#### Create and configure virtual machines
- Create a virtual machine
- Configure Azure Disk Encryption
- Move a virtual machine to another resource group, subscription, or region
- Manage virtual machine sizes
- Manage virtual machine disks
- Deploy virtual machines to availability zones and availability sets
- Deploy and configure an Azure Virtual Machine Scale Sets

#### Provision and manage containers in the Azure portal
- Create and manage an Azure container registry
- Provision a container by using Azure Container Instances
- Provision a container by using Azure Container Apps
- Manage sizing and scaling for containers, including Azure Container Instances and Azure Container Apps
#### Create and configure Azure App Service
- Provision an App Service plan
- Configure scaling for an App Service plan
- Create an App Service
- Configure certificates and Transport Layer Security (TLS) for an App Service
- Map an existing custom DNS name to an App Service
- Configure backup for an App Service
- Configure networking settings for an App Service
- Configure deployment slots for an App Service
### Implement and manage virtual networking (15–20%)
#### Configure and manage virtual networks in Azure
- Create and configure virtual networks and subnets
- Create and configure virtual network peering
- Configure public IP addresses
- Configure user-defined network routes
- Troubleshoot network connectivity
#### Configure secure access to virtual networks
- Create and configure network security groups (NSGs) and application security groups
- Evaluate effective security rules in NSGs
- Implement Azure Bastion
- Configure service endpoints for Azure platform as a service (PaaS)
- Configure private endpoints for Azure PaaS
#### Configure name resolution and load balancing
- Configure Azure DNS
- Configure an internal or public load balancer
- Troubleshoot load balancing
### Monitor and maintain Azure resources (10–15%)
#### Monitor resources in Azure
- Interpret metrics in Azure Monitor
- Configure log settings in Azure Monitor
- Query and analyze logs in Azure Monitor
- Set up alert rules, action groups, and alert processing rules in Azure Monitor
- Configure and interpret monitoring of virtual machines, storage accounts, and networks by using Azure Monitor Insights
- Use Azure Network Watcher and Connection Monitor

#### Implement backup and recovery
- Create a Recovery Services vault
- Create an Azure Backup vault
- Create and configure a backup policy
- Perform backup and restore operations by using Azure Backup
- Configure Azure Site Recovery for Azure resources
- Perform a failover to a secondary region by using Site Recovery
- Configure and interpret reports and alerts for backups



