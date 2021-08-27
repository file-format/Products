---
title: fileformat - MimeKit


draft: false
weight: 5



ProductName: MimeKit
Githublink: https://github.com/jstedfast/MimeKit
ListingPage_Short_Description: Free .NET library for MIME creation and parsing to create messages, encrypt or decrypt messages, add attachments to Email messages inside .NET applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text=".NET MIME Creation and Parser Library for message Encryption, Decryption, and Signing as well as verifying Digital Signatures using S/MIME or OpenPGP Standards. "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET MIME Creation & Parsing Library "
Header_H2_Text=".NET MIME Creation and Parser Library for message Encryption, Decryption, and Signing as well as verifying Digital Signatures using S/MIME or OpenPGP Standards. " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>MimeKit is an Open Source C# .NET library that enables software developers to create and parse email messages using the Multipurpose Internet Mail Extension (MIME). The main reason behind the development of the project was that it has been felt that the majority of email client (and server) software had less-than-satisfactory MIME implementations. Most of the times these email clients would incorrectly try to parse a MIME message and thus will not be able to get the full benefits that MIME.</p>
<p>The main aim of the MimeKit project is to address all these issues by as closely as possible and at the same time also provide computer programmers a tremendously easy to use high-level API. The great thing about the library is that it is much faster with all the available solutions. Even some commercial MIME parsers are not even come close to matching MimeKit's performance.</p>
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
<p>An overview of MimeKit features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Parse Messages</li>
<li>Get message Body</li>
<li>Traverse MimeMessage</li>
<li>Get Decoded Content</li>
<li>Create Message</li>
<li>Add attachments</li>
<li>Encrypt Messages</li>
<li>Decrypt messages,</li>
<li>PGP/MIME support</li>
<li>S/MIME support</li>
<li>Verify DKIM Signatures</li>
<li>Signing with ARC</li>
<li>Verify ARC Signatures</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MimeKit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MimeKit supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/email/msg/">MSG</a> </li>
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
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>MimeKit</header><footer><small></small></footer></div>
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
<h2 class="h2title">Getting Started with MimeKit</h2>
<p>The easiest way to install MimeKit is through NuGet.  In Visual Studio's Package Manager Console, enter the following command</p>
<p>You can install it using pip.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>install via NuGet</h3>
<pre><code class="html"> Install-Package MimeKit  </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install via GitHub </h3>
<pre><code class="html">git clone --recursive https://github.com/jstedfast/MailKit.git </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">.NET API to Create New Messages</h2>
<p>The Open Source API MailKit library enables software developers to create MIME messages with few simple commands.  A TextPart is a leaf-node MIME part with a text media-type. The first argument to the TextPart constructor specifies the media-subtype, in this case, plain. Another media subtype you are probably familiar with is the HTML subtype. The easiest way for both get and set the string content of the MIME part is the Text property.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Open Source API to Create Message - C#</h3>
<pre><code class="c#">var message = new MimeMessage();
message.From.Add(new MailboxAddress("fred", "<span id="cloak35e4797f837954595d465a28c112c89a">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloak35e4797f837954595d465a28c112c89a').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addy35e4797f837954595d465a28c112c89a='fr&#101;d'+'&#64;';addy35e4797f837954595d465a28c112c89a=addy35e4797f837954595d465a28c112c89a+'t&#101;st'+'&#46;'+'c&#111;m';var addy_text35e4797f837954595d465a28c112c89a='fr&#101;d'+'&#64;'+'t&#101;st'+'&#46;'+'c&#111;m';document.getElementById('cloak35e4797f837954595d465a28c112c89a').innerHTML+='<a '+path+'\''+prefix+':'+addy35e4797f837954595d465a28c112c89a+'\'>'+addy_text35e4797f837954595d465a28c112c89a+'<\/a>';</script>"));
message.To.Add(new MailboxAddress("frans", "<span id="cloak46206d777d788c3227a97a20d8646c14">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloak46206d777d788c3227a97a20d8646c14').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addy46206d777d788c3227a97a20d8646c14='fr&#97;ns'+'&#64;';addy46206d777d788c3227a97a20d8646c14=addy46206d777d788c3227a97a20d8646c14+'fr&#97;nk'+'&#46;'+'c&#111;m';var addy_text46206d777d788c3227a97a20d8646c14='fr&#97;ns'+'&#64;'+'fr&#97;nk'+'&#46;'+'c&#111;m';document.getElementById('cloak46206d777d788c3227a97a20d8646c14').innerHTML+='<a '+path+'\''+prefix+':'+addy46206d777d788c3227a97a20d8646c14+'\'>'+addy_text46206d777d788c3227a97a20d8646c14+'<\/a>';</script>"));
message.Subject = "FileFormat ";

message.Body = new TextPart("plain")
{
    Text = "File Format Developer Guide"
};                                  
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate Message with Attachments using .NET API</h2>
<p>MailKit API provides features for generating a message with attachments inside .NET applications.  Attachments are just like any other MimePart, the main difference is that they contain a content-disposition header holding value of the attachment instead of inline or no Content-Disposition header at all. To send out both a text/HTML and a text/plain version of the message, you need to create a TextPart for each part and then add them to a multipart/alternative.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Generate Email Attachments Free using C#</h3>
<pre><code class="c#">var message = new MimeMessage();
message.From.Add(new MailboxAddress("fred", "<span id="cloak20d0fffe3e72c007158d85f4bf5168f4">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloak20d0fffe3e72c007158d85f4bf5168f4').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addy20d0fffe3e72c007158d85f4bf5168f4='fr&#101;d'+'&#64;';addy20d0fffe3e72c007158d85f4bf5168f4=addy20d0fffe3e72c007158d85f4bf5168f4+'t&#101;st'+'&#46;'+'c&#111;m';var addy_text20d0fffe3e72c007158d85f4bf5168f4='fr&#101;d'+'&#64;'+'t&#101;st'+'&#46;'+'c&#111;m';document.getElementById('cloak20d0fffe3e72c007158d85f4bf5168f4').innerHTML+='<a '+path+'\''+prefix+':'+addy20d0fffe3e72c007158d85f4bf5168f4+'\'>'+addy_text20d0fffe3e72c007158d85f4bf5168f4+'<\/a>';</script>"));
message.To.Add(new MailboxAddress("frans", "<span id="cloakdfcce630c28fef90d52d59639bec2084">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="text/javascript">document.getElementById('cloakdfcce630c28fef90d52d59639bec2084').innerHTML='';var prefix='&#109;a'+'i&#108;'+'&#116;o';var path='hr'+'ef'+'=';var addydfcce630c28fef90d52d59639bec2084='fr&#97;ns'+'&#64;';addydfcce630c28fef90d52d59639bec2084=addydfcce630c28fef90d52d59639bec2084+'fr&#97;nk'+'&#46;'+'c&#111;m';var addy_textdfcce630c28fef90d52d59639bec2084='fr&#97;ns'+'&#64;'+'fr&#97;nk'+'&#46;'+'c&#111;m';document.getElementById('cloakdfcce630c28fef90d52d59639bec2084').innerHTML+='<a '+path+'\''+prefix+':'+addydfcce630c28fef90d52d59639bec2084+'\'>'+addy_textdfcce630c28fef90d52d59639bec2084+'<\/a>';</script>"));
message.Subject = "FileFormat";
var path = "image.png";
var body =   message.Body = new TextPart("plain")
{
    Text = "File Format Developer Guide"
};

// create an image attachment for the file located at path
var attachment = new MimePart("image", "gif")
{
    Content = new MimeContent(File.OpenRead(path), ContentEncoding.Default),
    ContentDisposition = new ContentDisposition(ContentDisposition.Attachment),
    ContentTransferEncoding = ContentEncoding.Base64,
    FileName = System.IO.Path.GetFileName(path)
};

// now create the multipart/mixed container to hold the message text and the
// image attachment
var multipart = new Multipart("mixed")
{
    body,
    attachment
};

// now set the multipart/mixed as the message body
message.Body = multipart;                                  
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Encrypt or Decrypt Messages with S/MIME</h2>
<p>The Open Source MailKit API provides features for encrypting messages using S/MIME cryptography context. S/MIME uses an application/pkcs7-mime MIME part to encapsulate encrypted content.  Create the message body with the message text and some image attachments.  After that, you can encrypt the message body using the custom S/MIME cryptography context.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}