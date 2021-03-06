---
title: "Plug-in development (Developer Guide for Dynamics 365 for Customer Engagement apps) | MicrosoftDocs"
description: "Learn more about how to develop plug-ins that can integrate with Dynamics 365 for Customer Engagement apps to modify or augment the standard behavior of the platform. "
ms.custom: 
ms.date: 1/18/2019
ms.reviewer: 
ms.service: crm-online
ms.suite: 
ms.tgt_pltfrm: 
ms.topic: article
applies_to: 
  - Dynamics 365 for Customer Engagement (online)
ms.assetid: aa037f4a-b5ae-485c-aac9-8a138a57c576
caps.latest.revision: 30
author: JimDaly
ms.author: jdaly
manager: amyla
search.audienceType: 
  - developer
search.app: 
  - D365CE
---
# On-premise plug-in development

[!INCLUDE[](../includes/cc_applies_to_update_9_0_0.md)]

A plug-in is custom business logic (code) that you can integrate with [!INCLUDE[pn_dynamics_crm_online](../includes/pn-dynamics-crm-online.md)] apps to modify or augment the standard behavior of the platform. Another way to think about plug-ins is that they are handlers for events fired by [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)] apps. You can subscribe, or register, a plug-in to a known set of events to have your code run when the event occurs.

> [!NOTE]
> [!INCLUDE[cc-cdsnote-1](./includes/cc-cdsnote-1.md)]
>
> The plug-in documentation that is applicable to Dynamics 365 for Customer Engagement apps (online) users is now available in the PowerApps documentation at: [Use plug-ins to extend business processes](/powerapps/developer/common-data-service/plug-ins)
>
> [!INCLUDE[cc-cdsnote-2-section](./includes/cc-cdsnote-2-section.md)]
  
 For more information about plug-in run-time execution, see [Event Framework](/powerapps/developer/common-data-service/event-framework).  
  
## In This Section

 [Impersonation in Plug-ins](impersonation-plugins.md)  

 [Register and Deploy Plug-ins](register-deploy-plugins.md)  
  
 [Debug a Plug-in](debug-plugin.md) 

 [Access external web resources](access-web-resources.md)  

 [Offline plug-in execution](support-offline-execution.md)  
  
## Related Sections  
 [Write Plug-Ins to Extend Business Processes](write-plugin-extend-business-processes.md)  
 [Web Service Authentication and Impersonation](authenticate-users.md)
