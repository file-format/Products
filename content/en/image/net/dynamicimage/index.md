---
title: fileformat - Open Source APIs for Images - DynamicImage


draft: false
weight: 7



ProductName: DynamicImage
Githublink: https://github.com/tgjones/dynamic-image
ListingPage_Short_Description: An Open Source .NET API that allows developers to manipulate Images using Free .NET API.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Manipulate Images using Free .NET API."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source .NET API for Images"
Header_H2_Text="Manipulate Images using Free .NET API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>DynamicImage is an open source image manipulation API that simplifies dealing with images in ASP.NET applications. DynamicImage uses Windows Presentation Foundation (WPF) internally for bitmap manipulation. Images are composed in the API by using one or more layers. The API provides wide range of filter to be used in the image programatically, each layer of image can have on or more filters.</p>
<p>Furthermore, the API provides other image processing features including blending layers with underneeth layer, create image layer with byte array, apply global filters, use gradient fill, user grayscall image and more.</p>

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
<p>An overview of DynamicImage features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Compose Images</li>
<li>Layers</li>
<li>Filters</li>
<li>Blend Modes</li>
<li>Byte Source Image</li>
<li>Global Filters</li>
<li>Gradient Fill</li>
<li>Grayscall Source Image</li>
<li>Lomo Effect</li>
<li>Indexed Source Image</li>
<li>Positioning</li>
<li>Transparent Source Image</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>ImageResizer</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>ImageResizer supports popular image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://wiki.fileformat.com/image/png/">PNG</a>, <a href="https://wiki.fileformat.com/image/gif/">GIF</a>, <a href="https://wiki.fileformat.com/image/bmp/">BMP</a>      </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>,  <a href="https://wiki.fileformat.com/image/png/">PNG</a>, <a href="https://wiki.fileformat.com/image/gif/">GIF</a>, <a href="https://wiki.fileformat.com/image/bmp/">BMP</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>DynamicImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>DynamicImage requires .NET 4.0 or above..</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>DynamicImage</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with DynamicImage</h2>
<p>The recommended way to install DynamicImage is via NuGet. Please use the following command to install DynamicImage.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">Install-Package DynamicImage</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create Dynamic Image using C#</h2>
<p>DynamicImage API allows creating images programmatically. The API offer two ways create image - using the object model & using a fluent interface. Using object model, you can start by creating a new Compostion() and add layers to it by using compostion.Layers.Add() method. You can your image URL using ImageUrlGenerator.GetImageUrl() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Layers in Images using Free .NET API</h2>
<p>The Open Source API DynamicImage allows adding one more layers in your image. The API provides wide range of layers including Image, Julia Fractal, Mandelbrot Fractal, Polygon Shape, Rectangle Shape, and Text layer. You can easily add layer in your image by using LayerBuilder properties.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Filter in Images using C#</h2>
<p>ImageResizer library allows developers to add filter in your images. Filters can be be applied on one or more layers. You can use as many filters as you like on a single layer. The API provides a bunch of filters, the most common include border, color key, color tint, emboss, grayscale, inversion, outer glow, sepia, solarize and more. You can simply add filter in you layers by using Layers.Filter.Add() method.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}