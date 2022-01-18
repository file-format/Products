---
title: PHP API – Create, Edit Password Protected PDF from UTF-8 Encoded HTML
description: mPDF – An open source, free PHP Library to create, modify, and manipulate PDF documents. Create Password Protected PDF Documents from UTF-8 encoded HTML via PHP API.
keywords: PDF API, PDF library, convert PDF files, PHP APIs , PHP PDF programming, render PDF Elements, UTF-8 encoded HTML to PDF, PHP PDF Library, Open Source PDF Library, Extract PDF content , extract data from a PDF, manipulate PDF documents, add tables to PDF
draft: false
weight: 10



ProductName: mPDF 
Githublink: https://github.com/mpdf/mpdf
ListingPage_Short_Description: An open source, free PHP Library to create, modify, and manipulate PDF documents inside your own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Create, Modify, and Manipulate PDF Documents, Add Tables, Headers & Footers to PDF Files via PHP API."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP Library for Processing PDF Files"
Header_H2_Text="Create, Modify, and Manipulate PDF Documents, Add Tables, Headers & Footers to PDF Files via PHP API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>mPDF is an Open source PHP Library that enables users to create, modify, and manipulate PDF documents inside their own PHP application. The library supports PDF creation from UTF-8 encoded HTML and accepts UTF-8 encoded HTML. It auto-detect RTL characters within a document and Transfers tables, lists, table cell alignment, justified text as well as full-text reversal for RTL characters. Moreover, it also auto-detects non-RTL characters and displays it in the original order.</p>
<p>The library supports several important basic and advanced features for PDF documents management, such as PDF creation, Bookmarks, CSS style sheets, PDF Page layout, and orientation, inserting tables or nested tables, adding images ( JPG, GIF, PNG, SVG, BMP or WMF format, Text justification, PDF documents security, headers & footers, page numbering, and many more.</p>
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
<p>An overview of mPDF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>UTF-8 encoding</li>
<li>RTL languages</li>
<li>CJK languages</li>
<li>Bookmarks</li>
<li>CSS stylesheets</li>
<li>Page layout</li>
<li>Page orientation</li>
<li>Headers & footers</li>
<li>Images</li>
<li>Tables</li>
<li>Nested tables</li>
<li>Extract text</li>
<li>Watermarks</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>mPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>mPDF supports PDF file format as well as industry-standard formats for export.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a> </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>mPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>mPDF only requires PHP runtime.</p>
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
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>mPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with mPDF</h2>
<p>The Official installation method for mPDF library is through <a href="https://getcomposer.org/download/">composer</a> packagist package mpdf/mpdf. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install mPDF via composer</h3>
<pre><code class="html">$ composer require mpdf/mpdf<br></code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">PDF Files Creation from UTF-8 Encoded HTML</h2>
<p>mPDF library provides functionality for creating PDF documents from UTF-8 encoded HTML inside PHP application. UTF-8 encoded HTML is accepted as the standard input. Once the PDF file is created, you can also make changes to it according to your own needs. The library facilitates you to insert new pages, add new content, insert images, use bookmarks, add headers & footers to an existing page, and much more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Tables to PDF via PHP</h2>
<p>The open source library mPDF gives software developers the ability to add and modify tables inside a PDF document. The library supports CSS styles for tables/cells and custom attributes adding a horizontal border at the top and bottom of the table. It also includes support for border-collapse (CSS border-collapse:collapse or separate), as well as cellSpacing and cellPadding. Moreover, you can rotate tables, AutosizePermalink, repeating Table Header row on a new page, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Headers & Footers to PDF File</h2>
<p>The mPDF library includes support for adding headers & footers to a PDF document via PHP. The library provides a number of different ways to set page headers and page footers in a PDF, such as defines a header/footer for the whole document, includes images in a header/footer, complex headers/footers with the advantage of HTML code, setting the header/footer at the start of a document and much more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create Password Protected PDF Documents</h2>
<p>The mPDF library includes complete support for settings security of the PDF documents. The library gives users the ability to determine whether the document is encrypted and what permissions are granted to the user. It also enables you to set a password for opening the PDF document or to modify the PDF document.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}