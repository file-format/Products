---
title: Compression Library for Go - Pgzip
description: Pgzip allows software developers to create, manage & extract files from archives via Go API.

draft: false
weight: 21



ProductName: pgzip
Githublink: https://github.com/mholt/Archive
ListingPage_Short_Description: It provides complete functionality for parallel compression and decompression of large Files using the Go language.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Golang API for programmatically generating as well as reading standard GZIP files. Compress large files by splitting it into blocks and perform compression/decompression in parallel."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Go Library for Parallel Compression and Decompression"
Header_H2_Text="Golang API for programmatically generating as well as reading standard GZIP files. Compress large files by splitting it into blocks and perform compression/decompression in parallel." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>pgzip is an open source library that provides complete functionality for parallel compression and decompression using Go language. The library is useful for compressing a large amount of data as it is divided into blocks and performed compression/decompression in parallel. The pgzip library is incredibly popular among the developer community and allows Go apps to directly read compressed files with just a couple of commands.</p>
<p>The library is stable and allows developers to programmatically generate as well as read standard GZIP files. To get the best out of the library it is recommended to use compress or decompress a big amount of data (more than 2MB at a time). The library supports several important features such as compress files, decompress files, open and read GZIP files and much more.</p>

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
<p>An overview of pgzip features.</p>
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
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>pgzip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>pgzip supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>GZIP, ZIP</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, GZIP</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>pgzip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>pgzip only requires Go.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li>Go &gt;= 1.2 </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>pgzip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with pgzip</h2>
<p>The recommended way to install pgzip is from GitHub. Use the following command for smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install pgzip via command</h3>
<pre><code class="html">go get github.com/klauspost/pgzip/...</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compress Large Files via Go API</h2>
<p>The open source pgzip library has included functionality for compressing large amounts of data files using a couple of lines of Go code. The API supports the splitting of the large file into small parts (by default the block size is 1MB) and can be processed up to the number of CPU threads. You can easily control the size of the blocks as well as customize it according to your needs and how many you want to be processed in parallel. For better performance gains, it is advised that users at least be compressing more than 1 megabyte of data at a time.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Decompressing Files via Go API</h2>
<p>The free pgzip library enables software developers to decompress their files inside their own Go applications. Same as compression the decompression can also be performed by customizing the block size. You can easily get your own reader and specify your own read-ahead. For your reader, you need to define the block size and the maximum number of blocks that are going to be decoded ahead.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Performance Improvement</h2>
<p>The performance of pgzip can be improved as compared to gzip when you have big amounts of data. As pgzip processes blocks in parallel, it obviously has a speed advantage on the other compressors. Use for high throughput, high compression material, like logs, JSON, CSV data can also be useful. One great advantage of pgzip while decompression is it allows you to do other work while the decompression is taking place.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}