---
title: PHP Library to Manipulate Images – Load, Resize & Convert GIF, PNG, JPEG
description: WideImage- open Source free image manipulation PHP library allows programmers to load, manipulate & save images in GIF, PNG, JPEG, BMP, GD and GD2 formats.
keywords: image processing, PHP images, image processing library, PHP PNG API, PHP JPG, PHP image API, PHP Image creation, Modify images, Image filtering API, PHP fade image , image filtering API, image animation, 3d image rendering, plasma effect, PHP Image Binarization, Display images, Transform images in PHP
draft: false
weight: 17



ProductName: WideImage
Githublink: https://github.com/smottt/WideImage
ListingPage_Short_Description: A stable PHP API that provides support for manipulating image file formats like PNG, JPEG, BMP, TIFF & more..
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHP Library that enables Software programmers to Load, Resize & Convert GIF, PNG, JPEG images with ease."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source PHP API to Manipulate Images"
Header_H2_Text="PHP Library that enables Software programmers to Load, Resize & Convert GIF, PNG, JPEG images with ease." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The WideImage is an open source object-oriented library that gives software developers the capability to manipulate images inside their own PHP applications. The library provides a simple way of loading, manipulating, and saving images in the most common image formats. The library supports features like resizing image, cropping, merging, writing a text with a shadow, convert to other formats, image cloning, apply watermark on the image, and many more.</p>
<p>The library currently includes support for some of the most common image file formats which are natively supported by the GD extension on the server such as GIF, PNG, JPG, GD, GD2, WBMP, XBM, XPM). It also supports BMP (read/write) and TGA (read-only). The library supports cross-format conversion. Developers can easily load an image in the format of their choice and then can save in any other supported image file formats.</p>
<p>The library uses GD extension to carry out most of the supported operations on images. The GD extension doesn’t support some functions and few are performing slow as they are coded in pure PHP. The WideImage team has worked hard to optimize the library code and have updated the GD functions to improve performance.</p>

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
<p>An overview of WideImage features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Manipulate image</li>
<li>Save images</li>
<li>Resize images</li>
<li>Cropping images</li>
<li>Copy image</li>
<li>Edit images</li>
<li>Image cloning</li>
<li>Apply watermark</li>
<li>Save to browser</li>
<li>Display images</li>
<li>Draw text </li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>WideImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>WideImage supports popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>
<a href="https://docs.fileformat.com/image/gif/">GIF</a>,
<a href="https://docs.fileformat.com/image/png/">PNG</a>,
<a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>,
<a href="https://docs.fileformat.com/image/bmp/">BMP</a>,
<a href="https://docs.fileformat.com/image/tga/">TGA</a>, 
GD, GD2 </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, 
<a href="https://docs.fileformat.com/image/png/">PNG</a>, 
<a href="https://docs.fileformat.com/image/bmp/">BMP</a>, 
<a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, GD, GD2</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>WideImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>WideImage works with PHP &gt;= 5.3 & above</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<p>PHP &gt;= 5.2 and above.<p>
</ul>
<!--/right--></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>WideImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with WideImage</h2>
<p>It requires PHP 5.2+ with GD2 extension. You can easily install the WideImage library via PEAR. Please use the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install WideImage via PEAR</strong></h3>
<pre><code class="html">pear channel-discover pear.kozak.si
pear install kozak.si/WideImage </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Saving Images to Other Formats via PHP</h2>
<p>The open source WideImage library has provided support for saving images to a file, directly to a browser, or can retrieve an image data as a string inside your own apps. To save to a file you need to pass the file name and its path as a parameter. While saving to JPEG or PNG, you can set the quality of the image for JPEG, and compression level for PNG. While retrieving as a string, you can effortlessly capture image data and save it to a database or file. You can also save the image directly to the browser. You need to pass the image type parameter and it will be saved in the suggested format.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Loading Images via PHP API</h2>
<p>The WideImage API allows software programmers to load an image of their choice with ease inside their own PHP application. The library provided several options for loading images, such as loading an image from a file, by providing a URL, from a binary string or from a valid GD image resource. You need to provide a complete file path and image name. The binary string option is useful when required to load images from a database.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Resizing and Cropping</h2>
<p>The free library WideImage has provided functionality for resizing or cropping images using PHP commands. You need to provide the new dimensions of the image. If one dimension is provided and the other isn’t specified (or null is given), the library smartly calculated it from the ratio of the other dimension. For operations like resizing and cropping where the coordinates are passed as parameters, the smart coordinates option is useful.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}