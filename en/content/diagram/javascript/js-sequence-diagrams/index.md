---
title: Convert Text to UML Sequence Diagram via Open Source JavaScript API
description: JS-Sequence-Diagrams – An Open Source Free JavaScript Library for UML Sequence Diagram. Create, convert Simple text to UML Sequence Diagrams via JavaScript API.
keywords: Free Diagramming API, Free UML API, Text to UML tool, web-based UML drawing tool,  Open Source Text to UML, JavaScript UML Diagraming, JavaScript Diagram APIs,  JavaScript  Text To UML API, JavaScript API, JavaScript TextToUML library, create  TextToUML diagrams, modify TextToUML diagrams, read Visio files in Java, Open Source Visio VSD
draft: false
weight: 2



ProductName: JS-Sequence-Diagrams
Githublink: https://github.com/bramp/js-sequence-diagrams
ListingPage_Short_Description: Generate UML sequence diagrams from simple text via open source JavaScript library.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert Simple Text to UML Sequence Diagram via Open Source Free JavaScript Library."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source JavaScript API for UML Sequence Diagrams"
Header_H2_Text="Convert Simple Text to UML Sequence Diagram via Open Source Free JavaScript Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>JS-Sequence-Diagrams give software developers the capability to generate UML sequence diagrams from simple text via open source JavaScript library. A sequence diagram shows the objects and classes involved in the development and the order of messages exchanged between the objects. The library uses Jison to parse the text, and Snap.svg to draw the image.  </p>
<p>It draws simple SVG sequence diagrams from the textual representation of the diagram. The library includes two styles to render the diagram, the “normal” and the “hand-drawn”. There are several CSS classes provided for SVG diagram customization.</p>

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
<p>An overview of JS Sequence Diagrams features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Generate Diagram</li>
<li>Text to Diagram</li>
<li>UML Diagram</li>
<li>Style Diagram</li>
<li>Diagram to SVG</li>
<li>Customized Diagram</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>JS Sequence Diagrams</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>JS Sequence Diagrams supports popular compression file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/page-description-language/svg/">SVG</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://wiki.fileformat.com/page-description-language/svg/">SVG</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>JS Sequence Diagrams</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>JS Sequence Diagrams only requires Java run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li><em> </em>JavaScript</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>JS Sequence Diagrams</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with JS Sequence Diagrams</h2>
<p>The recommended way to install JS Sequence Diagrams is to run bower install bramp/js-sequence-diagrams and include the scripts below:</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install JS Sequence Diagrams via bower</h3>
<pre><code class="html"> &lt;script src="/{{ bower directory }}/bower-webfontloader/webfont.js" /&gt;<br>
&lt;script src="/{{ bower directory }}/snap.svg/dist/snap.svg-min.js" /&gt;<br>
&lt;script src="/{{ bower directory }}/underscore/underscore-min.js" /&gt;<br>
&lt;script src="/{{ bower directory }}/js-sequence-diagrams/build/sequence-diagram-min.js" /&gt; <br>  </code></pre>

<p>also, import the CSS if you plan to use the hand-drawn theme:</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Generate UML Sequence Diagrams from Simple Text</h2>
<p>JS Sequence Diagrams library enables software developers to generate UML sequence diagrams from simple text. The library allows you to add diagram title and place notes over multiple participants. The latest release uses Snap.svg along with Raphaël for drawing the diagrams. Snap.svg is a pure SVG implementation and permits the usage of CSS styling, better font support, animations and more.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Export Diagram to SVG via JavaScript API</h2>
<p>JS Sequence Diagrams provides features for exporting diagrams to SVG via open source JavaScript API. Once the diagram is created, the API allows users to download it in the SVG format into the location of their choice. JS Sequence Diagrams has included several important CSS classes that can be applied to the SVG diagram when using snap.svg. It has included sequence classes for applying to main SVG tag, title class for the title of the diagram, actor class for applying to the actors, note class for all notes and signal class for applying to the signals.</p>


{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}