---
title: Build & Send Email Messages, Attach Files via Open Source PHP APIs
description: PHPMailer - Open Source PHP API to Send Email to Multiple users via To, CC, BCC & Reply-to addresses. Make SMTP Connection & send email messages via Gmail sever.
keywords: PHP mailing library, PHP email API, free PHP Library, Open Source email Library, PHP PST programming, PHP EML, java Outlook MSG, Add Attachments to Email, PHP eml library, create  MSG email, Extract email messages, PHP outlook, PHP PST development, Conversion b/t MimeMessage, Conversion b/t EML and Outlook MSG
draft: false
weight: 11



ProductName: PHPMailer 
Githublink: https://github.com/PHPMailer/PHPMailer
ListingPage_Short_Description: Open surce PHP library that creates application for building and sending email messages with minimum effort and cost.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHPMailer"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source PHP API for Email Processing"
Header_H2_Text="PHP library that allows to attach and send multiple files, compose and send email messages to multiple users via To, CC, BCC, and Reply-to addresses." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>PHPMailer is an open source PHP email sending library that enables software developers to create applications for building and sending email messages with minimum effort and cost. It also provides support for making an SMTP connection with authentication as well as sending email messages using Gmail servers.</p>
<p>The library has provided the capability to send emails to multiple users via To, CC, BCC, and Reply-to addresses. It also allows users to encode email messages using UTF-8 content and 8bit, base64, binary, and quoted-printable encodings. It also enables users to attach and send multiple files with ease. </p>
<p>The library has provided multiple methods for sending email messages. The library provides several important features for email management such as add attachments to an email message, automatic email validation, error handling in over 50 languages, S/MIME and DKIM signing support, Integrated SMTP support, protection from header injection attacks, and many more.</p>

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
<p>An overview of PHPMailer features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Send emails</li>
<li>Receive emails</li>
<li>Read emails</li>
<li>Multiple attachment</li>
<li>View attachment</li>
<li>Save attachment</li>
<li>Email encryption</li>
<li>Use Gmail sever</li>
<li>SMPT support</li>
<li>IMAP support</li>
<li>
</ul>
</div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="docxtemplater library "><header>PHPMailer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache PHPMailer supports popular Microsoft Outlook file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/email/msg/">MSG</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="docxtemplater library "><header>PHPMailer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>PHPMailer only requires PHP run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>PHP 5.2 and above.</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="docxtemplater library "><header>PHPMailer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PHPMailer</h2>
<p>The recommended way to install PHPMailer is via Composer, please use the following command for easy installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install PHPMailer API via Composer </h3>
<pre><code class="html">composer require phpmailer/phpmailer <br></code></pre>
You can also <a href="https://github.com/PHPMailer/PHPMailer/archive/master.zip">download</a> it from GitHub and manually install it with ease.

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Send Email Message via PHP API</h2>
<p>Sending emails messages in PHP is a very common approach nowadays adopted by software developers. The PHPMailer library gives software developers the power to send email messages inside their own applications with a couple of PHP commands. The library also supports sending plaintext emails for non-HTML email clients. You can also send emails from a local webserver with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Send Email Message to a List via PHP</h2>
<p>The open source library PHPMailer is usually used to send an email message to mailing lists.  The library is very reliable and can send emails a message to a whole list of recipients proficiently. After setting up a PHPMailer instance using SMTP, they can connect to a MySQL database to retrieve a list of recipients. You can set your custom email messages as well as one particular one to all recipients.  You can also select some specific users from the list for sending emails.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Multiple Attachment to Email</h2>
<p>It is often required to share multiple files among your team members or with the customers.  The PHPMailer is a very powerful library that gives software developers the capability to send emails with multiple attachments. It uses a very simple form that accepts a file upload and emails it. On the other hand, it is a little more complex form that allows uploading multiple files at once and sends all of them as attachments to an email.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Sending Email via Gmail</h2>
<p>The open source library PHPMailer gives software developers the capability to send their email messages via Google’s Gmail service. To send emails via Gmail servers you need some more settings than normal SMTP settings.  It uses id & password authentication. You can use the IMAP commands to save messages to a folder.  You can also get a list of available folders or labels using an IMAP commands</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}