# AnalyticDB {#concept_dcx_fwp_ydb .concept}

CloudMonitor provides multiple metrics, such as the rated disk capacity, occupied disk capacity, and disk usage, to help you monitor the status of AnalyticDB. After you purchase AnalyticDB, CloudMonitor automatically collects data based on these metrics. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_p4r_pwp_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |diskSize|The rated disk capacity.|Instance, table schema, and worker|MB|1 minute|
    |diskUsed|The occupied disk capacity.|Instance, table schema, and worker|MB|1 minute|
    |diskUsedPercent|The disk usage.|Instance, table schema, and worker|Percentage|1 minute|

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **AnalyticDB**. The ADS page appears.
    3.  Click the name of a database or click **Monitoring Charts** in the **Actions** column for a database to view the monitoring charts.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_eyk_wyp_ydb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **AnalyticDB**. The ADS page appears.
    3.  Click **Alarm Rules** in the **Actions** column for a database to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


