﻿---
title: Windows PowerShell for Office Web Apps Server
TOCTitle: Windows PowerShell for Office Web Apps Server
ms:assetid: 56bfd3b3-f563-423d-aea0-65b331f73b96
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee890080(v=office.15)
ms:contentKeyID: 48409061
ms.date: 12/13/2016
mtps_version: v=office.15
---

# Windows PowerShell for Office Web Apps Server

 

_**Applies to:** Office Web Apps Server_


**Summary:** Find articles about the OfficeWebApps Windows PowerShell cmdlets that configure Office Web Apps Server.

**Audience:** IT Professionals

Office Web Apps Server is a new Office server product that delivers browser-based versions of Word, PowerPoint, Excel, and OneNote. A single Office Web Apps Server farm can support users who access Office files through SharePoint 2013, Lync Server 2013, Exchange Server 2013, shared folders, and websites.

![Office 2013 logo](images/JJ219457.a106e261-2cd0-43b7-af77-92de7e4b6fb9(Office.15).png "Office 2013 logo")The following table lists and describes the articles for each OfficeWebApps Windows PowerShell cmdlet for Office Web Apps Server.


> [!TIP]
> If Windows PowerShell doesn’t recognize these cmdlets when you run them, you may need to import the <STRONG>OfficeWebApps</STRONG> module. Use this command:<BR><CODE>Import-Module -Name OfficeWebApps</CODE>




### OfficeWebApps Windows PowerShell cmdlets

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Article</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="get-officewebappsfarm.md">Get-OfficeWebAppsFarm</a></p></td>
<td><p>Returns details about the OfficeWebAppsFarm object that the current server is a member of.</p></td>
</tr>
<tr class="even">
<td><p><a href="get-officewebappshost.md">Get-OfficeWebAppsHost</a></p></td>
<td><p>Returns the list of host domains that are on the Allow List for an Office Web Apps Server farm.</p></td>
</tr>
<tr class="odd">
<td><p><a href="get-officewebappsmachine.md">Get-OfficeWebAppsMachine</a></p></td>
<td><p>Returns details about the current server that is in an Office Web Apps Server farm.</p></td>
</tr>
<tr class="even">
<td><p><a href="new-officewebappsfarm.md">New-OfficeWebAppsFarm</a></p></td>
<td><p>Creates a new Office Web Apps Server farm on the local computer.</p></td>
</tr>
<tr class="odd">
<td><p><a href="new-officewebappshost.md">New-OfficeWebAppsHost</a></p></td>
<td><p>Adds a host domain to the Allow List for an Office Web Apps Server farm.</p></td>
</tr>
<tr class="even">
<td><p><a href="new-officewebappsmachine.md">New-OfficeWebAppsMachine</a></p></td>
<td><p>Adds the current server to an existing Office Web Apps Server farm.</p></td>
</tr>
<tr class="odd">
<td><p><a href="remove-officewebappshost.md">Remove-OfficeWebAppsHost</a></p></td>
<td><p>Removes a host domain from the Allow List for an Office Web Apps Server farm.</p></td>
</tr>
<tr class="even">
<td><p><a href="remove-officewebappsmachine.md">Remove-OfficeWebAppsMachine</a></p></td>
<td><p>Removes the current server from the Office Web Apps Server farm.</p></td>
</tr>
<tr class="odd">
<td><p><a href="repair-officewebappsfarm.md">Repair-OfficeWebAppsFarm</a></p></td>
<td><p>Removes all servers flagged as unhealthy from an Office Web Apps Server farm.</p></td>
</tr>
<tr class="even">
<td><p><a href="set-officewebappsfarm.md">Set-OfficeWebAppsFarm</a></p></td>
<td><p>Configures the settings of an existing Office Web Apps Server farm.</p></td>
</tr>
<tr class="odd">
<td><p><a href="set-officewebappsmachine.md">Set-OfficeWebAppsMachine</a></p></td>
<td><p>Changes the settings of the current server that is in an Office Web Apps Server farm.</p></td>
</tr>
</tbody>
</table>


### Other Office resources for IT pros

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><img src="images/JJ219457.22cad0f4-303d-4a40-90a3-fa08e69dfdaf(Office.15).png" title="What&#39;s new icon (box)" alt="What&#39;s new icon (box)" /></p></td>
<td><p><strong>Newly published content</strong></p></td>
<td><p>See the following article for a list of new or recently updated Office Web Apps Server articles.</p>
<ul>
<li><p><a href="https://technet.microsoft.com/en-us/library/ff433481(v=office.15)">Newly published content for Office Web Apps and Office Web Apps Server</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><img src="images/JJ219457.6b2d6dfa-7dc8-40fb-8335-af68b575f8cb(Office.15).png" title="Getting started" alt="Getting started" /></p></td>
<td><p><strong>Getting started</strong></p></td>
<td><p>Download Office Web Apps Server.</p>
<ul>
<li><p><a href="http://go.microsoft.com/fwlink/p/?linkid=256561">Volume Licensing Service Center (VLSC)</a></p>
<p>To download Office Web Apps Server you must have a license, under a Volume Licensing agreement, for Office Professional Plus 2013, Office Standard 2013, or Office for Mac 2011. The download is located under those Office products on the VLSC portal.</p></li>
</ul>
<p>Download the language packs for Office Web Apps Server.</p>
<ul>
<li><p><a href="http://go.microsoft.com/fwlink/p/?linkid=263945">Microsoft Download Center</a></p></li>
</ul>
<p>Learn more about Office Web Apps Server.</p>
<ul>
<li><p><a href="deploy-the-infrastructure-office-web-apps-server.md">Deploy the infrastructure: Office Web Apps Server</a></p></li>
</ul>
<p>Explore these links to learn how Office Server products can use Office Web Apps Server to provide web-based viewing and editing of Office files.</p>
<ul>
<li><p><a href="use-office-web-apps-with-sharepoint-2013.md">Use Office Web Apps with SharePoint 2013</a></p></li>
<li><p><a href="http://go.microsoft.com/fwlink/p/?linkid=256902">Deploying Office Web Apps Server and Lync Server 2013</a></p></li>
<li><p><a href="http://go.microsoft.com/fwlink/p/?linkid=256611">Office Web Apps Server Integration (Exchange Server 2013)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><img src="images/JJ219457.6fa793ee-ede9-4476-901c-de96ea37fc3a(Office.15).png" title="Chat icon" alt="Chat icon" /></p></td>
<td><p><strong>Provide feedback</strong></p></td>
<td><p>To provide feedback about the documentation for Office 2013 Office 365 ProPlus, choose the <strong>Feedback</strong> link at the bottom of the page. This delivers your feedback directly to the documentation team.</p></td>
</tr>
</tbody>
</table>


## Find training and other resources about Office


<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Download</strong></p>
<ul>
<li><p><a href="http://technet.microsoft.com/evalcenter/hh973391">Office 365 ProPlus</a></p></li>
<li><p><a href="http://go.microsoft.com/fwlink/p/?linkid=507653">Office 365</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/evalcenter/ee390818.aspx">Office 2013</a></p></li>
<li><p><a href="http://code.msdn.microsoft.com/office/">Office code samples</a></p></li>
<li><p><a href="http://gallery.technet.microsoft.com/office/">Office scripts and sample files</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/office/aa905351">Office developer downloads</a></p></li>
<li><p><a href="http://www.microsoft.com/download/en/office.aspx?q=office">Office downloads</a></p></li>
<li><p><a href="http://www.microsoft.com/en-us/download/search.aspx?q=office+365">Office 365 downloads</a></p></li>
</ul></td>
<td><p><strong>How To</strong></p>
<ul>
<li><p><a href="http://technet.microsoft.com/en-us/library/jj220060.aspx">Build apps for Office</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/library/cc178982.aspx">Deploy Office 2013</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/library/cc179068.aspx">Manage Office 2013</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/office/ff381682.aspx">Train Office 2010 end users</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/office/aa905496.aspx">Office SDKs</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/office/aa905375">Office developer training</a></p></li>
<li><p><a href="http://www.microsoft.com/resources/msdn/en-us/office/media/video/video.html?cid=odc%26from=mscomodc">Office developer videos</a></p></li>
<li><p><a href="http://www.microsoft.com/resources/msdn/en-us/office/media/video/video.html?cid=o365%26from=mscomo365">Office 365 developer videos</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/office/ff519671">Office IT pro training</a></p></li>
<li><p><a href="http://www.microsoft.com/resources/technet/en-us/office/media/video/video.html?cid=otc%26from=mscomotc">Office IT pro videos</a></p></li>
<li><p><a href="http://www.microsoft.com/resources/technet/en-us/office/media/video/video.html?cid=o365%26from=mscomo365">Office 365 IT pro videos</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/openspecifications/">Open specifications</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/library/cc307282(v=office.12).aspx">Office protocols</a></p></li>
</ul></td>
<td><p><strong>Sites</strong></p>
<ul>
<li><p><a href="http://msdn.microsoft.com/en-us/office">Office developers</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/office">Office IT Pros</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/office/hh506337">Office 365 developers</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/hh912691">Office 365 IT pros</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/library/cc303401.aspx">Office 2013 Resource Kit</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/sharepoint">SharePoint developers</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/sharepoint">SharePoint IT Pros</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/vstudio/aa718325">Visual Studio developers</a></p></li>
<li><p><a href="http://office.microsoft.com/">Office.com</a></p></li>
</ul></td>
<td><p><strong>Help</strong></p>
<ul>
<li><p><a href="http://technet.microsoft.com/en-us/office/ee748587.aspx">Office updates</a></p></li>
<li><p><a href="http://blogs.msdn.com/b/officeapps">Apps for Office and SharePoint blog</a></p></li>
<li><p><a href="http://social.msdn.microsoft.com/forums/en-us/category/officedev%2coldevelopment%2csharepoint2010%2csharepoint%2cprojectserver2010%2cprojectprofessional2010%2cuc/">Forums: Office for Developers</a></p></li>
<li><p><a href="http://community.office365.com/en-us/forums/default.aspx">Forums: Office 365</a></p></li>
<li><p><a href="http://social.technet.microsoft.com/wiki">TechNet Wiki</a></p></li>
<li><p><a href="http://stackoverflow.com/search?q=office">StackOverflow: Office</a></p></li>
<li><p><a href="http://mvp.microsoft.com/en-us/mvp/search-mvp.aspx?kw=office">Office MVPs</a></p></li>
<li><p><a href="http://technet.microsoft.com/en-us/ms772425">Office IT pro support</a></p></li>
<li><p><a href="http://msdn.microsoft.com/en-us/office/aa905515">Office developer support</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


[](use-office-web-apps-with-sharepoint-2013.md)

