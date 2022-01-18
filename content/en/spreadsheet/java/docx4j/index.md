---
title: Open Source Java Spreadsheet Library for XLSX Files | DOCX4J
description: DOCX4J - Open Source Free Java Excel Spreadsheet Library. Read, write, edit & convert Microsoft Excel Spreadsheets via Java API.
keywords: Java Excel APIs, Java .xlsx, Java .xlsx API, Java .xlsx library, Java Excel library, create Excel spreadsheet, convert XLSX to CSV, add sheet to workbook, convert XLSX to HTML, add cells to sheet, Java Excel programming, modify Excel files, add chart to Excel files, Open Source Excel Library, Free Java Excel APIs, Open Source Java API for Excel, Open Source Spreadsheet APIs, Free, Open Source Excel Library,
draft: false
weight: 11



ProductName: DOCX4J
Githublink: https://github.com/plutext/docx4j
ListingPage_Short_Description: Open Source Java Library supports reading and writing XLSX spreadsheet file format, in a fast and scalable way.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Create, Read, Edit and Convert Microsoft Excel Spreadsheet files in Java applications via Open Source API."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Java Library for Microsoft<sup>®</sup> Spreadsheet Documents"
Header_H2_Text="Create, Read, Edit and Convert Microsoft Excel Spreadsheet files in Java applications via Open Source API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is DOCX4J?</h2>
<p>DOCX4J is similar to Microsoft's OpenXML SDK, but for Java. DOCX4J is JAXB-based open source(Apache v2) library for manipulating Mircorsoft Office file formats. It provides the functionality to read, write, edit & and save XLSX file format.</p>
<p>Using the API you can generate Spreadsheet documents, edit them, format the text & paragraphs,insert charts, insert tables & images and manage other form elements and much more. Basically, it emphasis is on power, if the format supports it you can do it using the API.</p>

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
<li>Generate XLSX file</li>
<li>Add Cells & Columns</li>
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
<li>Read XLSX</li>
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
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a>, <a href="https://docs.fileformat.com/page-description-language/xslfo/">FO</a>, <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/pdf/">PDF</a></li>
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
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
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
<h2 class="h2title">Java Library to Read & Write XLSX</h2>
<p>It is a powerful library to Create & Manipulate exisitng as well as new XLSX file format. It enables the developers to access and read data from a specific sheet inside a spreadsheet. Usually a spreadsheet contains several worksheets. If a user is interested to read data from only one sheet and skip the other sheets. By using the following steps, you can create Microsoft Excel in Java</p>
<h3>Create Excel Easily</h3>
<ol>
<li>Initialize object of SpreadsheetMLPackage</li>
<li>Create worksheet</li>
<li>Get sheet data</li>
<li>Save document</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create Excel Free using Java</h3>
<pre><code class="java">// Create spreadsheet package
SpreadsheetMLPackage pkg = SpreadsheetMLPackage.createPackage();
// Create worksheet
WorksheetPart sheet = pkg.createWorksheetPart(new PartName("/xl/worksheets/sheet1.xml"),"Sheet1", 1);
SheetData sheetData = sheet.getContents().getSheetData();
// Save
pkg.save(new File("FileFormat.xlsx"));        
         </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Work with Spreadsheet Cells using Java API</h2>
<p>DOCX4J allows you to access cell and set its value by coordinates. You can also create a new cell and set up a formula in it. You can also configure the cell to occupy various types of data, such as date, time, and number with leading zeros.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Add Content in Excel Cell - Java</h3>
<pre><code class="java">// Create spreadsheet package
SpreadsheetMLPackage pkg = SpreadsheetMLPackage.createPackage();
// Create worksheet
WorksheetPart sheet = pkg.createWorksheetPart(new PartName("/xl/worksheets/sheet1.xml"),"Sheet1", 1);
SheetData sheetData = sheet.getContents().getSheetData();
// Add Data
Row row = Context.getsmlObjectFactory().createRow();
Cell cell = Context.getsmlObjectFactory().createCell();
cell.setV("1234");
row.getC().add(cell);
CTXstringWhitespace ctx = Context.getsmlObjectFactory().createCTXstringWhitespace();
ctx.setValue("Open Source Java Library for Spreadsheet Documents");
CTRst ctrst = new CTRst();
ctrst.setT(ctx);
cell.setT(STCellType.INLINE_STR);
cell.setIs(ctrst);
row.getC().add(cell);
sheetData.getRow().add(row);
// Save
pkg.save(new File("FileFormat.xlsx"));        
         </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}