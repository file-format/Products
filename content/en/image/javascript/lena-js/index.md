---
title: Image Processing JavaScript Library – Apply Effects on Images via Filters
description: lena.js – JavaScript open Source image processing API allows programmers to apply different effects to images using different kinds of filters.
keywords: image processing, Compare PNG Images, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, compare images by ignoring Antialiasing, compare images by ignoring Caret
draft: false
weight: 1



ProductName: LensJs
Githublink: https://github.com/davidsonfellipe/lena.js
ListingPage_Short_Description: A light-weight JavaScript image processing library that enables software developers to apply different types of effects on images using multiple filters.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="JavaScript API for applying different effects to images using different kinds of filters such as gaussian, grayscale, highpass, invert, laplacian, mirror,RGB, Roberts, saturation & more."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="JavaScript API for applying different effects to images using different kinds of filters such as gaussian, grayscale, highpass, invert, laplacian, mirror,RGB, Roberts, saturation & more." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Lena.js a very simple light-weight image processing library that enables software developers to work with different types of images from inside their JavaScript applications. It is a pure JavaScript library that can work on Node as well as in-browser without any external dependencies.  The library is open source and is available under the MIT license. The library is not very good with heavy images inside the browser but is very efficient for the manipulation of small images.</p>
<p>Lena.js is very easy to use and can apply different effects to images. The image filters enable software apps to apply different effects on images with just one click. The library has included support for several important image filters, some important ones are gaussian, grayscale, highpass, invert, laplacian, mirror, noise, prewitt, RGB, Roberts, saturation, sepia, sharpen, and many more. The library also supports applying multiple filters to an image.  The filters are stored in the same global variable LenaJS and can be accessed through its id using the key or dot notation.</p>

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
<p>An overview of Lena.js features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Process images</li>
<li>Image effects</li>
<li>Create image filter</li>
<li>Apply filters</li>
<li>Multiple filters</li>
<li>Gaussian Filter</li>
<li>Grayscale Filter</li>
<li>Highpass Filter</li>
<li>Invert Filter</li>
<li>Sharpen Filter</li>
<li>Sobel Filter</li>
<li>Thresholding Filter</li>
<li>Lowpass 5x5 Filter</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Lena.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Lena.js supports the popular Image file formats listed below.</p>
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
<div class="d1-logo" style="border: none;"><header>Lena.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Lena.js can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Lena.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with LenaJs</h2>
<p>The recommended way to install LenaJs via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Lena.Js via NPM</strong></h3>
<pre><code class="html"> npm install lena.js --save </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Apply Filters on Image via JavaScript</h2>
<p>The open source Lena.js library has provided a set of useful filters that can be used to apply a different kinds of effects to images inside JavaScript applications. First please provide the correct address to the image and then select the filter from the list of available filters. You can use filterImage and redrawCanvas method to easily apply a filter to the selected image. An image and a canvas will be used to apply the filter.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Applying Multiple Filters on Images</h2>
<p>The Lena.js library enables software developers to apply multiple filters on their images inside their own JavaScript apps. Usually, a single filter is applied to an image by filterImage method. To apply multiple filters to an image you need to use the redrawCanvas method instead of filterImage. You need to pass an image already rendered with a filter as the first argument and need pass a new filter as a second argument which will be appended to the image with ease.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Processing Images via JavaScript API</h2>
<p>The LenaJs library gives software programmers the capability to programmatically add filter in images inside JavaScript. Applying filters with LenaJs is pretty simple, the API provides two ways to add filters; filterImage() and redrawCanvas(). You need to provide an image and a canvas to the method to apply filter. In order to get the filter you can user LenaJs['filername'] method and apply it to the image using filterImage() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}