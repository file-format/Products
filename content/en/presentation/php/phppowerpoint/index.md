---
title: Open Source PHP PowerPoint API – Generate & Modify PPTX & ODP Files
description: PHPPowerPoint - Open Source Free PHP API allows Developers to create & convert PowerPoint PPTX & ODP Presentations. Add charts & shapes PPTX files.
keywords: PHP PowerPoint API, PHP PPT, PHP PPTX, PHP ODP API, PHP PPTX library, PHP PowerPoint API, create PPT Presentations, add slide in PPT, modify PowerPoint PPT, add slide to Presentations, add chart to PPTX, add shape to PPTX.
draft: false
weight: 9



ProductName: PHPPowerPoint
Githublink: https://github.com/delphiki/PHPPowerPoint
ListingPage_Short_Description: Read and write popular presentation file formats like PPTX and ODP via open source PHP library.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHPPowerPoint"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP API for Microsoft<sup>®</sup> PowerPoint Files"
Header_H2_Text=" Generate, Modify & Convert PPTX or ODP Presentation Files via Free PHP Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is PHPPowerPoint?</h2>
<p>PHPPowerPoint is an open source PHP library gives software developers the capability to read and write popular presentation file formats like PPTX and ODP. It provides support for setting presentation Metadata such as author, title, description, etc. It also supports different formatting, styles, fills, gradients. You can also use different printing options such as header, footer, page margins, paper size, and orientation, etc.</p>
<p>PHPPowerPoint provides support for several important features such as Set presentation metadata, add slides, fonts and font styles support, various formatting & styles support, add hyperlinks and rich-text strings, add images, setting printing options and more.</p>
<p> </p>

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
<p>An overview of PHPPowerPoint features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header>Overview</header>
<ul>
<li>Create presentation</li>
<li>Set metadata</li>
<li>Add slides,</li>
<li>Font styles support</li>
<li>Apply formatting</li>
<li>Styles support</li>
<li>add hyperlinks</li>
<li>Add images</li>
<li>Printing options</li>
<li>Set Print Area</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPPresentation"><header>PHPPowerPoint</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>PHPPowerPoint supports popular Microsoft PowerPoint & OpenOffice file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/pptx/">PPTX</a>, <a href="https://docs.fileformat.com/presentation/odp/">ODP</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPPresentation"><header>PHPPowerPoint</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>There are two ways to install PHPPowerPoint, i.e. via <a href="https://getcomposer.org/">Composer</a> or manually by downloading the library.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i>Mandatory</header>
<ul>
<li>PHP 5.3+</li>
<li><a href="https://www.php.net/manual/en/book.zip.php">PHP Zip</a> extension</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPPresentation"><header>PHPPowerPoint</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PHPPowerPoint</h2>
<p>To install and use PHPPowerPoint, copy the contents of the Classes folder and include PHPPowerPoint.php somewhere in your code like below.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Include Code in PHPPowerPoint.php</h3>
<pre><code class="html"> include_once '/path/to/Classes/PHPPowerPoint.php'; </code></pre>

<p>After that, you can use the library by creating a new instance of the class.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate & Modify PPTX Presentations via PHP API</h2>
<p>PHPPowerPoint library enables software developers to create a new PowerPoint presentation file inside their own PHP applications. Developers can set properties like the creator, setting title or subject, setting description, etc. Developers can also add a new slide, remove an existing slide, create template slide, insert image or shape to a slide and more using open source PHP API.</p>
<h3>Create PPTX in PHP</h3>
<ol>
<li>Initialize PHPPowerPoint</li>
<li>Create a new slide</li>
<li>Add text shape</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create PowerPoint Slide in PHP</h3>
<pre><code class="c#">$phpPowerPoint = new PHPPowerPoint();
// create new slide
$slide = $phpPowerPoint-&gt;createSlide();
// add text shape
$shape = $slide-&gt;createRichTextShape();
     </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Shapes to PowerPoint Presentations</h2>
<p>Software developers can easily add shapes into PPTX presentations using Open source PHP library PHPPowerPoint. Shapes are objects that can be included to a presentation’s slide. There several types of shapes that can be used inside presentations, such as rich text, line, chart, drawing, and table, etc.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Chart to PPTX Presentations via PHP</h2>
<p>PHPPowerPoint allows developers to add charts and images into a PowerPoint presentation. The library provides support for bar, pie, line or a scatter chart. To insert a chart, first of all, you need to add a slide and then generate sample data for the chart. After that, you can create a chart that should be inserted in a shape.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}