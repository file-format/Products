---
title: Swift Image Processing Library – Resize, Rotate, Flip & Iterate Images
description: SwiftImage - Open Source Swift Library for image processing. It allows to Resize, Rotate, Flip or Iterate Images & access pixels of the images and modify them
keywords: Open Source Swift APIs, image processing API,  Swift image creation, image processing library, Swift PNG API, Swift JPG, Swift image API,  Swift Image creation, Modify images, Image filtering API, Swift JPG, Swift image API, Swift Image creation, draw a circle on an image, copy an image, paint an image into another image, draw a line on an image, cast an image, cache an image, add two images, Modify images, Image filtering API
draft: false
weight: 1



ProductName: SwiftImage
Githublink: https://github.com/koher/swift-image
ListingPage_Short_Description: A Swift Library for image processing. It allows to Resize, Rotate, Flip or Iterate Images & access pixels of the images and modify them.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free Swift API provides the capability to handle image processing tasks such as  images rotation, flipping and resizing images, cropping image, image conversion to other format, and many more"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Swift Library for Image Processing"
Header_H2_Text="Free Swift API provides the capability to handle image processing tasks such as  images rotation, flipping and resizing images, cropping image, image conversion to other format, and many more" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>SwiftImage is a very powerful Swift image processing open source library that enables software developers to work with different kinds of images using Swift code.  The library can easily access pixels of the images and modify them according to as required.  It is a high-performance e <em>image library</em> that gives developers the capability to download, cache, and process <em>images</em> with ease</p>
<p>The SwiftImage library is very stable as well as feature-rich and has included several important features for handling their images such as rotating images, flipping and resizing images, image cropping, image conversion to other formats, applying filters and image Binarization, and many more. The library is very powerful and can convert a RGBA image to Grayscale with just one-liner code.</p>
<p>One great feature of SwiftImage library is that it supports the copy-on-write process that’s why image instances can never be shared and defensive copying is unnecessary.  The library uses Image with the RGBA type which is a generic type and represents various formats of pixels.  The library also supports gray-scale images without nested parameters. It supports both 8-bit and 16-bit Grayscale images.</p>

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
<p>An overview of SwiftImage features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Convert images</li>
<li>Rotating images</li>
<li>Modify Images</li>
<li>Image effects</li>
<li>flipping Images</li>
<li>Apply filters</li>
<li>Gaussian blur</li>
<li>Resizing images</li>
<li>Cropping images</li>
<li>image reading </li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>SwiftImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>SwiftImage supports the popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li> JPEG,  PNG, BMP, GIF</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://wiki.fileformat.com/image/png/">PNG</a>, <a href="https://wiki.fileformat.com/image/bmp/">BMP</a>, GIF</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SwiftImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>SwiftImage only requires Swift to be installed.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Swift</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SwiftImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with SwiftImage</h2>
<p>You can easily install SwiftImage is using Swift Package Manager. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install SwiftImage </strong><strong>via Github </strong></h3>
<pre><code class="html"> .package(url: "https://github.com/koher/swift-image.git", from: "0.7.0"),</code></pre>

<p>You easily download the <a href="https://github.com/koher/swift-image/archive/refs/heads/master.zip">zip file</a> from the Github repository. Unpack the zip file and include the files in your project or Clone the latest sources using the following command.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Resizing via Swift</h2>
<p>The open source SwiftImage library gives software developers the capability to resize images inside their own Swift applications with a couple of lines of code. The library makes it easy for software developers to load and resize images using several important functions such as resize an image by providing width & height,  crop an image to custom size,  apply a filter to an image, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Rotate, Flip or iterate Images via Swift API</h2>
<p>The SwiftImage library has provided complete support for programmatically rotating as well as Flipping images using Swift commands.  Developers can use different available functions to flip the image, such as flipping images horizontally as well as vertically. Developers can also flip as well as iterate images according to their own needs and save it back on disk at the place of their choice.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Filtering Support via Swift</h2>
<p><em>Image</em> <em>filtering</em> is a very useful technique that helps developers to modify or enhance images<em> with ease. </em>The open source SwiftImage library has provided different types of very useful filters that can be applied to images to enhance their properties inside Swift applications.  The library supports several important filters such as mean filter, Gaussian filter, enhanced edges, blur images, image brightness, and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}