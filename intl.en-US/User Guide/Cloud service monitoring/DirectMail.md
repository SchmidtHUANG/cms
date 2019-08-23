# DirectMail {#concept_pwd_g2d_zdb .concept}

CloudMonitor provides multiple metrics, such as metrics about the Web or API messaging sending method, Simple Mail Transfer Protocol \(SMTP\) message sending method, and abnormal accounts, to help you monitor the status of DirectMail. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase DirectMail, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_ycm_n2d_zdb .section}

-   **Metrics** 

    |Metric|Unit|Minimum frequency|
    |:-----|:---|:----------------|
    |Web or API over-length-error QPS|Count/minute|1 minute|
    |Web/API over-quota-error QPS|Count/minute|1 minute|
    |Web/API spam QPS|Count/minute|1 minute|
    |Web/API success QPS|Count/minute|1 minute|
    |SMTP authentication failure QPS|Count/minute|1 minute|
    |SMTP authentication success QPS|Count/minute|1 minute|
    |SMTP over-length-error QPS|Count/minute|1 minute|
    |SMTP over-quota-error QPS|Count/minute|1 minute|
    |SMTP spam QPS|Count/minute|1 minute|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **DirectMail**. On the DirectMail page that appears, you can view the metrics of DirectMail.

## Alerting service {#section_lvy_fgd_zdb .section}

CloudMonitor allows you to set alert rules for the metrics of DirectMail so that you can receive alerts when any exception occurs.

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **DirectMail**. The DirectMail page appears.
    3.  Click the **Alarm Rules** tab and then click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


