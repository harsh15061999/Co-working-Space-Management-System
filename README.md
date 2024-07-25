# Co-working-Space-Management-System

Database-Project: Co-working-Space-Management-System

Problem Statement

The principal objective of this study was to design and execute a relational database and write queries on the implemented database. The goal of this project is to build a Coworking Space Management system for ‘SmartSpaces,’ an upcoming provider of coworking spaces aiming to expand across Boston, Massachusetts.

Design Approach

The first step in implementing the database was to generate the data according to the requirements. Mockaroo was used to populate data. Additionally, the data was manually refined in Excel to fine-tune the format required by MySQL. The generated data was stored in a CSV file. Using DDL commands, we created the database named 'coworking’ and their respective tables. Datatypes for each column, Foreign key, Primary key, and Not Null constraints were specified while creating a table. I used the Import csv option to upload the data to the respective tables. 

The database was further refined on a few columns of the ‘Invoice’ table, such as ‘SpaceCost’ and ‘ServiceCost’ based on the update statements using the ‘PerSeatCost’ and ‘SeatsBooked.’ The created database ‘coworking’ was connected to Python in Jupyter Notebook, and few analytics were depicted, giving insights into how ‘SmartSpaces’ can expand their services across Boston. Few metrics like ‘Recurring Users’, Capacity of Neighborhoods and revenue generated can assist in understanding the locations where the organization should focus on building their services. 
