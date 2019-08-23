# Auto Scaling {#concept_oxw_1rd_zdb .concept}

CloudMonitor provides multiple metrics, such as the minimum and maximum numbers of instances, to help you monitor the status of Auto Scaling. CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase Auto Scaling, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_rbs_4td_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |Minimum number of instances|User and scaling group|Count|5 minutes|
    |Maximum number of instances|User and scaling group|Count|5 minutes|
    |Total instances|User and scaling group|Count|5 minutes|
    |Running instances|User and scaling group|Count|5 minutes|
    |Instances being added|User and scaling group|Count|5 minutes|
    |Instances being removed|User and scaling group|Count|5 minutes|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Auto Scaling**. The Alibaba Cloud Auto Scaling page appears.
    3.  Click the name of a scaling group or click **Monitoring Charts** in the **Actions** column for a scaling group to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_vvn_dwd_zdb .section}

-   **Set alert rules for a single scaling group** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Auto Scaling**. The Alibaba Cloud Auto Scaling page appears.
    3.  Click the name of a scaling group or click **Monitoring Charts** in the **Actions** column for a scaling group to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Set alert rules for multiple scaling groups at a time** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **Auto Scaling**. The Alibaba Cloud Auto Scaling page appears.
    3.  Select target scaling groups and click **Set Alarm Rules** under the list to set alert rules for the selected scaling groups.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


