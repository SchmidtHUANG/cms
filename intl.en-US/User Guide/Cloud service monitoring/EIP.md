# EIP {#concept_mng_pf5_xdb .concept}

CloudMonitor provides multiple metrics, such as the inbound traffic, outbound traffic, received packets, and transmitted packets, to help you monitor the status of Elastic IP Address \(EIP\). CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs. After you purchase EIP, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_bbw_jk4_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Inbound bandwidth|The traffic per second that passes through EIP to Elastic Compute Service \(ECS\).|Instance|bit/s|1 minute|
    |Outbound bandwidth|The traffic per second that passes through EIP from ECS.|Instance|bit/s|1 minute|
    |Received packets|The number of packets per second that pass through EIP to ECS.|Instance|PPS|1 minute|
    |Transmitted packets|The number of packets per second that pass through EIP from ECS.|Instance|PPS|1 minute|
    |Packet loss rate due to throttling|The packet loss rate when the actually used bandwidth exceeds the configured upper limit.|Instance|PPS|1 minute|


-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Elastic IP Address**. The Elastic IP Address page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_xtw_qk4_ydb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Elastic IP Address**. The Elastic IP Address page appears.
    3.  Click **Alarm Rules** in the **Actions** column for an instance to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


