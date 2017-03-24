---
title: "Configure Data Streaming Destination | Microsoft Docs"
ms.date: "03/01/2017"
ms.prod: "sql-server-2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "integration-services"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "SQL11.DTS.DESIGNER.DATASTREAMINGDEST.F1"
ms.assetid: bcdbb833-20c8-47ff-a641-bb517f9a1af3
caps.latest.revision: 7
author: "douglaslMS"
ms.author: "douglasl"
manager: "jhubbard"
---
# Configure Data Streaming Destination
  Configure the Data Streaming Destination by using the **Advanced Editor for Data Streaming Destination** dialog box. Open this dialog box by double clicking the component or by right-clicking the component in the data flow designer and then clicking **Edit**.  
  
 This dialog box has three tabs: **Component Properties**, **Input Columns**, and **Input and Output Properties**.  
  
## Component Properties tab  
 This tab has the following editable fields:  
  
|Field|Description|  
|-----------|-----------------|  
|Name|Name of the data streaming destination component in the package.|  
|ValidateExternalMetadata|Indicates whether the component is validated using external data sources at design time. If set to false, validation against external data sources is delayed until runtime.|  
|IDColumnName|The view generated by the Data Feed Publish Wizard has this additional ID column. The ID column serves as the EntityKey for the output data from the data flow when the data is consumed as an OData feed by other applications.<br /><br /> The default name for this column is _ID. You can specify a different name for the ID column.|  
  
## Input Columns tab  
 In the top pane of this tab, you see all the available input columns. Select the columns that you want to include in the output of this component. The selected columns are displayed in a list in the bottom pane. You can change the name of the output column by entering the new name for the **Output Alias** field in the list.  
  
## Input Output Properties tab  
 Similar to the Input Columns tab, you can change names of output columns in this tab. In the tree view to the left, expand **Data Streaming Destination Input** and then expand **Input Columns**. Click the input column name and change the name of the output column name in the right pane.  
  
## See Also  
 [Data Streaming Destination](../../integration-services/data-flow/data-streaming-destination.md)   
 [Walkthrough: Publish an SSIS Package as a SQL View](../../integration-services/data-flow/walkthrough-publish-an-ssis-package-as-a-sql-view.md)  
  
  