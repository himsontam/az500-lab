**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Can You Configure Network Security to Allow Application Traffic \[Advanced\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created Azure virtual networks.
  - Create a virtual network for the web tier
  - Create a virtual network for the application tier
  - Create a virtual network for the database tier
- I have created three virtual networks named webVNET, appVNET, and dbVNET.
- i have created two peering connections between webVNET and appVNET.
- i have created two peering connections between appVNET and dbVNET.
- Implemented peering for internal communication between virtual networks.
  - Create virtual network peering connections from webVNET to **appVNET**
- Created Azure virtual machines for a multi-tier app.
  - I have created a virtual machine named webVM1.
  - I have created a virtual machine named appVM1.
  - I have created a virtual machine named dbVM1.
- Configured a network security group.
  - Add an inbound security rule to the webVM1-nsg NSG
  - in **Windows PowerShell** to install IIS:
    - Install-WindowsFeature -name web-Server -IncludeManagementTools
  - I have added an inbound security rule named AllowAllweb to the webVM1-nsg NSG that allows HTTP and HTTPS traffic.
- Configured an inbound security rule to allow HTTP and HTTPS traffic.

**Lab Topology**

Create a virtual network for the web tier by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230538** |
| Name | webVNET |
| IPv4 address space | 10.10.0.0/16 |
| Subnet name | web |
| Subnet address range | 10.10.0.0/25 |

Create a virtual network for the application tier by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230538** |
| Name | appVNET |
| IPv4 address space | 10.20.0.0/16 |
| Subnet name | app |
| Subnet address range | 10.20.0.0/25 |

Create a virtual network for the database tier by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230538** |
| Name | dbVNET |
| IPv4 address space | 10.30.0.0/16 |
| Subnet name | db  |
| Subnet address range | 10.30.0.0/25 |

Create virtual network peering connections from webVNET to **appVNET** by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| This virtual network - Peering link name | webVNET-to-appVNET |
| Remote virtual network - Peering link name | appVNET-to-webVNET |
| Virtual network | **appVNET** |

Create an Azure virtual machine for the web tier by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230538** |
| Virtual machine name | webVM1 |
| Image | **Windows Server 2019 Datacenter - Gen2** |
| Size | **Standard_B2ms - 2 vcpus 8 GiB memory** |
| Username | AzureAdmin |
| Password | Az!41230538! |
| Virtual network | **webVNET** |
| Subnet | **web (10.10.0.0/25)** |
| Boot diagnostics | **Disable** |

- Create an Azure virtual machine for the application tier by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230538** |
| Virtual machine name | appVM1 |
| Image | **Ubuntu Server 20.04 LTS - Gen2** |
| Size | **Standard_B2ms - 2 vcpus 8 GiB memory** |
| Authentication type | **Password** |
| Username | AzureAdmin |
| Password | Az!41230538! |
| Virtual network | **appVNET** |
| Subnet | **app (10.20.0.0/25)** |
| Boot diagnostics | **Disable** |

- Create an Azure virtual machine that hosts SQL Server 2019 on Windows Server 2019 by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230538** |
| Virtual machine name | dbVM1 |
| Image | **Free SQL Server License: SQL 2019 Developer on Windows Server 2019 - Gen2** |
| Size | **Standard_B2ms - 2 vcpus 8 GiB memory** |
| Username | AzureAdmin |
| Password | Az!41230538! |
| Virtual network | **dbVNET** |
| Subnet | **db (10.30.0.0/25)** |
| Boot diagnostics | **Disable** |
| SQL connectivity | **Private (within Virtual Network)** |
| SQL Authentication | **Enable** |

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

- - I learnt how to create a virtual network for the web tier, application tier, and database tier
        - I have created three virtual networks named webVNET, appVNET, and dbVNET.
        - i have created two peering connections between webVNET and appVNET.
        - i have created two peering connections between appVNET and dbVNET.
- I have learnt how to implement peering for internal communication between virtual networks.
  - I create virtual network peering connections from webVNET to **appVNET**
- I have learnt how to create Azure virtual machines for a multi-tier app.
  - I have created a virtual machine named webVM1.
  - I have created a virtual machine named appVM1.
  - I have created a virtual machine named dbVM1.
- I have learnt how to configure a network security group and add an inbound security rule to NSG
- I have learnt how to use **Windows PowerShell** to install IIS
  - - Install-WindowsFeature -name web-Server -IncludeManagementTools
  - I have added an inbound security rule to NSG that allows HTTP and HTTPS traffic.
- I have learnt how to configure an inbound security rule to allow HTTP and HTTPS traffic.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/da6c74a68a774e258e0bc2be1cf7e9f9?sid=72e30e3b-0fb2-4431-a9dc-aa41b0e502e1**](https://www.loom.com/share/da6c74a68a774e258e0bc2be1cf7e9f9?sid=72e30e3b-0fb2-4431-a9dc-aa41b0e502e1)