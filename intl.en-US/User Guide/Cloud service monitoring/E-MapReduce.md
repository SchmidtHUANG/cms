# E-MapReduce {#concept_dcn_bpd_zdb .concept}

CloudMonitor provides multiple metrics, such as the CPU idle rate, memory capacity, and disk capacity, to help you monitor the status of Elastic MapReduce \(E-MapReduce\). CloudMonitor also allows you to set alert rules for these metrics so that you can receive alerts when any exception occurs.

After you purchase E-MapReduce, CloudMonitor automatically collects data based on these metrics.

## Monitoring service {#section_ozm_fpd_zdb .section}

-   **Metrics** 

    |Metric|Dimension|Unit|Minimum frequency|
    |:-----|:--------|:---|:----------------|
    |Inbound traffic rate|User, cluster, and role|bit/s|30 seconds|
    |Outbound traffic rate|User, cluster, and role|bit/s|30 seconds|
    |CPU idle rate|User, cluster, and role|Percentage|1 minute|
    |User-mode CPU usage|User, cluster, and role|Percentage|30 seconds|
    |System-mode CPU usage|User, cluster, and role|Percentage|30 seconds|
    |Idle disk capacity|User, cluster, and role|Bytes|30 seconds|
    |Total disk capacity|User, cluster, and role|Bytes|30 seconds|
    |15-minute load average|User, cluster, and role|-|30 seconds|
    |5-minute load average|User, cluster, and role|-|30 seconds|
    |1-minute load average|User, cluster, and role|-|30 seconds|
    |Idle memory capacity|User, cluster, and role|Bytes|30 seconds|
    |Total memory capacity|User, cluster, and role|Bytes|30 seconds|
    |Received packets per second|User, cluster, and role|PPS|30 seconds|
    |Transmitted packets per second|User, cluster, and role|PPS|30 seconds|
    |Running processes|User, cluster, and role|Count|30 seconds|
    |Total processes|User, cluster, and role|Count|30 seconds|
    |Blocked processes|User, cluster, and role|Count|30 seconds|
    |Created processes or threads|User, cluster, and role|Count|30 seconds|
    |MemNonHeapUsedM|User, cluster, and role|Bytes|30 seconds|
    |MemNonHeapCommittedM|User, cluster, and role|Bytes|30 seconds|
    |MemNonHeapMaxM|User, cluster, and role|Bytes|30 seconds|
    |MemHeapUsedM|User, cluster, and role|Bytes|30 seconds|
    |MemHeapCommittedM|User, cluster, and role|Bytes|30 seconds|
    |MemHeapMaxM|User, cluster, and role|Bytes|30 seconds|
    |MemMaxM|User, cluster, and role|Bytes|30 seconds|
    |ThreadsNew|User, cluster, and role|-|30 seconds|
    |ThreadsRunnable|User, cluster, and role|-|30 seconds|
    |ThreadsBlocked|User, cluster, and role|-|30 seconds|
    |ThreadsWaiting|User, cluster, and role|-|30 seconds|
    |ThreadsTimedWaiting|User, cluster, and role|-|30 seconds|
    |ThreadsTerminated|User, cluster, and role|-|30 seconds|
    |GcCount|User, cluster, and role|-|30 seconds|
    |GcTimeMillis|User, cluster, and role|-|30 seconds|
    |CallQueueLength|User, cluster, and role|-|30 seconds|
    |NumOpenConnections|User, cluster, and role|-|30 seconds|
    |ReceivedByte|User, cluster, and role|-|30 seconds|
    |SentByte|User, cluster, and role|-|30 seconds|
    |BlockCapacity|User, cluster, and role|-|30 seconds|
    |BlocksTotal|User, cluster, and role|-|30 seconds|
    |CapacityRemaining|User, cluster, and role|-|30 seconds|
    |CapacityTotal|User, cluster, and role|-|30 seconds|
    |CapacityUsed|User, cluster, and role|-|30 seconds|
    |CapacityUsedNonDFS|User, cluster, and role|-|30 seconds|
    |CorruptBlocks|User, cluster, and role|-|30 seconds|
    |ExcessBlocks|User, cluster, and role|-|30 seconds|
    |ExpiredHeartbeats|User, cluster, and role|-|30 seconds|
    |MissingBlocks|User, cluster, and role|-|30 seconds|
    |PendingDataNodeMessageCount|User, cluster, and role|-|30 seconds|
    |PendingDeletionBlocks|User, cluster, and role|-|30 seconds|
    |PendingReplicationBlocks|User, cluster, and role|-|30 seconds|
    |PostponedMisreplicatedBlocks|User, cluster, and role|-|30 seconds|
    |ScheduledReplicationBlocks|User, cluster, and role|-|30 seconds|
    |TotalFiles|User, cluster, and role|-|30 seconds|
    |TotalLoad|User, cluster, and role|-|30 seconds|
    |UnderReplicatedBlocks|User, cluster, and role|-|30 seconds|
    |BlocksRead|User, cluster, and role|-|30 seconds|
    |BlocksRemoved|User, cluster, and role|-|30 seconds|
    |BlocksReplicated|User, cluster, and role|-|30 seconds|
    |BlocksUncached|User, cluster, and role|-|30 seconds|
    |BlocksVerified|User, cluster, and role|-|30 seconds|
    |BlockVerificationFailures|User, cluster, and role|-|30 seconds|
    |BlocksWritten|User, cluster, and role|-|30 seconds|
    |ByteRead|User, cluster, and role|-|30 seconds|
    |ByteWritten|User, cluster, and role|-|30 seconds|
    |FlushNanosAvgTime|User, cluster, and role|-|30 seconds|
    |FlushNanosNumOps|User, cluster, and role|-|30 seconds|
    |FsyncCount|User, cluster, and role|-|30 seconds|
    |VolumeFailures|User, cluster, and role|-|30 seconds|
    |ReadBlockOpNumOps|User, cluster, and role|-|30 seconds|
    |ReadBlockOpAvgTime|User, cluster, and role|Milliseconds|30 seconds|
    |WriteBlockOpNumOps|User, cluster, and role|-|30 seconds|
    |WriteBlockOpAvgTime|User, cluster, and role|Milliseconds|30 seconds|
    |BlockChecksumOpNumOps|User, cluster, and role|-|30 seconds|
    |BlockChecksumOpAvgTime|User, cluster, and role|Milliseconds|30 seconds|
    |CopyBlockOpNumOps|User, cluster, and role|-|30 seconds|
    |CopyBlockOpAvgTime|User, cluster, and role|Milliseconds|30 seconds|
    |ReplaceBlockOpNumOps|User, cluster, and role|-|30 seconds|
    |ReplaceBlockOpAvgTime|User, cluster, and role|Milliseconds|30 seconds|
    |BlockReportsNumOps|User, cluster, and role|-|30 seconds|
    |BlockReportsAvgTime|User, cluster, and role|Milliseconds|30 seconds|
    |NodeManager\_AllocatedContainers|User, cluster, and role|-|30 seconds|
    |ContainersCompleted|User, cluster, and role|-|30 seconds|
    |ContainersFailed|User, cluster, and role|-|30 seconds|
    |ContainersIniting|User, cluster, and role|-|30 seconds|
    |ContainersKilled|User, cluster, and role|-|30 seconds|
    |ContainersLaunched|User, cluster, and role|-|30 seconds|
    |ContainersRunning|User, cluster, and role|-|30 seconds|
    |ActiveApplications|User, cluster, and role|-|30 seconds|
    |ActiveUsers|User, cluster, and role|-|30 seconds|
    |AggregateContainersAllocated|User, cluster, and role|-|30 seconds|
    |AggregateContainersReleased|User, cluster, and role|-|30 seconds|
    |AllocatedContainers|User, cluster, and role|-|30 seconds|
    |AppsCompleted|User, cluster, and role|-|30 seconds|
    |AppsFailed|User, cluster, and role|-|30 seconds|
    |AppsKilled|User, cluster, and role|-|30 seconds|
    |AppsPending|User, cluster, and role|-|30 seconds|
    |AppsRunning|User, cluster, and role|-|30 seconds|
    |AppsSubmitted|User, cluster, and role|-|30 seconds|
    |AvailableMB|User, cluster, and role|-|30 seconds|
    |AvailableVCores|User, cluster, and role|-|30 seconds|
    |PendingContainers|User, cluster, and role|-|30 seconds|
    |ReservedContainers|User, cluster, and role|-|30 seconds|

    **Note:** 

    -   Monitoring data is retained for up to 31 days.
    -   You can view the monitoring data for up to 14 consecutive days.
-   **View monitoring data** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **E-MapReduce**. The E-MapReduce Monitoring List page appears.
    3.  Click the ID of a cluster or click **Monitoring Charts** in the **Actions** column for a cluster to view the monitoring charts.
    4.  In **Time Range**, select a preset time period or customize a time period. You can view the monitoring data for up to 14 consecutive days.
    5.  Optional. Click the zoom-in icon in the upper-right corner of a monitoring chart to enlarge the chart.

## Alerting service {#section_z1k_fqd_zdb .section}

-   **Set alert rules** 
    1.  Log on to the [CloudMonitor console](https://partners-intl.console.aliyun.com/#/cms).
    2.  In the left-side navigation pane, choose **Cloud Service Monitoring** \> **E-MapReduce**. The E-MapReduce Monitoring List page appears.
    3.  Click the ID of a cluster or click **Monitoring Charts** in the **Actions** column for a cluster to view the monitoring charts.
    4.  Click the bell icon in the upper-right corner of a monitoring chart or click **Create Alarm Rule** in the upper-right corner of the page. Specify the resource range, set alert rules, set the notification method, and then click **Confirm**.
-   **Parameters** 

    For more information about alert rule parameters, see [Alarm rule parameters](reseller.en-US/User Guide/Alarm service/Alarm rules/Alarm rule parameters.md#).


