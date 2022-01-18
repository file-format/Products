---
title: JavaScript Library for Image Processing - Get image size without full download
description: Probe-Image-Size – open source image processing library that allows Software programmers to get image size with downloading image via JavaScript Library
keywords: JavaScript Image Processing, Tiny JavaScript Library, Tiny Image Processing Library, image processing, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, Get color from image, get color, get image color, color, JavaScript Color API, Get Image Size, Size, Image Size
draft: false
weight: 1



ProductName: Probe-Image-Size
Githublink: https://github.com/nodeca/probe-image-size
ListingPage_Short_Description: Open-source JavaScript Image Processing API to get image size without fully downloading the image.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Get image size without full download."
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="Get image size without full download." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Probe-Image-Size?</h2>
<p>Probe-Image-Size is a free and open-source API that allows JavaScript developer to get the image size of the image without actually downloading the image. The API is small in size and works with remote and local data without any heavy dependencies. The API is effective with large images, reduces memory, increases processing speed and downloads minimal data from the remote. In the output data, the API provides the width and height of the image before any transformations like orientation and cropping are applied.</p>
<p>The API currently supports getting file size of JPEG, GIF, PNG, WebP, BMP, TIFF, SVG, PSD, ICO, AVIF, HEIC and HEIF. Formats like JPEG & TIFF can store size anywhere. Always provide full file content to sync methods, if you want to guarantee the file size.</p>

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
<p>An overview of Probe-Image-Size features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Get Image Size</li>
<li>Width</li>
<li>Height</li>
<li>Length</li>
<li>Type</li>
<li>Mime</li>
<li>wUnits</li>
<li>hUnits</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Probe-Image-Size</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Probe-Image-Size supports the popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/webp/">WebP</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a href="https://docs.fileformat.com/image/ico/">ICO</a>, <a href="https://docs.fileformat.com/image/avif/">AVIF</a>, <a href="https://docs.fileformat.com/image/heic/">HEIC</a>,</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Probe-Image-Size</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Probe-Image-Size can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript</li>
<li>stream.js</li>
<li>http.js</li>
<li>sync.js</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Probe-Image-Size</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Probe-Image-Size</h2>
<p>The recommended way to install Probe-Image-Size via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Probe-Image-Size via NPM</strong></h3>
<pre><code class="html"> npm install probe-image-size </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Get Image Size via Free JavaScript API</h2>
<p>The open source Probe-Image-Size library allows JavaScript developers get size of the image without downloading it. In order to get size of the image, the API provides probe() method. The method gets source image and options for image processing. By using the following code, you can easily get size of your image without downloading it</p>
<h3>Get Size of Image without Downloading</h3>
<ol>
<li>Import Library</li>
<li>Get Image Size</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Get Image Size in JavaScript</h3>
<pre><code class="c#">const probe = require('probe-image-size');
// get by URL
let result = await probe('http://example.com/image.jpg');
      </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}