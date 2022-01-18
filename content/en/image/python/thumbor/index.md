---
title: Image Processing API for Python - Thumbor


draft: false
weight: 21



ProductName: Thumbor
Githublink: https://github.com/thumbor/thumbor
ListingPage_Short_Description: Free Python API that provides On-demand crop, re-sizing and flipping of images.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="On-demand crop, re-sizing and flipping of images"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source Python API for Images"
Header_H2_Text="On-demand crop, re-sizing and flipping of images" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Thumbor is an open source Python API to crop, re-size and flip images. You can access the feature of the API, thumbor offer endpoint to retrive image and image's metadata. Using the API, you can remove the space around the images using the trim functionality, you can add munual corpping functionality is your application using the manual crop feature or you can just fit in the image exactly the size specified.</p>
<p>Furthermore, using the API you can use filters, extract metadata, specify the size of the output image, align image horizontaly and vertically using the API endpoints.</p>

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
<p>An overview of Thumbor features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Resize Image</li>
<li>Flip Image</li>
<li>Add Filters</li>
<li>Trim</li>
<li>Manual Crop</li>
<li>Fit In</li>
<li>Horizontal Align</li>
<li>Vertical Align</li>
<li>Smart Cropping</li>
<li>Extract Metadata</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Thumbor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Thumbor supports popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a>XCF</a>, <a>SVG</a>, <a href="https://docs.fileformat.com/image/png/">PDF</a>, <a>DJUV</a>, <a>WEBM</a>, <a>OGV</a>, <a>STL</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/gif/">GIF</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a>, <a>XCF</a>, <a>SVG</a>, <a href="https://docs.fileformat.com/image/png/">PDF</a>, <a>DJUV</a>, <a>WEBM</a>, <a>OGV</a>, <a>STL</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Thumbor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Thumbor v7.0.0 and later only supports python 3.7+</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Thumbor</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Thumbor</h2>
<p>The recommended way to install thumbor is via Pip. Please use the following command to install thumbor.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pip install thumbor</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manual Cropping in Images via Free Python API</h2>
<p>Using Thumbor API you can the functionality of cropping images manually in your own applications. In order to perform manula cropping, you need to pass two points as arguments seperated by a colon. where the first point is the left-top point of the cropping rectangle and the second point is the right-bottom point. This crop is performed before the rest of the operations, so it can be used as a prepare step before resizing and smart-cropping</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Horizontal and Vertical Image Alignment - Python</h2>
<p>The Open Source image library thumbor allows aligning images horizontaly and vertically. The horizotal align image controls wher the crop of the image will occur. You can use three parametes for the horizotal align feature. Left only the left side, center will trim equally from both side, and the right will only trim form the right. Similarly, while using verticle alignment, top only trims the bottom, center will trim from both top and bottom, and bottom align will trim the image from the top.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Filters in Images via Free Python API</h2>
<p>Thumbor allows pyhton developers to add filters in images programatically. The API runs the filters in in a pipline and each filter is applied on the image in a spcified order. The API provies wide range of filters including, AutoJPG, Background Color, Blur, Brightness, Contrast, Convolution, Equalize, Extract focal points, Filling, Focal, Format, Grayscale, Maxbytes, No upscale, Noise, Proportion, Quality, Red eye, RGB, Rotate, Round Corners, Sharpen, Stretch, Strip EXIF, Strip ICC, and watermark.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}