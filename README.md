# Azure SQL Data Warehouse DWU Calculator Perf Collector

This perf collector will capture resource utilization for a database server and create a CSV file to be uploaded to the [Azure SQL Data Warehouse DWU Calculator](http://dwucalculator.azurewebsites.net/). To assist in capturing the correct performance metrics, download and run this project to capture your database utilization. The project is configured to capture the below performance counters for a one hour period.

* Logical Disk - Disk Read Bytes/sec
* Logical Disk - Disk Write Bytes/sec
