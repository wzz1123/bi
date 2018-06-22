# How to make chart join {#concept_jrd_kfz_5db .concept}

You can create a dashboard with multiple charts join by using the following steps.

Users often have the following requirements when preparing dashboards. When a region of a chart control in a dashboard is selected, the content of other chart controls related to the chart control in the dashboard is linked with the content of members of the dimension corresponding to the selected region.

The following uses a sample dataset provided in the data modeling as an example to describe how to prepare a dashboard associated with multiple charts.

The dashboard consists of two chart controls. A pie chart is located at the top, showing the profit data of the region. A table is located at the bottom, showing the sales and profit data of cities in the region.

To better understand the content to be learned, you can first access the [Multi-chart associated demo report](https://das.base.shuju.aliyun.com/token3rd/shulaibao/preview.htm?pageId=34d4d8f7-4f0e-456d-874f-c8a05114b80b&accessToken=c55dc0b8868e33a9c3a5d825d4620100).

## Prepare a sample dataset {#section_pyy_lgz_5db .section}

Use a CSV file to create a dataset, see [Upload local files](../../../../intl.en-US/Quick Start/Data modeling/Data source management/Upload local files.md#) The sample dataset can also be downloaded from this section.

After creating the dataset, rename it as **Sales Data Demo Dataset**.

## Prepare a pie chart showing the profit distribution in the area {#section_uyf_5d2_vdb .section}

Click Dashboards. The dashboard management page is displayed. Click Create \> Dashboard. The dashboard editing page is displayed.

-   Double-click pie chart icon, and select **Sales Data Demo Dataset**.
-   Select **area** for Dimension.
-   Select **profit\_amt** for Measurement.

Click **Update**.

On the **Style** tab,  set the title of the pie chart to Regional Data.

## Prepare a list describing the sales and profit data of cities in the area {#section_vkw_ll2_vdb .section}

Doublke-click table icon. Put the table under the pie chart.

-   Select **Sales Data Demo Dataset**.
-   Select **area** and **city** for Dimension.
-   Select **profit\_amt** and **order\_number** for Measurement.

On the **Style** tab, set the title of the table to **City Data Details**.

Click **Update**.

## Join multiple charts with the pie chart {#section_yvx_kmf_vdb .section}

Click **More** tab on pie chart. Join tables by using fields.

## Preview the association effect {#section_utx_tmf_vdb .section}

Click **Preview** to check the association effect.

When you click different area on the pie chart, data of the following associated table chart changes accordingly.

For example, click **East** in the pie chart, the detailed information is displayed in the table.

## Save the dashboard {#section_nsz_qnf_vdb .section}

Click Save to save current dashboard.

## Make public the dashboard {#section_qmt_znf_vdb .section}

Make sure the dashboard does not contain any sensitive data.

