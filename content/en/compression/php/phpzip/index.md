---
title: Open Source PHP Library - Create, Update, Delete & Extract ZIP-Archives
description: PhpZip - Open Source Free PHP Library for working with ZIP-Archives. Create, Update, Open & Extract ZIP-Archives & Password Protected Archives via PHP API.
keywords: Free PHP API, Free ZIP library, PHP ZIP, PHP Compression, compress files, decompress files, ZIP PHP API, PHP compression Library, Open Source PHP Library, PHP Zip programming, create zip archives, Opening zip archives, Modify ZIP archives, save archive to a file, BZIP2 compression, Password Protected Archives
draft: false
weight: 4



ProductName: PhpZip
Githublink: https://github.com/Ne-Lexa/php-zip
ListingPage_Short_Description: PHP API enabling software programmers to work with popular compression file formats from within your own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Create, Update, Delete & Extract Compression File Formats like ZIP or BZIP2 and Password Protected Archives via PHP API."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP Library for Working with ZIP-Archives"
Header_H2_Text="Create, Update, Delete & Extract Compression File Formats like ZIP or BZIP2 and Password Protected Archives via PHP API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>PhpZip is an open source PHP library that provides functionality for working with ZIP-archives. The API generates the Zip file in memory (or temp file) and allows users to save the final Zip file to the users suggested location. It gives you the power to get information about each entry in the archive. It also supports archival comments as well as individual entry comments.</p>
<p>The API supports several important features, such as creating and modifying ZIP-archives, opening and unzipping zip files, appending to existing ZIP, WinZip AES encryption files, BZIP2 compression, external file attributes, and ZIP64 extensions, saving the archive to a file & more.</p>

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
<p>An overview of PhpZip features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create ZIP-archives</li>
<li>Modify ZIP-archives</li>
<li>Unzipping zip files</li>
<li>Append File</li>
<li>Extract zip</li>
<li>AES encryption</li>
<li>BZIP2 compression</li>
<li>ZIP64 extensions</li>
<li>Set password </li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>PhpZip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>PhpZip supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a style="font-size: 12.16px;" href="https://docs.fileformat.com/compression/zip/">ZIP</a><span style="font-size: 12.16px;">, </span><a style="font-size: 12.16px;" href="https://docs.fileformat.com/compression/bz2/">BZIP2</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/bz2/">BZIP2</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>PhpZip</header><footer><small></small></footer></div>
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
<li>PHP &gt;= 5.5 (preferably 64-bit)</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>PhpZip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with PhpZip</h2>
<p>First of all, you need to have PHP 5.5 and above to run the library smoothly. The easiest way to install is to have the <a href="https://getcomposer.org/">Composer</a> installed on your computer. Once the composer is installed you need to add this requirement to your composer.json file.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Here is the command</h3>
<pre><code class="html">"phpzip/phpzip":"&gt;=2.0.7" <br></code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Entries to the Archive via PHP Library</h2>
<p>Software programmers can easily add files to a ZIP archive using PhpZip library inside their own PHP apps. To add a file you need to specify the name of the entry in the archive as well as provide a path. The API also provides the facility to add an entry from the stream to the ZIP archive. It also provides support for adding a new directory.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Delete Entries form the ZIP-Archive</h2>
<p>PhpZip library provides a feature for deleting entries from the ZIP archive. There are several options available for deleting the entries, such as delete an entry in the archive using its name, deleting all entries in the ZIP archive, deleting entries using glob pattern and deleting entries using PCRE pattern.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Working with Password Protected Archives</h2>
<p>PhpZip library provides support for traditional deflate compression and BZIP2 compression with the extension php-bz2. PhpZip library requires PHP 5.5 & above to work with password-protected archives. It facilities developers to set a password for reading all or some entries in the archive, change the password for the archive, delete the archive password, Set password or encryption method and may other options.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}