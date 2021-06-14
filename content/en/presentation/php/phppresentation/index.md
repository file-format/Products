---
title: PHP Class Library for Reading & Writing PPT, PPTX & ODP Presentations
description: PHP Presentation - An Open Source Free PHP API for PowerPoint PPT, PPTX & ODP Presentations. Work with slides, shapes, plain & 3D charts via PHP library.
keywords: Free PPTX library, Free PowerPoint, Free presenations API, PHP PowerPoint API, PHP PPT, PHP PPTX, PHP ODP API, PHP PPTX library, PHP PowerPoint API, create PPT Presentations, add slide in PPT, modify PowerPoint PPT, add slide to Presentations, add chart to PPTX, add shape to PPTX, 
draft: false
weight: 4



ProductName: PHPPresentation
Githublink: https://github.com/PHPOffice/PHPPresentation
ListingPage_Short_Description: Add presentation processing capabilities such as creation, editing, formatting, conversion & much more into your PHP applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHPPresentation"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="PHP Class Library for Presentation Formats"
Header_H2_Text="" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is PHPPresentation?</h2>
<p>PHPPresentation is a collection of classes provided as an open-source PHP library that lets you perform read and write operations on different Microsoft PowerPoint and OpenOffice presentation file formats. Using PHPPresentation library, you can work with presentation slides, shapes, formatting styles, plain and 3D charts, slide comments and drawing objects.</p>

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
<p>An overview of PHPPresentation features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header>Overview</header>
<ul>
<li>Slides</li>
<li>Shapes</li>
<li>Styles</li>
<li>Charts</li>
<li>Comments</li>
<li>Drawing</li>
<li>Media</li>
<li>RichText</li>
<li>Tables</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPPresentation"><header>PHPPresentation</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>PHPPresentation supports popular Microsoft PowerPoint & OpenOffice file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/presentation/pptx/">PPTX</a>, <a href="https://wiki.fileformat.com/presentation/odp/">ODP</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/presentation/ppt/">PPT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPPresentation"><header>PHPPresentation</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>There are two ways to install PHPPresentation, i.e. via <a href="http://getcomposer.org/">Composer</a> or manually by downloading the library.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i>Mandatory</header>
<ul>
<li>PHP 5.3+</li>
<li><a href="http://php.net/manual/en/book.zip.php">PHP Zip</a> extension</li>
<li><a href="http://www.php.net/manual/en/xml.installation.php">PHP XML Parser</a> extension</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPPresentation"><header>PHPPresentation</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PHPPresentation</h2>
<p>To use PHPPresentation on your system, you need to install PHP version 5.1 or newer.  The recommended way to install the PHPPresentation library is through <a href="http://getcomposer.org/">composer</a>. Please add the following lines to your composer.json.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the command</h3>
<pre><code class="html"> {
    "require": {
       "phpoffice/phppresentation": "dev-master"
    }
}<br></code></pre>


<p>Composer offers a convenient installer that you can execute directly from the command line. Feel free to download this file or review it on <a href="https://github.com/composer/getcomposer.org/blob/master/web/installer">GitHub.</a> There are two ways to install Composer. Install it locally as part of your project, or globally as a system-wide executable.</p>
<p>You can also manually install PHPPresentation by downloading the latest release from the Github <a href="https://github.com/PHPOffice/PHPPresentation/releases">releases page</a> . Please do register the autoloader if you do not use composer in your project.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Customize Presentation Settings</h2>
<p>PHPPresentation allows you to access and set various properties of presentations. Title, creator and company name can be configured. You can also configure if the presentation displays the comments or not. Similarly, you can also set the last view of the presentation, the thumbnail of the presentation, as well as the zoom value for the presentation. By using the following lines of code you can set Presentation Settings</p>
<h3>Set Presentation Settings in PHP</h3>
<ol>
<li>Initialize PhpPresentation</li>
<li>Get PresentationProperties</li>
<li>Enable display for the comments</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Enable Display for Comments</h3>
<pre><code class="c#">$oPresentation = new PhpPresentation();
$oProperties = $oPresentation-&gt;getPresentationProperties();
// enable the display for comment
$oProperties-&gt;setCommentVisible(true);
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Customize Slide Settings</h2>
<p>PHPPresentation allows you to define the name of the slides. You can also make any slides visible or hidden within the presentation. You can add various type of shape objects to slides, such as rich-text, line, chart, drawing, and table. Furthermore, you can also configure the common properties and styles of these shapes. Multiple animations can be created on a slide. WMV and OGV video media can be embedded in slides for Microsoft Windows and Linux readers, respectively. RichText, drawing objects and tables can also be worked with using PHPPresentation.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Work with Charts and Styles</h2>
<p>Using PHPPresentation you can create, customize and embed charts in slides. Both minor and major type of gridlines can be defined for the X and Y-axis. Also, you can configure the gridline width, its fill type and fill color. At the moment support is available for Bar Charts and 3D Bar Charts.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}