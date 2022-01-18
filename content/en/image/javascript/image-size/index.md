---
title: JavaScript Library for Image Processing - JavaScript API for detecting image dimensions
description: Image Size – Open source image processing library that allows detecting image dimensions
keywords: JavaScript Image Processing, Tiny JavaScript Library, Tiny Image Processing Library, image processing, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, Get color from image, get color, get image color, color, JavaScript Color API
draft: false
weight: 1



ProductName: Image-Size
Githublink: https://github.com/image-size/image-size
ListingPage_Short_Description: Open-source JavaScript Image Processing API for for detecting image dimensions programmatically.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="JavaScript API for detecting image dimensions"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="JavaScript API for detecting image dimensions" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Image-Size?</h2>
<p>Image-Size is a simple light-weight image processing library that enables software developers to get dimensions of images at run time. The API supports a wide range of image formats and you can get dimensions of most of the popular file formats using the API. The API provides a synchronous and asynchronous method for working with the images. The asynchronous functions have a default concurrency limit of 100 and in order to change this limit, you can manually change concurrency. Furthermore, the asynchronous version doesn't work if the input is a Buffer and you'll have to use the asynchronous method instead.</p>

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
<p>An overview of Image-Size features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Get Image Dimensions</li>
<li>Synchronous</li>
<li>Asynchronous</li>
<li>Multi-size Images</li>
<li>Get Dimensions using URL</li>
<li>Disabling certain image types</li>
<li>Disabling all file-system reads</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Image-Size</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Image-Size supports the popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/ico/">CUR</a>, <a href="#">DDS</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a>, <a href="https://docs.fileformat.com/image/ico/">ICNS</a>, <a href="https://docs.fileformat.com/image/ico/">ICO</a>, <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="#">KTX</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="#">PNM</a>, <a href="https://docs.fileformat.com/image/psd/">PSD</a>, <a href="https://docs.fileformat.com/page-description-language/svg/">SVG</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a href="https://docs.fileformat.com/image/webp/">WebP </a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Image-Size</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Image-Size can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Image-Size</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Image-Size</h2>
<p>The recommended way to install Image-Size via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Image-Size Thief via NPM</strong></h3>
<pre><code class="html"> npm install image-size --global </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Get Image Dimensions via Free JavaScript API</h2>
<p>The open-source Image-Size library allows JavaScript developers to get dimensions of the images programmatically. In order to get dimensions from an image, the API provides sizeOf() method. By using the following two lines of code, you can easily get the dimensions of the image.</p>
<h3>Get Image Dimensions</h3>
<ol>
<li>Load Image-Size Library</li>
<li>Get dimensions using sizeOf() method and pass image path as string</li>
<li>Get width of image using dimensions.width and height using dimensions.height</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Get image dimensions in JavaScript</h3>
<pre><code class="c#">const sizeOf = require('image-size')
const dimensions = sizeOf('images/funny-cats.png')
console.log(dimensions.width, dimensions.height)
    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}