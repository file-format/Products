---
title: Open Source .NET API for Video File Formats - Read & Write Metadata of Video File Formats
description: TagLib-Sharp - An Open Source Free .NET API for Video File Format. Read and Write Metadata tags of video file formats
keywords: TagLib API, TagLib Sharp API, Free Audio API,  Free .NET API, Free MP4 API, Open Source MP4 API, Free MP4 Audio
draft: false
weight: 1



ProductName: Taglib-Sharp
Githublink: https://github.com/mono/taglib-sharp
ListingPage_Short_Description: Free API to read and write metadata in Video File Formats.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read & Write Metadata of video File Format."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text=".NET Library for Manipulating video Documents"
Header_H2_Text="Read & Write Metadata of video File Format." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Taglib-Sharp is an open-source API developed for reading and writing metadata in video file formats. Using the API, you can read & write standard tags of video file format and can also create and extract metadata of custom tags. The API is designed to extract any format, any container the video file format is using.</p>
<p>TagLib-Sharp in free software released under the LGPL. The developer can create their own metadata extraction & creation applications using the API. The developers can work with a wide range of video file formats for metadata manipulation.</p>

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
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Taglib-Sharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Taglib-Sharp supports popular video file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/video/mkv/">MKV</a>, <a href="https://docs.fileformat.com/video/avi/">AVI</a>, <a href="https://docs.fileformat.com/video/wmv/">WMV</a>, <a href="https://docs.fileformat.com/video/mp4/">MP4</a>, <a href="https://docs.fileformat.com/video/asf/">ASF</a>,<a href="https://docs.fileformat.com/audio/m4a/">MPEG</a>, OGV</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/video/mkv/">MKV</a>, <a href="https://docs.fileformat.com/video/avi/">AVI</a>, <a href="https://docs.fileformat.com/video/wmv/">WMV</a>, <a href="https://docs.fileformat.com/video/mp4/">MP4</a>, <a href="https://docs.fileformat.com/video/asf/">ASF</a>,<a href="https://docs.fileformat.com/audio/m4a/">MPEG</a>, OGV</li>
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
<h2 class="h2title">Extract Metadata Tags from video via Free .NET API</h2>
<p>Taglib-Sharp allows .NET programmers to extract metadata tags from video file formats easily. You can extract the tag regardless of the container or the format of the tag. To extract metadata tag, first, you need to load the video file using TagLib.File.Create() method and read tag e.g Title using TagFile.Tag.Title property. The following code snippet demonstrates, how to extract metadata properties from video file.</p>
<h3>Extract Metadata from using C#</h3>
<ol>
<li>Load video using TagLib.File.Create() method and pass file path as string</li>
<li>Extract title as a string using tfile.Tag.Title property</li>
<li>Extract video duration as TimeSpan using tfile.Properties.Duration property</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Merge XLSX to PDF via Free PHP API</h3>
<pre><code class="C#">var tfile = TagLib.File.Create(@"video.avi");
string title = tfile.Tag.Title;
TimeSpan duration = tfile.Properties.Duration;
Console.WriteLine("Title: {0}, duration: {1}", title, duration);
                                                            </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Free C# API to Write video Metadata Tags</h2>
<p>The open-source API TagLib-Sharp allows .NET developers to write standard as well as custom metadata tags in video file formats. To write, you can read a video file using TagLib.File.Create() method and new tag value using Tag. Tile property.</p>

{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Merge XLSX to PDF via Free PHP API</h3>
<pre><code class="C#">var tfile = TagLib.File.Create(@"video.avi");
string title = tfile.Tag.Title;
TimeSpan duration = tfile.Properties.Duration;
Console.WriteLine("Title: {0}, duration: {1}", title, duration);
                                                            </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}