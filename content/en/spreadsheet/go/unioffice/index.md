---
title: Generate, Edit & Manipulate Office Excel XLSX Spreadsheets via Go API
description: Unioffice - Open source Go API allows reading, writing & editing Office Excel XLSX spreadsheet. Add multiple charts, images & tables in a worksheets via PHP library.
keywords: Free Go Excel, Free Excel library,  alternative to MS Excle, Go XLSX API, Go XLSX library,  Go Excel API, Go Excel Library, Go XLSM, Go XLTM API, Go Spreadsheets API, create spreadsheet, add comments to cells,  Read XLSX files, manage Rows or Cells, add Comments to Excel
draft: false
weight: 34



ProductName: unioffice
Githublink: https://github.com/unidoc/unioffice
ListingPage_Short_Description: An open source Go library that provides fast ways for reading, writing, and manipulating Excel XLSX files inside their own applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read, Write, Edit Microsoft Excel XLSX documents via Open Source Go API. Add multiple charts, images, and tables inside your spreadsheets. "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Creating Excel XLSX Files"
Header_H2_Text="Read, Write, Edit Microsoft Excel XLSX documents via Open Source Go API. Add multiple charts, images, and tables inside your spreadsheets. " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Unioffice is an open source pure go library that gives software developers the capability to generate, modify, and manipulate Office Excel XLSX documents inside their own Go applications. The library is very stable and provides the highest degree of productivity with very little effort and cost.</p>
<p>The open source unioffice library fully supports several important features related to Excel spreadsheet creation and modifications, such as create new Excel sheet from the scratch, creating cells with various number/date/time formats, Excel Cell formatting, Cell validation support, Retrieve cell values as formatted by Excel, conditional formatting, Merge and unmerge cells, data validation including combo box dropdowns, Embedded Images and much more.</p>

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
<p>An overview of unioffice features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read spreadsheet</li>
<li>write spreadsheet</li>
<li>CSV support</li>
<li>HTML table</li>
<li>TSV Spreadsheet</li>
<li>Add sheet</li>
<li>XLSX Spreadsheet</li>
<li>XML Spreadsheet</li>
<li>HTML table to JSON</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>unioffice</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>unioffice supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>XLSX</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a>, XLSX</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>unioffice</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>unioffice only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>go1.8+</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>unioffice</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with unioffice</h2>
<p>The recommended way to unioffice into your project is by using <a href="https://github.com/unidoc/unioffice.git">GitHub</a>. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install unioffice via GitHub</h3>
<pre><code class="html">go get github.com/unidoc/unioffice/
go build -i github.com/unidoc/unioffice/...  </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Excel XLSX Creation via Go API</h2>
<p>The Open source library unioffice allows computer programmers to create an Excel XLSX spreadsheet inside their own Go applications. It gives you the capability to add new sheet to your existing Excel documents and assign name to a sheet and save the file to the path of your choice. It also provides support for several important features such as add new rows and columns to a sheet, define the number of rows and columns, set the default value of a cell,  and more.  You can also open and modify the existing spreadsheet with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Multiple Charts to an Excel XLSX File</h2>
<p>The unioffice library has provided support for adding charts to an Excel spreadsheet with just a couple of lines of code.  You can create charts based on the available data in your worksheet as well as without the availability of any data at all. Charts give you the capability to visually display data in different formats such as Bar, Column, Pie, Line, Area or Radar, etc. Developers can easily select from the available chart options and can control its values.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Insert Images to XLSX Spreadsheets</h2>
<p>The unioffice library fully supports the inclusion of images into XLSX Spreadsheets with just a couple of lines of Go code. It supports modifying images as well as deleting existing images inside an XLSX worksheet. It also provides options to insert a picture and set its properties like size, position, etc. as well as with printing support.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Apply Conditional Formatting on Spreadsheet’s Cells</h2>
<p>Conditional Formatting is a useful feature that helps Excel users to apply a format to a cell or a range of cells based on certain criteria. The unioffice library has provided functionality that enables software developers to apply conditional formatting to their spreadsheet with just a couple of Go commands. The library has included support for conditionally formatting cells, styling, gradients, icons, data bar & more to come.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}