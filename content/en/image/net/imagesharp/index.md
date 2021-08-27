---
title: Open Source C# .NET Library for 2D Graphics – Create & Resize Images
description: ImageSharp is a Cross-Platform C# .NET Library for processing 2D graphics. Developers can read, write, modify, resize & convert PNG, JPEG, GIF & TIFF Images.
keywords: .NET Imaging, .NET imae library, image processing,  C# images, image processing library, C# PNG API, C# JPG, C# image API,  C# Image creation, Modify images, Image filtering API, C#  fade image , image filtering  API, image animation, C# 3d image  rendering, plasma effect, C# resize Image
draft: false
weight: 3



ProductName: ImageSharp  
Githublink: https://github.com/SixLabors/ImageSharp
ListingPage_Short_Description: It provides the capability to perform simple and advanced image creation and manipulation inside .NET apps.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="ImageSharp"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source C# .NET Library for 2D Graphics"
Header_H2_Text="Read, Write, Modify, Resize & Convert PNG, JPEG, GIF & TIFF Images using .NET API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>ImageSharp is a simple yet very powerful cross-platform open source library for the processing of image files inside C# applications. It is a fully managed and cross-platform 2D graphics API designed to permit the processing of images. ImageSharp is an open source image processing library that was released with the goal of providing an alternative to the System.Drawing APIs.</p>
<p>This API is comprehensive and supports advanced algorithms for image processing. The API is improved year by year to provide support for more advanced image processing. Its only dependency is .NET itself, which makes it extremely portable. The API has included support for advanced features like image resizing, image encoding and decoding, decode image metadata only,  image cloning, Draw watermark on the image, Draw text along a path and many more.</p>

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
<p>An overview of ImageSharp features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Feature Overview</header>
<ul>
<li>Image resize</li>
<li>Modify images</li>
<li>Image encoding</li>
<li>image metadata</li>
<li>Image cloning</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header>Feature Overview</header>
<ul>
<li>Image watermark</li>
<li>Display images</li>
<li>Draw text</li>
<li>Image effect</li>
<li>Image encoding</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Apache POI"><header>ImageSharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>ImageSharp supports Excel spreadsheet format as well as it can export data to common file formats.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li>PNG, JPEG, BMP, TIFF, TGA, DICOM</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/png/">PNG</a>,<a href="https://docs.fileformat.com/image/jpeg/"> JPEG</a>, <a href="https://docs.fileformat.com/image/bmp/">BMP</a>, <a href="https://docs.fileformat.com/image/tiff/">TIFF</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Apache POI"><header>ImageSharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>ImageSharp only requires .NET Standard 1.3 and .NET Core 2.1 SDK installed or higher as well.</p>
<p> </p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><!-- <header><i class="fa fa-cubes"> &nbsp;</i></header>
    <ul>
    <li>Python 2.6 & above</li>
    </ul> --></div>
<!--/left--> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img style="border: 1px solid #9289d7; border-radius: 50%;" src='listing-image.png' alt="Apache POI"><header>ImageSharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with ImageSharp</h2>
<p>A Stable release is available on <a href="https://www.nuget.org/profiles/sixlabors">NuGet</a> For beta versions, make sure that the Include Prerelease switch is enabled. Development releases are available via MyGet.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install ImageSharp via Nuget</strong></h3>
<pre><code class="html">Install-Package SixLabors.ImageSharp -Version number </code></pre>

You can also install it manually; download the latest release files directly from the  <a href="https://github.com/SixLabors/ImageSharp.git">GitHub repository</a>.
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">C# API to Resize Images</h2>
<p>The ImageSharp library allows C# .NET programmers to resize images inside their own .NET applications. Resizing an image requires the process of generating and iterating through the pixels of a target image and sampling areas of a source image to choose what color to implement for each pixel. You can easily set the algorithm when processing images, such as Bicubic, Hermite, Box, CatmullRom, Lanczos2 and more.   Apart from the basic resizing operations, ImageSharp also offers more advanced features.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Free C# API to Resize Images</h3>
<pre><code class="c#">// Load File 
using (Image image = Image.Load("fileformat.jpg"))
{
    // Resize file 
    image.Mutate(x =&gt; x
            .Resize(image.Width / 2, image.Height / 2)
            .Grayscale());
    // Save
    image.Save("fileformat_out.jpg");
}                                
                                    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Draw Watermark on Image</h2>
<p>Usually, people protect their images by putting a large watermark overlaid to preventing people from using the images without authorization. The ImageSharp library provides support for adding watermark to images inside C++ applications. To start you need a font family and you can easily get one from the system font store. Drawn the text over the image & grey it with 50% opacity.</p>
<h2 class="h2title">Draw Text Along a Path</h2>
<p>The ImageSharp library allows C# .NET developer to draw some text following the contours of a path. It is recommended to create a font collection. First, let’s generate the text as a set of vectors drawn along the path. After drawing the path so we can see what the text is supposed to be following.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}