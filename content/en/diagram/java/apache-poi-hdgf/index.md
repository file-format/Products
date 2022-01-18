---
title: Open Source Java Library for Visio Diagrams – Extract Text from VSD
description: Apache POI HDGF- Open Source Java Library for Visio VSD diagrams. Access, read & extract textual content from Microsoft Visio VSD file format via Java API.
keywords: Free Visio API, Free Visio library, Open Source Visio API, Java Visio Diagraming, Java Diagram APIs, Java Visio API, Java .vlc API, Java Visio library, create Visio diagrams, modify Visio diagrams, read Visio files in Java, Open Source Visio VSD
draft: false
weight: 1



ProductName: Apache POI HDGF 
Githublink: https://github.com/apache/poi
ListingPage_Short_Description: Open Source Java library for Microsoft Visio binary files that provides the ability to read low level contents as well as extract textual contents from a Visio diagram.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache POI HDGF"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Java Library for Visio Diagrams"
Header_H2_Text="Read & Extract textual contents stored in Microsoft Visio Binary format via Free Java APIs." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Apache POI HDGF (Horrible DiaGram Format) is a pure Java implementation for Microsoft Visio binary (VSD) files. This module is young and its capabilities are limited at this time, however, it provides low-level access to the streams, chunks and chunk commands in order to provide a way to extract the textual content from the file. </p>

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
<p>An overview of Apache POI-HDGF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Accessing Visio documents</li>
<li>Read Visio files</li>
<li>Extract textual content</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HDGF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache POI HDGF supports popular Microsoft Visio file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader Only</header>
<ul>
<li><a href="https://docs.fileformat.com/image/vsd/">VSD</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer Only</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HDGF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache POI-HDGF only requires Java run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HDGF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache POI HDGF</h2>
<p>First of all, you need to have the Java Development Kit (JDK) installed on your system. If you already have it then proceed to the Apache POI's <a href="http://poi.apache.org/download.html">download</a> page to get the latest stable release in an archive. Extract the contents of the ZIP file in any directory from where the required libraries can be linked to your Java program. That is all!</p>
<p>Referencing Apache POI in your Maven-based Java project is even simpler. All you need is to add the following dependency in your pom.xml and let your IDE fetch and reference the Apache POI Jar files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Apache POI Maven Dependency</h3>
<pre><code class="html">&lt;!-- https://mvnrepository.com/artifact/org.apache.poi/poi --&gt;
&lt;dependency&gt;
 &lt;groupId&gt;org.apache.poi&lt;/groupId&gt;
 &lt;artifactId&gt;poi-scratchpad&lt;/artifactId&gt;
 &lt;version&gt;4.1.0&lt;/version&gt;
&lt;/dependency&gt;
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract<strong> </strong>Textual Content from a Visio Diagram using Java</h2>
<p>Apache POI HDGF has provided basic text extraction for all the project supported file formats. POI-HDGF allows software developers to extract the textual content from a Visio file. Developers need to iterate through the Visio diagram pages to cover the whole Visio diagram text. They can use VisioTextExtractor class to locate all the text entries in a Visio file and returns their contents. It Returns the textual contents of the file. Each textual object's text will be separated by a newline.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract Text from VSD - Java</h3>
<pre><code class="java">// open VSD file
VisioTextExtractor extractor = new VisioTextExtractor(new FileInputStream("sample.vsd"));
// read text
System.out.println(extractor.getAllText());
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Java APIs to Access and Read Microsoft Visio Diagrams</h2>
<p>Apache POI-HDGF enables programmers to Access Visio documents in VSD file formats. Developers can read the contents of a Visio diagram. As the API is at a early stage, therefore, the available features are limited at this time. </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"> </h2>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}