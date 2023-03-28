Are you ready to hear about an exciting project that I recently worked on? 

### Scenario
I played the role of a Data Engineer hired by a New York-based coffee shop chain looking to expand nationally by opening a number of franchise locations. As part of their expansion process, they wanted to revamp their data infrastructure and streamline their operations.

My role was to design a relational database system that would improve their operational efficiencies and make it easier for their executives to make data-driven decisions. Currently, their data was scattered across different systems such as accounting software, supplier databases, point of sales systems, and even spreadsheets. My job was to bring all of this data together into a centralized database system.

### Steps
I kicked off the project by identifying the entities and attributes in the different data sources. Using PgAdmin 4, I designed a database schema using an Entity-Relationship Diagram (ERD) and applied normalization to the database tables to reduce redundancy. 

![Data entities & attributes](/existing_data.png "Data entities & attributes")


![Entity-Relationship Diagram Design](/task_correction.png "Entity-Relationship Diagram")

Defining relationships between the tables using primary and foreign keys, I then created database objects by generating and running SQL scripts from the ERD tool.

![SQL Script](/generated_sql_script.png "SQL Script")

![Populating Database](/populate_database.png "Populating Database")

One of the most exciting parts of the project was creating views and materialized views that were tailored to the specific needs of external business partners. For example, I created a view in the PostgreSQL database that returned information needed by the external payroll company, which included a list of employees and the locations at which they work. 

![Database Tables](/Task6A.png "Database Tables")


![Sales Details Table](/Task6B.png "Sales Details Table")


![View of Staff Location](/Task7.png "View of Staff Location")


![Materialized View of Product Info](/Task8.png "Materialized View of Product Info")


I exported the results to a CSV file and created a materialized view that returned information needed by a marketing consultant who required access to the product data in their MySQL database for a marketing campaign. I was even able to import the data from a CSV file to their MySQL database using phpMyAdmin.

![Load Data to MySQL database using phpMyAdmin](/Task10.png "Load Data to MySQL database using phpMyAdmin")

Overall, this project was an exciting opportunity to design and implement a comprehensive database system that will enable this coffee shop chain to make data-driven decisions, streamline its operations, and achieve its expansion goals. 
