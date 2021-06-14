---
title: Open Source C Library - Create, Edit, Delete & Extract ZIP Archives
description: Open Source Free C zip Library – software developers can create, List, update, Extract, delete files fron ZIP Archives via C API.
keywords: Free ZIP library, C ZIP, C Compression, compress files, decompress files, ZIP C API, PHP compression Library, Open Source C Library, C Zip programming, create  zip archives, Opening zip archives, Modify ZIP archives, save archive to a file, List zip archive
draft: false
weight: 11



ProductName: zip
Githublink: https://github.com/kuba--/zip
ListingPage_Short_Description: Free C library that enables software programmers to create, list, modify & extract ZIP Archives insisde their own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="zip"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="C API for Compression File Formats & zip archive"
Header_H2_Text="" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The open source portable ZIP library is written in C language that enables software developers to create and modify the ZIP archive.  The library is written on top of the miniz library and layering functions on top of the miniz v1.15 API. The interface of the library is extremely simple and that’s why there will be no problems for users to understand it. Several advanced ZIP compression and extraction related features are fully supported by the library, such as creating new ZIP archive with default compression level, append to the existing ZIP archive, extracting ZIP archive into a folder, extract a ZIP entry into memory,  extract a ZIP entry into a file,  list of all zip, extract an archive to a specific directory & many more.</p>

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
<li>Create ZIP-archives</li>
<li>Modify ZIP-archives</li>
<li>Unzipping ZIP files</li>
<li>Extract ZIP archive</li>
<li>Append File</li>
<li>Extract specific entry</li>
<li>List of ZIP archive</li>
<li>Extract ZIP</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHP Compression API"><header>zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>zip supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>ZIP</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>ZIP</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHP Compression API"><header>zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>There are two ways to install zip, i.e. via CMake or manually by downloading the library.</p>
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
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="PHP Compression API"><header>zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with zip</h2>
<p>It is recommended to build the library, via CMake. You can get it from <a href="http://www.cmake.org/cmake/resources/software.html">CMake web site</a> . Please use the following command to Compile zip library.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Compile zip library as a dynamic library</h3>
<pre><code class="html">$ mkdir build
$ cd build
$ cmake -DBUILD_SHARED_LIBS=true ..
$ make<br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate New Archive via C Library</h2>
<p>The zip library provides software developers the capability to generate a new zip archive with default compression level inside their own applications. It also allows to modify an existing zip archive with ease. You can easily add new files or can select and extract a file to the location of your choice.  To add a file to archive users requires specifying the name of the file as well as providing the complete path.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extracting Content from ZIP Archive</h2>
<p>The open source zip library allows programmers to easily extract the contents of an archive into a folder with just a couple of C commands. It provides functionality for either extracting everything inside the archive or just some specific files. For best results please always provide a complete path of the file inside the archive in order to extract it.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">More Control over ZIP Archive</h2>
<p>The zip library provides several important features for better control over the contents of a ZIP archive. Several methods and properties are available that can help users to get complete information about the archive before extracting its contents. It supports features like count the number of files in an archive, iterate through all the files in an archive, extracts only selected files, removing files from an archive and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}