---
title: Open Source Swift image API - Create, Edit, Resize, Crop & Load Image
description: SwiftGD - Open source swift image Processing library to Create, Edit, Resize, Crop & Load Image on Server-side. Manipulate images, Draw shapes & add Image effects
keywords: Open Source Swift APIs, image processing API,  Swift image creation, image processing library, Swift PNG API, Swift JPG, Swift image API,  Swift Image creation, Modify images, Image filtering API, Swift JPG, Swift image API, Swift Image creation, draw a circle on an image, copy an image, paint an image into another image, draw a line on an image, cast an image, cache an image, add two images
draft: false
weight: 1



ProductName: SwiftGD
Githublink: https://github.com/twostraws/swiftgd
ListingPage_Short_Description: A small size wonderful Swif library that has included support for server-side Swift image creation, editing, manipulation & much more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Swift Library for included support for image loading, saving, and manipulating. It allows image creation with custom width and height, image resizing & cropping a specific part of the image"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Swift API for server-Side Image Processing"
Header_H2_Text="Swift Library for included support for image loading, saving, and manipulating. It allows image creation with custom width and height, image resizing & cropping a specific part of the image" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>SwiftGD is a small size wonderful library that has included support for server-side Swift image manipulation.  It a fantastic Swift wrapper for libgd, allowing the creation of images and draw shapes in places where Core Graphics functionality isn’t available. The library is very simple to use and can easily handle image loading, saving, and manipulating using Swift code.  One great feature of the library is that it manages GD resources for users, so the underlying memory is released when the images are destroyed.</p>
<p>The library is has included support for several important features related to image handling such as PNGs & JPEGs loading from disk, PNGs & JPEGs images saving to disk, image creation with custom width and height, image resizing support, cropping a specific part of the image, drawing shapes and lines, color filing from coordinates, horizontal or vertical image flipping, image stroking support, drawing or text filling and many more. The library has also included several important effects such as pixelate, blur, colorize, de-saturate, and so on. . The library is open source and is available under the   MIT License.</p>

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
<p>An overview of SwiftGD features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Create images</li>
<li>Edit Images</li>
<li>Process images</li>
<li>Image effects</li>
<li>Apply filters</li>
<li>Multiple filters</li>
<li>draw shapes</li>
<li>Gaussian blur</li>
<li>Image tint</li>
<li>Render Image</li>
<li>Flip images</li>
<li>image reading </li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>SwiftGD</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>SwiftGD supports the popular Image file formats listed below.</p>
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
<li> <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, GIF</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SwiftGD</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>SwiftGD only requires Swift to be installed.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Swift</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SwiftGD</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with SwiftGD</h2>
<p>Clone the latest sources using the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install </strong>SwiftGD<strong> via Github </strong></h3>
<pre><code class="html"> $ git clone https://github.com/twostraws/SwiftGD.git</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Creating New Images using Swift</h2>
<p>The open source Swift library SwiftGD enables software developers to create new images with just a couple of lines of Swift code. Developers can easily create an image from scratch by providing the width and height of the image. It also supports creating images from data instances.  It also generates Images while users perform a resize or crop operation, which means the original image will be untouched.  You can also apply some basic effects on images with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Shapes Drawing using Swift</h2>
<p>The SwiftGD library makes it easy for software developers to draw and manipulate shapes inside their Swift applications. The library has provided several methods that can be used to draw into your images, such as apply flood fill from one point to the other,  drawing a line from one point to the other, pixel setting a specific point, fills an ellipse at the center, drawing an empty ellipse at the center, empty rectangle drawing from one side to the other and so on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Manipulation inside Swift Apps</h2>
<p>The open source Swift library SwiftGD allows computer programmers to manipulate images with ease inside Swift apps. The library has provided several methods which can be used to apply effects to images such as applying a Gaussian blur effect, applies image tint, renders your image grayscale, flips your image horizontally as well as vertically, simplifies your image to large pixels, and much more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Images Loading & Reading</h2>
<p>The free Swift library SwiftGD gives software apps the capability to load and read images inside their own Swift apps. You need to provide the location of the image on the disk for successful loading. The file extension is used by the library for loading the correct file format, so it's important you name your files with "jpg", "jpeg", or "png".</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}