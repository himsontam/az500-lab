**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Can You Manage Access to Azure Key Vault by Using Templates \[Expert\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created a virtual machine.
  - Create an Azure virtual machine
  - Install the Azure Automanage Machine Configuration extension for Windows on the **webVM1** virtual machine by using the default settings.
- Enabled Azure Disk Encryption on a virtual machine.
  - Create an Azure key vault
  - Enable Azure Disk Encryption for the webVM1 **OS disk** by using the **KV41230361** key vault and a new key named WebVM1-key.
- Created an Azure SQL database.
  - Create an Azure SQL database.
  - Enable Microsoft Defender for SQL for the **db41230361** database.
- Enabled Microsoft Defender for SQL.
  - Perform a vulnerability assessment for the **db41230361** database.
- Created an Azure Cosmos DB account.
- Create an Azure Cosmos DB account by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| API | **Azure Cosmos DB for NoSQL** |
| Resource Group | **corp-datalod41230361** |
| Account Name | cosmos41230361 |
| Location | **(US) East US** |
| Apply Free Tier Discount | **Do Not Apply** |
| Geo-Redundancy | **Disable** |
| Multi-region Writes | **Disable** |

- Update the cosmos41230361 Cosmos DB account to allow access from your **current IP** address and **accept connections from within public Azure datacenters**.
- Create a container in a new database in the cosmos41230361 account by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Database id | Database1 |
| Container id | Customers |
| Partition key | /\_partitionKey |
| Container throughput | **Manual** |
| Estimate your required RU/s with capacity calculator | 500 |

- Create a new item in the **Customers** container by using the following JSON code:

{

"firstName": "Tracy",

"lastName": "Nguyen",

"age": 32,

"salary": 90000.00,

"company": "Veraq",

"isVested": false

}

- Create a second item in the Customers container by using the following JSON code:

{

"firstName": "Shrestha",

"lastName": "Patel",

"company": "BEC"

}

- Execute a new query that selects all of the items in the **Customers** container.
- Enabled RBAC.
  - Assign the Cosmos DB Account Reader Role role to User1-41230361 for the cosmos41230361 Cosmos DB account.

**Lab Topology**

Create an Azure virtual machine by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230361** |
| Virtual machine name | webVM1 |
| Image | **Windows Server 2019 Datacenter - x64 Gen2** |
| Size | **Standard_B2ms** |
| Username | AzureAdmin |
| Password | Az!41230361! |
| Public inbound ports | **Allow selected ports** |
| Select inbound ports | **RDP (3389)** |
| OS disk type | **Standard HDD** |
| Boot diagnostics | **Disable** |

Create an Azure key vault by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230361** |
| Key vault name | KV41230361 |
| Pricing tier | **Standard** |
| Permission model | **Azure role-based access control** |
| Azure Virtual Machines for deployment | **Selected** |
| Azure Resource Manager for template deployment | **Selected** |
| Azure Disk Encryption for volume encryption | **Selected** |

Create an Azure SQL database on a new logical SQL server by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230361** |
| Database name | db41230361 |
| Server name | sql41230361 |
| Authentication method | **Use SQL authentication** |
| Server admin login | AzureAdmin |
| Password | AzPwd41230361! |
| Workload environment | **Development** |
| Service Tier | **Standard (Budget friendly)** |
| DTUs | **10** |
| Data max size (GB) | **250** |
| Connectivity method | **Public endpoint** |
| Allow Azure services and resources to access this server | **Yes** |
| Add current client IP address | **Yes** |
| Enable Microsoft Defender for SQL | **Not now** |
| Use existing data | **Sample** |

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

- - I learnt how to create a virtual machine and install the Azure Automanage Machine Configuration extension for Windows on virtual machine
    - I learnt how to enable Azure Disk Encryption on a virtual machine.
      - I learnt how to create an Azure key vault and enable Azure Disk Encryption for **OS disk** by using key vault
    - I learnt how to create an Azure SQL database and enable Microsoft Defender for SQL for database.
- I learnt how to enable Microsoft Defender for SQL and perform a vulnerability assessment for database.
- I learnt how to create an Azure Cosmos DB account and then allow access from your **current IP** address and **accept connections from within public Azure datacenters**.
- I learnt how create a container in a new database, and learnt how to create a new item in container by using JSON code.
- I learnt how to execute a new query that selects all of the items in the **Customers** container.
- I learnt how to enable RBAC by assigning the Cosmos DB Account Reader Role role to Cosmos DB account.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/3cc74b4744554f29abb1813e164aa1aa?sid=450c1c9e-96f2-427e-925d-d9c82bdb908b**](https://www.loom.com/share/3cc74b4744554f29abb1813e164aa1aa?sid=450c1c9e-96f2-427e-925d-d9c82bdb908b)