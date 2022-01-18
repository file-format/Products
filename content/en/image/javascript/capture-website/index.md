---
title: JavaScript Library for Image Processing - capture screenshots of websites
description: Capture Website – open source image processing library that allows Software programme to capture screenshots of websites
keywords: JavaScript Image Processing, Tiny JavaScript Library, Tiny Image Processing Library, image processing, JavaScript images, image processing library, JavaScript PNG API, JavaScript JPG, JavaScript image API, JavaScript Image creation, Modify images, Get color from image, get color, get image color, color, JavaScript Color API, Capture Screenshot
draft: false
weight: 1



ProductName: Capture-Website
Githublink: https://github.com/sindresorhus/capture-website
ListingPage_Short_Description: Open-source JavaScript Image Processing API for capturing screenshots of websites programmatically.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="JavaScript API for capturing screenshots of websites"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open Source JavaScript Library for Image Processing"
Header_H2_Text="JavaScript API for capturing screenshots of websites" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Capture-Website?</h2>
<p>Capture-Website is an open-source lightweight image processing library that enables JavaScript developers to capture screenshots of websites. Using the API, you can take screenshots of any website by using the URL of the site and the screenshots are saved on the output file path. You can set the width, height, type, and image quality of screenshots. Furthermore, you can also take screenshots based on specific device size.</p>
<p>Using the API, you can not only take screenshots of the visible portion but the complete site including the full scrollable page. By default, the API uses a white background for the screenshots. If you remove the background, the API will capture screenshots with transparency.</p>

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
<p>An overview of Capture-Website features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>Capture Screenshots</li>
<li>Set width</li>
<li>Set height</li>
<li>Set type</li>
<li>Set quality</li>
<li>Scale Factor</li>
<li>Emulate Device</li>
</ul>
</div>
<div class="d1-col d1-left"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Capture-Website</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Capture-Website supports the popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-arrows-v"> </i>Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Capture-Website</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Capture-Website can be used in multiple environments like Node or browsers etc.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right">
<ul>
<li>JavaScript </li>
<li>Puppeteer</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Capture-Website</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Capture-Website</h2>
<p>The recommended way to install Capture-Website via NPM. Please use the following command to install it.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install Capture-Website Thief via NPM</strong></h3>
<pre><code class="html"> npm install capture-website </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Capture Screenshots of Website via Free JavaScript API</h2>
<p>The open-source Capture-Website library allows JavaScript developers to capture screenshots of websites programmatically. In order to capture screenshots of the site, the API provides captureWebsite.file() method. The method takes an input file name, output file path and options for the screenshots. By using the following two lines of code, you can easily get take screenshots of the website.</p>
<h3>Capture Website Screenshots</h3>
<ol>
<li>Import capture Website Library</li>
<li>Capture Screenshots of site using captureWebsite.file(input, outputFilePath, options?). The method captures a screenshot of the given input and saves it to the given outputFilePath.</li>
<li>You can also set options like height, width type and width for the output file</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Capture Screenshots of Website in JavaScript</h3>
<pre><code class="c#">import captureWebsite from 'capture-website';
  await captureWebsite.file('https://fileformat.com', 'screenshot.png');
            
      </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Capture Screenshots for Specific Device Size in JavaScript</h2>
<p>The open-source Capture-Website library allows JavaScript developers to capture screenshot as it was taken on the specified device. In order to capture screenshots of the site, the API provides emulateDevice property. You can emulate an iPhone X size screenshot. By using the following two lines of code, you can easily emulate screenshots of the website.</p>
<h3>Emulate Device for Screenshots</h3>
<ol>
<li>Import capture Website Library</li>
<li>Capture Screenshots of site using captureWebsite.file(input, outputFilePath, options?). The method captures a screenshot of the given input and saves it to the given outputFilePath.</li>
<li>Emulate using emulateDevice property and set the value to 'iPhone X'</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Emulate Screenshots of Website in JavaScript</h3>
<pre><code class="c#">import captureWebsite from 'capture-website';
  
  await captureWebsite.file('https://fileformat.com', 'screenshot.png', {
    emulateDevice: 'iPhone X'
  });
            
      </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}