# SSB-Iceberg-Demo
 

## Prereqs:

SSB Project requires 3 kafka topics, and 3 impala tables which are not part of this repo.  Please see upstream documenation for details.

***

## Fork Project    

1. Fork this repo and import your repo as a project in Sql Stream Builder
2. Open your Project and have a look around at the left menu and explorer
3. Import Your Keytab
4. Check out Source Control.  If you created repo, you may have to press import still.
5. Inspect/Add Data Sources
6. Inspect/Add Virtual Kafka Tables

***

## Modify Jobs

1. CSA_1_11_Iceberg_Sample - Example in CSA 1.11 docs
2. Countries_Kafka - Select from Kafka Countries, Create IceBerg Table, Insert Results
3. Routes_Kafka - Select from Kafka Routes, Create IceBerg Table, Insert Results
4. Test_Hue_Tables

***

## Execution of Jobs:

Warning: These are not full ssb jobs.  In these are samples you execute each statements one at a time.

***

## Evaluating Results: