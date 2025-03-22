**Practical Work Experience and Portfolio Building**

**Evidence Reporting Document**

- **Introduction**

_The main goal of this document is to keep track of the practical hands-on work experience and lab challenges you will complete throughout the program. By doing so, at the end of the program, you will have a great portfolio that you can use for evidence of your practical skills, and you can also come back for review whenever needed. This evidence is essential in the long run and keeps you on track with the time you will spend on your career upgrade process. These notes will also play a vital role in identifying the skills and tools to reflect on your marketing materials like your CV/resume or LinkedIn Page._

- **General Details**

**Date: 17 May 2024**

**Your Name: LOK HIM TAM (Himson)**

**Email-address:** <lokhimtamhimson@gmail.com>

**Name of the Challenge:** Can You Enable Security for an Azure SQL Database \[Advanced\]

**Access Details (URL or source):** AZ500

**Details of the Challenge:**

In this lab I have working following exercise:

- Created an Azure SQL database.
  - Create an Azure SQL database
  - Log in to the **db41230724** database as AzureAdmin using AzPwd41230724! as the password, and then create a query to retrieve all of the rows in the SalesLT.Customer table
  - I have created an Azure SQL database with name prefixed by db.
  - i have created a new logical SQL server with name prefixed by sql.
  - I have created a Server admin login named AzureAdmin for the logical SQL server.
  - i have allowed Azure services and resources to access the logical SQL server.
  - i have copied the correct number of Affected rows from the query.
- Enabled Microsoft Defender for SQL.
  - Enable Microsoft Defender for SQL for the **db41230724** database.
  - I have enabled Microsoft Defender for SQL.
- Performed a vulnerability assessment.
  - Perform a vulnerability assessment for the **db41230724** database.
  - I have performed a vulnerability assessment.
- Enabled database auditing.
  - Create a storage account
  - Enable database auditing on the **db41230724** database, and then store the audit log in the **sa41230724** storage account.
  - Attempt to drop the SalesLT.Customer table by using the [DROP TABLE](https://docs.microsoft.com/en-us/sql/t-sql/statements/drop-table-transact-sql) statement, and then review the error message.
    - see the following error message: **Failed to execute query. Error: Could not drop object 'SalesLT.Customer' because it is referenced by a FOREIGN KEY constraint.**
  - Review the audit log for the **db41230724** database, and then review the audit record of the **failed** DROP TABLE statement.
- I have created a storage account with name prefixed by sa.
- i have enabled database auditing.

**Lab Topology**

Create an Azure SQL database on a new logical SQL server by using the values in the following table. For any property that is not specified, use the default value.

| **Property** | **Value** |
| --- | --- |
| Resource group | **corp-datalod41230724** |
| Database name | db41230724 |
| Server name | sql41230724 |
| Authentication method | **Use SQL authentication** |
| Server admin login | AzureAdmin |
| Password | AzPwd41230724! |
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

- - I have learnt how to create an Azure SQL database, and then create a query to retrieve all of the rows in the SalesLT.Customer table
        - I have created an Azure SQL database with name prefixed by db.
        - i have created a new logical SQL server with name prefixed by sql.
        - I have created a Server admin login named AzureAdmin for the logical SQL server.
        - i have allowed Azure services and resources to access the logical SQL server.
        - i have copied the correct number of Affected rows from the query.
- I have learnt how to enable Microsoft Defender for SQL.
  - I have enabled Microsoft Defender for SQL.
  - I have learnt how to performed a vulnerability assessment for database.
    - I have performed a vulnerability assessment.
  - I have learnt how to enable database auditing on database, and then store the audit log in the storage account.
  - I have created a storage account with name prefixed by sa.
  - i have enabled database auditing.

1. Prepare a self-reflection and reporting video using any screen recording tool (like Loom) and share the link.

_(The report may include but is not limited to your thoughts about the problem solved, difficulties encountered, any notes to discuss with your peers, anything to ask the mentors and last but not least how it may help you in your ideal job. Please prepare the summary in a way that you are presenting this to your managers and colleagues in your ideal workplace)_

**URL:**

[**https://www.loom.com/share/4826b2f7f4244a16bfbd184bcbcc2981?sid=d4c22a83-bff5-4a35-81e8-b32f312a457b**](https://www.loom.com/share/4826b2f7f4244a16bfbd184bcbcc2981?sid=d4c22a83-bff5-4a35-81e8-b32f312a457b)