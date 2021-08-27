---
title: Open Source Swift Email Library – Create & Send Messages with Attachment
description: Hedwig - Swift API that allows sending messages with attachment, sending messages to multiple users, Twig integration, UTF-8 characters support, and so on.
keywords: Swift mailing library, Swift email API, free Swift Library, Open Source email Library, Swift  MSG  programming, Swift Outlook MSG, Add Attachments to Email,  create  MSG email, Extract email messages, Swift outlook, encode email messages, POP3 support, SMTP support, Parse Email messages, send attachments to multiple users, encode email messages, Twig integration, UTF-8 characters support
draft: false
weight: 23



ProductName: Hedwig
Githublink: https://github.com/onevcat/Hedwig
ListingPage_Short_Description: Open surce Swift library that enables software developers to generate and parse email messages inside their own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free Swift API that allows developers to send messages with attachments, sending messages to multiple users, mail validation and customization, mail header support, and so on."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Swift  Library for Email Management "
Header_H2_Text="Free Swift API that allows developers to send messages with attachments, sending messages to multiple users, mail validation and customization, mail header support, and so on." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The Hedwig Swift library gives software developers the ability to create and send email messages to any SMTP server inside their own swift applications. The library is very easy to use and can be used on multiple platforms.  The library is open source and released under the MIT license.  The library can be easily connected to all SMTP servers, using whether plain, SSL, or TLS port.</p>
<p>The Hedwig is pure Swift implementation and has provided several important features related to email messages handling such as create emails, email authentication support, send email messages with HTML body, add attachments to emails, send emails to multiple users, inline image support, read email messages, email validation, and customization, mail header support, queued mail sending, send mails concurrently and so on. The library is very stable and enables users to handle email messages more efficiently.</p>

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
<p>An overview of Hedwig features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Generate message</li>
<li>Send Email</li>
<li>Multipart messages</li>
<li>Track emails</li>
<li>Add images</li>
<li>Text Email</li>
<li>HTML Email</li>
<li>View attachment</li>
<li>Save attachment</li>
<li>Email encryption</li>
<li>Twig integration</li>
<li>UTF-8 characters</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Hedwig</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Hedwig supports the popular email file formats as listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/email/msg/">MSG </a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a>, MSG</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Swift </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Hedwig requires the following</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Swift.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Hedwig</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Hedwig</h2>
<p>The easiest way to install the Hedwig library is via GitHub. Please first need to <a href="https://github.com/onevcat/Hedwig/archive/master.zip">download</a> it and then can easily install it using the following command for easy installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Hedwig via GitHub</h3>
<pre><code class="html"> go get https://github.com/onevcat/Hedwig.git</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Email Creation & Sending via Swift Library</h2>
<p>The open source Hedwig library enables software programmers to compose and send email messages inside their Swift applications. You need to provide a message title as well message body.  The library has provided support for sending text as well as HTML-based email messages. You can also send an email message to multiple users using CC and BC options. Once all the required information is provided the email message will be directed to all the provided recipients.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Send Emails with Attachments vis Swift Library</h2>
<p>The Hedwig library has provided complete functionality for sending email messages with attachments using Swift commands. The library has provided several ways to add attachments to your email messages, such as create an attachment from a local file path, embed image attachments in HTML, and create attachments from raw data. You can also access and read attachments with just a couple of lines of code.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read Existing Email Message</h2>
<p>The open source Hedwig library allows developers to programmatically access and read email messages inside their own Swift apps. You can access emails using SMTP settings (security layer, authentication method, etc.). You can use multiple methods to access incoming emails such as the most recent emails, emails sorted by name or date, view messages in ascending or descending order, and so on.</p>
<h2 class="h2title">Use Custom Email Headers</h2>
<p>The free email Hedwig enables programmers to add custom headers to their email messages inside their own Swift applications with ease. It encompasses very useful information related to the email transmission process and helps users to track their email messages with ease.  The Hedwig library allows you to manage your custom headers with ease.</p>
<p> </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}