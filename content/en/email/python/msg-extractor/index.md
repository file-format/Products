---
title: Open Source Python API to Read & Parse Outlook MSG Files | MSG Extractor
description: MSG Extractor - Open Source Python API for Reading & Parsing Outlook MSG Files. The Library allows to access read & extract Email messages from MSG files.
keywords: Python MSG, Python email, Python API, Python outlook, access MSG contents, Python email APIs, Python Outlook API, Python MSG API, Python email library, read outlook MSG, view email messages, extract attachments from MSG, Open Source python email, Open Source Email API
draft: false
weight: 10



ProductName: MSG-Extractor
Githublink: https://github.com/TeamMsgExtractor/msg-extractor
ListingPage_Short_Description: Develop Python applications having the ability to read and access Microsoft Outlook MSG Files using open source Python libraries.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read & parse Microsoft<sup>®</sup> Outlook MSG emails via Python."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Python Library for Outlook<sup>®</sup> MSG Files"
Header_H2_Text="Read & parse Microsoft<sup>®</sup> Outlook MSG emails via Python." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is MSG-Extractor Library?</h2>
<p>MSG-Extractor gives software developers the ability to process Microsoft Outlook MSG files from Python apps. It automates the extraction of key email data such as from, to, cc fields as well as subject, body, date, and attachments. The Python MSG library also supports features such as reading an email message, extracting attachments, embedding MSG files, command-line arguments and save attachments to custom location. </p>

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
<p>An overview of MSG-extractor features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Access MSG</li>
<li>Extract textual info</li>
<li>Get headers</li>
<li>Extract Sender Info</li>
<li>Extract Subject</li>
<li>Extract Body</li>
<li>Extract attachments</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MSG-extractor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MSG-extractor supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/email/msg/">MSG</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MSG-Extractor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MSG-Extractor only requires Python.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><!--<header><i class="fa fa-cubes">` </i></header-->
<ul>
<li>Python 2.7 and 3.4</li>
</ul>
</div>
<!--/left
  <div class="d1-col d1-right">&nbsp;</div>--> <!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="MSG Python APIs" />--><header>MSG-Extractor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">How to Install MSG-Extractor?</h2>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install via MSG-Extractor via PyPi</h3>
<pre><code class="html"> pip install extract-msg </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Open MSG File via Python</h2>
<p>The MSG-Extractor library allows Python developers to access & read contents of Outlook MSG files. You can access the email recipient addresses as well as view email messages & attachments. By using the following lines of code, you can easily read message via python</p>
<h3>Open MSG File</h3>
<ol>
<li>Open existing MSG file using extract_msg.Message() method and pass file name as parameter</li>
<li>Get and print sender of the email using msg.sender property</li>
<li>Get and print date of the email using msg.date property</li>
<li>Get and print subject of the email using msg.subject property</li>
<li>Get and print message body of the email using msg.body property</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Python Dependency for MSG-Extractor</h3>
<pre><code class="python">f = r'MS_Outlook_file.msg' 
# open message
msg = extract_msg.Message(f)
# print sender name
print('Sender: {}'.format(msg.sender))
# print date
print('Sent On: {}'.format(msg.date))
# print subject
print('Subject: {}'.format(msg.subject))
# print body
print('Body: {}'.format(msg.body))</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Save Attachments & Messages</h2>
<p>MSG-Extractor library enables the extraction of attachments from Outlook MSG files. The API provides the functionality to scans all the email messages stored in MSG and displays the list of messages that it finds. Users can select the attachments of their choice and save it to a chosen folder. It also allows users to delete unwanted files.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}