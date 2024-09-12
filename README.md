# Advanced Project on Property Market, Rental Market (incl. Scools, Transport & Crime) in Australia

This project initiates with CSV files in house values, rental values, schools, transport, crime and location data.

With siginificant data profiling on each files, a BUS diagram was implemented to have an idea of what the data warehouse design would look like (incl. an ERD)

SSIS was used as the main tool for the ETL process to pipeline the data into SQL Management Studio load tables. From load tables, the data were pipelining into transformed staging tables, and then following the transformed staging tables into creating a star schema model with dimention and fact tables for easy reporting and dashboard creation. 

With PowerBI as the main BI tool, and SQL star schema model as the source, dashboards are created for data analysis and insights.

SSRS as the reporting tool in paginated format were also implemented and connected with PowerBI dashboards.
