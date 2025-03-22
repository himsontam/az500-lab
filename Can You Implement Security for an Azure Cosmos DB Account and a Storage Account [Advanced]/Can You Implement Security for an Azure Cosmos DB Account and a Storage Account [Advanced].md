**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Can You Implement Security for an Azure Cosmos DB Account and a Storage Account \[Advanced\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created an Azure Cosmos DB account.
  - Create an Azure Cosmos DB account
  - Allow requests from your current IP address
  - Create a container in a new database
  - Create a new item in the **Customers** container
  - Execute a new SQL query that selects all of the items in the **Customers** container,
  - I have created an Azure Cosmos DB account.
  - i have created a database named Database1 in the Azure Cosmos DB account.
  - I have created a container named Customers in Database1.
- Created a storage account.
  - Create a storage account
- Generated an SAS key for the storage account.
  - Create a container named images
  - Upload any image file on your computer to the **images** container as a **64 KB** block blob by using an authentication type of **Account key** and the **Hot (Inferred)** access tier.
  - Generate a SAS key for the blob file
  - I have created a storage account.
  - I have created a container named images in the storage account.
- Assigned a role to a user for the Azure Cosmos DB account.
  - Assign the Cosmos DB Account Reader Role to User1-41230659 for the cosmos41230659 Cosmos DB account.
  - Create a new SQL query that selects all of the items in the **Customers** container in the **Database1** database in the **cosmos41230659** account.
- Attempt to create a new item in the **Customers** container by using the following JSON code:
- {
- "firstName": "Harry",
- "lastName": "Oneal",
- "company": "Veraq"

}

The operation should fail with an _The input authorization token can't serve the request_ error message because the user has read-only access.

- - I have assigned the Cosmos DB Account Reader Role to User1 for the Azure Cosmos DB account.

**Lab Topology**

Create an Azure Cosmos DB account by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| API | **Azure Cosmos DB for NoSQL** |
| Resource Group | **corp-datalod41230659** |
| Account Name | cosmos41230659 |
| Location | **(US) East US** |
| Apply Free Tier Discount | **Do Not Apply** |
| Geo-Redundancy | **Disable** |
| Multi-region Writes | **Disable** |

Create a container in a new database in the cosmos41230659 account by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Database id | Database1 |
| Container id | Customers |
| Partition key | /\_partitionKey |
| Throughput | **Manual** |
| Container throughput | 500 |

Create a storage account by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230659** |
| Storage account name | sa41230659 |
| Region | **(US) East US** |
| Performance | **Standard** |
| Redundancy | **Geo-redundant storage (GRS)** |
| Allow Blob public access | **Enabled** |

Generate a SAS key for the blob file that you uploaded by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Signing method | **Account key** |
| Signing key | **Key 1** |
| Permissions | **Read** |
| Start | The current date at 12:00:00 AM |
| Expiry | Tomorrow's date at 12:00:00 AM |
| Allowed protocols | **HTTPS only** |

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

- - I have learnt how to create an Azure Cosmos DB account, and allow requests from your current IP address
    - I have how to create a container in a new database and create a new item in the **Customers** container
    - I have learnt how to execute a new SQL query that selects all of the items in the **Customers** container,
    - I have created an Azure Cosmos DB account.
    - i have created a database named Database1 in the Azure Cosmos DB account.
    - I have created a container named Customers in Database1.
- I have learnt how to create a storage account.
- I have learnt how to generate an SAS key for the storage account.
  - I have created a storage account.
  - I have created a container named images in the storage account.
- I have learnt how to assigned a role to a user for the Azure Cosmos DB account.
  - I have assigned the Cosmos DB Account Reader Role to User1 for the Azure Cosmos DB account.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/d1046a8e0f56408385962faf94dbc232?sid=ac0e238a-2d7d-4b42-bc8b-9a8ccb95630f**](https://www.loom.com/share/d1046a8e0f56408385962faf94dbc232?sid=ac0e238a-2d7d-4b42-bc8b-9a8ccb95630f)