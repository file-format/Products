---
title: Open Source Java Library for Office Word Binary Documents Processing
description: POI HWPF - Open Source free Java library for MS word binary documents processing. Create, modify or add custom header & footer to Word DOC files via Java API.
keywords: Free Word API, random word api free, Convert Word Document Free, Open Source API, Open Source Word API. Java Word processing, Java Word processing APIs, Java Doc API, Java .doc API, Java word library, create Word Documents, modify Word documents, add image to word files, Open Source Java Libraries, Open Source Word processing
draft: false
weight: 2



ProductName: Apache POI HWPF
Githublink: https://github.com/apache/poi
ListingPage_Short_Description: HWPF adds the Microsoft Word DOC file processing capabilities to your Java applications.
ListingPage_Product_Small_Image: listing-image.png
ListingPage_Product_Small_Image_class: 
---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Apache POI HWPF"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="Process Microsoft Word Binary Documents"
Header_H2_Text="Create, Read, Manipulate & Convert DOC files via Open Source Java Library." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Apache POI HWPF is a Apache POI port for Microsoft Word DOC file format. It provides functionality for reading and writing DOC files without needing any additional libraries. It also provides limited read only support for the older Word 6 and Word 95 file formats. At this stage, HWPF is mainly concerned with formatted text. It provides basic text extraction, specific text extraction, access of header & footers and changing text features.</p>
<p>It facilitates developers to create MS-Word Documents with the ability to manipulate paragraphs, add different styles to text, add a table, extract text and much more.</p>

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
<p>An overview of Apache POI-HWPF features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Create document</li>
<li>Create paragraph</li>
<li>Apply font styles</li>
<li>Convert DOC</li>
<li>Add table</li>
<li>Border paragraph</li>
<li>Text alignments</li>
<li>Extract paragraph</li>
<li>Handle ranges</li>
<li>Use headers/footers</li>
<li>Use mail merge</li>
<li>Endnotes support</li>
<li>Footnotes support</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HWPF </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Apache POI HWPF supports popular Microsoft Word file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Input/Output</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/doc/">DOC</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Input Only</header>
<ul>
<li><a href="https://docs.fileformat.com/web/html/">HTML</a>,
 <a href="https://docs.fileformat.com/page-description-language/xslfo/"> FO</a>, 
 <a href="https://docs.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HWPF </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Apache POI-HWPF only requires Java run-time.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-cubes"> </i>Java</header></div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo"><img class="bg-lite" src='listing-image.png' alt="Apache POI"><header>Apache POI HWPF </header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Apache POI HWPF</h2>
<p>First of all, you need to have the Java Development Kit (JDK) installed on your system. If you already have it then proceed to the Apache POI's <a href="http://poi.apache.org/download.html">download</a> page to get the latest stable release in an archive. Extract the contents of the ZIP file in any directory from where the required libraries can be linked to your Java program. That is all!</p>
<p>Referencing Apache POI in your Maven-based Java project is even simpler. All you need is to add the following dependency in your pom.xml and let your IDE fetch and reference the Apache POI Jar files.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Apache POI Maven Dependency</h3>
<pre><code class="html">&lt;!-- https://mvnrepository.com/artifact/org.apache.poi/poi --&gt;
 &lt;dependency&gt;
  &lt;groupId&gt;org.apache.poi&lt;/groupId&gt;
  &lt;artifactId&gt;poi-scratchpad&lt;/artifactId&gt;
  &lt;version&gt;4.0.0&lt;/version&gt;
 &lt;/dependency&gt;
 </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create and Modify Word Documents using Java APIs</h2>
<p>Apache POI HWPF enables programmers to create new Word Documents in DOC file formats. The API also allows developers to modify an existing Word Documents according to their own needs. The API also supports adding a paragraph in a Word document, apply text alignments & font styles and much more.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Modify DOC file - Java</h3>
<pre><code class="java">// open an empty doc file, using APACHE POI we cannot create .doc file format from scratch
HWPFDocument doc = new HWPFDocument(new FileInputStream("empty.doc"));
Range range = doc.getRange();
// inset text
CharacterRun run = range.insertAfter("File Format Developer Guide -" +
"Learn about computer files that you come across in" +
"your daily work at: www.fileformat.com");
OutputStream out = new FileOutputStream("document.pdf");
// save document
doc.write(out);
out.close();</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert Word Documents to Other Formats using Java</h2>
<p>Apache POI HWPF enables Software developers to convert Microsoft word documents to any supported file formats with ease. At the moment the Java developers can convert Word documents to HTML, FO and Text format. The <em>org.apache.poi.hwpf.converter</em> package contains Word-to-HTML and Word-to-FO converters.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert DOC to HTML</h3>
<pre><code class="java">// load document
HWPFDocumentCore wordDocument = WordToHtmlUtils.loadDoc(new FileInputStream("document.doc"));
Document newDocument = DocumentBuilderFactory.newInstance().newDocumentBuilder().newDocument();
// initialize WordToHtmlConverter
WordToHtmlConverter wordToHtmlConverter = new WordToHtmlConverter(newDocument );
// process document
wordToHtmlConverter.processDocument( wordDocument );
StringWriter stringWriter = new StringWriter();
Transformer transformer = TransformerFactory.newInstance().newTransformer();
transformer.setOutputProperty( OutputKeys.INDENT,"yes" );
transformer.setOutputProperty( OutputKeys.ENCODING,"utf-8" );
transformer.setOutputProperty( OutputKeys.METHOD,"html" );
transformer.transform(
  new DOMSource( wordToHtmlConverter.getDocument() ),
  new StreamResult( stringWriter ) );
// get html
String html = stringWriter.toString();</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Read Text From DOC File</h2>
<p>Apache POI HWPF provides WordExtractor class to read text from Micosoft Word DOC file format. You can extract text from the file with only a few lines of code.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Extract text from a DOC file</h3>
<pre><code class="java">// load DOC file
FileInputStream fis = new FileInputStream(new File("document.doc"));
// open file
HWPFDocument doc = new HWPFDocument(fis);
// read text
WordExtractor extractor = new WordExtractor(doc);
// display text
System.out.println(extractor.getText());
</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Add Custom Header & Footer to DOC</h2>
<p>Apache POI HWPF enables Java developers to create custom headers and footers inside Word documents. Apache POI HWPF is described as"moderately functional". </p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
 
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}