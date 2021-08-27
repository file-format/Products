---
title: Open Source C Library for Compression & Decompression of Data Files
description: zlib – An open source free C data compression library to create archiver that enables computer programmers to compress and decompress your data and data.
keywords: C Compression, Java compression API, compress files in Java, decompress files Java,  JAR Java Archive, Java 7-zip, Java GZip library, Java  BZip2, Java BZip2,  Java Zip programming, Java RAR Archive, Java TAR, create  ZIP archive, Java compression Library, Open Source Java Library
draft: false
weight: 13



ProductName: zlib
Githublink: https://github.com/madler/zlib
ListingPage_Short_Description: An open source C API that supports creating archiver that enables computer programmers to compress and decompress their data files.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source C Data Compression Library to Create Archiver that enables Programmers to Compress and Decompress your Data Files."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="C API for Compression & Decompression of Data Files"
Header_H2_Text="Open Source C Data Compression Library to Create Archiver that enables Programmers to Compress and Decompress your Data Files." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The zlib open source free data compression C library enables computer programmers to create archiver for working with compression file formats inside their own applications. It is a lossless data-compression library for use on virtually any computer hardware and operating system. The great thing is that zlib data format is itself portable across platforms.</p>
<p>The zlib library is stable, portable, and free. The Zlib engine uses a simple API that mechanizes the compression and decompression of your files. The library uses virtual functions that allow users to customize their user interface to zlib. zlib is also a crucial component of many software platforms, including Linux, macOS, and iOS. The library offers facilities for controlling the processor and memory usage.</p>

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
<p>An overview of zlib features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Compression</li>
<li>Decompression</li>
<li>Compressed string of data</li>
<li>Save compressed data</li>
<li>Decompressed File data</li>
<li>Generate Archives</li>
<li>Extract archives</li>
<li>Extract ZIP</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for PHP" />--><header>zlib</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>zlib supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/tar/">TAR</a>, <a href="https://docs.fileformat.com/compression/bz2/">BZIP2</a>, TBZ, TGZ</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>AR, ZIP, TBZ2, TBZ, TGZ</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>zlib </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>zlib only requires C run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>C</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>zlib</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with zlib</h2>
<p>To run your project using zlib, you need to download the repository from <a href="https://github.com/madler/zlib.git">GitHub</a>. Use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the command</h3>
<pre><code class="html"> git clone https://github.com/madler/zlib.git<br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compressing a String of Data</h2>
<p>zlib provides the functionally for compressing string of data inside your own applications. It allows to compresses the given input data to the given destination directory or file. The zlib library provides us with the compress function, which can be used to compress a string of data. It requires two arguments for data that need to compressed and a parameter for the level of compression.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Saving Compressed Data to a File</h2>
<p>The open source zlib library provides us with some handy set of functions for file compression. It facilitates users and applications to save the compressed data into a file or disk space and use it later. You need to provide the data as well as the name of the file for saving the compressed data. After saving the compressed data you can later view and use that data according to your needs.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Decompressing a String of Data & File Data</h2>
<p>The open source zlib library also facilitates users and archivers applications to decompressing a String of Data inside their own apps. Some useful set of functions are provided for this purpose. You can easily decompress a compressed string of data using the decompress function. It also supports decompressing large data streams as well as compressed data contained in a file.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
<p> </p>
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}