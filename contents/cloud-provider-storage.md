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

SQL database
Database for MySQL
Database for PostgreSQL
Data warehouse
Cosmos DB
Table storage
Redis cache
Data Factory
Server Stretch database
Import/Export service

### Backup Services: 

Archive storage
Recovery backups
Site recovery

## GCP Storage Services

Google Cloud Platform offers fewer storage and database services, but they’re more unified and targeted.

See the storage features that Google offers below.

### Storage:

Cloud storage
Persistent disk
Transfer appliance
Transfer service

### Database:

Cloud SQL
Cloud Bigtable
Cloud Spanner
Cloud Datastore

### Backup Services: 

Nearline (frequently accessed data)
Coldline (infrequently accessed data)
