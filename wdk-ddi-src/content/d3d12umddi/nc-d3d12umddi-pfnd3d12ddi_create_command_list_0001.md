---
UID: NC:d3d12umddi.PFND3D12DDI_CREATE_COMMAND_LIST_0001
title: PFND3D12DDI_CREATE_COMMAND_LIST_0001 (d3d12umddi.h)
description: Creates a command list.
ms.assetid: ff7999b0-ba8c-4302-b1b8-a65d6ccb2822
ms.date: 10/19/2018
keywords: ["PFND3D12DDI_CREATE_COMMAND_LIST_0001 callback function"]
req.header: d3d12umddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
tech.root: display
ms.custom: RS5
f1_keywords:
 - "d3d12umddi/PFND3D12DDI_CREATE_COMMAND_LIST_0001"
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - d3d12umddi.h
api_name:
 - PFND3D12DDI_CREATE_COMMAND_LIST_0001
product:
 - Windows
dev_langs:
 - c++
---

# PFND3D12DDI_CREATE_COMMAND_LIST_0001 callback function

## -description

Creates a command list.

## -parameters

### -param Arg1

A handle to the display device (graphics context).

### -param Arg2

Pointer to a D3D12DDIARG_CREATE_COMMAND_LIST_0001 structure.

## -returns

Returns HRESULT.

## -prototype

```cpp
//Declaration

PFND3D12DDI_CREATE_COMMAND_LIST_0001 Pfnd3d12ddiCreateCommandList0001; 

// Definition

HRESULT Pfnd3d12ddiCreateCommandList0001 
(
	 D3D12DDI_HDEVICE
	CONST D3D12DDIARG_CREATE_COMMAND_LIST_0001 *
)
{...}

PFND3D12DDI_CREATE_COMMAND_LIST_0001 


```

