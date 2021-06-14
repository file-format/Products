---
title: Open Source Ruby Library - Email Messages Generation Parsing & Encoding
description: Mail - Open Source Ruby API to Generate, Parse & Send Email messages with attachments to multiple users, encode email messages, POP3 and SMTP support & so on.
keywords: Ruby mailing library, Ruby email API, free Ruby Library, Open Source email Library, Ruby  MSG  programming, Ruby Outlook MSG, Add Attachments to Email,  create  MSG email, Extract email messages, Ruby outlook, encode email messages, POP3 support, SMTP support, Parse Email messages, send attachments to multiple users, encode email messages
draft: false
weight: 20



ProductName: Mail
Githublink: https://github.com/mikel/mail
ListingPage_Short_Description: Open surce Ruby library that enables software developers to generate and parse email messages inside their own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free Ruby API that allows Email messages generation & parsing, sending messages with attachments to multiple users, Twig integration, UTF-8 characters support, and so on."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Ruby Library for Email Messages "
Header_H2_Text="Free Ruby API that allows Email messages generation & parsing, sending messages with attachments to multiple users, Twig integration, UTF-8 characters support, and so on." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Mail is an open source Ruby library that gives software programmers the power to develop apps for email messages generation and receiving using Ruby code.  It is a pure ruby implementation and has provided several important features related to email messages generation and parsing such as access and read email messages, reading UTF-8 headers support, multipart email support, creating a multipart alternate email,  POP3 and SMTP support, Auto-encoding of non-US-ASCII bodies and much more.</p>
<p>The modern version of Ruby has included more advanced features for handling text encoding that’s where Mailer library is very useful as it is designed to work with lower as well as a modern version of Ruby equally.  So it is now capable to handle email messages more efficiently. Developers can also create MIME emails with ease.</p>
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
<p>An overview of Mail features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Send emails</li>
<li>Parse emails </li>
<li>multipart email</li>
<li>Read emails</li>
<li>Add attachments</li>
<li>Save attachment</li>
<li>Email encoding</li>
<li>POP3 support</li>
<li>UTF-8 headers</li>
<li>SMPT support</li>
<li>IMAP support</li>
<li>Auto-encoding</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Mail</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Mail supports popular file formats listed below.</p>
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
<li><a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://wiki.fileformat.com/web/html/">HTML</a>, MSG</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Mail</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Mail requires the following</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Ruby SDK</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Mail</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Mail</h2>
<p>The easiest way to install the Mail library is via RubyGems. Please use the following command for easy installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Mail via Rubygems</h3>
<pre><code class="html"># gem install mail</code></pre>

<p>You can also use <a href="https://github.com/mikel/mail/archive/master.zip">GitHub</a> to manually download and install the library. </p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate and Send Emails via Ruby Library</h2>
<p>The open source Mail library enables software programmers to create and manage email messages inside their apps using Ruby. It will automatically assign a unique random message ID to the email message. Once you provided all the required information, it will send the email message to all the recipients.  It also supports sending email messages to multiple users, attaching files, image embedding, and much more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Encode Email Messages via Ruby</h2>
<p>Character encoding is a very useful technique used to send email messages with non-Latin data such as Arabic, Hebrew, Chinese, Japanese, and Russian, etc. The encoding standards say the email application how to interpret the text characters in your HTML or the body of the email. The open source Mail library has provided complete support for encoding email messages and decoding.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Accessing and Reading Email Message</h2>
<p>The open source Mail library has provided support for accessing and reading email messages inside Ruby applications. You can get email messages from POP as well as IMAP several with ease. There are several methods to access incoming emails such as the most recent emails, emails sorted by date, ascending or descending order, multipart email reading, extract attachments, and so on</p>
<h2 class="h2title">Attaching and Share Files</h2>
<p>The free Mail library has provided complete support for sending email messages with attachments using Ruby commands. This is a very useful feature that can be used to share files inside an organization with ease. You can also easily access and read the attached files with a couple of lines of code. It has provided support for attaching and sending files like PDF, Microsoft Word, Images, and many more.</p>
<p> </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}