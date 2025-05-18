# Hosting Options for .NET Applications

This page provides a clear overview of where and how you can host your .NET application. From fully managed platforms to containers and virtual machines, we list the most common providers and hosting types. 
so you can choose the setup that best fits your needs for control, scalability, and ease of management.


### VM


| Cloud Provider    | Headquarter (legal) | Out-of-the-box Backup | Price in Euro (2-core VM) | OpenSource | Hypervisor | CO₂ Emissions (kg CO₂e/hour) | Documentation |
|------------------|-------------         |-----------------------|---------------------------|------------|------------|------------------------------|---------------|
| Microsoft Azure  | USA                  | Yes                   | €29.95–€216.00/month      | No         | Hyper-V    | Varies by region and usage   | [Azure AKS](https://learn.microsoft.com/en-us/azure/aks/) |
| AWS              | USA                  | Yes                   | €29.95–€216.00/month      | No         | Xen/KVM    | 0.0093–0.0142                | [AWS EKS](https://docs.aws.amazon.com/eks/) |
| GCP              | USA                  | Yes                   | €29.95–€216.00/month      | No         | KVM        | Varies by region and usage   | [GCP GKE](https://cloud.google.com/kubernetes-engine/) |
| UpCloud          | Finland              | Optional              | €18–€35/month             | No         | KVM        | Not publicly disclosed       | [UpCloud Resources](https://upcloud.com/resources/) |
| Leaseweb         | Netherlands          | Yes                   | €26,02/month              | No         | VMware     | Not publicly disclosed       | [Leaseweb Backup](https://www.leaseweb.com/en/products-services/back-up) |
| Fuga Cloud       | Netherlands          | Optional              | €29.95–€216.00/month      | No         | KVM        | Not publicly disclosed       | [Fuga Cloud](https://fuga.cloud/) |
| Hetzner        | Germany                | Optional              | €4.15/month               | No         | KVM        | Not disclosed | https://www.hetzner.com/cloud |
| OVHcloud       | France                 | Optional              | €29.34/month              | No         | KVM        | Not disclosed | https://www.ovhcloud.com/en-ie/public-cloud/prices/ |
| Gcore          | Luxembourg             | Optional              | €30.02/month              | No         | KVM        | Not disclosed | https://gcore.com/pricing/cloud |
| EuroVPS        | Netherlands            | Optional              | €36/month                 | No         | KVM        | Not disclosed | https://www.eurovps.com/cloud-servers |
| LifeinCloud    | Italy                  | Yes                   | €17/month                 | No         | KVM        | Not disclosed | https://lifeincloud.com/products/virtual-machines/cloud-servers/ |
| IONOS          | Germany                | Optional              | ?                         | No         | VMware     | Not disclosed | https://cloud.ionos.co.uk/prices |
| Exoscale | Switzerland                  | Optional              | €17–€36/month             | No         | KVM        | Not disclosed | https://www.exoscale.com/pricing/ |
| STACKIT |  Germany                     | Optional               | Pricing varies             | No        | KVM        | Not disclosed | https://www.stackit.de/en/pricing/cloud-services/ |
| gridscale | Germany | Optional | Pricing varies | No | KVM | Not disclosed | https://gridscale.io/en/pricing/ |
| Neonephos | Netherlands | Optional | Pricing varies | No | KVM | Not disclosed | https://neonephos.org/ |


### AKS

| Cloud Provider    | Headquarter | Out-of-the-box Backup | Price in Euro (2-node cluster) | OpenSource | Kubernetes Version | CO₂ Emissions         | Documentation |
|------------------|-------------|-----------------------|-------------------------------|------------|--------------------|-----------------------|---------------|
| Microsoft Azure  | USA         | Yes                   | ~€160–€200/month              | No         | AKS                | Varies by region      | [AKS Docs](https://learn.microsoft.com/en-us/azure/aks/) |
| AWS              | USA         | Optional              | ~€200–€250/month              | Yes        | EKS                | Varies by region      | [EKS Docs](https://docs.aws.amazon.com/eks/) |
| GCP              | USA         | Optional              | ~€150–€220/month              | Yes        | GKE                | Varies by region      | [GKE Docs](https://cloud.google.com/kubernetes-engine/) |
| IONOS            | Germany     | Optional              | ~€60–€80/month                | Yes        | CNCF Certified     | 100% renewable energy | [IONOS Kubernetes](https://cloud.ionos.co.uk/managed/kubernetes) |
| Gcore            | Luxembourg  | Optional              | ~€70–€80/month                | Yes        | CNCF Certified     | Not disclosed         | [Gcore Kubernetes](https://gcore.com/cloud/managed-kubernetes) |
| Cyso Cloud       | Netherlands | Optional              | ~€75.98/month                 | Yes        | CNCF Certified     | Not disclosed         | [Cyso Kubernetes](https://cyso.cloud/managed-kubernetes/) |
| PlusServer       | Germany     | Optional              | ~€100–€120/month              | Yes        | CNCF Certified     | Not disclosed         | [PlusServer Kubernetes](https://www.plusserver.com/en/product/managed-kubernetes/) |
| OVHcloud         | France      | Optional              | ~€55–€73/month                | Yes        | CNCF Certified     | High sustainability   | [OVHcloud Pricing](https://www.ovhcloud.com/en/public-cloud/prices/) |
| Exoscale         | Switzerland | Optional              | ~€136/month                   | Yes        | CNCF Certified     | Not disclosed         | [Exoscale Kubernetes](https://www.exoscale.com/pricing/) |
| Infomaniak       | Switzerland | Optional              | ~€55/month                    | Yes        | CNCF Certified     | Not disclosed         | [Infomaniak Kubernetes](https://zifeo.com/articles/230617-low-cost-k8s) |
| ASERGO           | Denmark     | Optional              | Contact for pricing           | Yes        | CNCF Certified     | Not disclosed         | [ASERGO Kubernetes](https://asergo.com/kubernetes/kubernetes-cluster-pricing) |
| ScaleUp Tech     | Germany     | Optional              | Contact for pricing           | Yes        | CNCF Certified     | Sustainable data centers | [ScaleUp Kubernetes](https://www.scaleuptech.com/en/cloud-hosting/managed-kubernetes/) |
| Leafcloud        | Netherlands | Optional              | €80/month                     | Yes        | CNCF Certified     | Heat recycling powered | [Leafcloud Kubernetes](https://leaf.cloud/products/kubernetes/) |
| ScaleOps     | Israel      | N/A                   | €230–€250/month               | N/A        | N/A                | N/A                   | [ScaleOps Docs](https://scaleops.com/) |


## Runtime (no container)

| Cloud Provider | Headquarter | Out of the box backup | Price in Euro (approx.) | OpenSource | CO₂ Emission*       | Documentation                                             |
|----------------|-------------|-----------------------|-------------------------|------------|---------------------|-----------------------------------------------------------|
| Microsoft Azure | USA         | Yes                   | €100 - €200/month       | No         | Varies by region    | [Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/) |
| AWS             | USA         | Optional              | €120 - €220/month       | No         | Varies by region    | [AWS Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/) |
| Google Cloud    | USA         | Optional              | €100 - €180/month       | No         | Varies by region    | [Google App Engine](https://cloud.google.com/appengine/docs) |
| NodeChef        | USA (Global)| Yes                   | €50 - €90/month         | No         | Not disclosed       | [NodeChef .NET Hosting](https://www.nodechef.com/dotnet-hosting) |
| OVHcloud        | France      | Optional              | €40 - €70/month         | No         | High sustainability | [OVHcloud Managed Hosting](https://www.ovhcloud.com/en/web-hosting/) |
| Platform.sh     | France      | Yes                   | Contact for pricing     | No         | Not disclosed       | [Platform.sh .NET](https://platform.sh/docs/languages/dotnetcore/) |
| Cloudways   | Malta       | Yes                   | €50 - €100/month        | No         | Varies by provider  | [Cloudways Managed Hosting](https://www.cloudways.com/en/) |
| Stackhero   | France      | Yes                   | €15 - €90/month         | No         | 100% renewable      | [Stackhero Managed Services](https://www.stackhero.io/en/) |


[![Edit on GitHub](https://img.shields.io/badge/Edit_on_GitHub-blue?logo=github)](https://github.com/mikekrom1/nomadsky/edit/main/content/hostingdotnet.md)
