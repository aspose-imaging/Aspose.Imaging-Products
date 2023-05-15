
---
title: C# Görüntü Biçimlerini Dönüştürme 
weight: 3920
url: /tr/net/conversion/ 
lang: tr
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: .NET kitaplığı aracılığıyla popüler resim, fotoğraf, resim formatlarını dönüştürün. Birkaç satır C# koduyla HTML5 Canvas dahil PSD, PDF, GIF, JPG, SVG'ye dönüştürün.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# ile Görüntü Dosyalarını Dönüştürme" h2="Çapraz platform .NET tabanlı gelişmiş görüntü işleme uygulamaları oluşturmak için Görüntü formatlarını, Meta Dosyalarını, WebP, Svg, Apng'yi dönüştürün." downloadText="İndirmek" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API, programcılar için gelişmiş görüntü işleme ve işleme özelliklerini kolaylaştırır. Geliştiriciler, fotoğraf ve resimler dahil olmak üzere tarama ve vektör görüntülerini PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF ve diğer görüntü biçimlerine dönüştürmek için entegre edebilir. . API yalnızca dosyaların dönüştürülmesiyle değil, aynı zamanda görüntüleri siyah n beyaza ve gri tonlamaya dönüştürmek, GIF görüntü katmanlarını dönüştürmek ve daha fazlasıyla ilgilenir.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Görüntüyü Bitmap BMP, JPG, PNG'ye Dönüştür" %}}

C# Image API kullanarak, Inter format dönüştürme, istenen formatın uzantısını değiştirmek kadar kolaydır. Burada **image to bmp**, **image to jpg**, **image to png** gibi birkaç genel durum verilmiştir ve geliştiriciler kendi özel biçimleri için kolayca geliştirebilirler. İşlem, kaynak görüntüyü [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load) aracılığıyla yüklemektir. Herhangi bir özel ayar için bir hedef [görüntü formatı seçenekleri](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) nesnesi oluşturun. Son olarak, hedef dosyayı yol ve parametre olarak Kaydetme seçenekleriyle ileterek [Kaydetme Yöntemini](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) çağırın.

{{% blocks/products/pf/feature-page-code h3="Görüntülerin Ara Dönüşümü için C# Kodu" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/apng-to-bmp/" style="padding:15px;">APNG ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/dib-to-bmp/" style="padding:15px;">DIB ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM ile BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/dng-to-bmp/" style="padding:15px;">DNG ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/emf-to-bmp/" style="padding:15px;">EMF ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/eps-to-bmp/" style="padding:15px;">EPS ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/gif-to-bmp/" style="padding:15px;">GIF ile BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Raster Görüntüyü PDF'ye Dönüştürme" %}}

Raster görüntüleri PDF'ye dönüştürme işlemi, API'nin belirli PDF ayarları için [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) sağlaması dışında görüntülerin karşılıklı dönüştürülmesiyle aynıdır. . Programcılar, özel ihtiyaçları için kolayca geliştirebilir.

{{% blocks/products/pf/feature-page-code h3="Raster Görüntüleri PDF'ye Dönüştürme Kodu" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/apng-to-PDF/" style="padding:15px;">APNG ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/odg-to-PDF/" style="padding:15px;">ODG ile PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/otg-to-PDF/" style="padding:15px;">OTG ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/png-to-PDF/" style="padding:15px;">PNG ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/svg-to-PDF/" style="padding:15px;">SVG ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/eps-to-PDF/" style="padding:15px;">EPS ile PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/gif-to-PDF/" style="padding:15px;">GIF ile PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="SVG'yi Raster Görüntülere Dönüştür BMP, PNG, JPG" %}}

SVG'nin dönüştürme işlemi aynıdır, SVG dosyasını yükleyin, İlgili görüntü kaydetme seçeneklerini kullanın ve Kaydet yöntemini çağırın. Image API, PageWidth, PageHeight ve raster görüntülerin ayarlanması için [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) sağlar, başlatma ve SvgRasterizationOptions seçeneklerini almak için VectorRasterizationOptions özelliğini kullanır. 

{{% blocks/products/pf/feature-page-code h3="SVG'den Raster Görüntülere C# Kodu" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG ile BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG ile JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/tr/net/conversion/SVG-to-png/" style="padding:15px;">SVG ile PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Dönüştürülecek tüm desteklenen Görüntüler biçimler" %}}
Aşağıda, dönüştürebileceğiniz görüntü biçimlerinin tam listesi sunulmaktadır:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/apng/" style="padding:15px;">Şuradan Dönüştür APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/bmp/" style="padding:15px;">Şuradan Dönüştür BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/dib/" style="padding:15px;">Şuradan Dönüştür DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/dicom/" style="padding:15px;">Şuradan Dönüştür DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/djvu/" style="padding:15px;">Şuradan Dönüştür DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/dng/" style="padding:15px;">Şuradan Dönüştür DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/emf/" style="padding:15px;">Şuradan Dönüştür EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/emz/" style="padding:15px;">Şuradan Dönüştür EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/gif/" style="padding:15px;">Şuradan Dönüştür GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/jpeg2000/" style="padding:15px;">Şuradan Dönüştür JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/jp2/" style="padding:15px;">Şuradan Dönüştür JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/j2k/" style="padding:15px;">Şuradan Dönüştür J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/jpg/" style="padding:15px;">Şuradan Dönüştür JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/jpeg/" style="padding:15px;">Şuradan Dönüştür JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/png/" style="padding:15px;">Şuradan Dönüştür PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/tga/" style="padding:15px;">Şuradan Dönüştür TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/tif/" style="padding:15px;">Şuradan Dönüştür TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/tiff/" style="padding:15px;">Şuradan Dönüştür TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/webp/" style="padding:15px;">Şuradan Dönüştür WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/wmf/" style="padding:15px;">Şuradan Dönüştür WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/wmz/" style="padding:15px;">Şuradan Dönüştür WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/svg/" style="padding:15px;">Şuradan Dönüştür SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/svgz/" style="padding:15px;">Şuradan Dönüştür SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/eps/" style="padding:15px;">Şuradan Dönüştür EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/cdr/" style="padding:15px;">Şuradan Dönüştür CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/cmx/" style="padding:15px;">Şuradan Dönüştür CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/otg/" style="padding:15px;">Şuradan Dönüştür OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/odg/" style="padding:15px;">Şuradan Dönüştür ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/from/ico/" style="padding:15px;">Şuradan Dönüştür ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Dönüştürülecek tüm desteklenen görüntü formatları" %}}
Aşağıda, dönüştürebileceğiniz görüntü biçimlerinin tam listesi sunulmaktadır:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/bmp/" style="padding:15px;">E dönüşmek BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/gif/" style="padding:15px;">E dönüşmek GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/dicom/" style="padding:15px;">E dönüşmek DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/emf/" style="padding:15px;">E dönüşmek EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/jpg/" style="padding:15px;">E dönüşmek JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/jpeg/" style="padding:15px;">E dönüşmek JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/jp2/" style="padding:15px;">E dönüşmek JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/j2k/" style="padding:15px;">E dönüşmek J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/jpeg2000/" style="padding:15px;">E dönüşmek JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/png/" style="padding:15px;">E dönüşmek PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/psd/" style="padding:15px;">E dönüşmek PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/dxf/" style="padding:15px;">E dönüşmek DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/svg/" style="padding:15px;">E dönüşmek SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/tiff/" style="padding:15px;">E dönüşmek TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/webp/" style="padding:15px;">E dönüşmek WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/wmf/" style="padding:15px;">E dönüşmek WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/pdf/" style="padding:15px;">E dönüşmek PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/html/" style="padding:15px;">E dönüşmek HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/emz/" style="padding:15px;">E dönüşmek EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/wmz/" style="padding:15px;">E dönüşmek WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/tga/" style="padding:15px;">E dönüşmek TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/svgz/" style="padding:15px;">E dönüşmek SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/canvas/" style="padding:15px;">E dönüşmek CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/ico/" style="padding:15px;">E dönüşmek ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/tr/net/conversion/to/apng/" style="padding:15px;">E dönüşmek APNG</a></div>
                </div>
        </div>
    </div>
</div>

