---
title: Fast C# .NET Library for XLSX Spreadsheets – Read & Write Excel Files
description: FastExcel - Open Source Fast .NET Library for XLSX Spreadsheets. Generate, Edit, manage Rows or Cells and add Comments to Excel files in a fast way via C# API.
keywords: Free .NET Excel, Free Excel library,  alternative to MS Excle, .NET XLSX API, .NET XLSX library,  C# Excel API, .NET Excel Library, C# Spreadsheets API, create spreadsheet, add comments to cells,  Read XLSX files, manage Rows or Cells, add Comments to Excel, 
draft: false
weight: 4



ProductName: FastExcel
Githublink: https://github.com/mrjono1/FastExcel
ListingPage_Short_Description: A .NET library provides fast ways for reading, writing and manipulating Excel XLSX files inside their own applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Provides Fast Excel XLSX Spreadsheets Reading, Writing & Manipulation via Free .NET Library."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET Library for Microsoft<sup>®</sup> Excel Spreadsheets  "
Header_H2_Text="Provides Fast Excel XLSX Spreadsheets Reading, Writing & Manipulation via Free .NET Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is FastExcel?</h2>
<p>An Open source FastExcel C# .NET library provides functionality for speedy reading and writing of Excel XLSX spreadsheet. The good thing is that the API has small memory footprint while running. The Open XML SDK is not used at all for interacting with the data. It goes directly for editing the underlying xml files.</p>
<p>The main aim of the project is to provide a light weight fast way of interacting with data in Excel with basic functionality. A great effort has been made to make it faster. .NET developers can easily use several important features inside their own applications, such as reading and writing Excel files, cell ranges, manage tables, managing rows, insert texts, add images, add new sheets and many more. </p>

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
<p>An overview of FastExcel features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Read XLSX</li>
<li>Write XLSX</li>
<li>Add images</li>
<li>Add comments</li>
<li>Cell ranges</li>
<li>Add rows</li>
<li>Manage tables</li>
<li>Excel encryption</li>
<li>Formula calculation</li>
</ul>
</div>
<!--/left--></div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>FastExcel</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>FastExcel supports popular Spreadsheet file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/spreadsheet/xls/">TXT</a>, <a href="https://wiki.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://wiki.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>FastExcel</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>FastExcel only requires .NET Framework 4.5 or higher and .NET Core 2.0.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with FastExcel</h2>
<p>The recommended way to install FastExcel  is from Nuget, Please use the following command for fasters installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install FastExcel  from NuGet</h3>
<pre><code class="html"> Install-Package FastExcel -Version 3.0.6</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate Spreadsheet Files via .NET API</h2>
<p>FastExcel gives C# .NET programmers the competency to generate an Excel spreadsheet inside their own .NET applications. You can easily define how many rows and columns you want keep inside the sheet. It also requires to assign name to a sheet. Developers can set font type and text size for a created sheet. The following are the the steps to generate and insert data in excel fastly.</p>
<h3>Generate Excel Fastly</h3>
<ol>
<li>Initialize object of FastExcel</li>
<li>Create worksheet</li>
<li>Populate row data</li>
<li>Write Excel</li>
</ol>
<br>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create Free Excel Fastly - C#</h3>
<pre><code class="c#">using (FastExcel.FastExcel fastExcel = new FastExcel.FastExcel(new FileInfo("Template.xlsx"), new FileInfo("Output.xlsx")))
{
    //Create a worksheet with some rows
    var worksheet = new Worksheet();
    var rows = new List();
    for (int rowNumber = 1; rowNumber &lt; 100000; rowNumber++)
    {
        List cells = new List();
        for (int columnNumber = 1; columnNumber &lt; 13; columnNumber++)
        {
            cells.Add(new Cell(columnNumber, columnNumber * DateTime.Now.Millisecond));
        }
        cells.Add(new Cell(13, "FileFormat" + rowNumber));
        cells.Add(new Cell(14, "FileFormat Developer Guide"));

        rows.Add(new Row(rowNumber, cells));
    }
    worksheet.Rows = rows;

    fastExcel.Write(worksheet, "sheet1");
}
                            </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Rows and Cell Management in Excel Worksheet</h2>
<p>The open source .NET API FastExcel support features for managing cells and rows inside Excel spreadsheets. It allows to developers to create new rows, merge a row to the next row, get all cells in this row, create a new cell, select a range of cells, select value from a cell, the worksheet that this cell is on and many more.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Read Excel Free - C#</h3>
<pre><code class="c#">// Create an instance of Fast Excel
using (FastExcel.FastExcel fastExcel = new FastExcel.FastExcel(new FileInfo("input.xlsx")))
{
    //Create a some rows in a worksheet
    var worksheet = new Worksheet();
    var rows = new List();

    for (int rowNumber = 1; rowNumber &lt; 100000; rowNumber += 50)
    {
        List cells = new List();
        for (int columnNumber = 1; columnNumber &lt; 13; columnNumber += 2)
        {
            cells.Add(new Cell(columnNumber, rowNumber));
        }
        cells.Add(new Cell(13, "File Format Developer Guide"));

        rows.Add(new Row(rowNumber, cells));
    }
    worksheet.Rows = rows;
    // Read the data
    fastExcel.Update(worksheet, "sheet1");
}
                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Comments Addition to Excel Cell</h2>
<p>FastExcel API facilitates .NET developers to add and modify comments to Excel Cell. It is very beneficial to insert comments for reminders & notes for others subject. The API supports features like adding a comment, moving comment box, display or hide comments, deleting a comment, comment formatting etc.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}