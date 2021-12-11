---
title: Open Source .NET API for Audio File Formats - Read & Write Metadata of Audio File Formats
description: TagLib-Sharp - An Open Source Free .NET API for Video File Format. Read and Write Metadata tags of Audio File Formats
keywords: TagLib API, TagLib Sharp API, Free Audio API,  Free .NET API, Free MP3 API, Open Source MP3 API, Free MP3 Audio, Extract Metadata, Write MP3 Metadata, Extract Audio Metadata, Write Audio Metadata, .NET Audio Tags, Audio Tags, Custom Audio Tags, Free MP3 Tags

draft: false
weight: 1



ProductName: Taglib-Sharp
Githublink: https://github.com/mono/taglib-sharp
ListingPage_Short_Description: Free API that allows software developers to Read & Write Audio File Format metadata tags in .NET Application.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Read & Write Metadata of Audio File Format."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Free .NET Library to Handle Metadata of Audio Documents"
Header_H2_Text="Read & Write Metadata of Audio File Format." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Taglib-Sharp is an open source API developed for reading and writing metadata in audio file formats. Using the API, you can read & write standard tags of audio file format and can also create and extract metadata of custom tags. The API is designed to extract any format, any container the audio file format is using.</p>
<p>TagLib-Sharp in free software released under the LGPL. The developer can create their own metadata extraction & creation applications using the API. Futhermore, the API allows them to work with wide range of audio file formats for metadata manipulation.</p>

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
<p>Taglib-Sharp supports popular Audio file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/audio/mp3/">MP3</a>,  <a href="https://docs.fileformat.com/audio/aac/">AAC</a>,  <a href="https://docs.fileformat.com/audio/wav/">WAV</a>, AA, AAX, AIFF, APE, DSF, FLAC, M4A, M4B, M4P, MPC, MPP, OGG, OGA, WMA, WV, WEBM</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/audio/mp3/">MP3</a>,  <a href="https://docs.fileformat.com/audio/aac/">AAC</a>,  <a href="https://docs.fileformat.com/audio/wav/">WAV</a>, AA, AAX, AIFF, APE, DSF, FLAC, M4A, M4B, M4P, MPC, MPP, OGG, OGA, WMA, WV, WEBM</li>
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
<p>The best way to install to install Taglib-Sharp is via NuGet you can run the following command and install Taglib-Sharp in you application.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Taglib-Sharp from NuGet</h3>
<pre><code class="html"> Install-Package Taglib-Sharp</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Metadata Tags from Audio via Free .NET API</h2>
<p>Taglib-Sharp allows .NET programmers extract metadata tags from audio file formats easily. You can extract tag regardless of container of format of the tag. In order to extract metadata tag, first you need to load audio file using TagLib.File.Create() method and read tag e.g Title using TagFile.Tag.Title property.</p>

{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Taglib-Sharp from NuGet</h3>
<pre><code class="html"> Install-Package Taglib-Sharp</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Free C# API to Write Audio Metadata Tags</h2>
<p>The open source API TagLib-Sharp allows .NET developers to write standard as well as custom metadata tags in audio file formats. In order to write you can read an audio file using TagLib.File.Create() method and new tag value using Tag.Tile property.</p>

{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Taglib-Sharp from NuGet</h3>
<pre><code class="html"> Install-Package Taglib-Sharp</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}