---
title: C++ Image Processing Library – Apply Image Filtering & Rendering
description: CImg - open Source C++ image processing library allows programmers to apply image filtering, render, create, edit & manipulate formats like PNG, JPEG, BMP & TIFF.
keywords: image processing, C++ images, image processing library, C++ PNG API, C++ JPG, C++ image API, C++ Image creation, Modify images, Image filtering API, C++ fade image , image filtering API, image animation, 3d image rendering, plasma effect, C++ Image Binarization
draft: false
weight: 1



ProductName: CImg
Githublink: https://github.com/dtschump/CImg
ListingPage_Short_Description: C++ implementation of the Image File Formats. It supports working with popular image file formats like PNG, JPEG, BMP, TIFF & more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apply Image Filters, Create, Manipulate & Render Popular Images file formats using Free C++ API."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source C++ Library for Image Processing"
Header_H2_Text="Apply Image Filters, Create, Manipulate & Render Popular Images file formats using Free C++ API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>CImg Library is an open source library that provides useful features for loading, saving, displaying and processing various types of images inside C++ applications. The CImg is a lightweight and user-friendly library. The good thing is that it avoids handling complex dependencies and library compatibility issues. It is made of a single header file CImg.h that must be included in your C++ source. It helps developers by performing complex image processing activities in just a few lines of code.</p>
<p>The API supports advanced features like handling 3D images, Transform images, image filtering, image animation, Image Binarization and more. CImg library is portable & self-contained. It is can be easily used on different operating systems with ease. Moreover, it’s also compatible with <em>numerous C++ compilers such as </em>Visual C++, ICC, G++, etc.</p>

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
<p>An overview of CImg features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Image creation</li>
<li>Modify images</li>
<li>Image filtering</li>
<li>Fade image</li>
<li>image filtering</li>
<li>image animation</li>
<li>3d rendering</li>
<li>plasma effect</li>
<li>Image Binarization</li>
<li>Display images</li>
<li>Transform images</li>
</ul>
</div>
<!--/left--></div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>CImg</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>CImg supports popular image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/image/png/">PNG</a>,<a href="https://docs.fileformat.com/image/jpeg/"> JPEG</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, TGA, DICOM</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/png/">PNG</a>,<a href="https://docs.fileformat.com/image/jpeg/"> JPEG</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>CImg</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>CImg can work with any C++ based programming language</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li>C++</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>CImg</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with CImg</h2>
<p>The CImg Library is available as .zip package which is platform-independent. It contains all the required files, along with various examples, which shows how to use the library functions and classes.</p>
<p>You need to add these two lines in your C++ source code, in order to be able to work with CImg.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Add these lines for CImg working</strong></h3>
<pre><code class="html"> #include"CImg.h" 
using namespace cimg_library </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">C++ API to Create & Modify Images</h2>
<p>CImg open-source library allows C++ developers to create and manipulate different types of images inside their own applications. It also supports how to handle image display and mouse events. First of all, you need to include the main and only header files of the CImg library. The good thing is the library reduces the developer's load by allowing them to write a small amount of code. Please also note that the source will perfectly work on UNIX and Windows systems.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Image Filtering Support</h2>
<p>CImg library provides support for the image filtering process. Sometimes we need to retrieve information about images and that’s where Image filtering is commonly used. The image filtering process is one of the most common methods to apply to images to retrieving information. Mostly, filters are used in image noise removal, computer image derivatives, image edge enhancement, Shape analysis and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}