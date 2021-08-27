---
title: .NET Library for Word Processing – Add Tables & Images in Documents
description: NPOI – An Open source Free.NET Library for Word Documents Processing. Add text & paragraphs, create tables in DOCX, parse table & insert images via C# API.
keywords: .NET Word, alternative to MS Word, .NET DOCX API, .NET DOTM, .NET DOTX, NET DOCM,  C# Word API, .NET Word Library, C# Word Processing  API, create word, add text in it,  Read DOCX files, 
draft: false
weight: 3



ProductName: NPOI
Githublink: https://github.com/tonyqus/npoi
ListingPage_Short_Description: NPOI API allows .NET developers to read & write DOCX files within .NET applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source .NET API allows to Read, Write, Manipulate & Convert Microsoft<sup>®</sup> Word files."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text=".NET Library for Creating Word Processing Documents"
Header_H2_Text="Open Source .NET API allows to Read, Write, Manipulate & Convert Microsoft<sup>®</sup> Word files." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is NPOI?</h2>
<p>NPOI is a .NET version of the POI Java Project. It is an open-source .NET library to read and write Microsoft<sup>®</sup> Office file formats. NPOI.XWPF namespace allows you to manipulate the <a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a> file format.</p>
<p>NPOI allows you to add text & paragraphs, insert hyperlinks, create & parse tables, insert images, and by using XWPFWordExtractor class you can also extract text from existing Word Processing Documents.</p>

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
<li>Create DOCX</li>
<li>Style Text</li>
<li>Add Paragraphs</li>
<li>Add Tables</li>
<li>Insert Images</li>
<li>Read documents</li>
<li>Extract text</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Open XML SDK</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>NPOI supports popular Word Processing file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a></li>
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
<h2 class="h2title">Getting Started with NPOI</h2>
<p>Once you have met the prerequisites, you can manually download the repository from <a href="https://github.com/tonyqus/npoi">GitHub</a> or install it from NuGet.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install NPOI from NuGet</h3>
<pre><code class="html"> Install-Package NPOI -Version 2.4.1</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manipulate DOCX file using C#</h2>
<p>NPOI allows .NET programmers to create as well as modify word processing from their own .NET applications. In order to modify an existing file, you can open an existing file and append changes like text, paragraphs, tables, and more.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create DOCX using NPOI - C#</h3>
<pre><code class="c#">XWPFDocument doc = new XWPFDocument();
doc.CreateParagraph();
using (FileStream sw = File.Create("fileformat.docx"))
{
        doc.Write(sw);
}
                        </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create a Table in DOCX using C#</h2>
<p>The API allows the developers to add a table in Word Processing documents. You can add a table, set table properties, set table grid, and column grid properties. Furthermore, you can manage table cells and rows using TableCell and TableRow classes respectively. The following simple lines of code can add Table in Word document in C#.</p>
<ol>
<li>Create a new DOCX document using XWPFDocument</li>
<li>Add table in the document by using doc.CreateTable() method and set rows and column numbers as int</li>
<li>Get first row and first cell by using table.GetRow(1).GetCell(1) and add text to it using setText() method</li>
<li>Save the file by using FileStream() method and set output file name and creation file mode</li>
</ol>
<br>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create Table in DOCX using NPOI - C#</h3>
<pre><code class="c#">XWPFDocument doc = new XWPFDocument();
                        
XWPFTable table = doc.CreateTable(3, 3);

table.GetRow(0).GetCell(0).SetText("File Format Developer Guide");

FileStream out1 = new FileStream("table.docx", FileMode.Create);
doc.Write(out1);
out1.Close();
                        </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}