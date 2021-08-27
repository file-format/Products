---
title: Open Source C++ Library for Spreadsheets – Read & Write Excel Files
description: OpenXLSX – Open Source Free C++ Library for Excel files.  Create, Modify & Convert Spreadsheets, protect workbook or worksheet, set column widths via C++ API.
keywords: Free Spreadsheets API, Free Excel API, read excel files, C++ excel, alternative to MS Excel, cplusplus Excel library, cplusplus spreadsheet, MS Excel library, parse excel files,   C++ Excel API, Free Excel Library, C++ Spreadsheets API, protect Excel worksheets, unprotect Excel worksheets, set column widths

draft: false
weight: 15



ProductName: OpenXLSX
Githublink: https://github.com/troldal/OpenXLSX
ListingPage_Short_Description: C++ implementation gives software developers the power to read, write, create and modify Excel files as well as data formatting with lesser dependencies.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read, Write, Edit and Convert Microsoft<sup>®</sup> Excel Spreadsheet files via Open Source C++ API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source C++ Library for Excel Spreadsheet "
Header_H2_Text="Read, Write, Edit and Convert Microsoft<sup>®</sup> Excel Spreadsheet files via Open Source C++ API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is OpenXLSX?</h2>
<p>OpenXLSX is an open-source C++ library that gives computer programmers the power to read, write, create and modify Excel files as well as data formatting with lesser dependencies. It is a work in progress and aims to provide all the important features for spreadsheet creation and manipulation.</p>
<p>OpenXLSX provides support for several important features, such as Create, open and save spreadsheet files, read or write & modify cell contents, Copy cells and cell ranges, Copy worksheets & many more. OpenXLSX can be built and run on several platforms such as Windows, Linux & Linux.</p>

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
<p>An overview of OpenXLSX features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create spreadsheets</li>
<li>Open spreadsheets</li>
<li>save spreadsheets</li>
<li>clone worksheet</li>
<li>Column Widths</li>
<li>Copy worksheets</li>
<li>Set Header/footer</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Add filters</li>
<li>Add styles</li>
<li>Read cells</li>
<li>Copy Cells</li>
<li>Cell ranges</li>
<li>Merge cells</li>
<li>Add rows</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>OpenXLSX</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>OpenXLSX supports the following formats.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>XLS, XLSX</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>OpenXLSX</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>OpenXLSX only requires C++ runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>C++</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>OpenXLSX</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with OpenXLSX</h2>
<p>The current stable version is available on CRAN. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install OpenXLSX via CRAN</h3>
<pre><code class="html"> install.packages("openxlsx", dependencies = TRUE) </code></pre>
<h3>Development version</h3>
<pre><code class="html">install.packages("openxlsx", dependencies = TRUE) 
    require(devtools)
    install_github("ycphs/openxlsx")
    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">C++ API to Create & Modify Spreadsheet Files</h2>
<p>The open-source API OpenXLSX enables programmers to generate an excel spreadsheet from scratch. It also provides support for modifying the existing spreadsheet with ease. To modify an existing file you need to open it and insert the data you want to include in the files. You can create a new worksheet and add it to the empty workbook, add data to it and much more. You can also assign a name to the sheet and can also add content to it. By using the following steps, you can create a Microsoft Excel document in C++</p>
<h3>Create Excel Document in C++</h3>
<ol>
<li>Initialize XLDocument object</li>
<li>Create document</li>
<li>Add worksheet in document</li>
<li>Add text in cell</li>
<li>Save document</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create Excel Easily - C++</h3>
<pre><code class="c#">// initialize XLDocument
XLDocument doc;
// create document
doc.create("./Demo01.xlsx");
// add worksheet
auto wks = doc.workbook().worksheet("Sheet1");
// add text
wks.cell(XLCellReference("A1")).value() = "  Hello OpenXLSX!  ";
// save document
doc.save();
                                    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Protect Workbook or Worksheet</h2>
<p>Evert organizations work hard to collect their required data and don’t want anyone to play with their data.  OpenXLSX provides developers with the functionality to preventing people from editing various parts of a <em>workbook</em>. You can protect it by providing a password to limit who can even open it. It is always useful to protect a certain part of a workbook and let the users make changes to other parts when required.</p>
<h2 class="h2title">Manage Worksheet Column Widths</h2>
<p>The Open-source API OpenXLSX enables software programmers to set worksheet column widths to a specific width or "auto" for automatic width sizing. We can use <em>widths = “auto” </em>in the <em>setColWidths</em> function to auto-widen the column based on the data. You can also use merge cells<em> </em>to create a header for the data frame’s column headers. It also provides features for hiding the columns.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}