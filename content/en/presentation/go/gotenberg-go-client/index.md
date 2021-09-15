---
title: Open Source Go Library to Convert PowerPoint to PDF Files
description: Gotenberg Go Client - Open Source Go library enables programmers to convert pptx and ppt to PDF
keywords: Go PPTX, Go Powerpoint, Go PowerPoint APIs, Go PPt API, Go  PPTX API, Go Powerpoint library, Free API, Open Source API, Convert PPTX, Convert PPT, PPTX to PDF, PPT to PDF. PDF conversion, PPTX conversion, PPT conversion 
draft: false
weight: 1



ProductName: Gotenberg Go client
Githublink: https://github.com/thecodingmachine/gotenberg-go-client
ListingPage_Short_Description: Free GO API to convert PPT and PPTX to PDF
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert Microsoft Presentations to PDF via Free GO API "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Converting Microsoft<sup>®</sup> PowerPoint Files"
Header_H2_Text="Convert Microsoft Presentations to PDF via Free GO API " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Gotenberg Go client?</h2>
<p>Often times, GO developers are looking for open-source and free APIs to convert Microsoft Presentation to PDF file format. Gotenberg Go client is free GO library for developers to convert PPT and PPTX to PDF file format easily. The developers can easily integrate PPTX to PDF and PPT to PDF conversion feature inside their own application.</p>
<p>By default, a handful of fonts are installed and the API also support Asian characters. In order to get any specific fonts in the output PDF document, you will have to install your own fonts.</p>

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
<li>Convert PowerPoint to PDF</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Gotenberg Go client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Gotenberg Go client supports popular Microsoft Presentation formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/ppt/">PPT</a>, <a href="https://docs.fileformat.com/presentation/ppt/">PPTX</a></li>
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
<div class="d1-logo" style="border: none;"><header>Gotenberg Go client</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Gotenberg Go client only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>go1.8+</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
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
<p>The recommended way to install the Gotenberg Go client into your project is by using Github. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Gotenberg Go client via GitHub</h3>
<pre><code class="html">$ go get -u github.com/thecodingmachine/gotenberg-go-client/v7
                                                    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert PPTX to PDF via Free Go API</h2>
<p>The open-source library Gotenberg Go client allows converting one or more Microsoft Presentation file formats to PDF file format in a single function. The API uses, gotenberg.NewOfficeRequest() method to load a new file and accepts filename and file path as parameters. In order to convert you PowerPoint file to PDF, you can load one or more file and convert it to PDF easily. The following code snippet demonstrates, how you can convert PPTX to PDF in GO</p>
<h3>Convert PowerPoint to PDF in GO</h3>
<ol>
<li>Load two PPTx files using NewDocumentFromPath() method and pass filename and file path as parameters</li>
<li>Convert both files to PDF using gotenberg.NewOfficeRequest() method and pass doc objects</li>
<li>Save PDF document</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert PPTX to PDF via Free GO API</h3>
<pre><code class="go">c := &gotenberg.Client{Hostname: "http://localhost:3000"}
    doc, _ := gotenberg.NewDocumentFromPath("document.pptx", "/path/to/file")
    doc2, _ := gotenberg.NewDocumentFromPath("document2.pptx", "/path/to/file")
    req := gotenberg.NewOfficeRequest(doc, doc2)
    dest := "fileformat.pdf"
    c.Store(req, dest)
                                                    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}