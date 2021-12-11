---
title: Open Source .NET API for Audio File Formats - Read & Write Metadata of Audio File Formats
description: NAudio -  Open-Source API that enables software developers to read, play, record, convert & encode Audio File Formats using .NET applications.
keywords: NAudio API, API, Free Audio API,  Free .NET API, Free MP3 API, Open Source MP3 API, Free MP3 Audio, Extract Metadata, Write MP3 Metadata, Extract Audio Metadata, Write Audio Metadata, .NET Audio Tags, Audio Tags, Custom Audio Tags, Free MP3 Tags
draft: false
weight: 1


ProductName: NAudio
Githublink: https://github.com/naudio/NAudio
ListingPage_Short_Description: Open-Source API that enables software developers to read, play, record, convert & encode Audio File Formats using .NET applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Play, Reocord, Encode, Read & Convert Audio files via .NET API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Free.NET Library for Manipulating Audio File Formats"
Header_H2_Text="Play, Record, Encode, Read & Convert Audio files via .NET API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>NAudio is an open source API to manipulate audio files programmtically. The API allows the .NET Developer to read audio from different standards, playback audio, convert audio formats, record system audio and more. The API intends to provide a comprehensive set of useful utility classes by using which you can construct your own audio manipulation application.</p>
<p>Using the API, you can playback audio using Waveout, DirectSound, ASIO & WASAPI and can read audio from WAV, AIFF, MP3, G.711, ADPCM, WMA, AAC, MP4 and more. The API allows encoding audio using and ACM codec installed on your machine, you can mix and manipulate audio streams using 32-bit mixing engine.</p>

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
<p>An overview of NAudio features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Play Audio</li>
<li>Read Audio</li>
<li>Convert Audio</li>
<li>Modify Bit Depth</li>
<li>Encode Audio</li>
<li>Create WMA</li>
<li>Create AAC/MP4 Audio</li>
<li>Support for UWP</li>
<li>Work with sound-cards</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>NAduio</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>NAudio supports popular Audio file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/audio/mp3/">MP3</a>,  <a href="https://docs.fileformat.com/audio/aac/">AAC</a>,  <a href="https://docs.fileformat.com/audio/wav/">WAV</a>,  G.711 mu-law, G.711 a-law, MP4, WMA, ADPCM, G.722</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/audio/mp3/">MP3</a>,  <a href="https://docs.fileformat.com/audio/aac/">AAC</a>,  <a href="https://docs.fileformat.com/audio/wav/">WAV</a>, MP4, WMA</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>NAudio</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>NAudio work with .NET Core App 3.0, .NET Framework 3.5, .NETStandard 2.0 & UAP 10.0.</p>
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with NAudio</h2>
<p>The best way to install to install NAudio is via NuGet you can run the following command and install NAudio in you application.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install NAudio from NuGet</h3>
<pre><code class="html"> Install-Package NAudio</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Play Audio File using Free C# API</h2>
<p>NAudio allows .NET programmers play audio files from their own .NET applications. After your file is successfully opened you can use WaveOutEvent as an output device to play audio. You can simply play audio by passing AudioFile to outPutDevice with Init method and call Play() method.</p>

{{< /SinglePage/PageBody/features/text >}}

{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Free C# API to Convert MP3 to WAV file</h2>
<p>The API allows the developers to convert MP3 files to other file formats. The developers can add MP4 conversion feature in their own application, if the ACM MP3 codec is present in the application machine. This codec is usually pre installed in most version of Windows. Converting MP3 to WAV is pretty simple you just need to open MP3 file using MP4FileReader and convert it using WaveFileWriter.CreateWaveFile() method.</p>

{{< /SinglePage/PageBody/features/text >}}


{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Concatenate Multiple Audio Files via C#</h2>
<p>The API allows the developers to Concatenate multiple audio files into single audio file. The Concatenation process is pretty simple. You can load your multiple audio files using AudioFileReader() method and Concatenate them using ConcatenatingSampleProvider() method.</p>

{{< /SinglePage/PageBody/features/text >}}


{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}