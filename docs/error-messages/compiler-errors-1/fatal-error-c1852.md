---
title: "Fatal Error C1852 | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: ["cpp-tools"]
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: ["C1852"]
dev_langs: ["C++"]
helpviewer_keywords: ["C1852"]
ms.assetid: fa011004-b8d6-46f1-ba80-4785e4ce137f
caps.latest.revision: 6
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
ms.workload: ["cplusplus"]
---
# Fatal Error C1852
'filename' is not a valid precompiled header file  
  
 The file is not a precompiled header.  
  
### To fix by checking the following possible causes  
  
1.  Invalid file specified with **/Yu** or **#pragma hdrstop**.  
  
2.  The compiler assumes a file extension of .pch if you do not specify otherwise.