---
title: ExcelDNA – Create & Deploy Excel Add-Ins using C#, F# or VB .NET


draft: false
weight: 7



ProductName: ExcelDna
Githublink: https://github.com/Excel-DNA/ExcelDna
ListingPage_Short_Description: Free API to create & deploy Excel Add-Ins using .NET.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="ExcelDna allows you to create & deploy Excel Add-Ins using C#, F# or VB .NET."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source .NET Library for Processing Excel Spreadsheets"
Header_H2_Text="ExcelDna allows you to create & deploy Excel Add-Ins using C#, F# or VB .NET." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Excel-DNA is an open source API to integrate .NET into Excel. The API allows you to create high performace user defined functions(UDFs) and more in your native (.xll) add-ins for Excel. You don't need any installation or registration, your entire add-in can be packed into a single .xll.</p>
<p>The Excel-DNA Runtime is free for all use, and is distributed under a permissive open-source license that also allows commercial use. It is developed using .NET and users have to install .NET Framework runtime. The Excel and the .NET code intergrate with each other using Add-In (.xll) that exposes .NET code to excel. You can write you code in text-based (.dna) script files (C#, Visual Basic or F#), or compiled .NET libraries (.dll).</p>

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
<p>An overview of ExcelDna features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create Excel Add-In</li>
<li>Multi-threaded recalculation</li>
<li>Registration-free RTD servers</li>
<li>Customized Ribbon interface</li>
<li>Logging mechanism</li>
<li>Offloading UDF computations</li>
<li>Integrated Custom Task Panes</li>
<li>Clean up ExcelReference</li>
<li>Add XML schema for .dna</li>
<li>Add option to pack .pdb</li>
</ul>
</div>
<!--/left--></div>
<!-- <div class="d1-logo" style="border: none;">
         <img src='listing-image.png' alt="Compression APIs for .NET" /
         <header>Excen-DNA</header>
         <footer><small></small></footer>
        </div> --> <!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Excel-DNA supports popular formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/spreadsheet/xlsx/">XLSX</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a>.XLL</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Excel-DNA</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Excel-DNA only requires .NET Framework 4.0 or greater.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Excel-DNA</h2>
<p>The recommended way to install ExcelDNA is from Nuget, Please use the following command for fasters installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install ExcelDNA from NuGet</h3>
<pre><code class="html"> Install-Package ExcelDna.AddIn</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create Excel Functions via .NET API</h2>
<p>ExcelDNA gives C# .NET programmers the competency to generate Excel functions inside using C#. You can also use ExcelFunctionAttributes like Name, Description, Category, IsHidden, IsExceptionSafe and more. The IsMacroType attribute changes the parameters Excel-DNA uses when registering the function.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Support for Dynamic Arrays</h2>
<p>The open source .NET API Excel-DNA also supports the use of dynamic arryays inside excel. when you write an dynamic arrya formula it determines if the formula has the potential to return multiple values.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Diagnostic Logging</h2>
<p>ExcelDNA API allows .NET developers to use diagnostic logging while working with Excel Add-In. Excel-DNA uses the standard .NET System.Diagnostics.Trace mechanisms for diagnostic logging.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}