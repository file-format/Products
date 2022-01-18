---
title: WebGL JavaScript Free Library | Generate 3D Interactions & Animations
description: Curtainsjs is a WebGL JavaScript library to create 3D interaction, animations, and can convert HTML elements into 3D WebGL textured planes
keywords: WebGL JavaScript Library, Free 3D Library, JavaScript 3D, JavaScript 3D library, read 3D Files, write 3D Files, convert 3D Files, Open Source 3D library, Render 3D files, Open Source JS Library, render 3D WebGL, read FBX files, read 3D Collada Files
draft: false
weight: 11



ProductName: Curtains.js
Githublink: https://github.com/martinlaxenaire/curtainsjs
ListingPage_Short_Description: A WebGL JavaScript Free Library to create powerful 3D interactions and animations with ease
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="A free JavaScript API that allows to convert HTML DOM elements into interactive textured plane, manage WebGL & positioning meshes relative to the DOM elements of web page"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="JavaScript Library to Create 3D Interaction & Animation"
Header_H2_Text="An open source JavaScript library that allows to convert HTML DOM elements into interactive textured plan, and manage WebGL & positioning meshes relative to the DOM elements of web page" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>curtains.js is an open source lightweight JavaScript library that gives software developers the capability to transform HTML DOM elements into interactive textured planes with ease. The library allows users to create powerful 3D interaction and animation by translating HTML elements containing images and videos into 3D WebGL textured planes, letting users animate those via shaders.</p>
<p>The library is easy to use but you need to have good basics knowledge of HTML, CSS, JavaScript, and shaders. A <em>shader</em> is a set of instructions that runs in the graphics pipeline and tells the computer how to render each pixel. You also need to know more about the vertex and fragment shaders, how to use uniforms as well as the GLSL syntax basics.</p>
<p>This curtains.js library is available under the MIT license which means it is free to use for personal and commercial projects. The main aim of the library is to provide an easy way for the handling of WebGL and positioning mesh relative to DOM elements of web page. WebGL is a JavaScript API for real-time rendering of 3D and 2D graphics within a browser.</p>

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
<p>An overview of curtains.js features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>3D Interactions</li>
<li>3D Animations</li>
<li>Convert HTML Elements</li>
<li>WebGL</li>
<li>Vertex Shaders</li>
<li>Fragment Shaders</li>
<li>Renders Properties</li>
<li>Manage Scenes</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>curtains.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>curtains.js supports file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>WebGL</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a>, WebGL</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>curtains.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>curtains.js only requires JavaScript</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li>JavaScript</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>curtains.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with curtains.js</h2>
<p>The easiest way to install curtains.js is using NPM. Use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install curtains.js via NPM</h3>
<pre><code class="html">npm i curtainsjs </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Manage Scenes using JavaScript</h2>
<p>curtains.js has useful functionality related to scenes management and its relevant properties. The Scene will pile all the objects that will be drawn including planes and shader passes in different arrays, and call them in the right order to be drawn. You can easily reset the plane stacks, clear the place stack, rebuild it with the new place indexes, add new planes to a scene, remove a plane from a scene, changing the position of a plane, and so on.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Handling Renders Properties</h2>
<p>The free library curtains.js provides the capability for handling renders using the Renderer class. It provides functionalities related to the WebGL context such as creation and restoration, extensions, WebGL commands, and more. It can be used to generate a container, append a canvas, handle WebGL extensions, context lost/restoration events, and create a Scene class object that will keep tracks of all added objects. Apart from the above it also supports handling global WebGL commands, such as scene clearance, frame buffers binding, setting depth, blend func, and so on.</p>
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Animate Images and Videos</h2>
<p>The open source library curtains.js gives software developers the power to animate images and videos inside their own applications with ease. The library enables developers to create <em>planes</em> containing images and videos that act like plain HTML elements, with position and size defined by CSS rules. You can also use multiple textures, multiple planes, multiple planes canvas text, multiple video texture, and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}