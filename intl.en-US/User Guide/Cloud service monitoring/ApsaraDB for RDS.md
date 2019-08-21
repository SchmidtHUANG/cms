# ApsaraDB for RDS {#concept_l2z_2ys_xdb .concept}

CloudMonitor provides multiple metrics, such as the disk usage, input/output operations per second \(IOPS\) usage, connection usage, and CPU usage, to help you monitor the status of ApsaraDB for Relational Database Service \(RDS\). After you purchase RDS, CloudMonitor automatically collects data based on these metrics.

**Note:** 

-   Only primary and read-only instances in RDS support the monitoring and alerting services.
-   By default, CloudMonitor creates alert rules for each primary instance and read-only instance. The alert threshold is 80% for the CPU usage, connection usage, IOPS usage, and disk usage. When the usage of a resource exceeds 80%, an SMS message and an email are sent to the specified contacts.

## Monitoring service {#section_mm5_5zs_xdb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Disk usage|The percentage of the disk capacity used by the instance.|Instance|Percentage|5 minutes|
    |IOPS usage|The percentage of the IOPS used by the instance.|Instance|Percentage|5 minutes|
    |Connection usage|The percentage of instances that the current application connects to. The number of instances that an application can connect to is limited. This metric indicates the percentage of connected instances.|Instance|Percentage|5 minutes|
    |CPU usage|The percentage of the CPU capacity used by the instance. The CPU usage is determined by the database memory size.|Instance|Percentage|5 minutes|
    |Memory usage|The percentage of the memory used by the instance. Currently, only MySQL databases support this metric.|Instance|Percentage|5 minutes|
    |Read-only instance latency|The latency of the MySQL read-only instance.|Instance|Seconds|5 minutes|
    |Inbound traffic|The inbound traffic per second to the instance.|Instance|bit/s|5 minutes|
    |Outbound traffic|The outbound traffic per second from the instance.|Instance|bit/s|5 minutes|
    |Instance failure|An event-type metric. You can set alert rules for this metric.|-|-|-|
    |Instance failover|An event-type metric. You can set alert rules for this metric.|-|-|-|

    The metrics of inbound and outbound traffic support only MySQL and SQLServer databases.

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for RDS**. The ApsaraDB for RDS page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_fkc_y1t_xdb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **ApsaraDB for RDS**. The ApsaraDB for RDS page appears.
    3.  Click **Alarm Rules** in the **Actions** column for an instance to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


