# How to query date by using the Filter Bar {#task_uxp_dpf_vdb .task}

The Filter bar allows you to search data by date. You can set the date range for searching needed data.

The following examples use "company\_sales\_record" as the dataset.

## Create a dataset {#task_o2m_kpf_vdb}

1.   Log on to the Quick BI console. 
2.   Select **Workspace** \> **Data sources** . The data source management page is displayed. 
3.   Click **Create**, and select a data source. 

    For more operations on creating data sources, see [Create a Cloud Data Source](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a cloud data source.md#), [Create a Data Source from External Database](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Create a data source from external database.md#), and [Upload Local Files](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Upload local files.md#).

4.   Click the **Create Dataset** icon to create a dataset. 

## Create a dashboard {#task_c4b_3pf_vdb}

1.   Click **Dashboards** to go to the dashboard management page. 
2.   Click the dataset switch icon and select the **company\_sales\_record** dataset. 
3.   Select a chart type, for example, a bar chart. 
4.   Select the required field. 

    **Note:** If you want to query a certain date, the data must contain fields with date content.

5.   Click **Update**.  

## Enable the date query {#task_xtb_srf_vdb}

1.   Double-click the **Filter bar** icon. 
2.   Select **company\_sales\_record** as the source dataset. 
3.   Select **report\_date\(month\)** as the field to be queried. 
4.   Click **Single-Dataset** and select the **bar chart** as the chart to be associated. 
5.   In the query box, click the field name to open the field filtering menu. 
6.   Select **Date Range** and set the start time and end time of the date in the query box. 
7.   Click **Search**. The system updates the chart based on the specified conditions. 

