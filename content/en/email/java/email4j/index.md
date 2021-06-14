---
title: Java API for Email Management via SMTPClient, POP3Client & IMAPClient
description: Email4J - Open Source Java Library for emails management. It supports SMTPClient, POP3Client & IMAPClient. You can add attachments, embedded images & more.
keywords: Java mailing library, Java email API, free java Library, Open Source email Library, Java PST programming, java EML, java Outlook MSG, Add Attachments to Email, Java eml library, create  MSG email, Extract email messages, Java outlook, Java PST development, Conversion b/t MimeMessage, Conversion b/t EML and Outlook MSG
draft: false
weight: 9



ProductName: Email4J
Githublink: https://github.com/juandesi/email4j
ListingPage_Short_Description: Free Java library allows to access, read, send Email messages. You can add attachments, mark emails, move messages, delete a particular email inside Java apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Java library that supports access, read, send Email messages. You can add attachments, mark emails,  move messages, delete a particular email inside Java apps."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Free Java API for Email Management"
Header_H2_Text="Open Source Java library that supports access, read, send Email messages. You can add attachments, mark emails,  move messages, delete a particular email inside Java apps." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Email4J is an open source Java library that enables software developers to handle tasks related to email management inside their own Java applications without worrying about the internal complexities.  The library is very useful and easy to handle. It supports features like compose email messages, sending emails, add headers and attachments, copy emails, read email messages, mark emails,  move messages, delete a particular email, listing folders, and much more.</p>
<p>Email4J is a high-level java library built on top of the javax.mail api that provides the capability for handling and sending emails messages with ease. The library supports connectivity with different email clients such as SmtpClient, Pop3Client, and ImapClient. By using these clients you can easily access and manage your emails.  Each client has a particular set of operations and works underlying used protocol.</p>

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
<p>An overview of Email4J features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read emails</li>
<li>CRLF injection attacks</li>
<li>OST support</li>
<li>Embedded images</li>
<li>Add custom headers</li>
<li>CLI support</li>
<li>S/MIME support</li>
<li>Batch processing</li>
<li>Add attachments</li>
<li>Batch processing</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img class="bg-lite" src='listing-image.png' alt="Apache POI" />--><header>Email4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Email4J supports popular email file formats as listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><span class="wikilink"><a href="https://wiki.fileformat.com/email/eml/">EML</a>, <a href="https://wiki.fileformat.com/email/pst/">PST</a></span></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a>,<span class="wikilink"> EML, PST</span></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img class="bg-lite" src='listing-image.png' alt="Apache POI" />--><header>Email4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Simple Java Mail only requires Java run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>JDK 1.6 or higher</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img class="bg-lite" src='listing-image.png' alt="Apache POI" />--><header>Email4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Email4J</h2>
<p>The easiest way to install Email4J is via GitHub. Please first you need to <a href="https://github.com/bbottema/simple-java-mail/archive/develop.zip">download</a> it and then can easily install it using the following command for easy installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Email4J via GitHub</h3>
<pre><code class="html">git clone --depth=1 https://github.com/juandesi/email4j.git  </code></pre>

<p>Dependency that needs to be added to pom.xml file is,</p>
<h3>Maven Dependency</h3>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Accessing and Reading Email via Java Library</h2>
<p>The free Email4J library enables Java developers to access & read email messages inside their own applications with a couple of lines Java code. Firstly you need to provide the correct path to the folder containing the emails. The library also enables users to view folders and emails inside these folders. You can easily retrieve information related to email messages such as email Subject, attachments,  email body, recipient list, and much more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Send Email via SMTPClient</h2>
<p>The open source Java library Email4J enables software developers to send email messages by using the Simple Mail Transfer Protocol (SMTP). The client mainly focuses on the operation to send the mail to the specified recipients that it receives. You can also include an attachment to an email message. Firstly you need to create the attachment and then the latter can add it to the message. The library has provided a simple builder, that can be used to build the outgoing emails.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manage Emails via IMAPClient</h2>
<p>The free Java library Email4J has provided the capability to access and manage email messages by using the Internet Message Access Protocol (IMAP). The ImapClient directly communicates with a mailbox and users can easily retrieve, read, move, mark, or delete email messages. You need to provide a correct path to the folder containing the emails and the client will retrieve all of them for you with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}