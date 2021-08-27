---
title: Read Office Excel XLSX Spreadsheets via Go API
description: Go-Excel Open source Go API allows reading Office Excel XLSX spreadsheet. 
keywords: Free Go Excel, Free Excel library,  alternative to MS Excle, Go XLSX API, Go XLSX library,  Go Excel API, Go Excel Library, Go XLSM, Go XLTM API, Go Spreadsheets API, create spreadsheet, add comments to cells,  Read XLSX files, manage Rows or Cells, add Comments to Excel
draft: false
weight: 35



ProductName: Go-Excel
Githublink: https://github.com/szyhf/go-excel
ListingPage_Short_Description: An open source lightweight Go library for reading Microsoft Excel Spreadsheets.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read XLSX documents via Open Source Go API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Reading Excel XLSX Files"
Header_H2_Text="Read XLSX documents via Open Source Go API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Go-Excel is an an open source lightweight pure go library for reading Microsoft Excel documents. The API amis to proivide simple and easy way to read XLSX files as relate-db-like table. While reading an XLSX file, the API expects the first row as title row and rows as data rows.</p>
<p>The API provides set of tags to manipuplat Excel documents. The column tag maps to the feild name in the title row, default tag sets default value when no value is defined, split tag splits a string and convert them to slice, nil tag skips scan value in the cell and req tag returns error if the column title doesnot exist in Excel.</p>

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
<p>An overview of go-excel features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read spreadsheet</li>
<li>Read titles</li>
<li>Skip empty rows</li>
<li>Map Colun</li>
<li>Split String</li>
<li>Slice</li>
<li>Read Map</li>
<li>Read Struct</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Go-Excel</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Go-Excel supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>unioffice</header><footer><small></small></footer></div>
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
<div class="d1-logo" style="border: none;"><header>Go-Excel</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Go-Excel</h2>
<p>The recommended way to install Go-Excel into your project is by using <a href="https://github.com/szyhf/go-excel">GitHub</a>. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install go-excel via GitHub</h3>
<pre><code class="html">go get github.com/szyhf/go-excel </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read Excel File via Free Go API</h2>
<p>The open source library Go-Excel allows computer programmers to read Excel files via GO. While reading excel file, you can use field name as default column name and you can map a column into more than one feild. Afte setting the reading options you open a new connection with Excel file using excel.NewConnector() method and successfull, connecting to a the excel file you can read its content using conn.NewReader() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Advance methods to Read Excel via GO API</h2>
<p>The open souurce API Go-Excel provides basic as well as advance methods to read excel files. You can use th index row as title, every row before the tittle row will be ignored and default title row is set to 0. You can skip the empty rows, skip column larger than the title. The API allows setting empty cells with default values and you can set default values by using unmarshal via encoding.BinaryUnmarshaler</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}