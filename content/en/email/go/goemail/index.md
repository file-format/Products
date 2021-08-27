---
title: Free GO API, to send emails using SMTP Server
description: GoEmail- Open Source Go Library for SMTP. Generate Message with Attachments, Encrypt/Decrypt Messages with PGP/MIME.
keywords: Free Go library,  GO API, GO, GO Email, Email Attachment, HTML Email, Text Email, Free GO API, Free Email Message, MSG Library, Open Source outlook Library, GO POP3 library, create  MSG Documents, SMTPGO .GO Libraries, GO outlook, GO IMAP, GO EML, c-sharp, email, mime, mime-parser, dkim, smime, smtp, imap, pop3, imap-client, pop3-client, smtp-client
draft: false
weight: 17



ProductName: GoEmail
Githublink: https://github.com/go-gomail/gomail
ListingPage_Short_Description: Free GO API, to send emails using SMTP Server.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free GO API, to send emails using SMTP Server."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library to Send Email Messages"
Header_H2_Text="Free GO API, to send emails using SMTP Server." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>GoEmail is an simple open source GO API for sending email messages. Using the API, you can send email using SMTP server, but the API provides the flexablility to send email message using local postfix. The API is lightweight and has no external dependencies when you are using Go 1.5 where as for the API to work you need atleast Go version 1.2 or greater. While using the SMPT connection, the API allows sending multiple emails using the same SMTP connection.</p>
<p>The API provides a bunch of feautes for the developers to ease the Email sending operation within GO. The developers can send SMPT emails, add attachments in email, embed images in your message and use HTML or text templates for generating a new email message. The API automatically encodes special character in the message and provides supports for SSL and TLS certificates.</p>
<p><span style="font-size: 12.16px;">. </span></p>

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
<p>An overview of go-email features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create Email</li>
<li>SMTP</li>
<li>From, To, Cc, Bcc</li>
<li>Emabed Images</li>
<li>Text Email</li>
<li>HTML Email</li>
<li>Attachments</li>
<li>SSL</li>
<li>TLS</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Go-Email</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Go-Email supports popular file formats listed below.</p>
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
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Go-Email</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Go-Email requires the following</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Go v1.2 or above. With Go 1.5, no external dependencies are used</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Go-Email</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Go-Email</h2>
<p>The recommended way to go-email into your project is by using GitHub. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Go-Email via GitHub</h3>
<pre><code class="html">go get gopkg.in/gomail.v2</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Free GO API to Send Email Messages</h2>
<p>The open-source API Go provides an efficent way to compose email message via SMTP connection. In order to create a new email, you can create a new message instance by using NewMessage() method. The API provides different methods to set From, To, Subject and Body. In order to set From, To & Subject, you can use SetHeader() method of the API. Similary for the insert data in body of the email, you use SetBody() method of the API. Once, you have your email content ready you can open a new SMTP connection NewDialer() method by provinding SMPT connection details. Once you have your connention open, the message can be delivered to the destination.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}