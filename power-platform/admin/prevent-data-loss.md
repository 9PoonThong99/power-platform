---
title: Manage data loss prevention (DLP) policies | Microsoft Docs
description: Walkthrough of how to manage data loss prevention policies for Power Apps.
author: manasmams
manager: kvivek
ms.service: power-platform
ms.component: pa-admin
ms.topic: conceptual
ms.date: 03/21/2018
ms.author: manasma
search.audienceType: 
  - admin
search.app: 
  - D365CE
  - PowerApps
  - Powerplatform
---

# Manage data loss prevention (DLP) policies
An organization's data is critical to its success. Its data needs to be readily available for decision-making, but it needs to be protected so that it isn't shared with audiences that shouldn't have access to it. To protect this data, Power Apps lets you create and enforce data loss prevention (DLP) policies that define which consumer connectors specific business data can be shared with. For example, an organization that uses Power Apps may not want its business data that's stored in SharePoint to be automatically published to its Twitter feed.

To create, edit, or delete DLP policies, you must have either Environment Admin or Power Platform service admin permissions. For more information, see [Environments administration in Power Apps](environments-administration.md).

For instructions on how to create a DLP policy, see [Create a data loss prevention (DLP) policy](create-dlp-policy.md).

## Find a DLP policy
1. Sign in to the Admin center at [https://admin.powerapps.com](https://admin.powerapps.com).
2. In the navigation pane, click or tap **Data policies**. If you have a long list of policies, use the **Search** box to find specific DLP policies.

    ![](./media/prevent-data-loss/data-policies.png)

## Edit a DLP policy
1. In the list of data loss prevention policies, click or tap the pencil icon next to the policy you want to edit.

    ![Sign in](./media/prevent-data-loss/3.png)
2. Make your changes, and then click or tap **Save Policy**.

    > [!NOTE]
    > Environment DLP policies cannot override tenant-wide DLP policies.
    >
    >

    To review the changes, find the DLP policy in the list of data loss prevention policies and click or tap it to review its properties.

## Delete a DLP policy
1. In the list of data loss prevention policies, click or tap the trash can icon next to the policy you want to delete.

    ![Sign in](./media/prevent-data-loss/3-delete.png)
4. In the confirmation dialog box, click or tap **Delete**.

    The policy is deleted and no longer appears in the list of data loss prevention policies.

## Next steps
* [Learn more about environments](environments-administration.md)
* [Learn more about Microsoft Power Apps](/powerapps/maker/canvas-apps/getting-started)
