# ApsaraDB for MongoDB {#concept_bwg_gx4_ydb .concept}

CloudMonitor provides multiple metrics, such as the CPU usage and memory usage, to help you monitor the status of ApsaraDB for MongoDB. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs. After you purchase ApsaraDB for MongoDB, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_xjm_3x4_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |CPU usage|The CPU usage of the instance.|User, instance, and primary/secondary node|Percentage|5 minutes|
    |Memory usage|The memory usage of the instance.|User, instance, and primary/secondary node|Percentage|5 minutes|
    |Disk usage|The disk usage of the instance.|User, instance, and primary/secondary node|Percentage|5 minutes|
    |Input/Output operations per second \(IOPS\) usage|The IOPS usage of the instance.|User, instance, and primary/secondary node|Percentage|5 minutes|
    |Connection usage|The percentage of instances to which the current application connects. The number of instances to which an application can connect is limited. This metric indicates the percentage of connected instances.|User, instance, and primary/secondary node|Percentage|5 minutes|
    |Average number of SQL queries per second|The average number of SQL queries per second for the instance.|User, instance, and primary/secondary node|Count|5 minutes|
    |Connections in use|The number of instances to which the current application connects.|User, instance, and primary/secondary node|Count|5 minutes|
    |Disk space occupied by an instance|The total disk space occupied by the instance.|User, instance, and primary/secondary node|Bytes|5 minutes|
    |Disk space occupied by data|The disk space occupied by data.|User, instance, and primary/secondary node|Bytes|5 minutes|
    |Disk space occupied by logs|The disk space occupied by logs.|User, instance, and primary/secondary node|Bytes|5 minutes|
    |Inbound internal network traffic|The inbound traffic of the instance.|User, instance, and primary/secondary node|Bytes|5 minutes|
    |Outbound internal network traffic|The outbound traffic of the instance.|User, instance, and primary/secondary node|Bytes|5 minutes|
    |Request count|The total number of requests sent to the server.|User, instance, and primary/secondary node|Count|5 minutes|
    |Insert operations|The total number of insert commands received since the last time the instance was started.|User, instance, and primary/secondary node|Count|5 minutes|
    |Query operations|The total number of query commands received since the last time the instance was started.|User, instance, and primary/secondary node|Count|5 minutes|
    |Update operations|The total number of update commands received since the last time the instance was started.|User, instance, and primary/secondary node|Count|5 minutes|
    |Delete operations|The total number of delete operations performed since the last time the instance was started.|User, instance, and primary/secondary node|Count|5 minutes|
    |Getmore operations|The total number of getmore operations performed since the last time the instance was started.|User, instance, and primary/secondary node|Count|5 minutes|
    |Command operations|The total number of commands sent to the database since the last time the instance was started.|User, instance, and primary/secondary node|Count|5 minutes|
    |Instance failure|An event-type metric. You can set alert rules for this metric.|-|-|-|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for MongoDB**. The MongoDB page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_cpf_3qp_ydb .section}

-   **Set alert rules for a single instance** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for MongoDB**. The MongoDB page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart to set alert rules for the corresponding metric of this instance.
-   **Set alert rules for multiple instances at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for MongoDB**. The MongoDB page appears.
    3.  Select target instances and click **Set Alarm Rules** under the list to set alert rules for the selected instances.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


