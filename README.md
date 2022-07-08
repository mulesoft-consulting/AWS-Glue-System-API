# AWS-Glue-System-API
System API to integrate with AWS Glue and search RDS by database name, table or column list

# Pre-requisites:
- Check out AWSGlueLakeFormationJavaClient from the following git location
https://github.com/mulesoft-consulting/AWSGlueLakeFormationJavaClient.git
- Run mvn clean install to build and publish it into your local/remote artifact repo

# How to run:
- Ensure you have the right version of AWSGlueLakeFormationJavaClient mentioned in pom.xml
- Run this as any other mule api
- Invoke the endpoint /glue/searchTablesbyDatabase with the following query parameters
  - awsAccessKey
  - awsSecretKey
  - awsRegion
  - databaseName
  
 
