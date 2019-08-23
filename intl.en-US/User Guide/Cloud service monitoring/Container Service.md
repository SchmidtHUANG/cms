# Container Service {#concept_smn_jp5_ydb .concept}

CloudMonitor provides multiple metrics, such as the CPU usage and memory usage, to help you monitor the status of Container Service. After you create a Container Service cluster, CloudMonitor automatically collects data based on these metrics. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_dvv_qp5_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |containerCpuUtilization|The CPU usage of the container.|User and container|Percentage|30 seconds|
    |containerMemoryUtilization|The memory usage of the container.|User and container|Percentage|30 seconds|
    |containerMemoryAmount|The amount of memory used by the container.|User and container|Bytes|30 seconds|
    |containerInternetIn|The inbound traffic of the container.|User and container|Bytes|30 seconds|
    |containerInternetOut|The outbound traffic of the container.|User and container|Bytes|30 seconds|
    |containerIORead|The I/O read traffic of the container.|User and container|Bytes|30 seconds|
    |containerIOWrite|The I/O write traffic of the container.|User and container|Bytes|30 seconds|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Container Service**. The Clusters page appears.
    3.  Click **Monitoring Charts** in the **Actions** column for a cluster to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_gd3_dq5_ydb .section}

-   **Set alert rules for a single cluster** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Container Service**. The Clusters page appears.
    3.  Click **Monitoring Charts** in the **Actions** column for a cluster to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple clusters at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Container Service**. The Clusters page appears.
    3.  Select target clusters and click **Set Alarm Rules** under the list to set alert rules for the selected clusters.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


