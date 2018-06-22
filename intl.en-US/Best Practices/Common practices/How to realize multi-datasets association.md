# How to realize multi-datasets association {#task_jby_zcg_vdb .task}

For association of multiple charts, the dashboard supports single-dataset association and multi-datasets association.

For association of multiple charts, the dashboard supports single-dataset association and multi-datasets association.

Multi-datasets association is to associate data from different datasets for comparison. However, for multi-datasets association, you must make sure that the values of data in the associated items are identical. Otherwise, the association does not work.

The following is an example of querying report forms from different datasets \(company\_sales\_record\_1124 and company\_sales\_record\_cn\) by using the multi-datasets association function.

## Create a dataset {#task_yw1_q2g_vdb}

1.   Log on to the Quick BI console. 
2.   Select **Workspace** \> **Data sources**. The data source management page is displayed. 
3.   Click **Create**, and select a data source. 

    For more operations on creating data sources, see [Create a Cloud Data Source](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a cloud data source.md#), [Create a Data Source from External Database](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a data source from external database.md#), and [Upload Local Files](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Upload local files.md#).

4.   Click Create Dataset icon to create the dataset. 

    For more operations on creating datasets, see [Create a dataset](../../../../intl.en-US/Quick Start/Data modeling/Dataset management/Create a dataset.md#).


## Create a dashboard {#task_i5h_bfg_vdb}

1.   Click **Dashboards** to enter the dashboard management page. 
2.   Click to switch the dataset to company\_sales\_record\_1124. 
3.   Select a chart type, for example, Table. 
4.   Select the required field. 
5.   Click **Update**.  
6.   Click **Style**, and rename the title of the chart **Overseas report form**. 
7.   Click to switch the dataset to company\_sales\_record\_cn. 
8.   Select a chart type, for example, Table. 
9.   Select the required field. 
10.  Select **Update**, and the system automatically draws a chart. 
11.  Click **Style**, and rename the title of the chart **Domestic report form**. 
12.  Click **Save** to save the dashboard. 

## Implement multi-datasets association {#task_khg_lgg_vdb}

1.   Double-click the **Filter bar** widget, and drag it to the top of the dashboard. 
2.   On the **Data** page, select a target dataset, for example, company\_sales\_record\_cn. 
3.   Select a field to be queried, for example, product\_box. 
4.   Click **Single-Dataset**, and select the domestic report form. 
5.   Click **Multi-Dataset**, and click the drop-down arrow next to the overseas report form to open the field list. 
6.   Select the same field to be queried \(product\_box\). 
7.   In the widget, click **Product\_box** to open the field filter menu. 
8.   Select **Enum** as a filter condition for the field, and then select single choice or multiple choices. 
9.   Click the drop-down arrow of the product box, and select the item to be filtered. 
10.  Click **Search**, and the widget performs the query on both the domestic report form and overseas report form. 

