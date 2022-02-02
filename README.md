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



# Azure Fundamentals part 5: Describe identity, governance, privacy, and compliance features



Secure access to your applications by using Azure identity services



What is authentication?


Authentication is the process of establishing the identity of a person or service that wants to access a resource. It involves the act of challenging a party for legitimate credentials and provides the basis for creating a security principal for identity and access control. It establishes whether the user is who they say they are.

What is authorization?


Authentication establishes the user's identity, but authorization is the process of establishing what level of access an authenticated person or service has. It specifies what data they're allowed to access and what they can do with it.



What is Azure Active Directory?


Azure Active Directory (Azure AD) provides identity services that enable your users to sign in and access both Microsoft cloud applications and cloud applications that you develop


How does Azure AD compare to Active Directory?


Active Directory is related to Azure AD, but they have some key differences.

Microsoft introduced Active Directory in Windows 2000 to give organizations the ability to manage multiple on-premises infrastructure components and systems by using a single identity per user.

For on-premises environments, Active Directory running on Windows Server provides an identity and access management service that's managed by your own organization. Azure AD is Microsoft's cloud-based identity and access management service. With Azure AD, you control the identity accounts, but Microsoft ensures that the service is available globally. If you've worked with Active Directory, Azure AD will be familiar to you.

When you secure identities on-premises with Active Directory, Microsoft doesn't monitor sign-in attempts. When you connect Active Directory with Azure AD, Microsoft can help protect you by detecting suspicious sign-in attempts at no extra cost. For example, Azure AD can detect sign-in attempts from unexpected locations or unknown devices.




Who uses Azure AD?


Azure AD is for:
- IT administrators : Administrators can use Azure AD to control access to applications and resources based on their business requirements.
- App developers :Developers can use Azure AD to provide a standards-based approach for adding functionality to applications that they build, such as adding SSO functionality to an app or enabling an app to work with a user's existing credentials.
- Users : Users can manage their identities. For example, self-service password reset
- Online service subscribers
  
  Microsoft 365, Microsoft Office 365, Azure, and Microsoft Dynamics CRM Online subscribers are already using Azure AD.
  
  A tenant is a representation of an organization. A tenant is typically separated from other tenants and has its own identity.
  
  Each Microsoft 365, Office 365, Azure, and Dynamics CRM Online tenant is automatically an Azure AD tenant.



What services does Azure AD provide?


Azure AD provides services such as:
- Authentication
- Single sign-on
- Application management
  
  You can manage your cloud and on-premises apps by using Azure AD. Features like Application Proxy, SaaS apps, the My Apps portal (also called the access panel), and single sign-on provide a better user experience.
- Device management
  
  Along with accounts for individual people, Azure AD supports the registration of devices. Registration enables devices to be managed through tools like Microsoft Intune. It also allows for device-based Conditional Access policies to restrict access attempts to only those coming from known devices, regardless of the requesting user account.


What's single sign-on?


Single sign-on enables a user to sign in one time and use that credential to access multiple resources and applications from different providers.

With SSO, you need to remember only one ID and one password. Access across applications is granted to a single identity that's tied to the user, which simplifies the security model. As users change roles or leave an organization, access is tied to a single identity. This change greatly reduces the effort needed to change or disable accounts.


How can I connect Active Directory with Azure AD? Using Azure AD Connect


why? Connecting Active Directory with Azure AD enables you to provide a consistent identity experience to your users.

Azure AD Connect synchronizes user identities between on-premises Active Directory and Azure AD. Azure AD Connect synchronizes changes between both identity systems, so you can use features like SSO, multifactor authentication, and self-service password reset under both systems. Self-service password reset prevents users from using known compromised passwords.



What are multifactor authentication and Conditional Access?



What's multifactor authentication?


Multifactor authentication is a process where a user is prompted during the sign-in process for an additional form of identification. 

These elements fall into three categories:
- Something the user knows
  
  This might be an email address and password.
- Something the user has
  
  This might be a code that's sent to the user's mobile phone.
- Something the user is
  
  This is typically some sort of biometric property, such as a fingerprint or face scan that's used on many mobile devices.


What's Azure AD Multi-Factor Authentication?

Azure AD Multi-Factor Authentication is a Microsoft service that provides multifactor authentication capabilities.

- Azure Active Directory
  
  The Azure Active Directory free edition enables Azure AD Multi-Factor Authentication for administrators with the global admin level of access, via the Microsoft Authenticator app, phone call, or SMS code. You can also enforce Azure AD Multi-Factor Authentication for all users via the Microsoft Authenticator app only, by enabling security defaults in your Azure AD tenant.
  
  Azure Active Directory Premium (P1 or P2 licenses) allows for comprehensive and granular configuration of Azure AD Multi-Factor Authentication through Conditional Access policies (explained shortly).
- Multifactor authentication for Office 365
  
  A subset of Azure AD Multi-Factor Authentication capabilities is part of your Office 365 subscription.

For more information on licenses and Azure AD Multi-Factor Authentication capabilities, see Available versions of Azure AD Multi-Factor Authentication.



When can I use Conditional Access?


Conditional Access is useful when you need to:
- Require multifactor authentication to access an application.
  
  You can configure whether all users require multifactor authentication or only certain users, such as administrators.
  
  You can also configure whether multifactor authentication applies to access from all networks or only untrusted networks.
- Require access to services only through approved client applications.
  
  For example, you might want to allow users to access Office 365 services from a mobile device as long as they use approved client apps, like the Outlook mobile app.
- Require users to access your application only from managed devices.
  
  A managed device is a device that meets your standards for security and compliance.
- Block access from untrusted sources, such as access from unknown or unexpected locations.

Conditional Access comes with a What If tool, which helps you plan and troubleshoot your Conditional Access policies. You can use this tool to model your proposed Conditional Access policies across recent sign-in attempts from your users to see what the impact would have been if those policies had been enabled. The What If tool enables you to test your proposed Conditional Access policies before you implement them.

Where is Conditional Access available?


To use Conditional Access, you need an Azure AD Premium P1 or P2 license. If you have a Microsoft 365 Business Premium license, you also have access to Conditional Access features.

SUMMARY
- Authentication (AuthN) establishes the user's identity.
- Authorization (AuthZ) establishes the level of access that an authenticated user has.
- Single sign-on (SSO) enables a user to sign in one time and use that credential to access multiple resources and applications.
- Azure Active Directory (Azure AD) is a cloud-based identity and access management service. Azure AD enables an organization to control access to apps and resources based on its business requirements.
- Azure AD Multi-Factor Authentication provides additional security for identities by requiring two or more elements to fully authenticate. In general, multifactor authentication can include something the user knows, something the user has, and something the user is.
- Conditional Access is a tool that Azure AD uses to allow or deny access to resources based on identity signals such as the user's location.




Build a cloud governance strategy on Azure



The term governance describes the general process of establishing rules and policies and ensuring that those rules and policies are enforced.

When running in the cloud, a good governance strategy helps you maintain control over the applications and resources that you manage in the cloud. Maintaining control over your environment ensures that you stay compliant with:
- Industry standards, like PCI DSS.
- Corporate or organizational standards, such as ensuring that network data is encrypted.

Governance is most beneficial when you have:
- Multiple engineering teams working in Azure.
- Multiple subscriptions to manage.
- Regulatory requirements that must be enforced.
- Standards that must be followed for all cloud resources.

Control access to cloud resources by using Azure role-based access control



How is role-based access control applied to resources?


Role-based access control is applied to a scope, which is a resource or set of resources that this access applies to.

Here's a diagram that shows the relationship between roles and scopes.



Scopes include:
- A management group (a collection of multiple subscriptions).
- A single subscription.
- A resource group.
- A single resource.

Observers, Users managing resources, Admins, and Automated processes illustrate the kinds of users or accounts that would typically be assigned each of the various roles.

When you grant access at a parent scope, those permissions are inherited by all child scopes. For example:
- When you assign the Owner role to a user at the management group scope, that user can manage everything in all subscriptions within the management group.
- When you assign the Reader role to a group at the subscription scope, the members of that group can view every resource group and resource within the subscription.
- When you assign the Contributor role to an application at the resource group scope, the application can manage resources of all types within that resource group, but not other resource groups within the subscription.


When should I use Azure RBAC?


Use Azure RBAC when you need to:
- Allow one user to manage VMs in a subscription and another user to manage virtual networks.
- Allow a database administrator group to manage SQL databases in a subscription.
- Allow a user to manage all resources in a resource group, such as virtual machines, websites, and subnets.
- Allow an application to access all resources in a resource group.


How is Azure RBAC enforced?


Azure RBAC is enforced on any action that's initiated against an Azure resource that passes through Azure Resource Manager. Resource Manager is a management service that provides a way to organize and secure your cloud resources.

RBAC uses an allow model. When you're assigned a role, RBAC allows you to perform certain actions, such as read, write, or delete. If one role assignment grants you read permissions to a resource group and a different role assignment grants you write permissions to the same resource group, you have both read and write permissions on that resource group.


Who does Azure RBAC apply to?


You can apply Azure RBAC to an individual person or to a group. You can also apply Azure RBAC to other special identity types, such as service principals and managed identities. These identity types are used by applications and services to automate access to Azure resources.


How do I manage Azure RBAC permissions?


You manage access permissions on the Access control (IAM) pane in the Azure portal. This pane shows who has access to what scope and what roles apply. You can also grant or remove access from this pane.


Prevent accidental changes by using resource locks


A resource lock prevents resources from being accidentally deleted or changed.

Even with Azure role-based access control (Azure RBAC) policies in place, there's still a risk that people with the right level of access could delete critical cloud resources. Think of a resource lock as a warning system that reminds you that a resource should not be deleted or changed.


What levels of locking are available?


You can apply locks to a subscription, a resource group, or an individual resource. You can set the lock level to CanNotDelete or ReadOnly.
- CanNotDelete means authorized people can still read and modify a resource, but they can't delete the resource without first removing the lock.
- ReadOnly means authorized people can read a resource, but they can't delete or change the resource. Applying this lock is like restricting all authorized users to the permissions granted by the Reader role in Azure RBAC.


How do I delete or change a locked resource?


Although locking helps prevent accidental changes, you can still make changes by following a two-step process.

To modify a locked resource, you must first remove the lock. After you remove the lock, you can apply any action you have permissions to perform. This additional step allows the action to be taken, but it helps protect your administrators from doing something they might not have intended to do.

Resource locks apply regardless of RBAC permissions. Even if you're an owner of the resource, you must still remove the lock before you can perform the blocked activity.


Combine resource locks with Azure Blueprints


What if a cloud administrator accidentally deletes a resource lock? If the resource lock is removed, its associated resources can be changed or deleted.

To make the protection process more robust, you can combine resource locks with Azure Blueprints. Azure Blueprints enables you to define the set of standard Azure resources that your organization requires. For example, you can define a blueprint that specifies that a certain resource lock must exist. Azure Blueprints can automatically replace the resource lock if that lock is removed.



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