---
title: Open Source C Library - Create, Edit, Delete & Extract ZIP Archives
description: Libzip - Open Source Free C compression Library – software developers can create, List, update, Extract, delete files from ZIP Archives via C API.
keywords: Free ZIP library, C ZIP, C Compression, compress files, decompress files, ZIP C API, PHP compression Library, Open Source C Library, C Zip programming, create  zip archives, Opening zip archives, Modify ZIP archives, save archive to a file, List zip archive
draft: false
weight: 12



ProductName: libzip
Githublink: https://github.com/nih-at/libzip
ListingPage_Short_Description: Free C API that allows to create, read & manipulate popular compression file formats like ZIP or ZIP64 Archives.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source C Library to Create, Edit, Delete & Extract ZIP Archives inside your own apps. "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="C Library for Managing Compression File Formats"
Header_H2_Text="Open Source C Library to Create, Edit, Delete & Extract ZIP Archives inside your own apps. " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Libzip is an open source C library that gives software developers the capability to create and modify ZIP archives inside their own applications with minimum effort. The developers can easily add files from data buffers as well as different files, or compressed data copied directly from other zip archives. It also supports to revert changes made without closing the archive. Moreover, the library also supports encryption and decryption of Winzip AES and legacy PKware.</p>
<p>The API is well documented and can be easily accessed.  The API provides complete support for several advanced compression and extraction related features for ZIP and ZIP64 archives, such as adding a file to or replacing the file in a ZIP archive, adding a directory to a ZIP archive, delete a file from a ZIP archive, file encryption, and decryption support, last modification time, open file in a ZIP archive for reading, write data to zip source & many more.</p>
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
<div class="d1-logo" style="border: none;">  <!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>libzip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>libzip supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, ZIP64</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>ZIP, ZIP64</li>
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
<p>libzip only requires C<i class="fa fa-cubes"> run-time</i></p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<ul>
<li class="d1-col d1-left"> C</li>
</ul>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>libzip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with libzip</h2>
<p>CMake is highly recommended to build the libzip library. You can get it from the <a href="https://cmake.org">cmake</a> website easily.</p>
<p>A typical installation code is given below</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Compile zip Library for Basic Usage</h3>
<pre><code class="html">mkdir build
cd build
cmake ..
make
make test
make install <br></code></pre>

<p>You can also install libzip manually; download the latest release files directly from <a href="https://github.com/nih-at/libzip.git">GitHub</a> repository.</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add or Replace File in a ZIP archive</h2>
<p>Managing a ZIP archive in their own applications is always the demand of IT companies as well as individuals. The libzip library provides these features facility to the computer programmers by allowing them to add a file to ZIP archive as well as replace or delete files in an existing ZIP archive with ease. The available methods are very user friendly and you require just a couple of lines of code to achieve this task.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create a New Archive via C Library</h2>
<p>The libzip library allows developers to generate a new zip archive inside their own C applications. You can also modify an existing ZIP archive by adding or editing files inside it.  The library gives complete control to users by allowing them to view a list of files inside the ZIP archive, delete a directory or file in a ZIP archive, open or close files, and many more.</p>
<h2 class="h2title">Read and Extract Files in a ZIP Archive</h2>
<p>The open source libzip library facilitates users to easily read and extract the contents of a ZIP archive. The library supports extracting files and folders into a place of your choice with just a couple of lines of C code. The library provides supports for extracting the complete data inside the archive as well as extracting specific files of your choice.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">More Control over ZIP Archive</h2>
<p>The zip library provides several important features for better control over the contents of a ZIP archive. Several methods and properties are available that can help users to get complete information about the archive before extracting its contents. It supports features like count the number of files in an archive, iterate through all the files in an archive, extracts only selected files, removing files from an archive, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}