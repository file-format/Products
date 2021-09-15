---
title: Open Source Go Library to Create Read & Write Office Word DOCX Files
description: Unioffice - Open Source Go library enables programmers to generate, edit & read office Word DOCX documents. Insert header/footer, tables & images to Word DOCX.
keywords: Go DOCX, Go Word processing, Go Word processing APIs, Go Doc API, Go .docx API, Go word library, create  Word Documents, modify Word documents, add image to word files, Open Source JavaScript Libraries, Open Source Word processing, Open Source Go Library
draft: false
weight: 16



ProductName: unioffice
Githublink: https://github.com/unidoc/unioffice
ListingPage_Short_Description: An Open Source library allows to create, edit and manipulating office Word DOCX file format inside Go applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Go Library for Managing & Automating common Word Processing tasks like inserting Header & Footer, Tables & Images to Word DOCX files & more."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Go LIbrary to Generate & Edit MS Word Documents"
Header_H2_Text="Open Source Go Library for Managing & Automating common Word Processing tasks like inserting Header & Footer, Tables & Images to Word DOCX files & more." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>unioffice is a powerful open source pure Go library that allows software developers to manage word documents and automate common word processing tasks with ease inside their own applications without requiring Microsoft Word. The library is quite well optimized and allows you to easily edit the code to meet your requirements.</p>
<p>The unioffice library is a strong Go-based library that can be used for generating, editing, formatting, and processing of Office Open XML documents. The library supports several important word processing features, such as read, write & modify Word documents, Text Formatting support, Auto-generated table of contents, Placing an on a document page, headers and footers insertion, adding tables,  Opening a document as a template, form fields support and much more.</p>

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
<p>An overview of unioffice features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read DOCX files</li>
<li>Write DOCX files</li>
<li>Edit Word DOCX</li>
<li>Add Paragraphs</li>
<li>Set fonts</li>
<li>Add tables</li>
<li>Add header & footers</li>
<li>Text alignment</li>
<li>Add images</li>
<li>Bookmarks support</li>
<li>Hyperlinks support</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>unioffice</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>unioffice supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/ppt/">DOCX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a><a href="https://docs.fileformat.com/presentation/pptx/">,</a> <a href="https://docs.fileformat.com/presentation/ppt/">DOCX</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>unioffice</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>unioffice only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>go1.8+</li>
</ul>
</div>
</div>
</div>
<div class="diagram1 d1-poi">
<div class="d1-row"><!--/left--><!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>unioffice</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with unioffice</h2>
<p>The recommended way to unioffice into your project is by using GitHub. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install unioffice via GitHub</h3>
<pre><code class="html">go get github.com/unidoc/unioffice/
go build -i github.com/unidoc/unioffice/...  </code>  </pre>



{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create Word DOCX Document via Go API</h2>
<p>The open source library unioffice has provided the facility for creating a new Word DOCX Document with ease. You can also easily open and modify an existing Microsoft Word Document inside your own applications. The library also included features for adding new text paragraphs, insert images to a page, text alignment, adding headers and footer, add tables, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"> Insert Images in Word DOCX Files</h2>
<p>The open source library unioffice provides software developers the ability to use images inside Microsoft Word documents. It supports functionalities like inserting images to the place of your choice, modify an existing image, text wrapping around the image, delete the image, and many more. For adding an image it is necessary to provide name and location of the image.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Header & Footer to Word Document</h2>
<p>Headers and footers can be used to include the information that users want to appear on every page of a document such as an author name, document title, or page numbers. The unioffice library allows software developers to add header & footer to word documents with ease. It also allows to have different headers and footers depending on the document section. It also included support for even, odd, first functionalities.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Working with Tables in Word DOCX</h2>
<p>The open source library unioffice enables computer programmers to add and modify tables inside word documents. Tables are very useful and can be used to organize and present data in a better way.  It supports adding a table with and without borders as well as allows constructing a table style with ease. You can easily place content in a table and adjust the size according to your needs.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}