---
title: Read, Parse & Convert Outlook PST Files via Open Source Java API | LibPST
description: LibPST – An open source free Java Library for processing Outlook PST files. Read & extract email messages from PST files without using MS Outlook via Java API.
keywords: Free Java API, Java PST, Java email API, Java PST Library, Open Source outlook Library, Java PST programming, Java PST APIs, Java PST library, create PST Documents, Extract PST messages, Java outlook, Java PST development
draft: false
weight: 4



ProductName: Java-libpst 
Githublink: https://github.com/rjohnsondev/java-libpst
ListingPage_Short_Description: Develop Java applications having the ability to Read and convert Microsoft Outlook PST Files using open source Java libraries.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read & Extract the content of Outlook PST files without using Microsoft Outlook via Free Java Library."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Process Outlook PST Files via Open Source Java API"
Header_H2_Text="Read & Extract the content of Outlook PST files without using Microsoft Outlook via Free Java Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title"><strong>What is Java-libpst?</strong></h2>
<p>Java-libpst is an open source Java library for reading and extracting contents of Outlook PST files. PST is a popular file format used by MS Outlook for storing emails. It is used to archive message copies, attachments, calendar events, contacts, and other Outlook items. Java-libpst enables developers to access and extract all this information so that it may be migrated or used in other systems.</p>
<p>The library has much improved with the passage of time. It now allows developers to handle large PST files with reasonable speed, compressible encryption support, ANSI (32bit) support, Unicode (64bit) Outlook PST and Exchange OST support & much more.</p>

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
<p>An overview of Java-libpst features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Read outlook PST</li>
<li>Handle large PST</li>
<li>OST support</li>
<li>Access mail body</li>
<li>View attachment</li>
<li>Save attachment</li>
<li>Email encryption</li>
<li>Unicode (64bit)</li>
<li>ANSI (32bit)</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img class="bg-lite" src='listing-image.png' alt="Apache POI" />--><header>Java-libpst</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Java-libpst supports popular Microsoft Outlook file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><span class="wikilink"><a href="https://docs.fileformat.com/email/pst/">PST</a></span></li>
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
<div class="d1-logo" style="border: none;"><!--<img class="bg-lite" src='listing-image.png' alt="Apache POI" />--><header>Java-libpst</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Java-libpst only requires Java run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>JDK 1.6 or higher</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img class="bg-lite" src='listing-image.png' alt="Apache POI" />--><header>Java-libpst</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Java-libpst</h2>
<p>First of all, you need to install JDK 1.6 or higher.</p>
<p>Dependency that needs to be added to pom.xml file is,</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Maven Dependency</h3>
<pre><code class="html">&lt;!-- <strong>https://mvnrepository.com/artifact/com.pff/java-libpst</strong> --&gt;
&lt;dependency&gt;
 &lt;groupId&gt;<strong>com.pff</strong>&lt;/groupId&gt;
 &lt;artifactId&gt;<strong>java-libpst</strong>&lt;/artifactId&gt;
 &lt;version&gt;<strong>0.9.3</strong>&lt;/version&gt;
&lt;/dependency&gt;
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"><strong>Load & Parse PST Files via Java</strong></h2>
<p>Java-libpst library allows to load & parse a PST with the functionality iterate over the PST folders and email collection within each folder. It also allows to get email details, like subject, body, HTML body, recipient list and so on.</p>
<ol>
<li>Load PST file via PSTFile constructor</li>
<li>Get root folder with the help of PSTFile.getRootFolder() method</li>
<li>Get children of root folder which are email messages</li>
<li>Store each email in an instance of PSTMessage</li>
<li>Parse email subject, body and so on for further processing</li>
</ol>
<br>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Parse PST - Java</h3>
<pre><code class="java">// Open sample PST
PSTFile pstFile = new PSTFile("sample.pst");
// Get display name
System.out.println(pstFile.getMessageStore().getDisplayName());

// Read emails in folder
if (pstFile.getRootFolder().getContentCount() &gt; 0) {
 PSTMessage email = (PSTMessage)pstFile.getRootFolder().getNextChild();
 while (email != null) {
  System.out.println("Email:"+email.getSubject());
  email = (PSTMessage)pstFile.getRootFolder().getNextChild();
 }

}
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"><strong>Extract Email Addresses from PST File in Java Apps</strong></h2>
<p>java-libpst API enables Java developers to extract email addresses and other details from PST files inside their own Java applications. Developers can easily go through e email and read the mail which is an attachment of an email.</p>
<p> </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}