# demopipeline


Problem: 
   Data Factory V2 
   -> Azure Blob Store 
   -> Azure SQL DW Polybase 
   -> Azure SQL DW  
   -> Power BI.

plan:

* config variables
* create blob store
* configure local files
* create pipeline from local to blob
* execute pipeline to import data from local to blob staging 
* create DW
* create external tables
* execute polybase import to DW
* create pbi template in direct query mode

* all scripted.

* tear down resource group

Learnings:
ARM templates

