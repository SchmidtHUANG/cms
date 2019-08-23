# Log Service {#concept_fwh_cn5_ydb .concept}

CloudMonitor provides multiple metrics, such as the inbound traffic and outbound traffic, total queries per second \(QPS\), and log statistics, to help you monitor the status of Log Service. After you create a Log Service project, CloudMonitor automatically collects data based on these metrics. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_vxj_qn5_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Inflow|The inbound traffic of the Logstore per minute.|User, project, and Logstore|Bytes|1 minute|
    |Outflow|The outbound traffic of the Logstore per minute.|User, project, and Logstore|Bytes|1 minute|
    |SumQPS|The number of writes per minute in the Logstore.|User, project, and Logstore|Count|1 minute|
    |LogMethodQPS|The number of writes per minute for each method in the Logstore.|User, project, Logstore, and method|Count|1 minute|
    |LogCodeQPS|The number of writes per minute for each status code in the Logstore.|User, project, Logstore, and status|Count|1 minute|
    |SuccessdByte|The number of resolved bytes in the Logstore.|User, project, and Logstore|Bytes|10 minutes|
    |SuccessdLines|The number of lines in resolved logs in the Logstore.|User, project, and Logstore|Count|10 minutes|
    |FailedLines|The number of lines in logs that failed to be resolved in the Logstore.|User, project, and Logstore|Count|10 minutes|
    |AlarmPV|The total number of Elastic Compute Service \(ECS\) configuration errors in the Logstore.|User, project, and Logstore|Count|5 minutes|
    |AlarmUv|The total number of ECS instances with incorrect configurations in the Logstore.|User, project, and Logstore|Count|5 minutes|
    |AlarmIPCount|The number of errors incurred by each IP address in the Logstore.|User, project, Logstore, alert type, and source IP address|Count|5 minutes|

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Log Service**. The Log Service page appears.
    3.  Click **Monitoring Charts** in the **Actions** column for a project to view the monitoring charts.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_bgt_d45_ydb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Log Service**. The Log Service page appears.
    3.  Click **Alarm Rules** in the **Actions** column for a project to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    **Note:** 

    -   When setting alert rules, you can specify the status for a status-related metric. Valid values of the status field include 200, 400, 401, 403, 405, 500, and 502.
    -   You can specify the method for a metric related to the operation count. Valid values of the method field include PostLogStoreLogs, GetLogtailConfig, PutData, GetCursorOrData, GetData, GetLogStoreHistogram, GetLogStoreLogs, ListLogStores, and ListLogStoreTopics.
    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


