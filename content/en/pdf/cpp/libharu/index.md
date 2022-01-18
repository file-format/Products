---
title: Open Source C++ Library for PDF – Generate & Manipulate PDF Documents
description: Open Source C++ Library to create, edit, Manipulate & convert PDF files in native C++ applications.
keywords: C++ PDF, open source PDF, process PDF in C++, cpp PDF API, C ++ PDF Library, Open Source PDF Library, C++ PDF programming, C++ PDF API, Embed Images in PDF, C++ PDF API, generate PDF Documents, manipulate PDF files, PDF export , PDF manipulation
draft: false
weight: 6



ProductName: LibHaru
Githublink: https://github.com/libharu/libharu
ListingPage_Short_Description: C++ implementation of PDF format gives developers the capability to handle simple and complex PDF Documents inside their own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="LibHaru"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source C++ Library for PDF Documents"
Header_H2_Text="Generate, Edit, Manipulate & Convert PDF Files via Open Source C++ API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>LibHaru is an open source C++ library that enables software developers to generate PDF file format, currently, the API doesn't allow reading or edited existing PDF documents. Using the API you can generate PDF file - add text, lines, and annotations int it. Furthermore, you can also add images of PNG and JPEG format in the document. LibHaru also allows compressing the PDF document with the deflate-decode format and generates encrypted PDF documents.</p>
<p>LibHaru is written ANSI-C and can work both as static-library and shared-library. To use it with a C++ program you can compile it with any C++ compiler and use it as a static-library.</p>


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
<p>An overview of LibHaru features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Generate PDF file</li>
<li>Add text, lines, images</li>
<li>Add text and link Annotations</li>
<li>Embed JPEG and PNG images</li>
<li>Embed Fonts</li>
<li>Encrypt PDF files</li>
<li>Use various character set</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="LibHaru"><header>LibHaru</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>LibHaru supports PDF formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header></div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="LibHaru"><header>LibHaru</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>LibHaru requires the following libraries</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i> Mandatory</header>
<ul>
<li><a href="https://www.zlib.net/">Zlib</a></li>
<li><a href="http://www.libpng.org/">LibPng</a></li>
</ul>
</div>
<!--/left
<div class="d1-col d1-right">&nbsp;</div> --> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="LibHaru"><header>LibHaru</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with LibHaru</h2>
<p>LibHaru is written in ANSI-C and to use it with C++, you can compile it with any compliant C++ compiler. First of all, you can download and extract the latest version of the API. There are several kinds of makefile, for e compiler, in the script directory. Build the library with an appropriate makefile.</p>
<p>After you unpack the library in your desired folder, you can cd into the folder and run the following command to make a lib file</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="xml">NMAKE -f script/Makefile.msvcr
</code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">C++ Library to Generate PDF File Format</h2>
<p>LibHaru has provided a set of features that enables software developers to generate PDF file format. Using the API you can create a new PDF document, set document object attributes, create a new page, set page object, set page description and save the document to a file ora memory stream.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Embed Images in PDF using C++</h2>
<p>LibHaru enables software developers to embed JPEG and PNG images in PDF documents. Using the API you can get image size, width, height, bits per component and color space. Furthermore, you can set a color mask and mask image for the embedded image.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}