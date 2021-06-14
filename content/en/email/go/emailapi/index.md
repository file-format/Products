---
title: Open Source GO Library for Email Messages
description: Email- Open Source Go Library for IMAP, POP3 & SMTP. Generate Message with Attachments, Encrypt/Decrypt Messages with PGP/MIME.
keywords: Free Go library,  GO API, GO MSG Library, Open Source outlook Library, GO POP3 library, create  MSG Documents, SMTPGO .GO Libraries, GO outlook, GO IMAP, GO EML, c-sharp, email, mime, mime-parser, dkim, smime, smtp, imap, pop3, imap-client, pop3-client, smtp-client
draft: false
weight: 14



ProductName: Email
Githublink: https://github.com/jordan-wright/email
ListingPage_Short_Description: Free GO .NET Library for Generating Email Message with Attachments.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free GO .NET Library for Generating Message with Attachments."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Email Messages"
Header_H2_Text="Free GO .NET Library for Generating Message with Attachments." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Email is an Open Source robust and flexible email libray for GO developers. It is a lightweight and simple email pakcage to provide email interface for humans. Using the API you can create a new email, set From, To Bcc and CC set email addresses in diffrent formats, use text & HTML in email body, and manage attachments. Furtheremore, the API allows designing custom email headers and allows reading receipts.</p>
<p>Using the API you can create an email for any type that implements the io.Reader infercae e.g you can send emails using your Gmail acocunt by setting email proporties directly from the struct.</p>
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
<li><a href="https://wiki.fileformat.com/email/msg/">MSG </a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://wiki.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Email</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Version &gt; 1 of this library requires Go v1.5 or above.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Go v1.5 or above.</li>
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
<h2 class="h2title">Getting Started with Email</h2>
<p>The easiest way to install Email is via GitHub. You can the following command to install Email Go API</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>install Email API via GitHub</h3>
<pre><code class="html">go get github.com/jordan-wright/email</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create New Messages via Free Go API</h2>
<p>The Open Source API Email library enables software developers to create email message via GO. Creating a new email with the API is pretty simple. You can start creating email by creating a new emial instance by using emial.NewEmail() method. You can set From, To Bcc and CC by using the propeties of new created email instance - email.From = = "John Don &lt;<span id="cloak525985d4645c6be117866f941a2cadf5">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloak525985d4645c6be117866f941a2cadf5').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addy525985d4645c6be117866f941a2cadf5='t&#101;st'+'&#64;';addy525985d4645c6be117866f941a2cadf5=addy525985d4645c6be117866f941a2cadf5+'gm&#97;&#105;l'+'&#46;'+'c&#111;m';var addy_text525985d4645c6be117866f941a2cadf5='t&#101;st'+'&#64;'+'gm&#97;&#105;l'+'&#46;'+'c&#111;m';document.getElementById('cloak525985d4645c6be117866f941a2cadf5').innerHTML+='<a '+path+'\''+prefix+':'+addy525985d4645c6be117866f941a2cadf5+'\'>'+addy_text525985d4645c6be117866f941a2cadf5+'<\/a>';</script>&gt;", email.To, email.Bcc and email.Cc respectively. Similary setting Subject and Body is peice of cake aswell. You can set the subject using, email.Subject and set body either by using email.Text or email.HTML method. When you have your email content ready, you can send it using email.Send() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Free GO API to Create Email with Attachments</h2>
<p>Email API provides features for generating a message with attachments inside GO applications.  Attachments are just like any other properties of email API. Just like you set From, To, Ccc, Bcc and subject, you can add attachments using email.AttachFile() method</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}