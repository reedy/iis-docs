﻿---
title: JobMetadata.TaskElement Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: TaskElement Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.JobMetadata.TaskElement
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.jobmetadata.taskelement(v=VS.90)
ms:contentKeyID: 35520696
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.JobMetadata.TaskElement
- Microsoft.Web.Media.TransformManager.JobMetadata.get_TaskElement
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.JobMetadata.get_TaskElement
- Microsoft.Web.Media.TransformManager.JobMetadata.TaskElement
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# TaskElement Property

Gets the task element from the manifest.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyTaskElementAsXElementGet
'Usage
DiminstanceAsJobMetadataDimvalueAsXElementvalue = instance.TaskElement
```

``` csharp
publicXElementTaskElement { get; }
```

``` c++
public:
virtualpropertyXElement^ TaskElement {
    XElement^ get () sealed;
}
```

``` fsharp
abstractTaskElement : XElementoverrideTaskElement : XElement
```

``` jscript
finalfunction getTaskElement () : XElement
```

#### Property Value

Type: [System.Xml.Linq. . :: . .XElement](https://msdn.microsoft.com/en-us/library/bb340098\(v=vs.90\))  
The task element.  

## See Also

#### Reference

[JobMetadata Class](jobmetadata-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
