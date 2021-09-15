---
title: Java API for PowerPoint Presentation - Add Slides & Charts in PPTX Files
description: DOCX4J - An Open Source Free Java API for PowerPoint PPTX presentations. Create, add & manipulate slides & charts inside OOXML Presentations via Java library.
keywords: Java PPTX, Java PPTX API, Free PPTX API, Free PowerPoint library, Java PPTX library, Java PowerPoint API, create PPTX Presentations, add slide in PPTX, modify PowerPoint PPTX, add slide to Presentations, Open Source PPTX Libraries, Open Source PowerPoint API
draft: false
weight: 8



ProductName: DOCX4J
Githublink: https://github.com/plutext/docx4j
ListingPage_Short_Description: DOCX4J allows creating, editing, manipulation & converting PPTX files via Java.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source solution to Create, Read, Edit and Convert Microsoft Presentation files in Java applications."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Java API for PPTX Presentation Documents"
Header_H2_Text="Open Source solution to Create, Read, Edit and Convert Microsoft Presentation files in Java applications." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>DOCX4J is similar to Microsoft's OpenXML SDK, but for Java. DOCX4J is JAXB-based open source(Apache v2) library for manipulating Microsoft Office file formats. It provides the functionality to read, write, edit and save Microsoft Office 2007 PPTX file format.  </p>
<p>Using the API you can generate Presentation documents, edit them, format the text & paragraphs, insert tables & images and manage other form elements and much more. Basically, its emphasis is on power, if the format supports it you can do it using the API.</p>

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
<p>An overview of DOCX4J features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Generate PPTX file</li>
<li>Add Slides</li>
<li>Insert Charts</li>
<li>Add paragraphs</li>
<li>Apply font styles</li>
<li>Apply a border to paragraph</li>
<li>Format title & subtitle</li>
<li>Insert images</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Extract paragraph</li>
<li>Duplicate Slides</li>
<li>Read PPTX</li>
<li>Add endnotes</li>
<li>Add footnotes</li>
<li>Extract images</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>DOCX4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>DOCX4J supports the following formats.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/pptx/">PPTX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/presentation/pptx/">PPTX</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a>, <a href="https://docs.fileformat.com/page-description-language/xslfo/">FO</a>, <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>DOCX4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>DOCX4J only requires Java runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>DOCX4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with DOCX4J</h2>
<p>First of all, you need to have the Java Development Kit (JDK) installed on your system. Referencing DOCX4J in your Maven-based Java project is even simpler. All you need is to add the following dependency in your pom.xml and let your IDE fetch and reference the DOCX4J Jar files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>DOCX4J Maven Dependency</h3>
<pre><code class="html">&lt;dependency&gt;
&lt;groupId&gt;org.docx4j&lt;/groupId&gt;
&lt;artifactId&gt;docx4j-JAXB-Internal&lt;/artifactId&gt;
&lt;version&gt;8.0.0&lt;/version&gt;
&lt;/dependency&gt;

&lt;dependency&gt;
&lt;groupId&gt;org.docx4j&lt;/groupId&gt;
&lt;artifactId&gt;docx4j-JAXB-ReferenceImpl&lt;/artifactId&gt;
&lt;version&gt;8.0.0&lt;/version&gt;
&lt;/dependency&gt;

&lt;dependency&gt;
&lt;groupId&gt;org.docx4j&lt;/groupId&gt;
&lt;artifactId&gt;docx4j-JAXB-MOXy&lt;/artifactId&gt;
&lt;version&gt;8.0.0&lt;/version&gt;
&lt;/dependency&gt;
    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate & Modify PPTX using Java</h2>
<p>DOCX4J allows adding slides, specifying a layout for new slide, adding title and contents, inserting images and shapes, etc. Once done you can change the name of the existing presentation as well as can save it to the location of your choice.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Generate PPTX using DOCX4J - Java</h3>
<pre><code class="java">// Create package
PresentationMLPackage presentationMLPackage = PresentationMLPackage.createPackage();
// Create main presentation
MainPresentationPart pp = (MainPresentationPart) presentationMLPackage.getParts().getParts().get(new
                PartName("/ppt/presentation.xml"));
// Create slide layout
SlideLayoutPart layoutPart = (SlideLayoutPart)
        presentationMLPackage.getParts().getParts()
                .get(new PartName("/ppt/slideLayouts/slideLayout2.xml"));
// Save presentation
presentationMLPackage.save(new File("FileFormat.pptx"));
                                    
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract & Manipulate Slides using Java API</h2>
<p>DOCX4J enables the software programmers to create & extract slides form PPTX file format. Software programmers can add a slide to an existing presentation with ease. Every slide in a presentation is based on a slide layout. lide layout is like a template for a slide, it allows users to inherit formatting choices, text boxes, titles or graphics, etc.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manipulating Charts using DOCX4J</h2>
<p>DOCX4J provides the specialized class to add a single-series column chart, multi-series chart, bubble chart, Line chart, pie charts & more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}