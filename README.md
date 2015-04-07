# brfss-data-structure
Table structure for importing CDC BRFSS 2013 data into SQL Server

The Behavioral Risk Factor Surveillance System is the largest phone survey in the U.S.
The survey includes questions about health-related/risk behaviors, disease conditions, demographic-socioeconomic variables.

The createimporttable.sql file creates a table structure into which you can load the full survey (~400,000 records).

The format2013data.sql file inserts and formats records from the import table, removing filler fields and adding a primary key.

Download the ASCII format data from CDC:
http://www.cdc.gov/brfss/annual_data/2013/files/LLCP2013ASC.ZIP (84 MG Zip file)
