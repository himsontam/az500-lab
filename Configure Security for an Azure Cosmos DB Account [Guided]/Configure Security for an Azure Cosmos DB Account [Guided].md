**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Configure Security for an Azure Cosmos DB Account \[Guided\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created an Azure Cosmos DB account.
  - Create an Azure Cosmos DB
  - Create a container named Customers in a new database named Database1 in the **cosmos41230322** account by using a partition key of /\_partitionKey and a Container Max RU/s of 1000.
  - Create a new item in the **Customers** container by using the following JSON code:

{

"firstName": "Tracy",

"lastName": "Nguyen",

"age": 32,

"salary": 90000.00,

"company": "Veraq",

"isVested": false

}

- - Create a new SQL query that selects all of the items in the **Customers** container, and then execute the query.
    - I have created a Cosmos DB account with name prefixed by cosmos.
    - I have created a database named Database1 in the Cosmos DB account.
    - I have created a container named Customers in the Database1 database.
    - I have created two items in the Customers container in the Database1 database.
- Created a container and added items to the container.
  - Create a virtual network
  - Allow access to the cosmos41230322 Azure Cosmos DB account from the App subnet in the AppVNet virtual network and from **your current IP address**.
  - Assign the **Cosmos DB Account Reader Role** to User1-41230322 for the cosmos41230322 Azure Cosmos DB account.
  - I have created a virtual network named AppVNet.
  - I created a subnet named App in the AppVNet virtual network.
  - I enabled a service endpoint for Microsoft.AzureCosmosDB for the App subnet.
  - I assigned the Cosmos DB Account Reader Role to the User1 prefixed user for the Cosmos DB account resource.
- Configured security for the Azure Cosmos DB account.
- Tested access to the Azure Cosmos DB account.

**Lab Topology**

Create an Azure Cosmos DB account by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| API | **Azure Cosmos DB for NoSQL** |
| Resource Group | **corp-datalod41230322** |
| Account Name | cosmos41230322 |
| Location | **(US) East US** |
| Apply Free Tier Discount | **Do Not Apply** |
| Geo-Redundancy | **Disable** |
| Multi-region Writes | **Disable** |

Create a virtual network in the Azure portal by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource Group | **corp-datalod41230322** |
| Name | AppVNet |
| Address space | 10.0.0.0/16 |
| Location | **(US) East US** |
| Subnet | App |
| Starting address | 10.0.10.0 |
| Subnet size | /24 |

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

- - I have learnt how to create an Azure Cosmos DB account and container in a new database
    - I have learnt how to create a new item in the **Customers** container and new SQL query that selects all of the items in the **Customers** container, and then execute the query.
    - I have created a Cosmos DB account with name prefixed by cosmos.
    - I have created a database named Database1 in the Cosmos DB account.
    - I have created a container named Customers in the Database1 database.
    - I have created two items in the Customers container in the Database1 database.
- I have learnt how to create a container and added items to the container.
  - I have learnt how to create a virtual network and allow access to Azure Cosmos DB account from subnet virtual network and access from **your current IP address**.
  - I have learnt how to assign the **Cosmos DB Account Reader Role** to Azure Cosmos DB account.
  - I have created a virtual network named AppVNet.
  - I created a subnet named App in the AppVNet virtual network.
  - I enabled a service endpoint for Microsoft.AzureCosmosDB for the App subnet.
  - I assigned the Cosmos DB Account Reader Role to the User1 prefixed user for the Cosmos DB account resource.
- I have learnt how to configured security for the Azure Cosmos DB account and test access to the Azure Cosmos DB account.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/51207cfa2c954010b0e19345157eb902?sid=a889025b-0c6c-45fe-94c7-8e1323ace7fe**](https://www.loom.com/share/51207cfa2c954010b0e19345157eb902?sid=a889025b-0c6c-45fe-94c7-8e1323ace7fe)