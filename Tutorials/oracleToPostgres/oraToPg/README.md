# Azure DMS: Oracle to Azure PostgreSQL



### **Scenario Details:** <br />
* Create an on-premise Oracle database through an **Azure Windows 2019 Server VM** with an Oracle image (*12.2.0.1.0 Enterprise Edition*) installed.
* Assess **tables and objects** that user wants to migrate to the created **Azure PostgreSQL Database**. 
* Then migrate the schema from the **Oracle Database** to the **Azure PostgreSQL Database**.
* After this set up **Azure DMS** by connecting both databases, so that continuous sync can happen between our tables.


### **Scenario Setup:**

* **Source VM:** Windows Server 2019 with Oracle Image (*12.2.0.1.0 Enterprise Edition*) installed.
* **Oracle Database:** Non-Container Database (*12.2.0.1.0 Enterprise Edition*).
* **PostgreSQL Database:** Azure PostgreSQL-Single Server, PostgreSQL version 10
* **Duration of Demo:** Approximately *30 minutes*

## Prerequisites
* [Prerequisites tutorial](https://github.com/Click2Cloud/azure-oracle-migration/blob/master/Tutorials/oracleToPostgres/Prerequisites/README.md)

## Oracle to PostgreSQL Migration using Azure DMS (Video)

* [Oracle to PostgreSQL: DMS Tutorial](https://github.com/Click2Cloud/azure-oracle-migration/blob/master/Tutorials/oracleToPostgres/DMS/dmsTutorial.md)
* [Oracle to PostgreSQL: DMS Tutorial (Video)](https://github.com/Click2Cloud/azure-oracle-migration/blob/master/Videos/azuredmsproject.mp4)
