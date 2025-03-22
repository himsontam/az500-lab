**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Can You Configure Multi-Scope Resource Permissions \[Expert\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Assigned roles at the resource group scope.
  - Assign the roles in the following table to allow users to manage specific resource types in the corp-datalod41229087 resource group:
- Created Azure network resources as a specific user.
  - Create a virtual network
  - Add a subnet
  - Create a network security group
  - Add an inbound security rule
  - Associate the webNSG network security group
  - Create a public IP address named
- Created an Azure virtual machine as a specific user.
- Assigned a role at the resource scope.
  - Assign the Virtual Machine Contributor role to manage only the VM1 virtual machine resource.
  - Associate the webIP public IP address to the existing **network interface** of the virtual machine **VM1**.

**Lab Topology**

Assign the roles in the following table to allow users to manage specific resource types in the corp-datalod41229087 resource group:

| **Role** | **User Name** |
| --- | --- |
| Network Contributor | Dev1-41229087 |
| Storage Account Contributor | Dev1-41229087 |
| Virtual Machine Contributor | Dev2-41229087 |

Create an Azure virtual machine by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41229087** |
| Virtual machine name | VM1 |
| Image | **Windows Server 2019 Datacenter - Gen2** |
| Size | **Standard_B2s - 2 vcpus 4 GiB memory** |
| Username | AzureAdmin |
| Password | Az!41229087! |
| Public inbound ports | **None** |
| Virtual network | **VNET1** |
| Subnet | **web (10.10.0.0/26)** |
| Public IP | **None** |
| NIC network security group | **None** |
| Boot diagnostics | **Disable** |

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

- I have learnt how to assign roles at the resource group scope.
- I have learnt how to create Azure network resources as a specific user.
  - I have learnt how to create a virtual network, Add a subnet, Create a network security group, Add an inbound security rule, Associate the webNSG network security group, and Create a public IP address
- I have learnt how to create an Azure virtual machine as a specific user.
  - I have learnt how to Virtual Machine Contributor role to manage only virtual machine resource.
  - I have learnt how to associate the public IP address to the existing **network interface** of the virtual machine **VM1**.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/215cc05e965b4d44af8a57a999593d6c?sid=325cc4d0-1bb1-4473-8b0f-b8df54144377**](https://www.loom.com/share/215cc05e965b4d44af8a57a999593d6c?sid=325cc4d0-1bb1-4473-8b0f-b8df54144377)