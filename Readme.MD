- Azure storage is a IAAS
- **Microsoft power BI -** Power BI is a collection of software services, apps, and connectors that work together to turn your unrelated sources of data into coherent, visually immersive, and interactive insights. Your data may be an Excel spreadsheet, or a collection of cloud-based and on-premises hybrid data warehouses.
- **Azure Data Lake** A Data Lake is a storage repository that can store a large amount of structured, semi-structured, and unstructured data. It is a place to store every type of data in its native format with no fixed limits on account size or file. It offers a large amount of data quantity for increased analytical performance and native integration.
Data Lake is like a large container which is very similar to real lake and rivers. Just like in a lake, you have multiple tributaries coming in; similarly, a data lake has structured data, unstructured data, machine to machine, logs flowing through in real-time.
- **Difference between Azure Data Lake and blob storage** - 
1) Azure Data Lake Store Gen2 is a superset of Azure Blob storage capabilities. In the list below, some of the key differences between ADLS Gen2 and Blob storage are summarized.
2) ADLS Gen2 supports ACL and POSIX permissions allowing for more granular access control compared to Blob storage.
3) ADLS Gen2 introduces a hierarchical namespace. This is a true file system, unlike Blob Storage which has a flat namespace. This capability has a significant impact on performance, especially in big data analytics scenarios.
4) ADLS Gen2 is an HDFS-compatible store. This means that Apache Hadoop services can use data stored in ADLS Gen2. Azure Blob storage is not Hadoop-compatible.
- **Waewhouse** - Store rooms
- **Data Warehouse** - It collect data from many normal database, intregate them, then do analysis on them, export a report.
- **diff between normal databse and Data Warehouse** - Normal database just store data and it has faster input. Data warehouse strore data for analytical purpose.
- **Data Lake vs Data Warehouse** - Data lakes and data warehouses are both widely used for storing big data, but they are not interchangeable terms. A data lake is a vast pool of raw data, the purpose for which is not yet defined. A data warehouse is a repository for structured, filtered data that has already been processed for a specific purpose. 
- **azure cosmodb-** We can say that cosmodb is a autoscale database. It creates seceondary read databases in another regions and whenever some data come into actual db then it replicate it to all secondary read db. Dont compare it with CDN because cosmo db gives you the live data of main db from secondary db.
- You need to identify the type of failure for which an Azure Availability Zone can be used to protect access to Azure services.
What should you identify? **ANS**  an Azure data center failure
- When you need to delegate permissions to several Azure virtual machines simultaneously you must deploy the virtual machines? **ANS** To the same resource group
- 
