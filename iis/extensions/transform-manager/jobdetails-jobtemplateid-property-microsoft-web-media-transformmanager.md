---
title: JobDetails.JobTemplateId Property  (Microsoft.Web.Media.TransformManager)
TOCTitle: JobTemplateId Property
ms:assetid: P:Microsoft.Web.Media.TransformManager.JobDetails.JobTemplateId
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.transformmanager.jobdetails.jobtemplateid(v=VS.90)
ms:contentKeyID: 35520763
ms.date: 06/14/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Media.TransformManager.JobDetails.get_JobTemplateId
- Microsoft.Web.Media.TransformManager.JobDetails.JobTemplateId
- Microsoft.Web.Media.TransformManager.JobDetails.set_JobTemplateId
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.TransformManager.Common.dll
api_name:
- Microsoft.Web.Media.TransformManager.JobDetails.get_JobTemplateId
- Microsoft.Web.Media.TransformManager.JobDetails.JobTemplateId
- Microsoft.Web.Media.TransformManager.JobDetails.set_JobTemplateId
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# JobTemplateId Property

Gets or sets the ID of the job template that defines the tasks for this job.

**Namespace:**  [Microsoft.Web.Media.TransformManager](microsoft-web-media-transformmanager-namespace.md)  
**Assembly:**  Microsoft.Web.Media.TransformManager.Common (in Microsoft.Web.Media.TransformManager.Common.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property JobTemplateId As String
    Get
    Set
'Usage

  Dim instance As JobDetails
Dim value As String

value = instance.JobTemplateId

instance.JobTemplateId = value
```

``` csharp
[DataMemberAttribute]
public string JobTemplateId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ JobTemplateId {
    String^ get ();
    void set (String^ value);
}
```

``` fsharp
[<DataMemberAttribute>]
member JobTemplateId : string with get, set
```

``` jscript
  function get JobTemplateId () : String
function set JobTemplateId (value : String)
```

#### Property Value

Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
The ID of the job template that defines the tasks for this job.  

## See Also

#### Reference

[JobDetails Class](jobdetails-class-microsoft-web-media-transformmanager.md)

[Microsoft.Web.Media.TransformManager Namespace](microsoft-web-media-transformmanager-namespace.md)
