---
title: Open Source Python API for Excel Spreadsheets - Read & Create Spreadsheet
description: Openpyxl– An open source Free Python API for managing Google Sheets. Developers can create, modify, share and parse Excel XML Spreadsheets via Python library.
keywords: Free python API, Python excel, python Google Sheets, alternative to MS Excel, python XML library, python Share Excel XML file, python Excel API, python Spreadsheets API, Read XML file, parse Excel XML Spreadsheets, merging Excel XML spreadsheets, read excel XML files, generate Excel files

draft: false
weight: 28



ProductName: Openpyxl
Githublink: https://bitbucket.org/openpyxl/openpyxl/src/master/
ListingPage_Short_Description: Python library to Read & Write Excel 2010 xlsx/xlsm files
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Python library to Read & Write Excel 2010 xlsx/xlsm files."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Python API for Spreadsheets"
Header_H2_Text="Python library to Read & Write Excel 2010 xlsx/xlsm files." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Openpyxl is an open source python API for reading & writing Microsoft Excel 2010 (XLSX/XLSM/XLTX/XLTM) file formats. The API allows the Python developer to read existing Excel files, create a new workbook, use number formats, use formulas, merger & un-merge cells, insert images and fold columns. Furthermore, the API allows you to manipulate your workbook in memory and there in no need to create a file on the file system.</p>
<p>The API is rich with features for manipulating Microsoft Excel file format programmatically. You can add charts, add/load & save comments, work with styles, table and more.</p>

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
<p>An overview of Openpyxl features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Read Excel</li>
<li>Write Excel</li>
<li>Save to file</li>
<li>Load from file</li>
<li>Add Charts</li>
<li>Add Tables</li>
<li>Add/Load Comments</li>
<li>Validate Cells</li>
<li>Parse Formulas</li>
<li>Use Filters</li>
<li>Conditional Formatting</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Openpyxl</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Openpyxl supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsm/">XLSM</a>, <a href="https://docs.fileformat.com/spreadsheet/xltx/">XLTX</a>, <a href="https://docs.fileformat.com/spreadsheet/xltm/">XLTM</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsm/">XLSM</a>, <a href="https://docs.fileformat.com/spreadsheet/xltx/">XLTX</a>, <a href="https://docs.fileformat.com/spreadsheet/xltm/">XLTM</a> </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlrd</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Openpyxl supports Python 2.7, 3.4, 3.5, 3.6 and 3.7</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Openpyxl</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Openpyxl</h2>
<p>The recommended way to install openpyxl is via PIP. Please use the following command to install Openpyxl.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pip install openpyxl</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manipulating Excel Workbooks via Free Python API</h2>
<p>Openpyxl API allows reading & writing Microsoft Excel 2010 file formats using Python. The developers can easily open existing workbook using load_workbook() method and create a new workbook using workbook() method. You can use numbers formats, use formulas, merge & unmerged cells. insert images and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Charts is Excel using Free Python API</h2>
<p>The Open Source spreadsheet library Openpyxl allows adding wide range of charts in your excel files programmatically. You can add 2D Area Charts, 3D Area Charts, Vertical/Horizontal & Stacked Bar Charts, 3D Bar Charts, Bubble Charts, Line Charts, 3D Line Charts, Scatter Charts, Pie Charts, Projected Pie Charts, 3D Pie Charts, Doughnut Charts, Radar Charts, Stock Charts, and Surface Charts.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Style Excel Spreadsheets using Python</h2>
<p>Openpyxl library allows developers the capability to style Excel Spreadsheets programmatically. Using the API, you can set font, font size, color, underlining, set borders, align cells and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}