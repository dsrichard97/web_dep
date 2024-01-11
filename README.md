# Database Mock Up
### Why a database Management system? 
A database management system (DBMS) is a software tool that allows users to manage a database. Users can use DBMSs to access and interact with the underlying data in a database. This can include actions like querying data and defining database schemas. 

Some examples: 
- user can access most of the data
- database adminstrators can configure settings

![alt text](https://github.com/dsrichard97/web_dep/blob/main/dbms-image-1.png "Database Uses")



## Python Configuration 
As a result since python is fast and can help us create a mock up random data sample to create our website. We will use python to create a random data for at least 500 memberships. The goal will be to export most of our data into a web page to mimic the similarity to a database. Due to privacy and data security it would be more difficult to include "real data" gathered from people. So this mocked up database shoudl mimic some high level simialrity functions. This project does not focus on Alteryx or SAP tools but rather a high level insight on mimicking ticketing system. Furthermore, python is a great tool to conigure random datasets. Libraries to consider: faker and random. 
- For info on Faker library: https://faker.readthedocs.io/en/master/
- For info on random library: https://docs.python.org/3/library/random.html

Here is a quick sample of the process. Due to security reasons I can not show the entiretity of the code. 
![alt text](https://github.com/dsrichard97/web_dep/blob/main/pythongif.gif "Python Connecting to Google BigQuery")

## Google BigQuery Databases
Google BigQuery allows users to store information on the cloud. As a result, the conversion of data is then pipelined to tables. These tables can then be pulled using SQL queries or creating an API engine. For more information please visit: https://cloud.google.com/bigquery/docs/share-access-views  .

From connecting python code we have the following tables 

### Appointments
![alt text](https://github.com/dsrichard97/web_dep/blob/main/appt.png "Appointments")
For sample data: https://github.com/dsrichard97/web_dep/blob/main/appointments_sampledata.csv

### Personal Information
![alt text](https://github.com/dsrichard97/web_dep/blob/main/personal_info.png "Personal Information")
For sample data: https://github.com/dsrichard97/web_dep/blob/main/personal_info_sampledata.csv

### Medical Records
![alt text](https://github.com/dsrichard97/web_dep/blob/main/medical_records.png "Medical Records")
For sample data: https://github.com/dsrichard97/web_dep/blob/main/medicalrecords_sampledata.csv

## Deployment onto WebPage
