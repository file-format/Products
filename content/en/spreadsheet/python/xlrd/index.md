---
title: Open Source Python API for Google Sheets - Create & Share Spreadsheet
description: Xlwings– An open source Free Python API for managing Google Sheets. Developers can create, modify, share and parse Excel XML Spreadsheets via Python library.
keywords: Free python API, Python excel, python Google Sheets, alternative to MS Excel, python XML library, python Share Excel XML file, python Excel API, python Spreadsheets API, Read XML file, parse Excel XML Spreadsheets, merging Excel XML spreadsheets, read excel XML files, generate Excel files

draft: false
weight: 29



ProductName: Xlrd
Githublink: https://github.com/python-excel/xlrd
ListingPage_Short_Description: Python library for reading and formatting XLS & XLSX file format.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Python library for reading and formatting XLS & XLSX file format."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Python API for Spreadsheets"
Header_H2_Text="Python library for reading and formatting XLS & XLSX file format." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Xlrd is an open source python API for reading & formatting Microsoft Excel (XLS, XLSX) file format. The API allows the Python developer to read Excel files, handle unicodes in it, manage dates, format cells & columns, use constant, foumulas, macros and more. Furthermore, the API provides loading worksheets on demand functionality that allows developers to save memory by loading only the required sheets.</p>
<p>The devloper no more maintains the API, and corrupted & non-standard Excel file will not work with this API. The API will ignore VBA modules, comments, hyperlinks, autofilters, advance filters and few other excel features as well.</p>

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
<p>An overview of Xlrd features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Read Excel</li>
<li>Handle Unicodes</li>
<li>Named References</li>
<li>Hanlde Constants</li>
<li>Read forumulas</li>
<li>On-Deman Worksheets</li>
<li>Format Rows</li>
<li>Manage Macros</li>
<li>Handle Dates</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Xlrd</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Xlrd supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlrd</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Xlrd requires Python 2.7 or 3.4+.</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlrd</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Xlrd</h2>
<p>You need to have Python 2.7 or 3.4+ or higher installed on your system to run Xlrd smoothly. The recommended way to install via PIP. Please use the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pip install xlrd</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read Excel Worksheets via Free Python API</h2>
<p>Xlrd API allows reading Microsoft Excel XLS & XLSX file using Python. The developers can easily open exisiting workbook using xlrd.open_workbook() method. You can get worksheets and sheet names of your excel file using workbook.nsheets & workbook.sheet_names properties respectively. In order to read rows & columns you can select a sheet by using workbook.sheet_by_index() method and use worksheet.nrows & worksheet.ncols respectively.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Load Worksheets on Demand using Python</h2>
<p>The Open Source spreadsheet library Xlrd allows software developers to load worksheets on demand. The functionality reduces memory usage and loads only required worksheets. You can use on-demand load functionality by using on_demang argument.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Formatting Informatin in Excel using Python</h2>
<p>Xlrd library gives developers the capability to read, display & render excel spreadsheet contents on a screen or to another file without losing the ability to display/render it. Defualt formatting is appllied to all empty cells. The API firstly will use Rowinfo & Colinfo class to get the properties. If Rowinfo & Colinfor class properties are not available the API will use the default properties.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}