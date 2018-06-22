# Data sources management overview {#concept_lpv_nxp_5db .concept}

Quick BI supports the following types of data sources.

## Cloud data sources {#section_agw_qxp_5db .section}

-   MaxCompute
-   MySQL
-   SQL Server
-   Analytic DB
-   Hybridgedb for MySQL
-   Hybridgedb for PostgreSQL
-   PostgreSQL
-   PPAS
-   Hive

## External database data sources {#section_kmm_sxp_5db .section}

-   MySQL
-   SQL Server
-   Oracle
-   Hive

## Other sources {#section_q5v_txp_5db .section}

-   CSV files
-   Excel files
-   Data IDE

Uploaded local files are stored in the exploration space. The exploration space is a dedicated storage area of Quick BI, providing 1G space for each user currently.

When creating data sources, the Quick BI has the following requirements for the network type of data sources.

1.  The RDS VPC instance can access Quick BI with an extranet domain name. However, an intranet domain name cannot access the Quick BI.
2.  RDS Mysql and SqlServer VPC instances can access Quick BI through an intranet domain name.
3.  Instances in the classic network can access Quick BI with an intranet domain name.
4.  Quick BI can be accessed by using the public network.

