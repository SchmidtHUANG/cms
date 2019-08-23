# Realtime Compute {#concept_g21_2bf_zdb .concept}

CloudMonitor provides multiple metrics, such as the service latency, to help you monitor the status of Realtime Compute. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase Realtime Compute, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_fhd_sbf_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Description|Minimum frequency|
    |:-----|:--------|:---|:----------|:----------------|
    |Service latency|Project and job|Seconds|The latency between data production and data processing.|1 minute|
    |Read records per second \(RPS\)|Project and job|RPS|The average number of data records read per second for the job.|1 minute|
    |Write RPS|Project and job|RPS|The average number of data records written per second for the job.|1 minute|
    |FailoverRate|Project and job|Percentage|The failover rate of the job. The lower the better.|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Stream Computing**. The ProjectList page appears.
    3.  Click the name of a project or click **Monitoring Charts** in the **Actions** column for a project to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_nhz_ccf_zdb .section}

-   **Set alert rules for a single project** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Stream Computing**. The ProjectList page appears.
    3.  Click the name of a project or click **Monitoring Charts** in the **Actions** column for a project to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple projects at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Stream Computing**. The ProjectList page appears.
    3.  Select target projects and click **Set Alarm Rules** under the list to set alert rules for the selected projects.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


