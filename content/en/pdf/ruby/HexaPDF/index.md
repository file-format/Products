---
title: Open Source Ruby Library – Load, Parse & Merge PDF Files, Reduce Size
description: HexaPDF - Open Source Ruby PDF library allows Software Developers to generate, edit & merge PDF files. Encrypt, Load, Parse & Reduce PDF Size via Ruby API.
keywords: PDF library,  Ruby PDF,  Java  PDF Library, Open Source PDF Library, Ruby PDF programming, Ruby PDF APIs, Ruby PDF library, create  PDF Documents, insert images to PDF, add list to PDF files, Extract Text from PDF, Split PDF to many, fill a PDF form, Extract data from PDF forms, Print a PDF file, PDF to PNG conversion, convert PDF to JPEG, Digitally sign PDF files
draft: false
weight: 1



ProductName: HexaPDF
Githublink: https://github.com/gettalong/hexapdf
ListingPage_Short_Description: Ruby library that enbables programmers to create & modify PDF documents, add text, reduce size of PDF, merge multiple files and so on.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="HexaPDF"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Ruby Library for PDF Processing"
Header_H2_Text="Create & modify PDF documents, merge PDF files, reduce size of PDFs, add annotations, extract images & text via Open Source free Ruby library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Portable Document Format (<em>PDF</em>) is a multi-platform file format that can be used to share and display documents in an electronic form independent of the software, hardware or operating system. HexaPDF is an open source PDF library that allows software developers to create powerful applications for working with PDF documents using Ruby code. It facilitates developers to create PDF files from scratch with minimum effort.</p>
<p>HexaPDF is a pure Ruby library that was designed to provide ease of use and improved performance. The library has included several important features related to PDF documents generation as well as manipulation such as opening & reading existing PDFs, modifying existing PDF files, meta information & text extraction, extracting images and files from PDFs, merging PDF files, encrypting or decrypting PDF files, optimizing PDF files for smaller file size and many more.</p>
<p>The library fully supports a high-level layer for composing a document of individual elements such as headers, paragraphs, links, emphasized text, and more. These elements are automatically adjusted, customized, and can be modified according to your needs. You can add additional element types with ease.</p>
<p><span style="font-size: 12.16px;">.</span></p>

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
<p>An overview of HexaPDF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Generate PDF</li>
<li>Reading PDF</li>
<li>Edit PDF</li>
<li>Meta information</li>
<li>Insert text</li>
<li>Add images</li>
<li>Text extraction</li>
<li>Manipulate PDF</li>
<li>Data Extraction</li>
<li>Header & Footer</li>
<li>Add pages</li>
<li>Draw shapes</li>
<li>PDF annotation </li>
</ul>
</div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PDF processing in Ruby"><header>HexaPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>HexaPDF supports PDF file format as well as industry-standard formats for export.</p>
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
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PDF Prcessing in Ruby"><header>HexaPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>HexaPDF only requires Ruby runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i></header>
<ul>
<li>Ruby</li>
</ul>
</div>
<!--/left--> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PDF Processing in Ruby"><header>HexaPDF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with HexaPDF</h2>
<p>For a smooth use of the HexaPDF library first important step is to install it. The recommended way for the installation is by using Rubygem. Please use the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install HexaPDF using Rubygem</h3>
<pre><code class="html"> $ gem install hexapdf </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create New PDFs using Ruby Library</h2>
<p>The open source PDF library HexaPDF has provided complete functionality for creating new PDF documents from the scratch with just a couple of Ruby commands. You need an empty document instance for PDF creation. Once the empty PDF file is created now it is possible to add new pages to it, draw lines, curves, rectangles, insert text, and apply colors to it. You can also adjust line size and apply different colors and effects to it.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Merging PDF Files via Ruby</h2>
<p>The Free PDF library HexaPDF makes is it easy for software programmers to combine their PDF documents using Ruby code. Merging PDF files can be performed using various ways. One simple way is to import pages from the source files into the target files. Which will preserve the page contents and then the merging command can be applied for merging files. For more complex merging please use the HexaPDF binary command.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Optimize PDF Size via Ruby Library</h2>
<p>The open source PDF library HexaPDF helps software professionals to reduce the size of PDF documents inside Ruby applications. There are different kinds of techniques that can be used to optimize the size of PDF such as removing unused and deleted objects, using object and cross-reference streams and recompressing page content streams, font sub-setting, merging or object, and so on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">PDF Encryption & Decrypting Support</h2>
<p>The HexaPDF library allows developers to secure their PDF documents by applying encryption using Ruby code.  A PDF has built-in support for securing them by encrypting the content and assigning usage rights. During the PDF encryption, all strings and byte streams are encrypted and the metadata stream is exempted so that it can be extracted during the parsing of the PDF file. So anyone interested to view the PDF documents must provide the password.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}