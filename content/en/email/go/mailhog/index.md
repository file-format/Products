---
title: Open Source GO Library for Testing Email Messages
description: MailHog- Open Source Go Library for IMAP, POP3 & SMTP. Generate Message with Attachments, Encrypt/Decrypt Messages with PGP/MIME.
keywords: Free Go library,  GO API, GO MSG Library, Open Source outlook Library, GO POP3 library, create  MSG Documents, SMTPGO .GO Libraries, GO outlook, GO IMAP, GO EML, c-sharp, email, mime, mime-parser, dkim, smime, smtp, imap, pop3, imap-client, pop3-client, smtp-client
draft: false
weight: 15



ProductName: MailHog
Githublink: https://github.com/mailhog/MailHog
ListingPage_Short_Description: Free Email Testing Tool for developer, developed in GO.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free Email Testing Tool for developer, developed in GO."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Testing Email Messages"
Header_H2_Text="Free Email Testing Tool for developer, developed in GO." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>MailHog is an Open Source email testing tool for developers. You can configure your applictions to use MailHog for SMTP delivery, you can reterive email messages with the JSON API or view them in the web UI. You can also end messages to real SMTP servers.</p>
<p>MailHog implement ESMTP server implementation, supports SMTP AUTH and PIPELINING, provides Web interface to view text or HTML emails, display real time email updates and releases emails to real SMTP servers. Furthermore, the API supports multipart MIME & allows downlading indiviual MEME parts. MailHog uses In-memory message storage and uses MongoDB and file based storage for message persistence.</p>
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
<li>From, To, Cc, Bcc</li>
<li>Format Address</li>
<li>Text Email</li>
<li>HTML Email</li>
<li>Attachments</li>
<li>Read Receipts</li>
<li>Custom Headers</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Email</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Email supports popular compression file formats listed below.</p>
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
<div class="d1-logo" style="border: none;"><header>MailKit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MailHog Requires Go 1.4+ to build..</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Go v1.4 or above.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Email</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with MailHog</h2>
<p>MailHog is built with GO that runs withour installation on multiple platofrms</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Run MailHog on MacOS</h3>
<pre><code class="html">brew update && brew install mailhog</code></pre>

You can start running MailHog in MacOs by running mailhog in the command line.
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Configure MailHog for Outgoing SMTP</h2>
<p>In order to configure outgoing SMTP you need to create JSON file with the following structure and set MH_OUTGOING_SMTP or -outgoing-smtp.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">{
"server name": {
    "name": "server name",
    "host": "...",
    "port": "587",
    "email": "...",
    "username": "...",
    "password": "...",
    "mechanism": "PLAIN"
}
                        }</code></pre>
<p>In the JSON file, only name, host and port are requried to send SMPT email.</p>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}