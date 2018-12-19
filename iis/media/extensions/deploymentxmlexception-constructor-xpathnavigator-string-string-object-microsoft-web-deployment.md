﻿---
title: DeploymentXmlException Constructor (XPathNavigator, String, String, Object) (Microsoft.Web.Deployment)
TOCTitle: DeploymentXmlException Constructor (XPathNavigator, String, String, Object)
ms:assetid: M:Microsoft.Web.Deployment.DeploymentXmlException.#ctor(System.Xml.XPath.XPathNavigator,System.String,System.String,System.Object)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.deployment.deploymentxmlexception.deploymentxmlexception(v=VS.90)
ms:contentKeyID: 20208684
ms.date: 05/02/2012
mtps_version: v=VS.90
dev_langs:
- vb
- csharp
- c++
- jscript
api_location:
- Microsoft.Web.Deployment.dll
api_name:
- Microsoft.Web.Deployment.DeploymentXmlException..ctor
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# DeploymentXmlException Constructor (XPathNavigator, String, String, Object)

Creates an instance of a [DeploymentXmlException](deploymentxmlexception-class-microsoft-web-deployment.md) object with an XPathNavigator, the XML file the exception was caused by, the message format, and the value that caused the exception.

**Namespace:**  [Microsoft.Web.Deployment](microsoft-web-deployment-namespace.md)  
**Assembly:**  Microsoft.Web.Deployment (in Microsoft.Web.Deployment.dll)

## Syntax

``` vb
'Declaration
PublicSubNew ( _
    navigatorAsXPathNavigator, _
    fileNameAsString, _
    messageFormatAsString, _
    valueAsObject _
)
'Usage
DimnavigatorAsXPathNavigatorDimfileNameAsStringDimmessageFormatAsStringDimvalueAsObjectDiminstanceAs NewDeploymentXmlException(navigator, _
    fileName, messageFormat, value)
```

``` csharp
publicDeploymentXmlException(
    XPathNavigatornavigator,
    stringfileName,
    stringmessageFormat,
    Objectvalue
)
```

``` c++
public:
DeploymentXmlException(
    XPathNavigator^ navigator, 
    String^ fileName, 
    String^ messageFormat, 
    Object^ value
)
```

``` jscript
publicfunctionDeploymentXmlException(
    navigator : XPathNavigator, 
    fileName : String, 
    messageFormat : String, 
    value : Object
)
```

#### Parameters

  - navigator  
    Type: [System.Xml.XPath. . :: . .XPathNavigator](https://msdn.microsoft.com/en-us/library/9x81sf5a\(v=vs.90\))  
    An XPathNavigator for the XML document being evaluated when the exception was thrown.  

<!-- end list -->

  - fileName  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The name of the file that was being evaluated when the exception was thrown.  

<!-- end list -->

  - messageFormat  
    Type: [System. . :: . .String](https://msdn.microsoft.com/en-us/library/s1wwdcbf\(v=vs.90\))  
    The unformatted message used along with value to create an exception message. This format uses standard .NET string formatting.  

<!-- end list -->

  - value  
    Type: [System. . :: . .Object](https://msdn.microsoft.com/en-us/library/e5kfa45b\(v=vs.90\))  
    The value that was found when evaluating and validating the XML found in fileName.  

## Remarks

This exception is thrown when a value is found in an XML document that was not expected.

## Permissions

  - Full trust for the immediate caller. This member cannot be used by partially trusted code. For more information, see [Using Libraries from Partially Trusted Code](https://msdn.microsoft.com/en-us/library/8skskf63\(v=vs.90\)).

## See Also

#### Reference

[DeploymentXmlException Class](deploymentxmlexception-class-microsoft-web-deployment.md)

[DeploymentXmlException Overload](deploymentxmlexception-constructor-microsoft-web-deployment.md)

[Microsoft.Web.Deployment Namespace](microsoft-web-deployment-namespace.md)
