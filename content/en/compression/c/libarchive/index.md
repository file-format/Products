---
title: Read, Write Tar, Zip, Pax, ISO & Cpio Files via Open Source C Library
description: Libarchive – An Open Source Free C Library for working with streaming archives.  Read & write compression files like RAR, Zip, TAR, GZip & BZip2 via C API.
keywords: Free Compression API, Free ZIP library, C Compression API, C compression Library, compress  files programmatically, decompress files,  Rar C API, C 7-zip, C GZip library,  C compression Library, Open Source C Library, C Zip programming, C Rar APIs, C Tar, create  zip file, compression file formats
draft: false
weight: 1



ProductName: Libarchive 
Githublink: https://github.com/libarchive/libarchive
ListingPage_Short_Description: Open Source C Library that supports popular compression file formats like RAR, 7ZIP, ZIP, TAR & more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="C Library for Reading/Writing streaming archives in TAR, ZIP, 7-ZIP, CPIO, PAX & ISO formats. "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source C API for Compression File Formats"
Header_H2_Text="C Library for Reading/Writing streaming archives in TAR, ZIP, 7-ZIP, CPIO, PAX & ISO formats. " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Libarchive is an open source pure C library that enables software developers to read and write streaming archives in different formats, such as TAR, ZIP, 7-ZIP, CPIO, PAX, and ISO9660 images. The great thing about Libarchive is that it is highly modular. From the beginning, it was designed in such a manner that adding new archive formats is easy as compare to other libraries.</p>
<p>Libarchive supports Reading and writing several popular compressing file formats. It reads several popular formats, such as TAR, ZIP, 7-ZIP, CPIO, PAX, RAR, XAR, LHA, AR, CAB, MTREE, and ISO images. It also provides writing support for popular formats like TAR, ZIP, ISO, XAR, PAX, CPIO, AR, MTREE and SHAR archives.</p>
<p><span style="font-size: 12.16px;">.</span></p>

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
<p>An overview of Libarchive features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create zip</li>
<li>gzip compression</li>
<li>bzip2 compression</li>
<li>Create tar</li>
<li>create gzip</li>
<li>lz4 compression</li>
<li>unzip files</li>
<li>7-Zip archives</li>
<li>unbzip2 files</li>
<li>XAR archives</li>
<li>shar archives</li>
<li>ZIPX archives</li>
<li>Uuencode </li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;">  <!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Libarchive</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Libarchive supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/rar/">RAR</a>, 7Zip, <a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/tar/">TAR</a>, <a href="https://docs.fileformat.com/compression/bz2/">BZIP2</a>, <a href="https://docs.fileformat.com/compression/gz/">GZIP</a>, PAX, CPIO</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>ZIP, TAR, BZIP2, Gzip, PAX, CPIO, ISO, MTREE</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><br><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Libarchive only requires <i class="fa fa-cubes">C run-time</i></p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Libarchive</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Libarchive</h2>
<p>The libarchive distribution contains a standard Autoconf-generated "configure" script that can be used to install libarchive, bsdtar, and bsdcpio on almost any POSIX-like system.</p>
<p>A typical installation code is given below</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the Command</h3>
<pre><code class="html">$ tar xzf libarchive-2.7.0.tar.gz
$ cd libarchive-2.7.0
$ ./configure
$ make
$ make check
$ make install <br></code></pre>

<p>You can also use the "cmake" utility to generate configuration files for a variety of IDEs, such as Visual Studio on Windows and XCode on Mac OS. Please remember that it can be used with libarchive 2.6.990a or later. You will first need to obtain and install the appropriate version of the cmake tool for your platform</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Use Automatic Format Detector</h2>
<p>Libarchive uses an automatic format detector when reading archives. It uses an internal “bidding” process that examines the incoming data using multiple modules. The detector automatically tackles archives that are compressed with Tar, Gzip, Bzip2, and many other popular compression algorithms.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Writing Files to Gzipped TAR Archive</h2>
<p>Libarchive enables software developers to write a group of files into a gzipped tar archive. The writing feature is more complex as compared to the reading feature. The common procedure is to first create the struct archive object, set any preferred options, initialize the archive, append entries and in the end, don’t forget to close the archive and release all resources.</p>
<h2 class="h2title">C API for Reading File Contents</h2>
<p>Libarchive allows computer programmers to read and extract the contents of a file. For file extracting from the archive you first iterate through it until you find one with the filename you want. After that, you can read data and writes it to a file on disk. Compression and format are automatically detected in reading.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">How to Extract Archives to Disk inside C Apps</h2>
<p>Libarchive API gives computer programmers the capability to extract most archives to a disk. To extract archives you need to read headers from the input archive and writes them to disk. To complete the task you need to pull data from a reading archive and write it to a write handler.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}