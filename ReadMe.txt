1. Run DataStream_and_MasterData_Creation.sql.
TRANSACTIONS and MASTERDATA tables are created and all data sources is prepared.

2. Run createDW.sql. 
Data warehouse is generated, which includes Fact table, dimension tables and contraints.

3. Run INLJ.sql.
Transactional data are loaded and transferred into DW after joining with MD.

4. Run queriesDW.sql.
OLAP queries are used to accomplish DW analysis. 