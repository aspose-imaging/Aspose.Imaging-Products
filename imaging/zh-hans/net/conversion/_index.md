
---
title: C# 图像格式转换 
weight: 3920
url: /zh-hans/net/conversion/ 
lang: zh-hans
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: 通过 .NET 库转换流行的图像、照片、图片格式。只需几行 C# 代码即可转换为 PSD、PDF、GIF、JPG、SVG，包括 HTML5 Canvas。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C# 转换图像文件" h2="转换图像格式、元文件、WebP、Svg、Apng 以构建基于 .NET 的跨平台高级图像处理应用程序。" downloadText="下载" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API 为程序​​员提供了高级图像处理和渲染功能。开发人员可以集成它来将光栅和矢量图像，包括照片和图片转换为 PSD、PDF、GIF、PNG、DICOM、SVG、JPG、JPEG2000、APNG、BMP、TIFF、HTML5 CANVAS、WEBP、WMF、EMF 和其他图像格式. API 不仅处理文件转换，还处理将图像转换为黑白和灰度，转换 GIF 图像层等等。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="将图像转换为位图 BMP、JPG、PNG" %}}

使用 C# Image API，Inter 格式转换就像更改所需格式的扩展名一样简单。以下是一些通用案例，例如**image to bmp**、**image to jpg**、**image to png**，开发人员可以轻松地针对他们的特定格式进行增强。过程是通过 [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load) 加载源图像。为任何特定设置创建目标 [图像格式选项](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) 的对象。最后调用[保存方法](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)，通过传递带有路径和保存选项的目标文件作为参数。

{{% blocks/products/pf/feature-page-code h3="图像相互转换的 C# 代码" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/apng-to-bmp/" style="padding:15px;">APNG 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/dib-to-bmp/" style="padding:15px;">DIB 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM 至 BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/dng-to-bmp/" style="padding:15px;">DNG 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/emf-to-bmp/" style="padding:15px;">EMF 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/eps-to-bmp/" style="padding:15px;">EPS 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/gif-to-bmp/" style="padding:15px;">GIF 至 BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="光栅图像到 PDF 转换" %}}

将光栅图像转换为 PDF 的过程与图像相互转换的过程相同，只是 API 为特定的 PDF 设置提供了 [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) .程序员可以根据他们的特定需求轻松地对其进行增强。

{{% blocks/products/pf/feature-page-code h3="光栅图像到 PDF 转换的代码" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/apng-to-PDF/" style="padding:15px;">APNG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/odg-to-PDF/" style="padding:15px;">ODG 至 PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/otg-to-PDF/" style="padding:15px;">OTG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/png-to-PDF/" style="padding:15px;">PNG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/svg-to-PDF/" style="padding:15px;">SVG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/eps-to-PDF/" style="padding:15px;">EPS 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/gif-to-PDF/" style="padding:15px;">GIF 至 PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="将 SVG 转换为光栅图像 BMP、PNG、JPG" %}}

SVG的转换过程是一样的，加载SVG文件，使用相关的图片保存选项，调用Save方法。 Image API 提供 [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) 用于设置 PageWidth、PageHeight 和光栅图像，使用它们的 VectorRasterizationOptions 属性进行初始化和获取 SvgRasterizationOptions 选项。 

{{% blocks/products/pf/feature-page-code h3="用于 SVG 到光栅图像的 C# 代码" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG 至 JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hans/net/conversion/SVG-to-png/" style="padding:15px;">SVG 至 PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="所有支持的图像格式转换" %}}
下面是完整的图像格式列表，您可以将其转换为：
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/apng/" style="padding:15px;">转换自 APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/bmp/" style="padding:15px;">转换自 BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/dib/" style="padding:15px;">转换自 DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/dicom/" style="padding:15px;">转换自 DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/djvu/" style="padding:15px;">转换自 DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/dng/" style="padding:15px;">转换自 DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/emf/" style="padding:15px;">转换自 EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/emz/" style="padding:15px;">转换自 EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/gif/" style="padding:15px;">转换自 GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/jpeg2000/" style="padding:15px;">转换自 JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/jp2/" style="padding:15px;">转换自 JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/j2k/" style="padding:15px;">转换自 J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/jpg/" style="padding:15px;">转换自 JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/jpeg/" style="padding:15px;">转换自 JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/png/" style="padding:15px;">转换自 PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/tga/" style="padding:15px;">转换自 TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/tif/" style="padding:15px;">转换自 TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/tiff/" style="padding:15px;">转换自 TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/webp/" style="padding:15px;">转换自 WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/wmf/" style="padding:15px;">转换自 WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/wmz/" style="padding:15px;">转换自 WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/svg/" style="padding:15px;">转换自 SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/svgz/" style="padding:15px;">转换自 SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/eps/" style="padding:15px;">转换自 EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/cdr/" style="padding:15px;">转换自 CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/cmx/" style="padding:15px;">转换自 CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/otg/" style="padding:15px;">转换自 OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/odg/" style="padding:15px;">转换自 ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/from/ico/" style="padding:15px;">转换自 ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="要转换为的所有支持的图像格式" %}}
下面是完整的图像格式列表，您可以从中进行转换：
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/bmp/" style="padding:15px;">转换成 BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/gif/" style="padding:15px;">转换成 GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/dicom/" style="padding:15px;">转换成 DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/emf/" style="padding:15px;">转换成 EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/jpg/" style="padding:15px;">转换成 JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/jpeg/" style="padding:15px;">转换成 JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/jp2/" style="padding:15px;">转换成 JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/j2k/" style="padding:15px;">转换成 J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/jpeg2000/" style="padding:15px;">转换成 JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/png/" style="padding:15px;">转换成 PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/psd/" style="padding:15px;">转换成 PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/dxf/" style="padding:15px;">转换成 DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/svg/" style="padding:15px;">转换成 SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/tiff/" style="padding:15px;">转换成 TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/webp/" style="padding:15px;">转换成 WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/wmf/" style="padding:15px;">转换成 WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/pdf/" style="padding:15px;">转换成 PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/html/" style="padding:15px;">转换成 HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/emz/" style="padding:15px;">转换成 EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/wmz/" style="padding:15px;">转换成 WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/tga/" style="padding:15px;">转换成 TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/svgz/" style="padding:15px;">转换成 SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/canvas/" style="padding:15px;">转换成 CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/ico/" style="padding:15px;">转换成 ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hans/net/conversion/to/apng/" style="padding:15px;">转换成 APNG</a></div>
                </div>
        </div>
    </div>
</div>

