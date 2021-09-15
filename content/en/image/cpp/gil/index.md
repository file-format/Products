---
title: Open Source C++ Generic Image Library - Generate Histogram & Gradients
description: Boost.GIL - open Source C++ generic library that abstracts image representations from algorithms. It generates histogram, image gradients, convolution & resampling.
keywords: image processing,  C++ images, image processing library, C++ PNG API, C++ JPG, C++ image API,  C++ Image creation, draw a circle on an image, copy an image, paint an image into another image, draw a line on an image, cast an image, cache an image, add two images, make a gaussian image, read a point from an image, Modify images, Image filtering API, C++  fade image , image filtering  API, image animation, 3d image  rendering, plasma effect
draft: false
weight: 36



ProductName: Boost.GIL
Githublink: https://github.com/boostorg/gil
ListingPage_Short_Description: C++ API that abstracts image representations from algorithms and supports generate a Histogram, image gradients, convolution & resampling and so on.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Boost.GIL"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source C++ Generic Image Library"
Header_H2_Text="C++ API that abstracts image representations from algorithms and supports working with simple and complex images. Generate a Histogram, compute image gradients, convolution & resampling, and so on." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Images are the fundamental part of many projects related to graphics, digital video, computer vision, and image processing. Moreover, images can be represented in many different ways (color space, bit depth, channel order, alignment policy, etc.). So working on a new image related project that can be generic as well as efficient is very challenging.  Boost Generic Image Library (GIL) is an open source library that gives software developers the capability to work with simple and complex images inside from their own C++ applications.</p>
<p>The great thing about the Boost.GIL  library is that it abstracts image representations from algorithms and allows writing code that can work on a variety of images with performance comparable to hand-writing for a particular image type. So it makes developer's jobs easy by allowing them to write code once and having it work for any image type.</p>
<p>The Boost.GIL library is designed as an STL and Boost compliment.  Another great aspect of the library is speed and flexibility. Speed has been the key part of the design of the library. You can easily define any image parameter at run time for a very minor performance cost as compared to many other libraries. It provides support for several important features such as non-byte-aligned pixels, computing image gradients, Boost integration, assign a channel to a gray-scale pixel, convolution & resampling, and so on.</p>

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
<p>An overview of Boost.GIL features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Feature Overview</header>
<ul>
<li>Handle images</li>
<li>Boost compliment</li>
<li>Image encoding</li>
<li>Image scaling,</li>
<li>Image rotation</li>
<li>Image cloning</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Feature Overview</header>
<ul>
<li>Read images</li>
<li>Write images</li>
<li>Display images</li>
<li>Draw text</li>
<li>Pixel-Level support</li>
<li>Image resizing </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Boost.GIL"><header>Boost.GIL</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Boost.GIL supports several important image file formats.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>JPEG, PNG, TIFF,  GIF, PDF, BMP, PNM, PS</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/png/">PNG</a>,<a href="https://docs.fileformat.com/image/jpeg/"> JPEG</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Boost.GIL"><header>Boost.GIL</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>ImageSharp only requires C++ installed. The library source code is currently being modernized for C++11.</p>
<p> </p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><!-- <header><i class="fa fa-cubes"> &nbsp;</i></header>
    <ul>
    <li>Python 2.6 & above</li>
    </ul> --></div>
<!--/left--> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Boost.GIL"><header>Boost.GIL</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Boost.GIL</h2>
<p>The easiest way to install Boost.GIL is by using GitHub. Please use the following command for a smooth installation</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Boost.GILvia GitHub.</strong></h3>
<pre><code class="html">git clone --https://github.com/boostorg/gil</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Reading and writing images</h2>
<p>Histogram is the graphical representation of the tonal distribution in a digital image. In the image processing context, the histogram of an image normally refers to a histogram of the pixel intensity values. The Boost.GIL library enables software developers to generate a histogram inside their own application using C++ code. It can be generated by counting the number of pixel values that fall in each bin. You can also compute the luminosity histogram of the image with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Pixel-Level Image Operations using C++ API</h2>
<p>The open source library Boost.GIL has provided complete support for pixel-level image operations inside their own C++ applications. The library has included some useful operations that enable users to handle pixel values, pixel pointers, and pixel references, such as making a pixel colored,  accessing a channel, comparing the two channels,  constructing const planar pointer, converting gray l-value to RGB, and so on.</p>
<h2 class="h2title">Resize Image Canvas using C++</h2>
<p>The open source library Leptonica has provided support for rotating images inside their own C applications. There are numerous ways for achieving the image rotation operation, such as rotation by shear, rotation by area mapping, special rotations by 90, 180 or 270 degrees, rotation by either 2 or 3 shear, and many more.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}