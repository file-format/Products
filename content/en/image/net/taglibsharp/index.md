---
title: Open Source .NET API for Image File Formats - Read & Write Metadata of Image File Formats
description: TagLib-Sharp - An Open Source Free .NET API for Video File Format. Read and Write Metadata tags of image file formats
keywords: TagLib API, TagLib Sharp API, Free Image API, Free .NET API, Free MP4 API, Open Source MP4 API, Free MP4 Audio
draft: false
weight: 1



ProductName: Taglib-Sharp
Githublink: https://github.com/mono/taglib-sharp
ListingPage_Short_Description: Open Source .NET Library for Image Processing that allows reading and writing metadata tags for images.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read & Write Metadata of Image File Format."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text=".NET Library for Manipulating Image Documents"
Header_H2_Text="Read & Write Metadata of Image File Format." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Taglib-Sharp?</h2>
<p>As a developer, have you ever had to extract metadata or write metadata to image files formats? There are a bunch of open-source and APIs available for image manipulation. Taglib-Sharp is one of them. The open-source API is developed for reading and writing metadata in Image file formats. Using the API, you can read & write standard tags of Image file format and can also create and extract metadata of custom tags.</p>
<p>TagLib-Sharp in free software released under the LGPL. The developer can create their own metadata extraction & creation applications using the API. The developers can work with a wide range of Image file formats for metadata manipulation.</p>

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
<p>An overview of Taglib-Sharp features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Read Metadata</li>
<li>Write Metadata</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Taglib-Sharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Taglib-Sharp supports popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a>, <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="#">PBM</a>, <a href="#">PPM</a>, <a href="#">PNM</a>, <a href="#">PCX</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a href="https://docs.fileformat.com/page-description-language/svg/">SVG</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a>, <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="#">PBM</a>, <a href="#">PPM</a>, <a href="#">PNM</a>, <a href="#">PCX</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a href="https://docs.fileformat.com/page-description-language/svg/">SVG</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Taglib-Sharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>The API works with .NET Framework 4.5 and .NET Standard 2.0.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Taglib-Sharp</h2>
<p>The best way to install Taglib-Sharp is via NuGet you can run the following command and install Taglib-Sharp in your application.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Taglib-Sharp from NuGet</h3>
<pre><code class="html"> Install-Package Taglib-Sharp</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Metadata Tags from Image via Free .NET API</h2>
<p>Taglib-Sharp allows .NET programmers to extract metadata tags from Image file formats easily. The API allows getting a bunch of image tags including, Rating, DateTime, Orientation, Software, ExposureTime, FNumber, ISOSpeedRatings, FocalLength, FocalLength35mm, Make, Model, and more. In order to get any property, you need to load the Image file using TagLib.File.Create() method and read tag e.g Make using Image.ImageTag.Make property.</p>
<h3>Extract Metadata from Images via Free C# API</h3>
<ol>
<li>Create a new client</li>
<li>Convert DOCX to Text using client.ConvertPath() and pass file path as parameter</li>
<li>Check for errors</li>
<li>Print plain text</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Free API to Extract Metadata from Images</h3>
<pre><code class="c#">// load file
var image = TagLib.File.Create("fileformat.png");
// get camera maker
string make = image.ImageTag.Make;
// get camera model
string model = image.ImageTag.Model;
// print properties
Console.WriteLine("Make: {0}, Model: {1}", title, model);
         </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}