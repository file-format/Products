---
title: Open Source Java Spreadsheet Library for XLSX Files | Documents4J
description: Documents4J - Open Source Free Java Excel Spreadsheet Library. Read, write, edit & convert Microsoft Excel Spreadsheets via Java API.
keywords: Java Excel APIs, Java .xlsx, Java .xlsx API, Java .xlsx library, Java Excel library, create Excel spreadsheet, convert XLSX to CSV, add sheet to workbook, convert XLSX to HTML, add cells to sheet, Java Excel programming, modify Excel files, add chart to Excel files, Open Source Excel Library, Free Java Excel APIs, Open Source Java API for Excel, Open Source Spreadsheet APIs, Free, Open Source Excel Library,
draft: false
weight: 23



ProductName: Documents4J
Githublink: https://github.com/documents4j/documents4j
ListingPage_Short_Description: Open Source Java Library for Converting Microsoft Excel File Format.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert Excel files in Java applications via Open Source API."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Java Library for Spreadsheet Documents"
Header_H2_Text="Convert Excel files in Java applications via Open Source API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Documents4J is an open-source Java API from converting Microsoft Excel to other fileformats. This is achieved by delegating the conversion to any native application which understands the conversion of the given file into the desired target format. The API offers two types of implementations local and remote. Using the local version document can be converted on the same machine which is cable of converting the requested file format. Using the Remote API, you send a document to the server using REST-API and server performs the requested conversion. </p>
<p>Documents4J is tranparent and simple to use. Developers can work with local version of the API while development and the remote version can used when the developers publishes app on the production.</p>

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
<p>An overview of Documents4J features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Convert Excel</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Documents4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Documents4J supports the following formats.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Documents4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Documents4J only requires Java runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Documents4J</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Documents4J</h2>
<p>First of all, you need to create a copy of documents4j on your local machine. Simply clone documents4j's repository by using git or by cloning it directly on GitHub. Once the repository is cloned, you can build the project using Mave</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Documents4J</h3>
<pre><code class="html">
git clone https://github.com/documents4j/documents4j.git
cd documents4j
mvn package
      </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert Microsoft Excel using Java</h2>
<p>Documents4J is a fluent API for performing document conversion. The API does not expose any details of the backing converter implementation. To perform document conversion the API offers IConverter interface. Using this inteface you can convert Microsoft Excel file format to your desired file format. To find out supported converison fileformats you can query getSupportedConversion() method which will return the source and the target file formats.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}