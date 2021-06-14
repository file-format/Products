---
title: Open Source Go Library for Batch Processing and Scripting PDF Documents
description: PDF library, PDF CPU, PDF Scripting, PDF Processing,  PDF CPU, Small PDF Library, Lightweight PDF Library,  Open Source PDF Library, Go PDF programming, Go PDF APIs, Go PDF library, create  PDF Documents, insert images to PDF, add list to PDF files, Extract Text from PDF, Split PDF to many, fill a PDF form, Extract data from PDF forms, Print a PDF file, PDF to PNG conversion, convert PDF to JPEG, Digitally sign PDF files
keywords: PDFCPU, PDF CPU - Open Source Go Library allows Software Developers to create, edit, manage PDF Documents. You can insert layers, images & lists to PDF files via Go API.
draft: false
weight: 18



ProductName: PDFCPU
Githublink: https://github.com/pdfcpu/pdfcpu
ListingPage_Short_Description: Open source Go API for batch processing and scripting PDF documents.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Go API for Batch Processing and Scripting PDF Documents."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for PDF Document Generation"
Header_H2_Text="Open Source Go API for Batch Processing and Scripting PDF Documents." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>PDFCPU is and open source comprehensive PDF processing library written in Go. It is built for batch processing and scripting PDF documents via command line interface. Furhtermore, the API makes it simple to intergrate PDF documents in your applicaitons using GO. The API makes it simple to create and manipulated PDF doucments with wide range of command set.</p>
<p>Using the API, you can add attachments in to your PDF document, change owner and user password, encrypt & decrypt data. The API allows adding or removing pages from PDF document, you can rotate, trim, split and validate your PDF using the API aswell. Furhtermore, the API allows adding keywords and optimizing PDF documents.</p>
<p>.</p>

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
<p>An overview of One File PDF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Generate PDFs</li>
<li>Attachments</li>
<li>Colors</li>
<li>Encryption</li>
<li>Decryption</li>
<li>Fonts</li>
<li>Grid</li>
<li>Import</li>
<li>Watermark</li>
<li>Validation</li>
<li>Rotate</li>
<li>Split</li>
<li>Trim</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>PDFCPU</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>PDFCPU supports PDF file format as well as industry-standard formats for export.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>PDFCPU</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>PDFCPU only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Go 1.14 and above.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>PDFCPU</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PDFCPU</h2>
<p>To install the PDFCPU on your system, please run the following command. </p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install PDFCPU via GitHub</h3>
<pre><code class="html">go get https://github.com/pdfcpu/pdfcpu<br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Encrypt PDF via Command Based Free Go Library</h2>
<p>PDFCPU is a command based PDF document manipulation API. The command based system allows manipulating large number of files efficiently. In order to encrypt PDF files the API provides the following commnd</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pdfcpu encrypt [-v(erbose)|vv] [-q(uiet)] [-mode rc4|aes] [-key 40|128|256] [perm none|all] [-upw userpw] -opw ownerpw inFile [outFile]<br></code></pre>

<p>Furhtermore, the API provides other document protection features including decryption, changing user password, changing owner password, listing & permission by using the following commands.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert Images to PDF via Free GO API</h2>
<p>The open-source API PDFCPU allows converting images to PDF easily and fastly. In order to convert the images you just need to run the following command and output PDF document will be generated automatically.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pdfcpu import [-v(erbose)|vv] [-q(uiet)] [description] outFile imageFile...<br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert Images to PDF via Free GO API</h2>
<p>Using the API you can also add, remove or list PDF document properties. Adding a document property is pretty simple, you just need to write and add property command and input name of the property and value.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pdfcpu properties add     [-v(erbose)|vv] [-q(uiet)] [-upw userpw] [-opw ownerpw] inFile nameValuePair...<br></code></pre>

<p>Similary, you can remove specific PDF document properties by using the following command.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}