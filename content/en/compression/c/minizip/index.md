---
title: Open Source C compression Library to Create Password Protected ZIP Archives
description: Minizip allows developer to create password protected ZIP archives, add or remove files from ZIP archives via C API
keywords: Free ZIP library, C ZIP, C Compression, compress files, decompress files, ZIP C API, PHP compression Library, Open Source C Library, C Zip programming, create zip archives, Opening zip archives, Modify ZIP archives, save archive to a file, List zip archive, password protected ZIP archives
draft: false
weight: 14



ProductName: Minizip
Githublink: https://github.com/nmoinvaz/minizip
ListingPage_Short_Description: Free C API that enables software developers to create and modify new ZIP archives, manage password protected ZIP archives, add/remove files in archives & more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Free C Library to Generate, Modify, Remove, or Extract ZIP Archives, Add/Remove Files inside your own apps."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Create & Modify Password Protected ZIP Archives via C Library"
Header_H2_Text="Open Source Free C Library to Generate, Modify, Remove, or Extract ZIP Archives, Add/Remove Files inside your own apps." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Minizip is an open source C library that facilitates software programmers to work with zip archives inside their own C applications. The Minizip library is stable and is one of the better and easier to use. It always used Deflate compression when adding files to the archive. Minizip is a pure C library that can be used on Windows, macOS, and Linux with ease. The library also supports PKWARE and WinZIP AES encryption and decryption.</p>
<p>The Minizip API provides complete support for numerous advanced compression and extraction related features for ZIP archives, such as creating and extracting zip archives, add or remove entries from zip archives, read and write zip archives from memory, password protection, buffered streaming support, splitting zip archives into multiple files, Unicode via through UTF-8 encoding, character encoding support, Follow and store symbolic links and many more.</p>


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
<p>An overview of Minizip features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Create Archives</li>
<li>Access Archives</li>
<li>Edit Archives</li>
<li>Create Password Protect Archives</li>
<li>Extract Password Protect Archives</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"> <!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Minizip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Minizip supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>ZIP, ZIP64</li>
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
<p>Minizip only requires C run-time</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<ul>
<li class="d1-col d1-left"> C</li>
</ul>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Minizip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Minizip</h2>
<p>CMake is highly recommended to build the Minizip library. You can get it from the <a href="https://cmake.org">cmake</a> website easily.</p>
<p>A typical installation code is given below</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Build Minizip Library from CMake</h3>
<pre><code class="html">cmake . -DMZ_BUILD_TEST=ON
cmake --build <br></code></pre>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create New ZIP Archive via C Library</h2>
<p>The Free Minizip library provides functionality for generating a new ZIP archive inside C applications. The compression library also supports editing an existing ZIP archive by inserting or deleting files inside it. You can easily display the list of all available files inside the ZIP archive. You can also open, modify, close, or delete a directory or file in the ZIP archive with just a couple of simple C commands.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Password Protected Archives Handling</h2>
<p>The open source Minizip library provides the capability to handle password-protected ZIP archives with ease. It provides set of features that allows software developers to protect their archives by setting a password, allowing reading all or some entries in the archive, alter the password for the archive, remove archive password, Set encryption & decryption methods and much more.</p>
<h2 class="h2title">Add or Remove Files from ZIP archive</h2>
<p>The open source Minizip library supports inserting files into a ZIP archive with just a couple of lines of code. The library also facilitates programmer to replace or delete files in an existing ZIP archive with ease. The available methods are user friendly and you require just a couple of lines of code to achieve this task. The library also supports Unicode filename through UTF-8 encoding.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Files from ZIP Archives to Disk</h2>
<p>The open source Minizip library enables computer programmers to read and extract the contents of an archive with ease. You can easily extract files and folders into a place of your choice on the disk. It also gives you the ability to extract complete data of an archive as well as extracting some particular files. The library also provides the ability to generate and verify CMS signature for each entry.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}