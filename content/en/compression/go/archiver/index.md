---
title: Open Source Go Library – Create & Extract ZIP, TAR & RAR Archives
description:  archiver - Open Source Free Go compression Library that allows software developers to create, manage & extract files from ZIP, TAR & RAR Archives via Go API.
keywords: open source Go API,  Free Go library, Go ZIP API, Go Compression API, compress files, decompress files, ZIP GO API, Go compression Library, Open Source Go Library, Go Zip programming, create  zip archives, Opening zip archives, create BZIP2 archives, save archive to a file, List zip archive, RAR Archive, TAR Go archive
draft: false
weight: 20



ProductName: archiver
Githublink: https://github.com/mholt/archiver
ListingPage_Short_Description: open source Go library that provides functionality for creating, managing & extracting archives with ease using Go commands.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Creating, Managing & Extracting Archives with ease using cross-platform, high-level Go API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Working with Archives"
Header_H2_Text="Creating, Managing & Extracting Archives with ease using cross-platform, high-level Go API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>archiver is an open source Go library that provides functionality for creating, managing & extracting archives with ease using Go commands. The library is very stable, cross-platform, high-level archival and compression operations for a variety of formats. Some of the most common functions such as Archive, Unarchive, Extract, CompressFile, and DecompressFile are implemented at the package level for user’s convenience.</p>
<p>The library enables software developers to compress & decompress files of various compression file formats such as Brotli (br), Bzip2 (bz2), Flate (ZIP), Gzip (GZ), lz4, snappy (SZ), xz, and Zstandard (ZSTD). It also provides support for archiving formats like ZIP, TAR, and RAR.</p>
<p>The API is well documented and very easy to use. It provides complete support for several important  features related to compression and decompression such as create archives, Extract folder from archives, compress files, decompress files,  extract specific files, Stream files, Traverse archive contents, create and Open password-protected RAR archives,  streaming compression as well as decompression, and much more.</p>

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
<p>An overview of archiver features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Read ZIP-archives</li>
<li>Modify ZIP-archives</li>
<li>generate ZIP-archives</li>
<li>Unzipping ZIP files</li>
<li>Extract ZIP archive</li>
<li>Append File</li>
<li>Extract specific file</li>
<li>List of ZIP archive</li>
<li>Add file</li>
<li>Add directory</li>
<li>Delete file</li>
<li>Close archive</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>archiver </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>archiver supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>ZIP<span style="font-size: 12.16px;">, </span>BZIP2, TAR, RAR, Flate, GZIP, LZ4, Brotli</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/bz2/">BZIP2</a>, TAR, RAR, Flate, GZIP, LZ4, Brotli</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>archiver</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>archiver only requires Go.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li>Go &gt;= 1.2 </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>archiver</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with archiver</h2>
<p>The recommended way to install archiver is from GitHub, please use the following command for smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install archiver via command</h3>
<pre><code class="html">go get github.com/mholt/archiver/cmd/arc"</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create an Archive File via Go</h2>
<p>The archiver library enables software developers to create an archive file of the source files to a new file at the destination using a couple of lines of Go code. You can also easily add a file or folder to the archive with ease. The file will be added to the top level of the archive and the directories are recursively added. When creating archives or compressing files using a specific instance of the format's type, the name of the output file MUST match that of the format, to prevent confusion later on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compress and Decompress Files</h2>
<p>The open source archiver library enables software developers to compress and decompress files inside their own applications. There are several important functions and methods included for compressing and decompressing files. You can use easily compress a file or directory, decompress a file or directory, extract a specific file, folder extraction, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract a Specific File or Folder from Archives</h2>
<p>The open source archiver library enables software developers to read & extract a specific file using Go API. The library supports extracting files and folders into a place of your choice with just a couple of lines of code.  You can easily select a particular file from a provided archive and can extract it to a place of your choice. Same as file you can also extract an entire folder to the destination of your choice.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}