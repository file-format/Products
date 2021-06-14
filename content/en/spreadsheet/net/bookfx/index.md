---
title: BookFx – Compose Excel Spreadsheets Like HTML DOM
description: BookFx - Open Source Fast .NET Library for XLSX Spreadsheets. Generate, Edit, manage Rows or Cells and add Comments to Excel files in a fast way via C# API.
keywords: Free .NET Excel, Free Excel library,  alternative to MS Excle, .NET XLSX API, .NET XLSX library,  C# Excel API, .NET Excel Library, C# Spreadsheets API, create spreadsheet, add comments to cells,  Read XLSX files, manage Rows or Cells, add Comments to Excel, 
draft: false
weight: 8



ProductName: BookFx
Githublink: https://github.com/bookfx/bookfx
ListingPage_Short_Description: Compose Excel Spreadsheets like HTML DOM elements
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Compose Excel spreadsheets based on a tree of nested components like the HTML DOM"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET Library for Composing Excel Spreadsheets"
Header_H2_Text="Compose Excel spreadsheets based on a tree of nested components like the HTML DOM" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>BookFx is an open source C# API for creating Microsoft Excel Worksheets using components like HTML DOM elements. The API uses tree of nodes, which renders to a XLSX file. This method allows nodes to be implemented as a resulable components. Furthermore, hierarchy of nodes is convenient for applying styles. BookFx helps you define the structure of the workbook in a better way and takes the pain out of the calculating sizes and addresses of ranges.</p>
<p>Every sheet in the workbook can contatin one root box at upper left corner, other boxes are strecthed to fit in the composite boxes. Boxes are placed in the form of RowBox, ColBox and StackBox.</p>

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
<p>An overview of BookFx features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create Excel</li>
<li>Add Rows</li>
<li>Add Columns</li>
<li>Add Boxes</li>
<li>Implicit Conversions</li>
<li>Composition</li>
<li>Styling</li>
<li>Spanning and Merging</li>
</ul>
</div>
<!--/left--></div>
<div class="d1-logo" style="border: none;"><header>BookFx</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>BookFx supports popular formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header></div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>BookFx</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>BookFx requires .NET Standard 2.0 and EPPlus</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with BookFx</h2>
<p>The recommended way to install BookFx is from Nuget, Please use the following command for fasters installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install BookFx from NuGet</h3>
<pre><code class="html"> Install-Package BookFx</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create Excel Like HTML DOM - C#</h2>
<p>BookFx allows C# .NET developers to create new excel worksheets. You can create a blank workbook using Make.Book().ToBytes() method. Its an effective method for creating workbooks without any complexity. You can even insert text while creating the workbook by using Make.Value("Hi, World!").ToSheet().ToBook().ToBytes() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Span & Merge in Excel using C#</h2>
<p>The API also allows spanning and merging rows and columns in excel. It uses ValueBox methods SpanTows and SpanCols and their combination Span to define the number of spanned cells. The Merger method is used to merge cells, but BookFx merges ranges of a ValueBox automatically if the box has a value or a formula.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Using Values and Formulas in Excel using C#</h2>
<p>BookFx also allows using values and formulas in your excel worksheets. Using the ValueBox you can create values and formulas. It can be created using Make.Value method. To use the formula the value should beging with '=' operator like Make.Value("=SUM(RC[1]:RC[3])").</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}