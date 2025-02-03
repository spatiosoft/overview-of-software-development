---
title: Cloud Computing
weight: 17
---

Cloud computing allows deploying, managing,
and scaling applications without the need to manage the underlying infrastructure. 
It is a model for enabling on-demand network access to a shared pool of configurable computing resources
(e.g., networks, servers, storage, applications, and services).
These resources can be rapidly provisioned and released.

Instead of managing physical servers in your own datacenters, you can rent the resources you need from a cloud provider.

The major cloud providers are:
- [Amazon Web Services (AWS)](https://aws.amazon.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [Google Cloud Platform (GCP)](https://cloud.google.com)
- [IBM Cloud](https://www.ibm.com/cloud)
- [Oracle Cloud](https://www.oracle.com/cloud)
- [Alibaba Cloud](https://www.alibabacloud.com)
- [Digital Ocean](https://www.digitalocean.com)

> [Overview of the trends in cloud computing](https://spatiosoft.com/blog/overview-of-cloud-computing/)

## Main components

The major cloud providers offer a wide range of services for very specific needs.
However, there are some common components that you will find in all cloud providers.

### Container

A container packages the code and its dependencies together.
It allows executing the code in a consistent environment, regardless of the underlying infrastructure.

### Network

The network is the backbone of cloud computing. 
It allows connecting the different components of the cloud infrastructure.

With a load balancer, you can distribute the incoming traffic across multiple servers.

### Storage

Storage offers spaces to store data. 
Usually, you can store as many data as you want as the system will scale automatically.

The storage is accessible from anywhere in the world and from all your components and microservices.
This allows sharing data between different components.

### Database

In the realm of cloud computing, database services offer a means to store, manage, and retrieve structured data. These services can be broadly classified into two categories: SQL (relational databases) and NoSQL (non-relational databases). SQL databases are ideal for applications that require complex queries and transactions, while NoSQL databases are better suited for applications that need to handle large volumes of unstructured data. Cloud database services offer scalability, high availability, and flexibility, thereby reducing the need for businesses to maintain their own physical databases.

### Access Management

Access management in cloud computing involves controlling who can access cloud resources and what actions they can perform. This is typically achieved through Identity and Access Management (IAM) systems, which authenticate and authorize individuals to access certain resources. IAM systems can manage roles, handle user identities, and enforce policies, ensuring that only authorized users can access sensitive data and applications.

### Monitoring

Monitoring in cloud computing is crucial for maintaining the health, performance, and availability of cloud services and applications. It involves collecting and analyzing metrics related to network traffic, resource usage, application performance, and security events. Monitoring tools can provide real-time alerts and dashboards, helping businesses identify and resolve issues before they affect users.

### Logging

Logging is the process of recording events that occur within a system. In cloud computing, logs can provide valuable information about user activities, system actions, and security incidents. They can be used for troubleshooting, auditing, and detecting anomalies. Cloud providers often offer logging services that can collect, analyze, and store logs from various sources.

### Security

Security in cloud computing involves protecting cloud-based data, applications, and infrastructures from threats. This can include measures such as encryption, firewalls, intrusion detection systems, and vulnerability scanning. Cloud providers also offer services for identity management, access control, and threat intelligence. Despite the shared security responsibility model in cloud computing, businesses must still take steps to protect their own data and applications.

### Zones and Regions

In cloud computing, a region is a specific geographical area where a cloud provider's data centers are located. Each region is divided into multiple isolated locations known as zones. Zones can help reduce the risk of data loss and downtime by distributing resources across multiple locations. When designing a cloud architecture, businesses should consider factors such as latency, cost, and regulatory requirements when choosing regions and zones.

## Infrastructure as Code

Infrastructure as Code (IaC) is a method of managing and provisioning computing infrastructure through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools. This allows developers to automate the process of setting up and managing cloud resources, making it easier to scale and replicate infrastructures. IaC can improve efficiency, reduce errors, and ensure consistency across different environments.
