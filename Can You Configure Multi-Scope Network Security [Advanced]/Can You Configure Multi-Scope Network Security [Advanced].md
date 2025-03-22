**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Can You Configure Multi-Scope Network Security \[Advanced\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created an Azure virtual network that contains subnets and a network security group.
  - Create a virtual network
  - Add a subnet
  - Create a network security group
  - Associate the webNSG network security group
- Deployed an Azure virtual machine to each subnet.
  - Create an Azure virtual machine
- Verified web connectivity by using network security groups.
  - Add an inbound security rule
  - Attempt to connect to VM1 by using **RDP** but will show error because the webNSG network security group does not allow RDP traffic from the internet on the web subnet.
  - Connect to VM2 by using **RDP**
  - Start **Windows PowerShell**® in the RDP session for **VM2**, and then run the following command to connect to **VM1** by using a nested RDP session
    - mstsc /v:VM1
  - Install **IIS** in the nested RDP session for **VM1** by using **Windows PowerShell**.

**Lab Topology**

Create a virtual network in the Azure portal by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41229016** |
| Name | webVNET |
| IPv4 address space | 10.10.0.0/16 |
| Subnet name | web |
| Subnet address range | 10.10.0.0/26 |

Create an Azure virtual machine by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41229016** |
| Virtual machine name | VM1 |
| Image | **Windows Server 2022 Datacenter: Azure Edition - x64 Gen2** |
| Size | **Standard_B2s - 2 vcpus 4GiB memory** |
| Username | AzureAdmin |
| Password | Az!41229016! |
| Public inbound ports | **None** |
| Virtual network | **webVNET** |
| Subnet | **web (10.10.0.0/26)** |
| NIC network security group | **None** |
| Boot diagnostics | **Disable** |

Add an inbound security rule to webNSG to allow HTTP and HTTPS traffic by using the values in the following table. For any property that is not specified, use the default value.

| **Setting** | **Value** |
| --- | --- |
| Destination port ranges | 80,443 |
| Protocol | **TCP** |
| Action | **Allow** |
| Name | AllowAllweb |

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

- I learnt how to create an Azure virtual network that contains subnets and a network security group.
  - I create a virtual network, Add a subnet, Create a network security group, and Associate the webNSG network security group
- I have learnt how to deploy an Azure virtual machine to each subnet.
- I have learnt how to verify web connectivity by using network security groups.
  - I have learnt how to Add an inbound security rule
  - I have learnt how to using RDP to connect VM
  - I have learnt how to use **Windows PowerShell**® in the RDP session for **VM2**, and then run the following command to connect to **VM1** by using a nested RDP session
    - mstsc /v:VM1
  - I learnt how to install **IIS** in the nested RDP session for **VM1** by using **Windows PowerShell**.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/b9742855d0a84db5893fe0e82916c995?sid=85d9f37f-a486-478e-9b04-92c667f89132**](https://www.loom.com/share/b9742855d0a84db5893fe0e82916c995?sid=85d9f37f-a486-478e-9b04-92c667f89132)