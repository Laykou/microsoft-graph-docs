---
title: "Mailbox usage reports"
description: "You can get information about users with a mailbox and their level of activity which is primarily based on emails sent and received. You can also see how much storage each mailbox consumes and how many mailboxes are approaching storage quotas."
localization_priority: Normal
author: "pranoychaudhuri"
ms.prod: "reports"
---

# Mailbox usage reports

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

You can get information about users with a mailbox and their level of activity which is primarily based on emails sent and received. You can also see how much storage each mailbox consumes and how many mailboxes are approaching storage quotas.

> **Note:** For details about different report views and names, see [Office 365 Reports - Mailbox usage](https://support.office.com/client/Mailbox-usage-beffbe01-ce2d-4614-9ae5-7898868e2729).

## Reports

| Function                                 | CSV return type | JSON return type                         | Description                              |
| :--------------------------------------- | :-------------- | :--------------------------------------- | ---------------------------------------- |
| [Get mailbox detail](../api/reportroot-getmailboxusagedetail.md) | Stream          | [mailboxUsageDetail](../resources/mailboxusagedetail.md) | Get details about mailbox usage.         |
| [Get mailbox counts](../api/reportroot-getmailboxusagemailboxcounts.md) | Stream          | [mailboxUsageMailboxCounts](../resources/mailboxusagemailboxcounts.md) | Get the total number of user mailboxes in your organization and how many are active each day of the reporting period. A mailbox is considered active if the user sent or read any email. |
| [Get quota status mailbox counts](../api/reportroot-getmailboxusagequotastatusmailboxcounts.md) | Stream          | [mailboxUsageQuotaStatusMailboxCounts](../resources/mailboxusagequotastatusmailboxcounts.md) | Get the count of user mailboxes in each quota category. |
| [Get storage](../api/reportroot-getmailboxusagestorage.md) | Stream          | [mailboxUsageStorage](../resources/mailboxusagestorage.md) | Get the amount of storage used in your organization. |
<!--
{
  "type": "#page.annotation",
  "suppressions": [
    "Error: /api-reference/beta/resources/mailbox-usage-reports.md:\r\n      Exception processing links.\r\n    System.ArgumentException: Link Definition was null. Link text: !INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)\r\n      at ApiDoctor.Validation.DocFile.get_LinkDestinations()\r\n      at ApiDoctor.Validation.DocSet.ValidateLinks(Boolean includeWarnings, String[] relativePathForFiles, IssueLogger issues, Boolean requireFilenameCaseMatch, Boolean printOrphanedFiles)"
  ]
}
-->