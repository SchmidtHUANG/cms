# Elasticsearch {#concept_cvv_lld_zdb .concept}

CloudMonitor provides multiple metrics, such as the cluster status, cluster queries per second \(QPS\), and cluster write QPS, to help you monitor the status of Elasticsearch. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase Elasticsearch, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_lsc_hnd_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |Cluster status|Cluster| |1 minute|
    |Cluster QPS|Cluster|Count/second|1 minute|
    |Cluster write QPS|Cluster|Count/second|1 minute|
    |CPU usage of a node|Node|Percentage|1 minute|
    |Disk usage of a node|Node|Percentage|1 minute|
    |Heap memory usage of a node|Node|Percentage|1 minute|
    |Load of a node within 1 minute|Node| |1 minute|
    |FullGC times of a node|Node|Count|1 minute|
    |Exceptions of a node|Node|Count|1 minute|
    |Cluster snapshot status|Cluster|A value of -1 indicates that no snapshot exists. A value of 0 indicates that the snapshot is created. A value of 1 indicates that the snapshot is being created. A value of 2 indicates that the snapshot fails to be created.|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Elasticsearch**. The Elasticsearch page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_jdy_m4d_zdb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Elasticsearch**. The Elasticsearch page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


