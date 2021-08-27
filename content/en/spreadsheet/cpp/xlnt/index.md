---
title: Open Source C++ Library for XLSX Spreadsheet - Set Page Margins & Styles
description: Xlnt - Open Source Cross-Platform C++ library for XLSX Spreadsheets. Read, write, set page margins, apply Formatting & Style to Excel XLSX files via C++ API.
keywords: Free XLSX API, Free Spreadsheets API, Free Excel API, read excel files, C++ excel, alternative to MS Excel, cplusplus Excel library, cplusplus spreadsheet, MS Excel library, parse excel files,   C++ Excel API, Free Excel Library, C++ Spreadsheets API, set column widths, set page margins, apply Formatting, apply Style to Excel XLSX
draft: false
weight: 16



ProductName: Xlnt
Githublink: https://github.com/tfussell/xlnt
ListingPage_Short_Description: Provides software developers the capability to generate, read, modify and manipulate Excel XLSX files inside C++ applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Xlnt"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Cross-Platform C++ Library for Excel Spreadsheet "
Header_H2_Text="Open Source API allows to Read, Write, Modify & Export Microsoft Excel XLSX Spreadsheet Files via C++ API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Xlnt is a modern open source C++ library that provides features for manipulating XLSX spreadsheets files. It enables software developers to read and write spreadsheet files from/to XLSX files. On May 10th, 2017 the first public release of Xlnt version 1.0 was available for public use. The recent work mostly focuses on compatibility enhancements and better performance.</p>
<p>The Xlnt library offers functionality for many important features, such as creating Excel-style workbook and numbers-style workbook, encrypted Workbook creation, Excel Binary Workbook, document Properties, hyperlink support, Page Margins, Comments, Cell Styles and many more.</p>

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
<p>An overview of Xlnt features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Feature Overview</header>
<ul>
<li>Excel-style workbook</li>
<li>numbers-style workbook</li>
<li>encrypted Workbook</li>
<li>Page Margins</li>
<li>Add Comments</li>
<li>Cell Styles</li>
</ul>
<p><span style="font-size: 12.16px;">Feature Overview</span></p>
</div>
<div class="d1-col d1-right">
<ul>
<li>Excel Binary Workbook</li>
<li>Hyperlink support</li>
<li>Document Properties</li>
<li>Open spreadsheets</li>
<li>save spreadsheets</li>
<li>Read cells</li>
<li>Add rows</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Xlnt"><header>Xlnt</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Xlnt supports Excel spreadsheet format as well as it can export data to common file formats.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>XLSX</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a><a href="https://docs.fileformat.com/web/html/">, </a>XLSB</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Xlnt"><header>Xlnt</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Xlnt requires C++14 or higher</p>
<p>.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><!-- <header><i class="fa fa-cubes"> &nbsp;</i></header>
<ul>
<li>Python 2.6 & above</li>
</ul> --></div>
<!--/left--><!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Xlnt"><header>Xlnt</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Xlnt</h2>
<p>The following steps update the compiler and set the appropriate environment variables.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install PIP Command</h3>
<pre><code class="html">sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt update
sudo apt-get upgrade
sudo apt-get install gcc-6 g++-6
export CC=/usr/bin/gcc-6  
export CXX=/usr/bin/g++-6
</code></pre>

<p>First Download the zip files from the Xlnt repository at <a href="https://github.com/tfussell/xlnt/archive/master.zip">GitHub</a> and then apply the following commands.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">C++ API to Read from an Existing XLSX Spreadsheet</h2>
<p>The open source Xlnt library provides functionality for reading an existing XLSX spreadsheet inside C++ applications. It also allows developers to print the string values to the screen.  Moreover, once you read the contents it is also possible to export the contents into a file and store on the location of your choice. </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Apply Formatting & Style to Excel Spreadsheet</h2>
<p>The Xlnt library enables programmers to apply formatting and styles to their data inside an Excel spreadsheet. A format in Xlnt corresponds to the alignment, border, fill, font, number format, and protection settings applied to a cell. On the other hand, a style is a named style created in the "Cell styles" dropdown in Excel. It needs to have a name and optionally any of alignment, border, fill, font, number format, protection. A cell can have both a format and a style.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Setting Page Margins of a Worksheet</h2>
<p>The open source Xlnt enables programmers to apply page margins to an Excel worksheet page inside their own C++ applications.  Page margins specify how much blank area should be left around the information in an Excel worksheet. They provide a visual border for users printed pages and an area where the page can be held or bound.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"> </h2>
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}