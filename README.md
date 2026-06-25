# Mini project 1: Data lake folder design

## Business problem
An e-commerce company received daily data from multiple source system
. Order from the transaction database 
. customer from CRM system
. Product from the product master system
. Payment from payment gateway API
. Website event from clickstream logs

The company needs a clean azure data lake storage gen2 design so data engineers
can ingest , process validate and serve reliable data to analyst , data sciencce and business users

GOAL: Design a practical data lake folder structure using raw , bronze, silver and gold layers

 The design should support
 . Daily batch ingestion
 . Orignal raw data preservation(protection)
 . Reprocessing from source files
 . Cleaned datasets for analytics
 . Business ready gold output
 . Simple access control by layer

 
