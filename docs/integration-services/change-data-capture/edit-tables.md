---
title: "Edit Tables"
description: "Edit Tables"
author: chugugrace
ms.author: chugu
ms.date: "03/01/2017"
ms.service: sql
ms.subservice: integration-services
ms.topic: conceptual
f1_keywords:
  - "tabProps"
---
# Edit Tables

[!INCLUDE [oracle-cdc-retirement](../includes/attunity-oracle-cdc-retirement.md)]

  Use the **Tables** tab to make changes to the tables and columns that you selected from the Oracle source database. This tab has the following elements:  
  
 **Table list**  
 The table list has three columns:  
  
-   **Oracle Table Name**: The name of the table, including the table schema.  
  
-   **Capture Instance**: The name of the capture instance used to name instance-specific change data capture objects. The capture instance cannot be NULL. If not specified, the name is derived from the source schema name plus the source table name in the format `<schema-name>_<table-name>.` The capture instance name cannot exceed 100 characters and must be unique within the database. You can click in any cell in this column to manually edit the **capture_instance**.  
  
-   **Security Role**: The name of the database role used to gain access to change data. You can click in any cell in this column to manually edit the **security_role**.  
  
 **Add Tables**  
 Click **Add Tables** to open the Table Selection dialog box where you can [Add Tables to a CDC Instance](../../integration-services/change-data-capture/add-tables-to-a-cdc-instance.md). The first time this session that you access the Oracle database, you must [Connect to Oracle](../../integration-services/change-data-capture/connect-to-oracle.md).  
  
 **Edit**  
 Select a table from the list and select **Edit** to open the **Properties** dialog box for that table where you can [Edit the Table Properties](../../integration-services/change-data-capture/edit-the-table-properties.md).  
  
> [!NOTE]  
>  You cannot edit type mapping for tables that already have mirror tables. You can do this for new tables only.  
  
 **Remove**  
 Select a table from the list and click **Remove** to remove the table from the CDC instance.  
  
## See Also  
 [How to Edit the CDC Instance Properties](../../integration-services/change-data-capture/how-to-edit-the-cdc-instance-properties.md)   
 [Select Oracle Tables and Columns](../../integration-services/change-data-capture/select-oracle-tables-and-columns.md)  
  
  
