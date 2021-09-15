---
title: JavaScript Library for Image Processing - Capture screenshots of websites in various resolutions
description: Pageres – open source image processing library that allows Software programmers to capture screenshots of websites via JavaScript Library
keywords: JavaScript Image Processing, Tiny JavaScript Library, Tiny Image Processing Library,  image processing, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, Get color from image, get color, get image color, color, JavaScript Color API, Screenshot, Capture Screenshots
draft: false
weight: 1



ProductName: Pageres
Githublink: https://github.com/sindresorhus/pageres
ListingPage_Short_Description: Open-source JavaScript Image Processing API to Capture screenshots of websites in various resolutions.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Capture screenshots of websites in various resolutions."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="Capture screenshots of websites in various resolutions." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Pageres?</h2>
<p>Pageres is free and open-source API that allows JavaScript developer to take screenshot of websites programmatically. The purpose of the API is to make sure that your website is responsive. It is lightweight and fast and can generate 100 screenshots from 10 different websites in just over a minute. It takes screenshots in various resolutions to make sure that the website is responsive. Furthermore, the API can also be used to render SVG images.</p>
<p>In order to take screenshots of the site, you need to pass the URL of the site. You can specify size, width, height, date and time for the output screenshot. Furthermore, you can specify an incremental name for the screenshots - so, when a file exists, it appends an incremental number.</p>

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
<p>An overview of Pageres features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Capture Screenshot</li>
<li>Size</li>
<li>Width</li>
<li>Height</li>
<li>Crop</li>
<li>Date</li>
<li>Time</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Pageres</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Pageres supports the popular Image file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li>  <a href="https://docs.fileformat.com/image/jpeg/">JPG</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a> </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Pageres</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Pageres can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Pageres</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Pageres</h2>
<p>The recommended way to install Pageres via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Pageres via NPM</strong></h3>
<pre><code class="html"> npm install pageres </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Capture Screenshot of Website via Free JavaScript API</h2>
<p>The open source Pageres library allows JavaScript developers to take screenshots of website programmatically. In order to take screenshots of the website, the API provides Pageres() method. You can set delay, timeout, crop, CSS and other options while taking screenshots. For the output file, you can set size, width, height, date and time. By using the following code, you can take screenshots of your website.</p>
<h3>Capture Screenshots in JavaScript</h3>
<ol>
<li>Import Library</li>
<li>Capture Screenshots</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Capture Screenshots of website in JavaScript</h3>
<pre><code class="c#">const Pageres = require('pageres');

(async () =&gt; {
        await new Pageres({delay: 2})
                .src('https://products.fileformat.com', ['480x320', '1024x768', 'iphone 5s'], {crop: true})
                .dest(__dirname)
                .run();

        console.log('Finished generating screenshots!');
})();
});
                        </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}