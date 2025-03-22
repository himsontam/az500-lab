**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Configure an Application Security Group \[Guided\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created a virtual network for a web server tier.
  - Create a virtual network
  - I created a virtual network named webVNET.
  - i created a subnet named web in the webVNET virtual network.
- Created an application security group and associated network security group.
  - Create an application security group named webASG in the **corp-datalod41230482** resource group.
  - Create a network security group named webNSG in the **corp-datalod41230482** resource group.
  - Add an inbound security rule to webNSG to allow HTTP and HTTPS traffic
  - Add a second inbound security rule to **webNSG** to allow RDP traffic
  - Associate the network security group to the **web** subnet in **webVNET**.
  - I created an application security group named webASG.
  - I created a network security group named webNSG.
  - I created inbound security rules that allow RDP, HTTP, and HTTPS traffic to flow to webASG.
  - I associated the web subnet with the webNSG network security group.
- Created an Azure virtual machine and tested application security.
  - Create an Azure virtual machine
  - Associate the **webASG** application security group with the VM1 virtual machine NIC.
  - Connect to VM1 through **RDP**
  - in **Windows PowerShell®** to install Internet Information Services (IIS):
    - Install-WindowsFeature -name web-Server -IncludeManagementTools
- I created an Azure virtual machine named VM1.
- i associated the webASG application security group with the virtual machine NIC.
- i installed IIS on the virtual machine via RDP.
- i have routed web traffic correctly.

**Lab Topology**

Create a virtual network in the Azure portal by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230482** |
| Name | webVNET |
| IPv4 address space | 10.10.0.0/16 |
| Subnet name | web |
| Subnet address range | 10.10.0.0/25 |

Create an Azure virtual machine by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230482** |
| Virtual machine name | VM1 |
| Image | **Windows Server 2019 Datacenter - x64 Gen2** |
| Size | **Standard_B2s - 2 vcpus 4 GiB memory** |
| Username | AzureAdmin |
| Password | Az!41230482! |
| Public inbound ports | **None** |
| Virtual network | **webVNET** |
| Subnet | **web (10.10.0.0/25)** |
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

- I have learnt how to create a virtual network for a web server tier.
  - I created a virtual network named webVNET.
  - i created a subnet named web in the webVNET virtual network.
- I have learnt how to create an application security group and associated network security group.
  - I created an application security group named webASG.
  - I created a network security group named webNSG.
  - I created inbound security rules that allow RDP, HTTP, and HTTPS traffic to flow to webASG.
  - I associated the web subnet with the webNSG network security group.
- I learnt how to create an Azure virtual machine and tested application security.
  - I learnt how to use **Windows PowerShell®** to install Internet Information Services (IIS):
    - Install-WindowsFeature -name web-Server -IncludeManagementTools
- I created an Azure virtual machine named VM1.
- i associated the webASG application security group with the virtual machine NIC.
- i installed IIS on the virtual machine via RDP.
- i have routed web traffic correctly.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/a72771c500a94c409927a95723080890?sid=a649485e-ed7b-4027-bfce-3b1efc9aa9ff**](https://www.loom.com/share/a72771c500a94c409927a95723080890?sid=a649485e-ed7b-4027-bfce-3b1efc9aa9ff)