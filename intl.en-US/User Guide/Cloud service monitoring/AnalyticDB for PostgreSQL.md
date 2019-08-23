# AnalyticDB for PostgreSQL {#concept_pl4_tlf_zdb .concept}

CloudMonitor provides multiple metrics, such as the CPU usage and memory usage, to help you monitor the status of AnalyticDB for PostgreSQL. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase AnalyticDB for PostgreSQL, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_hrz_vlf_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |Disk usage|User and instance|Percentage|5 minutes|
    |Connection usage|User and instance|Percentage|5 minutes|
    |CPU usage|User and instance|Percentage|5 minutes|
    |Memory usage|User and instance|Percentage|5 minutes|
    |I/O throughput usage|User and instance|Percentage|5 minutes|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **AnalyticDB for PostgreSQL**. The AnalyticDB for PostgreSQL Monitoring List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_v1x_hmf_zdb .section}

-   **Set alert rules for a single instance** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **AnalyticDB for PostgreSQL**. The AnalyticDB for PostgreSQL Monitoring List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple instances at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **AnalyticDB for PostgreSQL**. The AnalyticDB for PostgreSQL Monitoring List page appears.
    3.  Select target instances and click **Set Alarm Rules** under the list to set alert rules for the selected instances.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


