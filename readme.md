# Most Popular Services: AWS, Azure, and Google Cloud Platform

## The Models

- **Private Cloud**
  - The organization has total control of resources and security.
  - The organization must handle maintenance and hardware upgrades.
  - You own the datacenter.
  - The organization is responsible for operating the services.
  - Users outside the environment do not have access.

- **Public Cloud**
  - No expenses for vertical scaling.
  - Shared datacenter.
  - The service provider owns the services.
  - Access is provided via the internet.

- **Hybrid Cloud**
  - Combines public and private datacenters.
  - Offers more flexibility.
  - Suitable for large corporations.

- **Multi-Cloud**
  - Involves multiple models and service providers.
  - Ideal for large corporations.

---

## The Cost

- **The Consumption or Usage-Based Model**
  - Better correlates cost and outcomes for customers to evaluate return on investment and justify future spending.
  - Provides the best control of expenses.

- **CapEx (Capital Expenses)**
  - Involves physical structures.
  - Over time, the value and effect of these expenses decrease.

- **OpEx (Operational Expenses)**
  - Covers service expenses with constant payments.
  - Includes monthly payments.
  - Accounts for cloud resources with ongoing changes and maintenance.

## **IaaS**

Infrastructure as a Service (IaaS) delivers on-demand infrastructure resources via the cloud, such as compute, storage, networking, and virtualization. 

- Customers do not have to manage, maintain, or update their data center infrastructure but are responsible for the operating system, middleware, virtual machines, and any apps or data.

## **CaaS**

Containers as a Service (CaaS) delivers and manages all the hardware and software resources to develop and deploy applications using containers. Often considered a subset or extension of IaaS, CaaS uses containers instead of VMs as its primary resource.

- Developers and IT operations teams can use CaaS to develop, run, and manage applications without building and maintaining the infrastructure or platform to run and manage containers.
- Customers still need to write the code and manage their data and applications, but the cloud service provider manages and maintains the environment for deploying containerized apps.

## **PaaS**

Platform as a Service (PaaS) delivers and manages all hardware and software resources for developing applications through the cloud. 

- Developers and IT operations teams can use PaaS to develop, run, and manage applications without building and maintaining the infrastructure or platform.
- Customers still need to write the code and manage their data and applications, but the cloud service provider manages and maintains the environment.

## **SaaS**

Software as a Service (SaaS) provides the entire application stack, delivering a complete cloud-based application that customers can access and use. 

- SaaS products are fully managed by the service provider and come ready to use, including updates, bug fixes, and maintenance.
- Most SaaS applications are accessed through a web browser, eliminating the need to download or install anything on customer devices.

---

## SLA and High Availability

The SLA (*Service Level Agreement*) defines service availability:  
- A 99% SLA allows 1.68 hours of weekly downtime.  
- A 99.9% SLA reduces downtime to 10.1 minutes.  

High availability can be achieved by configuring redundancy across different locations, which is critical for disaster resilience.

---

## Creating Virtual Machines

The process of creating virtual machines in Azure is straightforward, offering options such as auto-restart, monitoring, and disk settings. Key configurations include:  
- Selecting the resource group.  
- Defining region, OS, and authentication type.

---

## Storage

Storage setup requires a unique account name and involves the following considerations:  
- **Region**: Where the storage resides.  
- **Performance**: Standard or Premium.  
- **Redundancy**: Options include LRS (locally redundant) or GRS (geo-redundant).  

Data can be managed using containers, file shares, and queues.

---

## Data Migration

Azure provides tools for migrating on-premises data to the cloud:  
- **AZ Copy**: Facilitates smaller data transfers.  
- **Azure Data Box**: Supports transferring large volumes (up to 800TB) using physical hard drives shipped to customers.

---

## Identity and Security

User management is handled through **Entra ID**, which defines permissions:  
- **Entra Connect**: Synchronizes on-premises users with the cloud.  
- Users can also be grouped and managed effectively.

---

## Defender for Cloud

This tool enhances security by offering:  
- Insights into the environment.  
- Recommendations and validations to improve protection.
