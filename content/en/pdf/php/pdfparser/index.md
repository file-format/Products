---
title: Open Source PDF Parsing Library for PHP – Parse & Extract PDF Data
description: PDFParser – An open source, free PHP API for parsing PDF files. Parse PDFs & extract PDF elements (text, images, metadata) inside PHP applications.
keywords: PDF Parser, PDF library, parse PDF files, PHP APIs ,  PHP PDF programming, parse PDF Elements, parse PDF objects,  Extract PDF Elements,  PHP  PDF Library, Open Source PDF Library, Extract PDF metadata, compressed pdf  support, octal content encoding, Hexa content encoding
draft: false
weight: 7



ProductName: PDFParser  
Githublink: https://github.com/smalot/pdfparser
ListingPage_Short_Description: A standalone PHP library that provides various tools to read and extract data from a PDF file.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free PHP API allows Developers to Parse PDF Files, Extract Data & Elements from PDFs."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source PHP Library for Parsing PDF Files"
Header_H2_Text="Free PHP API allows Developers to Parse PDF Files, Extract Data & Elements from PDFs." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>PDFParser is an Open source PHP Library that allows software developers to parse PDF files and extract PDF elements inside their own PHP applications. PDFParser is built on top of TCPDF parser. PDFParser is a standalone PHP library that provides various tools to extract data from a PDF file.</p>
<p>Portable Document Format (PDF) is one of the World’s favorite document formats and still very popular. The API supports several important features for PDF parsing, such as loading and parsing PDF objects and headers, extracting metadata, extracting text from ordered pages, compressed PDF support, Hexa and octal content encoding support and many more.</p>
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
<p>An overview of PDFParser features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Load PDF objects</li>
<li>Parse objects</li>
<li>Parse headers</li>
<li>Extract metadata</li>
<li>Extract text</li>
<li>Compressed PDF</li>
<li>charset encoding</li>
<li>Hexa encoding</li>
<li>Octal encoding</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>PDFParser</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>PDFParser supports PDF file format as well as industry-standard formats for export.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/view/pdf/">PDF</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a> </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>PDFParser</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>PDFParser only requires PHP runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><!--<header><i class="fa fa-cubes">` </i></header-->
<ul>
<li>PHP 5.3 and above.</li>
</ul>
</div>
<!--/left
<div class="d1-col d1-right">&nbsp;</div> --> <!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>PDFParser</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PDFParser</h2>
<p>The PDFParser library will be automatically downloaded through the <a href="https://getcomposer.org/download/">composer</a> command line. Add PDFParser to your composer.json file.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Add  command to composer.json</h3>
<pre><code class="html"> { 
   "require": {
    "smalot/pdfparser": "*"
    } 
 } 
</code></pre>

<p>Use the composer to download the bundle by running the command:</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Parse PDF File & Extract Text from Each Page via PHP API</h2>
<p>PDFParser provides the functionality that enables computer programmers to parse PDF documents inside their own PHP application. First, you need to build necessary objects then load the PDF file, the parsed file can be stored on a variable and then this object will allow you to handle the PDF page by page. Now you can easily extract text from the entire PDF or separately by pages. Once the document is parsed now you can easily extract text from each page of the PDF.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Metadata from PDF Document</h2>
<p><em>Metadata</em> includes very important information about the PDF <em>document</em> and its contents such as Author, copyright information, creator, Creation Date and more. PDFParser gives developers the power to extract metadata from a PDF document. Once the document is parsed you can easily retrieve all details from the PDF file.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Text from a Specific PDF Page</h2>
<p>PDFParser allows developers to extract text from specific pages with ease by using a small amount of code. The API gives developers the ability to separately handle each page of the PDF document. Developers can iterate through the array of pages and can retrieve text from the page of their choice. The order of the array is the same as that of the PDF document.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}