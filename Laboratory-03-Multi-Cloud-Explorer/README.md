# Laboratory Activity 3 – Multi-Cloud Explorer

## Mission 3: Become a Multi-Cloud Explorer

This laboratory activity is about learning how AWS, Microsoft Azure, and Google Cloud Platform are different from each other. I researched their main services, compared them, and matched each platform with different business situations.

---

# Checkpoint 1 – Expand Your Cloud Portfolio

I created a new folder named `Laboratory-03-Multi-Cloud-Explorer` inside my existing Cloud Computing GitHub repository.

The folder contains the following files and screenshots:

```text
Laboratory-03-Multi-Cloud-Explorer/
│
├── README.md
├── aws-research.md
├── azure-research.md
├── gcp-research.md
├── cloud-platform-comparison.md
├── client-recommendations.md
├── reflection.md
│
└── screenshots/
    ├── aws-homepage.png
    ├── azure-homepage.png
    ├── gcp-homepage.png
    ├── killercoda-terminal.png
    └── github-repository.png
```

---

# Checkpoint 2 – Explore the Three Cloud Platforms

## Amazon Web Services (AWS)

### Brief Overview

Amazon Web Services, or AWS, is a cloud platform from Amazon. It provides different services that can be used to run applications, store data, create networks, manage databases, and protect cloud resources.

### Global Infrastructure

AWS uses Regions and Availability Zones in different parts of the world. A Region is a geographic area, while Availability Zones are separate locations inside a Region. This setup helps applications remain available even when one location has a problem.

### Cloud Management Console

The AWS Management Console is a website where users can view, create, configure, and manage AWS services.

### Four Core Services

1. **Amazon EC2** – Provides virtual servers for running applications.
2. **Amazon S3** – Stores files and other objects in the cloud.
3. **Amazon VPC** – Creates a private network for AWS resources.
4. **AWS IAM** – Controls users, roles, and access permissions.

### Three Advantages

1. AWS has a large selection of cloud services.
2. It has infrastructure in many locations around the world.
3. Resources can be increased or decreased depending on the workload.

### Typical Enterprise Use Cases

AWS can be used for:

- E-commerce websites
- Mobile applications
- Company databases
- File and data storage
- Backup systems
- Web applications

### Screenshot

The AWS screenshot is located in:

`screenshots/aws-homepage.png`

---

## Microsoft Azure

### Brief Overview

Microsoft Azure is Microsoft's cloud computing platform. It provides services for virtual machines, storage, networking, databases, security, identity, and other business applications.

### Global Infrastructure

Azure has Regions and Availability Zones in different locations around the world. Companies can select locations that are appropriate for their users and applications.

### Cloud Management Console

Azure Portal is the web interface used to create and manage Azure resources. Users can also monitor their cloud services through the portal.

### Four Core Services

1. **Azure Virtual Machines** – Runs Windows or Linux virtual machines.
2. **Azure Blob Storage** – Stores files and other unstructured data.
3. **Azure Virtual Network** – Provides networking for Azure resources.
4. **Microsoft Entra ID** – Manages identities and access to resources.

### Three Advantages

1. Azure works well with Microsoft products.
2. It is useful for companies that already have Microsoft systems.
3. It supports both cloud and hybrid-cloud environments.

### Typical Enterprise Use Cases

Azure can be used for:

- Windows Server systems
- Business applications
- Microsoft-based company environments
- Databases
- Hybrid cloud systems
- Enterprise applications

### Screenshot

The Azure screenshot is located in:

`screenshots/azure-homepage.png`

---

## Google Cloud Platform (GCP)

### Brief Overview

Google Cloud Platform, commonly called Google Cloud, is Google's cloud computing platform. It provides services for computing, storage, networking, databases, artificial intelligence, machine learning, and container applications.

### Global Infrastructure

Google Cloud uses Regions and Zones around the world. These locations allow companies to place their applications and resources in different areas.

### Cloud Management Console

Google Cloud Console is the web-based interface used to create, configure, monitor, and manage Google Cloud resources.

### Four Core Services

1. **Compute Engine** – Provides virtual machines for running applications.
2. **Cloud Storage** – Stores files and objects in the cloud.
3. **VPC** – Provides networking for Google Cloud resources.
4. **Cloud IAM** – Controls identities, roles, and permissions.

### Three Advantages

1. Google Cloud has strong AI and machine learning services.
2. It has good support for Kubernetes and containerized applications.
3. It uses Google's global network infrastructure.

### Typical Enterprise Use Cases

Google Cloud can be used for:

- Artificial Intelligence projects
- Machine Learning applications
- Data analytics
- Web applications
- Kubernetes applications
- Cloud storage

### Screenshot

The Google Cloud screenshot is located in:

`screenshots/gcp-homepage.png`

---

# Checkpoint 3 – Compare the Major Cloud Platforms

| Category | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| Launch Year | 2006 | 2010 | 2008 |
| Compute Service | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| Storage Service | Amazon S3 | Azure Blob Storage | Cloud Storage |
| Networking Service | Amazon VPC | Azure Virtual Network | VPC |
| Identity Service | AWS IAM | Microsoft Entra ID | Cloud IAM |
| Primary Strength | Large variety of services | Microsoft integration | AI, ML, and Kubernetes |
| Ideal Organizations | Startups, enterprises, and many other organizations | Organizations using Microsoft technologies | AI, data, and cloud-native organizations |

## Questions and Answers

### 1. Which cloud provider offers the broadest range of services?

For me, AWS has the broadest range because it covers many areas of cloud computing. It has services for servers, storage, databases, networking, security, analytics, and other workloads.

### 2. Which provider best integrates with Microsoft technologies?

Microsoft Azure is the strongest choice when Microsoft technologies are already being used. It is designed to work well with products and services such as Windows Server, Microsoft 365, and Microsoft identity systems.

### 3. Which provider is strongest in Artificial Intelligence and Kubernetes?

I would choose Google Cloud for this because it has strong AI and machine learning services and provides Google Kubernetes Engine. These services are useful for companies that build AI applications and container-based systems.

### 4. Which cloud platform would you personally choose and why?

I would choose AWS because it gives me many options when building different kinds of projects. I also like that I can start with a small setup and add more services when the project becomes larger.

---

# Checkpoint 4 – Cloud Platform Recommendation Challenge

## Client A – Startup Company

### Recommended Platform: AWS

I would recommend AWS for the startup because the company has a limited budget but expects its mobile application to grow quickly. AWS has services that can be started with smaller resources and expanded when more users join the application. The company can also separate its application, storage, and database needs using different AWS services. This gives the startup room to grow without changing its whole cloud platform.

### Possible Services

- Amazon EC2
- Amazon S3
- Amazon RDS

---

## Client B – University

### Recommended Platform: Microsoft Azure

I would recommend Azure because the university already depends on Windows Server, Microsoft 365, and Active Directory. Moving to Azure would fit better with the technologies the university is already familiar with. Azure can also provide virtual machines and identity services for the university's existing systems. This can make the transition to cloud services more practical.

### Possible Services

- Azure Virtual Machines
- Microsoft Entra ID
- Azure SQL Database

---

## Client C – AI Research Company

### Recommended Platform: Google Cloud

I would recommend Google Cloud for the AI research company because its main requirement is Artificial Intelligence and Machine Learning. Google Cloud has services designed for AI workloads and also provides Compute Engine for high-performance computing needs. The company can also use Kubernetes when it needs to deploy applications using containers. These features match the type of work being done by the research company.

### Possible Services

- Compute Engine
- Vertex AI
- Google Kubernetes Engine

---

## Client D – Global E-Commerce Company

### Recommended Platform: AWS

I would recommend AWS because the company serves customers from different parts of the world and needs its website to stay available. AWS provides services that can distribute traffic and automatically adjust resources when demand changes. It also has database and content delivery services that can support an online shopping system. This combination can help the company handle normal traffic as well as periods with many customers.

### Possible Services

- Amazon EC2
- Elastic Load Balancing
- EC2 Auto Scaling

---

# Checkpoint 5 – Match the Cloud Services

| Service Category | AWS | Azure | GCP |
|---|---|---|---|
| Virtual Machine | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| Object Storage | Amazon S3 | Azure Blob Storage | Cloud Storage |
| Identity Management | AWS IAM | Microsoft Entra ID | Cloud IAM |
| SQL Database | Amazon RDS | Azure SQL Database | Cloud SQL |
| Kubernetes | Amazon EKS | Azure Kubernetes Service (AKS) | Google Kubernetes Engine (GKE) |

---

# Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | It has many services that can support a small project and allow it to grow later. |
| Enterprise Organization | AWS | Its large service selection can support different enterprise workloads. |
| Microsoft Environment | Azure | It is the natural choice for organizations already using Microsoft technologies. |
| AI / Machine Learning | GCP | Google Cloud has services specifically designed for AI and machine learning workloads. |
| Kubernetes Deployment | GCP | Google Kubernetes Engine provides a managed Kubernetes environment. |
| Global Web Application | AWS | AWS provides global infrastructure and services that can help applications handle changing traffic. |

---

# Checkpoint 7 – Continue Your Linux Investigation

For this checkpoint, I used a KillerCoda Linux environment and checked the system using Linux commands.

## Commands Used

### Operating System

```bash
cat /etc/os-release
```

### CPU Information

```bash
lscpu
```

### Memory

```bash
free -h
```

### Disk Space

```bash
df -h
```

## Results

**Operating System:** Ubuntu 24.04.2 LTS

**CPU:** Intel Xeon E312x (Sandy Bridge), 1 CPU, approximately 2.0 GHz

**Memory:** 1.96 GiB total RAM

**Disk Space:** 19G total disk space

## Cloud Services That Could Host This Linux Server

| Cloud Provider | Service |
|---|---|
| AWS | Amazon EC2 |
| Azure | Azure Virtual Machines |
| GCP | Compute Engine |

The Linux server could be hosted as a virtual machine on any of these services. The commands used in KillerCoda helped me understand the basic hardware and operating system information before thinking about moving the server to the cloud.

### Screenshot

The terminal screenshot is saved as:

`screenshots/killercoda-terminal.png`

---

# Checkpoint 8 – Mission Reflection

See the complete reflection in:

`reflection.md`

---

# Screenshots

The evidence for this laboratory activity is stored inside the `screenshots` folder.

The screenshots include:

- AWS homepage or console
- Azure homepage or portal
- Google Cloud homepage or console
- KillerCoda terminal output
- Final GitHub repository structure

---

# Conclusion

This activity helped me understand that AWS, Azure, and Google Cloud have similar basic cloud services but have different strengths. The best platform depends on what a company actually needs. By comparing the services and the client situations, I learned that cloud selection should be based on requirements instead of simply choosing a popular provider.
