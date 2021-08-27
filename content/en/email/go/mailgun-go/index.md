---
title: Go API for Email Management – Built-in Polling & Email Templates Support
description: mailgun-go - Open Source Go API for emails management. It included built-in support for polling and email templates. Create and send emails using SMTP Server.
keywords: Free Go library,  GO API, GO MSG Library, Open Source outlook Library, GO POP3 library, create  MSG Documents, SMTPGO .GO Libraries, GO outlook, GO IMAP, GO EML, c-sharp, email, mime, mime-parser, Built-in Polling support, use email templates
draft: false
weight: 19



ProductName: Mailgun-go
Githublink: https://github.com/mailgun/mailgun-go
ListingPage_Short_Description: It has included support for polling as well as email templates and enables programmers to create and send emails using SMTP Server.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="GO Library that has included built-in support for polling and email templates and enables software programmers to compose, send & track emails using SMTP Server."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go  API to Manage Email Messages"
Header_H2_Text="GO Library that has included built-in support for polling and email templates and enables software programmers to compose, send & track emails using SMTP Server." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>A powerful Go API that gives software programmers the ability to manage their email messages inside their own apps using Mailgun API. The mailgun-go library is very easy to use and allows developers to send, receive as well as track their email messages painlessly.</p>
<p>The library has built-in support for polling and email templates.  It fully supports some common email-related features such as composing an email message, sending using Bcc and Cc fields, add custom email headers, add attachments, read receipts, and many more.</p>
<p>The library is very reliable and has a powerful email sending mechanism.  You can easily send emails to a high number of users with maximum accuracy.  It has included several important features related to emails such as email sending and receiving, track emails, event polling, email validation, send emails using email templates, and so on.</p>
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
<p>An overview of mailgun-go features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Send Email</li>
<li>Track emails</li>
<li>Event poling</li>
<li>Email validation</li>
<li>SMTP</li>
<li>From, To, Cc, Bcc</li>
<li>Add images</li>
<li>Text Email</li>
<li>HTML Email</li>
<li>View attachment</li>
<li>Save attachment</li>
<li>Email encryption</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>mailgun-go</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>mailgun-go supports popular file formats listed below.</p>
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
<div class="d1-logo" style="border: none;"><header>mailgun-go</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>mailgun-go requires the following</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Go v1.2 or above.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>mailgun-go</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with mailgun-go</h2>
<p>The easiest way to install mailgun-go is via GitHub. Please first you need to <a href="https://github.com/mailgun/mailgun-go/archive/master.zip">download</a> it and then can easily install it using the following command for easy installation. .</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install mailgun-go via GitHub</h3>
<pre><code class="html"> $go get github.com/mailgun/mailgun-go</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compose and Send Email Messages via Go API</h2>
<p>The open source mailgun-go library has included complete support for sending and receiving email messages using a couple of lines of Go commands. You can easily retrieve and view your email messages as well as other related information. It allows you to compose your email messages, attaché files or images, add a subject, use recipient list, and so on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Attach Files to Email Message via Go</h2>
<p>The email attachment is a useful process for sending a computer file along with your email messages.  The free library mailgun-go enables software engineers to develop apps that can easily attach files to an email message with just a couple of lines of Go code. Developers can easily attach multiple files such as PDF, MS Word, Spreadsheets, ZIP files to an email message.  The library also provides support for retrieving or deleting the existing attachments.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Email Templates Support</h2>
<p>The open source mailgun-go library gives software developers the capability to use email templates for creating and sending emails. It allows developers to create message templates on your Mailgun account and then can call it on the client-side. This allows you to have your layout and design managed on the server and handle the data on the client.</p>
<h2 class="h2title">Email Validations Support</h2>
<p>Quality data collection is always the demand for an organization. The email validation process is one of the most effective way of verifying the validity of the email address. The open source library mailgun-go has provided functionality for validating email addresses with just a couple of lines of code.</p>
<p> </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}