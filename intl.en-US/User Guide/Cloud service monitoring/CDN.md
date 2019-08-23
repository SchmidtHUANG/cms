# CDN {#concept_wf2_cwt_xdb .concept}

CloudMonitor provides multiple metrics, such as the queries per second \(QPS\), bandwidth, and byte hit ratio, to help you monitor the status of Content Delivery Network \(CDN\). After you add a CDN domain name, CloudMonitor automatically collects data based on these metrics. You can log on to the CloudMonitor console and view the monitoring details on the CDN monitoring page. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_cxz_lwt_xdb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Visits per second|The number of visits in the monitoring period divided by the monitoring period.|Domain name|QPS|1 minute|
    |Bandwidth|The maximum traffic per unit time.|Domain name|bit/s|1 minute|
    |Hit ratio|The probability that request bytes are found in the cache in the monitoring period. The number of request bytes is the number of requests multiplied by traffic. The byte hit ratio reflects the back-to-origin traffic.|Domain name|Percentage|1 minute|
    |Outbound traffic to the Internet|The traffic from CDN to the Internet.|Domain name|Bytes|5 minutes|
    |Percentage of status codes 4xx|The percentage of HTTP status codes 4xx to all the returned HTTP status codes in the monitoring period.|Domain name|Percentage|1 minute|
    |Percentage of status codes 5xx|The percentage of HTTP status codes 5xx to all the returned HTTP status codes in the monitoring period.|Domain name|Percentage|1 minute|

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Alibaba Cloud CDN**. The CDN page appears.
    3.  Click the Domain Name List tab.
    4.  Click a domain name or click **Monitoring Charts** in the **Actions** column for a domain name to view the monitoring charts.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_bbz_qj4_ydb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Alibaba Cloud CDN**. The CDN page appears.
    3.  Click the Domain Name List tab.
    4.  Click **Alarm Rules** in the **Actions** column for a domain name to view the alert rules. 
    5.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


