# cloud-tool-comparision
> A curated list of modern Cloud Provider Tools, projects and services.


Cloud tools are software applications that help users interact with cloud computing services. They can be used to manage cloud resources, deploy applications, and analyze data. There are a wide variety of cloud tools available, each with its own strengths and weaknesses.

## NoSql DB: 

A cloud NoSQL database is a database that is hosted in the cloud and that uses a non-relational data model. NoSQL databases are designed to store and manage large amounts of unstructured data, and they are often used for applications that require high scalability and performance.

Criteria | AWS DynamoDB	|Azure Cosmos DB |Google Cloud Firestore
----|----|----|----|
Data Model|	Key-value, Document|	Document, Key-value|	Document
Scalability|	Highly scalable|	Global scalability|	Horizontally scalable
Performance|	High performance|	Low latency|	Low latency
Pricing|	Pay-per-usage|	Pay-per-usage|	Pay-per-usage|
Availability|	Highly available|	Global distribution|	Highly available
Reliability|	Built-in redundancy|	SLA-backed reliability|	High reliability
Security|	Encryption at rest|	Encryption at rest|	Encryption at rest
Integrations|	AWS services|	Azure services|	Google Cloud services
Query Language|	AWS SDKs, Query API|	SQL, Gremlin, MongoDB|	Client libraries
Consistency|	Eventually consistent|	Strong or eventual|	Strong or eventual
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support|	AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	<a href="https://docs.aws.amazon.com/dynamodb/index.html">AWS Dynamodb</a>|	<a href="https://learn.microsoft.com/en-us/azure/cosmos-db/">Azure Cosmos-DB</a>|	<a href="https://cloud.google.com/datastore">Google Cloud Datastore</a>
Limitations|	Item size limit, Index|	Throughput limits|	Transaction limits

## Relational Database:

A cloud relational database is a database that is hosted in the cloud and that uses a relational data model. Relational databases are designed to store and manage structured data, and they are often used for applications that require high performance and scalability.

Criteria|	AWS RDS|	Azure SQL Database|	Google Cloud SQL
----|----|----|----|
Database Engine|	MySQL, PostgreSQL, Oracle, SQL Server|	SQL Server, MySQL, PostgreSQL, MariaDB|	MySQL, PostgreSQL
Scalability|	Vertical and horizontal scaling|	Vertical and horizontal scaling|	Vertical and horizontal scaling
Performance|	High performance|	High performance|	High performance
Pricing|	Pay-per-usage|	Pay-per-usage|	Pay-per-usage
Availability|	Highly available|	Highly available|	Highly available
Reliability|	Automated backups, fault-tolerant infrastructure|	Automated backups, fault tolerance|	Automated backups, failover replicas
Security|	Encryption at rest and in transit|	Encryption at rest and in transit|	Encryption at rest and in transit
Integrations|	AWS services|	Azure services|	Google Cloud services
Query Language|	SQL|	SQL|	SQL
Replication|	Multi-AZ replication|	Geo-replication|	Regional replication
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support|	AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	<A href="https://docs.aws.amazon.com/rds/index.html">AWS RDS</a>|	<A href="https://learn.microsoft.com/en-us/azure/azure-sql/?view=azuresql">Azure SQL</a>|	<a href="https://cloud.google.com/sql/docs">Google Cloud SQL</a>
Limitations|	Instance size limits, storage limits|	Instance size limits, performance tiers|	Instance size limits, storage limits

## Cache:

Cloud caching is a technique that stores frequently accessed data in the cloud, so that it can be retrieved more quickly than if it were stored on a local server. This can improve the performance of applications that rely on this data, such as web applications, mobile applications, and databases.

Criteria|	AWS ElastiCache|	Azure Cache for Redis|	Google Cloud Memorystore
----|----|----|----|
Cache Engine|	Redis, Memcached|	Redis|	Redis
Scalability|	Vertical and horizontal scaling|	Vertical and horizontal scaling|	Vertical and horizontal scaling
Performance|	Low-latency access|	Low-latency access|	Low-latency access
Pricing|	Pay-per-usage|	Pay-per-usage|	Pay-per-usage
Availability|	Highly available|	Highly available|	Highly available
Reliability|	Automated backups, fault tolerance|	Automated backups, fault tolerance|	Automated backups, fault tolerance
Security|	Encryption at rest and in transit|	Encryption at rest and in transit|	Encryption at rest and in transit
Integrations|	AWS services|	Azure services|	Google Cloud services
Data Persistence|	Redis persistent storage|	Redis persistent storage|	Redis persistent storage
Data Replication|	Multi-AZ replication|	Geo-replication|	Regional replication
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support|	AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	<a href="https://docs.aws.amazon.com/elasticache/index.html">AWS ElastiCache</a>|	<A href="https://learn.microsoft.com/en-us/azure/azure-cache-for-redis/">Azure Cache for Redis</a>|	<a href="https://cloud.google.com/memorystore/docs/redis">Google Cloud Memorystore</a>
Limitations|	Cache size limits, instance types|	Cache size limits, instance types|	Cache size limits, instance types

some examples of how cloud caching can be used:

- Caching static content: Cloud caching can be used to cache static content, such as images, CSS files, and JavaScript files. This can improve the performance of web applications by reducing the amount of time it takes to load these files.
- Caching dynamic content: Cloud caching can also be used to cache dynamic content, such as the results of database queries. This can improve the performance of applications that rely on this data, such as e-commerce applications and social media applications.
- Caching API responses: Cloud caching can also be used to cache API responses. This can improve the performance of applications that make frequent calls to APIs, such as mobile applications and IoT applications.

## Virtual Machines


A virtual machine (VM) in the cloud is a software program that creates a virtual computer within a physical computer. This allows you to run multiple operating systems and applications on the same physical hardware, without having to worry about compatibility issues.

There are many benefits to using virtual machines in the cloud, including:

Flexibility: You can easily create and destroy VMs as needed, without having to worry about hardware provisioning or maintenance.
Cost savings: You only pay for the resources that you use, so you can save money on hardware and software costs.
Scalability: You can easily scale up or down your VM resources as needed, to meet the demands of your workload.
Security: VMs are isolated from each other, which helps to improve security.

Criteria|	AWS EC2|	Azure Virtual Machines|	Google Compute Engine
----|----|----|----|
Instance Types|	Wide variety of options|	Diverse range of sizes|	Various machine types
Scalability|	Vertical and horizontal scaling|	Vertical and horizontal scaling|	Vertical and horizontal scaling
Performance|	High performance|	High performance|	High performance
Pricing|	Pay-per-usage|	Pay-per-usage|	Pay-per-usage
Availability|	Highly available|	Highly available|	Highly available
Reliability|	SLA-backed reliability|	SLA-backed reliability|	SLA-backed reliability
Security|	Encryption at rest and in transit|	Encryption at rest and in transit|	Encryption at rest and in transit
Integrations|	AWS services|	Azure services|	Google Cloud services
Operating Systems|	Wide range of options|	Windows, Linux|	Wide range of options
Networking|	VPC, Load Balancers|	Virtual Network, Load Balancer|	Virtual Private Cloud, Load Balancing
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support| AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	<a href="https://docs.aws.amazon.com/ec2/index.html">AWS EC2</a>|	<A href="https://learn.microsoft.com/en-us/azure/virtual-machines/">Azure Virtual Machines</a>|	<a href="https://cloud.google.com/compute/docs">Google Compute Engine</a>
Limitations|	Instance size limits|	Instance size limits|	Instance size limits

## Block Storage

Block storage is a type of cloud storage that stores data in blocks. Each block is a fixed-size unit of data, and blocks are typically 512 bytes to 1 megabyte in size. Block storage is designed for applications that require high performance and low latency, such as databases, virtual machines, and high-performance computing applications.

Criteria|	AWS EBS|	Azure Disk Storage|	Google Persistent Disk
----|----|----|----|
Storage Types|	SSD, HDD|	SSD, Standard|	SSD, Standard
Scalability|	Vertical scaling|	Vertical scaling|	Vertical scaling
Performance|	High performance|	High performance|	High performance
Pricing|	Pay-as-you-go|	Pay-as-you-go|	Pay-as-you-go
Availability|	Highly available|	Highly available|	Highly available
Snapshot|	Point-in-time backups|	Snapshot capabilities|	Snapshot capabilities
Encryption|	Encryption at rest|	Encryption at rest|	Encryption at rest
Replication|	EBS Multi-Attach|	Zone-redundant storage|	Regional Replication
Integration|	AWS services|	Azure services|	Google Cloud services
Volume Types|	General Purpose, Provisioned IOPS, Cold HDD, Throughput Optimized HDD|	Premium SSD, Standard SSD, Standard HDD	|SSD, Balanced, HDD
Snapshots|	EBS Snapshots|	Azure Snapshots|	GCP Snapshots
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support|	AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	AWS Documentation|	Azure Documentation|	Google Cloud Docs
Limitations|	Volume size limits, IOPS limits|	Disk size limits, IOPS limits|	Disk size limits, IOPS limits

## File System

A cloud file system is a hierarchical storage system in the cloud that provides shared access to file data. Users can create, delete, modify, read, and write files, as well as organize them logically in directory trees for intuitive access.

Criteria|	AWS EFS|	Azure Files|	Google Cloud Filestore
----|----|----|----|
Storage Type|	Network File System|	Network File Share|	Network File System
Scalability|	Automatic scaling|	Automatic scaling|	Automatic scaling
Performance|	Low-latency access|	Low-latency access|	Low-latency access
Pricing|	Pay-as-you-go|	Pay-as-you-go|	Pay-as-you-go
Availability|	Highly available|	Highly available|	Highly available
Data Redundancy|	Multi-AZ replication|	Zone-redundant storage|	Regional Replication
Encryption|	Encryption at rest|	Encryption at rest|	Encryption at rest
Protocol Support|	NFSv4.1|	SMB 3.0|	NFSv3
Integrations|	AWS services|	Azure services|	Google Cloud services
Data Transfer|	Data transfer within the same region is free|	Data transfer within the same region is free|	Data transfer within the same region is free
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support|	AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	AWS Documentation|	Azure Documentation|	Google Cloud Docs
Limitations|	File system size limits, performance scaling|	File size limits, performance scaling|	File size limits, performance scaling

## Serverless Computing

Serverless computing is a cloud computing execution model in which the cloud provider allocates machine resources on demand, taking care of the servers on behalf of their customers. "Serverless" is a misnomer in the sense that servers are still used by cloud service providers to execute code for developers. However, developers of serverless applications are not concerned with capacity planning, configuration, management, maintenance, fault tolerance, or scaling of containers, VMs, or physical servers.

In serverless computing, developers write code that is triggered by events, such as HTTP requests, database changes, or file uploads. The cloud provider then executes the code in response to the event, without the developer having to worry about provisioning or managing servers.

Criteria|	AWS Lambda|	Azure Functions|	Google Cloud Functions
----|----|----|----|
Compute Engine|	Event-driven Functions|	Event-driven Functions	|Event-driven Functions
Scalability|	Auto-scaling|	Auto-scaling|	Auto-scaling
Pricing|	Pay-per-invocation|	Pay-per-invocation|	Pay-per-invocation
Trigger Options|	Numerous event sources|	Numerous event sources|	Numerous event sources
Language Support|	Multiple languages|	Multiple languages|	Node.js, Python, Go, etc.
Integration|	AWS services integration|	Azure services integration|	Google Cloud services integration
Cold Start Time|	Varies based on runtime|	Varies based on runtime|	Varies based on runtime
Monitoring|	CloudWatch|	Azure Monitor|	Stackdriver Monitoring
Support|	AWS Support plans|	Azure Support plans|	Google Cloud Support
Documentation|	<a href="https://aws.amazon.com/lambda/?did=ft_card&trk=ft_card">AWS Serverless Computing</a>|	<a href="https://azure.microsoft.com/en-us/products/functions/?ef_id=_k_Cj0KCQjw7uSkBhDGARIsAMCZNJu_kqopA8z2JufjUIZkWsOyNhLHmemWkamy_GxZoM77xskNIvw4ivMaAs4SEALw_wcB_k_&OCID=AIDcmm5edswduu_SEM__k_Cj0KCQjw7uSkBhDGARIsAMCZNJu_kqopA8z2JufjUIZkWsOyNhLHmemWkamy_GxZoM77xskNIvw4ivMaAs4SEALw_wcB_k_&gad=1&gclid=Cj0KCQjw7uSkBhDGARIsAMCZNJu_kqopA8z2JufjUIZkWsOyNhLHmemWkamy_GxZoM77xskNIvw4ivMaAs4SEALw_wcB">Azure Functions</a>|	<a href="https://cloud.google.com/serverless">Google Serverless Computing</a>
Limitations|	Execution time limits, size restrictions|	Execution time limits, concurrency limits|	Execution time limits, memory limits

## Disclaimer
Please note that the information provided is a general overview and may not capture every detail or feature of each cloud. It's important to refer to the official documentation and websites of each cloud provider for the most up-to-date and comprehensive information regarding their Security offerings.
