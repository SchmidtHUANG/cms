# NAT Gateway {#concept_i53_3rf_zdb .concept}

CloudMonitor provides multiple metrics, such as the number of source network address translation \(SNAT\) connections, to help you monitor the status of Network Address Translation \(NAT\) Gateway. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase NAT Gateway, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_php_jrf_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |SNAT connections|User and instance|Count/minute|1 minute|
    |Inbound bandwidth of a bandwidth package|User and instance|bit/s|1 minute|
    |Outbound bandwidth of a bandwidth package|User and instance|bit/s|1 minute|
    |Received packets of a bandwidth package|User and instance|PPS|1 minute|
    |Transmitted packets of a bandwidth package|User and instance|PPS|1 minute|
    |Outbound bandwidth usage of a bandwidth package|User and instance|Percentage|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **NAT Gateway**. The NAT Gateway List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_oyk_bsf_zdb .section}

-   **Set alert rules for a single instance** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **NAT Gateway**. The NAT Gateway List page appears.
    3.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple instances at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **NAT Gateway**. The NAT Gateway List page appears.
    3.  Select target instances and click **Set Alarm Rules** under the list to set alert rules for the selected instances.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


