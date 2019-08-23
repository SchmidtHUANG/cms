# ApsaraDB for Redis {#concept_vhm_kv4_ydb .concept}

CloudMonitor provides multiple metrics, such as the used capacity and used connections, to help you monitor the status of ApsaraDB for Redis. After you create an ApsaraDB for Redis instance, CloudMonitor automatically collects data based on these metrics. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_j5m_hw4_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Used capacity|The used capacity of the instance.|Instance|Bytes|1 minute|
    |Used connections|The number of client connections.|Instance|Count|1 minute|
    |Write bandwidth|The write traffic per second.|Instance|bit/s|1 minute|
    |Read bandwidth|The read traffic per second.|Instance|bit/s|1 minute|
    |Failed operations|The number of failed KVStore operations.|Instance|Count|1 minute|
    |Used capacity percentage|The percentage of the used capacity to the total capacity.|Instance|Percentage|1 minute|
    |Used connection percentage|The percentage of used connections to total connections.|Instance|Percentage|1 minute|
    |Write bandwidth usage|The percentage of the write bandwidth to the total bandwidth.|Instance|Percentage|1 minute|
    |Read bandwidth usage|The percentage of the read bandwidth to the total bandwidth.|Instance|Percentage|1 minute|
    |Instance failure|An event-type metric. You can set alert rules for this metric.|-|-|-|
    |Instance failover|An event-type metric. You can set alert rules for this metric.|-|-|-|


-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for Redis**. The Redis Monitoring List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts. 
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_yy5_qw4_ydb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for Redis**. The Redis Monitoring List page appears.
    3.  Click **Alarm Rules** in the **Actions** column for an instance to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


