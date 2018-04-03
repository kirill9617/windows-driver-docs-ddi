---
UID: NS:d3d12umddi.D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041
title: D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041
author: windows-driver-content
description:
ms.assetid: b304f1ff-edff-46ce-8626-a2428c396c09
ms.author: windowsdriverdev
ms.date:
ms.topic: struct
ms.prod: windows-hardware
ms.technology: windows-devices
ms.keywords: D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041, D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041,
req.header: d3d12umddi.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.ddi-compliance:
req.unicode-ansi:
req.max-support:
req.typenames: D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041
topictype:
-	apiref
apitype:
-	HeaderDef
apilocation:
-	d3d12umddi.h
apiname:
-	D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041
product: Windows
targetos: Windows
---

# D3D12DDI_VIDEO_DECODE_OUTPUT_STREAM_ARGUMENTS_0041 structure

## -description

Output stream arguments for video decode.

## -struct-fields

### -field hDrvOutputTexture2D

The output texture. If decode conversion is enabled, this output specifies the post conversion output. If decode conversion is not enabled, this is the decode output.

### -field OutputSubresource

The output subresource to use for the <i>hDrvOutputTexture2D</i> parameter. If the output is an array, this allows specifying array indices.

### -field ConversionArguments

Optional output conversion arguments.

### -field Histograms

An array of D3D12DDI_VIDEO_DECODE_COMPONENT_HISTOGRAM_0041 structures.
