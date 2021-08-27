---
title: Open Source Java API for PowerPoint – Create & Merge Presentations
description: POI-XLSF - Open Source Free Java library for MS PowerPoint PPTX Presentations. Append Slide, Merge Multiple PPTX Presentations,  add images via Java API.
keywords: Java PPTX, Java PPTX API, Java PPTX library, Java PowerPoint API, create PPTX Presentations, add slide in PPTX, modify PowerPoint PPTX, add slide to Presentations, Open Source PPTX Libraries, Open Source PowerPoint API
draft: false
weight: 1



ProductName: Apache POI XSLF  
Githublink: https://github.com/apache/poi
ListingPage_Short_Description: Provides capabilities such as reading, writing, manipulation & conversion of PPTX files via Java.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache POI XSLF"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Java API for PPTX Presentations"
Header_H2_Text="Create, Edit and Merge Microsoft PowerPoint OOXML Presentations via Java Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Apache POI XLSF is Java implementation for reading, creating or editing PowerPoint PPTX files. It provides the necessary functionality for working with PowerPoint 2007 OOXML file format, enabling developers to extract data such as text, images, embedded objects & more from PowerPoint PPTX presentations. Developers can also add shapes to a slide, manage hyperlinks & images, add videos, and convert PPTX to SVG.</p>

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
<p>An overview of Apache POI XLSF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create presentation</li>
<li>Read presentation</li>
<li>Create slides</li>
<li>Manage slide layout</li>
<li>Manage hyperlinks</li>
<li>Add images</li>
<li>Add video to PPTX </li>
<li>Convert PPTX to SVG</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Add chart</li>
<li>Format text</li>
<li>Append slide</li>
<li>Merge presentations</li>
<li>Re-order slides</li>
<li>Add image to slide</li>
<li>Delete slide</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI XLSF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache POI XLSF supports popular PowerPoint file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/pptx/">PPTX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/page-description-language/svg/">SVG</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI XLSF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache POI XLSF only requires Java runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI XLSF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache POI XLSF</h2>
<p>First of all, you need to have the Java Development Kit (JDK) installed on your system. If you already have it then proceed to the Apache POI's <a href="http://poi.apache.org/download.html">download</a> page to get the latest stable release in an archive. Extract the contents of the ZIP file in any directory from where the required libraries can be linked to your Java program. That is all!</p>
<p>Referencing Apache POI in your Maven-based Java project is even simpler. All you need is to add the following dependency in your pom.xml and let your IDE fetch and reference the Apache POI Jar files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Apache POI Maven Dependency</h3>
<pre><code class="html">&lt;!-- https://mvnrepository.com/artifact/org.apache.poi/poi --&gt;
&lt;dependency&gt;
    &lt;groupId&gt;org.apache.poi&lt;/groupId&gt;
    &lt;artifactId&gt;poi&lt;/artifactId&gt;
    &lt;version&gt;4.1.0&lt;/version&gt;
&lt;/dependency&gt;
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Java API to Create New Presentations & Append Slide to Existing File</h2>
<p>Apache POI XLSF enables computer programmers to create new PowerPoint presentations in PPTX file format from scratch. Developers can also transform an existing presentation according to their needs. It provides the ability to read & modify the existing presentations as well as append slides to the existing presentation according to their need.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create a Slide - Java</h3>
<pre><code class="java">// create a new PPTX file
FileOutputStream fileOutputStream = new FileOutputStream(new File("Slide.pptx"));
// create a new slide show
XMLSlideShow xmlSlideShow = new XMLSlideShow();
// save file
xmlSlideShow.write(fileOutputStream);
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create New Slide from a Predefined Slide Layout in Java Apps</h2>
<p>Apache POI XLSF API has included support for adding new slides from a predefined slide layout inside PPTX presentation. <em>Slide layouts</em> contain formatting, positioning, and placeholder boxes for all of the content that appears on a slide.  PowerPoint presentations have several slide layouts; first of all, you need to see which slide layouts are available for use. There are different slide masters and in each slide master, there are several slide layouts. </p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Title Layout Slide - Java</h3>
<pre><code class="java">//  create a new PPTX file
FileOutputStream fileOutputStream = new FileOutputStream(new File("Slidelayout.pptx"));
// create a new slide show
XMLSlideShow xmlSlideShow = new XMLSlideShow();
// initialize slide master object
XSLFSlideMaster xslfSlideMaster = xmlSlideShow.getSlideMasters().get(0);
// set Title layout
XSLFSlideLayout xslfSlideLayout = xslfSlideMaster.getLayout(SlideLayout.TITLE);
// create a new slide with title layout
XSLFSlide xslfSlide = xmlSlideShow.createSlide(xslfSlideLayout);
// select place holder
XSLFTextShape xslfTextShape = xslfSlide.getPlaceholder(0);
// set title
xslfTextShape.setText("Test");
// save file
xmlSlideShow.write(fileOutputStream);
// close stream
fileOutputStream.close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Merge Multiple PPTX Presentations together using Java</h2>
<p>Do you have multiple PPTX presentations that you want to combine into one presentation? Apache POI XLSF APIs can surely help you and enables Java developers to merge their multiple PPTX files together.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Merge Slides - Java</h3>
<pre><code class="java">// create a new PPTX file
FileOutputStream fileOutputStream = new FileOutputStream("MergegSlide.pptx");
// select two PPTX files
String[] inputFiles = {"Slide.pptx", "SlideLayout.pptx"};
// create a new slide show
XMLSlideShow slideShow = new XMLSlideShow();
// merge slides
for(String file : inputFiles){
    FileInputStream inputstream = new FileInputStream(file);
    XMLSlideShow xmlSlideShow = new XMLSlideShow(inputstream);
    for(XSLFSlide srcSlide : xmlSlideShow.getSlides()) {
        slideShow.createSlide().importContent(srcSlide);
    }
}
// saving file
slideShow.write(fileOutputStream);
// close stream
fileOutputStream.close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}