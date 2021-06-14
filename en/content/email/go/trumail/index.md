---
title: A Fast and Free Email Verification API written in Go.
description: Trumail- Open Source Go Library for email verification and validation. 
keywords: Free Go library,  GO API, GO, Email Verification, Email Validation, Free email verification, Free email validation, Go email verification, Go email validation
draft: false
weight: 18



ProductName: Trumail
Githublink: https://github.com/trumail/trumail
ListingPage_Short_Description: A Fast and Free Email Verification API written in Go.
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="A Fast and Free Email Verification API written in Go."
Image_Tag_Text=""
Image_Alt_Text=" "
Image_title_Text=""
Header_H1_Text="Open Source Go Library to Verify Email Messages"
Header_H2_Text="A Fast and Free Email Verification API written in Go." >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Trumail is open-source email verification & validation system. Trumail is a fast email address verification API written purely in Go. The aim of building API was to provide developers a simple solutions to manage bounced emails. Using the API you can prevent bounced emails and low-quality users. If you are a devloper writing a new applicaiton to make sure that on valid user can subscribe to your application, trumail can help you verfiy it.</p>
<p>Using the API is pretty simple. The API provides and email verification endpoint. In order to verfiy the email address, you need to send and GET request to the main lookup endpoint. By using the API open-source code, you can host it in your own environment and use it as per you needs.</p>
<p><span style="font-size: 12.16px;">. </span></p>

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
<p>An overview of Trumail features.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Email Address Verification</li>
</ul>
</div>
<!--/left -->
<div class="d1-col d1-right"> </div>
</div>
<div class="d1-logo" style="border: none;"><header>Trumail</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Trumail supports popular file formats listed below.</p>
<div class="diagram1 d2  d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v "> </i> Reader</header></div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa  fa-long-arrow-down"> </i> Writer</header></div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Trumail</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Trumail requires the following.</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"> </div>
<div class="d1-col d1-right">
<ul>
<li>Trumail requires at least Go 1.11.</li>
</ul>
</div>
</div>
<!--/row-->
<div class="d1-logo" style="border: none;"><header>Hermes</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Trumail</h2>
<p>The recommended way to trumail into your project is by using GitHub. Please use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Go-Email via GitHub</h3>
<pre><code class="html">go get -d github.com/sdwolfe32/trumail/...
go install github.com/sdwolfe32/trumail
trumail</code></pre>


{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Validate & Verify Email Address via Free Go API</h2>
<p>Verifying email address with the Trumail API is pretty string forward. In order to verfiy the email adress you need to send and HTTP GET request to the following URL</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<pre><code class="html">https://api.trumail.io/v2/lookups/{{format}}?email={{email}}</code></pre>

<p>The email verification is not a very complicated process. Firstly and TCP conneciton is formed with the server on port 25 then identify the server name and set and reply-to email. Lastly, by using RCPT command the email address is vefified.</p>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}