# Hosting Options for .NET, PHP,JAVA, Node.JS, Python, Rust, Ruby Applications

This page provides a clear overview of where and how you can host your application. From fully managed stacks to containers and virtual machines, we list the most common providers and hosting types. 
So you can choose the setup that best fit your needs for control, scalability, and ease of management.

## Click and run (Runtime)

| Supported languages| Cloud Provider | Headquarter | Out of the box backup | Price in Euro (approx.) | OpenSource | CO₂ Emission     | Documentation                                             |
|--------------------|----------------|-------------|-----------------------|-------------------------|------------|---------------------|-----------------------------------------------------------|
|.NET, Java, Nodes.js ,Python, PowerShell, TypeScript, PHP | Microsoft Azure | USA         | Yes                   | €100 - €200/month       | No         | ?    | [Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/) |
| .NET, Java, Nodes.js ,Python, PowerShell, TypeScript, Go, Rust, Ruby | AWS             | USA         | Yes              | €120 - €220/month       | No         | ?    | [AWS Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/) |
|.NET, Java, Python, PHP, Nodes.js , Go, Ruby | Google Cloud    | USA         | Yes              | €100 - €180/month       | No         | ?    | [Google App Engine](https://cloud.google.com/appengine/docs) |
| ?| NodeChef        | USA (Global)| Yes                   | €50 - €90/month         | No         | ?       | [NodeChef .NET Hosting](https://www.nodechef.com/dotnet-hosting) |
|? | OVHcloud        | France      | ?              | €40 - €70/month         | No         | ? | [OVHcloud Managed Hosting](https://www.ovhcloud.com/en/web-hosting/) |
| ?|Platform.sh     | France      | Yes                   | Contact for pricing     | No         | ?       | [Platform.sh .NET](https://platform.sh/docs/languages/dotnetcore/) |
|PHP |Cloudways   | Malta       | Yes                   | €50 - €100/month        | No         | ?  | [Cloudways Managed Hosting](https://www.cloudways.com/en/) |
|Node.js, PHP, Python, Ruby | Stackhero   | France      | Yes                   | €15 - €90/month         | No         | ?      | [Stackhero Managed Services](https://www.stackhero.io/en/) |


## Single Docker Container

| Cloud Provider    | Headquarter  | Out of the box backup | Price in Euro (approx.)          | OpenSource | CO₂ Emission        | Documentation                                                        |
|------------------|--------------|-----------------------|---------------------------------|------------|----------------------|----------------------------------------------------------------------|
| Microsoft Azure   | USA          | Yes                   | ~€20 - €100/month               | No         | ?     | [Azure Container Instances](https://learn.microsoft.com/en-us/azure/container-instances/) |
| AWS              | USA          | Ys              | ~€15 - €90/month                | No         | ?     | [AWS Fargate](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html) |
| Google Cloud     | USA          | Yes              | ~€20 - €90/month                | No         | ?     | [Google Cloud Run](https://cloud.google.com/run/docs)                 |
| DigitalOcean     | USA          | No                    | ~€10 - €40/month                | No         | ?     | [DigitalOcean App Platform](https://www.digitalocean.com/docs/app-platform/) |
| Heroku          | USA          | Yes                   | ~€7 - €50/month                 | No         | ?        | [Heroku Container Registry](https://devcenter.heroku.com/articles/container-registry-and-runtime) |
| Scaleway        | France       | ?              | ~€10 - €50/month                | No         | ?       | [Scaleway Containers](https://www.scaleway.com/en/docs/containers/)  |
| Exoscale        | Switzerland  | ?              | ~€15 - €60/month                | No         | ?        | [Exoscale Kubernetes & Containers](https://www.exoscale.com/pricing/)|
| UpCloud         | Finland      | ?              | ~€20 - €60/month                | No         | ?        | [UpCloud Container Hosting](https://www.upcloud.com/cloud-hosting/)  |
| Railway         | USA          | Yes                   | Free tier, paid from €5/month   | No         | ?        | [Railway](https://railway.app/docs/deploy/docker)                    |
| Render          | USA          | Yes                   | Free tier, paid from ~€7/month  | No         | ?        | [Render Docker Services](https://render.com/docs/docker)             |
| Leafcloud       | Netherlands  | ?              | ~€15 - €45/month                | No         | ?         | [Leafcloud Docs](https://www.leafcloud.nl/docs)                      |
| Gridscale      | Germany       | ?              | ~€15 - €50/month                | No         | ?        | [Gridscale Docs](https://gridscale.io/en/documentation)              |
| Stackhero      | France        | Yes                   | ~€15 - €50/month                | No         | ?       | [Stackhero Docs](https://docs.stackhero.io/)                         |
| NeoNephos     | Germany       | ?              | ~€20 - €60/month                | No         | ?        | [NeoNephos Docs](https://neonephos.org/docs/)                        |

### managed Kubernetes platform

| Cloud Provider    | Headquarter | Out-of-the-box Backup | Price in Euro (2-node cluster) | OpenSource | Kubernetes Version | CO₂ Emissions         | Documentation |
|------------------|-------------|-----------------------|-------------------------------|------------|--------------------|-----------------------|---------------|
| Microsoft Azure  | USA         | Yes                   | ~€160–€200/month              | No         | AKS                | ?      | [AKS Docs](https://learn.microsoft.com/en-us/azure/aks/) |
| AWS              | USA         | yes              | ~€200–€250/month              | Yes        | EKS                | ?      | [EKS Docs](https://docs.aws.amazon.com/eks/) |
| GCP              | USA         | Yes              | ~€150–€220/month              | Yes        | GKE                | ?      | [GKE Docs](https://cloud.google.com/kubernetes-engine/) |
| IONOS            | Germany     | ?              | ~€60–€80/month                | Yes        | ?                   | ? | [IONOS Kubernetes](https://cloud.ionos.co.uk/managed/kubernetes) |
| Gcore            | Luxembourg  | ?              | ~€70–€80/month                | Yes        | ?     | ?         | [Gcore Kubernetes](https://gcore.com/cloud/managed-kubernetes) |
| Cyso Cloud       | Netherlands | ?              | ~€75.98/month                 | Yes        | ?     | ?         | [Cyso Kubernetes](https://cyso.cloud/managed-kubernetes/) |
| PlusServer       | Germany     | ?              | ~€100–€120/month              | Yes        | ?     | ?         | [PlusServer Kubernetes](https://www.plusserver.com/en/product/managed-kubernetes/) |
| OVHcloud         | France      |?              | ~€55–€73/month                | Yes        | ?     | ?   | [OVHcloud Pricing](https://www.ovhcloud.com/en/public-cloud/prices/) |
| Exoscale         | Switzerland | ?              | ~€136/month                   | Yes        | ?     | ?         | [Exoscale Kubernetes](https://www.exoscale.com/pricing/) |
| Infomaniak       | Switzerland | ?              | ~€55/month                    | Yes        | ?     | ?         | [Infomaniak Kubernetes](https://zifeo.com/articles/230617-low-cost-k8s) |
| ASERGO           | Denmark     | ?              | ?           | Yes        | ?     | ?         | [ASERGO Kubernetes](https://asergo.com/kubernetes/kubernetes-cluster-pricing) |
| ScaleUp Tech     | Germany     | ?              | ?           | Yes        | ?     | ? | [ScaleUp Kubernetes](https://www.scaleuptech.com/en/cloud-hosting/managed-kubernetes/) |
| Leafcloud        | Netherlands | ?              | €80/month                     | Yes        | ?     | Heat recycling powered | [Leafcloud Kubernetes](https://leaf.cloud/products/kubernetes/) |

### VM

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








[![Edit on GitHub](https://img.shields.io/badge/Edit_on_GitHub-blue?logo=github)](https://github.com/mikekrom1/nomadsky/edit/main/content/hostingdotnet.md)

Explaination:
* An out of the box backup means the cloud provider has a backup-as-a-solution implementation so you dont need to run a decidated VM with backup software.
* Price in Euro is determined for hosting a 2 core VM or 2 nodes in a cluster or the smallest option they provide for one month.
* A cloud provider is labeled as Opensource when their hosting platform is public available.
* CO2 emissions are determined based on running this service for 1 hour.     

