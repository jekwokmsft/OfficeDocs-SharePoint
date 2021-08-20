---
title: "Step 3: Copy to migrations for file share migration"
ms.reviewer: 
ms.author: jhendr
author: JoanneHendrickson
manager: serdars
audience: ITPro
f1.keywords:
- NOCSH
ms.topic: article
ms.service: sharepoint-online
localization_priority: Priority
ms.collection:
- m365solution-migratefileshares
- m365solution-migratetom365
- m365solution-scenario 
- M365-collaboration
- SPMigration
search.appverid: MET150to the migration list in Migration Manager."
---

# Step 3: Copy to migrations

After a file share has been scanned and determined ready, add it to your migration list.  

1. Highlight one or rows from the scanned list. From the menu bar, select **Copy to migrations**. </br></br>

    ![File share scan list](media/mm-fileshare-scan-list.png)
</br>

2. Add a destination -- OneDrive, SharePoint or Teams. Select **Next**.
3.  Select a SharePoint site destination.  Enter the site path and the location within the site from the dropdown list. Select **Next**.

   ![Select a destination for your file share](media/mm-fileshare-copy-migrations-destinations.png)

4. Depending on the destination you selected: 
    - For OneDrive, enter the a OneDrive URL or email address and the location/folder name
    - For SharePoint, enter site URL and location
    - For Teams, select the team and the channel

4. Under configure settings, enter a friendly name for your migration. 
5. Select an agent group and then review and edit your settings as needed.
6. If you choose **Run later**, select a date and time, and then select **Schedule.**
7. If you choose **Run now**, select **Run**.

![Configure settings for your file share migration](media/mm-fileshare-copy-migrations-configure-settings-page.png)



>[!NOTE]
>Migration Manager for file shares isn't available for users of Office 365 operated by 21Vianet in China. It's also not available for users of Microsoft 365 with the German cloud that use the data trustee *German Telekom*. 
>
>It is supported for users in Germany whose data location isn't in the German datacenter.
>
> This feature is not supported for users of the Government Cloud, including GCC, Consumer, GCC High, or DoD.