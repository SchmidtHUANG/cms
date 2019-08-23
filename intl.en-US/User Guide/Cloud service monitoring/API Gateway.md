# API Gateway {#concept_cmr_q2c_zdb .concept}

CloudMonitor provides multiple metrics, such as the inbound traffic, outbound traffic, and response time, to help you monitor the status of API Gateway.

After you purchase API Gateway, CloudMonitor automatically collects data based on these metrics. You can log on to the CloudMonitor console and view the monitoring details on the API Gateway monitoring page. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

## Monitoring service {#section_hjg_v2c_zdb .section}

-   **Metrics** 

    |Metric|Description|Dimension|Unit|Minimum frequency|
    |:-----|:----------|:--------|:---|:----------------|
    |Error distribution|The numbers of 2XX, 4XX, and 5XX status codes returned for an API in the monitoring period.|User and API|Count|1 minute|
    |Inbound traffic|The total traffic of requests received by an API in the monitoring period.|User and API|Bytes|1 minute|
    |Outbound traffic|The total traffic of responses sent by an API in the monitoring period.|User and API|Bytes|1 minute|
    |Response time|The latency between the time when API Gateway calls the backend service of an API and the time when the result is received from the backend service in the monitoring period.|User and API|Seconds|1 minute|
    |Total requests|The total number of requests received by an API in the monitoring period.|User and API|Count|1 minute|

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **API Gateway**. The API Gateway Monitoring List page appears.
    3.  Click the name of an API or click **Monitoring Charts** in the **Actions** column for an API to view the monitoring charts.
    4.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_zbk_nhc_zdb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **API Gateway**. The API Gateway Monitoring List page appears.
    3.  Click **Alarm Rules** in the **Actions** column for an API to view the alert rules.
    4.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


