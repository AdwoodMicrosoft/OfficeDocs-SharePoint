---
title: "Creating and launching a healthy SharePoint portal"
ms.reviewer: 
ms.author: jhendr
author: JoanneHendrickson
manager: pamgreen
audience: ITPro
ms.topic: article
ms.prod: sharepoint-server-itpro
localization_priority: Priority
ms.collection: M365-collaboration
description: "Creating and launching a healthy SharePoint portal"
---

# Creating and launching a healthy SharePoint portal

A portal is a SharePoint site where your default landing page(s) for your company is created. Large organizations can have several portals. If you expect more than 20% of your users within your organization to access the page, you should consider that a portal page. 

This shouldn't be confused with a team site your department uses to collaborate and share documents within your team.

## Guidance

This set of guidance will walk you through best practices and recommendations before you launch your portal and how to keep your portal healthy.
  
||**What to do**|**Follow this**|
|:-----|:-----|:-----|
|![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/deploy-blue-32.png "Staged rollout")|[Plan the rollout of your portal](https://docs.microsoft.com/en-us/Office365/Enterprise/planportallaunchroll-out)|Launch in waves|
|![Alt image text](https://docs.microsoft.com/en-us/office/media/icons/PNGs/document-3-blue-32.png "Look and feel")|[Portal design guidance](https://aka.ms/spdesignguidance)|Review the guidance while designing your sites|</br>
|![Alt image text](media/page-diag-tool.png "Modern diagnostics tool")|[Run the Page Diagnostics for SharePoint tool](https://aka.ms/perftool)|Validate your pages and follow the guidance|
|![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/bandwidth-blue-32.png "Optimize your Performance")|Optimize your Performance|Follow the guidance below and run the Page Diagnostics for SharePoint tool|</br>
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/globe-hyperlink-blue-32.png "CDN") [Use CDN for better performance](https://docs.microsoft.com/en-us/office365/enterprise/use-office-365-cdn-with-spo)|Implement Public and Private Content Delivery Networks (CDN)|
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/graph-4-blue-32.png "Batch REST calls") [Batch calls to SharePoint when using the REST API](https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/make-batch-requests-with-the-rest-apis)|Combine operations into fewer requests|
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/analytics-usage-report-blue-32.png "Slow web parts") [Improve performance for slow web parts](https://go.microsoft.com/fwlink/?linkid=2099018)|Follow guidance to remediate common issues|
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/bandwidth-blue-32.png "Page weight") [Review page weight](https://go.microsoft.com/fwlink/?linkid=2099017)|Follow guidance to reduce page weight in your site pages|
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/task-list-planning-blue-32.png "Calls on a page") [Limit the number of requests to a page](https://docs.microsoft.com/en-us/Office365/Enterprise/modern-page-call-optimization)|Limit the number of web parts and calls into SharePoint|
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/picture-photo-blue-32.png "Optimize images") [Optimize your images](https://go.microsoft.com/fwlink/?linkid=2099113)|Follow basic image optimization for the web|
||![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/files-blue-32.png "iFrames") [Limit and use Iframes carefully](https://go.microsoft.com/fwlink/?linkid=2099016)|Don't use more than 2 Iframes on a page|
|![Alt image text](https://docs.microsoft.com/en-us/office/media/icons/PNGs/task-checklist-planning-blue-32.png "Modern portal limits")|[Modern portal limits](https://docs.microsoft.com/en-us/Office365/Enterprise/modern-portal-limits)|Follow the limits for modern portals to further optimize performance|</br>
|![Alt image text](https://docs.microsoft.com/en-us/Office/media/icons/PNGs/bandwidth-blue-32.png "Network optimization")|[Network optimization](https://aka.ms/O365IP)|Configure your URLs and IP endpoints|</br>
