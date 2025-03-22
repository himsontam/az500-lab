**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Configure Security by Using the Azure Kubernetes Service (AKS) \[Guided\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Deployed an AKS cluster that uses RBAC.
  - Create an Azure Kubernetes Service (AKS) cluster
- Assign the Azure Kubernetes Service Cluster User Role to the <User1-41228124@cloudslice.onmicrosoft.com> user at the resource scope.
- Connected to an AKS cluster as an administrator.
  - Launch an Azure **Cloud Shell** **Bash** session
- Connect to the aks cluster in the corp-datalod41228124 resource group as admin by using the [az aks get-credentials](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest"%20\l%20"az_aks_get_credentials"%20\o%20"The%20az%20aks%20get-credentials%20command%20documentation"%20\t%20"_blank) Azure command-line interface (Azure CLI) command.
  - az aks get-credentials --resource-group corp-datalod41228124 --name aks –admin
- Verify that the current context of the connection to the cluster is **aks-admin** by using the [kubectl config](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"kubectl-context-and-configuration"%20\o%20"The%20kubectl%20config%20command%20documentation"%20\t%20"_blank) command.
  - kubectl config current-context
- Display a list of the cluster nodes by using the [kubectl get](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"viewing-finding-resources"%20\o%20"The%20kubectl%20get%20command%20documentation"%20\t%20"_blank) command.
  - kubectl get nodes
- Deployed an application in the AKS cluster as a non-administrative user.
  - Launch a **Cloud Shell** **Bash** session
- Connect to the aks cluster in the corp-datalod41228124 resource group by using the az aks get-credentials CLI command.
  - - az aks get-credentials --resource-group corp-datalod41228124 --name aks
- Verify that the current context of the connection to the cluster is **aks** by using the kubectl config command.
  - kubectl config current-context
- Attempt to stop the aks cluster in the corp-datalod41228124 resource group by using the [az aks stop](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest"%20\l%20"az_aks_stop"%20\o%20"The%20az%20aks%20stop%20documentation"%20\t%20"_blank) CLI command.
  - az aks stop --resource-group corp-datalod41228124 --name aks
- Deploy an application named nginx-41228124 that uses the nginx container image from Docker Hub by using the [kubectl create deployment](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"creating-objects"%20\o%20"The%20kubectl%20create%20deployment%20command%20documentation"%20\t%20"_blank) command.
- kubectl create deployment nginx-41228124 --image=nginx
- Verify that an AKS pod was created for the application by using the kubectl get command.
- kubectl get pods
- Expose the pod in the nginx-41228124 deployment to the internet for testing by using the [kubectl expose deployment](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"updating-resources"%20\o%20"The%20kubectl%20expose%20deployment%20command%20documentation"%20\t%20"_blank) command.
- kubectl expose deployment nginx-41228124 --port=80 --type=LoadBalancer
- Run the following command to identify the public IP address of the application, and then re-run the command until the value in the **EXTERNAL-IP** column for **nginx-41228124** changes from **&lt;pending&gt;** to a public IP address
- kubectl get services

**Lab Topology**

Create an Azure Kubernetes Service (AKS) cluster by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41228124** |
| Cluster preset configuration | **Dev/Test** |
| Kubernetes cluster name | aks |
| Availability zones | **None** |
| Authentication and Authorization | **Local accounts with Kubernetes RBAC** |
| Node size | **Standard DS2_v2** - 2 vcpus, 8 GiB memory |
| Node count (Maximum node count) | 2   |
| Azure Monitor | **Off** |

Launch an Azure **Cloud Shell** **Bash** session by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41228124** |
| Cloud Shell region | **East US** |
| Storage account | cs41228124 |
| File share | cloudshell |

Launch a **Cloud Shell** **Bash** session by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41228124** |
| Cloud Shell region | **East US** |
| Storage account | **cs41228124** |
| File share | cloudshell |

- **Challenge Details**

**Before starting the challenge:**

1. Be sure that the lab is in the scope of your niche.
2. You have enough time to solve the full lab or have a proper plan to solve a part of it and complete the remaining sections later.
3. Try to build a good learning environment with less distraction for at least 30 minutes to an hour.

**After completing the challenge:**

1. Were you able to finish the lab? Did you need extra time? Was the lab relevant to your expectations? Did you need additional help to solve the lab?

- Yes I am able to finish the lab within 45 mins. It is relevant to my expectations. And I can finish it without additional help.

1. Write down your learning outcomes, skills you developed or improved and the tools you used in this challenge.

_(You may use the keywords listed in the lab details or add your own skills that you think you acquired.)_

- I have learnt how to deployed an AKS cluster that uses RBAC.
- I have learnt how to create an Azure Kubernetes Service (AKS) cluster by assign the Azure Kubernetes Service Cluster User Role
- I have learnt how to connected to an AKS cluster as an administrator.
- I have learnt how to connect to the aks cluster as admin by using the [az aks get-credentials](https://docs.microsoft.com/en-us/cli/azure/aks?view=azure-cli-latest"%20\l%20"az_aks_get_credentials"%20\o%20"The%20az%20aks%20get-credentials%20command%20documentation"%20\t%20"_blank) Azure command-line interface (Azure CLI) command.
  - az aks get-credentials --resource-group corp-datalod41228124 --name aks –admin
- I have learnt how to use this command to verify that the current context of the connection to the cluster is **aks-admin** by using the [kubectl config](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"kubectl-context-and-configuration"%20\o%20"The%20kubectl%20config%20command%20documentation"%20\t%20"_blank) command.
  - kubectl config current-context
- I have learnt how to display a list of the cluster nodes by using the [kubectl get](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"viewing-finding-resources"%20\o%20"The%20kubectl%20get%20command%20documentation"%20\t%20"_blank) command.
  - kubectl get nodes
- I have learnt how to deployed an application in the AKS cluster as a non-administrative user.
- I have learnt how to deploy an application as container image from Docker Hub by using the [kubectl create deployment](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"creating-objects"%20\t%20"_blank"%20\o%20"The%20kubectl%20create%20deployment%20command%20documentation) command.
  - kubectl create deployment nginx-41228124 --image=nginx
- I have learnt how to use the command to verify that an AKS pod was created for the application by using the kubectl get command.
  - kubectl get pods
- I have learnt how to expose the pod in deployment to the internet for testing by using the [kubectl expose deployment](https://kubernetes.io/docs/reference/kubectl/cheatsheet/"%20\l%20"updating-resources"%20\o%20"The%20kubectl%20expose%20deployment%20command%20documentation"%20\t%20"_blank) command.
  - kubectl expose deployment nginx-41228124 --port=80 --type=LoadBalancer
- I learnt how to use this command kubectl get services to get external public IP address

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/d33a184eaf1a4f9caa2ebfa33fed989f?sid=85f008f8-bcdf-444f-bd50-ebc8248938da**](https://www.loom.com/share/d33a184eaf1a4f9caa2ebfa33fed989f?sid=85f008f8-bcdf-444f-bd50-ebc8248938da)