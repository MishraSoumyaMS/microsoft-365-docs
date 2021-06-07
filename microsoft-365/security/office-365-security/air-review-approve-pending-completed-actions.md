---
title: Review and manage remediation actions in Microsoft Defender for Office 365
keywords: AIR, autoIR, Microsoft Defender for Endpoint, automated, investigation, response, remediation, threats, advanced, threat, protection
f1.keywords: 
- NOCSH
author: JoeDavies-MSFT
ms.author: josephd
manager: dansimp
audience: ITPro
ms.topic: how-to
localization_priority: Normal
search.appverid: 
- MET150
- MOE150
ms.collection: 
- M365-security-compliance
- m365initiative-defender-office365
description: Learn about remediation actions in automated investigation and response capabilities in Microsoft Defender for Office 365 Plan 2.
ms.technology: mdo
ms.prod: m365-security
ms.date: 01/29/2021
---

# Review and manage remediation actions in Office 365

As automated investigations on email & collaboration content result in verdicts, such as *Malicious* or *Suspicious*, certain remediation actions are created. In Microsoft Defender for Office 365, remediation actions can include:
- Soft deleting email messages or clusters
- Turning off external mail forwarding

These remediation actions are not taken unless and until your security operations team approves them. We recommend reviewing and approving any pending actions as soon as possible so that your automated investigations complete in a timely manner.

**Applies to**
- [Microsoft Defender for Office 365 plan 2](defender-for-office-365.md)


## Approve (or reject) pending actions

1. Go to the Microsoft 365 security center (<https://security.microsoft.com/airinvestigation>) and sign in.
2. Open pending investigations 
4. Open pending actions tab
5. Review the information in the flyout pane, and then take one of the following steps:
   - Select **Approve** to initiate a pending action.
   - Select **Reject** to prevent a pending action from being taken.

6. All action entries can be seen under  <https://security.microsoft.com/threatincidents>

## Re-do actions 

1. Go to the Action center (<https://security.microsoft.com/threatincidents>) and sign in.
2. Select appropriate remediation.
3. In the flyout, click on the mail submissions entry and wait forthe list to load 
4. Wait for the action button to enable and click on the Action button on top to change the action type 
5. This will create appropriate actions

## Next steps

- [Use Threat Explorer](threat-explorer.md)
- [How to report false positives/negatives in automated investigation and response capabilities](air-report-false-positives-negatives.md)

## See also

- [View details and results of an automated investigation in Office 365](air-view-investigation-results.md)
