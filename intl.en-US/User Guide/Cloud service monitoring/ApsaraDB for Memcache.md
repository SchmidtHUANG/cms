# ApsaraDB for Memcache {#concept_fvw_vt4_ydb .concept}

CloudMonitor provides multiple metrics, such as the used cache and read hit ratio, to help you monitor the status of ApsaraDB for Memcache. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs. After you purchase Memcache, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_kgs_yt4_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Used cache|The amount of used cache.|Instance|Bytes|1 minute|
    |Read hit ratio|The success rate of reading key-values \(KVs\).|Instance|Percentage|1 minute|
    |QPS|The number of KV read requests per second.|Instance|QPS|1 minute|
    |Records|The total number of KVs read in the monitoring period.|Instance|Count|1 minute|
    |Cache inbound bandwidth|The bandwidth used for writing data to the cache.|Instance|bit/s|1 minute|
    |Cache outbound bandwidth|The bandwidth used for reading data from the cache.|Instance|bit/s|1 minute|
    |Evictions|The number of KVs evicted per second.|Instance|Count/second|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for Memcache**. The ApsaraDB for Memcache List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.****

## Alerting service {#section_ryv_g54_ydb .section}

CloudMonitor allows you to set alert rules for the metrics of ApsaraDB for Memcache so that you can receive alerts when any exception occurs.

-   **Set alert rules for a single instance** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for Memcache**. The ApsaraDB for Memcache List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart to set alert rules for the corresponding metric of this instance.
-   **Set alert rules for multiple instances at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for Memcache**. The ApsaraDB for Memcache List page appears.
    3.  Select target instances and click **Set Alarm Rules** under the list to set alert rules for the selected instances.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


