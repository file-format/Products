---
title: .NET API for Excel Spreadsheets - Import and Export Data from PDF File Format
description: Magicodes.IE - Open source .NET API allows to Import and Export Data from PDF File Format
keywords: .NET Excel, alternative to MS Excle, .NET XLSX API, .NET ODS, .NET CSV,  C# Excel API, .NET Excel Library, C# Spreadsheets API, create spreadsheet, add comments to cells,  Read XLSX files, Add Image in Excel cell, read spreadsheet files, import PDF, export PDF
draft: false
weight: 1



ProductName: Magicodes.IE
Githublink: https://github.com/dotnetcore/Magicodes.IE
ListingPage_Short_Description: Open-Source API to Import and Export Data from Excel File Format.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open-Source API to Import and Export Data from Excel File Format"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text=".NET API for Microsoft<sup>®</sup> Excel Spreadsheets"
Header_H2_Text="Open-Source API to Import and Export Data from Excel File Format" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Magicodes.IE?</h2>
<p>Magicodes.IE is a pure .NET library that gives software developers the capability to import and export data from Microsoft Excel File Format. Using the API, you can import and export data as DTO, export general library, and export template, fancy & dynamic reports. The API does not allow manipulating XLS (Excel97-2003) file format and only supports XLSX and CSV file format.</p>
<p>One of the major features of the API is importing data as DTO. Magicodes.IE.Excel can automatically generate imported Excel templates, data validation, template validation, read settings, value constraints and mapping, and output Excel validation markup based on DTO and feature settings. Furthermore, the API supports various filters to support scenarios such as multi-language, dynamic control column display, and more.</p>

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
<p>An overview of Magicodes.IE features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Import Excel</li>
<li>Export Excel</li>
<li>DTO Support</li>
<li>Template Export</li>
<li>Fancy Export</li>
<li>Dynamic Export</li>
<li>Filters</li>
<li>Custom filtering</li>
<li>Skipping</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Magicodes.IE</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Magicodes.IE supports popular Spreadsheet file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/spreadsheet/csv/">CSV</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/spreadsheet/csv/">CSV</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Magicodes.IE</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Magicodes.IE can work with .NETFramework 4.6.1, .NETStandard 2.0, or .NETStandard 2.1.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Magicodes.IE</h2>
<p>The best way to install Magicodes.IE is via NuGet, please use the following command to install the API.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Magicodes.IE from NuGet</h3>
<pre><code class="html"> Install-Package Magicodes.IE.Excel</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Import Data in Excel via Free .NET API</h2>
<p>Magicodes.IE allows .NET programmers to import data in Microsoft Excel Spreadsheets programmatically. The API allows you to create DTO, generate import template and populate them with data. Using the API, you can easily call the import templates and import data in them. The following code snippet demonstrates, how to import data using an existing template. Please note that the code snippet is already using a predefined ImportStudentDto object.</p>
<h3>Free .NET API to Import Excel Data</h3>
<ol>
<li>Define a file path as a string</li>
<li>Import data to excel using a predefined ImportStudentDto and template. You can also define your own DTO as per your need</li>
<li>Check that the data is successfully imported and file it not null.</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Import data in Excel - C#</h3>
<pre><code class="c#">// set filepath
var filePath = ("filefoamt.xlsx");
// import data                                           
var result = await Importer.GenerateTemplate(filePath);
// check that if data is not null
result.ShouldNotBeNull();
// check if output file existsa
File.Exists(filePath).ShouldBeTrue();
                        </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}