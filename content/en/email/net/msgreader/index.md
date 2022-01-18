---
title: .NET Library for Outlook MSG Files – Read & Convert MSG as Text | MSGReader
description: MSGReader - An Open Source C# .NET library for MS Outlook MSG files. Developers can create, read, modify & convert Outlook MSG and EML files via .NET API.
keywords: .NET MSG, .NET EML, Free .NET MSG API, .NET MSG Library, Open Source outlook Library, .NET MSG programming, .NET MSG APIs, .NET MSG library, create MSG Documents, EML C# .NET Libraries, C# outlook, C# MSG, C# EML, convert Outlook MSG, convert Outlook EML
draft: false
weight: 2



ProductName: MSGReader 
Githublink: https://github.com/Sicos1977/MSGReader
ListingPage_Short_Description: Open Source C# .NET library that supports reading Outlook MSG and EML files without installing MS outlook. You can easily read properties from an Outlook MSG and EML messages.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="MSGReader"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text=".NET Library for Outlook MSG Files Processing"
Header_H2_Text="Open Source C# .NET API to Read, Write and Convert MS Outlook MSG and EML files." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>MSGReader is Open Source C# .NET library for reading Outlook MSG and EML files. It enables developers to read outlook MSG and EML files without using Microsoft Outlook. The most common outlook objects such as E-mail, Appointment, Task, Contact card & Sticky note are fully supported. All body types in MSG files, such as Text, HTML, HTML embedded into RTF and RTF are also supported.</p>
<p>There are a few options available for manipulation of MSG files in MSGReader. It allows developers to remove attachments from email message; they can also save the file to a new one. </p>

{{< /SinglePage/PageBody/tab/text >}}
{{< SinglePage/PageBody/tab/carousel-links >}}

<li data-target="#diagramcarousel" data-slide-to="0"><a href="#">At a Glance</a></li>
<li data-target="#diagramcarousel" data-slide-to="2"><a href="#">Platform Independence</a></li>
<li data-target="#diagramcarousel" data-slide-to="1"><a class="activetab" href="#">Supported File Formats</a></li>


{{< /SinglePage/PageBody/tab/carousel-links >}}
{{< /SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>At A Glance</h3>
<p>An overview of MSGReader features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read outlook MSG</li>
<li>Read email subject</li>
<li>Read mail body</li>
<li>Read attachment</li>
<li>Save attachment</li>
<li>MSG to text file</li>
</ul>
</div>
<!--/left
<div class="d1-col d1-right">&nbsp;</div>--></div>
<div class="d1-logo"><img class="bg-dark" src='listing-image.png' alt="MSGReader"><header>MSGReader</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MSGReader supports popular Microsoft Outlook file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/email/msg/">MSG</a>, <a href="https://docs.fileformat.com/email/eml/">EML</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/word-processing/rtf/">RTF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-dark" src='listing-image.png' alt="MSGReader"><header>MSGReader</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MSGReader only requires .NETFramework.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><!--<header><i class="fa fa-cubes">` </i></header-->
<ul>
<li>.NETFramework 3.5</li>
</ul>
</div>
<!--/left
<div class="d1-col d1-right">&nbsp;</div>--> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-dark" src='listing-image.png' alt="MSGReader"><header>MSGReader</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with MSGReader</h2>
<p>The easiest way to install MSGReader is via NuGet. To use it from Visual Studio’s Package Manager Console, please enter the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the command</h3>
<pre><code class="html"> Install-Package MSGReader </code></pre>

<p>Using MSGReader from a COM based language like VB script or VB6.</p>
<p>First you need to download the latest version and then open the MSGReader project, set Platform target to X86 & then build the code in release mode, Get"MsgReader.dll" file from BuildOutput folder & Copy the file to the desired location. After that Register the file for COM interop using the following command.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read & Save Outlook MSG Message Attachment using .NET</h2>
<p>MSGReader enables C# developers to access email message & its attachment of an Outlook MSG and EML file. It provides support for reading an Outlook MSG file and save the message body and all its attachments to an output folder</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Read MSG data - C#</h3>
<pre><code class="C#">// Read a email .msg file
Message message = new MsgReader.Outlook.Storage.Message("fileformat.msg");
// Read sender
Console.WriteLine("Sender:" + message.Sender);
// Read sent on
Console.WriteLine("SentOn:" + message.SentOn);
// Read recipient to
Console.WriteLine("recipientsTo:" + message.GetEmailRecipients(MsgReader.Outlook.RecipientType.To, false, false));
// Read recipient cc
Console.WriteLine("recipientsCc:" + message.GetEmailRecipients(MsgReader.Outlook.RecipientType.Cc, false, false));
// Read subject
Console.WriteLine("subject:" + message.Subject);
// Read body html
Console.WriteLine("htmlBody:" + message.BodyHtml);
</code></pre>

<h2 class="h2title">Convert Outlook MSG as Text File using .NET API</h2>
<p>MSGReader API provides the features for saving outlook MSG as text file using .NET API. Developers can easily access the MSG file contents. Create an instance of the save file dialog box and save the message as TXT file format.</p>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}