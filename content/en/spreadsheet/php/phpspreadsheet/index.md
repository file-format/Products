---
title: Open Source PHP Spreadsheet API - Create & Apply Excel AutoFilters
description: PHP-Spreadsheet - An Open Source Free PHP API for Excel XLS & XLSX Spreadsheets. Create & apply AutoFilters & use Formula Calculation Engine via Java Library.
keywords: Free APIs, Free PHP API, Open Source PHP API, PHP Excel, PHP Spreadsheet, Open Source Excel APIs, Open Source PHP APIs, Free XLSX API, Free XLS API, Create XLSX Free, Convert XLSX Free, Create XLS using PHP, Convert XLSX using PHP, PHP Excel programming, PHP Excel APIs, PHP .xls, PHP .xlsx, PHP .xlsx API, PHP .xls library, PHP Excel library, create Excel Spreadsheet, add sheet to workbook, add cells to sheet, modify Excel documents, add chart to Excel files
draft: false
weight: 1



ProductName: PHPSpreadsheet
Githublink: https://github.com/PHPOffice/PhpSpreadsheet
ListingPage_Short_Description: Open Source PHP API that allows developers to read, write and process files in Microsoft Excel & OpenOffice Calc file formats.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHPSpreadsheet"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP Library for Spreadsheet Files"
Header_H2_Text="Read, Write, Manipulate and Process Microsoft Excel & LibreOffice Calc files." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>PHPSpreadsheet is an open-source library that includes a set of classes to allow you to interact with and utilize various spreadsheet file formats of Microsoft Excel and LibreOffice Calc. PHPSpreadsheet supports spreadsheets which contain one or more worksheets, containing cells to hold data of various types, such as, numbers, formula, image, etc.</p>

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
<p>An overview of PHPSpreadsheet features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-file-excel-o"> </i>Overview</header>
<ul>
<li>Cells</li>
<li>Spreadsheets</li>
<li>Worksheets</li>
<li>Auto-filters</li>
<li>Formula Calculation Engine</li>
<li>Memory saving</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPSpreadsheet"><header>PHPSpreadsheet</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>PHPSpreadsheet supports popular Microsoft Excel & LibreOffice Calc file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader/Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/ods/">ODS</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, 
<a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>, 
<a href="https://docs.fileformat.com/web/html/">HTML</a>, 
<a href="https://docs.fileformat.com/spreadsheet/csv/">CSV</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://docs.fileformat.com/web/xml/">XML</a>, Gnumeric, SYLK</li>
</ul>
<header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPSpreadsheet"><header>PHPSpreadsheet</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>PHPSpreadsheet is installed via <a href="https://getcomposer.org/">Composer</a>. Use composer to install PhpSpreadsheet into your project.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i>PHP</header>
<ul>
<li>PHP version 7.1 or newer</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHPSpreadsheet"><header>PHPSpreadsheet</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PHPSpreadsheet</h2>
<p>First of all you need to have PHP version 7.1 or newer to develop using PhpSpreadsheet. The recommend way to install PhpSpreadsheet into your project is by using <a href="https://getcomposer.org">composer</a>. Open the terminal in your project root directory and run the command:</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the command</h3>
<pre><code class="html"> composer require phpoffice/phpspreadsheet </code></pre>


<p>Composer offers a convenient installer that you can execute directly from the command line. Feel free to download this file or review it on <a href="https://github.com/composer/getcomposer.org/blob/master/web/installer">GitHub.</a> There are two ways to install Composer. Install it locally as part of your project, or globally as a system wide executable.</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Work with Spreadsheet Cells</h2>
<p>PHPSpreadsheet allows you to access cell and set its value by coordinates. You can also create a new cell and set up a formula in it. You can also configure the cell to occupy various types of data, such as date, time, and number with leading zeros. PHPSpreadsheet also allows you to set a range of cells from an array, as well as looping through cells using iterators or indexes. You can also use value binders for allowing user-friendly data entry.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create a new XLSX - PHP</h3>
<pre><code class="PHP">&lt;?php

require 'vendor/autoload.php';

use PhpOffice\PhpSpreadsheet\Spreadsheet;
use PhpOffice\PhpSpreadsheet\Writer\Xlsx;
// Create a new Spreasheet
$spreadsheet = new Spreadsheet();
// Get active sheet
$sheet = $spreadsheet-&gt;getActiveSheet();
// Set cell value
$sheet-&gt;setCellValue('A1', 'File Format Developer Guide !');
// Save in Xlsx format
$writer = new Xlsx($spreadsheet);
$writer-&gt;save('FileFormat.xlsx');
</code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create & Apply AutoFilters</h2>
<p>Using PHPSpreadsheet, you can apply auto-filter ranges to filter out and display only those rows which match the criteria that you have defined in the auto-filter. You can apply filters to more than one column as additives.</p>
<p>PHPSpreadsheet allows you to set an auto-filter area on a worksheet. You can create, read and write auto-filter expressions. Furthermore, various types of filters are available, such as simple filters, matching blanks, DateGroup filters, custom filters, dynamic filters, and top ten filters.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Apply Auto Filter in XLSX - PHP</h3>
<pre><code class="PHP">&lt;?php
require 'vendor/autoload.php';

use PhpOffice\PhpSpreadsheet\Spreadsheet;
use PhpOffice\PhpSpreadsheet\Writer\Xlsx;
// Load existing file without filters 
$spreadsheet = \PhpOffice\PhpSpreadsheet\IOFactory::load('WithourFilter.xlsx');
// Select active worksheet
$spreadsheet-&gt;setActiveSheetIndex(0);
$spreadsheet-&gt;getActiveSheet()-&gt;setAutoFilter($spreadsheet-&gt;getActiveSheet()-&gt;calculateWorksheetDimension());

// Set active filters
$autoFilter = $spreadsheet-&gt;getActiveSheet()-&gt;getAutoFilter();
// Filter the Country column on a filter value of Germany
$autoFilter-&gt;getColumn('C')
 -&gt;setFilterType(Column::AUTOFILTER_FILTERTYPE_FILTER)
 -&gt;createRule()
 -&gt;setRule(
  Rule::AUTOFILTER_COLUMN_RULE_EQUAL,
  'Germany'
 );
// Save file
$writer = new Xlsx($spreadsheet);
$writer-&gt;save('Filter.xlsx');
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Formula Calculation Engine</h2>
<p>To perform from basic to advanced level calculations in your business spreadsheets, you can easily evoke PHPSpreadsheet’s formula calculation engine, and it will take care of the rest.</p>
<p>PHPSpreadsheet’s formula parser can automatically adjust a formula while rows/columns are being inserted/removed. Microsoft Excel formula is converted into PHP code before being executed. To boost performance, calculation cache is used to hold the result of the formula. Similarly, each individual worksheet is maintained by a separate cache.</p>



{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}