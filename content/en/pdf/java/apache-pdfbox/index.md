---
title: Java API for PDF – Add, Extract Images, Split or Merge PDF Documents
description: Apache PDFBox – An Open Source Java API for working with PDF files. Create, split or merge PDF documents, add, extract images to PDF via Java library.
keywords: Java PDF, Java PDF Library, Open Source PDF Library, Java PDF programming, Java PDF APIs, Java PDF library, Add image to PDF, Extract PDF Images, Split or Merge PDFs, create PDF Documents, Extract Text from PDF, Split PDF to many, fill a PDF form, Extract data from PDF forms
draft: false
weight: 2



ProductName: Apache PDFBox 
Githublink: https://github.com/apache/pdfbox
ListingPage_Short_Description: Java library for PDF format. It allows developers to handle simple & complex PDF Documents from their own Java applications.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache PDFBox"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Java API for PDF Documents Processing"
Header_H2_Text="Open Source Java Library to Create, Print & Split or Merge PDF Documents inside Java applications." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Apache PDFBox is an open source pure-Java library for working with PDF documents. Using this library, Java developers can develop Java programs that create new PDF documents and manipulate existing PDF documents with ease. It also enables developers to read and extract content from PDF documents. In addition to this, PDFBox also includes a command line utility for performing various operations over PDF documents using the available Jar file.</p>
<p>The Portable Document Format (PDF) is a file format that helps to present data in a manner that is independent of Application software, hardware, and operating systems. Apache PDFBox supports several advanced features, such as create, render, print, split, merge, alter, verify and extract text and meta-data of PDF files.</p>

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
<p>An overview of Apache PDFBox features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>PDF to text extraction</li>
<li>Merge PDF Documents</li>
<li>PDF Encryption</li>
<li>PDF Decryption</li>
<li>PDF Searching</li>
<li>Work with FDF form</li>
<li>Create PDF from text</li>
<li>PDF to image export</li>
<li>Print PDF document</li>
</ul>
</div>
<!--/left--> <!--<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache PDFBox" /><header>Apache PDFBox</header><footer><small></small></footer></div> -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo"><img class="bg-dark" src='listing-image.png' alt="Apache PDFBox"><header>Apache PDFBox</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache PDFBox provides support for important PDF formats as listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/pdf/">PDF</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/image/png/">PNG</a>,<a href="https://docs.fileformat.com/image/jpeg/"> JPEG</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-dark" src='listing-image.png' alt="Apache PDFBox"><header>Apache PDFBox</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache PDFBox only requires Java runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-dark" src='listing-image.png' alt="Apache PDFBox"><header>Apache PDFBox</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache PDFBox</h2>
<p>First of all, you need to download the latest release from PDFBox <a href="https://pdfbox.apache.org/download.cgi">download</a> page. To build PDFBox successfully you need to install Java 7 or higher and Maven 3 to. Use The following build command</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Installation command</h3>
<pre><code class="html"> mvn clean instal </code></pre>

<p>The command will compile Java sources & going to package the binary classes into jar packages by default.</p>
{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Java API to Create and Modify New PDF Documents</h2>
<p>Apache PDFBox allows programmers to generate a new PDF document from scratch. After creating the document, developers can save the document in the desired location. PDF is one of the most commonly used file formats nowadays. <em>PDF</em> document are compatible across various platforms and represents a document independently of the hardware, operating system, and application software used to create it. PDFBox also facilitates developers to modify existing PDF documents. Developers can add new pages as well as text to an existing page documents.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Create PDF Document - Java</h3>
<pre><code class="java">// Create a new PDF document
PDDocument document = new PDDocument();
// Save document
document.save("fileformat.pdf");
// Close document
document.close();
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Splitting and Merging PDF Documents using Java Library</h2>
<p>Apache PDFBox provides the capability to merge multiple PDF documents into a single PDF document. To merge multiple documents first you need to load existing PDF documents and then set a path to the destination file. After that developers can add all the source PDF files in the sequence they would like to find in the final merged PDF file. We can split the given PDF document into multiple PDF files. This Splitter class is used to split the given PDF document into several other separate documents.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Merge PDF Documents - Java</h3>
<pre><code class="java">// Initialize PDFMergerUtility object
PDFMergerUtility pdfMergerUtility = new PDFMergerUtility();
// Set output file path
pdfMergerUtility.setDestinationFileName("merged.pdf");
// Add source documents
pdfMergerUtility.addSource(new File("document1.pdf"));
pdfMergerUtility.addSource(new File("document2.pdf"));
// Merger documents
pdfMergerUtility.mergeDocuments(MemoryUsageSetting.setupMainMemoryOnly());
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add and Extract Images to PDF Documents inside Java Apps</h2>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<p>Apache PDFBox facilitates Java developers to insert images to an existing PDF document. Images always add real value to the piece of content. Images help us learn, grab attention, explain concepts and inspire. PDFBox provides a library for inserting an image into a PDF document. This library uses the Java program for inserting images in the PDF document. The API also enables developers to extract images from the existing PDF document and store it on the local disk.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Add Images in PDF - Java</h3>
<pre><code class="java">// Create a new PDF document
PDDocument document = new PDDocument();
// Create a new page
PDPage page = new PDPage();
// Add page
document.addPage(page);
// Initialize PDImageXObject object
PDImageXObject pdImage = PDImageXObject.createFromFile("logo.png",document);
// Initialize PDPageContentStream object
PDPageContentStream contents = new PDPageContentStream(document, page);
// Drawing image
contents.drawImage(pdImage, 70, 250);
// Close contents
contents.close();
// save document
document.save("image.pdf");
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Print PDF Documents in Various Ways using Java Library</h2>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<p>Apache PDFBox enables Java developers to print a PDF document using the standard Java printing API. It allows developers to print PDF documents in various ways. Developers can now print the document at its actual size which is the recommended way to print. It supports printing with a print preview dialog as well as custom attributes. Developers can also print PDF documents using a custom page size and custom margins.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}