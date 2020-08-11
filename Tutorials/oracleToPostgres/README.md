# Azure DMS: Oracle to Azure PostgreSQL-Hyperscale

The **Azure Database Migration Service** is a tool that serves as a way to :
* Migrate, guide, and automate your current **database migration** to **Azure**. 
* Effortlessly **migrate** data, schemas, and objects from various sources to the **cloud**.

## Azure DMS provides the following features:
* Supports Microsoft SQL Server, MySQL, PostgreSQL, MongoDB, and Oracle migration to Azure from **on-premise and other clouds**.
* Migration moves data, schema, and objects to Azure.
* Highly expansive migration service provides stable outcomes with almost **no downtime**.
* Database Migration Service (**DMS**) works with **PowerShell** commandlets to automatically migrate a list of databases.
* **Built-in** comprehensive **security** and **compliance**.



## Scenario
<kbd>
  <img src="https://github.com/alexanderpetraliac2c/azure-oracle-migration/blob/master/Images/15.png">
</kbd></p>



### **Scenario Details:** <br />
* Create an on-premise Oracle database through an **Azure Windows 2019 Server VM** with an Oracle image (*12.2.0.1.0 Enterprise Edition*) installed.
* Assess **tables and objects** that user wants to migrate to the created **Azure PostgreSQL Database**. 
* Then migrate the schema from the **Oracle Database** to the **Azure PostgreSQL Database**.
* After this set up **Azure DMS** by connecting both databases, so that continuous sync can happen between our tables.
* We then create an **Azure PostgreSQL-Hyperscale Database** and migrate the schema from regular PostgreSQL
* Finally, we connect PostgreSQL to PostgreSQL-Hyperscale using Azure DMS

### **Scenario Setup:**

* **Source VM:** Windows Server 2019 with Oracle Image (*12.2.0.1.0 Enterprise Edition*) installed.
* **Oracle Database:** Non-Container Database (*12.2.0.1.0 Enterprise Edition*).
* **PostgreSQL Database:** Azure PostgreSQL-Single Server, PostgreSQL version 10
* **PostgreSQL-Hyperscale Database:** Azure PostgreSQL-Hyperscale Server, PostgreSQL version 11
* **Duration of Demo:** Approximately *30 minutes*



## Step 1: Oracle to Azure PostgreSQL-Single Server
[Oracle to PostgreSQL Tuorial](https://github.com/Click2Cloud/azure-oracle-migration/tree/master/Tutorials/oracleToPostgres/oraToPg)


## Step 2: Azure PostgreSQL-Single Server to Azure PostgreSQL-Hyperscale
[PostgreSQL to PostgreSQL-Hyperscale Tuorial](https://github.com/Click2Cloud/azure-oracle-migration/tree/master/Tutorials/oracleToPostgres/pgToPgHyperscale)






