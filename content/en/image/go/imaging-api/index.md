---
title: Free Go API - Resize, Crop & Rotate JPEG, PNG, GIF, TIFF & BMP Images
description: Imaging - Open Source Go API that allows to resize, crop & rotate JPEG, PNG, GIF, TIFF & BMP Images. Adjust image brightness, contrast, gamma correction.
keywords: image processing, Go images, image processing library, Go PNG API, Go JPG, Go image API, Go Image creation, Modify images, Image filtering API, Go  fade image , image filtering  API, image animation, 3d image  rendering, plasma effect
draft: false
weight: 31



ProductName: Imaging
Githublink: https://github.com/disintegration/imaging
ListingPage_Short_Description:  A powerful open source library that provides complete functionality related to image creation and manipulation.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Powerful Go API that supports Resize, Crop & Rotate JPEG, PNG, GIF, TIFF, and BMP Images. You can also adjust image brightness, contrast, gamma correction of the images."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Image Creation & Manipulation"
Header_H2_Text="Powerful Go API that supports Resize, Crop & Rotate JPEG, PNG, GIF, TIFF, and BMP Images. You can also adjust image brightness, contrast, gamma correction of the images." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The open source Go Imaging API is a very powerful package that provides complete functionality related to image creation and manipulation. The library is very flexible and allows developers to easily create new images and modify existing ones with just a couple of lines of code.</p>
<p>The Imaging is a pure Go library that is small in size and efficient in functionality. It has included support for several important image file formats like JPEG, PNG, GIF, TIFF, BMP, and many more.  The library has also included several resampling filters for image resizing. Some important filters are NearestNeighbor, Lanczos, CatmullRom, MitchellNetravali, Linear, Box, and so on. The library has also facilitated developers to create custom filters.</p>
<p>The free Imaging library has included several important features relates to image processing, such as resizing image, image rotation, image cropping, adjust image brightness, image contrast adjustments, gamma correction of the images, changing the saturation of the image, clone images, image blur, encode and decode images,  image overlay, add sharpness, create thumbnail and many other features.</p>

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
<p>An overview of Imaging features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Manipulate image</li>
<li>Resize images</li>
<li>Cropping images</li>
<li>Copy image</li>
<li>Gamma correction</li>
<li>Modify images</li>
<li>Image cloning</li>
<li>Apply watermark</li>
<li>Change saturation</li>
<li>Display images</li>
<li>Draw text</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Imaging</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Imaging supports popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li> JPEG,  PNG, BMP, TIFF, GIF</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>imaginary</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>imaging can be used in multiple environments like Node or browsers etc.</p>
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
<div class="d1-logo" style="border: none;"><header>imaginary</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Imaging</h2>
<p>The easiest and recommended way to install Imagingis via GitHub. Download the <a href="https://github.com/disintegration/imaging/archive/master.zip">zip file</a> from the Github repository. Unpack the zip file and include the files in your project.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Imaging via GitHub</strong></h3>
<pre><code class="html">go get -u github.com/disintegration/imaging</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate New Image via Go API</h2>
<p>The open source imaging library has included support for generating new images inside their own application using Go commands. The new image creation requires image width, height, background color of the image, and output format of the image.  You can also easily modify the created image and perform different operations like flip, setting opacity, blend, blur, and much more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Conversion to Other Formats via Go</h2>
<p>Software developers can easily convert their images to other supported file formats inside their own GO Apps using a free imaging library.  You just need to provide the image name and the output image format.  Using the Save function you can easily export the images to several other supported image file formats such as PNG, BMP, GIF, JPEG, TIFF, and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Resize and Crop Images</h2>
<p>The Free imaging API has included functionality for resizing images according to your needs using Go commands. First, you need to open an image and provide height as well as the width of the image to resize it. Another option is that you can resize the image by just provide width by preserving the aspect ratio. The library also allows cropping the original image by provided custom width, height, and using the center anchor.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Flip, Rotate, Blur & Clone Images</h2>
<p>The Imaging library has included several important features for image manipulation such as image flipping, image rotation, blurring, and cloning. To make a copy of an existing image you just need to call the Clone function and provide the existing image. The library also supports rotating and flipping your image with just a couple of lines of code. You can easily rotate an image by the given angle counter-clockwise. The angle parameter is the rotation angle in degrees.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}