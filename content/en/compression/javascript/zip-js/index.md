---
title: Read, Write & Edit Large ZIP Files via Open Source JavaScript Library
description: Zip.JS - An Open Source JavaScript Library for Zipping and Unzipping Files. Read, write, delete & extract content of large ZIP files via JavaScript API.
keywords: Free Compression APIs, Free library for ZIP,  JavaScript Compression, JavaScript compression API, compress files in JavaScript, decompress files JavaScript,  JavaScript Archive, JavaScript 7-zip, JavaScript GZip library, JavaScript  BZip2, JavaScript Zip programming, JavaScript TAR, create  ZIP archive, JavaScript compression Library, Open Source JavaScript Library
draft: false
weight: 19



ProductName: Zip.js
Githublink: https://github.com/gildas-lormeau/zip.js
ListingPage_Short_Description: JavaScript API provides functionality for reading, writing & manipulate large ZIP files inside web applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text=" Open Source Free JavaScript API for Reading, Writing, Deleting & Manipulating Large ZIP Files Online."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="JavaScript Library for Reading & Writing Large ZIP Files "
Header_H2_Text=" Open Source Free JavaScript API for Reading, Writing, Deleting & Manipulating Large ZIP Files Online." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Zip.js is an Open Source JavaScript library allows software developers to ZIP and Unzip file inside their own applications. It provides a low-level API for reading and writing large zip files (up to 4GB with File writer API).  The library is fully compatible with all web browsers such as Chrome, Firefox, Safari 6 and Internet Explorer 10.</p>
<p>The library can handle multiple types of data thanks to a generic API.  If you want to read a ZIP file and would like to store its files into a variable, you need to use a ZIP.Reader object for reading the compressed ZIP data. If you would like to write uncompressed file data into the variable then need to use a ZIP.Writer object.</p>
<p>This library depends on Typed array (WebGL) and optionally you can use other APIs such as Web workers for spawning background workers running scripts in parallel to their main page, File API for programmatically selecting files and accessing their data,  File writer API for writing to files from web applications and File directories & system for navigating file system hierarchies.</p>

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
<p>An overview of Zip.js features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Compression</li>
<li>Decompression</li>
<li>file name</li>
<li>Zip entries listing</li>
<li>compressed data size</li>
<li>uncompressed data size</li>
<li>last modification date</li>
<li>file comment</li>
<li>uncompressed data checksum</li>
<li>Add file to ZIP</li>
<li>File encoding</li>
<li>ZIP archive</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Zip.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Zip.js supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Zip.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Zip.js works in all major browsers and Node.js</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>
<ul>
<li>JavaScript</li>
</ul>
</header><header> </header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Zip.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Zip.js</h2>
<p>Add zip.js, z-worker.js, deflate.js, and inflate.js in your project. Please also include zip.js script in your HTML page using the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Add ZIP.JS to HTML page</h3>
<pre><code class="html"> script type="text/javascript" src="/lib/zip.js"&gt;&lt;/script&gt; </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read ZIP Files via JavaScript Library</h2>
<p>The ZIP.JS library provides functionally for reading the content of a ZIP file inside JavaScript applications. First of all, you need to create a ZipReader object. The ZipReader object helps out the users in reading the content of a ZIP file. The library allows users to read file names, ZIP entries listing, compressed data size, uncompressed data size, last modification date, file comment, uncompressed data checksum and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title"> Writing Files to ZIP via JavaScript</h2>
<p>The ZIP.JS library enables software programmers to write data into the zip file. First of all you need to create a ZipWriter object to write output data. You can easily add a new entry into the ZIP by providing file name and location. Once the task is done the success callback function will inform about the successful entry and compression. In the end please do remember to close the opened zip and terminate the associated web workers.</p>
<h2 class="h2title"> </h2>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}