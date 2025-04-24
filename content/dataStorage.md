## Compiling code with no installation. 

Several cloud providers will manage the runtime for your, you only need to upload your code. This is either an entire website or just a function.  



| Cloud Provider| US Cloud ACT  | EU GDPR | Out of the box backup | Price in Euro | OpenSource | CO2 | Documentation | supported frameworks | 
| ------------- | ------------- |------------- |------------- |------------- |------------- |------------- |------------- |------------- |
| Microsoft Azure | Yes         | ~       | partly         | 3-70   | No | ? | https://learn.microsoft.com/en-us/azure/azure-functions

https://learn.microsoft.com/en-us/azure/app-service/ | .NET, Java, Nodes.js ,Python, PowerShell, TypeScript, PHP| 
|AWS|   | Yes | ~   | ?   | 3-40 | No | ? | https://docs.aws.amazon.com/lambda/
https://aws.amazon.com/lightsail/| .NET, Java, Nodes.js ,Python, PowerShell, TypeScript, Go, Rust, Ruby|


sddsfsdfsdfsd

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |


Cloudways	


# Cloud Hosting of Data: Finding the Right Fit

Choosing how to host your data in the cloud is a foundational decision — it affects everything from performance and scalability to how easily your team can access and analyze that data.

Just like with code, cloud data hosting typically falls into three broad categories:

1. **Virtual Machine (VM) Storage**
2. **Databases**
3. **Cloud Tables**

Each serves a different purpose and fits different kinds of data and workloads. Here's how they compare:

---

## 1. Virtual Machine (VM) Storage

This is the most raw and flexible way to host data in the cloud. You spin up a virtual machine and manage your own file system, storage volumes, or even a self-hosted database.

**Pros**:
- Full control over storage architecture and format
- Ideal for custom formats, legacy systems, or low-level tools
- Can be combined with any software or access method

**Cons**:
- Manual backups and scaling
- No built-in indexing, querying, or transactional guarantees
- Higher maintenance and risk of misconfiguration

**Best For**:
Custom software, legacy migration, experimental systems, or when you need full ownership over the stack.

---

## 2. Databases

Databases are the workhorse of modern cloud data hosting. They provide structured storage, querying, indexing, and transactional support out of the box. Options range from SQL (e.g., PostgreSQL, MySQL) to NoSQL (e.g., CosmosDB, MongoDB).

**Pros**:
- Rich querying and indexing capabilities
- Built-in scaling, backup, and security features
- Suitable for applications, reporting, and analytics

**Cons**:
- More complex schema design and planning required
- Costs can rise with high storage or compute usage
- May involve some vendor-specific features

**Best For**:
Business applications, dashboards, APIs, and systems that rely on relationships between data or structured queries.

---

## 3. Cloud Tables

Cloud tables are massively scalable, schema-flexible, and often serve as lightweight storage for key-value or event-style data. They're not full databases — think of them as the cloud-native cousin of spreadsheets or CSVs.

**Examples**: Azure Table Storage, Amazon DynamoDB, Google Bigtable

**Pros**:
- Low-cost and scalable
- Simple to access, especially for logs or streaming events
- Good fit for high-throughput, non-relational data

**Cons**:
- Limited querying (no joins, often no sorting or filtering)
- Optimized for access patterns, not flexibility
- Not ideal for relational data or ad-hoc querying

**Best For**:
Sensor data, logs, event streams, metadata, or storing fast-changing user states.

---

## Choosing the Right Model

- If you need full control and flexibility (or you're porting over legacy systems), **VM storage** is your best bet.
- For structured, transactional, or relational workloads, a **cloud database** is the most reliable and powerful option.
- For fast, scalable, and cheap data access — especially with simple structures — **cloud tables** shine.

The right choice depends on how your data is used, how often it changes, and how much structure (or lack of it) it has.

[![Edit on GitHub](https://img.shields.io/badge/Edit_on_GitHub-blue?logo=github)](https://github.com/mikekrom1/nomadsky/edit/main/content/dataStorage.md)

