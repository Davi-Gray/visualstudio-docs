---
description: "Retrieves the user-displayable name for this context."
title: IDebugMemoryContext2::GetName | Microsoft Docs
ms.date: 11/04/2016
ms.topic: reference
f1_keywords:
- IDebugMemoryContext2::GetName
helpviewer_keywords:
- IDebugMemoryContext2::GetName method
- GetName method
ms.assetid: 8c212556-7d9e-4d68-b2a9-8212f50d0287
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-debug
ms.workload:
- vssdk
dev_langs:
- CPP
- CSharp
---
# IDebugMemoryContext2::GetName

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
Retrieves the user-displayable name for this context.

## Syntax

### [C#](#tab/csharp)
```csharp
int GetName(
   out string pbstrName
);
```
### [C++](#tab/cpp)
```cpp
HRESULT GetName( 
   BSTR* pbstrName
);
```
---

## Parameters
`pbstrName`\
[out] Returns the name of the memory context.

## Return Value
 If successful, returns `S_OK`; otherwise, returns an error code.

## Remarks
 The name of a memory context is not normally used.

## See also
- [IDebugMemoryContext2](../../../extensibility/debugger/reference/idebugmemorycontext2.md)
