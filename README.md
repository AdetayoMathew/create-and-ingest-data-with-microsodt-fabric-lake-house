# create-and-ingest-data-with-microsodt-fabric-lake-house
# BACKGROUND 
Large-scale data analytics solutions have traditionally been built around a data warehouse, in which data is stored in relational tables and queried using SQL. The growth in “big data” (characterized by high volumes, variety, and velocity of new data assets) together with the availability of low-cost storage and cloud-scale distributed compute technologies has led to an alternative approach to analytical data storage; the data lake. In a data lake, data is stored as files without imposing a fixed schema for storage. Increasingly, data engineers and analysts seek to benefit from the best features of both of these approaches by combining them in a data lakehouse; in which data is stored in files in a data lake and a relational schema is applied to them as a metadata layer so that they can be queried using traditional SQL semantics.

In Microsoft Fabric, a lakehouse provides highly scalable file storage in a OneLake store (built on Azure Data Lake Store Gen2) with a metastore for relational objects such as tables and views based on the open source Delta Lake table format. Delta Lake enables you to define a schema of tables in your lakehouse that you can query using SQL.
# PROCESS
1. Created a new workspace
2. ![Screenshot (554)](https://github.com/Mathex7/create-and-ingest-data-with-microsodt-fabric-lake-house/assets/106633060/6b98e6cf-5007-48b4-a9a6-179105f7d51c)

3. Created  a lakehouse Switching to the data engineering experience
4. ![Screenshot (556)](https://github.com/Mathex7/create-and-ingest-data-with-microsodt-fabric-lake-house/assets/106633060/ccef95db-f49e-43ed-9ba6-231d844953ae)

5. Uploaded my data. this data was gotten from https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/sales.csv
6. Created a  shortcut to quickly pull data from internal and external locations into my  datasets. Shortcuts can be updated or removed from your item, but these changes will not affect the original data and its source.
7. 
