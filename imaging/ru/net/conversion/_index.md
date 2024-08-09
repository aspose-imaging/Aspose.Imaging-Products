
---
title: Преобразование форматов изображений C# 
weight: 3920
url: /ru/net/conversion/ 
lang: ru
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Преобразование популярных форматов изображений, фотографий, изображений с помощью библиотеки .NET. Преобразование в PSD, PDF, GIF, JPG, SVG, включая HTML5 Canvas, с помощью нескольких строк кода C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование файлов изображений с помощью C#" h2="Преобразование форматов изображений, метафайлов, WebP, Svg, Apng для создания кроссплатформенных приложений для расширенной обработки изображений на основе .NET." downloadText="Скачать" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API упрощает расширенные функции обработки и рендеринга изображений для программистов. Разработчики могут интегрировать его для преобразования растровых и векторных изображений, включая фотографии и изображения, в PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF и другие форматы изображений. . API занимается не только преобразованием файлов, но также преобразованием изображений в черно-белые и оттенки серого, преобразованием слоев изображения GIF и многим другим.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование изображения в растровое изображение BMP, JPG, PNG" %}}

С помощью C# Image API преобразование формата Inter выполняется так же просто, как изменение расширения нужного формата. Вот несколько общих случаев, таких как **изображение в bmp**, **изображение в jpg**, **изображение в png**, и разработчики могут легко улучшить их для своего конкретного формата. Процесс загрузки исходного изображения через [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Создайте объект целевого[параметры формата изображения](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) для любых конкретных настроек. Наконец, вызовите [Метод сохранения](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4), передав целевой файл с путем и параметрами сохранения в качестве параметра.

{{% blocks/products/pf/feature-page-code h3="Код C# для взаимного преобразования изображений" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/apng-to-bmp/" style="padding:15px;">APNG к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/dib-to-bmp/" style="padding:15px;">DIB к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM к BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/dng-to-bmp/" style="padding:15px;">DNG к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/emf-to-bmp/" style="padding:15px;">EMF к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/eps-to-bmp/" style="padding:15px;">EPS к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/gif-to-bmp/" style="padding:15px;">GIF к BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Преобразование растрового изображения в PDF" %}}

Процесс преобразования растровых изображений в PDF такой же, как и взаимное преобразование изображений, за исключением того, что API предоставляет [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) для определенных настроек PDF. . Программисты могут легко улучшить его для своих конкретных нужд.

{{% blocks/products/pf/feature-page-code h3="Код для преобразования растровых изображений в PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/apng-to-PDF/" style="padding:15px;">APNG к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/odg-to-PDF/" style="padding:15px;">ODG к PDF</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/otg-to-PDF/" style="padding:15px;">OTG к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/png-to-PDF/" style="padding:15px;">PNG к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/svg-to-PDF/" style="padding:15px;">SVG к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/eps-to-PDF/" style="padding:15px;">EPS к PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/gif-to-PDF/" style="padding:15px;">GIF к PDF</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Преобразование SVG в растровые изображения BMP, PNG, JPG" %}}

Процесс преобразования SVG такой же, загрузите файл SVG, используйте соответствующие параметры сохранения изображения и вызовите метод сохранения. Image API предоставляет [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) для настройки PageWidth, PageHeight и растровых изображений, используя их свойство VectorRasterizationOptions для инициализации и получения параметров SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="Код С# для преобразования SVG в растровые изображения" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG к BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG к JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ru/net/conversion/SVG-to-png/" style="padding:15px;">SVG к PNG</a></p>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Все поддерживаемые форматы изображений для конвертации из" %}}
Ниже представлен полный список форматов изображений, в которые вы можете конвертировать:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/apng/" style="padding:15px;">Конвертировать из APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/bmp/" style="padding:15px;">Конвертировать из BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/dib/" style="padding:15px;">Конвертировать из DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/dicom/" style="padding:15px;">Конвертировать из DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/djvu/" style="padding:15px;">Конвертировать из DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/dng/" style="padding:15px;">Конвертировать из DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/emf/" style="padding:15px;">Конвертировать из EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/emz/" style="padding:15px;">Конвертировать из EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/gif/" style="padding:15px;">Конвертировать из GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/jpeg2000/" style="padding:15px;">Конвертировать из JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/jp2/" style="padding:15px;">Конвертировать из JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/j2k/" style="padding:15px;">Конвертировать из J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/jpg/" style="padding:15px;">Конвертировать из JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/jpeg/" style="padding:15px;">Конвертировать из JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/png/" style="padding:15px;">Конвертировать из PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/tga/" style="padding:15px;">Конвертировать из TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/tif/" style="padding:15px;">Конвертировать из TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/tiff/" style="padding:15px;">Конвертировать из TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/webp/" style="padding:15px;">Конвертировать из WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/wmf/" style="padding:15px;">Конвертировать из WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/wmz/" style="padding:15px;">Конвертировать из WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/svg/" style="padding:15px;">Конвертировать из SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/svgz/" style="padding:15px;">Конвертировать из SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/eps/" style="padding:15px;">Конвертировать из EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/cdr/" style="padding:15px;">Конвертировать из CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/cmx/" style="padding:15px;">Конвертировать из CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/otg/" style="padding:15px;">Конвертировать из OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/odg/" style="padding:15px;">Конвертировать из ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/ico/" style="padding:15px;">Конвертировать из ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/from/avif/" style="padding:15px;">Конвертировать из AVIF</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Все поддерживаемые форматы изображений для преобразования в" %}}
Ниже представлен полный список форматов изображений, из которых вы можете конвертировать:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/bmp/" style="padding:15px;">Преобразовать в BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/gif/" style="padding:15px;">Преобразовать в GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/dicom/" style="padding:15px;">Преобразовать в DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/emf/" style="padding:15px;">Преобразовать в EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/jpg/" style="padding:15px;">Преобразовать в JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/jpeg/" style="padding:15px;">Преобразовать в JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/jp2/" style="padding:15px;">Преобразовать в JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/j2k/" style="padding:15px;">Преобразовать в J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/jpeg2000/" style="padding:15px;">Преобразовать в JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/png/" style="padding:15px;">Преобразовать в PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/psd/" style="padding:15px;">Преобразовать в PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/dxf/" style="padding:15px;">Преобразовать в DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/svg/" style="padding:15px;">Преобразовать в SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/tiff/" style="padding:15px;">Преобразовать в TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/webp/" style="padding:15px;">Преобразовать в WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/wmf/" style="padding:15px;">Преобразовать в WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/pdf/" style="padding:15px;">Преобразовать в PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/html/" style="padding:15px;">Преобразовать в HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/emz/" style="padding:15px;">Преобразовать в EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/wmz/" style="padding:15px;">Преобразовать в WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/tga/" style="padding:15px;">Преобразовать в TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/svgz/" style="padding:15px;">Преобразовать в SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/canvas/" style="padding:15px;">Преобразовать в CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/ico/" style="padding:15px;">Преобразовать в ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ru/net/conversion/to/apng/" style="padding:15px;">Преобразовать в APNG</a></div>
                </div>
        </div>
    </div>
</div>

