---
title: C# .NET Library for Zip, GZip, Tar & BZip2 Compression File Formats
description: SharpZipLib - Open Source Free C# .NET Library for Compression File Formats. Create & extract Zip, GZip, TAR & BZip2 compression files using .NET API.
keywords: Free compression API, Free ZIP library, C# Free API, Csharp Compress, .NET compression, compress files, decompress files, Rar .NET API, .NET 7-zip, .NET GZip library, .NET compression Library, Open Source .NET Library, .NET Zip programming, .NET Rar APIs, .NET Tar, create zip file
draft: false
weight: 2



ProductName: SharpZipLib
Githublink: https://github.com/icsharpcode/SharpZipLib
ListingPage_Short_Description: .NET API enabling software programmers to work with Archive formats like ZIP, GZIP, TAR & BZIP2 from .NET applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source Free .NET API for file Archive formats like ZIP, GZIP, TAR & BZIP2."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="C# .NET Library for Compression File Formats"
Header_H2_Text="Open Source Free .NET API for file Archive formats like ZIP, GZIP, TAR & BZIP2." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>SharpZipLib library is written entirely in C# for the .NET platform. It is implemented as an assembly and so you can incorporate it into other projects (in any .NET language).</p>
<p>It was originally ported from the GNU Classpath java.util.zip library so it could be used with SharpDevelop, which needed GZIP & ZIP compression. Later due to high user's demand, the BZIP2 and Tar archiving were also included in the library.</p>

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
<p>An overview of SharpZipLib features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create ZiP</li>
<li>Extract ZIP</li>
<li>Create TAR</li>
<li>Tar extraction</li>
<li>Create BZIP2</li>
<li>Create GZIP</li>
<li>Unzip files</li>
<li>Untar files</li>
<li>Unbzip2 files</li>
<li>Ungzip files </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>SharpZipLib</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>SharpZipLib supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a style="font-size: 12.16px;" href="https://docs.fileformat.com/compression/zip/">ZIP</a><span style="font-size: 12.16px;">, </span><a style="font-size: 12.16px;" href="https://docs.fileformat.com/compression/tar/">TAR</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/compression/zip/">ZIP</a>, <a href="https://docs.fileformat.com/compression/tar/">TAR</a>, <a href="https://docs.fileformat.com/compression/bz2/">BZIP2</a>, <a href="https://docs.fileformat.com/compression/gz/">GZIP</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SharpZipLib</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>SharpZipLib only requires .NET Framework.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>.NET Framework 4.5 & above</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>SharpZipLib</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with SharpZipLib</h2>
<p>You need to have .NET Framework 4.5 or above in order to configure SharpZipLib. Once you have the met the prerequisites, you can manually download the repository from <a href="https://github.com/adamhathcock/sharpcompress">GitHub</a> or directly fetch the assembly from the NuGet.</p>
<p>The recommended way to install SharpZipLib is from NuGet as it is available as a <a href="https://www.nuget.org/packages/SharpZipLib/">NuGet Package</a>. </p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install SharpZipLib from NuGet</h3>
<pre><code class="html"> Install-Package SharpZipLib</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">NET Library to Create & Extract ZIP Files</h2>
<p>SharpZipLib enables software developers to create a ZIP file inside their own .NET applications. Developers can easily compress all the files available inside a directory and assign them into a single zip file. ZIP is one of the most popular compression file format and gives users the facility to reduce the size of files. The API also supports extracting content of ZIP file to a place of user’s choice</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract files from ZIP - C#</h3>
<pre><code class="c#">// Open zip file
using (Stream fsInput = File.OpenRead("D:\\input.zip"))
using (var zf = new ZipFile(fsInput))
{
 // Set password if required
 zf.Password ="12345";
 // Unzip data
 foreach (ZipEntry zipEntry in zf)
 {
  if (!zipEntry.IsFile)
  {
   // Ignore directories
   continue;
  }
  String entryFileName = zipEntry.Name;
  var directoryName ="D:\\output\\test";
  if (directoryName.Length &gt; 0)
  {
   Directory.CreateDirectory(directoryName);
  }
  var buffer = new byte[4096];
  using (var zipStream = zf.GetInputStream(zipEntry))
  using (Stream fsOutput = File.Create("data.zip"))
  {
   StreamUtils.Copy(zipStream, fsOutput, buffer);
  }
 }
}
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create a Password Protected ZIP File</h2>
<p>SharpZipLib gives software developers the ability to compress all the files inside a folder into a ZIP file and define a password for the created files. If you want to create ZIP files without protection please set its value to null or don’t declare it to leave the file without any password protection. It supports large number of files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create a password protected ZIP file - C#</h3>
<pre><code class="java">// Create a new ZIP file 
using (FileStream fsOut = File.Create("D:\\output.zip"))
using (var zipStream = new ZipOutputStream(fsOut))
{
 //0-9, 9 being the highest level of compression
 zipStream.SetLevel(3);
 // Set password
 zipStream.Password ="12345";
 // Add files
 var files = Directory.GetFiles("D:\\sample");
 foreach (var filename in files)
 {
  var fi = new FileInfo(filename);
  // Make the name in zip based on the folder
  var entryName = filename.Substring(1);
  // Remove drive from name and fixe slash direction
  entryName = ZipEntry.CleanName(entryName);
  var newEntry = new ZipEntry(entryName);
  // Note the zip format stores 2 second granularity
  newEntry.DateTime = fi.LastWriteTime;
  newEntry.Size = fi.Length;
  zipStream.PutNextEntry(newEntry);
  var buffer = new byte[4096];
  using (FileStream fsInput = File.OpenRead(filename))
  {
   StreamUtils.Copy(fsInput, zipStream, buffer);
  }
  zipStream.CloseEntry();
 }

}
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}