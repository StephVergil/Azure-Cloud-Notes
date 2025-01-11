# Azure Cloud Presentation

## **What is Cloud Computing?**
Cloud computing is the practice of renting computer resources from a provider instead of owning them. It delivers computing services over the internet on a pay-as-you-go basis, such as:
- Virtual machines
- Storage
- Databases
- Networking

### **Key Components**
- **Cloud Providers:** Offer compute power (processing power) and storage capacity.
- **Self-Service Provisioning:** Access resources on-demand using any device, anytime, anywhere.

## **Shared Responsibility Model**
Responsibilities between provider and customer vary by service model:
- **IaaS:** Provides on-demand resources like VMs, networks, and storage.
- **PaaS:** Offers frameworks and tools for application development.
- **SaaS:** Subscription-based software (e.g., Office 365).

### **Deployment Models**
- **Public Cloud:** Owned by CSPs; accessible by anyone.
- **Private Cloud:** Dedicated to a single organization.
- **Community Cloud:** Shared by organizations with similar goals.
- **Hybrid Cloud:** Combines public and private clouds.

## **Cloud Security**
- Authenticate and manage user access.
- Encrypt data at rest and in transit.
- Apply updates and monitor usage.
- Conduct third-party audits.
- High availability and elasticity ensure security during disruptions.

## **Consumption-Based Model**
Pay only for resources used:
- **CapEx:** One-time costs like hardware.
- **OpEx:** Recurring costs like cloud subscriptions.

## **Reliability and Performance**
- **Reliability:** Systems recover from failures quickly.
- **High Availability:** Guaranteed uptime via SLAs.
- **Scalability:**
  - **Vertical:** Add CPU or RAM.
  - **Horizontal:** Add additional VMs.
- **Elasticity:** Adjust resources dynamically.

## **Azure Storage Tiers**
1. **Hot Tier:** High storage cost, low access cost (frequent data).
2. **Cool Tier:** Moderate costs (infrequent data).
3. **Archive Tier:** Low storage, high access cost (rarely used data).

**Blob Rehydration:** Move archival data to "hot" or "cool" tier for access.

## **Azure Storage Services**
1. **Blobs:** For unstructured data (documents, images).
   - **Page Blobs:** For virtual disks.
   - **Block Blobs:** For large files.
   - **Append Blobs:** For sequential additions (e.g., logs).
2. **Azure Files:** Managed SMB and NFS file shares.
3. **Azure Queues:** Message-based app communication.
4. **Azure Disks:** Persistent storage for VMs.
5. **Azure Tables:** Store structured NoSQL data.

## **Azure Management Infrastructure**
1. **Resources:** VMs, storage, or databases.
2. **Resource Groups:** Logical grouping of resources.
3. **Subscriptions:** Organize groups and set billing policies.
4. **Management Groups:** Apply governance to subscriptions.

## **Azure Tools and Services**
- **Azure VMs:** Customizable OS and apps for development or recovery.
- **Azure Functions:** Serverless compute for scalable execution.
- **Azure Monitor:** Tracks metrics and alerts.
- **Azure Policy:** Ensures compliance.
- **Azure Arc:** Manage resources across multi-cloud environments.

## **Azure Monitoring and Governance**
- **Azure Advisor:** Offers reliability, security, and cost recommendations.
- **Resource Tags:** Categorize and track costs.
- **Resource Locks:** Prevent accidental changes or deletions.
- **ARM Templates:** Automate deployments with JSON.

## **Study Tips and Example Questions**
1. **What cloud deployment model uses both public and private clouds?** Hybrid Cloud.
2. **What Azure service generates alerts based on resource utilization?** Azure Monitor.
3. **What is the purpose of Azure resource tags?** Categorize costs.
4. **Which Azure tool supports serverless computing?** Azure Functions.

---

This concise guide provides a comprehensive summary of Azure cloud services and concepts.
Link to PowerPoint: [Azure Cloud Presentation](https://github.com/StephVergil/Azure-Cloud_Presentation/blob/main/Azure_Cloud_Presentation.pptx)
