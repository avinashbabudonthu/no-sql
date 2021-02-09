# Install MongoDB
* Download mongo db from - https://www.mongodb.com/try/download/community
	* Select appropriate `version`, `platform`, `package`
	* Prefer downloading `zip`
	* Click `Download` button
* Unzip if zip is downloaded
* Install if msi is downloaded
* Start mongo db database
```
location-to-mongo-db-bin>mongod.exe
```
* Start mongo console to execute queries
```
location-to-mongo-db-bin>mongo.exe
```

# Database categories
* High level view\
![picture](pictures/database-categories.jpg)
* Specifics\
![picture](pictures/specifics-database-categories.jpg)
* Sql vs NoSql\
![picture](pictures/sql-vs-no-sql.jpg)
* Sql ACID properties\
![picture](pictures/sql-acid-properties.jpg)
* NoSql BASE property\
![picture](pictures/no-sql-base-property.jpg)
* Every NoSql works on `CAP` theory
![picture](pictures/no-sql-cap-theory.jpg)

# Basics
* Schema less
* Dynamic schema
* Most of NoSqls are open source
* Multiple types
	* Document
	* Key-Value
	* Tabular
	* Graph
* Examples
	* MongoDB
	* Cassandra
	* HBase
	* Neo4J
* Scaling
	* Horizontal scaling
		* What's the main difference? 
			* Horizontal scaling means scaling by adding more machines to your pool of resources (also described as `scaling out`)
			* Vertical scaling means scaling by adding more power (e.g. CPU, RAM) to an existing machine (also described as `scaling up`)
	* Supports distributed by default