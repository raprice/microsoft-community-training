---
title: Delete your training platform instance
original-url: https://docs.microsoftcommunitytraining.com/docs/delete-your-training-instance
author: nikotha
ms.author: nikotha
description: When you no longer need your training portal, you can delete it by deleting the resource group from the Azure portal.
ms.prod: learning-azure
---

# Delete your training platform instance

When you no longer need your training portal, you can delete it by deleting the resource group from the Azure portal.

1. In the Azure portal, navigate to Resource groups in the left navigation pane.

   ![Navigate Resource groups](../../media/image%2823%29.png)

2. From the list of resource groups, click on the resource group belonging to your Microsoft Community Training instance

    >[!Note]
    >There are two types of Resource Groups - Managed Resource Group and Parent Resource Group.
    >
    >Deleting Managed Resource Group is not allowed and what you need to delete is the Parent Resource Group – which will then itself delete the managed resource group as well.
    >
    >You may identify the Parent and Managed Resource Group using below description:
    >
    > * Parent Resource Group – Will have just one resource in it.
    > * Managed Resource Group – Will have multiple resources (typically more than 10)
    >
    > **Example of Parent Resource Group:**
    >
    >![Parent Resource group](../../media/ExampleParentResourceGrp.png)

3. Select **Delete resource group**. Verify deletion by entering the resource group name and select Delete.

   ![Delete resource group](../../media/image%2887%29.png)

> [!WARNING]  
> Once you delete your learning portal resource group, you will lose all data and it cannot be recovered.
