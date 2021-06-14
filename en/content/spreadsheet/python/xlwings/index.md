---
title: Open Source Python API for Google Sheets - Create & Share Spreadsheet
description: Xlwings– An open source Free Python API for managing Google Sheets. Developers can create, modify, share and parse Excel XML Spreadsheets via Python library.
keywords: Free python API, Python excel, python Google Sheets, alternative to MS Excel, python XML library, python Share Excel XML file, python Excel API, python Spreadsheets API, Read XML file, parse Excel XML Spreadsheets, merging Excel XML spreadsheets, read excel XML files,  generate Excel files

draft: false
weight: 27



ProductName: Xlwings
Githublink: https://github.com/xlwings/xlwings
ListingPage_Short_Description: Open Source API that makes it easy to call Python from Excel and vice versa.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Python library that makes it easy to call Python from Excel and vice versa."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Python API for Google Sheets"
Header_H2_Text="Python library that makes it easy to call Python from Excel and vice versa." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Xlwings is an open source python API for manipulating Excel file format. Using the API you can automate excel from pyton to produce reports, write UDFs(user defined funcitons), write macros, and control Excel remotely. Furthermore, the API allows manipulating data structures like cells, lists, range, NumPy arrays, panda data frames, and panda series.  </p>
<p>Xlwings requires installtion of Microsoft Excel, so everything works on Windows and macOS except that the UDFs only work on Windows.</p>

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
<p>An overview of Xlwings features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Python to Excel</li>
<li>Excel to Python</li>
<li>User Defined Function (UFDs)</li>
<li>Manage Cells</li>
<li>Range Expanding</li>
<li>NumPy Arrays</li>
<li>Pandas DataFrames</li>
<li>Pandas Series</li>
<li>Matplotlib Charts</li>
<li>Plotly Charts</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Xlwings</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Xlwings supports popular Excel spreadsheet file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li> <a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a>  <a href="https://wiki.fileformat.com/spreadsheet/xlsm/">XLSM</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a>  <a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSM</a> </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlwings</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Xlwings requires Python 3.5+ and Microsoft Excel.</p>
<div class="diagram1 d1-poi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Xlwings</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Xlwings</h2>
<p>You need to have Python 3.5 or higher installed on your system to run xlwings smoothly. The recommended way to install via PIP. Please use the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pip install xlwings</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Interact with Excel from Python</h2>
<p>Xlwings API allows manipulating Microsoft Spreadsheets using Python. Using the API you can connect to an exisitng workbook or create a new one using xlwings.Book() method. You can read/write values to & from ranges, expand ranges, convert datatypes easily. Furthermore, you can add Matplotlib & Plotly chart as pictures in your Excel Workbooks.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Call Python from Excel</h2>
<p>The Open Source spreadsheet library Xlwings allows software developers to communicated with Python via Excel. You can call python funcitons inside your excel either by using Run button of Xlwings Excel Add-In or by using the RunPython VBA funciton. The good thing about using Excel Add-In is that you dont need your workbooks to be macro-enabled, and you can save it as xlsx.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">User Defined Functions (UDFs) in Excel using Python</h2>
<p>Xlwings library gives developers the capability to write User Defined Funcitons (UDFs) inside Microsoft Excel fileformat programatically. Currently, UDFs are only available on windows. The API allows using simple funcitons, number of array dimensions, dynamic array formulas, arrya formulas with NumPy and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}