# Express Connect {#concept_blv_wxd_zdb .concept}

CloudMonitor provides multiple metrics, such as the inbound traffic and outbound traffic, to help you monitor the status of Express Connect. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase Express Connect, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_ohv_xxd_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |Inbound traffic|User and instance|Bytes|1 minute|
    |Outbound traffic|User and instance|Bytes|1 minute|
    |Inbound bandwidth|User and instance|bit/s|1 minute|
    |Outbound bandwidth|User and instance|bit/s|1 minute|
    |Latency|User and instance|Milliseconds|1 minute|
    |Packet loss rate|User and instance|Percentage|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Express Connect**. The Express Connect page appears.
    3.  Click the ID of a router interface or click **Monitoring Charts** in the **Actions** column for a router interface to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_ihr_vyd_zdb .section}

-   **Set alert rules for a single router interface** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Express Connect**. The Express Connect page appears.
    3.  Click the ID of a router interface or click **Monitoring Charts** in the **Actions** column for a router interface to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple router interfaces at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Express Connect**. The Express Connect page appears.
    3.  Select target router interfaces and click **Set Alarm Rules** under the list to set alert rules for the selected router interfaces.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


