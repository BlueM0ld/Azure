# Azure
Azure Notes


## What is cloud computing

- is a delivery of computing services over the internet by using pay as you go pricing model
- This helps you
	- Lower operating costs
	- run your infrastructure more efficiently
	- Scale applications accordingly to business needs  


## Why should I move to the cloud

- Teams can deliver features faster 

What does Azure offer

- Be ready for the future: Continuous innovation from Microsoft supports your development today and your product visions for tomorrow.

- Build on your terms: You have choices. With a commitment to open source, and support for all languages and frameworks, you can build how you want and deploy where you want to.

- Operate hybrid seamlessly: On-premises, in the cloud, and at the edge--we'll meet you where you are. Integrate and manage your environments with tools and services designed for a hybrid cloud solution.
- Trust your cloud: Get security from the ground up, backed by a team of experts, and proactive compliance trusted by enterprises, governments, and startups.



## How does Azure work ?

### What is the Azure portal 

- its a web based unified GUI console that provides an alternative to the command line tools 
	- Through the GUI you can build, manage and monitor everything
	- create custom dashboards and an view of resources
	- Configure accessibility 
- The portal is resilient and is has high availability - as its present in every azure data center 
- Updates continuously so has no downtime for maintenance activities 

## What is Azure MarketPlace

- Is a store that helps connect users with Microsoft partners independent software vendors offering solutions/services. All solutions are certified to run on Azure

## Azure Accounts

- To use azure services we need an azure subscription and account
- You can create multiple subscriptions to give separate business distinction
- You can start creating Azure resources within each subscription


## Discuss different types of cloud model - what are public, private and hybrid clouds 

### Deployment models

- Public Cloud
	- Services offered over the internet available for all
	- Cloud resources are owned by a third party
	- No capital payments to scale up
	- You only pay for what you use
	- Applications are easily provisioned and deprovisioned
- Private Cloud
	- Cloud resources are exclusively used by users from one business or org 
	- A private cloud can be physically located on prem or can be hosted by a third party
	- Hardware must be purchased for start-up and maintainance
	- Organisations have complete control resources and security
	- Organisations have complete control over resources and security
- Hybrid Cloud
	- Combines public and private cloud by allowing data and applications be shared between them.
	- Provides the most flexibility
	- Organizations determine where to run their applications and control security/compliance and legal requirements


## Describe cloud benefits and considerations


### What are some cloud computing advantages
- High availability
	- Depending on SLA (service level agreement) you can give provide zero down time on applications when errors occur
- Scalability : Vertical scaling and horizontal scaling
	- Scale VERITCALLY  to increase compute capacity by adding RAM/CPUs to a virtual machine
	- Scale HORIZONTALLY  to increase the compute capacity by adding instances of resources 
- Elasticity
	- Configure your applications with autoscaling so that they always have resources available
- Agility
	- Deploy and configure your app quickly with rapidly changing requirements
- Geo-distribution
	- Deploy your app to regional databases around the world 
- Disaster recovery
	- Using cloud based backup services, data replication and geo distribution

### Capital expenses VS operating expenses

- Capital Expenditure
	- Up-front spending of physical infrastructure then deducting the up front cost overtime
- Operational Expenditure [OpEx]
	- spending money on products and services now
	- Being billed for them now
	- There's no upfront cost
	- You pay for a service/product as you use it

## Cloud Computing is a consumption based model/ [OpEx]
- Users only pay for what they use
- There are many benefits of using a consumption based model
	- No upfront costs
	- No need to purchase and manage costly infrastructure - where users may not use it to its full capacity
	- You can pay for additional resources when they are needed
	- You can also stop paying for resources when they are not needed

## Describe different cloud services

what are cloud service models?
- There are 3 models : Iaas, Paas, Saas
	- Iaas (Infrastructure as a service) 
		- Closest to managing physical services where a cloud provider will keep the hardware up to date
		- However OS maintenance and network configuration is up to the cloud tenant
		- Is the most flexible category of cloud services
			- Advantages:
				- No CapEx - no upfront cost
				- Agility - applications can be provisioned and deprovisioned quickly 
				- Management - the user manages the services have provisioned
				- Consumption based model - organisations pay for what they use
				- Skills - Little needed as dependant on cloud provider
				- Cloud benefits - use the skills of the cloud provider to ensure workloads are secure and available
	- Paas (Platform as a service)
		- Managed by the hosting environment
		- Cloud provider manages the VMs and networking resources
		- Cloud tenant deploys their applications into the managed hosting environment
			- Advantages:
				- No CapEx - no upfront cost
				- Agility - More agile than IaaS as there's no need to configure servers for running applications
				- Consumption based model - organisations pay for what they use under OpEx Model
				- Productivity - Users can focus on application development only because the cloud provider handles all platform management
				- Cloud benefits - use the skills of the cloud provider to ensure workloads are secure and available
			- Disadvantages 
				- Platform limitations - may affect how the application runs

	- Saas (Software as a service)
		- Cloud provider manages all aspects of the application environment such as VMs and networking resources
		- Cloud tenant only needs to provide their data storage and applications  which is managed by the cloud provider
		- Advantages
			- No CapEx Users have no up-front costs.
			- Agility access to the latest software quickly and easily.
			- Pay-as-you-go pricing model. Users pay for the software they use on a subscription model, typically monthly or yearly, regardless of how much they use the software.
			- Skills. No deep technical skills are required to deploy, use, and gain the benefits of SaaS.
			- Flexibility. Users can access the same application data from anywhere
		- Disadvantages
			- Software limitations - Might affect how users work 
		






## What is serverless computing?


- Like PaaS, serverless computing enables developers to build applications faster by eliminating the need for them to manage infrastructure
-  cloud service provider automatically provisions, scales, and manages the infrastructure required to run the code.
-  "serverless" name comes from the fact that the tasks associated with infrastructure provisioning and management are invisible to the developer.
- enables developers to increase their focus on the business logic
-  increase their productivity, bring products to market faster, optimize resources and focus on innovation


## Azure subscriptions, managements and resources


- Resources: Resources are instances of services that you create, like virtual machines, storage, or SQL databases.
- Resource groups: Resources are combined into resource groups, which act as a logical container into which Azure resources like web apps, databases, and storage accounts are deployed and managed.
- Subscriptions: A subscription groups together user accounts and the resources that have been created by those user accounts. For each subscription, there are limits or quotas on the amount of resources that you can create and use. Organizations can use subscriptions to manage costs and the resources that are created by users, teams, or projects.
- Management groups: These groups help you manage access, policy, and compliance for multiple subscriptions. All subscriptions in a management group automatically inherit the conditions applied to the management group