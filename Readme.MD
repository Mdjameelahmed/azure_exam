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
- **What is Azure Trust Center** -The Trust Center is an important part of the Microsoft Trusted Cloud Initiative and provides support and resources for the legal and compliance community. The Trust Center provides: In-depth information about security, privacy, compliance offerings, policies, features, and practices across Microsoft cloud products.
- Your company plans to migrate all on-premises data to Azure. You need to identify whether Azure complies with the company's regional requirements. What should you use? **ANS**  The Trust Center.
- **Azure Knowledge center** - The Azure Knowledge Center is a searchable database that contains answers to common support questions, from a community of Azure experts.
- **Azure portal** - console of azure
- **Azure marketplace** - Azure Marketplace is an online store that contains thousands of IT software applications and services built by industry-leading technology companies. In Azure Marketplace you can find, try, buy, and deploy the software and services you need to build new solutions and manage your cloud infrastructure.
- **Azure Event Hubs** - Azure Event Hubs is a big data streaming platform and event ingestion service. It can receive and process millions of events per second. Data sent to an event hub can be transformed and stored by using any real-time analytics provider or batching/storage adapters.
Azure Event Hubs can be used to ingest, buffer, store, and process your stream in real time to get actionable insights. Event Hubs uses a partitioned consumer model, enabling multiple applications to process the stream concurrently and letting you control the speed of processing.
Azure Event Hubs can be used to capture your data in near-real time in an Azure Blob storage or Azure Data Lake Storageג€‰for long-term retention or micro-batch processing.
- Which Azure service should you use to collect events from multiple resources into a centralized repository? **ANS** Azure Event Hubs
- **Azure monitor** - cloudwatch of azure
- **Azure Analysis Services** Azure Analysis Services is a fully managed platform as a service (PaaS) that provides enterprise-grade data models in the cloud. Use advanced mashup and modeling features to combine data from multiple data sources, define metrics, and secure your data in a single, trusted tabular semantic data mode
- **Azure Stream Analytics** Azure Stream Analytics is a fully managed, serverless engine by Microsoft for real-time analytics. It offers the possibility to perform real-time analytics on multiple streams of data from sources such as sensors, web data sources, social media and other applications.
- **Azure stream analytics vs Azure Analysis Services vs data warehouse** -
upcoming

- **azure databricks** is an apache spark-based analytics service
- **Azure Databricks** is a fast, easy, and collaborative Apache Spark-based analytics service. For a big data pipeline, the data (raw or structured) is ingested into Azure through Azure Data Factory in batches, or streamed near real-time using Kafka, Event Hub, or IoT Hub.
- **Azure data factory** - Azure Data Factory is a Microsoft cloud service offered by the Azure platform that allows data integration from many different sources. 
- **Azure HDinsight** - Azure HDInsight is a managed Apache Hadoop service that lets you run Apache Spark, Apache Hive, Apache Kafka, Apache HBase, and more in the cloud.
- azure key vault is used to store secrets for - Servers applications
- If a resource group named RG1 has a delete lock, then to delete this by administrator also at first The delete lock must be removed before an administrator. Because This lock is applicable for everyone
- **About Resource lock -**
1) You can set locks that prevent either deletions or modifications. In the portal, these locks are called Delete and Read-only. In the command line, these locks are called CanNotDelete or ReadOnly. In the left navigation panel, the subscription lock feature's name is Resource locks, while the resource group lock feature's name is Locks.

2) CanNotDelete means authorized users can read and modify a resource, but they can't delete it.
3) ReadOnly means authorized users can read a resource, but they can't delete or update it. Applying this lock is similar to restricting all authorized users to the permissions that the Reader role provides.
- **DDOS Protection**- DDoS Protection enables you to protect your Azure resources from denial of service (DoS) attacks with always-on monitoring and automatic network attack mitigation. There is no upfront commitment and your total cost scales with your cloud deployment.
- **Azure Traffic Manager** is a DNS-based traffic load balancer. This service allows you to distribute traffic to your public facing applications across the global Azure regions. Traffic Manager also provides your public endpoints with high availability and quick responsiveness.
- Which two types of customers are eligible to use Azure Government to develop a cloud solution? Each correct answer presents a complete solution. **ANS** - A United States government entity. && A United States government contractor.
- which azure service should you use **ANS** - Azure AD identity protection
- Resource groups provide organizations with the ability to manage the compliance of Azure resources across multiple subscriptions. **Ans** Azure policies
- From AZURE MONITOR , you can view which user turned off a specific virtual machine during the last 14 days. **ANS** Azure Activity Log.
- **Azure Firewall** - control traffic to multiple vm
- Documents and email messages are protected by - **Azure information Protection**
- Used to add automatic watermark by - **Azure information Protection**
- What should you use to evaluate whether your company's Azure environment meets regulatory requirements? **Ans** - The Security Center blade from the Azure portal.
- you can track your company's regulatory standards and regulations, such as ISO 27001. by **ans** - Compliance Manager
- Your company has an Azure environment that contains resources in several regions.

- A company policy states that administrators must only be allowed to create additional Azure resources in a region in the country where their office is located. You need to create the Azure resource that must be used to meet the policy requirement. What should you create? **Ans** An Azure policy.
- **Azure AD connect health** -
- **Azurre AD identity protection** -
- **Azure AD Previleged Identity management** -
- **Azure advance threat protection** -
- The **Microsoft Online Services Privacy Statement** explains what data Microsoft processes, how Microsoft processes the data, and the purpose of processing the data.
- You have several virtual machines in an Azure subscription. You create a new subscription. *** THE VIRTUAL MACHINES CANNOT BE MOVED TO THE NEW SUBSCRIPTION *** **Ans** The virtual machines can be moved to the new subscription.
- Your company has 10 offices. You plan to generate several billing reports from the Azure portal. Each report will contain the Azure resource utilization of each office. Which Azure Resource Manager feature should you use before you generate the reports? **Ans** Tags
- Your company plans to migrate to Azure. The company has several departments. All the Azure resources used by each department will be managed by a department administrator. What are two possible techniques to segment Azure for the departments? Each correct answer presents a complete solution. **Ans**  multiple resource groups and multiple subscriptions
- Azure subscription is just like a container
- If Microsoft plans to end support for an Azure service that does NOT have a successor service, Microsoft will provide notification at least **12 months before**.
- You are not charged for **unused network interfaces.**
- You are charged for **public ip addresses**
- You are not charged for **unused user account and groups**
- A support plan solution that gives you best practice information, health status and notifications, and 24/7 access to billing information at the lowest possible cost is a Standard support plan. **Ans** basic
- https://azure.microsoft.com/en-us/support/plans/
- In which Azure support plans can you open a new support request? You can open support cases in the following plans: Premier, Professional Direct, Standard, and Developer only. You cannot open support cases in the Basic support plan.
- You can create an Azure support request from **support.microsoft.com.** - azure portal
- What is guaranteed in an Azure Service Level Agreement (SLA) for virtual machines? **Ans** Uptime (availability zone 99.99% availability set 99.95%)
- The Basic support plan does not have any technical support for engineers.
- The Developer support plan has only technical support for engineers via email.
- The Standard, Professional Direct, and Premier support plans have technical support for engineers via email and phone. 
- Your company plans to request an architectural review of an Azure environment from Microsoft. Which support plan should you recommend? **Ans** Premier.
- What-is-required-to-use-Azure-Cost-Management? **ANS** an enterprise aggrement (EA)
- Your Azure trial account expired last week. You are now unable to *** CREATE ADDITIONAL AZURE ACTIVE DIRECTORY (AZURE AD) USER ACCOUNTS. **ANS** Start an existing vm ( you can create ADDITIONAL AZURE ACTIVE DIRECTORY (AZURE AD) USER ACCOUNTS because it is free )
- **Azure Subscription** -
- we cant install azure cli on iphone

