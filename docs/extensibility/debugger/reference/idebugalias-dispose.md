---
title: "IDebugAlias::Dispose | Microsoft Docs"
ms.custom: ""
ms.date: "11/04/2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "vs-ide-sdk"
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "IDebugAlias::Dispose"
helpviewer_keywords: 
  - "IDebugAlias::Dispose method"
ms.assetid: e84909a4-d378-4f48-bf25-2c014c77c8e3
caps.latest.revision: 7
author: "gregvanl"
ms.author: "gregvanl"
manager: ghogen
---
# IDebugAlias::Dispose
Marks this alias for removal.  
  
## Syntax  
  
```cpp  
HRESULT Dispose();  
```  
  
```csharp  
int Dispose();  
```  
  
#### Parameters  
 None.  
  
## Return Value  
 If successful, returns S_OK; otherwise, returns an error code.  
  
## Remarks  
 Once this method is called, the alias is no longer available.  
  
## See Also  
 [IDebugAlias](../../../extensibility/debugger/reference/idebugalias.md)