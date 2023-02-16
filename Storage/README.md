# No SQL

Big Table / Datastore (docs) / Firestore (docs)

# SQL

SQL / Spanner

Cloud SQL instances are fully managed, relational MySQL, PostgreSQL, and SQL Server databases. Google handles replication, patch management, and database management to ensure availability and performance.  

Ref to: Database Migration API (Google Database Migration Service is a fully managed service for migrating databases to Google Cloud Platform. Database Migration Service allows you to migrate your databases to Google Cloud managed databases with minimal downtime, freeing you from operational considerations such as resource management and performance optimization.)  


REF: https://cloud.google.com/database-migration?_ga=2.178139941.-10387226.1676586037


Supported source databases for PostgreSQL include:

RDS 9.6.10+, 10.5+, 11.1+, 12, 13, 14
Self-managed (on prem, on any cloud VM) 9.4, 9.5, 9.6, 10, 11, 12, 13, 14
Aurora 10.11+, 11.6+, 12.4+, 13.3
Cloud SQL 9.6, 10, 11, 12, 13, 14

It is also highly recommended that you connect to the source using SSL/TLS, so that the data you send to and receive from the source is secure.  

# File System

Filestore 

Used to share files between VM instances

Storage

Can be used to save images, ...

# Object System