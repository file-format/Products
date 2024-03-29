---
title: Open Source JavaScript Library | Read, Write & Render 3D Files
description: three.js is an open source JavaScript library to read, write, render and convert 3D File Formats like WebGL, FBX, Collada & OBJ
keywords: JavaScript 3D, JavaScript 3D library, read 3D Files, write 3D Files, convert 3D Files, Open Source 3D library, Render 3D files, Open Source JS Library, render 3D WebGL, read FBX files, read 3D Collada Files
draft: false
weight: 10

ProductName: three.js 
Githublink: https://github.com/mrdoob/three.js
ListingPage_Short_Description: Read, write and render 3D file formats (WebGL, FBX, Collada, and OBJ) via open source 3D JavaScript library
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="three.js"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="JavaScript Library for 3D File Formats"
Header_H2_Text="Open source JavaScript library for reading, writing, and rendering WebGL, FBX, Collada as well as OBJ file formats" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}
<p>three.js is an open source easy to use, pure JavaScript 3D library that gives software developers the capability to render WebGL files. The three.js library offers loaders for numerous file formats like FBX, Collada as well as OBJ but the recommended format for importing and exporting data is glTF. The great thing about glTF file format is that it is compact and can be easily transmitted.</p>
<p>The library supports several features related to 3D models such as creating a scene, loading 3D models, creating text, drawing lines setting a camera, create a geometric cube, adds cube to the scene, rendering the scene, adds viewport to element, and many more.</p>

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
<p>An overview of three.js features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>Create 3D Scenes</li>
<li>Load 3D Models</li>
<li>Draw Lines</li>
<li>Read/Write FBX</li>
<li>Read/Write Collada</li>
<li>Convert 3D Scenes</li>
<li>Export Data in glTF</li>
<li>Component Handling</li>
<li>Textures Handling</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Lib3MF"><header>three.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>three.js supports popular 3D file formats listed below</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>WebGL. glTF, Collada</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, WebGL, <a href="https://docs.fileformat.com/3d/gltf/">glTF</a>, Collada</li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="three.js"><header>three.js</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>three.js can run on any modern JavaScript bundler - the most popular choice is webpack</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right"><header><i class="fa fa-cubes"> </i> Mandatory</header>
<ul>
<li>JavaScript </li>
</ul>
</div>
<!--/left
<div class="d1-col d1-right">&nbsp;</div> --> <!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="three.js"><header>Lib3MF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with three.js</h2>
<p>The easiest way to install three.js is by using NPM. Use the following command for a smooth installation. </p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3><strong>Install three.js via NPM</strong></h3>
<pre><code class="html">npm install --save three </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create 3D Scene using JavaScript</h2>
<p>The open source library three.js supports creating 3D scene. To display anything with three.js you require scene, camera, and renderer. You can use different cameras and their attribute to complete the scene. Next, you can use a renderer instance and set the size at which we want it to render our app. You can keep the lower or higher resolution. Lastly, you add the <strong>renderer</strong> element (&lt;canvas&gt;) to your HTML document. You can easily create a cube by using BoxGeometry and use the material to color it. After that, you need a <strong>Mesh</strong> that can be inserted into the scene and moved according to the need.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Loading 3D Models via JavaScript</h2>
<p>The three.js library allows loading 3D models with just a couple of lines of JavaScript code. 3D models are available in hundreds of file formats. E model comes with different purposes, miscellaneous features, and varying complexity. First, you need to have a loader and after that, you will be able to load the scene.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Draw Lines in a Diagram</h2>
<p>The library three.js supports drawing lines or circles. To start with you need to set up the renderer, scene, and camera. After that, you need to define material and can use LineBasicMaterial or LineDashedMaterial. After material, you will need geometry with some vertices. Lines are drawn between each consecutive pair of vertices.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}