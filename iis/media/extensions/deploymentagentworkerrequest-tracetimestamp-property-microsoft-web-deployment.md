﻿---
title: DeploymentAgentWorkerRequest.TraceTimestamp Property  (Microsoft.Web.Deployment)
TOCTitle: TraceTimestamp Property
ms:assetid: P:Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.TraceTimestamp
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentagentworkerrequest.tracetimestamp(v=VS.90)
ms:contentKeyID: 20209093
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.TraceTimestamp
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.get_TraceTimestamp
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.get_TraceTimestamp
- Microsoft.Web.Deployment.DeploymentAgentWorkerRequest.TraceTimestamp
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# TraceTimestamp Property

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicMustOverrideReadOnlyPropertyTraceTimestampAsDateTime
'Usage
DiminstanceAsDeploymentAgentWorkerRequestDimvalueAsDateTimevalue = instance.TraceTimestamp
```

``` csharp
publicabstractDateTimeTraceTimestamp { get; }
```

``` c++
public:
virtualpropertyDateTimeTraceTimestamp {
    DateTimeget () abstract;
}
```

``` jscript
abstractfunction getTraceTimestamp () : DateTime
```

#### Property Value

Type: [System. . :: . .DateTime](https://msdn.microsoft.com/en-us/library/03ybds8y\(v=vs.90\))  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentAgentWorkerRequest Class](deploymentagentworkerrequest-class-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
