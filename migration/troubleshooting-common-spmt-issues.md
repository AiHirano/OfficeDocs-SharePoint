---
title: "Troubleshooting SharePoint Migration Tool"
ms.author: jhendr
author: JoanneHendrickson
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ms.prod: sharepoint-server-itpro
localization_priority: Priority
ms.collection: 
- IT_Sharepoint_Server_Top
- Strat_SP_gtc
- SPMigration
search.appverid: MET150
ms.custom: 
description: "How to troubleshoot common errors in the SharePoint Migration Tool."
---

## Troubleshooting common SPMT errors
|**Error Code**|**Recommended action**|
|:-----|:-----|
|0x0201000D|Check if the list exists or if you can access it in the source site and target site.|
|0x02050008|Unable to access your local storage.  Restart your migration.|
|0x02010023|Your source list template is not supported.  Please try another.|
|0x0201000C|Check your credentials and then re-enter your username and password.|
|0x02010017|You must be a site collection admin.|
|0x02060009| 1 - The site collection cannot be created because the URL is already in use or an invalid URL.|
|| 2 -  The site collection cannot be created because the URL contains invalid character.|
|| 3 -  The site collection cannot be created or updated.|
|0x02010018| 1 - Check your credentials and then try again.|
|| 2 -  A problem occurred accessing SharePoint.  Check your credentials and try again.|
|| 3 - A problem occurred accessing SharePoint.  Check your credentials and your network connection and try again.|
|| 4 - A problem occurred accessing SharePoint.  Check your credentials and your site URL for accuracy and try again.|
|| 5 - A problem occurred accessing SharePoint.  Check your credentials and the format of your URL. Retry.|
|| 6 - A problem occurred accessing SharePoint.  Check your credentials and try again.  If the problem continues, please create a support case.|
|| 7 - A problem occurred accessing SharePoint.  Check your credentials and try opening your site in a browser.|
|0x0204000A|Cannot create package file. All files and folders in the SPMT working folder, *%appdata%\Microsoft\MigrationToolStorage*, must be closed. Restart your migration.|
|0x02030001|1 - Check your credentials.  Restart your migration. 
|| 2 - Check your credentials. Restart your migration.
|| 3 - Check your credentials and your network connection. Restart your migration. 
|| 4 - Check your credentials and your site URL. Restart your migration.
|| 5 - Check your credentials and the format of your URL.  Restart your migration.
|| 6 - Check your credentials and restart your migration.  If this continues, please a support case.
|| 7 - Check your credentials and try opening your site in a browser. Restart your migration.|
|0x02010008|Confirm the path and format of the user mapping file and that you have permission to access it.|
|0x02050001|All files and folders in the SPMT working folder, *%appdata%\Microsoft\MigrationToolStorage*, must be closed. Restart your migration.|
|0x02010002|Check your network status.  If you can access the source sites from a browser, then create a support case.|
|0x02010010|Make sure the source list and target list have the same template. |
|0x0204000D|All files and folders in the SPMT working folder, *%appdata%\Microsoft\MigrationToolStorage*, must be closed during migration. Restart your migration.|
|0x02080001|The file in the package has been changed or deleted while uploading. All files and folders in the SPMT working folder, %appdata%\Microsoft\MigrationToolStorage, must be closed. Restart your migration.|
|0x02010006|The source SharePoint site does not have any defined role definitions. Check to see if your role exists when accessing source site.|
|0x02040009|The package can’t be created because the directory cannot be found.  All files and folders in the SPMT working folder, %appdata%\Microsoft\MigrationToolStorage, must be closed. Restart your migration.|
|0x02010020|Disable migrating version history in SPMT settings or enable versioning in SPO.|
|0x0201000E|Check if the global setting has filtered out special characters in the target path or if the path has unsupported characters.|
|0x02010016|We are unable to find your SharePoint Server user.  Make sure you are a site collection admin.|
