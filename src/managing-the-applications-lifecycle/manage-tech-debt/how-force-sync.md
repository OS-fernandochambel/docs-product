---
tags: 
summary: Learn how to request a synchonization between the probe and AI Mentor Studio.
locale: en-us
guid: b67d9ffc-b28f-4e00-8ffc-6544f9d66812
app_type: traditional web apps, mobile apps, reactive web apps
---

# How to request a synchronization

<div class="info" markdown="1">

Architecture Dashboard is now AI Mentor Studio.

</div>

Synchronization of data between the AI Mentor Studio LifeTime probe and the AI Mentor Studio SaaS occurs every 12 hours, but you may also request unscheduled synchronizations. 

<div class="info" markdown="1">

There's a daily limit to the number of unscheduled synchronization requests that AI Mentor Studio can process for each infrastructure. You can request 5 synchronization requests per day.

</div>

To force a synchronization, follow these steps:

1. Go to theAI Mentor Studio LifeTime plugin (`https://<lifetime_environment>/ArchitectureDashboardProbe/`) and select **Monitor**.

    ![Select Monitor](images/sync-plugin-monitor-lt.png)

1. Select **Request Synchronization**.

    ![Request synchronization](images/sync-plugin-request-lt.png)

After these steps, the synchronization request enters the **Outbound Queue** as **SyncRequest**.

<div class="info" markdown="1">

Select **Refresh** to update the queues and check changes to the status of **SyncRequest**.

</div>
