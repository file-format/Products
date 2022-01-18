---
title: Open Source Go Library for Adding Watermark in PDF Documents
description: PDF library, MarkPDF, Mark PDF, PDF CPU, PDF Scripting, PDF Processing, PDF CPU, Small PDF Library, Lightweight PDF Library, Open Source PDF Library, Go PDF programming, Go PDF APIs, Go PDF library, create PDF Documents, insert images to PDF, add list to PDF files, Extract Text from PDF, Split PDF to many, fill a PDF form, Extract data from PDF forms, Print a PDF file, PDF to PNG conversion, convert PDF to JPEG, Digitally sign PDF files
keywords: Mark PDF, Image Watermark, Text Watermark, Open Source Go Library allows Software Developers to create, edit, manage PDF Documents. You can insert layers, images & lists to PDF files via Go API.
draft: false
weight: 19



ProductName: MarkPDF
Githublink: https://github.com/ajaxray/markpdf
ListingPage_Short_Description: A tiny command line tool for watermarking PDF files using image or text.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="A tiny command line tool for watermarking PDF files using image or text"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Go Library for PDF Document Generation"
Header_H2_Text="A tiny command line tool for watermarking PDF files using image or text" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>MarkPDF is simple and tiny open-source PDF document manipulation API to add text and image based watermarks in PDF documents. The API provides a set of commands and command line tool for document manipulation. It's pretty simple and fast to use. Using the commands, the developer can configure position, rotation, stretch and set opacity of PDF document.</p>
<p>The API is lightweigh with no external depednecies. Currenly the API supported adding only image and text as watermarks in your document. While using text watermakrs the API supports Courier, Helvetica and Times Roman fonts only and while using image watermark you can use PNG images.</p>
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
<p>An overview of MarkPDF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Text Watermark</li>
<li>Image Watermark</li>
<li>Positing</li>
<li>Opacity</li>
<li>Rotation</li>
<li>Stretch</li>
<li>Set Font</li>
<li>Set Color</li>
<li>Set Font Size</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>MarkPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MarkPDF supports the following file formats.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/image/png/">PNG</a></li>
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
<div class="d1-logo" style="border: none;"><header>MarkPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MarkPDF only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Go 1.3 and above.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>MarkPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with MarkPDF</h2>
<p>To install the MarkPDF on your system, you need to download the latest stable <a href="https://github.com/ajaxray/markpdf/releases">release</a> then rename it and give it execute permission. </p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install MarkPDF via GitHub</h3>
<pre><code class="html">mv markpdf_linux-amd64 markpdf 
sudo chmod +x markpdf<br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate PDF Document via Free Go Library</h2>
<p>Generating PDF documents with Go is pretty simple. All you need to do is create a blank PDf document with A4 size by using pdf.NewPDF("A4") method of the API. You can set measurements of the doucment in centimeters using pdf.SetUnits("cm") method and Similarly draw grid in newly created PDF document using pdf.DrawUnitGrid() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Set Font in PDF using Free GO API</h2>
<p>This lightweight open-source API allows basic document manipulation and genration operation for PDf document. Once you have create a new document, you need to set font and font styles. In order to set fonts, pdf.SetFont() method, set position using pdf.SetXY() method and color of the text using pdf.SetColor() method respectively.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}