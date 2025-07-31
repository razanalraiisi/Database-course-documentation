## Database Course Documentation

#### 1.Comparison Assignment: Flat File Systems vs. Relational Databases.

![Flat File Systems vs. Relational Databases](images/Relational-Database-vs-Flat-File.jpg)

Flat file systems and relational databases both serves the purpose of storing information, but they do so in very different ways.
##### Structure:
  Flat file systems resemble spreadsheets, where data is stored in a single table made up of rows and columns. Each row represents a record, and each column holds specific data fields like name, address, or phone number.
  In contrast, relational databases use multiple interconnected tables. Each table focuses on a specific type of data, example: customers, products, orders, they are linked using unique identifiers such as customer ID or product ID. This design supports better organization and scalability.


##### Data Redundancy:
  Flat files often duplicate data across rows since they store all information in one place without referencing. This leads to data repetition and potential inconsistencies. 
  On the other hand, relational databases minimize redundancy by separating data into related tables and referencing shared values. This ensures data is stored efficiently and remains consistent across the system.


##### Relationships:
  Flat files lack built-in support for relationships between data entries, making it difficult to cross-reference or combine related data. Relational databases are designed to handle relationships between tables using keys.
  For example using foreign keys, an order can link to a customer and a product through their respective IDs, allowing for complex queries across datasets.


##### Example Usage:
  Flat file systems are suitable for smaller applications like contact lists or simple inventory records in a small store. Their simplicity makes them easy to use without much technical knowledge.
  In contrast, relational databases are ideal for large scale or expanding businesses such as LBM (Lumber and Building Materials) dealers with multiple branches. These databases allow centralized storage of customer, order, and product data, which can be efficiently queried and compared across locations.


##### Drawbacks:
  Flat file systems and relational databases both have drawbacks, especially when dealing with large or complex datasets. Flat file systems can become difficult to manage once you have more than a few thousand records.
  They are harder to update, may contain non-unique records, have a higher risk of data duplication, and often become inefficient over time. Additionally, they struggle with maintaining consistency, leading to data redundancy and potential errors.
  On the other hand, relational databases, while more powerful and efficient, come with their own challenges. They are more complex to design and manage, requiring technical expertise to set up relationships and ensure data integrity. They may also require specialized software and resources, which can be a limitation for small-scale or temporary data storage needs.

#### 2. DBMS Advantages
![DBMS Advantages](images/DBMS%20Advantages%20Mind%20map.png)

#### 3. Roles in a Database System
A **Database Administrator (DBA)** manages and maintains database systems to ensure data security, performance, and compliance. DBAs work across various industries like tech, finance, and education, handling tasks such as:
- Installing, configuring, and monitoring databases.

- Enforcing standards, policies, and security measures.

- Supporting database design and testing.

- Performing backups, tuning, and updates.

- Monitoring usage, performance, and concurrency.

A **Systems Analyst** evaluates an organization’s existing IT systems and designs improvements to meet business objectives. They gather requirements from stakeholders,
analyze system needs, and create detailed specifications including data models and workflows. They guide system design and implementation, ensuring new systems are efficient and meet user needs.

A **Database Designer** defines the structure and organization of data. They identify entities, relationships, and attributes, crafting conceptual, logical, and physical data models. They determine normalization,
indexing, partitioning, and schemas to optimize storage and performance. 

A **Database Developer** builds and maintains the database infrastructure. They write SQL, develop stored procedures, design ETL processes, and optimize performance. They collaborate with BI teams to support analytics and ensure the database meets application and reporting needs.

An **Application Developer** creates software applications that interact with the database. While not always a database expert, they integrate front-end or back-end code to query and manipulate data. Their work closely ties to database functionality, especially in smaller teams.

A **BI Developer** designs and implements data solutions to support business analytics. They build ETL pipelines, data models, dashboards, and reports using BI tools. They transform raw data into insightful information, ensuring security and compliance in BI systems.