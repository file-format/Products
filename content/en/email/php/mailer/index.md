---
title: Open Source PHP Library - Create & Send Email Messages, Attach Files
description: Mailer - Open Source PHP Library to Create & send Email messages to multiple users, attach files, Emails encryption & using tags or metadata in emails inside PHP apps.
keywords: PHP mailing library, PHP email API, free PHP Library, Open Source email Library, PHP PST programming, PHP EML, java Outlook MSG, Add Attachments to Email, PHP eml library, create MSG email, Extract email messages, PHP outlook, PHP PST development, Conversion b/t MimeMessage, Conversion b/t EML and Outlook MSG
draft: false
weight: 13



ProductName: Mailer
Githublink: https://github.com/symfony/mailer
ListingPage_Short_Description: It helps software programmers to send emails from their PHP applications as well as offers easy integration with other popular mailing services.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHP API that allows sending messages with attachment, sending messages to multiple users, Twig integration, UTF-8 characters support and so on."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP Library to Send Email Messages"
Header_H2_Text="PHP API that allows sending messages with attachment, sending messages to multiple users, Twig integration, UTF-8 characters support and so on." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The Mailer and Mime components are useful parts of the Symfony framework for creating and sending email messages. It is open source and is available under the MIT License. The component helps software programmers to send emails from their PHP applications as well as offers easy integration with other popular mailing services. There two main parts of the Mailer component the Transport and Mailer itself.</p>
<p>The great thing about the Symfony's mailer component is the high availability. It uses a technique known as"failover" which make sure that emails are sent even if one mailer server fails. The failover transport is configured with two or more transports. So if one fails it will automatically switch to the other transport to complete the sending task. It also effectively manage load balancing and uses the “round-robin” technique to distribute the mailing workload across multiple transporters.</p>
<p>The Mailer component supports several important features related to email message handling such as sending messages with attachments, sending messages to multiple users, multipart messages support, Twig integration, UTF-8 characters support, embed images inlining CSS Styles, messages encryption, and many more.</p>


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
<p>An overview of Mailer features.</p>
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
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Mailer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Mailer supports popular file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/email/msg/">MSG </a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a>, MSG</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Mailer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Mailer requires the following</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>PHP 5.3 or above.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Mailer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Mailer </h2>
<p>The recommended way to install the Mailer component is via Composer, please use the following command for easy installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Mailer via GitHub</h3>
<pre><code class="html"> $ composer require symfony/mailer</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate and Send Emails via PHP Library</h2>
<p>The open source Mailer library supports email message creation and sending via PHP code. Developers need to create email object and provide the required information. Once ready the message will be sent to the recipients via the configured transport. You can easily send emails to multiple users by select fields like From, To, Bcc, and Cc fields. You can also easily attach files, embed images, and include other contents inside your email messages.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Attach Files and Images to Emails via PHP</h2>
<p>Sharing documents and photos as<em> email attachments</em> is easy and cost-effective. Moreover, it is often required to share up-to-date data and files for the timely completion of collaborative tasks. One fast and easy way to do this is via email attachments. The Mailer library enables software developers to easily attach and send documents like PDF, Microsoft Word, Images, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Email Messages Encryption Support</h2>
<p>Encryption helps users to protect their email messages from unwanted access and preventing hackers from accessing secure data and messages. The open source Mailer library has included complete support for email message encryption using PHP commands. A certificate is used while encrypting an email message. It encrypts the entire message including attachments, images, contents, etc. Once the message is delivered the recipients that have the corresponding key can access and read the message.</p>
<h2 class="h2title">Use Tags and Metadata in Emails</h2>
<p>The open source Mailer library supports adding tags and metadata to your email messages with ease. They are useful for grouping emails together, tracking emails, and workflow. Please remember that your transport will convert them to their appropriate format if it supports headers otherwise it does not support tags and metadata, they will be added as custom headers inside your emails.</p>
<p> </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}