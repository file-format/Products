---
title: Java Library to Compress, Extract & Compare Large ZIP Archives
description: ZT – ZIP - Open Source Java Archiving Library that enables software developers to Compress, Extract & Compare Large ZIP Archives using Free Java API.
keywords: Java Compression, Java compression API, compress files in Java, decompress files Java,  JAR Java Archive, Java 7-zip, Java GZip library, Java Zip programming, Java RAR Archive, create  ZIP archive, Java compression Library, Open Source Java Library, Add or replace entries in a ZIP archive, Extract a ZIP archive, Check if an entry exists in a ZIP archive, extract an entry from a ZIP archive into a byte array, extract a ZIP archive
draft: false
weight: 10



ProductName: zt-zip
Githublink: https://github.com/thrau/jarchivelib
ListingPage_Short_Description: Open Source Java Archiving Library that enables software developers to compress, extract & compare large ZIP archives.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Java API enables programmers to compress a file or directory into a ZIP archive, comparing two ZIP archives entries & so on."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Java Compression Library for Handling ZIP Archives"
Header_H2_Text="Open Source Java API enables programmers to compress a file or directory into a ZIP archive, comparing two ZIP archives entries & so on." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>zt-zip (ZeroTurnaround ZIP Library) is a simple archiving and compression library for Java that enables software developers to operate with Java archives inside their own apps. The library supports packing and unpacking directories recursively and easily iterate through ZIP entries.  The library is very simple and produces efficient results when only single entries are extracted from ZIP files.</p>
<p>The library has included support for both basic and some advanced features, such as Compress a directory into a ZIP archive, compress a file into a ZIP archive, add an entry from file or byte array to a ZIP archive, replace a ZIP archive entry from file or from a byte array, Add or replace entries in a ZIP archive, Extract a ZIP archive, Check if an entry exists in a ZIP archive, extract an entry from a ZIP archive into a byte array, extract a ZIP archive which becomes a directory and many more.</p>
<p>The library is very safe to use and makes sure that no streams are left open by accident. The library also supports comparing two ZIP archives entries with different names as well as with the same name. You can also easily transform a ZIP archive entry into uppercase. </p>

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
<p>An overview of zt-zip features.</p>
<div class="diagram1 d1-poi">s
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Create ZIP Archive</li>
<li>Extract ZIP file</li>
<li>Check entry</li>
<li>Extract file</li>
<li>Compress directory</li>
<li>Add entry byte array</li>
<li>Add entry from file</li>
<li>Replace file in archive</li>
<li>Delete archive file</li>
<li>Transform ZIP archive</li>
<li>Compare ZIP archive</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>zt-zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>zt-zip supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>ZIP<span style="font-size: 12.16px;">, G</span>ZIP</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/gz/">GZIP</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>zt-zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>zt-zip only requires Java 1.5 & above</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>
<ul>
<li>Java 1.5 & above</li>
</ul>
</header><header> </header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>zt-zip</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with zt-zip</h2>
<p>To run your project using zt-zip, firs of all you need to Java 1.5 & above. Use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install via Git command</h3>
<pre><code class="html"> git clone https://github.com/zeroturnaround/zt-zip.git  <br></code></pre>
<h3>Jarchivelib Maven Dependency</h3>
<pre><code class="html">&lt;dependency&gt;
&lt;groupId&gt;org.zeroturnaround&lt;/groupId&gt;
&lt;artifactId&gt;zt-zip&lt;/artifactId&gt;
&lt;version&gt;1.14&lt;/version&gt;<br>&lt;type&gt;jar&lt;/type&gt;
&lt;dependency&gt;<br></code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compress a File into a ZIP Archive via Java</h2>
<p>The open source zt-zip library has provided functionality for compressing a file into a ZIP archive using Java commands.  The library also provides support for adding a directory into the ZIP archive with ease. The library supports adding an entry from a file to as well as from a byte array to a ZIP archive.  It is also possible to replace an entry in the ZIP archive.  You can also compress a directory into a ZIP archive with a parent directory.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compare Two ZIP Archives via Java API</h2>
<p>The zt-zip library gives software programmers the power to compare two ZIP archives ignoring timestamps of the entries inside their own Java apps. You just need to provide the complete address of the two files. Using the library developers can easily compare two ZIP archive entries with different names as well as with the same names.</p>
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extracting ZIP Archives via Java</h2>
<p>The free zt-zip library allows to programmatically extract files from ZIP archives inside their own apps using a couple of lines of Java code. It has included several important features related unpacking files, such as extract an entry from a ZIP archive into a file or byte array, check if an entry exists or not, extract a ZIP archive which becomes a directory, extract files using name matching pattern and many more.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}