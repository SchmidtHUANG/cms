# Open Ad {#concept_tyx_psf_zdb .concept}

CloudMonitor provides multiple metrics, such as the real-time bidding \(RTB\) page view \(PV\), queries per second \(QPS\) of RTB, and ad click PV, to help you to monitor the status of Open Ad. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase Open Ad, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_xkm_rsf_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |RTB PV|User|Count|1 minute|
    |RTB QPS|User|Count/second|1 minute|
    |Ad click PV|User|Count|1 minute|
    |Ad click QPS|User|Count/second|1 minute|
    |Ad click latency|User|Milliseconds|1 minute|
    |Ad impression PV|User|Count|1 minute|
    |Ad impression QPS|User|Count/second|1 minute|
    |Ad impression latency|User|Milliseconds|1 minute|
    |Active crowd number of Data Management Platform \(DMP\)|User|Count/day|1 hour|
    |Valid crowd requests of DMP|User|Count/day|1 hour|
    |Storage space occupied by DMP|User|Bytes/day|1 hour|
    |Active crowd number of Umeng Data Intelligence Platform \(DIP\)|User|Count/day|1 hour|
    |Valid crowd requests of Umeng DIP|User|Count/day|1 hour|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Openad**. On the Openad page that appears, you can view the overall status of Open Ad.
    3.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_z3g_dtf_zdb .section}

CloudMonitor allows you to set alert rules for the metrics of Open Ad so that you can receive alerts when any exception occurs.

-   **Method 1** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Openad**. The Openad page appears.
    3.  Click the bell icon in the upper-right corner of a monitoring chart. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Method 2** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Openad**. The Openad page appears.
    3.  Click the **Alarm Rules** tab.
    4.  On the Alarm Rules tab, click **Create Alarm Rule** in the upper-right corner. Specify the related resource, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


