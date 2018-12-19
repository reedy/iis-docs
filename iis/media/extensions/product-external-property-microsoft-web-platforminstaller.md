﻿---
title: Product.External Property  (Microsoft.Web.PlatformInstaller)
TOCTitle: External Property
ms:assetid: P:Microsoft.Web.PlatformInstaller.Product.External
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.platforminstaller.product.external(v=VS.90)
ms:contentKeyID: 22049770
ms.date: 05/02/2012
mtps_version: v=VS.90
f1_keywords:
- Microsoft.Web.PlatformInstaller.Product.External
- Microsoft.Web.PlatformInstaller.Product.get_External
dev_langs:
- CSharp
- JScript
- VB
- c++
api_location:
- Microsoft.Web.PlatformInstaller.dll
api_name:
- Microsoft.Web.PlatformInstaller.Product.External
- Microsoft.Web.PlatformInstaller.Product.get_External
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# External Property

Gets a value that determines whether a product is external.

**Namespace:**  [Microsoft.Web.PlatformInstaller](microsoft-web-platforminstaller-namespace.md)  
**Assembly:**  Microsoft.Web.PlatformInstaller (in Microsoft.Web.PlatformInstaller.dll)

## Syntax

``` vb
'Declaration
PublicReadOnlyPropertyExternalAsBooleanGet
'Usage
DiminstanceAsProductDimvalueAsBooleanvalue = instance.External
```

``` csharp
publicboolExternal { get; }
```

``` c++
public:
propertyboolExternal {
    boolget ();
}
```

``` jscript
function getExternal () : boolean
```

#### Property Value

Type: Boolean  
true if the product is external, otherwise false.  

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see <https://msdn.microsoft.com/en-us/library/8skskf63(v=vs.90)>.

## See Also

#### Reference

[Product Class](product-class-microsoft-web-platforminstaller.md)

[Product Members](product-members-microsoft-web-platforminstaller.md)

[Microsoft.Web.PlatformInstaller Namespace](microsoft-web-platforminstaller-namespace.md)
