1. Introduction
This project helps migrate customer data from CSV files to RDBMS for the company Piggybank. In this project, after I create a database for Piggybank, I define the metrics to evaluate the new imported data and create a pipeline to import data to the database. I also create summary reports using the latest data imported.
This project is built following the requirement in the file 'Data engineering case' in the folder 'Requirement'.
2. Folder structure
This package includes folders:
- Requirement: It contains the brief, instruction and requirement for the project.
- Data: It contains 4 raw data files and the file 'CUSTOMER_CAR' which is the merged version of the 4 raw data files. 'CUSTOMER_CAR' is also the result for question 4. In the database, 'CUSTOMER_CAR' is a view and the code to create it can be checked in the database as well as in the SQL script folder (which will be mentioned below).
- Deliverables: It contains the answers, solutions for the case:
	+ Documentation: This is the final outcome for the project.
	+ Piggybank.db: This is the final database after designing and migrating data
	+ Report: This includes 'Data Quality Reporting' PPT file which answers question 3c, the jupyter notebook (whose output is the html file) includes 'Summary report' and 'DPD bucket report' which are the answers for questions 6a and 6b respectively in the case.
- SQL script: It includes all the scripts used to build the database. In that folder, all codes are arranged into 4 sub-folders - only the one 'data clean and table update' are not visible in the Database, the other 3 can be viewed in the database file Piggybank.db.
- Other: This folder includes some pictures, charts inserted into the Documentation.