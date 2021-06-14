---
title: Open Source C++ Image Library – Faster Parallel Image Processing
description: Video++ - Free Open Source C++ image library for faster parallel images processing and manipulation. It enhanced set of image processing algorithms using C++ APIs.
keywords: image processing,  C++ images, image processing library, C++ PNG API, C++ JPG, C++ image API,  C++ Image creation, draw a circle on an image, copy an image, paint an image into another image, draw a line on an image, cast an image, cache an image, add two images, make a gaussian image, read a point from an image, Modify images, Image filtering API, C++  fade image , image filtering  API, image animation, 3d image  rendering, plasma effect
draft: false
weight: 38



ProductName: Video++
Githublink: https://github.com/matt-42/vpp
ListingPage_Short_Description: Free C++ image library for faster parallel images processing and manipulation. It also enhanced set of image processing algorithms & more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Free C++ API that supports generic N-dimensional image containers, enhanced set of image processing algorithms, and so on."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source  C++ Library for Parallel Image Processing "
Header_H2_Text="Free C++ API that supports generic N-dimensional image containers, enhanced set of image processing algorithms, and so on." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Video++ is a powerful multi-threaded and cross-platform C++ image editing API that enables software developers to work with images and video files inside their own C++ applications. The library is very easy to handle and is developed taking advantage of the new features of C++11/C++14. The main idea behind Video++ is to redesign from scratch an image processing framework taking advantage of the new C++ standard.</p>
<p> One great feature of the Video++ library is the easy definition of parallel image processing kernels which run up to 32 times faster than the naïve non-optimized version. The library has included several important features such as generic N-dimensional image containers, enhanced set of image processing algorithms, fill color, better memory management, fill border, use of 3D sub-images, and many more.</p>
<p>The library has provided a useful feature of accessing the image containers which offer access to the pixel buffer and to another piece of information useful to process the image.  It also provides interoperability to openCV and supports explicit conversions to and from OpenCV image types.</p>

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
<p>An overview of Video++ features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Open image</li>
<li>Image containers</li>
<li>Modify image </li>
<li>Access pixels</li>
<li>Add to image</li>
<li>Parallel processing</li>
<li><span style="font-size: 12.16px;">Evaluate Image expressions</span></li>
</ul>
</div>
<!--/left--></div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Video++</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Video++ supports popular image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>PNG, JPEG, BMP, TIFF</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/image/png/">PNG</a>,<a href="https://wiki.fileformat.com/image/jpeg/"> JPEG</a>, <a href="https://wiki.fileformat.com/image/bmp/">BMP</a>, <a href="https://wiki.fileformat.com/image/tiff/">TIFF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Image APIs for C++" />--><header>Video++</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Video++ can work with any C++ based programming language</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>C++11 or higher</li>
</ul>
</div>
<!--/left--><!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Video++</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Video++</h2>
<p>You can easily install Vireo is using <a href="https://github.com/matt-42/vpp/archive/master.zip">GitHub</a>. Please use the following command for a complete installation. The Video++ is header-only so to access all the necessary features, you must include vpp.h header.  You also require to get Eigen3 and Boost on your system before install Video++.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install OpenImageIO via git command</strong></h3>
<pre><code class="html"> git clone https://github.com/matt-42/vpp.git
cd vpp
./install.sh your_install_prefix # Install iod and vpp in a given prefix
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<p><code class="html"></code></p>
<h2 class="h2title">Parallel Image Processing via C++ Library</h2>
<p>The open source Video++ library allows software developers to define kernels for processing parallel images using C++ commands. The great thing is that the kernels can run 32 times faster than normal ones. It equally spread the execution of kernels over all available CPU cores running several threads running on several cores. It supports features like filling border with value, fill border mirror, set the alignment, access image pixels, apply filters on images and so on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Addition via C++</h2>
<p>The open source Video++ library has provided complete functionality for adding images using pixel wise filter. It offers a set of generic objects and routines that allow writing efficient implementations of simple filters quickly.  Many image processing filters are simple functions that fill pixels with computed values, thus featuring no dependencies between computations regarding different pixels.</p>

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