---
title: Open Source PHP Library to Convert DOCX and DOC to PDF
description: Gotenberg PHP Client – Open Source Free PHP library for Microsoft Word DOC & DOCX files. Convert DOC and DOCX to PDF for free.
keywords: Gotenberg PHP Client , Free API, Free PHP API, Free API, Free DOCX API, Free DOC API, Open Source PHP API, Open Source DOCX API, Open Source DOC API, Convert DOCX Free, Create Docx using PHP, Convert DOCX using PHP, modify word files, convert word DOCX, add images to DOCX, Convert DOCX to PDF, DOC to PDF, DOCX to PDF Free. Free DOCX Converter
draft: false
weight: 1



ProductName: Gotenberg Go client
Githublink: https://github.com/thecodingmachine/gotenberg-go-client
ListingPage_Short_Description: An Open Source library that allows to converting Word Processing Documents to PDF
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert Microsoft Word Processing Documents to PDF via Free GO API"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Converting Microsoft<sup>®</sup> Word Processing Files"
Header_H2_Text="Convert Microsoft Word Processing Documents to PDF via Free GO API" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Gotenberg Go client?</h2>
<p>Gotenberg Go client is an open-source go library that gives software developers the capability to convert Microsoft Word Processing documents to PDF inside their own applications. Gotenberg is a Docker-powered stateless API for converting Office documents to PDF. Using the API, you can easily convert DOCX, DOC, RTF, and TXT file format to PDF.</p>
<p>By using the API, you can convert one or more word processing documents at the same time and save the resultant document in PDF format. The API provides structured logging allowing you to have relevant information about what’s going on.</p>

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
<p>An overview of Gotenberg Go client features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Convert Word to PDF</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Gotenberg Go client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Gotenberg Go client supports popular Microsoft Word formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a>, <a href="https://docs.fileformat.com/word-processing/doc/">DOC</a>, <a href="https://docs.fileformat.com/word-processing/rtf/">RTF</a>, <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Gotenberg Go client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Gotenberg Go client only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>go1.8+</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><br><header>Gotenberg Go client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Gotenberg Go client</h2>
<p>The recommended way to install the Gotenberg Go client into your project is by using GitHub. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Gotenberg Go client via GitHub</h3>
<pre><code class="html">$ go get -u github.com/thecodingmachine/gotenberg-go-client/v7
             </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert DOCX to PDF via Free Go API</h2>
<p>The Open source library Gotenberg Go client allows computer programmers to convert DOCX to PDF inside their own Go applications. In order to convert you DOCX to PDF, you just need to load your document and convert it using gotenberg.NewOfficeRequest() method. By using the following lines of code, you can easily convert DOCX to PDF</p>
<h3>Convert Word Processing to PDF in GO</h3>
<ol>
<li>Load two DOCX files using NewDocumentFromPath() method and pass filename and file path as parameters</li>
<li>Convert both files to PDF using gotenberg.NewOfficeRequest() method and pass doc objects</li>
<li>Save PDF document</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert DOCX to PDF via Free GO API</h3>
<pre><code class="go">c := &gotenberg.Client{Hostname:"http://localhost:3000"}
doc, _ := gotenberg.NewDocumentFromPath("document.docx","/path/to/file")
doc2, _ := gotenberg.NewDocumentFromPath("document2.docx","/path/to/file")
req := gotenberg.NewOfficeRequest(doc, doc2)
dest :="result.pdf"
c.Store(req, dest)
             </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}