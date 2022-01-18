---
title: .NET Library for Spreadsheets – Read, Write Excel XLS & XLSX Files
description: NOPI – An Open source Free .NET Library for Excel XLSX, XLS Spreadsheet. Read, Write and add images or comments to cells in Excel spreadsheet via C# API.
keywords: Free Excel API, Free .NET library, .NET Excel, alternative to MS Excle, .NET XLSX API, .NET ODS, .NET CSV, C# Excel API, .NET Excel Library, C# Spreadsheets API, create spreadsheet, add comments to cells, Read XLSX files, Add Image in Excel cell, read spreadsheet files
draft: false
weight: 3



ProductName: NPOI
Githublink: https://github.com/nissl-lab/npoi
ListingPage_Short_Description: NPOI allows developers to create & manipulate XLS & XLSX using .NET applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read, write, manipulate & convert XLS & XLSX files via open-source .NET library."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Free .NET Library for Excel<sup>®</sup> Spreadsheets"
Header_H2_Text="Read, write, manipulate & convert XLS & XLSX files via open-source .NET library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is NPOI?</h2>
<p>NPOI is a .NET version of POI Java project. It is an open source .NET library to read and write Microsoft Excel file formats. <strong>NPOI.HSSF</strong> namespace provides the ability to manipulate <a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a> file format, while <strong>NPOI.XSSF</strong> namespace allows you to create & modify <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a> files.</p>
<p>NPOI allows you to add text, insert hyperlinks, create & style cells & columns, insert images and read content from existing XLS & XLSX files without any external dependency.</p>

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
<p>An overview of NPOI features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create XLS, XLSX</li>
<li>Style Text</li>
<li>Add Paragraphs</li>
<li>Add Tables</li>
<li>Insert Images</li>
<li>Insert Charts</li>
<li>Merge Cells</li>
<li>Use Basic formulas</li>
<li>Convert XLS to HTML</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Open XML SDK</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>NPOI supports popular Spreadsheet file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xls/">XLS</a>, <a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Open XML SDK</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>NPOI supports .NET Standard 2.0 and .NET Framework 4.0 or above.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">How to Install NPOI?</h2>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install NPOI from NuGet</h3>
<pre><code class="html"> Install-Package NPOI -Version 2.4.1</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manipulate XLSX File via C#</h2>
<p>NPOI allows .NET programmers to create as well as modify spreadsheet from their own .NET applications. In order to modify an existing file, you can load the file and update text, tables, styles and more.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Edit XLSX with NPOI - C#</h3>
<pre><code class="c#">IWorkbook wb = new XSSFWorkbook();

// Create a Worksheet
ISheet ws = wb.CreateSheet("FileFormat");

ICellStyle style = wb.CreateCellStyle();

//Setting the line of the top border
style.BorderTop = BorderStyle.Thick;
style.TopBorderColor = 256;

style.BorderLeft = BorderStyle.Thick;
style.LeftBorderColor = 256;

style.BorderRight = BorderStyle.Thick;
style.RightBorderColor = 256;

style.BorderBottom = BorderStyle.Thick;
style.BottomBorderColor = 256;

IRow row = ws.CreateRow(0);
ICell cell = row.CreateCell(1);
cell.CellStyle = style;

FileStream sw = File.Create("fileformat.xlsx");
wb.Write(sw);
sw.Close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert XLS to XLSX with NPOI</h2>
<p>Follow the steps in order to save XLS file as XLSX after you opened and modified it using NPOI.</p>
<ol>
<li>Create new XSSFWorkbook</li>
<li>Create appropriate XSSFSheet for each worksheet of XLS</li>
<li>Copy data from XLS worksheet to XLSX worksheet</li>
<li>Copy formatting from XLS worksheet to XLSX worksheet</li>
<li>Save workbook in XLSX format</li>
</ol>
<br>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert XLS to XLSX with NPOI - C#</h3>
<pre><code class="c#">HSSFWorkbook retVal = new HSSFWorkbook();
for (int i = 0; i &lt; source.NumberOfSheets; i++)
{
	HSSFSheet hssfSheet = (HSSFSheet)retVal.CreateSheet(source.GetSheetAt(i).SheetName);

	XSSFSheet xssfsheet = (XSSFSheet)source.GetSheetAt(i);
	CopySheets(xssfsheet, hssfSheet, retVal);
}</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Image to XLSX via C#</h2>
<p>The API allows the developers to add images in spreadsheet documents. You can add a image and set image properties. The API allow various methods to manipulate in images in XLSX file format easily. IClientAnchor allows you set top, bottom, left and right positioning of image inside the worksheet.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create Table with XSSF NPOI - C#</h3>
<pre><code class="c#">IWorkbook wb = new XSSFWorkbook();
ISheet sheet1 = wb.CreateSheet("First Sheet");

// Add picture data to this workbook.
byte[] bytes = File.ReadAllBytes("fileformat.png");
int pictureIdx = wb.AddPicture(bytes, PictureType.PNG);

ICreationHelper helper = wb.GetCreationHelper();

// Create the drawing patriarch. This is the top level container for all shapes.
IDrawing drawing = sheet1.CreateDrawingPatriarch();

// add a picture shape
IClientAnchor anchor = helper.CreateClientAnchor();

// set top-left corner of the picture,
// subsequent call of Picture#resize() will operate relative to it
anchor.Col1 = 3;
anchor.Row1 = 2;
IPicture pict = drawing.CreatePicture(anchor, pictureIdx);
// auto-size picture relative to its top-left corner
pict.Resize();

FileStream sw = File.Create("image.xlsx");
wb.Write(sw);
sw.Close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}