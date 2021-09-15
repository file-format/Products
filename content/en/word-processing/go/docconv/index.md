---
title: Open Source Go Library to Convert DOCX to Plain Text
description: Docconv - Convert Microsoft Word Processing Documents to Plain Text via Free GO API
keywords: Go DOCX, Go Word processing, Go Word processing APIs, Go Doc API, Go .docx API, Go word library, create  Word Documents, modify Word documents, add image to word files, Open Source JavaScript Libraries, Open Source Word processing, Open Source Go Library, Convert DOCX, DOCX to  Plain Text
draft: false
weight: 1



ProductName: Docconv
Githublink: https://github.com/sajari/docconv
ListingPage_Short_Description: Open Source library to convert Microsoft Word documents to Plain Text via Free Go API.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Convert Microsoft Word Processing Documents to Plain Text via Free GO API "
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library for Converting Microsoft<sup>®</sup> Word Processing Files"
Header_H2_Text="Convert Microsoft Word Processing Documents to Plain Text via Free GO API " >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<h2 class="h2title">What is Docconv?</h2>
<p>Oftentimes, while working with Microsoft Word Processing documents, the developers need the document text in plain format. Sometimes, they process the text or just display it in a different format. The open-source and free API Docconv allows GO developers to extract text from DOC and DOCX in plain format.</p>
<p>The library is developed completely in GO but has some dependencies to work properly. The API requires tidy, wv, popplerutils, and unrtf <a href="https://github.com/JalfResi/justext">JustText</a></p>

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
<p>An overview of Docconv features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"><header>Features Overview</header>
<ul>
<li>DOC to Text</li>
<li>DOCX to Text</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><header>Docconv</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Docconv supports popular Microsoft Word formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/docx/">DOCX</a>, <a href="https://docs.fileformat.com/word-processing/doc/">DOC</a></li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-arrows-v "> </i>Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Docconv</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Docconv only requires Go runtime.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-right"> </div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><br><header>Docconv</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Docconv</h2>
<p>The recommended way Docconv into your project is by using GitHub. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Docconv via GitHub</h3>
<pre><code class="html">$ go get code.sajari.com/docconv/...

                                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Convert DOCX to Plain via Free Go API</h2>
<p>The open source library Docconv allows computer programmers to convert DOCX to Plain Text inside their own Go applications. In order to convert your DOCX to Plain Text, you just need to load your document and convert it using occonv.ConvertPath() method. By using the following lines of code, you can easily convert DOCX to Plain Text.</p>
<h3>Convert Word Processing to Text in GO</h3>
<ol>
<li>Create a new client</li>
<li>Convert DOCX to Text using client.ConvertPath() and pass file path as parameter</li>
<li>Check for errors</li>
<li>Print plain text</li>
</ol>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Convert DOCX to PDF via Free GO API</h3>
<pre><code class="go">// create a new client
c := client.New()
// convert DOCX to Text
res, err := client.ConvertPath(c, "fileformat.docx")
if err != nil {
        log.Fatal(err)
}
// print output
fmt.Println(res)
                                                </code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}