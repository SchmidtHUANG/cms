# MNS {#concept_qyg_ysp_ydb .concept}

CloudMonitor provides multiple metrics, such as the numbers of delayed messages, invalid messages, and active messages, to help you monitor the status of Message Service \(MNS\). After you create an MNS queue, CloudMonitor automatically collects data based on these metrics. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_gly_ltp_ydb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |ActiveMessages|The total number of active messages in the queue.|User, region, bucket, and queue|Count|5 minutes|
    |InactiveMessages|The total number of inactive messages in the queue.|User, region, bucket, and queue|Count|5 minutes|
    |DelayMessage|The total number of delayed messages in the queue.|User, region, bucket, and queue|Count|5 minutes|
    |SendMessageCount|The number of requests for sending a message.|User, region, and queue|Count|60 minutes|
    |BatchSendMessageCount|The number of requests for sending multiple messages at a time.|User, region, and queue|Count|60 minutes|
    |ReceiveMessageCount|The number of requests for receiving a message.|User, region, and queue|Count|60 minutes|
    |BatchReceiveMessageCount|The number of requests for receiving multiple messages at a time.|User, region, and queue|Count|60 minutes|
    |BatchDeleteMessageCount|The number of requests for deleting multiple messages at a time.|User, region, and queue|Count|60 minutes|
    |ChangeMessageVisibilityCount|Change the number of visible messages.|User, region, and queue|Count|60 minutes|

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Message Service**. The MNS List page appears.
    3.  Click the name of a queue or click **Monitoring Charts** in the **Actions** column for a queue to view the monitoring charts.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_akp_dvp_ydb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Message Service**. The MNS List page appears.
    3.  Click **Alarm Rules** in the **Actions** column for a queue to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


