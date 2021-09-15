---
title: Open Source C# .NET PDF API - Generate, Process & Combine PDF Files
description: PDFsharp - An Open Source Fee .NET API for PDF Documents processing. Generate, modify & convert PDFs, Combine Multiple PDF, and PDF Annotations via C# library.
keywords: .NET PDF, open source PDF, process PDF,  dotnet PDF API,  C# PDF Library, Open Source PDF Library, .NET PDF programming, .NET PDF APIs, .NET PDF library, generate  PDF Documents, manipulate PDF files, PDF export , PDF manipulation, 
draft: false
weight: 3



ProductName: PDFsharp
Githublink: https://github.com/empira/PDFsharp
ListingPage_Short_Description: .NET implementation of PDF format gives developers the power to handle simple and complex PDF Documents inside their own .NET apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PDFsharp"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET API for PDF Processing"
Header_H2_Text="Create, Manipulate, Convert & Process PDF Documents via Free C# .NET Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is PDFsharp?</h2>
<p>Open Source .NET library that can be used to create, render, merge, split, modify, print and extract text or meta-data of PDF files. The PDFsharp API supports creating PDF documents on the fly from any .NET language.  It also supports importing data from various sources via XML files or direct interfaces. It supports numerous options for page layout, text formatting, and document design.</p>
<p>PDFsharp provides graphical implementation based either on GDI+ or WPF. The API makes developer’s job easy by providing features for using one source code for drawing on a PDF page as well as in a window or on the printer. It supports several important features for processing PDF files such as modifying PDF, merge or split PDFs, XPS to PDF conversion, PDF rendering, PDF data extraction, Font embedding and subsetting, Unicode support and many more.</p>

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
<p>An overview of PDFsharp features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create PDF</li>
<li>Modify PDF</li>
<li>PDF merging</li>
<li>XPS to PDF</li>
<li>PDF rendering</li>
<li>Manipulate PDF</li>
<li>PDF annotations</li>
<li>Data extraction</li>
<li>Font embedding</li>
<li>Encrypt PDF</li>
<li>PDF form</li>
<li>Unicode support</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="iText 7"><header>PDFsharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>API mainly supports PDF format but can export PDF documents to a number of other formats.</p>
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
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>,<a href="https://docs.fileformat.com/image/jpeg/"> JPEG</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a>, </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="iText 7"><header>PDFsharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>PDFsharp can work with any .NET based programming language.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i></header>
<ul>
<li>.NET </li>
</ul>
</div>
<!--/left--> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="iText 7"><header>PDFsharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PDFsharp</h2>
<p>PDFsharp is dual-licensed as AGPL/Commercial software. AGPL is a free/open-source software license.</p>
<p>It is highly recommended using NuGet to add PDFsharp to your project,</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>NuGet command</h3>
<pre><code class="html"> Install-Package PdfSharp</code></pre>

<p>With Visual Studio you can install the NuGet Package Manager to easily access NuGet packages. It works with VS 2012 Express as well as with the community editions of VS 2013 and VS 2015. In Visual Studio go to "Tools" =&gt; "Extensions and Updates..." to install the NuGet Package Manager if you do not have it yet. The NuGet Package Manager will download the package for you, install it, add a reference to your project.</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate & Modify PDF Documents via Free .NET API</h2>
<p>Software developers can use PDFsharp API to create a new PDF document inside their own .NET applications. Once the document is created you can add an empty page as well insert graphics or text with ease. It also facilitates developers to modify the existing document according to their needs and save it with the name of their choice. Using the following steps you can generate & manipulate PDF documents in C#.</p>
<ol>
<li>Initialize PdfDocument</li>
<li>Add Page</li>
<li>Get an XGraphics object for drawing</li>
<li>Create a font</li>
<li>Add Text</li>
<li>Save Document</li>
</ol>
<br>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create PDF using C#</h3>
<pre><code class="c#">// Create a new PDF document
PdfDocument pdfDocument = new PdfDocument();
// Create an empty page
PdfPage pdfPage = pdfDocument.AddPage();
// Get an XGraphics object for drawing
XGraphics xGraphics = XGraphics.FromPdfPage(pdfPage);
// Create a font
XFont xFont = new XFont("Verdana", 20, XFontStyle.BoldItalic);
// Draw the text
xGraphics.DrawString("File Format Developer Guide", xFont, XBrushes.Black,
        new XRect(0, 0, pdfPage.Width, pdfPage.Height),
        XStringFormats.Center);
// Save the document...
pdfDocument.Save("fileformat.pdf");
        </code></pre>

<h2 class="h2title">Create PDF Annotations</h2>
<p>Annotations allow users to add custom content on <em>PDF</em> pages. PDF applications normally allow creating & modifying various types of annotations, such as text, lines, notes or shapes, etc. PDFsharp enables programmers to create various types of PDF annotations inside their own applications. The library supports the creation of text annotations, link and rubber stamp annotations.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}