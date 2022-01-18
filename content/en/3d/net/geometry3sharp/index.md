---
title: .NET 3D APIs for Working with 3D Bitmap, Mesh Creation & Ray-Casting
draft: false
weight: 2
ProductName: Geometry3Sharp
Githublink: https://github.com/gradientspace/geometry3Sharp
ListingPage_Short_Description: An open source .NET 3D library for Working with 3D Bitmap, Mesh Creation & Ray-Casting against the Mesh surface
ListingPage_Product_Small_Image: listing-image.png 

---

{{< SinglePage/PageLayout/wrapper >}}
{{< SinglePage/PageHeader/header-text
Header_Image="header-image.png"
Image_H2_Text="Work with 3D Bitmap, Mesh Creation & Ray-Casting against the Mesh surface via Open Source .NET 3D APIs"
Image_Tag_Text=""
Image_Alt_Text=""
Image_title_Text=""
Header_H1_Text="C# .NET 3D Library for 2D/3D Geometric Computation"
Header_H2_Text="Work with 3D Bitmap, Mesh Creation & Ray-Casting against the Mesh surface via Open Source .NET 3D APIs" >}}

{{< SinglePage/PageBody/menu/submenu >}}
{{< SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/tab/diagram-carousel-header-wrapper >}}
{{< SinglePage/PageBody/tab/text >}}



<p>Geometry3Sharp is an open source pure C# library for working with geometric computations like 2D/3D Vector Math, Curves and Surfaces, Spatial Queries, and Implicit Surfaces. Geometry3Sharp is fully compatible with Unity. You need to set the G3_USING_UNITY scripting define and after that you will have transparent interop between G3 and Unity vector types.</p>
<p>The library supports several features related to mesh creation and ray-casting against the mesh surface, mesh simplification, Unity re-meshing animations, generating 3D lattices, marching cubes, working with 3d bitmaps, fast mesh, surfacing point sets with fast winding numbers and more.</p>

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
<p>An overview of Geometry3Sharp features</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header>Features Overview</header>
<ul>
<li>Re-meshing</li>
<li>DMesh3</li>
<li>Marching Cubes</li>
<li>Mesh Simplification</li>
<li>Re-meshing Animations</li>
<li>3D Lattices</li>
<li>Bitmaps</li>
<li>Fast Mesh</li>
<li>Mesh Selections</li>
<li>2D Curves</li>
</ul>
</div>
</div>
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Geometry3Sharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram1-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<p>Geometry3Sharp supports popular compression file formats listed below.</p>
<div class="diagram1 d2 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-arrows-v"> </i> Reader</header>
<ul>
<li>SVG, HTML</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"><header><i class="fa fa-long-arrow-down"> </i> Writer</header>
<ul>
<li><a href="https://docs.fileformat.com/word-processing/txt/">TXT</a>, <a href="https://docs.fileformat.com/page-description-language/svg/">SVG</a>, <a href="https://docs.fileformat.com/web/html/">HTML</a></li>
</ul>
</div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Geometry3Sharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2-->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< SinglePage/PageBody/tab/diagram-carousel-item >}}
<h3>Platform Independence</h3>
<p>Geometry3Sharp only requires .NET Framework</p>
<div class="diagram1 d1-poi">
<div class="d1-row">
<div class="d1-col d1-left">
<ul>
<li>.NET Framework 3.5</li>
</ul>
</div>
<!--/left-->
<div class="d1-col d1-right"> </div>
<!--/right--></div>
<!--/row-->
<div class="d1-logo" style="border: none;"><!--<img src='listing-image.png' alt="Compression APIs for .NET" />--><header>Geometry3Sharp</header><footer><small></small></footer></div>
<!--/logo--></div>
<!--/diagram2 -->
{{< /SinglePage/PageBody/tab/diagram-carousel-item >}}

{{< /SinglePage/PageBody/tab/diagram-carousel-body-wrapper >}}

{{< /SinglePage/PageBody/tab/wrapper >}}
{{< SinglePage/PageBody/features/feature-wrap >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Getting Started with Geometry3Sharp</h2>
<p>The easiest way to install Geometry3Sharp is by using NuGet. Use the following command for a smooth installation.</p>
{{< /SinglePage/PageBody/features/text >}}

{{< SinglePage/PageBody/features/code >}}
<h3>Install Geometry3Sharp via NuGet</h3>
<pre><code class="html">Install-Package geometry3Sharp -Version 1.0.324 </code></pre>

{{< /SinglePage/PageBody/features/code >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">3D Mesh Construction via .NET Library</h2>
<p>Geometry3Sharp provides functionality for interactive mesh creation using .NET. First of all, construct a DMesh3 object from lists of vertex x/y/z coordinates. Utility function makes this construction simple. Moreover, the NewVertexInfo type has provided extra constructors for other cases, such as vertex colors and UVs.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">Create Bitmap3 Voxelization of a Mesh</h2>
<p>Geometry3Sharp enables software developers to create Bitmap3 Voxelization of a mesh inside their own applications. There are several ways to create this Bitmap3 voxelization of a mesh such as Voxelization with the mesh winding number, voxelization with Point-containment queries, creating a Minecraft-style surface mesh and more. The tutorials for the above are provided in the GitHub documentation section.</p>
{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}
{{< SinglePage/PageBody/features/single-feature-content >}}

{{< SinglePage/PageBody/features/text >}}
<h2 class="h2title">3D Printer Control </h2>
<p>The Geometry3Sharp library allows developers to directly generate GCode for their 3D printer. It only requires geometry3Sharp, gsGCode, and gsSlicer libraries.</p>

{{< /SinglePage/PageBody/features/text >}}
{{< /SinglePage/PageBody/features/single-feature-content >}}

{{< /SinglePage/PageBody/features/feature-wrap >}}
{{< /SinglePage/PageLayout/wrapper >}}