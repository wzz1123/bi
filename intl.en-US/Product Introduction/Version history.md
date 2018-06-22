# Version history {#concept_gkr_bdb_5db .concept}

## Quick Bi V2.0 Edition {#section_sxs_kgb_5db .section}

1. Product interaction process

The quick Bi interaction is upgraded to support the use of full links, and it is divided into Home, Workspace, Guide, and Subscription.

-   Home: The Home page includes the areas of Shared with Me and Favorites. A new user can quickly view resources in the workspace through the Report demos, and they also can join a workspace to view the resources in that workspace.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/1054_en-US.png)

-   Workspace: You can manage the data source, dataset, dashboard, and workbook, meanwhile, the display style of dashboard component is optimized, and the function of widgets is enhanced.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/1055_en-US.png)

-   Guide: The Guide provides a product process through a process chart.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/1056_en-US.png)

-   Subscription: You can create, manage, and monitor appropriate mail tasks through the Subscription function.

New Standard Edition

-   Added PostgreSQL, PPAs, and Oracle data sources
-   Add an image widget

New in advanced Edition

-   Workbook

    Added a data analysis method for a workbook. The workbook supports cell-level counting, displaying data from different data sources, and processing them at the same time. It also supports more than 200 data processing functions.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9067/1057_en-US.png)

-   Subscription

    Added mail subscription management lists to support mail task in dashboard.

-   Supports collaboration within a team

    Allows other members of the workspace to work together to edit a dashboard or spreadsheet.

-   New permission request and approval flow

    Support for dashboard, spreadsheet, portal permission requests, and message approval, helps users to take the initiative to obtain report permissions.


Four, the trial function embedded report changes

The Quick BI pro supports 20 reports embedded, and the Quick BI Basic closes third-party embedded entry, but the reports which are already embedded still can be edited.

## Quick BI v1.12  {#section_yd5_fhb_5db .section}

The features are updated as follows:

-   Add the HybridgeDB for MySQL data source.
-   The management control page of third-party embeddable system reports is added to the personal space. You can add and embed third-party system reports for easy use. For more information, see  [Help](https://help.aliyun.com/knowledge_detail/55768.html).
-   Add View function in SQL server data sources.
-   You can add notes for fields.

## Quick BI v1.11 {#section_izg_vhb_5db .section}

The features are updated as follows:

-   Added the following widgets in dashboard:

    -   Five charts: Polar chart, Cloud chart, Tornado chart, Hierarchy chart, and Conversion chart.
    -   One widget: IFRAME.
    More charts are contained in dashboard.

-   Added new rules in Table chart: You can use different colors and marks to display specified values or value ranges. The results of the data presentation are more clear.
-   New dashboard chart filter new detail filter feature: Metric filter in chart, not only support, filter by after-aggregation metric, filtering is now also supported based on the fine-grained metric of the pre-aggregation details. Quick BI supports more filtering methods.

## Quick BI  V1.10 {#section_b4t_f3b_5db .section}

The new dashboard product is released, and features are updated as follows:

-   The new dashboard uses the mainstream tile layout, users can easily adjust the size and location of the chart.
-   The new dashboard provides 12 charts and 2 widgets to optimize chart functionality. For example, the scattered chart supports to 1000 dimension values, the date widget is combined into the Filter, chart color is more beautiful and so on.
-   The new dashboard interaction logic is updated according to the user's habits, and the chart configuration is configured according to the chart elements. Users easy to learn and easy to use.
-   The new dashboard supports setting dimension and measurement filtering at the chart level, and the query condition is more flexible.
-   The Filter bar of the new dashboard supports both Single-Dataset and Multi-Dataset. The functions are more powerful.
-   The new dashboard's chart supports canceling the association between charts.
-   The new dashboard supports searching data during the report editing.

## Quick BI  v1.9 {#section_t1v_l3b_5db .section}

The features are updated as follows:

-   SQLServer data sources of ECS are supported.
-   Supports Excel-type files uploading: Meets the needs of users to upload and make reports from Excel files.
-   Table schema updating and data content updating of the exploration space are supported: The new version supports adding fields to the table schema and updating of table data content. You can add data files to the table and delete existing data files from the table.
-   Dashboard watermark optimization: Watermarks in previous versions display the user's base ID, and the current version replaces the base ID with a user login name.
-   To enhance the calculation field function: A calculated field is a new column that created by an existing field and SQL functions. The calculation field is conformed to the SQL column definition syntax rules  If the user needs to add a new field that uses existing fields to calculate, you can choose to add new calculation fields. Flexible data analysis, such as user attribute grouping analysis and price interval analysis, can be achieved by fields function of the field.
-   Quick BI Basic version release: The Basic edition supports the following features: Connect to multiple data sources; use a worksheet for data analysis; create a dashboard with a variety of data charts; create data portals; data downloads, share a worksheet, dashboard, portal, dashboard that can be embedded in a third-party system.\( Number <=2 of visits per account month <= 10 thousand per dashboard \), local files are uploaded to exploration space \(capacity <= 100 m per account \).
-   Support for dashboard data download: supports data corresponding to a graph control in a dashboard that can be downloaded in xlsx format.
-   Data line-level permission setting Style Optimization: removes the column display boxes that are redundant in the Set line-level permissions interface in the old version, the operation of querying Member values is appended to each selected controlled field, these interactive optimizes make the operation of Row-level permissions more smooth and convenient.
-   Added Analyst roles in the workspace: The analyst is a role between the developer and the viewer. This role can use data sources and datasets to create reports, but the analyst cannot create or edit data sources and datasets. The requirement comes from the user's proposal, it is a role requirement that is refined from the user's real usage scenario.
-   Batch upload of users in organizational unit management is supported: Earlier versions only allow the organizational unit administrator to manually add members. The batch user upload function is required for organizational unit that has a large number of members. This function enables the organizational unit administrator to add users in batches by filling in the workbook with Alibaba Cloud accounts and nicknames according to the template requirements. A maximum of 3000 users can be added at a time.
-   Users who choose to share and transfer in a drop-down box in support of cluster space: previous versions used to share and transfer reports in cluster space when selecting users through a fuzzy search. way, only the match to keyword displays a list of the corresponding users, and currently supports the selection of users in the form of a drop-down box, it is easier for users to use.

## Quick BI v1.8 {#section_r34_s3b_5db .section}

The features are updated as follows:

-   Data modeling optimization: Previous maintenance of the data set can only be performed in the worksheet, multiple work sheets affect each other and are error prone, the new release centrally manages the maintenance of the data set from the worksheet, supporting a table of facts. from a fact table. It makes the dataset editing is easier to use.
-   Terms of data objects and use general terms in the industry are unified. Metering is changed to measurement, and drilling group is changed to layer schema.

## Quick BI v1.7 {#section_ccl_v3b_5db .section}

The features are updated as follows:

-   Support for CSV file data sources: enables CSV files to be uploaded to Discovery space, enables users to freely analyze their own data.
-   The main navigation bar is optimized. Data sources and datasets are integrated into a single data tag.

## Quick BI v1.6 {#section_sf1_y3b_5db .section}

The features are updated as follows:

-   Publishing datasets speed-up function: Based on Quick  Bi built-in Acceleration Engine allows users to create extreme-speed data sets in the form, make the tables in maxcompute into extreme-speed data sets, and greatly increase the query speed.
-   Add greenplum Data source Database open source database project, features such as OSS storage, JSON data types, hyperloglog Prediction and Analysis are supported by the Ali cloud depth extension. Complying with SQL 2008 standard query syntax and OLAP aggregate functions, ApsaraDB HybridDB offers a flexible hybrid analyzing capability.
-   Implement the ability to share to any member: The former sharing function can only be shared with users in a same organization. The new feature makes sharing easier to collaborate between users.

## Quick BI v1.5 {#section_enp_bjb_5db .section}

The features are updated as follows:

-   New dashboard publishing features.
-   The scenario analysis - HiChina log analysis template goes live.

## Quick BI v1.4 {#section_pzm_cjb_5db .section}

The features are updated as follows:

-   Distributed execution layer framework optimization upgrade.
-   Supports data source deletion.
-   SQLServer is supported.

## Quick BI v1.3 {#section_vf4_cjb_5db .section}

The features are updated as follows:

-   Add User demo.
-   The process of creating a file is optimized.

## Quick BI v1.2 {#section_ex4_cjb_5db .section}

The features are updated as follows:

-   Simplify tenant models, data source management, work-sharing areas, authorization, and applications.
-   Implement dashboard embedded into a third-party system to showcase.

## Quick BI  V1.1 {#section_orh_kjb_5db .section}

The features are updated as follows:

-   The problem about user's data source network connection is solved.
-   Implement the sharing function.

## Quick BI V1.0 {#section_fhv_kjb_5db .section}

The features are updated as follows:

-   Quick BI supports developing and creating datasets, workbooks, dashboards, and data portals.

