---
title: Open Source APIs for Images - Colourful


draft: false
weight: 8



ProductName: Colourful
Githublink: https://github.com/tompazourek/Colourful
ListingPage_Short_Description: Free .NET library for Working with Color Spaces.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free .NET library for Working with Color Spaces"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source .NET API for Images"
Header_H2_Text="Free .NET library for Working with Color Spaces" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Colourful is an open source library written in C# to manipulate colors in images. The API allows wide range of color manipulating features including Color conversion, Chromatic adaptation, Conversion between RGB working spaces. Colourful also supports computing correlated color temperature (CCT) from chromaticity and computing chromaticity from CCT.</p>
<p>The API has serveral formulas to differentiante between colors furthermore, colourful contains definition of all 24 Macbeth ColorChecker colors in sRGB, which are useful for color calibration.</p>

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
<p>An overview of MetadataExtractor features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Extract Exif</li>
<li>Extract IPTC</li>
<li>Extract XMP</li>
<li>Extract JFIF / JFXX</li>
<li>Extract ICC Profiles</li>
<li>Photoshop fields</li>
<li>WebP properties</li>
<li>Netpbm properties</li>
<li>PNG properties</li>
<li>BMP properties</li>
<li>GIF properties</li>
<li>ICO properties</li>
<li>PCX properties</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>MetadataExtractor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>MetadataExtractor supports popular image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/page-description-language/eps/">EPS</a>, <a href="https://docs.fileformat.com/image/gif/">HEIF</a>, <a href="https://docs.fileformat.com/image/bmp/">HEIC</a>, <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a>JFIF</a>, <a>Netpbm</a>, <a>PCX</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/psd/">PSD</a>, <a>TGA</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a href="https://docs.fileformat.com/image/webp/">WebP</a>, <a>ARW </a>, <a>CR2 </a>, <a>NEF</a>, <a>ORF</a>, <a>RW2 </a>, <a>RWL </a>, <a>SRW </a>  </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>MetadataExtractor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>MetadataExtractor targerts .NET Framework 3.5, 4.5 and .NET Standard 1.3, 2.0.</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>MetadataExtractor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with MetadataExtractor</h2>
<p>The recommended way to install MetadataExtractor is via NuGet. Please use the following command to install MetadataExtractor.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">Install-Package MetadataExtractor</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Metadata from Images using C#</h2>
<p>MetadataExtractor allows extracting wide range of metadata information from images. You can extract all information in image by looping directories and then by looping throught each tag in it. Directory contains metadata type informtion and tag includes the properties. You can extract specific information from images using directories.OfType().FirstOrDefault() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Extract Camera Specific Maker Notes using C#</h2>
<p>The Open Source image processing API MetadataExtractor allows extracting camera-specific makernote for cameras manufactured Canon, Apple, Agfa, Casio, DJI, Epson, Fujifilm, Kodak, Kyocera, Leica, Minolta, Nikon, Olympus, Panasonic, Pentax, Reconyx, Sanyo, Sigma/Foveon and Sony.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}