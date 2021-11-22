---
title: Open Source Cross-Platform .NET Library for IMAP, POP3 & SMTP
description: MailKit - Open Source C# .NET Library for IMAP, POP3 & SMTP. Generate Message with Attachments, Encrypt/Decrypt Messages with PGP/MIME.
keywords: Free .NET library,  .NET API, .NET MSG Library, Open Source outlook Library, .NET POP3 library, create  MSG Documents, SMTP C# .NET Libraries, C# outlook, C# IMAP, C# EML, c-sharp, email, mime, mime-parser, dkim, smime, smtp, imap, pop3, imap-client, pop3-client, smtp-client
draft: false
weight: 6



ProductName: MailKit
Githublink: https://github.com/jstedfast/MailKit
ListingPage_Short_Description: Open Source C# .NET library for generating message with attachments or encrypt/decrypt messages with PGP/MIME and ARC signatures.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free C# .NET Library for Generating Message with Attachments, Encrypt/Decrypt Messages with PGP/MIME. "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET Library for IMAP, POP3 & SMTP"
Header_H2_Text="Free C# .NET Library for Generating Message with Attachments, Encrypt/Decrypt Messages with PGP/MIME. " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>MailKit is an Open Source .NET library for IMAP, POP3, and SMTP. It is a cross-platform mail client library built on top of MimeKit. The project aims to provide a robust, fully-featured and RFC-compliant SMTP, POP3, and IMAP client implementations</p>
<p>The API supports several important features related to SASL Authentication, proxy support, SMTP client, POP3 client, IMAP4 client, client-side sorting and threading of messages.</p>
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
<p>An overview of MailKit features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>SMTP Client</li>
<li>POP3 Client</li>
<li>IMAP Client</li>
<li>MIME Parser</li>
<li>Client-side sorting</li>
<li>SASL Authentication</li>
<li>Supports S/MIME v3.2.</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MailKit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MailKit supports popular compression file formats listed below.</p>
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
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MailKit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MimeKit only requires.NETFramework.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><!--<header><i class="fa fa-cubes">` </i></header-->
<ul>
<li> .NETFramework 3.5 & higher.</li>
</ul>
</div>
<!--/left
    <div class="d1-col d1-right">&nbsp;</div>--> <!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MimeKit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with MailKit</h2>
<p>The easiest way to install MailKit is via NuGet. To use it from Visual Studio’s Package Manager Console, please enter the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>install Mailkit via NuGet</h3>
<pre><code class="html">Install-Package MailKit   </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Mailkit via GitHub </h3>
<pre><code class="html">git clone --recursive https://github.com/jstedfast/MailKit.git </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create New Messages via .NET</h2>
<p>The Open Source API MailKit library enables software developers to create MIME messages with few simple commands.  A TextPart is a leaf-node MIME part with a text media-type. The first argument to the TextPart constructor specifies the media-subtype, in this case, plain. Another media subtype you are probably familiar with is the HTML subtype. The easiest way for both get and set the string content of the MIME part is the Text property.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Generate and Send Message Free using C#</h3>
<pre><code class="c#">var message = new MimeMessage();
message.From.Add(new MailboxAddress("fred", "<span id="cloakf0de3a7795f1b0a57bae0ae6b5fe50b8">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloakf0de3a7795f1b0a57bae0ae6b5fe50b8').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addyf0de3a7795f1b0a57bae0ae6b5fe50b8='fr&#101;d'+'&#64;';addyf0de3a7795f1b0a57bae0ae6b5fe50b8=addyf0de3a7795f1b0a57bae0ae6b5fe50b8+'t&#101;st'+'&#46;'+'c&#111;m';var addy_textf0de3a7795f1b0a57bae0ae6b5fe50b8='fr&#101;d'+'&#64;'+'t&#101;st'+'&#46;'+'c&#111;m';document.getElementById('cloakf0de3a7795f1b0a57bae0ae6b5fe50b8').innerHTML+='<a '+path+'\''+prefix+':'+addyf0de3a7795f1b0a57bae0ae6b5fe50b8+'\'>'+addy_textf0de3a7795f1b0a57bae0ae6b5fe50b8+'<\/a>';</script>"));
message.To.Add(new MailboxAddress("frans", "<span id="cloaka042fe52de8b0c71a984ea9a02c9b037">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloaka042fe52de8b0c71a984ea9a02c9b037').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addya042fe52de8b0c71a984ea9a02c9b037='fr&#97;ns'+'&#64;';addya042fe52de8b0c71a984ea9a02c9b037=addya042fe52de8b0c71a984ea9a02c9b037+'fr&#97;nk'+'&#46;'+'c&#111;m';var addy_texta042fe52de8b0c71a984ea9a02c9b037='fr&#97;ns'+'&#64;'+'fr&#97;nk'+'&#46;'+'c&#111;m';document.getElementById('cloaka042fe52de8b0c71a984ea9a02c9b037').innerHTML+='<a '+path+'\''+prefix+':'+addya042fe52de8b0c71a984ea9a02c9b037+'\'>'+addy_texta042fe52de8b0c71a984ea9a02c9b037+'<\/a>';</script>"));
message.Subject = "FileFormat ";

message.Body = new TextPart("plain")
{
    Text = "File Format Developer Guide"
};

using (var client = new SmtpClient())
{
    // For demo-purposes,
    client.ServerCertificateValidationCallback = (s, c, h, e) =&gt; true;

    client.Connect("smtp.test.com", 587, false);

    // Note: only needed if the SMTP server requires authentication
    client.Authenticate("frans", "password");

    client.Send(message);
    client.Disconnect(true);
}                                   
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate Message with Attachments using .NET API</h2>
<p>MailKit API provides features for generating a message with attachments inside .NET applications.  Attachments are just like any other MimePart, the main difference is that they contain a content-disposition header holding value of the attachment instead of inline or no Content-Disposition header at all. To send out both a text/HTML and a text/plain version of the message, you need to create a TextPart for each part and then add them to a multipart/alternative.</p>
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Encrypt/Decrypt Messages with PGP/MIME</h2>
<p>The MailKit library provides features for encrypting email messages with PGP/MIME inside .NET applications. The PGP/MIME uses a MIME part with a multipart/encrypted mime-type to encapsulate encrypted data. If you want to encrypt a message it is always a better approach to use SecureMailboxAddress instead of a MailboxAddress for every recipient, which will allow users to specify the unique fingerprint of each recipient's PGP key.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}
