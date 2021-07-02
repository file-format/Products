---
title: PHP Library to Manipulate Images – Load, Resize & Convert GIF, PNG, JPEG
description: Gregwar's Image - Open Source free image manipulation PHP library allows programmers to load, crop, negate, sharp, merge colorize, fill and rotate images
keywords: Gregwar's Image, Convert Image Free, Free Image Crop, Rotate Image, Free Image API, Rotate Image, image processing, PHP images, image processing library, PHP PNG API, PHP JPG, PHP image API, PHP Image creation, Modify images, Image filtering API, PHP  fade image , image filtering  API, image animation, 3d image  rendering, plasma effect, PHP Image, Display images, Transform images in PHP
draft: false
weight: 17



ProductName: Gregwar's Image
Githublink: https://github.com/Gregwar/Image
ListingPage_Short_Description: A simple object-oriented image processesing and cahing API.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="PHP Library that enables Software programmers to resize, sharp, merge, colorize, fill and rotate images."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source PHP API to Manipulate Images"
Header_H2_Text="PHP Library that enables Software programmers to resize, sharp, merge, colorize, fill and rotate images." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>The Gregwar's Image is an open source object-oriented library that gives software developers the capability to manipulate images inside their own PHP applications. Using the API, you can resize, scale resize, force resize, crop resize, zoom crop, crop, and negate images. Futhermore, the API also allows you to set brightness, contrast, convert image to grayscale, emboss the image, smooth the image, sharp image, colorize image and more.</p>

<p>The API never applies a feature on an opened image. Instead - The API first caches all the images and then applies the features. The API adds the image in operations array consisting of name, type and you can use the hash to look up for the file in the cache.</p>


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
<p>An overview of Gregwar's Image features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Manipulate image</li>
<li>Resize images</li>
<li>Scale Resize</li>
<li>Force Resize</li>
<li>Crop Resize</li>
<li>Zoom Crop</li>
<li>Crop</li>
<li>Negate</li>
<li>Brightness</li>
<li>Contract</li>
<li>Grayscale</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Gregwar's Image</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Gregwar's Image supports popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>
<a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>, 
<a href="https://wiki.fileformat.com/image/jpeg/">JPG</a>,
<a href="https://wiki.fileformat.com/image/png/">PNG</a>, 
<a href="https://wiki.fileformat.com/image/gif/">GIF</a>
</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> 
<a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>, 
<a href="https://wiki.fileformat.com/image/jpeg/">JPG</a>,
<a href="https://wiki.fileformat.com/image/png/">PNG</a>, 
<a href="https://wiki.fileformat.com/image/gif/">GIF</a>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Gregwar's Image</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Gregwar's Image works with PHP &gt;= 5.2 & above</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>PHP &gt;= 5.2 and above</li>
</ul>
<!--/right--></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Gregwar's Image</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Gregwar's Image</h2>
<p>It requires PHP 5.2+. You can easily install the Gregwar's Image library via composer. Please use the following command.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Gregwar's Image via Composer</strong></h3>
<pre><code class="html">{
    ...
    "require": {
        "gregwar/image": "2.*"
    }
}</code></pre>

<p>Download the <a href="https://github.com/Gregwar/Image/archive/refs/heads/master.zip">zip file</a> from the Github repository. Unpack the zip file and include the files in your project.</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Resize Images via Free PHP API</h2>
<p>The open source Gregwar's Image library has provided support for resizing images inside applications. Using the API, the developer can simply import Gregwar library, open the image, resize it and save it. The resizing process is pretty simple and only requires one line of code. You can open the with open() method and resize it using resize() method.</p>
<h3>Resize Image in PHP</h3>
<ol>
<li>Import Library</li>
<li>Open Image and pass image file path, resize it and provide output image size width and height.</li>
<li>Negate the image colors and save the image</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Resize Image  via Free GO API</h3>
<pre><code class="php">Image::open('fileformat.png')
     ->resize(100, 100)
     ->negate()
     ->save('output.jpg');
     </code></pre>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}