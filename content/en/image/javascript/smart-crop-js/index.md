---
title: JavaScript Library for Image Processing - Crop Images Smartly
description: SmartCrop.js – open source image processing library that allows Software programmers to crop images smartly via JavaScript Library
keywords: JavaScript Image Processing, Tiny JavaScript Library, Tiny Image Processing Library,  image processing, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, Get color from image, get color, get image color, color, JavaScript Color API, Crop Image, Smart Crop Image
draft: false
weight: 1



ProductName: SmartCrop.js
Githublink: https://github.com/jwagner/smartcrop.js
ListingPage_Short_Description: SmartCrop.js is light-wight JavaScript Image processing API for Cropping Images Smartly.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Open Source API for Cropping Images Smartly"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="Open Source API for Cropping Images Smartly" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is SmartCrop.js?</h2>
<p>SmartCrop.js is free and open-source API that allows JavaScript developer to crop images automatically. The API is content aware and uses set of algorithms to crop images. The API finds edges using the laplace, finds faces by finding regions with color like skin, finds regions with high saturation and processes the image. After finding a specific region, the API boost that region and generates a set of candidate crops.</p>
<p>While cropping the image, you can use HTMLImageElement, HTMLCanvasElement or HTMLVideoElement and set image cropping options including minScale, width, height, boost, and ruleOfThirds.</p>

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
<p>An overview of SmartCrop.js features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Crop</li>
<li>Smart Crop</li>
<li>MinScale</li>
<li>Set Width</li>
<li>Set Height</li>
<li>Boost</li>
<li>RuleOfThirds</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>SmartCrop.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>SmartCrop.js supports the popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>  <a href="https://docs.fileformat.com/image/jpeg/">JPG</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>  <a href="https://docs.fileformat.com/image/jpeg/">JPG</a> </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SmartCrop.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>SmartCrop.js can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>SmartCrop.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with SmartCrop.js</h2>
<p>The recommended way to install SmartCrop.js via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install SmartCrop.js via NPM</strong></h3>
<pre><code class="html"> npm install smartcrop </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Smart Crop Images via Free JavaScript API</h2>
<p>The open source SmartCrop.js library allows JavaScript developers to smart crop images programmatically. Based on the API algorithm, the API finds high saturation areas, finds color with skin tones, and find edges and provides a smart guess to crop the image. In order to smart crop the image, the API provides smartcrop.crop(image, options) method. The method gets and image and image options for the crop. By using the following one line of code, you can easily get an smart crop for your image</p>
<h3>Smart Crop Image in JavaScript</h3>
<ol>
<li>Import Library</li>
<li>Crop Image</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Crop Image in JavaScript</h3>
<pre><code class="c#">smartcrop.crop(image, { width: 100, height: 100 }).then(function(result) {
console.log(result);
});
                        </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}