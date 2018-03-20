# IBM Cloudant to Db2 tutorials using Apache Spark™ in Data Science Experience

**The example tutorials in this directory have moved [here](https://github.com/cloudant-labs/data-flow-examples/tree/master/spark-on-watson-studio). Please see the [data-flow-examples](https://github.com/cloudant-labs/data-flow-examples) repository for additional tutorials using various technologies to extract data from IBM Cloudant and write the data to IBM Db2 Warehouse on Cloud.**

**Note:** These examples are only intended as a starting point for loading Cloudant documents into Apache Spark and inserting them into Db2 Warehouse on Cloud. They are not intended as a drop-in replacement for the deprecated Cloudant warehouse integration. In particular these examples do not perform upsert or handle document deletion.

This directory contains the following example tutorials:

- [Scala tutorial for saving 'animaldb' database to Db2 Warehouse on Cloud](animaldb-scala-load-to-dashdb.md)  
An introductory tutorial in Scala for loading Cloudant documents into a Db2 table.
  
- [Python tutorial for saving 'animaldb' database to Db2 Warehouse on Cloud](animaldb-python-load-to-dashdb.md)    
An introductory tutorial in Python for loading Cloudant documents into a Db2 table.

- [Python tutorial for saving filtered 'crimes' Spark DataFrame to Db2 Warehouse on Cloud](crimes-load-to-dashdb-python.md)    
A tutorial in Python for loading Cloudant documents into Apache Spark, and saving a nested JSON object from the documents into a Db2 table.
  
- [Scala tutorial for loading docs and saving filtered 'sales' Spark DataFrame to Db2 on Cloud](sales-continuous-load-cloudant-to-db2.md)    
A tutorial in Scala that leverages Spark Streaming to continuously load Cloudant documents into a Db2 table.
