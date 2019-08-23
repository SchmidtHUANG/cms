# SLB {#concept_by4_yqt_xdb .concept}

CloudMonitor provides multiple metrics, such as the inbound traffic and outbound traffic, to help you to monitor the status of Server Load Balancer \(SLB\). CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs. After you create an SLB instance, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_kbm_drt_xdb .section}

-   **Metrics** 
    -   Layer-4 protocol metrics

        |Metric|Description|Dimension|Unit|Minimum frequency|
        |:-----|:----------|:--------|:---|:----------------|
        |Inbound traffic on a port|The traffic consumed for accessing the port from the Internet.|Port|bit/s|1 minute|
        |Outbound traffic on a port|The traffic consumed for accessing the Internet from the port.|Port|bit/s|1 minute|
        |Received packets on a port|The number of packets received on the port per second.|Port|Count/second|1 minute|
        |Transmitted packets on a port|The number of packets transmitted on the port per second.|Port|Count/second|1 minute|
        |New connections on a port|The average number of times that the status is SYN\_SENT at first for a TCP three-way handshake in the monitoring period.|Port|Count|1 minute|
        |Active connections on a port|The number of connections in the ESTABLISHED status on the port in the monitoring period.|Port|Count|1 minute|
        |Inactive connections on a port|The number of connections in statuses other than ESTABLISHED on the port in the monitoring period.|Port|Count|1 minute|
        |Concurrent connections on a port|The total number of connections on the port \(including both active and inactive connections\) in the monitoring period.|Port|Count|1 minute|
        |Healthy backend Elastic Compute Service \(ECS\) instances|The number of instances that pass the health test.|Port|Count|1 minute|
        |Faulty backend ECS instances|The number of instances that fail the health test.|Port|Count|1 minute|
        |Connections discarded on a port|The average number of connections discarded on the port per second.|Port|Count/second|1 minute|
        |Received packets discarded on a port|The average number of received packets discarded on the port per second.|Port|Count/second|1 minute|
        |Transmitted packets discarded on a port|The average number of transmitted packets discarded on the port per second.|Port|Count/second|1 minute|
        |Inbound traffic discarded on a port|The average inbound traffic discarded on the port per second.|Port|bit/s|1 minute|
        |Outbound traffic discarded on a port|The average outbound traffic discarded on the port per second.|Port|bit/s|1 minute|
        |Active connections on an instance|The number of connections in the ESTABLISHED status on the instance in the monitoring period.|Instance|Count/second|1 minute|
        |Inactive connections on an instance|The number of connections in statuses other than ESTABLISHED on the instance in the monitoring period.|Instance|Count/second|1 minute|
        |Connections discarded on an instance|The number of connections discarded on the instance per second.|Instance|Count/second|1 minute|
        |Received packets discarded on an instance|The number of received packets discarded on the instance per second.|Instance|Count/second|1 minute|
        |Transmitted packets discarded on an instance|The number of transmitted packets discarded on the instance per second.|Instance|Count/second|1 minute|
        |Inbound traffic discarded on an instance|The amount of inbound traffic discarded on the instance per second.|Instance|bit/s|1 minute|
        |Outbound traffic discarded on an instance|The amount of outbound traffic discarded on the instance per second.|Instance|bit/s|1 minute|
        |Concurrent connections on an instance|The total number of connections on the instance \(including both active and inactive connections\) in the monitoring period.|Instance|Count/second|1 minute|
        |New connections on an instance|The average number of times that the status is SYN\_SENT at first for a TCP three-way handshake in the monitoring period.|Instance|Count/second|1 minute|
        |Received packets on an instance|The number of packets received on the instance per second.|Instance|Count/second|1 minute|
        |Transmitted packets on an instance|The number of packets transmitted on the instance per second.|Instance|Count/second|1 minute|
        |Inbound traffic on an instance|The traffic consumed for accessing the instance from the Internet.|Instance|bit/s|1 minute|
        |Outbound traffic on an instance|The traffic consumed for accessing the Internet from the instance.|Instance|bit/s|1 minute|

    -   Layer-7 protocol metrics

        |Metric|Description|Dimension|Unit|Minimum frequency|
        |:-----|:----------|:--------|:---|:----------------|
        |QPS on a port|The QPS on the port.|Port|Count/second|1 minute|
        |Response time \(RT\) on a port|The average response time to requests on the port.|Port|Milliseconds|1 minute|
        |Status codes 2xx on a port|The number of status codes 2xx returned by SLB to the client on the port.|Port|Count/second|1 minute|
        |Status codes 3xx on a port|The number of status codes 3xx returned by SLB to the client on the port.|Port|Count/second|1 minute|
        |Status codes 4xx on a port|The number of status codes 4xx returned by SLB to the client on the port.|Port|Count/second|1 minute|
        |Status codes 5xx on a port|The number of status codes 5xx returned by SLB to the client on the port.|Port|Count/second|1 minute|
        |Other status codes on a port|The number of other status codes returned by SLB to the client on the port.|Port|Count/second|1 minute|
        |Upstream status codes 4xx on a port|The number of status codes 4xx returned by RS to SLB on the port.|Port|Count/second|1 minute|
        |Upstream status codes 5xx on a port|The number of status codes 5xx returned by RS to the client on the port.|Port|Count/second|1 minute|
        |Upstream RT on a port|The average response time to requests from RS to the proxy on the port.|Port|Milliseconds|1 minute|
        |QPS on an instance|The QPS on the instance.|Instance|Count/second|1 minute|
        |RT on an instance|The average response time to requests on an instance.|Instance|Count/second|1 minute|
        |Status codes 2xx on an instance|The number of status codes 2xx returned by SLB to the client on the instance.|Instance|Count/second|1 minute|
        |Status codes 3xx on an instance|The number of status codes 3xx returned by SLB to the client on the instance.|Instance|Count/second|1 minute|
        |Status codes 4xx on an instance|The number of status codes 4xx returned by SLB to the client on the instance.|Instance|Count/second|1 minute|
        |Status codes 5xx on an instance|The number of status codes 5xx returned by SLB to the client on the instance.|Instance|Count/second|1 minute|
        |Other status codes on an instance|The number of other status codes returned by SLB to the client on the instance.|Instance|Count/second|1 minute|
        |Upstream status codes 4xx on the instance|The number of status codes 4xx returned by RS to SLB on the instance.|Instance|Count/second|1 minute|
        |Upstream status codes 5xx on an instance|The number of status codes 5xx returned by RS to SLB on the instance.|Instance|Count/second|1 minute|
        |Upstream RT on an instance|The average response time to requests from RS to the proxy on the instance.|Instance|Milliseconds|1 minute|

        **Note:** In the preceding table, new connections, active connections, and inactive connections refer to TCP connection requests sent from clients to SLB.

-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Server Load Balancer**. The Server Load Balancer page appears.
    3.  Click a region. All instances in the region appear in the instance list.
    4.  Click the ID of an instance or click **Monitoring Charts** in the **Actions** column for an instance to view the monitoring charts.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_cyl_4st_xdb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Server Load Balancer**. The Server Load Balancer page appears.
    3.  Click a region. All instances in the region appear in the instance list.
    4.  Click **Alarm Rules** in the **Actions** column for an instance to view the alert rules.
    5.  Click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the alert method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


