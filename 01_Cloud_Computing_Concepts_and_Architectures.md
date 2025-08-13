
# Cloud Computing Concepts and Architectures

---

## 1. Overview
Cloud computing is the delivery of computing services over the internet ("the cloud") to provide faster innovation, flexible resources, and economies of scale.  
The **CSA Security Guidance v4** starts with this domain because understanding cloud fundamentals is key before discussing security.

---

## 2. Cloud Definition (NIST)
According to **NIST SP 800-145**, cloud computing is:
> "A model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources… that can be rapidly provisioned and released with minimal management effort or service provider interaction."

---

## 3. Essential Cloud Characteristics
NIST defines **5 essential characteristics**:
1. **On-Demand Self-Service** — Customers can provision resources automatically without human interaction.
2. **Broad Network Access** — Services are available over the network and accessed via standard mechanisms (e.g., web browsers, APIs).
3. **Resource Pooling** — Multiple customers share resources with logical separation.
4. **Rapid Elasticity** — Resources can scale up/down quickly.
5. **Measured Service** — Usage is monitored and billed accordingly.

---

## 4. Cloud Service Models
### a) **IaaS** (Infrastructure as a Service)
- Virtualized hardware resources (compute, storage, networking).
- Example: AWS EC2, Azure Virtual Machines.
- Security: Customer responsible for OS patching, application security.

### b) **PaaS** (Platform as a Service)
- Provides platform & runtime environment.
- Example: AWS Elastic Beanstalk, Azure App Service.
- Security: Customer focuses on application security; provider handles OS & infrastructure.

### c) **SaaS** (Software as a Service)
- Fully managed applications delivered over the internet.
- Example: Google Workspace, Microsoft 365.
- Security: Customer responsible for user access, data protection.

---

## 5. Deployment Models
1. **Public Cloud** — Owned by providers, open to the public (AWS, Azure).
2. **Private Cloud** — Dedicated to one organization.
3. **Hybrid Cloud** — Combination of public and private.
4. **Community Cloud** — Shared by organizations with similar needs.

---

## 6. Shared Responsibility Model
Security responsibilities are divided:
- **Provider**: Physical infrastructure, hardware, underlying software.
- **Customer**: Data, application security, identity management.
- Example: AWS diagram — "Security *of* the cloud" vs "Security *in* the cloud".

---

## 7. Cloud Reference Architecture
Defined by **NIST SP 500-292**:
- **Cloud Consumers** — Use cloud services.
- **Cloud Providers** — Manage cloud services.
- **Cloud Brokers** — Manage usage, performance, and delivery.
- **Cloud Auditors** — Evaluate cloud services.
- **Cloud Carriers** — Provide connectivity.

---

## 8. Security Considerations
- **Data Security**: Encryption, data residency.
- **Identity Management**: Strong authentication & authorization.
- **Compliance**: GDPR, HIPAA, etc.
- **Availability**: Redundancy & failover.

---

## 9. Real-World Example
- **AWS S3 Misconfiguration** — Publicly exposed data buckets due to poor IAM policies.
- Lesson: Understand the **shared responsibility model** and configure resources securely.

---

## 10. Key Takeaways
- Know **NIST cloud definition & 5 characteristics**.
- Understand differences between **IaaS, PaaS, SaaS**.
- Remember **deployment models** and **shared responsibility**.
- Security starts at the **design stage**, not after deployment.
