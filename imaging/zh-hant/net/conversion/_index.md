
---
title: C# 圖像格式轉換 
weight: 3920
url: /zh-hant/net/conversion 
lang: zh-hant
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: 通過 .NET 庫轉換流行的圖像、照片、圖片格式。只需幾行 C# 代碼即可轉換為 PSD、PDF、GIF、JPG、SVG，包括 HTML5 Canvas。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C# 轉換圖像文件" h2="轉換圖像格式、元文件、WebP、Svg、Apng 以構建基於 .NET 的跨平台高級圖像處理應用程序。" downloadText="下載" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API 為程序員提供了高級圖像處理和渲染功能。開發人員可以集成它來將光柵和矢量圖像，包括照片和圖片轉換為 PSD、PDF、GIF、PNG、DICOM、SVG、JPG、JPEG2000、APNG、BMP、TIFF、HTML5 CANVAS、WEBP、WMF、EMF 和其他圖像格式. API 不僅處理文件轉換，還處理將圖像轉換為黑白和灰度，轉換 GIF 圖像層等等。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="將圖像轉換為位圖 BMP、JPG、PNG" %}}

使用 C# Image API，Inter 格式轉換就像更改所需格式的擴展名一樣簡單。以下是一些通用案例，例如**image to bmp**、**image to jpg**、**image to png**，開發人員可以輕鬆地針對他們的特定格式進行增強。過程是通過 [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load) 加載源圖像。為任何特定設置創建目標 [圖像格式選項](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) 的對象。最後調用[保存方法](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)，通過傳遞帶有路徑和保存選項的目標文件作為參數。

{{% blocks/products/pf/feature-page-code h3="圖像相互轉換的 C# 代碼" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/apng-to-bmp/" style="padding:15px;">APNG 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/dib-to-bmp/" style="padding:15px;">DIB 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM 至 BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/dng-to-bmp/" style="padding:15px;">DNG 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/emf-to-bmp/" style="padding:15px;">EMF 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/eps-to-bmp/" style="padding:15px;">EPS 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/gif-to-bmp/" style="padding:15px;">GIF 至 BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="光柵圖像到 PDF 轉換" %}}

將光柵圖像轉換為 PDF 的過程與圖像相互轉換的過程相同，只是 API 為特定的 PDF 設置提供了 [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) .程序員可以根據他們的特定需求輕鬆地對其進行增強。

{{% blocks/products/pf/feature-page-code h3="光柵圖像到 PDF 轉換的代碼" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/apng-to-PDF/" style="padding:15px;">APNG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/odg-to-PDF/" style="padding:15px;">ODG 至 PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/otg-to-PDF/" style="padding:15px;">OTG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/png-to-PDF/" style="padding:15px;">PNG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/svg-to-PDF/" style="padding:15px;">SVG 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/eps-to-PDF/" style="padding:15px;">EPS 至 PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/gif-to-PDF/" style="padding:15px;">GIF 至 PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="將 SVG 轉換為光柵圖像 BMP、PNG、JPG" %}}

SVG的轉換過程是一樣的，加載SVG文件，使用相關的圖片保存選項，調用Save方法。 Image API 提供 [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) 用於設置 PageWidth、PageHeight 和光柵圖像，使用它們的 VectorRasterizationOptions 屬性進行初始化和獲取 SvgRasterizationOptions 選項。 

{{% blocks/products/pf/feature-page-code h3="用於 SVG 到光柵圖像的 C# 代碼" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG 至 BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG 至 JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/zh-hant/net/conversion/SVG-to-png/" style="padding:15px;">SVG 至 PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="所有支持的圖像格式轉換" %}}
下面是完整的圖像格式列表，您可以將其轉換為：
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/apng" style="padding:15px;">轉換自 APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/bmp" style="padding:15px;">轉換自 BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/dib" style="padding:15px;">轉換自 DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/dicom" style="padding:15px;">轉換自 DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/djvu" style="padding:15px;">轉換自 DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/dng" style="padding:15px;">轉換自 DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/emf" style="padding:15px;">轉換自 EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/emz" style="padding:15px;">轉換自 EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/gif" style="padding:15px;">轉換自 GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/jpeg2000" style="padding:15px;">轉換自 JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/jp2" style="padding:15px;">轉換自 JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/j2k" style="padding:15px;">轉換自 J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/jpg" style="padding:15px;">轉換自 JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/jpeg" style="padding:15px;">轉換自 JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/png" style="padding:15px;">轉換自 PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/tga" style="padding:15px;">轉換自 TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/tif" style="padding:15px;">轉換自 TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/tiff" style="padding:15px;">轉換自 TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/webp" style="padding:15px;">轉換自 WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/wmf" style="padding:15px;">轉換自 WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/wmz" style="padding:15px;">轉換自 WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/svg" style="padding:15px;">轉換自 SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/svgz" style="padding:15px;">轉換自 SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/eps" style="padding:15px;">轉換自 EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/cdr" style="padding:15px;">轉換自 CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/cmx" style="padding:15px;">轉換自 CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/otg" style="padding:15px;">轉換自 OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/odg" style="padding:15px;">轉換自 ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/from/ico" style="padding:15px;">轉換自 ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="要轉換為的所有支持的圖像格式" %}}
下面是完整的圖像格式列表，您可以從以下格式進行轉換：
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/bmp" style="padding:15px;">轉換成 BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/gif" style="padding:15px;">轉換成 GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/dicom" style="padding:15px;">轉換成 DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/emf" style="padding:15px;">轉換成 EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/jpg" style="padding:15px;">轉換成 JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/jpeg" style="padding:15px;">轉換成 JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/jp2" style="padding:15px;">轉換成 JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/j2k" style="padding:15px;">轉換成 J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/jpeg2000" style="padding:15px;">轉換成 JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/png" style="padding:15px;">轉換成 PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/psd" style="padding:15px;">轉換成 PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/dxf" style="padding:15px;">轉換成 DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/svg" style="padding:15px;">轉換成 SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/tiff" style="padding:15px;">轉換成 TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/webp" style="padding:15px;">轉換成 WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/wmf" style="padding:15px;">轉換成 WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/pdf" style="padding:15px;">轉換成 PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/html" style="padding:15px;">轉換成 HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/emz" style="padding:15px;">轉換成 EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/wmz" style="padding:15px;">轉換成 WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/tga" style="padding:15px;">轉換成 TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/svgz" style="padding:15px;">轉換成 SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/canvas" style="padding:15px;">轉換成 CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/ico" style="padding:15px;">轉換成 ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/zh-hant/net/conversion/to/apng" style="padding:15px;">轉換成 APNG</a></div>
                </div>
        </div>
    </div>
</div>

