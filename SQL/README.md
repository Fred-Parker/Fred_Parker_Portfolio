# Azure-Report---Paws-Whiskers
An overview / report on how using Microsoft Azure effectively could benefit the operations of a local petshop.

Data Laws 

Storing customer data is a great way to track business strengths and weaknesses, and can greatly help with in-depth analysis of customer trends and preferences. However, it is vital that any information stored and used about customers is fully compliant with data protection laws and guidelines. At Paws & Whiskers, it is vital that your staff and analysts compiling data are aware of the law surrounding the storage and usage of your customer data. Here are a few key regulations to be aware of: 

 

General Data Protection Regulations (GDPR) EU 1 - When storing data, there are some EU GDPR regulations that must be adhered to. Here are some of the key principles that Paws & Whiskers will be expected to demonstrate knowledge and adherence to: 

 

Lawfulness, Fairness, and Transparency: Ensure that personal data is processed lawfully, fairly, and in a transparent manner. Inform customers about how their data will be used. 

Purpose Limitation: Collect data for specified, explicit, and legitimate purposes and do not process it in a manner that is incompatible with those purposes. 

Data Minimization: Ensure that the data collected is adequate, relevant, and limited to what is necessary for the intended purposes. 

Accuracy: Keep personal data accurate and up to date. Take reasonable steps to ensure that inaccurate data is corrected or deleted without delay. 

Storage Limitation: Retain personal data only for as long as necessary for the purposes for which it was collected. Implement clear retention policies and conduct regular audits. 

Integrity and Confidentiality: Process data in a manner that ensures appropriate security, including protection against unauthorized or unlawful processing, accidental loss, destruction, or damage. 

Accountability: Be able to demonstrate compliance with GDPR principles. Maintain records of data processing activities and implement appropriate technical and organizational measures. 

Data Protection Act (DPA) UK2 – In addition to the EU GDPR laws, there are also additional UK specific laws introduced by the DPA that PAws & Whiskers will need to be aware of and follow:  

National Security and Defence: The DPA 2018 includes specific provisions related to the processing of personal data for national security and defence purposes, which are not explicitly covered by the GDPR. 

Immigration: The DPA 2018 has provisions that allow for the processing of personal data for immigration control purposes, which are not specifically addressed in the GDPR. 

Law Enforcement: The DPA 2018 includes Part 3, which deals with the processing of personal data by competent authorities for law enforcement purposes. This part implements the EU Law Enforcement Directive, which is separate from the GDPR. 

Children's Data: The DPA 2018 sets the age of consent for data processing at 13 years, whereas the GDPR allows member states to set the age between 13 and 16. 

Automated Decision-Making: The DPA 2018 includes additional safeguards and provisions for automated decision-making, including profiling, which are more detailed than those in the GDPR. 

In addiiton to these above regulations there are also some industry-specific recommendations I would like to make for Paws & Whiskers to consider. 

 

Here are some regulations to be aware of and adhere to when processing customer payments by card: 

Payment Card Industry Data Security Standard (PCI DSS): This standard applies to any business that handles credit card information. It sets requirements for securing cardholder data, including encryption, access controls, and regular security testing.3 

Paws & Whiskers will be required to provide clear and accurate information to all customers about how their payments are processed, stored and handled: 

Consumer Protection Regulations: These regulations ensure that businesses provide clear and accurate information to consumers, including details about payment processes and data handling practices. ￼ 

Paws & Whiskers will need to obtain customer consent to store contact details and to use these details in dissemination of any marketing materials it would like to distribute: 

Privacy and Electronic Communications Regulations (PECR): These regulations cover the use of electronic communications, such as email and SMS, and require businesses to obtain consent before sending marketing messages. ￼ 

It is my recommendation that Paws & Whiskers adhere to robust and effective cybersecurity practices to help protect the data that is stored about customers and their payments. Not only will this help protect Paws & Whiskers against cyber-attack, but it will also give peace of mind to any customers who consent to having their details stored and used by Pets & Whiskers: 

Cybersecurity Best Practices: Implementing strong cybersecurity measures, such as encryption, firewalls, and regular security audits, is essential to protect sensitive and payment information from unauthorized access and breaches. 

Azure Service Recommendations 

 

There are a few core Azure services I would recommend to Pets & Whiskers based on their specific requirements and planned usage for their data. 

 

Data Storage Options: 

 

Azure Blob Storage - By leveraging Azure Blob Storage, the pet shop can efficiently manage and store their data, ensuring that it is secure, accessible, and cost-effective. Here are some benefits of using Azure Blob Storage: 

Scalability: Azure Blob Storage can handle large volumes of unstructured data, making it ideal for storing various types of data such as customer information, inventory records, and transaction logs. 

Cost-Effective: It offers multiple storage tiers (Hot, Cool, and Archive) that allow you to optimize costs based on how frequently you need to access the data. 

Security: Azure Blob Storage provides robust security features, including encryption at rest and in transit, role-based access control (RBAC), and shared access signatures (SAS) to ensure that your data is protected. 

High Availability and Durability: With built-in redundancy and disaster recovery capabilities, Azure Blob Storage ensures that your data is always available and protected against data loss. 

Integration with Other Azure Services: It seamlessly integrates with other Azure services such as Azure Data Lake Storage, Azure Databricks, and Azure Stream Analytics, enabling you to build comprehensive data solutions. 

Flexibility: Azure Blob Storage supports various data types, including text, images, videos, and backups, making it versatile for different use cases in a pet shop. 

Azure SQL Database - By leveraging Azure SQL Database, the pet shop can ensure its customer data is stored securely, accessed quickly, and managed efficiently. Here are some benefits of using Azure SQL DB as data storage: 

 

Scalability: Whether the pet shop is small or has a large clientele, Azure SQL Database scales easily to meet Paws & Whiskers needs. They can start small and grow without worrying about capacity limits. 

Security: Microsoft provides advanced security features, including encryption, data masking, and threat detection, to help keep customer data safe and comply with regulations like GDPR. 

Performance: Azure SQL Database is built on a powerful infrastructure that ensures high performance for the necessary queries and transactions. 

Reliability: With built-in high availability and disaster recovery options, Azure SQL Database would ensure the data is always accessible, minimizing the risk of downtime. 

Cost-Efficiency: You pay for what you use, which can be cost-effective. Plus, it eliminates the need for maintaining physical servers. 

Integration: Seamlessly integrates with other Azure services and tools, making it easier to build a comprehensive ecosystem for the business needs, including data analytics and reporting. 

Data Analysis Tools: There are a couple of reliable and beneficial data analysis tools that I recommend Paws & Whiskers consider including in their exploration of Azure. 

Azure Machine Learning – This could easily automate analysis of customer purchase patterns and identify trends and popularity across all the products Pets & Whiskers offers. It could also help with monitoring inventory, and forecasting purchases, to help always keep popular products in stock with less human-effort needed to monitor stock-levels. It could also assist with compiling and anlaysing customer feedback, product recommendations, and pricing optimisations. 

 

Azure Synapse Analytics – Azure Synapse Analytics could help to unify data insights from various sources such as sales, inventory, and customer interactions, to provide actionable insights to support better business decision making.  

 

Data Integration and Automation:  

 

Azure Data Factory – This could help to automate the input and storage of data, which historically has been done manually by Paws & Whiskers staff, allowing for a more efficient process of data ingesting and orchestration. 

 

Data Types & Data Modelling 

 

Data Categories – Paws & Whiskers will be working with a variety of different data types to help facilitate thorough and accurate data storage, analysis, and forecasting. These data types include customer details (demographic, purchases, transaction history etc), purchase details (cost of items, amount of items sold, drillable data to show purchasing history and trends), stock data (items in stock, number of items kept, minimum desirable stock-levels, cost of each item, and where the item is ordered from). 

 

Data Modelling Approach – To reliably model this data that Paws & Whiskers will be tracking and storing, it is vital that we would plan a robust and effective approach to modelling this data. Here is an approach to modelling the data that includes both a relational model and a data warehouse approach:  
 
Relational Model -  

Entities and Tables: 

Customers: 

CustomerID (Primary Key) 

FirstName 

LastName 

Email 

PhoneNumber 

Address 

Pets: 

PetID (Primary Key) 

Name 

Species 

Breed 

DateOfBirth 

CustomerID (Foreign Key) 

Products: 

ProductID (Primary Key) 

ProductName 

Category 

Price 

StockQuantity 

Sales: 

SaleID (Primary Key) 

CustomerID (Foreign Key) 

SaleDate 

TotalAmount 

SaleDetails: 

SaleDetailID (Primary Key) 

SaleID (Foreign Key) 

ProductID (Foreign Key) 

Quantity 

UnitPrice 

Relationships: 

Each Customer can have multiple Pets, forming a one-to-many relationship. 

Each Sale is linked to a Customer, forming a many-to-one relationship. 

Each Sale can have multiple Products through SaleDetails, forming a many-to-many relationship via a junction table. 

Data Warehouse Approach -  

Fact and Dimension Tables: 

FactSales: 

SaleID (Primary Key) 

CustomerID 

ProductID 

SaleDate 

Quantity 

TotalAmount 

DimCustomers: 

CustomerID (Primary Key) 

FirstName 

LastName 

Email 

PhoneNumber 

Address 

DimPets: 

PetID (Primary Key) 

Name 

Species 

Breed 

DateOfBirth 

CustomerID 

DimProducts: 

ProductID (Primary Key) 

ProductName 

Category 

Price 

DimDate: 

DateKey (Primary Key) 

Date 

Day 

Month 

Year 

Quarter 

Relationships: 

The FactSales table holds transactional data and links to the dimension tables (DimCustomers, DimPets, DimProducts, DimDate) via foreign keys, forming a star schema. 

This structure ensures that the relational model is optimised for transactional operations, while the data warehouse model is optimised for reporting and analytics, supporting different needs at Paws & Whiskers. 

 

Data Storage Formats & Structures in Azure 

 

Data Formats – When storing the data at Paws & Whiskers there are a few different data types that would prove suitable for the different types of data being stored. Raw data could be stored as a CSV (Comma Separated Values) format, which would make plain text files easy to read, and edit using any text editor. Structured data could be stored in a JSON (Javascript Object Notation) format, which would be a useful way of storing large quantities of key:value data such as customer information. Parquet format would be a good option for data that we want to analyse – data stored in a column format optimises read and write efficiency for analytical queries. It would also be able to be compressed to a smaller file ratio compared to CSV files, making it both cheaper to store and quicker to transfer. 

 

Data Security and Encryption – Azure has several built-in encryption features that would prove effective as options for securing the data Paws & Whiskers stores and using access controls to protect data will also help business compliance with the previously outlined data-privacy regulations. Here are some of the options I will recommend Paws & Whiskers consider, including encryption of data both in transit and at rest: 

 

Encryption at Rest: 

Azure Storage Service Encryption (SSE): Automatically encrypts data stored in Azure Storage (blobs, files, queues, and tables) using 256-bit AES encryption. 

Azure Disk Encryption (ADE): Encrypts OS and data disks of Azure Virtual Machines using BitLocker for Windows and DM-Crypt for Linux. 

Encryption at Host: Ensures that all data stored on the host, including temp disks and caches, is encrypted. 

Encryption in Transit: 

TLS/SSL: Azure uses Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols to encrypt data as it travels between clients and Azure services. 

 

Additional Considerations 

 

Finally, here are some additional things I recommend Paws & Whiskers consider when using Azure to boost their data handling effiency and analysis. 

 

Backup and Disaster Recovery – Using Azure Backup and Azure Site Recovery you can reliably safeguard against data loss. This helps to protect data against loss or damage and helps ensure overall business continuity and consistency. 

 

Data Visualisation – Using Azure’s built-in PowerBI support and functionality is a great tool to consider for generating and analysing in-depth visualisations on the data that Paws & Whiskers will be storing. Integrating Power BI with Azure services such Azure Stream Analytics and Azure Event Hubs would allow the business to create real-time dashboards that display data as frequently updated as they could want – Paws & Whiskers could monitor sales performances and customer transactions and feedback as they happen live. 

 

Future Scalability – Finally, using Azure effectively would help Paws & Whiskers to scale their databases and analysis platforms as the business and its analytical needs grow. Azure is well suited to handling large-data sets, and storage is fully scalable to business's needs. Azure Databricks and Azure Synapse analytics enable complex analysis of large datasets. A flexible pricing model ensures that you are always paying for exactly what your business needs and no more. 
