---
title: Go XLSX Library – Handle Worksheets, Rows/Columns, Styles in Excel File
description: Xlsx - Open source Go library enables programmers to create or modify Excel XLSX Spreadsheet, add new sheets, handle Rows & Columns in Worksheet via Go API.
keywords: Free Go Excel, Free Excel library, alternative to MS Excle, Go XLSX API, Go XLSX library, Go Excel API, Go Excel Library, Go XLSM, Go Spreadsheets API, create spreadsheet, add comments to cells, add new sheets, handle Rows, manage Columns in Worksheet, Read XLSX files, manage Rows or Cells, add Comments to Excel
draft: false
weight: 39



ProductName: xlsx
Githublink: https://github.com/plandem/xlsx
ListingPage_Short_Description: Go XLSX API that enables programmers to generate & manage Excel XLSX Spreadsheets, handle Rows & Columns in Worksheets, and much more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Go API that supports Microsoft Excel XLSX Spreadsheet generation, manage worksheets, handling Rows & Columns in Worksheets via Go API."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Go Library for Working with Excel XLSX Documents"
Header_H2_Text="Open Source Go API that supports Microsoft Excel XLSX Spreadsheet generation, manage worksheets, handling Rows & Columns in Worksheets via Go API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The xlsx library provides a fast and reliable way for working with Microsoft Excel files using Go. The library helps to simplify reading and writing Excel XLSX file format. XLSX file format was introduced in 2007 and uses the Open XML standard adapted by Microsoft back in 2000. The library is open source and available under the BSD-3-Clause license.</p>
<p>The open source xlsx library supports several important features related to Microsoft Excel Documents creation and manipulation such as creating a new XlSX file, opening existing Excel files, accessing your worksheets, adding new worksheets, Managing rows and columns inside a worksheet, adding cells, getting cell from a row, formatting cells, applying styles to cells, named ranges support and much more.</p>

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
<p>An overview of xlsx features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Create XLSX file</li>
<li>Modify XLSX file</li>
<li>Read XLSX</li>
<li>Add images</li>
<li>Add charts</li>
<li>Merge cells</li>
<li>Copy rows</li>
<li>Conditional formatting</li>
<li>Add comments</li>
<li>Cell ranges</li>
<li>Add rows</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>xlsx</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>xlsx supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>XLSX</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>,<a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>xlsx</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>xlsx only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Go 1.2+</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>xlsx</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Xlsx2Go</h2>
<p>The recommended way to install xlsx is from GitHub, Please use the following command for smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install xlsx via GitHub</h3>
<pre><code class="html">go get https://github.com/tealeg/xlsx.git</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Creating NEW XLSX Files via Go Library</h2>
<p>The Open source xlsx library gives software developers the capability to create a new empty XLSX file from scratch using a couple of Go commands. The developers can use the new NewFile() function to generate a new file. Once it is created you can easily add new content to the workbook. You can add a new sheet or appending an existing sheet with ease. Once created and the working is completed, please save your work, it is recommended Close()the sheet.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Access and Read XLSX Files</h2>
<p>The Open source xlsx library has provided a set of functions that allow developers to access open and read an existing XLSX spreadsheet file inside their own Go applications. You can also easily access sheets of a workbook with just a couple of Go commands. Developers can also access a particular sheet of their choice with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Handling Rows and Columns in Worksheets</h2>
<p>Cells are the backbone of an Excel Worksheet. A worksheet is made up of cells organized in rows and columns. The xlsx library gives software developers a wide range of features for handling rows and columns inside their apps using Go commands. It supports adding new rows and columns, iterating rows and columns, deleting unwanted rows and columns, add new cells to a row, getting value from a cell, apply formatting to a range of cells, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Apply Styles and Formatting</h2>
<p>The Free library xlsx library has provided several important functions that enable software developers to apply formatting and styles to their spreadsheets with ease. Styles provide layout and decoration of cells like font, color, content alignment, font size, fill, etc. You can easily apply the style to a range of cells with just a couple of lines of code. You just need to create a style once and reuse it when needed. You can also apply number and date formats for cells.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}