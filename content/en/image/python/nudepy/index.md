---
title: Image Processing API for Python - NudePy


draft: false
weight: 24



ProductName: Nude.Py
Githublink: https://github.com/hhatto/nude.py
ListingPage_Short_Description: Image Nudity Detection with Python.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Image Nudity Detection with Python"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Open-Source Python API for Images"
Header_H2_Text="Image Nudity Detection with Python" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Nude.Py?</h2>
<p>Nude.Py is an open-source Python API for detecting nudity in images. This API is a port of nude.js. It is an implementation of a nudity scanner based on approaches from research papers. Using the API, you can analyze image data and afterwards you can decide whether or not this image should be displayed.</p>
<p>The API is simple and easy to use, you can work the API using python 2.7 + or as well as python 3.3+. You can check the nudity in the images via command-line or by using python module.</p>

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
<p>An overview of Wand features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Detect Nudity</li>
<li>Use Command-Line</li>
<li>Use Python Module</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Nude.Py</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Nude.Py supports popular Image file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li> <a href="https://docs.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>, <a href="https://docs.fileformat.com/image/jpeg/">JPG</a> </li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Nude.Py</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Nude.Py works with Python 2.7+ or 3.3+ and requires Cython and Pillow</p>
<div class="diagram1 d1-oi">
<div class="d1-row"><!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Nude.Py</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Nude.Py</h2>
<p>The recommended way to install Nude.Py is via Pip. Please use the following command to install Pip.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">pip install --upgrade nudepy</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Check Nudity in Images via Free Python API</h2>
<p>Nude.Py API allows checking nudity in images programmatically. You can check for nudity in images by using two approaches, one by using command-line and the second by using Python module. Using the command-line tool you need to write the command Nude.py with the filepath, using the python module, you can load a file using Nude() module and parse it using Nude.Parse() method. It only requires one line of code to check for nudity in images using Nude.py.</p>
<h3>Nudity Verification in Python</h3>
<ol>
<li>Import Nude.Py Library</li>
<li>Check Nudity</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Check for Nudity in Images</h3>
<pre><code class="c#">import nude
from nude import Nude

print(nude.is_nude('Image.jpg'))
    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}