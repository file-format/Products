---
title: Open Source Java API for MS Outlook MSG – Read & Extract Attachments
description: An Open Source Free Java API for Outlook MSG files. Read sender information, subject and body from MSG files via Java. Access & extract MAPI Message attachments.
keywords: Free Java API, Free Outlook library, Open Source Email API, Java email, Java email APIs, Java Outlook API, Java MSG API, Java email library, read outlook MSG, view email messages, r Open Source Java outlook
draft: false
weight: 1



ProductName: Apache POI HSMF 
Githublink: https://github.com/apache/poi
ListingPage_Short_Description: Java implementation of the Outlook MSG format providing low-level read access to MSG files along with a user-facing way to get at the common textual content of MSG files.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache POI HSMF"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Process MSG Files via Open Source Java API"
Header_H2_Text="Read Microsoft Outlook MSG files to access Render Information, Subject & Body contents or Extract Attachments with Apache POI." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>If you are a Java developer looking for an email processing library to process email messages, you may want to consider Apache POI-HSMF. It is the POI Project's pure Java implementation of the Outlook MSG format, providing low-level read access to MSG files along with a user-facing way to get at the common textual content of MSG files such as sender, subject, message body and more. Developers can get message headers information, save email messages, read fixed Size properties from MSG file, extract embedded message properties, Working with message encoding and much more. </p>

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
<p>An overview of Apache POI-HSMF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Access MSG file</li>
<li>Extract textual information</li>
<li>Get message headers</li>
<li>Extract sender information</li>
<li>Extract message subject</li>
<li>Extract message body</li>
<li>Extract attachments</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HSMF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache POI-HSMF supports popular Microsoft Outlook file formats listed below.</p>
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
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HSMF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache POI-HSMF only requires Java run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HSMF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache POI HSMF</h2>
<p>First of all, you need to have the Java Development Kit (JDK) installed on your system. If you already have it then proceed to the Apache POI's <a href="http://poi.apache.org/download.html">download</a> page to get the latest stable release in an archive. Extract the contents of the ZIP file in any directory from where the required libraries can be linked to your Java program. That is all!</p>
<p>Referencing Apache POI in your Maven-based Java project is even simpler. All you need is to add the following dependency in your pom.xml and let your IDE fetch and reference the Apache POI Jar files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Apache POI Maven Dependency</h3>
<pre><code class="html">&lt;!-- https://mvnrepository.com/artifact/org.apache.poi/poi --&gt;
&lt;dependency&gt;
 &lt;groupId&gt;org.apache.poi&lt;/groupId&gt;
 &lt;artifactId&gt;poi&lt;/artifactId&gt;
 &lt;version&gt;4.1.0&lt;/version&gt;
&lt;/dependency&gt;
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"><strong>API to Access Outlook MSG Files</strong></h2>
<p>Apache POI-HSMF allows Java developers and programmers to access the contents of Outlook MSG files. Apache POI-HSMF is port of the Microsoft Outlook message file format to pure Java. The API is at the basic level as of now and, therefore, limited functionality is available for working with email messages. Developers can get</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract Data from MSG - Java</h3>
<pre><code class="java">// Open MSG file
MAPIMessage msg = new MAPIMessage("sample.msg");
// Read Content
System.out.println("From:" + msg.getDisplayFrom());
System.out.println("To:" + msg.getDisplayTo());
System.out.println("CC:" + msg.getDisplayCC());
System.out.println("BCC:" + msg.getDisplayBCC());
System.out.println("Subject:" + msg.getSubject());
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"><strong>Read & Extracts Attachments from Outlook MSG File</strong></h2>
<p>Apache POI-HSMF API enables Java developers to parse Outlook MSG files; extract and read the contents of the embedded document. Developers can access attachments of MAPI message. It supports reading one or several Outlook MSG files and for each of them creates a text file from available chunks and a directory that contains attachments. It reads attachments from the Outlook MSG file and writes it to disk as an individual file.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract Attachments for MSG - Java</h3>
<pre><code class="java">// Open MSG file
MAPIMessage msg = new MAPIMessage("sample.msg");
// Extract Attachment
AttachmentChunks[] attachments = msg.getAttachmentFiles();
if(attachments.length &gt; 0) {
 File d = new File("D:\\Attachments");
 if(d.mkdir()) {
  for(AttachmentChunks attachment : attachments) {
   processAttachment(attachment, d);
  }
 }
}
</code></pre>

<h2 class="h2title"><strong>Save Email Message Contents inside Java Apps</strong></h2>
<p>Java programmers can use Apache POI-HSMF API to extract and save email messages content. The email body can be extracted to create a new file, and you can then write it to disc with the help of FileWrite.</p>
<p>. </p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}