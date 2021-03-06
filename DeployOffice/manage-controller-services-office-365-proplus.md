---
title: "How admins can manage controller services in Office 365 ProPlus"
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: Ent_O365
ms.custom: Ent_Office_ProPlus
description: "Provides information to admins on how to use Group Policy settings to manage services in Office 365 ProPlus"
---

# How admins can manage controller services in Office 365 ProPlus 

The following information shows administrators what controls are available for services in Office 365 ProPlus in which Microsoft acts as data controller.<sup>1</sup>

> [!NOTE]
> - For more information about these services and the controls available to your users, see [Microsoft's other connected services](https://support.office.com/article/92c234f1-dc91-4dc1-925d-6c90fc3816d8).
> - Unless otherwise noted, the listed connected services are subject to the [Microsoft Services Agreement](https://www.microsoft.com/servicesagreement/).
> - Users access these services through Office applications, such as Excel or PowerPoint. 
> - Some of these services may be available in other versions of Office, such as Office Professional Plus 2016. 
> - For Group Policy, be sure to download the latest [Administrative Template files (ADMX/ADML) for Office](https://www.microsoft.com/download/details.aspx?id=49030) so that you have the most current policy settings.


## 3D Maps
3D Maps is a three-dimensional data visualization tool in Excel that provides information and insights that may not be available in traditional two-dimensional tables and charts.

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Add-ins 
Users can install Microsoft and third-party add-ins that provide a wide variety of additional functionality to Office applications and services.

To avoid any unintended transfer of data to Microsoft via an add-in, we recommend that you disable the use of unknown add-ins by your users. You can do this by using Group Policy and the **Block Web Add-ins** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Security Settings\Trust Center\Trusted Catalogs. 

## Editor
Editor gives users an overview of document errors and lets them choose which ones they want to fix.

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Insert 3D Models
Users can insert rotatable 3D models based on the subject chosen by the user. 

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Map Charts
Users can create and insert a customized map and charts specific to their data set in Excel. 

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Office Help and Quick Starts 
Office Help creates and publishes help experiences. It provides self-help articles and videos, called Quick Starts, on how to troubleshoot and use Office. 

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Office Store
The Office Store provides add-ins for users to extend the functionality of Office applications. 

You can disable this service for your users by using Group Policy and the **Block the Office Store** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Security Settings\Trust Center\Trusted Catalogs.

## Office templates
Users can download free, pre-built document templates from Office by choosing File > New in an Office app. 

You can disable this service for your users by using Group Policy and the **Disable web templates in File | New and on the Office Start screen** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Web Options… But, this policy setting doesn’t prevent users from downloading templates from Office.com using their web browsers.

## Online Pictures 
Online Pictures provides access to search engines such as Bing, third-party providers such as Pexels, and the user’s personal OneDrive, to search for pictures. 

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Online Video 
Online Video provides access to third-party providers such as YouTube, and the user’s personal OneDrive, to search for videos. 

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## PowerPoint QuickStarter
QuickStarter builds a PowerPoint outline based on a subject provided by the user. 

You can disable this service for your users by using Group Policy and the **Turn off QuickStarter** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft PowerPoint 2016\PowerPoint Options\General. 

You can also use the **Send personal information** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Privacy\Trust Center. 

## Researcher
Researcher in Word helps users to find topics and incorporate reliable sources and content for research papers.

You can disable this service for your users by using Group Policy and the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

## Resume Assistant 
Resume Assistant helps users with their resume or CV by providing examples and suggestions from LinkedIn.

You can disable this service for your users by using Group Policy and the **Allow LinkedIn Resume Assistant feature** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Word 2016\Word Options\General. 

You can prevent all LinkedIn features from appearing in Office applications by using Group Policy and the **Show LinkedIn features in Office applications** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Miscellaneous. 

## Send a Smile
Users can send feedback to Microsoft about their experiences in Office applications.

You can disable this service for your users by using Group Policy and the **Send Office Feedback** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Privacy\Trust Center.

You can also use the **Online Content Options** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Tools | Options | General | Service Options...\Online Content. 

You can disable the user option to send a screenshot of their desktop with their feedback to Microsoft by using the **Allow including screenshot with Office Feedback** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Privacy\Trust Center.

## Smart Lookup
Smart Lookup sends a word or phrase selected by the user to Bing as a search query, and provides more information, definitions, history and other resources from multiple third-party sites related to that word or phrase. 

You can disable this service for your users by using Group Policy and the **Send personal information** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Privacy\Trust Center. 

## Tell Me
Tell Me connects users to Office Help articles and videos via the search query entered. 

You can disable this service for your users by using Group Policy and the **Send personal information** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Privacy\Trust Center. 

## Translator
Translator takes a highlighted word or section of user text, as well as a few words from either side of that text, and performs the requested translation. 

You can disable this service for your users by using Group Policy and the **Send personal information** policy setting. This policy setting can be found under User Configuration\Policies\Administrative Templates\Microsoft Office 2016\Privacy\Trust Center. 

You can disable online-based translation features, including Translator and legacy translation features, by using the **Do not use online machine translation** policy setting and the **Use online translation dictionaries** policy setting. These policy settings can be found under User Configuration\Policies\Administrative Templates\Microsoft Word 2016\Miscellaneous.



*<sup>1</sup> “Controller” means the natural or legal person, public authority, agency or other body which, alone or jointly with others, determines the purposes and means of the processing of personal data; where the purposes and means of such processing are determined by Union or Member State law, the controller or the specific criteria for its nomination may be provided for by Union or Member State law.*
