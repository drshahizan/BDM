<a href="https://github.com/drshahizan/BDM/stargazers"><img src="https://img.shields.io/github/stars/drshahizan/BDM" alt="Stars Badge"/></a>
<a href="https://github.com/drshahizan/BDM/network/members"><img src="https://img.shields.io/github/forks/drshahizan/BDM" alt="Forks Badge"/></a>
<a href="https://github.com/drshahizan/BDM/pulls"><img src="https://img.shields.io/github/issues-pr/drshahizan/BDM" alt="Pull Requests Badge"/></a>
<a href="https://github.com/drshahizan/BDM"><img src="https://img.shields.io/github/issues/drshahizan/BDM" alt="Issues Badge"/></a>
<a href="https://github.com/drshahizan/BDM/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/drshahizan/BDM?color=2b9348"></a>
![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan%2BDM&labelColor=%23d9e3f0&countColor=%23697689&style=flat)




# Cloud Services Comparison Cheatsheet ☁️

<p align="center">
<img src="/images/cloud.gif"  height="800" />
</p>

Cloud computing is the delivery of computing services over the internet, such as servers, storage, databases, networking, software, analytics, and intelligence. Cloud services allow you to access IT resources on demand, without having to invest in or maintain physical infrastructure. There are three main types of cloud services: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).

The three leading cloud providers are Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). Each of them offers a wide range of products and services to meet different needs and use cases. In this cheatsheet, we will compare some of the most common and popular cloud services from each provider, as well as their pros and cons.

## Amazon Web Services (AWS):

AWS is the oldest and largest cloud provider, with a global market share of 32%¹. It offers over 200 cloud services, covering various aspects of computing, storage, networking, databases, analytics, application development, security, and more². Some of the most popular AWS services are:

### EC2 (Elastic Compute Cloud):
Scalable virtual servers for compute capacity. You can choose from different types and sizes of instances, depending on your workload and performance requirements. You can also use features such as auto-scaling, load balancing, and spot instances to optimize your costs and availability.

### S3 (Simple Storage Service):
Object storage for a wide variety of data types, such as images, videos, documents, backups, and archives. You can store and retrieve any amount of data, anytime, from anywhere on the web. You can also use features such as versioning, encryption, lifecycle management, and replication to enhance your data security and durability.

### RDS (Relational Database Service):
Managed relational databases like MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB. You can easily set up, operate, and scale your database in the cloud, without having to worry about the underlying infrastructure. You can also use features such as multi-AZ deployment, read replicas, backup and restore, and encryption to ensure high availability and performance.

### Lambda:
Serverless computing service for running code without provisioning or managing servers. You only pay for the compute time you consume, and you can scale your code automatically based on the incoming requests. You can use Lambda to execute code in response to events, such as HTTP requests, database changes, or messages from other AWS services.

### DynamoDB:
Fully managed NoSQL database service that provides fast and consistent performance at any scale. You can store and query any amount of structured or semi-structured data, with single-digit millisecond latency. You can also use features such as global tables, streams, transactions, and encryption to support your application needs.

### Redshift:
Data warehousing for analytics and business intelligence. You can store and analyze petabytes of data using SQL and standard BI tools. You can also use features such as columnar storage, compression, parallel processing, and encryption to optimize your query performance and data security.

### ECS (Elastic Container Service):
Container orchestration using Docker containers. You can easily run, scale, and manage your containerized applications on AWS, using either the ECS API or the AWS Fargate launch type. You can also integrate ECS with other AWS services, such as ECR, EKS, ALB, CloudFormation, and CloudWatch.

**Pros of AWS:**
- Broad range of services: AWS offers the most comprehensive and diverse portfolio of cloud services, covering almost every aspect of IT and business needs. You can find a service for almost any use case, from machine learning to gaming to blockchain.
- Global infrastructure: AWS has the largest and most reliable global cloud infrastructure, with 80 availability zones across 25 geographic regions³. You can deploy your applications closer to your customers and comply with local regulations.
- Innovation and leadership: AWS is the pioneer and leader of cloud computing, with a track record of delivering innovative and cutting-edge solutions. AWS is constantly adding new features and services, and lowering its prices, to stay ahead of the competition.

**Cons of AWS:**
- Complex pricing model: AWS has a complex and dynamic pricing model, with different rates and discounts for different services, regions, and usage patterns. You may find it hard to predict and control your cloud costs, especially if you use multiple services or scale your applications frequently.
- Steep learning curve: AWS has a steep learning curve, with a lot of technical details and jargon to master. You may need to invest a lot of time and resources to learn how to use AWS effectively and efficiently, and to keep up with the latest updates and best practices.

## Microsoft Azure:

Azure is the second-largest cloud provider, with a global market share of 20%¹. It offers over 200 cloud services, covering various aspects of computing, storage, networking, databases, analytics, application development, security, and more. Some of the most popular Azure services are:

### Azure Virtual Machines:
Scalable computing for Windows and Linux. You can choose from different types and sizes of virtual machines, depending on your workload and performance requirements. You can also use features such as availability sets, scale sets, and reserved instances to optimize your costs and availability.

### Azure Blob Storage:
Object storage for unstructured data, such as images, videos, documents, backups, and archives. You can store and access any amount of data, anytime, from anywhere on the web. You can also use features such as tiering, encryption, lifecycle management, and replication to enhance your data security and durability.

### Azure SQL Database:
Fully managed relational database service that is compatible with SQL Server. You can easily set up, operate, and scale your database in the cloud, without having to worry about the underlying infrastructure. You can also use features such as elastic pools, geo-replication, backup and restore, and encryption to ensure high availability and performance.

### Azure Functions:
Event-driven serverless compute. You only pay for the compute time you consume, and you can scale your code automatically based on the incoming requests. You can use Azure Functions to execute code in response to events, such as HTTP requests, database changes, or messages from other Azure services.

### Cosmos DB:
Globally distributed, multi-model database service that provides fast and consistent performance at any scale. You can store and query any amount of structured, semi-structured, or unstructured data, using various APIs, such as SQL, MongoDB, Cassandra, Gremlin, or Table. You can also use features such as global distribution, automatic indexing, transactions, and encryption to support your application needs.

### Azure Kubernetes Service (AKS):
Managed Kubernetes container orchestration. You can easily run, scale, and manage your containerized applications on Azure, using the Kubernetes API. You can also integrate AKS with other Azure services, such as ACR, ACI, Azure Monitor, and Azure DevOps.

**Pros of Azure:**
- Seamless integration for Windows environments: Azure offers seamless integration for Windows environments, such as Windows Server, SQL Server, Active Directory, .NET, and Visual Studio. You can easily migrate your existing Windows applications and data to Azure, and leverage the familiar tools and frameworks.
- Robust hybrid cloud options: Azure offers robust hybrid cloud options, such as Azure Stack, Azure Arc, and Azure Hybrid Benefit. You can extend Azure to your on-premises or edge environments, and use the same services, tools, and processes across your hybrid cloud.

**Cons of Azure:**
- Learning curve for beginners: Azure has a learning curve for beginners, especially if you are not familiar with Microsoft technologies. You may need to spend some time and effort to learn how to use Azure effectively and efficiently, and to keep up with the latest updates and best practices.
- Reliability and performance issues: Azure has faced some reliability and performance issues in the past, such as outages, latency, and downtime. You may need to carefully plan and test your disaster recovery and backup strategies, and monitor your application performance and availability.

## Google Cloud Platform (GCP):

GCP is the third-largest cloud provider, with a global market share of 9%¹. It offers over 100 cloud services, covering various aspects of computing, storage, networking, databases, analytics, application development, security, and more. Some of the most popular GCP services are:

### Compute Engine:
Virtual machines on Google's infrastructure. You can choose from different types and sizes of instances, depending on your workload and performance requirements. You can also use features such as preemptible instances, custom machine types, and sustained use discounts to optimize your costs and availability.

### Cloud Storage:
Object storage for different data types, such as images, videos, documents, backups, and archives. You can store and access any amount of data, anytime, from anywhere on the web. You can also use features such as lifecycle management, encryption, and versioning to enhance your data security and durability.

### BigQuery:
Serverless, highly scalable enterprise data warehouse. You can store and analyze petabytes of data using SQL and standard BI tools. You can also use features such as partitioning, clustering, encryption, and streaming to optimize your query performance and data security.

### Cloud Pub/Sub:
Scalable real-time messaging. You can publish and subscribe to messages from any application, on any platform, and in any location. You can also use features such as ordering, filtering, and encryption to ensure reliable and secure communication.

### Cloud AI Platform:
AI and machine learning services. You can build, deploy, and manage your AI and ML models using various tools and frameworks, such

## Contribution 🛠️
Please create an [Issue](https://github.com/drshahizan/BDM/issues) for any improvements, suggestions or errors in the content.

You can also contact me using [Linkedin](https://www.linkedin.com/in/drshahizan/) for any other queries or feedback.

[![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fdrshahizan&labelColor=%23697689&countColor=%23555555&style=plastic)](https://visitorbadge.io/status?path=https%3A%2F%2Fgithub.com%2Fdrshahizan)
![](https://hit.yhype.me/github/profile?user_id=81284918)

