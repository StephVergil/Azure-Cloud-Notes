# Azure Cloud Presentation

## **What is Cloud Computing?**
Cloud computing is the delivery of computing services over the internet on a pay-as-you-go basis, eliminating the need for owning physical infrastructure. It includes:
- **Virtual Machines:** For running applications and hosting data.
- **Storage:** Scalable options for unstructured and structured data.
- **Databases:** Managed services for relational and NoSQL databases.
- **Networking:** Advanced networking solutions for secure and high-speed connections.

### **Key Components**
- **Cloud Providers:** Offer computational power, storage, and managed services.
- **Self-Service Provisioning:** Access cloud resources on-demand using any internet-connected device, anytime, anywhere.

---

## **Shared Responsibility Model**
Responsibilities for cloud security and management are shared between providers and customers based on the service model:
- **IaaS (Infrastructure as a Service):** Customers manage operating systems, applications, and data, while providers handle physical hardware and virtualization.
- **PaaS (Platform as a Service):** Providers manage the infrastructure, OS, and runtime, allowing customers to focus on application development.
- **SaaS (Software as a Service):** Providers handle everything; customers simply use the software.

### **Deployment Models**
- **Public Cloud:** Managed by third-party providers and accessible via the internet.
- **Private Cloud:** Exclusive to one organization for enhanced control and security.
- **Community Cloud:** Shared infrastructure for organizations with common goals.
- **Hybrid Cloud:** Combines public and private clouds to leverage benefits of both.

---

## **Cloud Security**
- **Authentication & Access Management:** Enforce multi-factor authentication (MFA) and role-based access control (RBAC).
- **Data Encryption:** Encrypt sensitive data at rest and in transit.
- **Auditing & Monitoring:** Continuously monitor resources and perform third-party audits.
- **High Availability & Elasticity:** Ensure resilience through redundancy and dynamic scaling.

---

## **Consumption-Based Model**
Cloud services operate on a consumption-based billing model:
- **CapEx (Capital Expenditure):** One-time hardware and software costs.
- **OpEx (Operational Expenditure):** Recurring costs based on cloud usage, providing financial flexibility.

---

## **Reliability and Performance**
- **Reliability:** Quick recovery from system failures with fault-tolerant designs.
- **High Availability:** Uptime guarantees backed by SLAs.
- **Scalability:**
  - **Vertical Scaling:** Increase resources like CPU or memory in a system.
  - **Horizontal Scaling:** Add new instances to distribute workloads.
- **Elasticity:** Automatically adjust resources to meet demand spikes.

---

## **Azure Storage Tiers**
1. **Hot Tier:** For frequently accessed data with low access latency.
2. **Cool Tier:** Optimized for infrequent access at lower costs.
3. **Archive Tier:** Ideal for rarely accessed data with significant cost savings.

**Blob Rehydration:** Temporarily move archived data to hot or cool tiers for faster access.

---

## **Azure Storage Services**
1. **Blobs:** For unstructured data.
   - **Page Blobs:** Designed for virtual machine disks.
   - **Block Blobs:** Suitable for storing large files like videos.
   - **Append Blobs:** Optimized for sequential write operations (e.g., logging).
2. **Azure Files:** Managed file shares accessible via SMB and NFS.
3. **Azure Queues:** Asynchronous message storage for decoupled communication.
4. **Azure Disks:** Persistent block storage for virtual machines.
5. **Azure Tables:** NoSQL storage for structured, schema-less data.

---

## **Azure Management Infrastructure**
1. **Resources:** Fundamental entities like VMs and databases.
2. **Resource Groups:** Logical containers for organizing resources.
3. **Subscriptions:** Used for billing and access control.
4. **Management Groups:** Hierarchically organize subscriptions for governance.

---

## **Azure Tools and Services**
- **Azure Virtual Machines (VMs):** Flexible virtual computing environments for development, testing, or disaster recovery.
- **Azure Functions:** Event-driven, serverless compute platform.
- **Azure Monitor:** Offers detailed insights into resource health and performance.
- **Azure Policy:** Automates compliance with organizational standards.
- **Azure Arc:** Enables multi-cloud resource management and monitoring.

---

## **Azure Monitoring and Governance**
- **Azure Advisor:** Personalized recommendations for cost savings, reliability, and security improvements.
- **Resource Tags:** Assign metadata for better resource organization and cost tracking.
- **Resource Locks:** Protect critical resources from accidental changes.
- **ARM Templates:** Simplify resource deployment with reusable JSON templates.

---

## **Study Tips and Example Questions**
1. **What deployment model combines public and private clouds?** Hybrid Cloud.
2. **Which Azure service generates alerts based on resource utilization?** Azure Monitor.
3. **Why are Azure resource tags important?** They help categorize and track costs.
4. **Which Azure tool facilitates serverless computing?** Azure Functions.

---

## **Resources**
- [Microsoft Azure Documentation](https://learn.microsoft.com/en-us/azure/)
- [Azure Storage Overview](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)
- [Azure Fundamentals Learning Path](https://learn.microsoft.com/en-us/training/paths/azure-fundamentals/)
- [Azure Monitor Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/)
- [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)
- [Azure Security Best Practices](https://learn.microsoft.com/en-us/azure/security/)
- [Azure Governance Features](https://learn.microsoft.com/en-us/azure/governance/)

---

For the complete presentation, access the PowerPoint: [Azure Cloud Presentation](https://github.com/StephVergil/Azure-Cloud_Presentation/blob/main/Azure_Cloud_Presentation.pptx)
