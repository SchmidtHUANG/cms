# Function Compute {#concept_zbp_mc2_zdb .concept}

CloudMonitor provides multiple service-level and function-level metrics, such as the total invocations, average duration, and request status distribution, to help you monitor the status of Function Compute. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase Function Compute, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_zqh_pd2_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |BillableInvocations|User, service, and function|Count|1 minute|
    |BillableInvocationsRate|User, service, and function|Percentage|1 minute|
    |ClientErrors|User, service, and function|Count|1 minute|
    |ClientErrorsRate|User, service, and function|Percentage|1 minute|
    |ServerErrors|User, service, and function|Count|1 minute|
    |ServerErrorsRate|User, service, and function|Percentage|1 minute|
    |Throttles|User, service, and function|Count|1 minute|
    |ThrottlesRate|User, service, and function|Percentage|1 minute|
    |TotalInvocations|User, service, and function|Count|1 minute|
    |Average duration|User, service, and function|Milliseconds|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Function Compute**. On the Function Compute page that appears, you can view the overall status of Function Compute.
    3.  Click the **Service List** tab to view the service-level or function-level monitoring information.

## Alerting service {#section_av5_bf2_zdb .section}

CloudMonitor allows you to set alert rules for the metrics of Function Compute so that you can receive alerts when any exception occurs.

-   **Set alert rules for a single service** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Function Compute**. The Function Compute page appears.
    3.  Click the **Alarm Rules** tab and then click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple services at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Function Compute**. The Function Compute page appears.
    3.  Click the **Service List** tab.
    4.  Select target services and click **Set Alarm Rules** under the list to set alert rules for the selected services.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


