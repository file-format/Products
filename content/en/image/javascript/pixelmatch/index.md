---
title: JavaScript Image Comparison Library – Compare Images for Differences
description: pixel match – open source Fast Pixel-level Image Comparison library that allows programmers to compare images multiple environments like Node or browsers. 

draft: false
weight: 26



ProductName: pixelmatch
Githublink: https://github.com/mapbox/pixelmatch
ListingPage_Short_Description: A JavaScript implementation for comparing two images in any environment. It supports working with popular image file formats like PNG, JPEG, BMP, TIFF & more.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="JavaScript Library enables Software programmers to compare two images in multiple environments like Node or browsers etc."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source JavaScript API to Compare Images"
Header_H2_Text="JavaScript Library enables Software programmers to compare two images in multiple environments like Node or browsers etc." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Sometimes it is required to compare two images to see how similar they are. It is a very complicated process and required good knowledge to accomplish it. The open source pixelmatch library can be a very useful choice for comparing two images in any environment.  As the library has no dependencies and works on raw typed arrays of image data, so can be used in multiple environments like Node or browsers, etc.</p>
<p>The pixelmatch is very small in size and very simple to use but is a very fast pixel-level image comparison library. It is written in JavaScript and initially created to compare screenshots in tests. The library supports features like anti-aliased pixels detection and perceptual color difference metrics.</p>
<p>The Anti-aliasing detection is a very useful feature because usually it has been observed that rendering the same data on different applications, devices, or operating systems can generate slightly dissimilar results. But mostly it is recommended to ignore these small differences or tests to capture more meaningful data.</p>

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
<p>An overview of pixelmatch features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Compare images</li>
<li>Check dimensions</li>
<li>Anti-aliasing detection</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>pixelmatch</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>pixelmatch supports popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>GIF, PNG, JPEG, BMP</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li> <a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://wiki.fileformat.com/image/png/">PNG</a>, <a href="https://wiki.fileformat.com/image/bmp/">BMP</a>, <a href="https://wiki.fileformat.com/image/tiff/">TIFF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>pixelmatch</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>pixelmatch can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>pixelmatch</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with pixelmatch</h2>
<p>The recommended way to install pixelmatch is via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install pixelmatch via NPM</strong></h3>
<pre><code class="html"> npm install pixelmatch </code></pre>

<p>Download the <a href="https://github.com/mapbox/pixelmatch/archive/master.zip">zip file</a> from the Github repository. Unpack the zip file and include the files in your project.</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">What is Pixel Match Testing?</h2>
<p>If you need to compare two images to check if there is any difference between then you can use pixel match testing for this purpose. There can be two types of images, the original image, and the <em>modified</em> <em>image</em>. You can use an application that can fetch images from the screenshot of your app and after that, the image comparison library can be used to compare these images and display the results.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Comparing Images via JavaScript Library</h2>
<p>The open source library pixelmatch has provided complete functionality for comparing images inside JavaScript application with ease.  Software developers need to provide images data for comparing as well as the output place where it needs to write the image data with the differences. They also need to provide the dimension which is the width and height of the three images. You can use the threshold option that allows the images to be slightly different, which can be great in some cases. Please note that pixelmatch library needs that image must be of the same sizes.</p>

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