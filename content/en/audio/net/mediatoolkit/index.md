---
title: Open Source .NET API for Audio Processing - Convert and Process Audio Files
description: MediaToolkit -  Open-Source API that enables software developers to convert and process Audio File Formats using .NET applications.
keywords: MediaToolkit API, API, Free Audio API,  Free .NET API, Free MP3 API, Open Source MP3 API, Free MP3 Audio, Extract Metadata, Write MP3 Metadata, Extract Audio Metadata, Write Audio Metadata, .NET Audio Tags, Audio Tags, Custom Audio Tags, Free MP3 Tags, Convert Audio Free, Free Audio API, Process Audio API
draft: false
weight: 1



ProductName: MediaToolkit
Githublink: https://github.com/AydinAdn/MediaToolkit
ListingPage_Short_Description: Open-Source API that enables software developers to convert and process Audio File Formats using .NET applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert & Process Audio files via .NET API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Free.NET Library for Manipulating Audio File Formats"
Header_H2_Text="Convert & Process Audio files via .NET API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>MediaToolkit is an open source API to manipulate audio files programmatically. The API allows the .NET Developer to effortlessly convert, slice and get metadata of audio files. 
MediaToolkit API is a wrapper for FFmpeg. It is a free multimedia framework containing multiple audio codecs.</p>
<p>Using the API, you can resolve audio metadata and transcode audio into other formats using parameters including Bit rate, Frame rate, Resolution, Aspect ratio, Seek position, Duration, Sample rate and Media Format.</p>

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
<p>An overview of MediaToolkit features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Retrieve Metadata</li>
<li>Transcode audio</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>MediaToolkit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MediaToolkit supports popular Audio file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/audio/mp3/">MP3</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/audio/mp3/">MP3</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>MediaToolkit</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MediaToolkit package has no dependencies..</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with MediaToolkit</h2>
<p>The best way to install MediaToolkit is via NuGet you can run the following command and install MediaToolkit in you application.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install MediaToolkit from NuGet</h3>
<pre><code class="html"> Install-Package MediaToolkit</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Free C# API to Retrieve Audio Metadata</h2>
<p>The API allows the developers to retrieve metadata of Audio file formats. The developers can extract audio metadata inside their own application. In order to get metadata of audio file format the API provides the GetMetadata() method. By using the following lines of code, you can easily get metadata of audio file format.</p>
<h3>Retrieve Audio Metadata</h3>
<ol>
<li>Import MediaFile</li>
<li>Initialize MediaToolkit's Engine and Get audio metadata using Engine.GetMetadata(inputFile) method and pass MediaFile as parameter</li>
<li>Print Metadata</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Resize Image  via Free GO API</h3>
<pre><code class="c#">var inputFile = new MediaFile {Filename = @"C:\Path\Audio.mp3"};
using (var engine = new Engine())
{
    engine.GetMetadata(inputFile);
}
Console.WriteLine(inputFile.Metadata.Duration);</code></pre>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}