---
title: Open Source Image Processing Go Library to Create Edit & Convert Image
description: bimg – Open Sourc e Go API that allows images rotation, Fit images,  zoom the image, embed or extend an image, add blur effects to an image, and much more.
keywords: image processing, Go images, image processing library, Go PNG API, Go JPG, Go image API, Go Image creation, Modify images, Image filtering API, Go  fade image , image filtering  API, image animation, 3d image  rendering, plasma effect
draft: false
weight: 30



ProductName: bimg
Githublink: https://github.com/h2non/bimg
ListingPage_Short_Description:  A Free high-level Image processing Go library for programmatically read and manipulate images.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Go API that allows images rotation, Fit images, image thumbnails creation, zoom the image, embed or extend an image, add blur effects to an image, and much more."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source High-Level Image Processing Go library"
Header_H2_Text="Go API that allows images rotation, Fit images, image thumbnails creation, zoom the image, embed or extend an image, add blur effects to an image, and much more." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>bimg is an open source high-level image processing Go library that provides the capability for reading and manipulating images with just a couple lines of Go code.  The library is smaller in size but produces very well-organized and efficient results. The library is very fast as compare to other available libraries that require very small memory to complete the task.</p>
<p>The bimg is a high-level C library that is built on top of the libvips which is a very powerful library for processing images. It provides support for reading some very popular image file formats like JPEG, PNG, WEBP, TIFF, PDF, GIF, and SVG, etc. You can also easily export images to JPEG, PNG, WEBP formats as well as to transparent images. </p>
<p>The bimg library has included support for several important image processing features such as resizing images, enlarge the image,  image cropping including smart crop support, flip or rotate images, create image thumbnails, image zooming support, add watermark and Gaussian blur effect, extract specific area from an image, trim images, image conversion to other formats and many more.</p>

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
<p>An overview of bimg features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Generate image</li>
<li>Manipulate image</li>
<li>Save images</li>
<li>Resize images</li>
<li>Crop images</li>
<li>Copy image</li>
<li>Image cloning</li>
<li>Apply watermark</li>
<li>Save to browser</li>
<li>Display images</li>
<li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>bimg</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>bimg supports popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>JPEG, PNG, WEBP, TIFF, PDF, GIF, SVG</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://wiki.fileformat.com/image/png/">PNG</a>, WEBP</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>bimg</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>bimg can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Go 1.3+</li>
<li><a href="https://github.com/libvips/libvips">libvips</a>3+</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>bimg</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with bimg</h2>
<p>The easiest and recommend way to install bimg is via GitHub. Download the <a href="https://github.com/h2non/bimg/archive/master.zip">zip file</a> from the Github repository. Unpack the zip file and include the files in your project.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install bimg via GitHub</strong></h3>
<pre><code class="html"> go get -u gopkg.in/h2non/bimg.v1</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Conversion to Other Formats via Go</h2>
<p>The open source bimg library enables software developers to programmatically convert images to other supported file formats with just couple of lines of Go code. Let’s suppose you have an in JPEG format and you want to convert it to PNG. You need to provide image information like image name, address, and conversion format. The image will be successfully converted to the suggested format with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Crop or Resize Images</h2>
<p>The free bimg library gives software developers the capability to resize as well as crop their images inside their own Go applications. You need to provide the width and height of the new image and location as well.  It also supports forcing resize operation without preserving the aspect ratio. You can also add text and extract the area of your choice from an image. Crop crops the image to the exact size specified.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Adding Watermarks to Images</h2>
<p>The bimg API has included functionality for adding watermark to image inside Go applications with ease. Adding Watermark is a very useful feature for protecting your images. Watermarking is the easiest and very useful way for protecting your photos on the internet. You can easily place a logo or text watermark. The library helps you to programmatically add watermark to your image on any selected position as well as the opacity.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Flip and Rotate Images</h2>
<p>The open source bimg library gives software developers the capability to rotate their images according to their needs using Go language commands. There is a method for automatic image rotation. The AutoRotate function automatically rotates the image with no additional transformation based on the EXIF orientation metadata, if available. It also provides support for flip or flop images, image Interpretation, image length, image metadata and many more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}