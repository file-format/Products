---
title: JavaScript Library for Image Processing - Grab Color Platte from Images
description: Color Thief – open source image processing library that allows Software programmers to get color platte from images via JavaScript Library
keywords: JavaScript Image Processing, Tiny JavaScript Library, Tiny Image Processing Library,  image processing, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, Get color from image, get color, get image color, color, JavaScript Color API
draft: false
weight: 1



ProductName: Color Thief
Githublink: https://github.com/lokesh/color-thief
ListingPage_Short_Description: Open source JavaScript API for grabbing color platte from images.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="JavaScript API for grabbing color palette from images."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="JavaScript API for grabbing color palette from images." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Color Thief?</h2>
<p>Color Thief is a very simple lightweight image processing library that enables software developers to grab color from images using JavaScript. It is a pure JavaScript library that can work on Node as well as in-browser without any external dependencies. The API Gets the dominant color from the image. Color is returned as an array of three integers representing red, green, and blue values. While working in the browser, you need to use HTML image for processing and while using the Node you need to use the URL of the image.</p>
<p>The Color Thief package includes multiple distribution files to support different environments and build processes. color-thief.js is the main file for processing the images, color-thief.mjs is used for modern browsers as well as Webpack and Rollup and color-thief.umd.js is used for simple script tag loading.</p>

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
<p>An overview of Color Thief features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Get Color</li>
<li>Get Color Palette(</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Color Thief</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Color Thief supports the popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/jpeg/">JPG</a>,  <a href="https://docs.fileformat.com/image/png/">PNG</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Color Thief</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Color Thief can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Color Thief</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Color Thief</h2>
<p>The recommended way to install Color Thief via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Color Thief via NPM</strong></h3>
<pre><code class="html"> npm i --save colorthief </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Get Colors from Image via Free JavaScript API</h2>
<p>The open-source Color Thief library allows JavaScript developers to extract colors from the images programmatically. In order to get the dominant color from the image, the API provides getColor() method. The method gets the dominant color from the image. Color is returned as an array of three integers representing red, green, and blue (RGB) values. By using the following two lines of code, you can easily get the dominant color from the image.</p>
<h3>Get Dominant Color from Image</h3>
<ol>
<li>Load image</li>
<li>Get color</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract color from the image in Node.js</h3>
<pre><code class="c#">const img = resolve(process.cwd(), 'rainbow.png');

ColorThief.getColor(img)
.then(color =&gt; { console.log(color) })
.catch(err =&gt; { console.log(err) })
               </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Get Color Platte from Image via Free JavaScript API</h2>
<p>Using the API, you can also get color palette from the images In order to get color palette from the image, the API provides getPalette() method. The method gets a palette from the image by clustering similar colors. The palette is returned as an array containing colors, each color itself an array of three integers. By using the following two lines of code, you can easily get color platte from the image.</p>
<h3>Get Color Platte from Image</h3>
<ol>
<li>Load image</li>
<li>Get color platte</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract color platte image in Node.js</h3>
<pre><code class="c#">const img = resolve(process.cwd(), 'rainbow.png');

ColorThief.getPalette(img, 5)
.then(palette =&gt; { console.log(palette) })
.catch(err =&gt; { console.log(err) })
               </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}