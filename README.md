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
