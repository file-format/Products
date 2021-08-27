---
title: Open Source C Compression Library – Speedy & Better Compression Ratios
description: Zstandard - Open Source C library for fast real-time compression & decompression. It supports better small Data compression, high compression ratios & more.
keywords: open source C API,  Free C library, C ZIP API, C Compression API, compress files via C API, decompress files, ZIP C API, C compression Library, Open Source C Library, C Zip programming, create  zip archives, Opening zip archives, create BZIP2 archives, save archive to a file, List zip archive, RAR Archive, Small Data compression, special mode for small data
draft: false
weight: 15



ProductName: Zstandard
Githublink: https://github.com/facebook/zstd
ListingPage_Short_Description: Open Source C API for fast real-time & small data compression and decompression.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Zstandard"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="C Library for Powerful and Fast Compression "
Header_H2_Text="" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Zstandard is an open source C compression library that provides a powerful and fast algorithm for high compression ratios inside C applications. The library offers a very wide range of speed and is available under dual BSD and GPLv2 licensed. The library supports dictionary compression mode which is very useful for small data compression.</p>
<p>The Zstandard library target real-time compression scenarios at zlib-level and better compression ratios. The library supports regular compression levels from 1 up 22. Please remember that Levels 20 and higher must be used with care, as much more memory is required for smooth working.</p>
<p>The API is very stable, well documented, and very easy to handle. It has included support for several important functions related to compression and decompression, streaming compression as well as decompression, dictionary helper functions, frame sizing, better memory management. The library also supports advanced functions for compression and decompression, Buffer-less and synchronous inner streaming functions, buffer-less streaming compression, and decompression (synchronous mode).</p>

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
<p>An overview of zip features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header>Overview</header>
<ul>
<li>Compress data</li>
<li>Decompress data</li>
<li>Multi-threaded Compression</li>
<li>Small Data Compression</li>
<li>Modify ZIP-archives</li>
<li>Append File</li>
<li>Extract specific entry</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="C Compression API"><header>Zstandard</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Zstandard supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>ZIP, TAR</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/tar/">TAR</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="C Compression API"><header>Zstandard</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Zstandard only requires Go runtime for smooth running.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i>Mandatory</header>
<ul>
<li>C</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="C Compression API"><header>zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Zstandard</h2>
<p>The recommended way to install Zstandard is from GitHub, please use the following command for smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Zstandard library via GitHub</h3>
<pre><code class="html">go get <a href="https://github.com/facebook/zstd.git">https://github.com/facebook/zstd.git</a><br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compression and Decompression via C API</h2>
<p>The open source library Zstandard has included several important functions for compression and decompression. The library offers in-memory compression and decompression functions.  It offers several compression levels that extend the speed and ratio preferences. You can easily compress or decompress a single file as well as multiple files in a single command. With the new release, the decompression speed has been further improved.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Multi-threaded Compression & Decompression via C API</h2>
<p>There are several compression libraries that are single-threaded which means users need to trust another piece of software or writing your own multi-threaded code. The open source library Zstandard has included features that allow a compression operation to leverage multiple threads using C commands. The great thing is that the compression process can switch to multi-threaded API and the decompression process won’t require any special handling.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Small Data Compression and Decompression</h2>
<p>Usually, it has been seen that it is always very difficult to compress or decompress a smaller amount of data. It is a very common problem faced by most compression programs. The Zstandard library has improved this by offering a training mode which allows users to choose a selected type of data. Thus few samples are used with a small amount of data in the training module to tune the program. The result of the training module is stored in a file called the dictionary, which is used in the future before any compression and decompression. It has been observed that the compression algorithm learns from the past data that how to compress future data. Thus using the dictionary concept the compression and decompression ratio on small data has been greatly improved.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}