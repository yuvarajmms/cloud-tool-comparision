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
Documentation|	AWS Documentation|	Azure Documentation|	Google Cloud Docs
Limitations|	Instance size limits, storage limits|	Instance size limits, performance tiers|	Instance size limits, storage limits
