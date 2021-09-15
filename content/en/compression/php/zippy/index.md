---
title: PHP API - Create, Update & Extract AR, ZIP, TBZ2, TBZ, TGZ Archives
description: Zippy Open Source PHP API allows developers to Create, list, update, extract, delete compression file formats like AR, ZIP, TBZ2, TBZ, TGZ Archives & more.
keywords: PHP ZIP, PHP Compression, compress files, decompress files, ZIP PHP API, PHP compression Library, Open Source PHP Library, PHP Zip programming, create  zip archives, Opening zip archives, Modify ZIP archives, save archive to a file, BZIP2 compression
draft: false
weight: 17



ProductName: Zippy
Githublink: https://github.com/alchemy-fr/Zippy
ListingPage_Short_Description: A PHP implementation for compression file formats gives developers the capability to read, create & extract archives in AR, ZIP, TBZ2, TBZ, and TGZ Formats.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source PHP Library allows developers to Create, List, update, Extract, delete compression file formats Archives via PHP API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="PHP API to Create & Extract  ZIP, TAR, TBZ or TGZ Archives"
Header_H2_Text="Open Source PHP Library allows developers to Create, List, update, Extract, delete compression file formats Archives via PHP API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Zippy is an open source PHP library that provides functionality for working popular archive formats like TAR, ZIP, TBZ2, TBZ, TGZ, and more. The Zippy library is very simple to use and consists of a collection of adapters that helps in the most common compression and decompression operations like create, list update, extract, delete for a selected format. it aims for very high speeds and reasonable compression.</p>
<p>The library supports several important compression related features, such as creating and updating ZIP-archives, open and list an archive's contents, appending files to an existing archive,  BZIP2 compression support, customize file and directory names inside the archive, saving the archive to a file, extract an archive to a specific directory & more.</p>

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
<p>An overview of Zippy features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Generate ZIP-archives</li>
<li>Edit ZIP-archives</li>
<li>Extract archives</li>
<li>Manage AR archive</li>
<li>Manage TBZ2 archive</li>
<li>Manage TBZ archive</li>
<li>Manage TGZ archive</li>
<li>Append File</li>
<li>Extract zip</li>
<li>Set password</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for PHP" />--><header>Zippy</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Zippy supports popular compression file formats listed below.</p>
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
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Zippy </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>PhpZip only requires PHP &gt;= 5.5.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li>PHP &gt;= 5.5</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Zippy </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PhpZip</h2>
<p>First of all, you need to have PHP 5.5 and above to run the library smoothly. The only supported installation method is via Composer. Run the following command to require Zippy in your project.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the command</h3>
<pre><code class="html"> composer require alchemy/zippy<br></code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create a New Archive via PHP API</h2>
<p>Software programmers can easily create a new ZIP archive using the Zippy library inside their own PHP applications. The library supports creating an archive.zip that contains a directory "folder" that can contain different kinds of files. To add a file you need to specify the name of the entry in the archive as well as provide a path. It also provides support for adding a new directory. You can add files to your zip archive one at a time or add the whole directory at once..</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract an Archive to a Specific Directory</h2>
<p>The open source Zippy library provides the capability to programmatically extract an archive to a specific directory using PHP. You can use it to either extract everything inside the archive or just some specific files. Please it is important to remember that it’s required to specify the proper path of the file inside the archive in order to extract it. During the extraction process, the directory and file structure is well-kept and it extracts all files to their respective directories.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Listing Archive's Contents</h2>
<p>The open source Zippy library enables software developers to programmatically open and displays the contents of an archive via PHP commands. The library gives users full control and has provided methods and properties to get more information about the archive before extracting all its contents. You can count the number of files in an archive, iterate over all the files in the archive, extract only those files which are needed, and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Deleting Entries from a ZIP Archive</h2>
<p>The open source Zippy library provides the capability to delete entries from the ZIP archive via PHP commands. There are several options available for deleting the entries, such as delete an entry in the archive using its name, deleting all entries in the ZIP archive, deleting entries using glob pattern and deleting entries using PCRE pattern.</p>

<p> </p>
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}