---
title: Open Source Python API for Google Sheets - Create & Share Spreadsheet
description: Xlwt– An open source Free Python API for managing Google Sheets. Developers can create, modify, share and parse Excel XML Spreadsheets via Python library.
keywords: Free python API, Python excel, python Google Sheets, alternative to MS Excel, python XML library, python Share Excel XML file, python Excel API, python Spreadsheets API, Read XML file, parse Excel XML Spreadsheets, merging Excel XML spreadsheets, read excel XML files,  generate Excel files

draft: false
weight: 30



ProductName: Xlwt
Githublink: https://github.com/python-excel/xlwt
ListingPage_Short_Description: Python library for writing MS Excel 97/2000/XP/2003 XLS files.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Python library for writing MS Excel 97/2000/XP/2003 XLS files."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Python API for Google Sheets"
Header_H2_Text="Python library for writing MS Excel 97/2000/XP/2003 XLS files." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Xlwt is an open source python API for writing and formatting data in older(97/2000/XP/2003 XLS) Microsoft Excel file formats. Python developers can easily manipulating older Microsoft Excel files using this pure Python API with no dependencies on modules and packages outside the standard Python distrubution. The API provides rich writing and manipulating features including, merge cells, format rows, manipulate dates, use hyperlinks, insert images, use panes and more. </p>
<p>Xlwt is pretty easy and simple to use and the developers can install it using the pip package installer. Please note that, the API only supports XLS file format and XLSX file format is currently not supported.</p>

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
<p>An overview of Xlwt features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Write Excel</li>
<li>Format Dates</li>
<li>Format Cells</li>
<li>Use Formulas</li>
<li>Add Hyperlinks</li>
<li>Insert Images</li>
<li>Merge Cells</li>
<li>Use Panes</li>
<li>Style Rows</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Xlwt</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Xlwt supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header></div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>   </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlwt</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Xlwt requires Python 3.5+.</p>
<div class="diagram1 d1-poi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlwt</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Xlwt</h2>
<p>You need to have Python 3.5 or higher installed on your system to run Xlwt smoothly. The recommended way to install via PIP. Please use the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pip install xlwt</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create XLS using Free Python API</h2>
<p>Xlwt API allows creating Microsoft Excel XLS file using Python. In order to create a blank excel file you can create an instance using xlwt.Workbook() method. You can add sheets in it using Workbook.add_sheet() method. After you have your new workbook ready, you can add new rows & columns in it accordingly.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Sytle Excel Rows using Python</h2>
<p>The Open Source spreadsheet library Xlwt allows software developers to sytle excel rows programatically. You can simply style a row by using Workbook.row().set_style() method. The styling method allows you to set font, font height, color, and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Using Panes in XLS via Python</h2>
<p>Xlwt library gives developers the capability to freeze rows & columns in XLS fileformat using panes_frozen property. Using the panes properties provided by the API, you freeze specific rows and columns aswell.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}