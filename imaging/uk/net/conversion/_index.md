
---
title: Перетворення форматів зображень C# 
weight: 3920
url: /uk/net/conversion/ 
lang: uk
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Перетворюйте популярні формати зображень, фото, зображень за допомогою бібліотеки .NET. Конвертуйте у PSD, PDF, GIF, JPG, SVG, включаючи HTML5 Canvas, за допомогою кількох рядків коду C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Перетворення файлів зображень через C#" h2="Перетворюйте формати зображень, метафайли, WebP, Svg, Apng для створення кросплатформних додатків для передової обробки зображень на основі .NET." downloadText="Завантажити" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API полегшує розширену обробку зображень і функції візуалізації для програмістів. Розробники можуть інтегрувати його для конвертації растрових і векторних зображень, включаючи фотографії та зображення, у формати PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF та інші. . API займається не лише перетворенням файлів, але й перетворенням зображень на чорно-біле та у градаціях сірого, перетворенням шарів зображень GIF тощо.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення зображення на растрове BMP, JPG, PNG" %}}

За допомогою C# Image API конвертувати формат Inter так само просто, як просто змінити розширення потрібного формату. Ось кілька загальних випадків, таких як **зображення в bmp**, **зображення в jpg**, **зображення в png**, і розробники можуть легко покращити для свого конкретного формату. Процес завантаження вихідного зображення через [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Створіть цільовий об’єкт [параметри формату зображення](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) для будь-яких конкретних налаштувань. Нарешті викличте [метод збереження](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4), передавши цільовий файл із шляхом і параметрами збереження.

{{% blocks/products/pf/feature-page-code h3="Код C# для внутрішнього перетворення зображень" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/apng-to-bmp/" style="padding:15px;">APNG до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/dib-to-bmp/" style="padding:15px;">DIB до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM до BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/dng-to-bmp/" style="padding:15px;">DNG до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/emf-to-bmp/" style="padding:15px;">EMF до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/eps-to-bmp/" style="padding:15px;">EPS до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/gif-to-bmp/" style="padding:15px;">GIF до BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Конвертація растрового зображення в PDF" %}}

Процес перетворення растрових зображень у PDF такий самий, як і процес внутрішнього перетворення зображень, за винятком того, що API надає [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) для певних налаштувань PDF . Програмісти можуть легко вдосконалити його для своїх конкретних потреб.

{{% blocks/products/pf/feature-page-code h3="Код для перетворення растрових зображень у PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/apng-to-PDF/" style="padding:15px;">APNG до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/odg-to-PDF/" style="padding:15px;">ODG до PDF</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/otg-to-PDF/" style="padding:15px;">OTG до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/png-to-PDF/" style="padding:15px;">PNG до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/svg-to-PDF/" style="padding:15px;">SVG до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/eps-to-PDF/" style="padding:15px;">EPS до PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/gif-to-PDF/" style="padding:15px;">GIF до PDF</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Перетворення SVG на растрові зображення BMP, PNG, JPG" %}}

Процес перетворення SVG такий самий, завантажте файл SVG, використайте відповідні параметри збереження зображення та виклик методу збереження. API зображень надає [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) для встановлення параметрів PageWidth, PageHeight, а растрові зображення використовують властивість VectorRasterizationOptions для ініціалізації та отримання параметрів SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="Код C# для SVG до растрових зображень" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG до BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG до JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/uk/net/conversion/SVG-to-png/" style="padding:15px;">SVG до PNG</a></p>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Усі підтримувані формати зображень для конвертації" %}}
Нижче наведено повний список форматів зображень, у які можна конвертувати:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/apng/" style="padding:15px;">Перетворити з APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/bmp/" style="padding:15px;">Перетворити з BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/dib/" style="padding:15px;">Перетворити з DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/dicom/" style="padding:15px;">Перетворити з DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/djvu/" style="padding:15px;">Перетворити з DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/dng/" style="padding:15px;">Перетворити з DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/emf/" style="padding:15px;">Перетворити з EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/emz/" style="padding:15px;">Перетворити з EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/gif/" style="padding:15px;">Перетворити з GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/jpeg2000/" style="padding:15px;">Перетворити з JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/jp2/" style="padding:15px;">Перетворити з JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/j2k/" style="padding:15px;">Перетворити з J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/jpg/" style="padding:15px;">Перетворити з JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/jpeg/" style="padding:15px;">Перетворити з JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/png/" style="padding:15px;">Перетворити з PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/tga/" style="padding:15px;">Перетворити з TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/tif/" style="padding:15px;">Перетворити з TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/tiff/" style="padding:15px;">Перетворити з TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/webp/" style="padding:15px;">Перетворити з WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/wmf/" style="padding:15px;">Перетворити з WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/wmz/" style="padding:15px;">Перетворити з WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/svg/" style="padding:15px;">Перетворити з SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/svgz/" style="padding:15px;">Перетворити з SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/eps/" style="padding:15px;">Перетворити з EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/cdr/" style="padding:15px;">Перетворити з CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/cmx/" style="padding:15px;">Перетворити з CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/otg/" style="padding:15px;">Перетворити з OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/odg/" style="padding:15px;">Перетворити з ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/from/ico/" style="padding:15px;">Перетворити з ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Усі підтримувані формати зображень для конвертації" %}}
Нижче наведено повний список форматів зображень, з яких можна конвертувати:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/bmp/" style="padding:15px;">Перетворити в BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/gif/" style="padding:15px;">Перетворити в GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/dicom/" style="padding:15px;">Перетворити в DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/emf/" style="padding:15px;">Перетворити в EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/jpg/" style="padding:15px;">Перетворити в JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/jpeg/" style="padding:15px;">Перетворити в JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/jp2/" style="padding:15px;">Перетворити в JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/j2k/" style="padding:15px;">Перетворити в J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/jpeg2000/" style="padding:15px;">Перетворити в JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/png/" style="padding:15px;">Перетворити в PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/psd/" style="padding:15px;">Перетворити в PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/dxf/" style="padding:15px;">Перетворити в DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/svg/" style="padding:15px;">Перетворити в SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/tiff/" style="padding:15px;">Перетворити в TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/webp/" style="padding:15px;">Перетворити в WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/wmf/" style="padding:15px;">Перетворити в WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/pdf/" style="padding:15px;">Перетворити в PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/html/" style="padding:15px;">Перетворити в HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/emz/" style="padding:15px;">Перетворити в EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/wmz/" style="padding:15px;">Перетворити в WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/tga/" style="padding:15px;">Перетворити в TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/svgz/" style="padding:15px;">Перетворити в SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/canvas/" style="padding:15px;">Перетворити в CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/ico/" style="padding:15px;">Перетворити в ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/uk/net/conversion/to/apng/" style="padding:15px;">Перетворити в APNG</a></div>
                </div>
        </div>
    </div>
</div>

