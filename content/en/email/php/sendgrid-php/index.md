---
title: Send Email Messages & Get Them Delivered via Open Source PHP Library
description: Sendgrid-php - Open Source PHP Library for sending email messages to single or multiple recipients, transactional templates support, viewing email statistic & so on.
keywords: PHP mailing library, PHP email API, free PHP Library, Open Source email Library, PHP PST programming, PHP EML, java Outlook MSG, Add Attachments to Email, PHP eml library, create MSG email, Extract email messages, PHP outlook, PHP PST development, Conversion b/t MimeMessage, Conversion b/t EML and Outlook MSG
draft: false
weight: 12



ProductName: Sendgrid-php 
Githublink: https://github.com/sendgrid/sendgrid-php
ListingPage_Short_Description: Free PHP API that allows creating and sending email messages to single or multiple recipients, transactional templates and much more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Sendgrid-php"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP Library for Emails"
Header_H2_Text="Free PHP API that allows creating and sending email messages to single or multiple recipients, transactional templates, viewing email statistic and much more." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Sendgrid-php API makes developer's life easy by providing complete functionality for sending email messages through SendGrid using PHP. SendGrid is cloud-based email deli service and handles all the heavy tasks involved in sending messages and getting them delivered. It is easy to use inside your own application and allows users to fully integrate with SendGrid.</p>
<p> The library is flexible and makes it easy for the user to do custom integration. It provides several important features related to email management using PHP commands, such as sending an email message to single or multiple recipients, adding attachments, sending multiple emails to multiple recipients, transactional templates support, viewing email statistic, sending an SMS message, sending receipts to customers automatically and many more.</p>

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
<p>An overview of Sendgrid-php features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>create emails</li>
<li>Send emails</li>
<li>Read emails</li>
<li>Add attachments</li>
<li>View attachment</li>
<li>Email encryption</li>
<li>Email statistics</li>
<li>SMPT support</li>
<li>Email tracking<br><br></li>
</ul>
</div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHP mailing library"><header>Sendgrid-php</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Sendgrid-php supports popular Microsoft Outlook file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/email/msg/">MSG</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHP mailing library"><header>Sendgrid-php</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Sendgrid-php only requires PHP run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>PHP 5.2 and above.</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHP mailing library"><header>Sendgrid-php</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Sendgrid-php</h2>
<p>It is highly recommended to use Composer for installing Sendgrid-php, library. You can <a href="https://getcomposer.org/doc/00-intro.md">download</a> composer and after that can easily install the library using the following command. For smooth working, you need to create a SendGrid account and create an <a href="https://app.sendgrid.com/settings/api_keys">API Key</a></p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Sendgrid-php API via Composer </h3>
<pre><code class="html">composer require sendgrid/sendgrid </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Send Emails a Single or Multiple Users via PHP API</h2>
<p>The sendgrid-php library allows PHP programmers to programmatically sending email messages from their own PHP applications. The library has included several useful functions for sending and receiving email messages, such as sending emails to a single recipient, sending email messages to multiple users, sending multiple email messages to multiple users, add attachments to emails, sending email messages with Twilio Email and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Attachments to Emails via PHP</h2>
<p>Sending email attachments are commonly used to share data with multiple users inside an organization. The open source email library sendgrid-php, enables support developers to send email messages with multiple attachments inside their own PHP applications. You can easily attach multiple files using addAttachments method. The library supports attaching files from Box as well as from Amazon S3 storage to your emails. It is easy to attach PDF documents, a word processing file, a photograph, a spreadsheet document, and or anything else.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Email Statistics Support</h2>
<p>The free email library sendgrid-php has included complete support for accessing and viewing email statistics inside your own applications using PHP. The library provided several ways to check and view global as well as user statistics. You can retrieve all of your global email statistics between a given date range, retrieve statistics of sub-users, retrieve the monthly email statistics for all sub-users, view statistics for up to 10 different sub-users, retrieve monitor settings for a sub-user, and son on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create and Use Transactional Email Templates</h2>
<p><strong>The </strong>sendgrid-php library has provided support for sending email messages with a transactional template. You can easily create your own email templates using HTML, CSS and some content. It is always a good practice to test your templates before sending them to customers. For an easy start, you can use a free template from the internet and modify it according to your own needs. It is recommended to use table-based HTML templates as many popular email apps only read table-based HTML. You can easily modify and duplicate you templates.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}