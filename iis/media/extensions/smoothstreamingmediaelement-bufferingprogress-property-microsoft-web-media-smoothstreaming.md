﻿---
title: SmoothStreamingMediaElement.BufferingProgress Property  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: BufferingProgress Property
ms:assetid: P:Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.BufferingProgress
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.smoothstreamingmediaelement.bufferingprogress(v=VS.90)
ms:contentKeyID: 23961214
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.BufferingProgress
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.get_BufferingProgress
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.BufferingProgress
- Microsoft.Web.Media.SmoothStreaming.SmoothStreamingMediaElement.get_BufferingProgress
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# BufferingProgress Property

Gets or sets the buffering progress. (This property is available only for Windows Phone clients, not for Silverlight.)

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyBufferingProgressAsDouble
'Usage
DiminstanceAsSmoothStreamingMediaElementDimvalueAsDoublevalue = instance.BufferingProgress
```

``` csharp
publicdoubleBufferingProgress { get; }
```

``` c++
public:
propertydoubleBufferingProgress {
    doubleget ();
}
```

``` jscript
function getBufferingProgress () : double
```

#### Property Value

Type: [System. . :: . .Double](https://msdn.microsoft.com/en-us/library/643eft0t\(v=vs.90\))  
A value that indicates the buffering progress as a percentage.  

## Version Information

#### Silverlight

Supported in: 4  

#### Silverlight for Windows Phone

Supported in: Windows Phone OS 7.0  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[SmoothStreamingMediaElement Class](smoothstreamingmediaelement-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
