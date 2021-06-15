---
title: Java Library for PowerPoint PPT - Add Slides & Images to Presentation
description: POI-HSLF & POI-XLSF - Open Source Java API for creating, reading and modifying Microsoft PowerPoint PPT & PPTX Presentations Files.
keywords: Open Source PowerPoint API, Open Source Java API, Java PowerPoint API, create  PPT Presentations, add slide in PPTX, modify PowerPoint PPT, add slide to Presentations, Open Source Java Libraries
draft: false
weight: 1



ProductName: Apache POI HSLF
Githublink: https://github.com/apache/poi
ListingPage_Short_Description: Add PowerPoint Binary file format (PPT) processing capabilities to your own Java applications.
ListingPage_Product_Small_Image: listing-image.png

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache POI HSLF"
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Java Library for Microsoft<sup>®</sup> PPT Presentation File Formats"
Header_H2_Text="Add Slides & Images to Presentations, Convert PPT Files with open-source Free Java API." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Apache POI HSLF?</h2>
<p>Apache POI HSLF is pure Java implementation for reading, creating, modifying or rendering PowerPoint presentations.  It provides a way to read, create or modify PowerPoint presentation PPT file format. It provides support for extracting data such as text, images, sounds, embedded objects &amp; much more from PowerPoint presentations.</p>
<p>It also supports drawing a shape on a slide, adding hyperlinks, Tables, images, customize Headers &amp; Footers, create bulleted lists, retrieve embedded sounds and much more.</p>

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
<p>An overview of Apache POI HSLF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create presentation</li>
<li>Add new slide</li>
<li>Draw shape on slide</li>
<li>Presentation to PPT</li>
<li>Manage slide layout</li>
<li>Set page size</li>
<li>Render slide to images</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-file-o"> </i>Features Overview</header>
<ul>
<li>Work with tables</li>
<li>Add hyperlinks &amp; images</li>
<li>Retrieve OLE objects</li>
<li>Reorder slides</li>
<li>Remove shapes</li>
<li><span style="font-size: 12.16px;">Delete slide</span></li>
<li><span style="font-size: 12.16px;">Create bulleted lists</span></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header> Apache POI HSLF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache POI HSLF supports popular Microsoft PowerPoint file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://wiki.fileformat.com/presentation/ppt/">PPT </a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://wiki.fileformat.com/image/jpeg/">JPEG</a>, <a href="https://wiki.fileformat.com/image/png/">PNG</a>, <a href="https://wiki.fileformat.com/page-description-language/svg/">SVG</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HSLF</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache POI HSLF only requires Java runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache POI HSLF</h2>
<p>First of all, you need to have the Java Development Kit (JDK) installed on your system. If you already have it then proceed to the Apache POI's <a href="http://poi.apache.org/download.html">download</a> page to get the latest stable release in an archive. Extract the contents of the ZIP file in any directory from where the required libraries can be linked to your Java program. That is all!</p>
<p>Referencing Apache POI in your Maven-based Java project is even simpler. All you need is to add the following dependency in your pom.xml and let your IDE fetch and reference the Apache POI Jar files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Apache POI Maven Dependency</h3>
<pre><code class="html">&lt;!-- https://mvnrepository.com/artifact/org.apache.poi/poi --&gt;
    &lt;dependency&gt;
        &lt;groupId&gt;org.apache.poi&lt;/groupId&gt;
        &lt;artifactId&gt;poi-scratchpad&lt;/artifactId&gt;
        &lt;version&gt;4.1.0&lt;/version&gt;
    &lt;/dependency&gt;
    </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Dynamically Create New PPT or Modify Existing Presentations</h2>
<p>Apache POI HSLF enables programmers to create new PowerPoint presentations in PPT file formats. Developers can also transform an existing presentation according to their needs. The API also supports features for extracting data such as text, images, sounds, embedded objects &amp; so on from PowerPoint presentations.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create a PPT file - Java</h3>
<pre><code class="java">// create a new PPT file
FileOutputStream fileOutputStream = new FileOutputStream(new File("Slide.ppt"));
// create a new slide show
HSLFSlideShow xmlSlideShow = new HSLFSlideShow();
// save file
xmlSlideShow.write(fileOutputStream);
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Slides, Images &amp; Customize Header &amp; Footer to PPT</h2>
<p>Developers can easily add new slides and modify existing ones according to their own needs inside a PPT presentation using Apache HSLF API. Developers can now add customize headers and footers into their presentations. It also provides complete support for adding a title for a slide, create a slide with a predefined layout, work with slide/shape background and much more.</p>
<h3>Insert Images in PPT via Java</h3>
<ol>
<li>Create a new PPT file by using FileOutputStream and pass instance of new File() with output filename as string</li>
<li>Add new slide show using HSLFSlideShow() method</li>
<li>Add new slide using createSlide() method</li>
<li>Get image bytes using IOUtils.toByteArray() method and pass your image in it via FileInputStream() method</li>
<li>Add image to your slide using hslfSlideShow.addPicture(picture, HSLFPictureData.PictureType.PNG) method. The method accepts picture bytes and picture type as arguments</li>
<li>Write and save file</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Add Image in PPT - Java</h3>
<pre><code class="java">// create a new PPT file
FileOutputStream fileOutputStream = new FileOutputStream(new File("AddImage.ppt"));
// create a new slide show
HSLFSlideShow hslfSlideShow = new HSLFSlideShow();
// create slide
HSLFSlide slide = hslfSlideShow.createSlide();
// load image
byte[] picture = IOUtils.toByteArray(new FileInputStream(new File("apache-poi-logo-min.png")));
// add image
HSLFPictureData hslfPictureData = hslfSlideShow.addPicture(picture, HSLFPictureData.PictureType.PNG);
HSLFPictureShape pictureShape = slide.createPicture(hslfPictureData);
// save file
hslfSlideShow.write(fileOutputStream);
// close stream
fileOutputStream.close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert Slides to Image Formats using Java API</h2>
<p>Apache POI HSLF API enables Software developers to convert each slide of a PowerPoint Presentation into an image file format inside their Java applications. You can capture slides into java.awt.Graphics2D object (or any other) and serialize it into a PNG or JPEG format. The supported images could be in JPEG, PNG, DIB and so on.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert PPT to Image - Java</h3>
<pre><code class="java">//open an existing PPT file
HSLFSlideShow hslfSlideShow = new HSLFSlideShow(new FileInputStream(new File("PPTtoImage.ppt")));
// get dimensions
Dimension pgsize = hslfSlideShow.getPageSize();
java.util.List slide = hslfSlideShow.getSlides();

for (int i = 0; i &lt; slide.size(); i++) {
    BufferedImage img = new BufferedImage(pgsize.width, pgsize.height,BufferedImage.TYPE_INT_RGB);
    Graphics2D graphics = img.createGraphics();

    // clear the drawing area
    graphics.setPaint(Color.white);
    graphics.fill(new Rectangle2D.Float(0, 0, pgsize.width, pgsize.height));

    // render
    slide.get(i).draw(graphics);

    // create image
    FileOutputStream out = new FileOutputStream("PPTtoImage.png");
    javax.imageio.ImageIO.write(img, "png", out);
    out.close();
}</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}

{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert PPT to Image - Java</h3>
<pre><code class="java">//open an existing PPT file
HSLFSlideShow hslfSlideShow = new HSLFSlideShow(new FileInputStream(new File("PPTtoImage.ppt")));
// get dimensions
Dimension pgsize = hslfSlideShow.getPageSize();
java.util.List slide = hslfSlideShow.getSlides();

for (int i = 0; i &lt; slide.size(); i++) {
    BufferedImage img = new BufferedImage(pgsize.width, pgsize.height,BufferedImage.TYPE_INT_RGB);
    Graphics2D graphics = img.createGraphics();

    // clear the drawing area
    graphics.setPaint(Color.white);
    graphics.fill(new Rectangle2D.Float(0, 0, pgsize.width, pgsize.height));

    // render
    slide.get(i).draw(graphics);

    // create image
    FileOutputStream out = new FileOutputStream("PPTtoImage.png");
    javax.imageio.ImageIO.write(img, "png", out);
    out.close();
}</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}

{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert PPT to Image - Java</h3>
<pre><code class="java">//open an existing PPT file
HSLFSlideShow hslfSlideShow = new HSLFSlideShow(new FileInputStream(new File("PPTtoImage.ppt")));
// get dimensions
Dimension pgsize = hslfSlideShow.getPageSize();
java.util.List slide = hslfSlideShow.getSlides();

for (int i = 0; i &lt; slide.size(); i++) {
    BufferedImage img = new BufferedImage(pgsize.width, pgsize.height,BufferedImage.TYPE_INT_RGB);
    Graphics2D graphics = img.createGraphics();

    // clear the drawing area
    graphics.setPaint(Color.white);
    graphics.fill(new Rectangle2D.Float(0, 0, pgsize.width, pgsize.height));

    // render
    slide.get(i).draw(graphics);

    // create image
    FileOutputStream out = new FileOutputStream("PPTtoImage.png");
    javax.imageio.ImageIO.write(img, "png", out);
    out.close();
}</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}

{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert PPT to Image - Java</h3>
<pre><code class="java">//open an existing PPT file
HSLFSlideShow hslfSlideShow = new HSLFSlideShow(new FileInputStream(new File("PPTtoImage.ppt")));
// get dimensions
Dimension pgsize = hslfSlideShow.getPageSize();
java.util.List slide = hslfSlideShow.getSlides();

for (int i = 0; i &lt; slide.size(); i++) {
    BufferedImage img = new BufferedImage(pgsize.width, pgsize.height,BufferedImage.TYPE_INT_RGB);
    Graphics2D graphics = img.createGraphics();

    // clear the drawing area
    graphics.setPaint(Color.white);
    graphics.fill(new Rectangle2D.Float(0, 0, pgsize.width, pgsize.height));

    // render
    slide.get(i).draw(graphics);

    // create image
    FileOutputStream out = new FileOutputStream("PPTtoImage.png");
    javax.imageio.ImageIO.write(img, "png", out);
    out.close();
}</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}