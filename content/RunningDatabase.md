# Hosting Options for databases like PostgreSQL, MySQL, SQLite, MSSQL, MongoDB, Redis, MariaDB

This page provides a clear overview of where and how you can host your database. From fully managed stacks to containers and virtual machines, we list the most common providers and hosting types. 
So you can choose the setup that best fit your needs for control, scalability, and ease of management.

## Fully managed database, Click and go


| Cloud Provider     | Headquarter   | Supported Databases                                 | Price in Euro (approx.) | OpenSource | CO₂ Emission     | Documentation |
|--------------------|---------------|-----------------------------------------------------|-------------------------|------------|------------------|---------------|
| AWS         | USA           | PostgreSQL, MySQL, MariaDB, Oracle, SQL Server      | From ~€15/month         |  No      | ? | [AWS RDS Docs](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html) |
| Azure       | USA           | SQL Server, PostgreSQL, MySQL                       | From ~€20/month         |  No      | ? | [Azure SQL Docs](https://learn.microsoft.com/en-us/azure/azure-sql/) |
| Google Cloud  | USA         | PostgreSQL, MySQL, SQL Server                       | From ~€20/month         |  No      | ? | [Cloud SQL Docs](https://cloud.google.com/sql/docs) |
| MongoDB Atlas  | USA           | MongoDB                                             | From ~€9/month       |  Yes   | ? | [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) |
| Scaleway       | France        | PostgreSQL, MySQL                                   | From ~€5/month       |  Yes     | ? | [Scaleway Docs](https://www.scaleway.com/en/docs/) |
| OVHcloud       | France        | PostgreSQL, MySQL, MongoDB                          | From ~€3/month        |  Yes     | ? | [OVHcloud Docs](https://docs.ovh.com/gb/en/) |
| Exoscale       | Switzerland   | PostgreSQL, MySQL, Redis                            | From ~€10/month       | Yes     | ? | [Exoscale Docs](https://www.exoscale.com/docs/) |
| UpCloud        | Finland       | PostgreSQL                                          | From ~€15/month       |  Yes     | ? | [UpCloud Docs](https://upcloud.com/docs/) |
| IONOS          | Germany       | PostgreSQL, MySQL, MongoDB                          | From ~€5/month        |  Yes     | ? | [IONOS Docs](https://www.ionos.com/help/) |
| Stackhero      | France        | PostgreSQL, MySQL, Redis, MongoDB, Elasticsearch    | From ~€15/month       |  Yes     | ? | [Stackhero Docs](https://docs.stackhero.io/) |
| Seeweb         | Italy         | PostgreSQL, MySQL                                   | From ~€10/month        | Yes     | ? | [Seeweb Docs](https://kb.seeweb.it/) |
| Safe Swiss Cloud | Switzerland | PostgreSQL, MySQL, MongoDB                          | From ~€20/month        |  Yes     | ? | [Safe Swiss Cloud Docs](https://www.safeswisscloud.com/) |
| Timescale      | USA           | PostgreSQL                                          | From ~€10/month | Yes | ? | [Timescale Docs](https://docs.timescale.com/) |
| ScaleGrid      | USA           | PostgreSQL, MySQL, MongoDB                          | From ~€20/month         | Yes     | ? | [ScaleGrid Docs](https://scalegrid.io/docs/) |



## Database container images:
You can also run your own database in a container, keep in mind the database need to run on persistance storage

| Database      | Docker Image Link                                      | Open Source | License Required |
|---------------|--------------------------------------------------------|-------------|------------------|
| PostgreSQL    | [postgres](https://hub.docker.com/_/postgres)          |  Yes       |  PostgreSQL License (permissive) |
| MySQL         | [mysql](https://hub.docker.com/_/mysql)                |  Yes       |  GPLv2 – commercial license available for proprietary use |
| SQLite        | [nouchka/sqlite3](https://hub.docker.com/r/nouchka/sqlite3) |  Yes  |  Public domain (sqlite.org) |
| MS SQL Server    | [mcr.microsoft.com/mssql/server](https://hub.docker.com/_/microsoft-mssql-server) | No |  Free Developer/Express editions available |
| MongoDB       | [mongo](https://hub.docker.com/_/mongo)                |  Yes       | SSPL – not OSI approved, restrictions apply for SaaS |
| Redis         | [redis](https://hub.docker.com/_/redis)                |  Yes       |  BSD 3-Clause |
| MariaDB       | [mariadb](https://hub.docker.com/_/mariadb)            |  Yes       |  GPLv2 |

## Single Docker Container hosters:

| Cloud Provider    | Headquarter  | Persistent Storage | Out-of-the-box Backup | Price in Euro (approx.)          | OpenSource | CO₂ Emission        | Documentation                                                        |
|------------------|--------------|--------------------|-----------------------|----------------------------------|------------|---------------------|----------------------------------------------------------------------|
| Microsoft Azure  | USA          |  Yes             | Yes                   | ~€20 - €100/month                | No         | ?                   | [Azure Container Instances](https://learn.microsoft.com/en-us/azure/container-instances/) |
| AWS              | USA          |  Yes             | Yes                   | ~€15 - €90/month                 | No         | ?                   | [AWS Fargate](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html) |
| Google Cloud     | USA          |  Yes             | Yes                   | ~€20 - €90/month                 | No         | ?                   | [Google Cloud Run](https://cloud.google.com/run/docs)                 |
| DigitalOcean     | USA          |  No              | No                    | ~€10 - €40/month                 | No         | ?                   | [DigitalOcean App Platform](https://www.digitalocean.com/docs/app-platform/) |
| Heroku           | USA          |  No              | Yes                   | ~€7 - €50/month                  | No         | ?                   | [Heroku Container Registry](https://devcenter.heroku.com/articles/container-registry-and-runtime) |
| Scaleway         | France       |  No              | ?                     | ~€10 - €50/month                 | No         | ?                   | [Scaleway Containers](https://www.scaleway.com/en/docs/containers/)  |
| Exoscale         | Switzerland  |  Yes             | ?                     | ~€15 - €60/month                 | No         | ?                   | [Exoscale Kubernetes & Containers](https://www.exoscale.com/pricing/)|
| UpCloud          | Finland      |  Yes             | ?                     | ~€20 - €60/month                 | No         | ?                   | [UpCloud Container Hosting](https://www.upcloud.com/cloud-hosting/)  |
| Railway          | USA          |  No              | Yes                   | ~€5/month    | No         | ?                   | [Railway](https://railway.app/docs/deploy/docker)                    |
| Render           | USA          |  Yes             | Yes                   | ~€7/month   | No         | ?                   | [Render Docker Services](https://render.com/docs/docker)             |
| Leafcloud        | Netherlands  |  Yes             | ?                     | ~€15 - €45/month                 | No         | ?                   | [Leafcloud Docs](https://www.leafcloud.nl/docs)                      |
| Gridscale        | Germany      |  Yes             | ?                     | ~€15 - €50/month                 | No         | ?                   | [Gridscale Docs](https://gridscale.io/en/documentation)              |
| Stackhero        | France       |  Yes             | Yes                   | ~€15 - €50/month                 | No         | ?                   | [Stackhero Docs](https://docs.stackhero.io/)                         |
| NeoNephos        | Germany      | ?                | ?                     | ~€20 - €60/month                 | No         | ?                   | [NeoNephos Docs](https://neonephos.org/docs/)                        |

### managed Kubernetes platform

| Cloud Provider    | Headquarter | Persistent Storage | Out-of-the-box Backup | Price in Euro (2-node cluster) | OpenSource | Kubernetes Version | CO₂ Emissions         | Documentation |
|------------------|-------------|--------------------|-----------------------|-------------------------------|------------|--------------------|-----------------------|---------------|
| **Microsoft Azure**  | USA         | Yes (Azure Disks, Azure Files) |  Yes                   | ~€160–€200/month              |  No         | AKS                | ?      | [AKS Docs](https://learn.microsoft.com/en-us/azure/aks/) |
| **AWS**              | USA         | Yes (EBS, EFS)              | Yes              | ~€200–€250/month              |  No        | EKS                | ?      | [EKS Docs](https://docs.aws.amazon.com/eks/) |
| **GCP**              | USA         | Yes (Persistent Disks, Cloud Storage) |  Yes              | ~€150–€220/month              |  No        | GKE                | ?      | [GKE Docs](https://cloud.google.com/kubernetes-engine/) |
| **IONOS**            | Germany     | Yes (Integrated Block Storage) | ?              | ~€60–€80/month                |  No        | ?      | ?         | [IONOS Kubernetes](https://cloud.ionos.co.uk/managed/kubernetes) |
| **Gcore**            | Luxembourg  | Yes (Volumes via PVC)       | ?              | ~€70–€80/month                |  No        | ?      | ?         | [Gcore Kubernetes](https://gcore.com/cloud/managed-kubernetes) |
| **Cyso Cloud**       | Netherlands | Yes (NVMe SSD Block Storage) | ?              | ~€75.98/month                 |  No        | ?      | ?         | [Cyso Kubernetes](https://cyso.cloud/managed-kubernetes/) |
| **PlusServer**       | Germany     | Yes (Cinder CSI Plugin)     | ?              | ~€100–€120/month              |  No        | ?      | ?         | [PlusServer Kubernetes](https://www.plusserver.com/en/product/managed-kubernetes/) |
| **OVHcloud**         | France      | Yes (Cinder-based Volumes)  | ?              | ~€55–€73/month                |  No        | ?      | ?         | [OVHcloud Pricing](https://www.ovhcloud.com/en/public-cloud/prices/) |
| **Exoscale**         | Switzerland | Yes (Block Storage via CSI) | ?              | ~€136/month                   |  No        | ?      | ?         | [Exoscale Kubernetes](https://www.exoscale.com/pricing/) |
| **Infomaniak**       | Switzerland | Yes (Block Storage)         | ?          | ~€55/month                    |  No        | ?      | ?         | [Infomaniak Kubernetes](https://zifeo.com/articles/230617-low-cost-k8s) |
| **ASERGO**           | Denmark     | Yes (Standard Kubernetes Support) | ?              | ?                 |  No        | ?      | ?         | [ASERGO Kubernetes](https://asergo.com/kubernetes/kubernetes-cluster-pricing) |
| **ScaleUp Tech**     | Germany     | ?                     | ?              | ?                 |  No        | ?      | ?         | [ScaleUp Kubernetes](https://www.scaleuptech.com/en/cloud-hosting/managed-kubernetes/) |
| **Leafcloud**        | Netherlands | Yes (Block Storage)         | ?              | €80/month                     |  No        | ?      | Heat recycling powered | [Leafcloud Kubernetes](https://leaf.cloud/products/kubernetes/) |


#VM


| Cloud Provider    | Headquarter        | Out-of-the-box Backup | Price in Euro (2-core VM) | OpenSource | Hypervisor | CO₂ Emissions (kg CO₂e/hour) | Documentation |
|------------------|-------------         |-----------------------|---------------------------|------------|------------|------------------------------|---------------|
| Microsoft Azure  | USA                  | Yes                   | €29.95–€216.00/month      | No         | Hyper-V    | ?   | [Azure AKS](https://learn.microsoft.com/en-us/azure/) |
| AWS              | USA                  | Yes                   | €29.95–€216.00/month      | No         | Xen/KVM    | 0.0093–0.0142                | [AWS EKS](https://docs.aws.amazon.com/) |
| GCP              | USA                  | Yes                   | €29.95–€216.00/month      | No         | KVM        | ?   | [GCP GKE](https://cloud.google.com/) |
| UpCloud          | Finland              | yes              | €18–€35/month             | No         | KVM        | ?       | [UpCloud Resources](https://upcloud.com/resources/) |
| Leaseweb         | Netherlands          | Yes                   | €26,02/month              | No         | VMware     | ?       | [Leaseweb Backup](https://www.leaseweb.com/en/products-services/) |
| Fuga Cloud       | Netherlands          | ?              | €29.95–€216.00/month      | No         | KVM        | ?       | [Fuga Cloud](https://fuga.cloud/) |
| Hetzner        | Germany                | yes              | €4.15/month               | No         | KVM        | ? | https://www.hetzner.com/cloud |
| OVHcloud       | France                 | yes              | €29.34/month              | No         | KVM        | ? | https://www.ovhcloud.com/en-ie/public-cloud/prices/ |
| Gcore          | Luxembourg             | ?              | €30.02/month              | No         | KVM        | ? | https://gcore.com/pricing/cloud |
| EuroVPS        | Netherlands            | ?              | €36/month                 | No         | KVM        | ? | https://www.eurovps.com/cloud-servers |
| LifeinCloud    | Italy                  | Yes                   | €17/month                 | No         | KVM        | ? | https://lifeincloud.com/products/virtual-machines/cloud-servers/ |
| IONOS          | Germany                | ?              | ?                         | No         | VMware     | ? | https://cloud.ionos.co.uk/prices |
| Exoscale | Switzerland                  | ?              | €17–€36/month             | No         | KVM        | ? | https://www.exoscale.com/pricing/ |
| STACKIT |  Germany                     | ?               | ?                         | No        | KVM        | ? | https://www.stackit.de/en/pricing/cloud-services/ |
| gridscale | Germany | ? | ? | No | KVM | ? | https://gridscale.io/en/pricing/ |
| Neonephos | Netherlands | ? | ? | No | KVM | ? | https://neonephos.org/ |




[![Edit on GitHub](https://img.shields.io/badge/Edit_on_GitHub-blue?logo=github)](https://github.com/mikekrom1/nomadsky/edit/main/content/RunningDatabase.md)

Explaination:
* An out of the box backup means the cloud provider has a backup-as-a-solution implementation so you dont need to run a decidated VM with backup software.
* Price in Euro is determined for hosting a 2 core VM or 2 nodes in a cluster or the smallest option they provide for one month.
* A cloud provider is labeled as Opensource when their hosting platform is public available.
* CO2 emissions are determined based on running this service for 1 hour.     
