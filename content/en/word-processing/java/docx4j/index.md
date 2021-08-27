---
title: Open Source Java Library for DOCX Files | DOCX4J
description: POI- XWPF Library - Create, manipulate, convert and edit Word .docx documents via Java library
keywords: Java Word processing , Word processing API, Open Source Word processing, Java Word .docx APIs,  Java Docx API, Java word API, create  .docx files, modify Word documents, add image to document, Open Source Java Libraries
draft: false
weight: 9



ProductName: DOCX4J  
Githublink: https://github.com/plutext/docx4j
ListingPage_Short_Description: DOCX4J allows manipulating DOCX file format using your Java applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Create, Read, Edit and Convert Microsoft Word DOCX files, add text & tables via Java Libray."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Java API for Word DOCX Documents"
Header_H2_Text="Create, Read, Edit and Convert Microsoft Word DOCX files, add text & tables via Java Libray." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>DOCX4J is JAXB-based open source(Apache v2) library for manipulating Microsoft Office file formats. It provides the functionality to read, write, edit & and save Microsoft Word 2007 DOCX file format.  </p>
<p>DOCX4J is similar to Microsoft's OpenXML SDK, but for Java. It uses JAXB to create the in-memory object representation. Using the API you can generate Mircosoft Office documents, edit them, format the text & paragraphs, insert tables & images and manage other form elements and much more. Basically, its emphasis is on power, if the format supports it you can do it using the API.</p>

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
<li>Generate DOCX file</li>
<li>Add paragraphs</li>
<li>Apply font styles</li>
<li>Add table</li>
<li>Apply a border to paragraph</li>
<li>Format title & subtitle</li>
<li>Insert images</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Extract paragraph</li>
<li>Work with ranges</li>
<li>Manage headers/footers</li>
<li>Add forms to documents</li>
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
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/web/html/">HTML</a>, <a href="https://docs.fileformat.com/page-description-language/xslfo/">FO</a>, <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/view/pdf/">PDF</a></li>
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
<h2 class="h2title">Add Paragraph, Image & Table to Word Documents</h2>
<p>DOCX4J allows the developers to add paragraphs & images to Word documents. The API also provides the feature to add tables to DOCX document while making it possible to create simple and nested tables with user-defined data.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create DOCX Free using DOCX4J - Java</h3>
<pre><code class="">// Create word package
WordprocessingMLPackage wordPackage = WordprocessingMLPackage.createPackage();
// Create main document part
MainDocumentPart mainDocumentPart = wordPackage.getMainDocumentPart();
// Add Paragraph
mainDocumentPart.addParagraphOfText("Open Source Java API for Word DOCX Documents");
// Save file
wordPackage.save(new File("FileFormat.docx"));
                                    
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Text from DOCX</h2>
<p>DOCX4J provides the specialized class to extract data from Microsoft Word DOCX documents with just a few lines of code. In the same way, it can also extract headings, footnotes, table data and so on from a Word file.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract Text from DOCX Free - Java</h3>
<pre><code class="html">// Load document
WordprocessingMLPackage wordMLPackage = WordprocessingMLPackage.load(new File("FileFormat.docx"));
// Load main document part
MainDocumentPart mainDocumentPart = wordMLPackage.getMainDocumentPart();
// Extract nodes
String textNodesXPath = "//w:t";
List&lt;Object&gt; textNodes= mainDocumentPart.getJAXBNodesViaXPath(textNodesXPath, true);
// Print text
for (Object obj : textNodes) {
    Text text = (Text) ((JAXBElement) obj).getValue();
    String textValue = text.getValue();
    System.out.println(textValue);
}                                  
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate & Edit Word Documents using Java API</h2>
<p>DOCX4J enables the software programmers to create new Word Documents in DOCX file format. Developers can also load an existing Microsoft Word DOCX file to edit it according to their application needs. It allows to add new paragraphs, insert text, apply text alignment & borders, change text styling and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}