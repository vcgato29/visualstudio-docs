---
title: "How to: Serialize Symbol Information | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.technology: "vs-ide-debug"
ms.topic: "conceptual"
f1_keywords: 
  - "VS.ToolsOptionsPages.Performance.General"
helpviewer_keywords: 
  - "profiling tools, serializing symbol information"
  - "performance tools, serializing symbol information"
ms.assetid: 9e0da706-6325-4073-83d1-aeab3b7c137a
author: "mikejo5000"
ms.author: "mikejo"
manager: douge
ms.workload: 
  - "multiple"
---
# How to: Serialize symbol information
You can serialize symbols that you must have to analyze your application. Symbol serialization adds symbols to the .*vsp* file. By adding symbol information to the .*vsp* file, others can analyze a performance report without having access to the original symbols. If symbols are not serialized, you must have original instrumented .*exe* and .*pdb* files to analyze the .*vsp* file.  
  
### To automatically serialize symbol information  
  
1.  On the **Tools** menu, click **Options**.  
  
     The **Options** dialog box is displayed.  
  
2.  Click **Performance Tools**.  
  
3.  Under **General Setting**, select **Automatically serialize symbol information**.  
  
## See also  
 [Configure performance sessions](../profiling/configuring-performance-sessions.md)   
 [How to: Reference Windows symbol information](../profiling/how-to-reference-windows-symbol-information.md)   
 [How to: Save analyzed report files](http://msdn.microsoft.com/en-us/0340ddde-caf4-48ac-8af3-d15dcdade556)