---
title: ExcelDataReader – Read XLS, XLSX & CSV Documents
description: FastExcel - Open Source Fast .NET Library for XLSX Spreadsheets. Generate, Edit, manage Rows or Cells and add Comments to Excel files in a fast way via C# API.
keywords: Free .NET Excel, Free Excel library,  alternative to MS Excle, .NET XLSX API, .NET XLSX library,  C# Excel API, .NET Excel Library, C# Spreadsheets API, create spreadsheet, add comments to cells,  Read XLSX files, manage Rows or Cells, add Comments to Excel, 
draft: false
weight: 6



ProductName: ExcelDataReader
Githublink: https://github.com/ExcelDataReader/ExcelDataReader
ListingPage_Short_Description: Open-Source API to read XLS, XLSX and CSV fileformat for Excel(2.0-2007) .
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="ExcelDataReader allows you read Microsoft Excel file formats using C#."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET Library for Reading Excel Spreadsheets  "
Header_H2_Text="ExcelDataReader allows you read Microsoft Excel file formats using C#." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>ExcelDataReader is an open source lightweight API written in C# for reading Microsoft Excel Files. Using the API you can read Microsoft XLS, XLSX, and CSV easily. The API supports older versions of XLS files back to Excel 2.0, supports text dates, cached formula values and empty sheet paths in XLSX.</p>
<p>Furthermore, the API supports fallback encoding in XLS and more flexible column name handling in Datasets. It is easy to configure and is available on NuGet.</p>

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
<p>An overview of ExcelDataReader features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Read Excel</li>
<li>Date Create on Mac</li>
<li>Text Dates</li>
<li>Cached Formula</li>
<li>Empty Sheets Path</li>
<li>Fallback Encoding</li>
<li>Column Handling</li>
<li>Password Protection</li>
<li>Timespan values</li>
</ul>
</div>
<!--/left--></div>
<div class="d1-logo" style="border: none;"><header>ExcenDataReader</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>ExcelDataReader supports popular formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://wiki.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://wiki.fileformat.com/spreadsheet/csv/">CSV</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>ExcelDataReader</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>ExcelDataReader is cross platform API and canbe used with Windows with .Net Framework 2, Windows Mobile with Compact Framework, Linux, OS X, and BSD with Mono 2+</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with ExcelDataReader</h2>
<p>The recommended way to install ExcelDataReader is from Nuget, Please use the following command for fasters installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install ExcelDataReader from NuGet</h3>
<pre><code class="html"> Install-Package ExcelDataReader -Version 3.6.0</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read Excel Files via .NET API</h2>
<p>ExcelDataReader allows C# .NET developers to read Microsoft Excel Files easily and efficiently. The AsDataSet() extension method is a convenient helper for quickly getting the data. IExcelDataReader extends the System.Data.IDataReader and IDataRecord interfaces to navigate and retrieve data at a lower level.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read Protected Workbooks</h2>
<p>The open source .NET API ExcelDataReader also allows you to read password protected Microsoft Excel documents.You can read password protected file using setting password in ExcelReaderConfiguration configuration and opening it using CreateOpenXmlReader() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}