# Cloud Provider Storage

One of the greatest advantages of cloud computing is the expansive storage capabilities.

## AWS Storage Services

AWS takes the prize for range of storage options. The one the best AWS offering is [`Storage Gateway`](https://aws.amazon.com/storagegateway/?nc1=h_ls), that offers a hybrid platform. It offers a secondary archive storage option together with [`Glacier`](https://aws.amazon.com/glacier/?nc1=h_ls), a AWS backup service were designed 99.999999999% of durability.

You can use simple object storage with [Simple Storage Service (S3)](https://aws.amazon.com/s3/?nc1=h_ls) or block storage for large containers with the [Elastic Block Store (EBS)](https://aws.amazon.com/ebs/?nc1=h_ls). The [Elastic File System (Amazon EFS)](https://aws.amazon.com/efs/?nc1=h_ls) expands the capability of creating file which is ideal for large company that generate a petabyte of data.

Amazon Web Services also provides a number of [SQL-supported databases](https://aws.amazon.com/rds/?nc1=h_ls), an [ElastiCache](https://aws.amazon.com/elasticache/?nc1=h_ls) offers a memory database, and a [database migration service](https://aws.amazon.com/dms/?nc1=h_ls). 

Following is features of storage/backup that AWS offers:

### Storage:

- [Simple Storage Service (S3)](https://aws.amazon.com/s3/?nc1=h_ls): a simple object storage.
- [Elastic Block Storage (EBS)](https://aws.amazon.com/ebs/?nc1=h_ls): high performance block storage service designed for use with Amazon Elastic Compute Cloud (EC2).
- [Elastic File System (EFS)](https://aws.amazon.com/efs/?nc1=h_ls): a simple, scalable, fully managed elastic NFS file system for use with AWS Cloud services and on-premises resources.
- [Storage Gateway](https://aws.amazon.com/storagegateway/?nc1=h_ls): provides seamlessly connect on-premises applications to cloud storage, caching data locally for low-latency access
- [Snowball](https://aws.amazon.com/snowball/?nc1=h_ls): a petabyte-scale data transport solution that uses devices designed to be secure to transfer large amounts of data into and out of the AWS Cloud.
- [Snowball Edge](https://aws.amazon.com/snowball-edge/?nc1=h_ls): a data migration and edge computing device. Snowball Edge supports specific Amazon EC2 instance types as well as AWS Lambda functions.
- [Snowmobile](https://aws.amazon.com/snowmobile/?nc1=h_ls): an Exabyte-scale data transfer service used to move extremely large amounts of data to AWS.

### Database:

- [Aurora](https://aws.amazon.com/rds/aurora/?nc1=h_ls): MySQL and PostgreSQL-co.mpatible relational database built for the cloud
- [Relational Database Service (RDS)](https://aws.amazon.com/rds/?nc1=h_ls): available on several database instance types - optimized for memory, performance or I/O - and provides you with six familiar database engines to choose from, including *Amazon Aurora*, *PostgreSQL*, *MySQL*, *MariaDB*, *Oracle Database*, and *SQL Server*.
- [DynamoDB](https://aws.amazon.com/dynamodb/?nc1=h_ls): a key-value and document database that delivers single-digit millisecond performance at any scale.
- [ElastiCache](https://aws.amazon.com/elasticache/?nc1=h_ls): offers fully managed Redis and Memcached.
- [Redshift](https://aws.amazon.com/redshift/?nc1=h_ls): offers a cloud data warehouse.
- [Neptune](https://aws.amazon.com/neptune/?nc1=h_ls): fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets.
- [Database migration service (DMS)](https://aws.amazon.com/dms/?nc1=h_ls): supports homogeneous migrations such as Oracle to Oracle, as well as heterogeneous migrations between different database platforms, such as Oracle or Microsoft SQL Server to Amazon Aurora.

### Backup Services: 

- [Amazon S3 Glacier and S3 Glacier Deep Archive](https://aws.amazon.com/glacier/?nc1=h_ls): Cloud storage classes for data archiving and long-term backup. They are designed to deliver 99.999999999% durability, and provide comprehensive security and compliance capabilities that can help meet even the most stringent regulatory requirements.

## Azure Storage Services

Only Azure that has a backup and recovery system, which is in addition to their archive and standard system backups.

What follows is Azure’s available storage/backup solutions:

### Storage:

- [Blob Storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction): Object storage solution for the cloud. It is optimized for storing massive of unstructured data, such as text or binary data.
- [Queue Storage](https://docs.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction): To store and retrieve messages, the Queue messages can be up to 64 KB in size and can contain millions of messages queue.
- [File Storage](https://docs.microsoft.com/en-us/azure/storage/files/storage-files-introduction): Enables you to set up highly available network file shares that can be accessed by using standard Server Message Block (SMB) protocol.
- [Disk Storage](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/managed-disks-overview): is a Virtual Hard Disk (VHD), it like a physical disk in on premises server but, virtualized.
- [Data Lake Storage](https://docs.microsoft.com/id-id/azure/storage/blobs/data-lake-storage-introduction): Set of capabilities dedicated to big data analytics, built on Azure Blob storage

Here is for futher details about the [azure storage services](https://docs.microsoft.com/en-us/azure/storage/common/storage-introduction).

### Database:

- [SQL database](https://docs.microsoft.com/id-id/azure/sql-database/): Managed instance Microsoft SQL Server Database Engine in the cloud. The deployment models are a single database is the best choice for new modern cloud applications, elastic pools are the best place to host a large fleet of databases, and a managed instance provides high compatibility with SQL Server and enables easy migration to the cloud.
- [Database for MySQL](https://docs.microsoft.com/en-us/azure/mysql/): A fully managed relational database based on service powered by the MySQL community edition.
- [Database for PostgreSQL](https://docs.microsoft.com/en-us/azure/postgresql/): A fully managed relational database based on the open-source Postgres database engine.
- [Data warehouse](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-overview-what-is): A cloud-based Enterprise Data Warehouse (EDW) that uses Massively Parallel Processing (MPP) to quickly run complex queries accross petabytes of data.
- [Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/introduction): A globally distributed multi-model database service. You can elastically scale throughput and storage, and take advantage of fast, single-digit-millisecond data access using your favorite API including SQL, MongoDB, Cassandra, Tables, Gremlin, Sparks, etcd and more APIs.
- [Table storage](https://docs.microsoft.com/en-us/azure/cosmos-db/table-storage-overview): A service that stores structured NoSQL data in the cloud, providing a key/attribute store with a schemaless design.
- [Redis cache](https://docs.microsoft.com/en-us/azure/azure-cache-for-redis/cache-overview): A fully managed in-memory data structure store, a distributed non-relational database, and a message broker based on an in-memory data structure store, a distributed non-relational database, and a message broker based on the popular software [Redis](https://redis.io/).
- [Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/introduction): A managed cloud service that's built for these complex hybrid extract-transform-load (ETL), extract-load-transform (ELT), and data integration projects.
- [Server Stretch database](https://docs.microsoft.com/en-us/azure/sql-server-stretch-database/): Stretch Database migrates your cold data transparently and securely to the Microsoft Azure cloud.
- [Import/Export service](https://docs.microsoft.com/en-us/azure/storage/common/storage-import-export-service): Securely import large amounts of data to Azure Blob storage and Azure Files by shipping disk drives to an Azure datacenter. This service can also be used to transfer data (export) from Azure Blob storage to disk drives and ship to your on-premises sites. 

### Backup Services: 

- [Archive storage](https://docs.microsoft.com/id-id/azure/storage/blobs/storage-blob-storage-tiers): Optimized for storing data that is rarely accessed and stored for at least 180 days with flexible latency requirements (on the order of hours).
- [Azure Backup](https://docs.microsoft.com/en-us/azure/backup/backup-overview): A service backs up data from on-premises machines and Azure VMs to Azure cloud.
- [Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview): Replicates workloads running on physical and virtual machines (VMs) from a primary site to a secondary location. When an outage occurs at your primary site, you fail over to secondary location, and access apps from there. After the primary location is running again, you can fail back to it.

## GCP Storage Services

Google Cloud Platform offers fewer storage and database services, but they’re more unified and targeted.

See the storage features that Google offers below.

### Storage:

- [Cloud Storage](https://cloud.google.com/storage/): Storage solutions for any workload from High-performance object storage to Backup and archival storage.
- [Persistent Disk](https://cloud.google.com/persistent-disk/): A high-performance block storage for VM and container instances.
- [Cloud Storage for Firebase](https://firebase.google.com/docs): The Firebase SDKs for Cloud Storage add Google security to file uploads and downloads for your Firebase apps.
- [Data transfer services](https://cloud.google.com/products/data-transfer/): Transfer hundreds of terabytes of data to GCP.
- [Drive Enterprise](https://cloud.google.com/drive-enterprise/): Collaboration tools like Docs, Sheets, and Slides — all on a secure, cloud-based platform that makes it easy for users to share, store, and access files.

### Database:

- [Cloud Spanner](https://cloud.google.com/spanner/): The best of cloud specifically to combine the benefits of relational database structure with non-relational horizontal scale.
- [Cloud SQL](https://cloud.google.com/sql/): A fully managed database service that makes it easy to set up, maintain, manage, and administer your relational PostgreSQL, MySQL, and SQL Server (alpha preview) databases in the cloud.
- [Cloud Bigtable](https://cloud.google.com/bigtable/): A petabyte-scale, fully managed NoSQL database service for large analytical and operational workloads.
- [Cloud Firestore](https://cloud.google.com/firestore/): A fast, fully managed, serverless, cloud-native NoSQL document database that simplifies storing, syncing, and querying data for your mobile, web, and IoT apps at global scale.
- [Cloud Memorystore](https://cloud.google.com/memorystore/): A fully-managed in-memory data store service for Redis.
- [Firebase Realtime Database](https://firebase.google.com/products/realtime-database/): A cloud-hosted NoSQL database that lets you store and sync data between your users in realtime.

### Backup Services: 

- [Nearline (frequently accessed data)](https://cloud.google.com/storage/docs/storage-classes#nearline): A low-cost, highly durable storage service for storing infrequently accessed data.
- [Coldline (infrequently accessed data)](https://cloud.google.com/storage/docs/storage-classes#coldline): A very-low-cost, highly durable storage service for data archiving, online backup, and disaster recovery.
