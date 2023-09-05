# Azure-Factory-pipeline

You must create a pipeline that copies data from two excel files from blob to Azure cloud SQL tables. What are the necessary steps you need to take to ensure this pipeline will get executed successfully?
Important points –
1. You can take any two sample excels with different columns. For example – Employee table and payroll table
2. Mappings for columns should not be hard coded it should be coming dynamically from lookup table for both source and destination
Hint –
1. Create a table of source to destination mappings and source file name and destination name.
2. Create a procedure to return dynamic Json mapping.
