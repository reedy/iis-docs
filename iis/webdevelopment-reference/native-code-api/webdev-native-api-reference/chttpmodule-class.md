---
title: "CHttpModule Class | Microsoft Docs"
ms.custom: ""
ms.date: "10/07/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: d2cd5a3e-e7a4-5706-5441-9190228d36b0
caps.latest.revision: 21
author: "shirhatti"
manager: "wpickett"
---
# CHttpModule Class
Defines the base class for request-level HTTP modules.  
  
## Syntax  
  
```cpp  
class CHttpModule  
```  
  
## Methods  
 The following table lists the methods exposed by the `CHttpModule` class.  
  
|Name|Description|  
|----------|-----------------|  
|[~CHttpModule](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-chttpmodule-method.md)|Deallocates an instance of the `CHttpModule` class.|  
|[CHttpModule](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-chttpmodule-method.md)|Initializes a new instance of the `CHttpModule` class.|  
|[Dispose](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-dispose-method.md)|Releases all resources used by the current instance of the `CHttpModule` class.|  
|[OnAcquireRequestState](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onacquirerequeststate-method.md)|Represents the method that will handle an `AcquireRequestState` event, which occurs when IIS retrieves the state for the current request.|  
|[OnAsyncCompletion](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onasynccompletion-method.md)|Represents the method that will handle an asynchronous completion event, which occurs after an asynchronous operation has finished processing.|  
|[OnAuthenticateRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onauthenticaterequest-method.md)|Represents the method that will handle an `AuthenticateRequest` event, which occurs when IIS establishes the identity of a user.|  
|[OnAuthorizeRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onauthorizerequest-method.md)|Represents the method that will handle an `AuthorizeRequest` event, which occurs when IIS verifies user authorization.|  
|[OnBeginRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onbeginrequest-method.md)|Represents the method that will handle a `BeginRequest` event, which occurs as the first event in the HTTP integrated request-processing pipeline for the current request.|  
|[OnCustomRequestNotification](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-oncustomrequestnotification-method.md)|Represents the method that will handle a custom event, which occurs when a module raises a user-defined notification.|  
|[OnEndRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onendrequest-method.md)|Represents the method that will handle an `EndRequest` event, which occurs as the last event in the HTTP integrated request-processing pipeline for the current request.|  
|[OnExecuteRequestHandler](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onexecuterequesthandler-method.md)|Represents the method that will handle an `ExecuteRequestHandler` event, which occurs when IIS executes the handler for the current request.|  
|[OnLogRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onlogrequest-method.md)|Represents the method that will handle a `LogRequest` event, which occurs when IIS prepares to log the current request.|  
|[OnMapPath](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onmappath-method.md)|Represents the method that will handle a `MapPath` event, which occurs when an operation requests the physical path to be mapped for the current request.|  
|[OnMapRequestHandler](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onmaprequesthandler-method.md)|Represents the method that will handle a `MapRequestHandler` event, which occurs when IIS maps the current request to an event handler.|  
|[OnPostAcquireRequestState](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostacquirerequeststate-method.md)|Represents the method that will handle an `AcquireRequestState` post-event, which occurs after IIS has retrieved the state for the current request.|  
|[OnPostAuthenticateRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostauthenticaterequest-method.md)|Represents the method that will handle an `AuthenticateRequest` post-event, which occurs after IIS has established the identity of a user.|  
|[OnPostAuthorizeRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostauthorizerequest-method.md)|Represents the method that will handle an `AuthorizeRequest` post-event, which occurs after IIS has verified user authorization.|  
|[OnPostBeginRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostbeginrequest-method.md)|Represents the method that will handle a `BeginRequest` post-event, which occurs after the first event in the HTTP integrated request-processing pipeline.|  
|[OnPostEndRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostendrequest-method.md)|Represents the method that will handle an `EndRequest` post-event, which occurs after the last event in the HTTP integrated request-processing pipeline for the current request.|  
|[OnPostExecuteRequestHandler](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostexecuterequesthandler-method.md)|Represents the method that will handle an `ExecuteRequestHandler` post-event, which occurs after IIS executes the handler for the current request.|  
|[OnPostLogRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostlogrequest-method.md)|Represents the method that will handle a `LogRequest` post-event, which occurs after IIS has logged the current request.|  
|[OnPostMapRequestHandler](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostmaprequesthandler-method.md)|Represents the method that will handle a `MapRequestHandler` post-event, which occurs after IIS has mapped the current request to the appropriate event handler.|  
|[OnPostPreExecuteRequestHandler](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostpreexecuterequesthandler-method.md)|Represents the method that will handle a `PreExecuteRequestHandler` post-event, which occurs before IIS executes a request handler.|  
|[OnPostReleaseRequestState](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostreleaserequeststate-method.md)|Represents the method that will handle a `ReleaseRequestState` post-event, which occurs after the current state has been released.|  
|[OnPostResolveRequestCache](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostresolverequestcache-method.md)|Represents the method that will handle a `ResolveRequestCache` post-event, which occurs after IIS has resolved a request from the cache.|  
|[OnPostUpdateRequestCache](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpostupdaterequestcache-method.md)|Represents the method that will handle an `UpdateRequestCache` post-event, which occurs after IIS has stored the request in the cache.|  
|[OnPreExecuteRequestHandler](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onpreexecuterequesthandler-method.md)|Represents the method that will handle a `PreExecuteRequestHandler` event, which occurs before IIS executes a request handler.|  
|[OnReadEntity](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onreadentity-method.md)|Represents the method that will handle a `ReadEntity` event, which occurs when an operation reads data from the request buffer.|  
|[OnReleaseRequestState](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onreleaserequeststate-method.md)|Represents the method that will handle a `ReleaseRequestState` event, which occurs when the current state is released.|  
|[OnResolveRequestCache](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onresolverequestcache-method.md)|Represents the method that will handle a `ResolveRequestCache` event, which occurs when IIS resolves a request in the cache.|  
|[OnSendResponse](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onsendresponse-method.md)|Represents the method that will handle a `SendResponse` event, which occurs when IIS sends the response buffer.|  
|[OnUpdateRequestCache](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/chttpmodule-onupdaterequestcache-method.md)|Represents the method that will handle an `UpdateRequestCache` event, which occurs when IIS stores the request in the cache.|  
  
## Derived Classes  
 This class contains no derived classes.  
  
## Remarks  
 The `CHttpModule` class is the base class for request-level HTTP modules. To create a `CHttpModule`-derived class, you need to create a request-level HTTP module that contains a class that inherits from `CHttpModule` and a class that derives from the [IHttpModuleFactory](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpmodulefactory-interface.md) interface. For more information about creating HTTP modules, see [Designing Native-Code HTTP Modules](../../../webdevelopment-reference\native-code-development-overview\native-code-dev-overview/designing-native-code-http-modules.md).  
  
 The `CHttpModule` class provides protected constructor and destructor methods and a public `Dispose` method. At the end of the request, the `Dispose` method is called to delete the instance of the `CHttpModule`-derived class.  
  
 The `CHttpModule` class also defines the notification-specific methods that [!INCLUDE[iisver](../../../wmi-provider/includes/iisver-md.md)] calls when it processes request-level events within the integrated request-processing pipeline. An HTTP module can register for specific events by defining a list of notifications in a module's exported [RegisterModule](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/pfn-registermodule-function.md) function.  
  
## Deterministic request events  
 The majority of the request-level notification methods are processed chronologically during the normal flow of request-level events within the integrated pipeline. Each of the deterministic request-level notification methods has a matching post-event notification, which allows HTTP modules to process when an event occurs or immediately after the event occurs.  
  
 The following table lists the chronological request-level event and post-event notification methods in the order of their occurrence within the integrated pipeline.  
  
|Event notification method|Post-event notification method|  
|-------------------------------|-------------------------------------|  
|`OnBeginRequest`|`OnPostBeginRequest`|  
|`OnAuthenticateRequest`|`OnPostAuthenticateRequest`|  
|`OnAuthorizeRequest`|`OnPostAuthorizeRequest`|  
|`OnResolveRequestCache`|`OnPostResolveRequestCache`|  
|`OnMapRequestHandler`|`OnPostMapRequestHandler`|  
|`OnAcquireRequestState`|`OnPostAcquireRequestState`|  
|`OnPreExecuteRequestHandler`|`OnPostPreExecuteRequestHandler`|  
|`OnExecuteRequestHandler`|`OnPostExecuteRequestHandler`|  
|`OnReleaseRequestState`|`OnPostReleaseRequestState`|  
|`OnUpdateRequestCache`|`OnPostUpdateRequestCache`|  
|`OnLogRequest`|`OnPostLogRequest`|  
|`OnEndRequest`|`OnPostEndRequest`|  
  
 For example, `OnBeginRequest` occurs before `OnAuthenticateRequest`, `OnMapRequestHandler` occurs before `OnAcquireRequestState`, and so on.  
  
> [!NOTE]
>  Post-event notifications occur before the next chronological request-level notification. For example, `OnPostAuthenticateRequest` occurs before `OnAuthorizeRequest`, `OnPostUpdateRequestCache` occurs before `OnLogRequest`, and so on.  
  
## Nondeterministic request events  
 The remaining request-level notification methods are not processed in any specific order; instead, IIS processes these events when a specific nondeterministic event occurs. The following table lists the nondeterministic request-level event and any related post-event notification methods.  
  
|Event notification method|Post-event notification method|  
|-------------------------------|-------------------------------------|  
|`OnAsyncCompletion`|(None)<sup>1</sup>|  
|`OnCustomRequestNotification`|(None)<sup>2</sup>|  
|`OnMapPath`|(None)|  
|`OnReadEntity`|(None)|  
|`OnSendResponse`|(None)|  
  
 <sup>1</sup> The `OnAsyncCompletion` method is called when an asynchronous event occurs within an HTTP module. As such, you cannot register for an asynchronous notification by using a module's exported [RegisterModule](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/pfn-registermodule-function.md) function. Instead, your module would supply an `OnAsyncCompletion` method to process notifications that occur after calling methods that return asynchronously (for example, the [IHttpContext::ExecuteRequest](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpcontext-executerequest-method.md) and [IHttpResponse::WriteEntityChunks](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpresponse-writeentitychunks-method.md) methods). When IIS calls `OnAsyncCompletion`, the method will pass parameters that indicate the notification type and whether the notification was for an event or post-event.  
  
 <sup>2</sup> The `OnCustomRequestNotification` method does not have a corresponding post-event notification method. An HTTP module can register for a custom notification by using the module's exported `RegisterModule` function, but a module cannot register for a notification that occurs after a custom notification has occurred.  
  
## Example  
 The following example demonstrates how to create a simple "Hello World" HTTP module. The module defines an exported `RegisterModule` function that passes an instance of an `IHttpModuleFactory` interface to the [IHttpModuleRegistrationInfo::SetRequestNotifications](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpmoduleregistrationinfo-setrequestnotifications-method.md) method and registers for the [RQ_BEGIN_REQUEST](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/request-processing-constants.md) notification. IIS uses the [IHttpModuleFactory::GetHttpModule](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpmodulefactory-gethttpmodule-method.md) method to create an instance of a `CHttpModule` class and returns a success status. IIS also uses the [IHttpModuleFactory::Terminate](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/ihttpmodulefactory-terminate-method.md) method to remove the factory from memory.  
  
 When an `RQ_BEGIN_REQUEST` notification occurs, IIS calls the module's `OnBeginRequest` method to process the current request. `OnBeginRequest` clears the response buffer and modifies the MIME type for the response. The method then creates a data chunk that contains a "Hello World" string and returns the string to a Web client. Finally, the module returns a status indicator that notifies IIS that all notifications are finished and then exits.  
  
<!-- TODO: review snippet reference  [!CODE [CHttpModuleHelloWorld#1](CHttpModuleHelloWorld#1)]  -->  
  
 Your module must export the `RegisterModule` function. You can export this function by creating a module definition (.def) file for your project, or you can compile the module by using the `/EXPORT:RegisterModule` switch. For more information, see [Walkthrough: Creating a Request-Level HTTP Module By Using Native Code](../../../webdevelopment-reference\native-code-development-overview\native-code-dev-overview/walkthrough-creating-a-request-level-http-module-by-using-native-code.md).  
  
 You can optionally compile the code by using the `__stdcall (/Gz)` calling convention instead of explicitly declaring the calling convention for each function.  
  
## Requirements  
  
|Type|Description|  
|----------|-----------------|  
|Client|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)] on [!INCLUDE[winvista](../../../wmi-provider/includes/winvista-md.md)]<br />-   [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)] on [!INCLUDE[win7](../../../wmi-provider/includes/win7-md.md)]<br />-   [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)] on [!INCLUDE[win8](../../../wmi-provider/includes/win8-md.md)]<br />-   [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)] on [!INCLUDE[win10](../../../wmi-provider/includes/win10-md.md)]|  
|Server|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)] on [!INCLUDE[winsrv2008](../../../wmi-provider/includes/winsrv2008-md.md)]<br />-   [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)] on [!INCLUDE[winsrv2008r2](../../../wmi-provider/includes/winsrv2008r2-md.md)]<br />-   [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)] on [!INCLUDE[winsrv2012](../../../wmi-provider/includes/winsrv2012-md.md)]<br />-   [!INCLUDE[iis85](../../../wmi-provider/includes/iis85-md.md)] on [!INCLUDE[winsrv2012r2](../../../wmi-provider/includes/winsrv2012r2-md.md)]<br />-   [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)] on [!INCLUDE[winsrv2016](../../../wmi-provider/includes/winsrv2016-md.md)]|  
|Product|-   [!INCLUDE[iis70](../../../wmi-provider/includes/iis70-md.md)], [!INCLUDE[iis75](../../../wmi-provider/includes/iis75-md.md)], [!INCLUDE[iis80](../../../wmi-provider/includes/iis80-md.md)], [!INCLUDE[iis85](../../../wmi-provider/includes/iis85-md.md)], [!INCLUDE[iis100](../../../wmi-provider/includes/iis100-md.md)]<br />-   [!INCLUDE[iisexp75](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp75-md.md)], [!INCLUDE[iisexp80](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp80-md.md)], [!INCLUDE[iisexp100](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/includes/iisexp100-md.md)]|  
|Header|Httpserv.h|  
  
## See Also  
 [Creating Native-Code HTTP Modules](../../../webdevelopment-reference\native-code-development-overview\native-code-dev-overview/creating-native-code-http-modules.md)   
 [CGlobalModule Class](../../../webdevelopment-reference\native-code-api\webdev-native-api-reference/cglobalmodule-class.md)