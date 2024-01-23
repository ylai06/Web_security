# DevOps and Cloud Infrastructure
- concept of security by design.
- difference between cloud and on-premises computing. 
- different deployment models. 
- different delivery models. 
- the concept of Infrastructure by Code.
## Security Myths 
- The cloud is secure by design
- The cloud is unsecure by design
- Someone else’s platform means it's someone else’s problem.
## Cloud Computing
A model for enabling convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction

### On-premises Computing vs. Cloud Computing
  
| On-premises | Cloud |
| :----:| :----: |
| Manually Provisioned | Self-provisioned |
| Dedicated Hardware | Shared Hardware |
| Fixed Capacity | Elastic Capacity |
| Pay for Capacity  | Pay for Use |
| Capital & Operational Expenses | Operational Expenses |
| Managed via Sysadmins | Managed via APIs |

### 5 characteristics of cloud computing
1. On-demand Self-Services
2. Shared/ pooled Resources
3. Broad Network Access
4. Scalable and Elastic(彈性)
5. Metered(計量) by use

### Cloud Computing Benefit
- Improved security
- Unlimited capacity
- Cost efficiencies
- Time efficiencies
- Power efficiencies
- Improved process control

### Cloud Deployed Models
- **Private**: Cloud infrastructure for a single organization only, managed by the organization or a 3rd party, on or off the premises. 
- **Public**: Cloud infrastructure is available to the general public, owned by an organisation selling cloud service services.  
- **Hybrid**: Combination of cloud types. 
- **Community**: Cloud infrastructure shared by several organizations that have shared concerns, managed by an organisation or 3rd party. 

### Cloud Security Architecture(CSA) 
![CSA-Cloud-security-architecture-Understanding-the-relationships-and-dependencies-between](https://github.com/ylai06/Web_security/assets/108776748/5d1a70d9-6116-43b9-b93d-4e45ed8804e7)

Cloud Reference Models:
- **IaaS**: Infrastructure as a Service is on-demand access to cloud-hosted physical and virtual servers, storage and networking - the backend IT infrastructure for running applications and workloads in the cloud.
  - Consumers can provision computing resources within the provider's infrastructure upon which they can deploy and run arbitrary software, including OS and applications.
  - Example: Virtual Machines, Virtual Networks.
- **PaaS**: Platform as Service is on-demand access to a complete, ready-to-use, cloud-hosted platform for developing, running, maintaining and managing applications.
  - Consumers can create custom applications using programming tools supported by the provider and deploy them onto the provider's cloud infrastructure
  - Example: Auto Elastic, Continuous Integration.
- **SaaS**: Software as Service is on-demand access to ready-to-use, cloud-hosted application software.
  - Consumers use the provider’s applications running on the provider's cloud infrastructure.
  - Example: Built for Cloud, Uses PaaS.
 
## DevOps
Combining Operations and Development:
- Network Operation + Code Development = People Culture

| Operation | Development |
| :----:| :----: |
| Developers | System admins |
| Front end | Network admins |
| Quality assurance | Database admins |


## Infrastructure by Code
Infrastructure by Code aims to bring the principles of version control, testing, and collaboration to the domain of infrastructure management.

Testing:
- **Unit testing**: Unit testing is code-level testing and takes the smallest testable code blocks and verifies their execution. We lump in formatters and linters in this category in case you are also familiar with those
- **Integration testing**: Integration testing is at the heart of infrastructure. Sure we can test code that builds the systems; however, the actual build and runtime have to be validated. Integration testing focuses on testing several components together with a fully assembled and running system.
- **Security testing**: we look for security tests for both positive and negative security attributes. By that, we can check for expected hardening of the system or test for possible weak spots.

  

  


