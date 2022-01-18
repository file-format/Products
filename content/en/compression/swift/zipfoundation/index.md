---
title: Zip/Unzip Files & Directories in ZIP Archives via Free Swift Library
description: ZIP Foundation - open source Swift compression library to zip or unzip archives, create, read, edit ZIP archive, adding or deleting files in Swift Apps.
keywords: Free ZIP library, Swift ZIP, Swift Compression, compress files, decompress files, ZIP Swift API, Swift compression Library, Open Source Swift Library, Swift Zip programming, create zip archives, Opening zip archives, Modify ZIP archives, save archive to a file, List zip archive, password protected ZIP archives
draft: false
weight: 1



ProductName: ZIP Foundation
Githublink: https://github.com/weichsel/ZIPFoundation
ListingPage_Short_Description: ZIP foundation is a Swift library that can effortlessly handle ZIP archive files. It has included functionality for compression and decompression with high performance and stability
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="ZIP Foundation"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Swift Library to Create ZIP archives"
Header_H2_Text="" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>ZIP file is a compressed archive that makes it easier for users to reduce size of large files or groups of <em>files</em> to send, share and store them with ease. The ZIP foundation is a Swift library that can effortlessly handle ZIP archive files. The library is based on Apple’s libcompression and handles encoding or decoding of compressed archives with ease. The library has included functionality for compression and decompression with high performance and stability. The library is open source and is available under the MIT license for public use.</p>
<p>The ZIP Foundation is a easy to use and well-maintained documentation section. The Swift enables software developers to create, read and update ZIP archive files with just couple of lines of code. The great thing about the library is that it has no 3rd party dependencies and provides easy to use high-level methods. The library has included several important features related to ZIP archives, such as zipping files or directories, access individual entries, create a new archive, access individual entries, add a new entry, remove a particular entry, better memory management, and so on.</p>

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
<p>An overview of ZIP Foundation features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header>Overview</header>
<ul>
<li>Zipping files</li>
<li>Zip directories</li>
<li>Unzipping data</li>
<li>Zip specific files</li>
<li>Create ZIP-archives</li>
<li>Modify ZIP-archives</li>
<li>Add a file</li>
<li>Remove a file</li>
<li>Progress updates</li>
<li>Error handling</li>
<li>In-memory archive</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Swift Compression API"><header>ZIP Foundation</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>ZIP Foundation supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>ZIP</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Swift Compression API"><header>ZIP Foundation</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>ZIP Foundation only requires Swift runtime for smooth working.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i>Mandatory</header>
<ul>
<li>Swift</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Swift Compression API"><header>ZIP Foundation</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with ZIP Foundation</h2>
<p>You can easily install ZIP Foundation from CocoaPods. Please use the following command for installing the project on your system.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Compile ZIP Foundation library via CocoaPods</h3>
<pre><code class="html"> $ pod install</code></pre>

<p>You can easily install ZIP Foundation library from GitHub. Please use the following command for creating clone of the project on your system.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Zip Files & Directories via Swift Library</h2>
<p>The open source ZIP Foundation library enables software developers to zip different kinds of files or directories using Swift code. For zipping a single file you just need to pass a file URL representing the item you want to zip and a destination URL. By default, no compression is used in archive creation. You can also create a compressed ZIP archive by setting the parameter to set to .deflate. Same like files it also accepts the directory items and adds the directory content to the archive with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add or Remove Individual Entries</h2>
<p>It’s often required to access or read some specific entries in a ZIP archive with extracting the whole archive. The ZIP Foundation helps Software developers individually access specific entries and use them according to their own needs. It also facilitates programmers to incrementally update archive contents. Programmers can easily add a new file to an existing archive or replace or delete a file in an existing ZIP archive with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Process In-Memory Archives</h2>
<p>The open source ZIP Foundation library supports handling in-memory archives using Swift commands. That means the library supports the creation or the extraction of the archives that only exist inside the RAM. You can easily read as well as update the in-memory archive with just a couple of lines of code. It also allows consuming ZIP entry contents without writing them to the file system.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}