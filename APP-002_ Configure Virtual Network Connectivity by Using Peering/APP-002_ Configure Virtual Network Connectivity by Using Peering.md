**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 14 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Name of the Challenge:** APP-002_ Configure Virtual Network Connectivity by Using Peering

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Create a virtual network by using the Azure
  - created a virtual network named webVNET
  - created a subnet named web in the webVNET virtual network.
  - can use an [Azure virtual network](https://docs.microsoft.com/en-us/azure/virtual-network/concepts-and-best-practices) to create a network address space in the cloud that you will use to host resources—for example, virtual machines, load balancers, and application gateways—for secure access from on-premises networks and other virtual networks
- Create a virtual network by using Azure Cloud Shell
  - launching an Azure Cloud Shell Bash session
  - can use [Azure Cloud Shell](https://docs.microsoft.com/en-us/azure/cloud-shell/overview) to execute commands and scripts directly from the browser without having to pre-install the Azure command-line interface (CLI) or PowerShell® on a client computer. Cloud Shell uses a storage account for its implementation so that you can switch between remote devices while maintaining your scripts and files in the cloud.
  - In Azure Cloud Shell, run the following command to create a virtual network and subnet:  
        <br/>az network vnet create --name appVNET --resource-group corp-datalod40646264 --address-prefix 10.20.0.0/16 --subnet-name app --subnet-prefix 10.20.0.0/25
  - Verify that you created a virtual network named appVNET that contains a subnet named app by using the az network vnet show command.
  - Run the following command to verify the presence of a virtual network and subnet:  
        <br/>az network vnet show --name appVNET --resource-group corp-datalod40646264
  - created a virtual network named appVNET.
  - created a subnet named app in the appVNET virtual network.
- Configure peering connections between the virtual networks
  - Create virtual network peering connections from webVNET to **appVNET** by using the values in the following table. For any property that is not specified, use the default value.
  - created a network peering connection from webVNET to appVNET.
  - created a network peering connection from appVNET to webVNET.

**Lab Topology**

Create a virtual network in the Azure portal by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod40646264** |
| Name | webVNET |
| IPv4 address space | 10.10.0.0/16 |
| Subnet name | web |
| Subnet address range | 10.10.0.0/25 |

Launch an Azure Cloud Shell **Bash** session by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod40646264** |
| Storage account | cs40646264 |
| File share | cloudshell |

Create a virtual network by using the [az network vnet create](https://docs.microsoft.com/en-us/cli/azure/network/vnet?view=azure-cli-latest"%20\o%20"The%20az%20network%20vnet%20create%20command%20documentation"%20\t%20"_blank) Azure CLI command and the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| name | appVNET |
| resource-group | **corp-datalod40646264** |
| address-prefix | 10.20.0.0/16 |
| subnet-name | app |
| subnet-prefix | 10.20.0.0/25 |

Create virtual network peering connections from webVNET to **appVNET** by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| This virtual network - Peering link name | webVNET-to-appVNET |
| Remote virtual network - Peering link name | appVNET-to-webVNET |
| Virtual network | **appVNET** |

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

- Create a virtual network by using the Azure
  - I created a virtual network named webVNET and subnet named web in the webVNET virtual network.
- Create a virtual network by using Azure Cloud Shell
  - I can launch an Azure Cloud Shell Bash session
  - I can use [Azure Cloud Shell](https://docs.microsoft.com/en-us/azure/cloud-shell/overview) to execute commands and scripts directly from the browser without having to pre-install the Azure command-line interface (CLI) or PowerShell® on a client computer. Cloud Shell uses a storage account for its implementation so that you can switch between remote devices while maintaining your scripts and files in the cloud.
  - I learnt the following command to create a virtual network and subnet:  
        <br/>az network vnet create --name appVNET --resource-group corp-datalod40646264 --address-prefix 10.20.0.0/16 --subnet-name app --subnet-prefix 10.20.0.0/25
  - I created a virtual network named appVNET that contains a subnet named app by using the az network vnet show command.
  - I learnt the following command to verify the presence of a virtual network and subnet:  
        <br/>az network vnet show --name appVNET --resource-group corp-datalod40646264
  - I created a virtual network named appVNET and subnet named app in the appVNET virtual network.
- Configure peering connections between the virtual networks
  - I create virtual network peering connections from webVNET to **appVNET** by using the values in the following table. For any property that is not specified, use the default value.
  - I created a network peering connection from webVNET to appVNET.
  - I created a network peering connection from appVNET to webVNET.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:** [**https://www.loom.com/share/9f01698420144b25a67dd254531b5d0a?sid=d413578b-0ced-4bc6-8a6d-6919bf9d0aef**](https://www.loom.com/share/9f01698420144b25a67dd254531b5d0a?sid=d413578b-0ced-4bc6-8a6d-6919bf9d0aef)