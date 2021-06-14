---
title: Open Source Ruby Spreadsheet Library - Generate & Edit Excel Files
description:   Spreadsheet - Open Source Ruby Excel Spreadsheet Library to generate, edit and read Excel files. Add, group, hide or unhide rows and columns via Ruby code
keywords: Ruby Excel, Ruby Spreadsheet,  Ruby Excel programming, Ruby Excel APIs, Ruby .xls, Ruby .xlsx, Ruby .xlsx API, Ruby .xls library, Ruby Excel library, create  Excel Spreadsheet, add sheet to workbook, add cells to sheet, modify Excel documents, add chart to Excel files, Open Source Excel Library, Ruby .xlsx file format, Open Source Excel Library
draft: false
weight: 1



ProductName: Spreadsheet
Githublink: https://github.com/zdavatz/spreadsheet
ListingPage_Short_Description: Create, modify and manipulate Microsoft Excel compatible spreadsheets using Ruby API.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Ruby API to work with Microsoft Excel compatible spreadsheets. It allows to create a new spreadsheet, modify existing documents, group or ungroup Excel spreadsheet cells & more."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Ruby Library to Process Excel Spreadsheet  "
Header_H2_Text="Ruby API to work with Microsoft Excel compatible spreadsheets. It allows to create a new spreadsheet, modify existing documents, group or ungroup Excel spreadsheet cells & more." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The Ruby Spreadsheet Library helps software developers to work with Microsoft Excel compatible spreadsheets inside their own Ruby applications. The library is very stable and is available under the GPL-3.0 License for the general public. The library is very user-friendly as well as very secure. It has included support for various encoding features. By default, UTF-8 is used for spreadsheet encoding.</p>
<p>There are several important features supported by the library related to Excel spreadsheet creation as well as manipulation such as create new spreadsheets from the scratch, read existing Excel files, modify the existing spreadsheet, use page settings, add new rows and columns,  hide existing rows or columns, grouping rows and columns,  printing setting support, spreadsheet encoding support, backward compatibility and many more. Moreover, the library has significantly improved memory-efficiency while reading large Excel Files.</p>

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
<p>An overview of Spreadsheet features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read spreadsheet</li>
<li>Grouping support</li>
<li>Memory-efficiency</li>
<li>Modify Existing File</li>
<li>Formula support</li>
<li>Add new sheet</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Spreadsheets Creation</li>
<li>Style support</li>
<li>String Encodings</li>
<li>Outline support</li>
<li>Hide rows/columns</li>
<li>Unhide rows/columns</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Spreadsheet</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Spreadsheet supports the following formats.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a>,  <a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Spreadsheet</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>The spreadsheet library only requires Ruby runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Ruby</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Spreadsheet</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Spreadsheet</h2>
<p>The recommended way to install Spreadsheet into your project is by using RubyGems. Please use the following command for smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install xlsx-populate via npm</h3>
<pre><code class="html">udo gem install spreadsheet </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<p>You can <a href="https://github.com/zdavatz/spreadsheet/archive/master.zip">download</a> the compiled shared library from GitHub repository and install it.</p>
<h2 class="h2title">Generate New Excel Spreadsheet using Ruby</h2>
<p>The open source library Ruby Spreadsheet has provided complete support for generating Microsoft Excel compatible spreadsheets using Ruby code. You can easily create a new workbook and add sheets to it with just a couple of lines of Ruby code. Once created you can insert contents to it and apply formatting to it. You can also insert new rows or columns, insert text or images, and so on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read & Edit Existing Spreadsheet via Ruby</h2>
<p>The Ruby Spreadsheet library enables software programmers to access and open an existing spreadsheet inside their own application. The library provides only write support for BIFF8 (Excel97 and higher versions). You can also modify your existing spreadsheet documents with just a couple of lines of code. The library has provided limited support.  You can easily add, modify, or delete Excel cells as well as fill in Data to be evaluated by predefined Formulas.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Group or Hide Rows and Columns</h2>
<p>The open source Ruby Spreadsheet library allows computer programmers to group or ungroup Excel spreadsheet cells using Ruby commands.  The library also provided supports for creating a new spreadsheet file with an outline. You can also hide or unhide rows or columns of your choice with ease. While reading a spreadsheet file you can easily change the hidden and outline properties. Please remember that the outline_level must be below 8, which is due to the Excel data format.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}