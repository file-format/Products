---
title: Open Source PHP PowerPoint API – Convert PPTX and PPT to PDF
description: Gotenberg PHP Client- Open Source Free PHP API allows Developers to convert PPT and PPTX to PDF
keywords: PHP PowerPoint API, PHP PPT, PHP PPTX, PHP ODP API, PHP PPTX library, PHP PowerPoint API, create PPT Presentations, add slide in PPT, modify PowerPoint PPT, add slide to Presentations, add chart to PPTX, add shape to PPTX. Covert PPT to PDF, Convert PPTX to PDF, Convert PPTX Free, Convert PPT Free
draft: false
weight: 1



ProductName: Gotenberg Go client
Githublink: https://github.com/thecodingmachine/gotenberg-php-client
ListingPage_Short_Description: Free and open-source library to convert PPTX and PPT to PDF
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert Microsoft Presentation Documents to PDF via Free PHP API"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP Library for Converting Microsoft<sup>®</sup> Presentation Files"
Header_H2_Text="Convert Microsoft Presentation Documents to PDF via Free PHP API" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Gotenberg PHP Client?</h2>
<p>The open-source API Gotenberg PHP Client allows PHP developers to convert Microsoft Presentations to PDF inside their own application. This is a simple, yet powerful feature to include in your application. You can not only convert your PPT and PPTX to PDF but can also merge one or more documents into a single PDF. The API is simple and lightweight and can be easily integrated into your applications.</p>

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
<p>An overview of Gotenberg PHP Client features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Convert Presentation to PDF</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Gotenberg PHP Client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Gotenberg PHP Client supports popular Microsoft PowerPoint formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/ppt/">PPT</a>, <a href="https://docs.fileformat.com/presentation/pptx/">PPTX</a></li>
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
<div class="d1-logo" style="border: none;"><header>Gotenberg PHP Client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Unless your project already has a PSR7 HttpClient, your project requires guzzle6-adapter</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>guzzle6-adapter</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;">=<header>Gotenberg Go client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Gotenberg PHP client</h2>
<p>The recommended way Gotenberg PHP Client into your project is by using composer. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Gotenberg PHP Client via Composer</h3>
<pre><code class="html">$ composer require thecodingmachine/gotenberg-php-client
              </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert PPTX to PDF via Free PHP API</h2>
<p>The free API Gotenberg PHP client allows PHP developers to convert PPT & PPTX document into PDF inside their own applications. To merge and convert your PPTX to PDF, you just need to load your document and convert it using OfficeRequest() method. The following code snippet shows how to convert PPTX to PDF in PHP.</p>
<h3>Free API to Convert PPTX to PDF in PHP</h3>
<ol>
<li>Load PPTX file using DocumentFactory::makeFromPath() method and pass filename and file path as parameters</li>
<li>Convert PPTX to PDF using OfficeRequest() method and pass file objects as parameter</li>
<li>Save PDF document</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert PPTX to PDF via Free PHP API</h3>
<pre><code class="php">$client = new Client('http://localhost:3000', new \Http\Adapter\Guzzle6\Client());
$file = [
  DocumentFactory::makeFromPath('document.pptx', '/path/to/file')
];
$request = new OfficeRequest($file);
$dest = 'fileformat.pdf';
$client-&gt;store($request, $dest);
              </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}