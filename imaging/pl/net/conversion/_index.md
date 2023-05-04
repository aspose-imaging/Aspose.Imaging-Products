
---
title: Konwersja formatów obrazów C# 
weight: 3920
url: /pl/net/conversion 
lang: pl
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Konwertuj popularne formaty obrazów, zdjęć, obrazów za pomocą biblioteki .NET. Konwertuj do PSD, PDF, GIF, JPG, SVG, w tym HTML5 Canvas z kilkoma linijkami kodu C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwersja plików graficznych za pomocą C#" h2="Konwertuj formaty obrazów, metapliki, WebP, Svg, Apng, aby tworzyć wieloplatformowe zaawansowane aplikacje do przetwarzania obrazu oparte na platformie .NET." downloadText="Ściągnij" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API ułatwia programistom zaawansowane przetwarzanie i renderowanie obrazów. Programiści mogą go zintegrować, aby konwertować obrazy rastrowe i wektorowe, w tym zdjęcia i obrazy do formatu PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF i innych formatów graficznych . API zajmuje się nie tylko konwersją plików, ale także konwersją obrazów do czerni i bieli oraz skali szarości, konwersją warstw obrazu GIF i nie tylko.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj obraz na bitmapę BMP, JPG, PNG" %}}

Korzystając z interfejsu C# Image API, konwersja formatu Inter jest tak prosta, jak zmiana rozszerzenia żądanego formatu. Oto kilka ogólnych przypadków, takich jak **obraz na bmp**, **obraz na jpg**, **obraz na png**, a programiści mogą łatwo ulepszyć swój format. Proces ładuje obraz źródłowy przez [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Utwórz obiekt docelowy [opcje formatu obrazu](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) dla dowolnych określonych ustawień. Na koniec wywołaj [Save Method](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4), przekazując plik docelowy ze ścieżką i opcjami zapisu jako parametrem.

{{% blocks/products/pf/feature-page-code h3="Kod C# do konwersji między obrazami" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/apng-to-bmp/" style="padding:15px;">APNG do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/dib-to-bmp/" style="padding:15px;">DIB do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM do BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/dng-to-bmp/" style="padding:15px;">DNG do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/emf-to-bmp/" style="padding:15px;">EMF do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/eps-to-bmp/" style="padding:15px;">EPS do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/gif-to-bmp/" style="padding:15px;">GIF do BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Konwersja obrazu rastrowego na PDF" %}}

Proces konwersji obrazów rastrowych do formatu PDF jest taki sam, jak w przypadku konwersji między obrazami, z wyjątkiem tego, że API zapewnia [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) dla określonych ustawień PDF . Programiści mogą łatwo dostosować go do swoich specyficznych potrzeb.

{{% blocks/products/pf/feature-page-code h3="Kod do konwersji obrazów rastrowych na PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/apng-to-PDF/" style="padding:15px;">APNG do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/odg-to-PDF/" style="padding:15px;">ODG do PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/otg-to-PDF/" style="padding:15px;">OTG do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/png-to-PDF/" style="padding:15px;">PNG do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/svg-to-PDF/" style="padding:15px;">SVG do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/eps-to-PDF/" style="padding:15px;">EPS do PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/gif-to-PDF/" style="padding:15px;">GIF do PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Konwersja SVG do obrazów rastrowych BMP, PNG, JPG" %}}

Proces konwersji SVG jest taki sam, Załaduj plik SVG, Użyj odpowiednich opcji zapisu obrazu i wywołaj metodę Save. Image API zapewnia [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) do ustawiania PageWidth, PageHeight i obrazów rastrowych ich właściwości VectorRasterizationOptions do inicjowania i pobierania opcji SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="Kod C# dla SVG do obrazów rastrowych" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG do BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG do JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/pl/net/conversion/SVG-to-png/" style="padding:15px;">SVG do PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Wszystkie obsługiwane formaty do konwersji" %}}
Poniżej znajduje się pełna lista formatów graficznych, do których można dokonać konwersji:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/apng" style="padding:15px;">Konwertuj z APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/bmp" style="padding:15px;">Konwertuj z BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/dib" style="padding:15px;">Konwertuj z DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/dicom" style="padding:15px;">Konwertuj z DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/djvu" style="padding:15px;">Konwertuj z DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/dng" style="padding:15px;">Konwertuj z DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/emf" style="padding:15px;">Konwertuj z EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/emz" style="padding:15px;">Konwertuj z EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/gif" style="padding:15px;">Konwertuj z GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/jpeg2000" style="padding:15px;">Konwertuj z JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/jp2" style="padding:15px;">Konwertuj z JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/j2k" style="padding:15px;">Konwertuj z J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/jpg" style="padding:15px;">Konwertuj z JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/jpeg" style="padding:15px;">Konwertuj z JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/png" style="padding:15px;">Konwertuj z PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/tga" style="padding:15px;">Konwertuj z TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/tif" style="padding:15px;">Konwertuj z TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/tiff" style="padding:15px;">Konwertuj z TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/webp" style="padding:15px;">Konwertuj z WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/wmf" style="padding:15px;">Konwertuj z WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/wmz" style="padding:15px;">Konwertuj z WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/svg" style="padding:15px;">Konwertuj z SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/svgz" style="padding:15px;">Konwertuj z SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/eps" style="padding:15px;">Konwertuj z EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/cdr" style="padding:15px;">Konwertuj z CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/cmx" style="padding:15px;">Konwertuj z CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/otg" style="padding:15px;">Konwertuj z OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/odg" style="padding:15px;">Konwertuj z ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/from/ico" style="padding:15px;">Konwertuj z ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Wszystkie obsługiwane formaty obrazów do konwersji" %}}
Poniżej znajduje się pełna lista formatów graficznych, z których możesz dokonać konwersji:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/bmp" style="padding:15px;">Konwertuj na BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/gif" style="padding:15px;">Konwertuj na GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/dicom" style="padding:15px;">Konwertuj na DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/emf" style="padding:15px;">Konwertuj na EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/jpg" style="padding:15px;">Konwertuj na JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/jpeg" style="padding:15px;">Konwertuj na JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/jp2" style="padding:15px;">Konwertuj na JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/j2k" style="padding:15px;">Konwertuj na J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/jpeg2000" style="padding:15px;">Konwertuj na JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/png" style="padding:15px;">Konwertuj na PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/psd" style="padding:15px;">Konwertuj na PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/dxf" style="padding:15px;">Konwertuj na DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/svg" style="padding:15px;">Konwertuj na SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/tiff" style="padding:15px;">Konwertuj na TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/webp" style="padding:15px;">Konwertuj na WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/wmf" style="padding:15px;">Konwertuj na WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/pdf" style="padding:15px;">Konwertuj na PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/html" style="padding:15px;">Konwertuj na HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/emz" style="padding:15px;">Konwertuj na EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/wmz" style="padding:15px;">Konwertuj na WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/tga" style="padding:15px;">Konwertuj na TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/svgz" style="padding:15px;">Konwertuj na SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/canvas" style="padding:15px;">Konwertuj na CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/ico" style="padding:15px;">Konwertuj na ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/pl/net/conversion/to/apng" style="padding:15px;">Konwertuj na APNG</a></div>
                </div>
        </div>
    </div>
</div>

