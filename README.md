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



# Azure service level agreements and cost management

Migration to the cloud presents new ways to think about your IT expenses. The cloud also removes the burden of supporting IT infrastructure.

As you move to the cloud, you might ask:
- How much will it cost?
- What guarantees does Azure provide around uptime and connectivity?
- How do preview services impact my production applications?

Learn about the factors that influence cost, tools you can use to help estimate and manage your cloud spend, and how Azure's service-level agreements (SLAs) can impact your application design decisions.




Compare costs by using the Total Cost of Ownership Calculator


the Total Cost of Ownership (TCO) Calculator can help you compare the cost of running in the datacenter versus running on Azure.


What's the TCO Calculator?


The TCO Calculator helps you estimate the cost savings of operating your solution on Azure over time, instead of in your on-premises datacenter.

The term total cost of ownership is commonly used in finance. It can be hard to see all the hidden costs related to operating a technology capability on-premises. Software licenses and hardware are additional costs.

With the TCO Calculator, you enter the details of your on-premises workloads. Then you review the suggested industry average cost (which you can adjust) for related operational costs. These costs include electricity, network maintenance, and IT labor. You're then presented with a side-by-side report. Using the report, you can compare those costs with the same workloads running on Azure.



You don't need an Azure subscription to work with the TCO Calculator.


How does the TCO Calculator work?


Works on these 3 steps 
- Define your workloads : specs of on-prem infrastructure based on 4 cats
	- Servers
	  
	  This category includes operating systems, virtualization methods, CPU cores, and memory (RAM).
	- Databases
	  
	  This category includes database types, server hardware, and the Azure service you want to use, which includes the expected maximum concurrent user sign-ins.
	- Storage
	  
	  This category includes storage type and capacity, which includes any backup or archive storage.
	- Networking
	  
	  This category includes the amount of network bandwidth you currently consume in your on-premises environment.
- Adjust assumptions : whether your current on-premises licenses are enrolled for Software Assurance, which can save you money by reusing those licenses on Azure. You also specify whether you need to replicate your storage to another Azure region for greater redundancy.

- View the report: Choose a time frame between one and five years. the TCO Calculator generates a report that's based on the information you've entered. you can download, share or save this report


Purchase Azure services



During the meeting, some new questions arose as the discussion moves toward cloud migration:
- What types of Azure subscriptions are available?
- How do we purchase Azure services?
- Does location or network traffic affect cost?
- What other factors affect the final cost?
- How can we get a more detailed estimate of the cost to run on Azure?

It's important to learn how costs are generated in Azure so that you can understand how your purchasing and solution design decisions can impact your final cost


What types of Azure subscriptions can I use?


Azure offers both free and paid subscription options to fit your needs and requirements. They are:
- Free trial
  
  A free trial subscription provides you with 12 months of popular free services, a credit to explore any Azure service for 30 days, and more than 25 services that are always free. Your Azure services are disabled when the trial ends or when your credit expires for paid products, unless you upgrade to a paid subscription.
- Pay-as-you-go
  
  A pay-as-you-go subscription enables you to pay for what you use by attaching a credit or debit card to your account. Organizations can apply for volume discounts and prepaid invoicing.
- Member offers
  
  Your existing membership to certain Microsoft products and services might provide you with credits for your Azure account and reduced rates on Azure services. For example, member offers are available to Visual Studio subscribers, Microsoft Partner Network members, Microsoft for Startups members, and Microsoft Imagine members.


How do I purchase Azure services?


There are three main ways to purchase services on Azure. They are:
- Through an Enterprise Agreement
  
  Larger customers, known as enterprise customers, can sign an Enterprise Agreement with Microsoft. This agreement commits them to spending a predetermined amount on Azure services over a period of three years. The service fee is typically paid annually. As an Enterprise Agreement customer, you'll receive the best customized pricing based on the kinds and amounts of services you plan on using.
- Directly from the web
  
  Here, you purchase Azure services directly from the Azure portal website and pay standard prices. You're billed monthly, as a credit card payment or through an invoice. This purchasing method is known as Web Direct.
- Through a Cloud Solution Provider
  
  A Cloud Solution Provider (CSP) is a Microsoft Partner who helps you build solutions on top of Azure. Your CSP bills you for your Azure usage at a price they determine. They also answer your support questions and escalate them to Microsoft, as needed.


** need to expand on this long ass sub module 

https://docs.microsoft.com/en-us/learn/modules/plan-manage-azure-costs/5-estimate-workload-cost-pricing-calculator



Manage and minimize total cost on Azure



Understand estimated costs before you deploy


Read the relevant documentation to understand how each of your choices is metered and billed.

Calculate your projected costs by using the Pricing calculator and the Total Cost of Ownership (TCO) Calculator. Only add the products, services, and resources that you need for your solution.


Use Azure Advisor to monitor your usage

 identifies unused or underutilized resources and recommends unused resources that you can remove. 

Recommendations are sorted by impact: high, medium, or low. In some cases, Azure Advisor can automatically remediate, or fix, the underlying problem



Use spending limits to restrict your spending



Use Azure Reservations to prepay

Azure Reservations offers discounted prices on certain Azure services. Azure Reservations can save you up to 72 percent as compared to pay as you go


Choose low-cost locations and regions


But remember, some resources are metered and billed according to how much outgoing (egress) network bandwidth they consume. You should provision connected resources that are metered by bandwidth in the same Azure region to reduce egress traffic between them.


Research available cost-saving offers


Keep up to date with the latest Azure customer and subscription offers, and switch to offers that provide the greatest cost-saving benefit.


Use Azure Cost Management + Billing to control spending


Azure Cost Management + Billing is a free service that helps you understand your Azure bill, manage your account and subscriptions, monitor and control Azure spending, and optimize resource use.


Azure Cost Management + Billing features include:
- Reporting
  
  Use historical data to generate reports and forecast future usage and expenditure.
- Data enrichment
  
  Improve accountability by categorizing resources with tags that correspond to real-world business and organizational units.
- Budgets
  
  Create and manage cost and usage budgets by monitoring resource demand trends, consumption rates, and cost patterns.
- Alerting
  
  Get alerts based on your cost and usage budgets.
- Recommendations
  
  Receive recommendations to eliminate idle resources and to optimize the Azure resources you provision.


Apply tags to identify cost owners


Tags help you manage costs associated with the different groups of Azure products and resources. You can apply tags to groups of Azure resources to organize billing data.


Resize underutilized virtual machines


A common recommendation that you'll find from Azure Cost Management + Billing and Azure Advisor is to resize or shut down VMs that are underutilized or idle.

Be sure to properly plan for an outage, or shift your traffic to another instance while you perform resize operations.


Deallocate virtual machines during off hours

deallocate a VM means to no longer run the VM, but preserve the associated hard disks and data in Azure.

If you have VM workloads that are only used during certain periods, but you're running them every hour of every day, you're wasting money. These VMs are great candidates to shut down when not in use and start back when you need them, saving you compute costs while the VM is deallocated.


Delete unused resources

Regularly review your environment, and work to identify these systems. 

Migrate from IaaS to PaaS services

While you can think of IaaS as direct access to compute infrastructure, PaaS provides ready-made development and deployment environments that are managed for you.

Save on licensing costs



Choose cost-effective operating systems

 In some cases, the cost depends on which OS you choose. Either Linux or Windows

Use Azure Hybrid Benefit to repurpose software licenses on Azure

If you've purchased licenses for Windows Server or SQL Server, and your licenses are covered by Software Assurance, you might be able to repurpose those licenses on VMs on Azure.


https://docs.microsoft.com/en-us/learn/modules/plan-manage-azure-costs/8-summary