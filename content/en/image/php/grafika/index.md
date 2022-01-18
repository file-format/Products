---
title: Image Processing PHP Library – Compare Images & Apply Advance Filters
description: Grafika - image processing PHP open Source library allows programmers to compare Images, apply smart crop & Advance Filters or image blending with ease.
keywords: image processing, PHP images, image processing library, PHP PNG API, PHP JPG, PHP image API, PHP Image creation, Modify images, Image filtering API, PHP fade image , image filtering API, image animation, 3d image rendering, plasma effect, PHP Image Binarization, Display images, Transform images in PHP
draft: false
weight: 16



ProductName: Grafika
Githublink: https://github.com/kosinix/grafika
ListingPage_Short_Description: A powerful PHP image processing library that gives software Engineers the ability to compare Images, apply smart crop & advance filters and much more inside their own apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source PHP API includes support for image comparison, smart cropping, image blending, GIF animation, 5 resize modes, and many more."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="PHP Library for Comparing Images & Advanced Filters"
Header_H2_Text="Open Source PHP API includes support for image comparison, smart cropping, image blending, GIF animation, 5 resize modes, and many more." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Grafika is easy to use and powerful image processing PHP library that is blended with some unique features enabling software developers to create and manipulate their images and graphics inside their PHP applications. Grafika is based on Imagick and GD, so there is no need to worry about the differences between GD and Imagick API, Grafika normalizes these operations for you and makes your job easy.</p>
<p>The Grafika library has provided support for basic as well as several advance image creation and processing features. The library can be used to generate image thumbnails quickly and having high quality. The library has also included support for intelligent tailoring as well as image attribute processing with just a couple of lines of code.</p>
<p>The Grafika library contains some advanced features that make it unique from other available PHP libraries, such as applying smart cropping, compare images, advance filters, image blending, animated GIF support, 5 resize modes and more. It has also included support for some common features like image cloning, create blank images, make a copy of the image, apply watermark on the image, and many more.&lt;</p>

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
<p>An overview of Grafika features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Create editors</li>
<li>Creating images</li>
<li>Resizing images</li>
<li>Compare images</li>
<li>Smart crop</li>
<li>Animated GIF</li>
<li>Copy image</li>
<li>Edit images</li>
<li>Image cloning</li>
<li>Apply watermark</li>
<li>Display images</li>
<li>Image compression</li>
<li>Draw text</li>
<li>Image effect</li>
<li>Image encoding</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Grafika</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Grafika supports popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>,
<a href="https://docs.fileformat.com/image/png/">PNG</a>,
<a href="https://docs.fileformat.com/image/bmp/">BMP</a>,
<a href="https://docs.fileformat.com/image/tiff/">TIFF</a> 
</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"></i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>,
<a href="https://docs.fileformat.com/image/png/">PNG</a>,
<a href="https://docs.fileformat.com/image/bmp/">BMP</a>,
<a href="https://docs.fileformat.com/image/tiff/">TIFF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Grafika</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Grafika works with PHP &gt;= 5.3 & above</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Grafika</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Grafika</h2>
<p>The recommended way to install Grafika is via <a href="https://packagist.org/packages/imagecow/imagecow">Composer</a>. Inside your project directory, open the command line and type the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Grafika via composer</strong></h3>
<pre><code class="html">$ composer require kosinix/grafika:dev-master --prefer-dist</code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Images Creation via PHP APIs</h2>
<p>The open source Grafika library allows software developers to generate different kinds of images inside their own PHP application with a couple of lines of code. The most common way of making an image is by using the editor's open method. You easily create a blank image as well as create a copy of an image using the clone keyword inside your code. Moreover, you can also blend, fill, flip, set opacity as well as resize and crop images with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Compare Images inside PHP Apps</h2>
<p>The Grafika library gives software programmers the power to programmatically compare their images inside their own apps. It can compare the similarity between two images as well as gives you the ability to determine if the two images are equal or not. The great thing is that it can do a pixel by pixel comparison to determine if two images are exactly the same. It will compare if the two images are of the same width and height. If the dimensions differ, it will return false. If the dimensions are equal, it will loop through each pixel. If one of the pixels don't match, it will return false. The pixels are compared using their RGB (Red, Green, Blue) values.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Smart Image Cropping</h2>
<p>Image cropping is the removal of undesirable areas from a photographic or image. Cropping can be used to make the image size reduced or change the aspect ratio of an available image. The Grafika library has included features for basic as well as smart cropping via PHP. The smart cropping feature is useful and where the library decides the crop position with the important regions of the images preserved.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Animated GIF Support</h2>
<p>The animated GIFs are animated images that are most commonly used on the internet because of their simple creation and smaller file size which allows faster upload time. The Grafika has included limited support for animated GIFs. It allows resizing animated GIFs either on GD or Imagick and preserving its animation during the resizing process. It also supports flattening an animated GIF which means that the GIF will be converted to just a regular GIF and the animation will be removed.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}