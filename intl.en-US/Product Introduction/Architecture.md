# Architecture {#concept_zlb_pyv_tdb .concept}

The architecture of Quick BI is shown as follows.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9064/1012_en-US.png)

Key components and features are as follows.

-   Data connection module: Supports multiple Alibaba Cloud data sources such as MaxCompute, ApsaraDB for RDS \(MySQL, PostgreSQL, and SQL Server\),  Analytic DB, HybridDB \(MySQL and PostgreSQL\). This module encapsulates standard APIs to query the data sources.
-   Data preparation module: Provides lightweight ETC processing of data sources, mainly to customize SQL of MaxCompute for now, and is expected to support more data source pre-processing in the future.
-   Data modeling: Processes OLAP modeling of data sources. You can build multi-dimensional analysis models on the SQL syntax of your data sources by using calculated field and standard semantics,  such as dimensions \(date and location\), measurement, and star-type topology.
-   Worksheet/Workbook: Supports spreadsheet actions, which include analysis tools such as adding filters to a row or a column, common and advanced filtering, subtotal, auto-sum, and condition format. Workbook also supports data exporting, text formatting, and sheet formatting.
-   Dashboard: Provides 5 widgets \(filter bar, text area, TAB, IFRAME, and PIC\) and 17 kinds of visual charts, including line chart, pie chart, bar chart, funnel chart, treemap, geo bubble, geo chart, gauge, and so on.  You can drag-and-drop to create any visual you want, and any change in the dataset is reflected here at real-time speed.
-   Portal: Lets you package your dashboards, workbooks, and even external links to build an analytics product. You can also customize templates and menu bar.
-   QUERY engine: Queries data from data sources.
-   Organizational unit management and authorizations: Manages authorizations in a three-layer hierarchy: organization - workspace - role, to control access permission of each report.
-   Row-level permission management: Control access to data at row-level, enables different roles to have row-level access to data stored in a table.
-   Share and Make public: Transfers or shares worksheets, workbooks, dashboards, and portals to other authorized users, and makes public dashboards on the Internet for unauthorized users to access.

