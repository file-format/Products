---
title: Java API for Word OOXML Documents - Adding Paragraph, Image & Table
description: POI- XWPF - Open Source Free Java Library for Word DOCX Files. Developers can create, convert, add paragraph, Images & Table to Word DOCX documents via Java API.
keywords: Free Word API, Free Java API, Free DOCX API, Open Source DOCX API, Free DOCX Java, Random Word API, Free Java Word processing , Word processing API, Open Source Word processing, Convert DOCX Free, Java Word .docx APIs, Java Docx API, Java word API, create .docx files, modify Word documents, add image to document, Open Source Java Libraries
draft: false
weight: 4



ProductName: Apache POI XWPF 
Githublink: https://github.com/apache/poi
ListingPage_Short_Description: XWPF allows adding Microsoft Word 2007 DOCX file processing capabilities to your Java applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache POI XWPF"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Java API for Word OOXML Documents"
Header_H2_Text="Open Source solution to Create, Read, Edit and Convert Microsoft Word DOCX files in Java applications." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Apache POI XWPF provides the functionality to read & write Microsoft Word 2007 DOCX file format. XWPF has a fairly stable core API, providing access to the main parts of a Word DOCX file. It can be used for basic & specific text extraction, manipulation of header & footer, text manipulation & styling features. </p>
<p>Apache POI XWPF is more renowned for Microsoft Word file generation & document editing, formatting of text & paragraphs, image insertion, table creation & parsing, mail merge features, management of form elements and much more.</p>

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
<p>An overview of Apache POI XWPF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Generate DOCX file</li>
<li>Add paragraphs</li>
<li>Apply font styles</li>
<li>Convert DOCX files to other formats</li>
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
<li>Mail merge support</li>
<li>Add endnotes</li>
<li>Add footnotes</li>
<li>Extract images</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI XWPF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache POI-XWPF supports Microsoft Word Office Open XML file format.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/web/html/">HTML</a>, <a href="https://docs.fileformat.com/page-description-language/xslfo/">FO</a>, <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI XWPF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache POI-XWPF only requires Java runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI XWPF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache POI XWPF</h2>
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
<h2 class="h2title">Generate & Edit Word Documents using Java API</h2>
<p>Apache POI XWPF enables the software programmers to create new Word Documents in DOCX file format. Developers can also load an existing Microsoft Word DOCX file to edit it according to their application needs. It allows to add new paragraphs, insert text, apply text alignment & borders, change text styling and more.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Generate a DOCX file from scratch</h3>
<pre><code class="java">// initialize a blank document
XWPFDocument document = new XWPFDocument();
// create a new file
FileOutputStream out = new FileOutputStream(new File("document.docx"));
// create a new paragraph paragraph
XWPFParagraph paragraph = document.createParagraph();
XWPFRun run = paragraph.createRun();
run.setText("File Format Developer Guide -" +
 "Learn about computer files that you come across in" +
 "your daily work at: www.fileformat.com");
document.write(out);
out.close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Paragraph, Image & Table to Word Documents</h2>
<p>Apache POI XWPF allows the developers to add paragraphs & images to Word documents. The API also provides the feature to add tables to DOCX document while making it possible to create simple and nested tables with user-defined data.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create a new DOCX file with a table</h3>
<pre><code class="java">// initialize a blank document
XWPFDocument document = new XWPFDocument();
// create a new file
FileOutputStream out = new FileOutputStream(new File("table.docx"));
// create a new table
XWPFTable table = document.createTable();

// create first row
XWPFTableRow tableRowOne = table.getRow(0);
tableRowOne.getCell(0).setText("Serial No");
tableRowOne.addNewTableCell().setText("Products");
tableRowOne.addNewTableCell().setText("Formats");

// create second row
XWPFTableRow tableRowTwo = table.createRow();
tableRowTwo.getCell(0).setText("1");
tableRowTwo.getCell(1).setText("Apache POI XWPF");
tableRowTwo.getCell(2).setText("DOCX, HTML, FO, TXT, PDF");

// create third row
XWPFTableRow tableRowThree = table.createRow();
tableRowThree.getCell(0).setText("2");
tableRowThree.getCell(1).setText("Apache POI HWPF");
tableRowThree.getCell(2).setText("DOC, HTML, FO, TXT");

document.write(out);
out.close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Text from Word OOXML Document</h2>
<p>Apache POI XWPF provides the specialized class to extract data from Microsoft Word DOCX documents with just a few lines of code. In the same way, it can also extract headings, footnotes, table data and so on from a Word file.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract text from a Word file</h3>
<pre><code class="java">// load DOCX file
FileInputStream fis = new FileInputStream("document.docx");
// open file
XWPFDocument file = new XWPFDocument(OPCPackage.open(fis));
// read text
XWPFWordExtractor ext = new XWPFWordExtractor(file);
// display text
System.out.println(ext.getText());
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Custom Header & Footer to DOCX Documents</h2>
<p>Header and footer are an important part of the Word document as those usually contain extra information such as dates, page numbers, author's name and footnotes, which help in keeping longer documents organized and easier to read. Apache POI XWPF allows Java developers to add custom headers and footers to Word documents.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}