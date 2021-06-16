---
title: Open Source .NET Word Documents Processing Library | DOCX to PDF Converter
description: DOCXToPDFConverter – An Open Source .NET Word documents processing library. Covert DOCXToPDF via free C# API
keywords: Free Word Processing API, Free C# API, Open Source API, Open Source .NET API, Open Source Word Processing API, .NET Word Processing, alternative to MS Word, Free .NET DOC API, Free .NET DOCX API, DOCX to PDF, Convert DOCX
draft: false
weight: 1



ProductName: DOCXToPDFConverter
Githublink: https://github.com/smartinmedia/Net-Core-DocX-HTML-To-PDF-Converter
ListingPage_Short_Description: Free .NET API that allows the programmers to convert Microsoft Word Processing DOCX to PDF programmatically.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open-Source Library to Convert DOCX to PDF"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Free .NET Library for Converting Microsoft<sup>®</sup> Word Processing Documents"
Header_H2_Text="Open-Source Library to Convert DOCX to PDF" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is DOCXToPDFConverter?</h2>
<p>There are a bunch of open-source APIs available that allow generating PDF document via code. The problem with it is that, for even one line of change, the developer has to update the code, test it, release a new version and end user will verify the update. The process is too long and hectic for small updates like these. DOCXToPDFConverter is developed with aim to allow end users to update the output document via Word. End users can update the DOCX and the API will generate an output PDF file for it. Not only you can convert DOCX to PDF, but can also get HTML as output.</p>
<p>While working with DOCX to PDF and DOCX to HTML conversion the API parses source document, and introduces the dynamic content into predefined placeholders. The API works on Windows, Linux and MacOS.</p>

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
<p>An overview of DOCXToPDFConverter features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>DOCX to DOCX</li>
<li>DOCX to PDF</li>
<li>DOCX to HTML</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>DOCXToPDFConverter</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>DOCXToPDFConverter supports popular Word Processing file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a>, <a href="https://docs.fileformat.com/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>DOCXToPDFConverter</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>DOCXToPDFConverter works with .NETCoreApp 2.1. Furthermore, the API requires LibreOffice, Document.Format.OpenXm, and System.Drawing.Common.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with DOCXToPDFConverter</h2>
<p>First of all, you require to have .NETCoreApp 2.1. After that, please download the repository manually from <a href="https://github.com/smartinmedia/Net-Core-DocX-HTML-To-PDF-Converter">GitHub</a> or install it from NuGet.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Installation DOCXToPDFConverter from NuGet</h3>
<pre><code class="html"> Install-Package DocXToPdfConverter -Version 1.0.5</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert DOCX to PDF via Free .NET API</h2>
<p>DOCXToPDFConverter allows .NET programmers to convert DOCX to PDF programmatically. In order to convert DOCX to PDF, you need to define a source file, define path to LibreOffice, set placeholders, and convert the document using Convert() method. By using the following code snippet, you can convert DOCX to PDF.</p>
<h3>Convert DOCX to PDF in C#</h3>
<ol>
<li>Initialize path to LibreOffice soffice.exe</li>
<li>Initialize placeholders which you want to use in your Word Documents. There are 3 types of placeholders: one for plain text, one for table rows and one for images</li>
<li>Initialize ReportGenerator and pass locationOfLibreOfficeSoffice as parameter</li>
<li>Convert DOCX to PDF by using ReportGenerator's Convert() method and pass input DOCX file path, output PDF path and placeholders as parameters.</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Free .NET API to Convert DOCX to PDF</h3>
<pre><code class="c#">
// initialize LibreOffice soffice.exe filepath
string locationOfLibreOfficeSoffice = @"C:\PortableApps\LibreOfficePortable\App\libreoffice\program\soffice.exe";
// define placeholders
placeholders.NewLineTag = "<br>";
placeholders.TextPlaceholderStartTag = "##";
placeholders.TextPlaceholderEndTag = "##";
placeholders.TablePlaceholderStartTag = "==";
placeholders.TablePlaceholderEndTag = "==";
placeholders.ImagePlaceholderStartTag = "++";
placeholders.ImagePlaceholderEndTag = "++";
// initialize report generator
var test = new ReportGenerator(locationOfLibreOfficeSoffice);

// convert DOCX to PDF
test.Convert("Test-Template.docx", "Test-Template-out.pdf", placeholders);

                                        </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}