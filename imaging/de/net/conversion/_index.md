
---
title: Konvertierung von C#-Bildformaten 
weight: 3920
url: /de/net/conversion/ 
lang: de
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Konvertieren Sie beliebte Bild-, Foto- und Bildformate über die .NET-Bibliothek. Konvertieren Sie mit wenigen Zeilen C#-Code in PSD, PDF, GIF, JPG, SVG einschließlich HTML5 Canvas.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertierung von Bilddateien über C#" h2="Konvertieren Sie Bildformate, Metafiles, WebP, Svg, Apng, um plattformübergreifende .NET-basierte fortschrittliche Bildverarbeitungsanwendungen zu erstellen." downloadText="Download" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API vereinfacht die erweiterte Bildverarbeitung und Rendering-Funktionen für Programmierer. Entwickler können es integrieren, um Raster- und Vektorbilder, einschließlich Fotos und Bilder, in PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF und andere Bildformate zu konvertieren . Die API befasst sich nicht nur mit der Konvertierung von Dateien, sondern auch mit der Konvertierung von Bildern in Schwarzweiß und Graustufen, der Konvertierung von GIF-Bildebenen und mehr.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Bild in Bitmap BMP, JPG, PNG konvertieren" %}}

Mit der C#-Bild-API ist die Interformat-Konvertierung so einfach wie das Ändern der Erweiterung des gewünschten Formats. Hier sind einige generische Fälle wie **Bild zu BMP**, **Bild zu JPG**, **Bild zu PNG**, die Entwickler leicht für ihr spezifisches Format verbessern können. Der Prozess lädt das Quellbild über [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Erstellen Sie ein Zielobjekt [Bildformatoptionen](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) für alle spezifischen Einstellungen. Rufen Sie schließlich die [Save-Methode](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) auf, indem Sie die Zieldatei mit Pfad und Speicheroptionen als Parameter übergeben.

{{% blocks/products/pf/feature-page-code h3="C#-Code für die Interkonvertierung von Bildern" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/apng-to-bmp/" style="padding:15px;">APNG zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/dib-to-bmp/" style="padding:15px;">DIB zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM zu BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/dng-to-bmp/" style="padding:15px;">DNG zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/emf-to-bmp/" style="padding:15px;">EMF zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/eps-to-bmp/" style="padding:15px;">EPS zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/gif-to-bmp/" style="padding:15px;">GIF zu BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Umwandlung von Rasterbildern in PDF" %}}

Der Vorgang zum Konvertieren von Rasterbildern in PDF ist derselbe wie bei der Interkonvertierung von Bildern, außer dass die API [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) für bestimmte PDF-Einstellungen bereitstellt . Programmierer können es leicht für ihre spezifischen Bedürfnisse erweitern.

{{% blocks/products/pf/feature-page-code h3="Code für die Umwandlung von Rasterbildern in PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/apng-to-PDF/" style="padding:15px;">APNG zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/odg-to-PDF/" style="padding:15px;">ODG zu PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/otg-to-PDF/" style="padding:15px;">OTG zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/png-to-PDF/" style="padding:15px;">PNG zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/svg-to-PDF/" style="padding:15px;">SVG zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/eps-to-PDF/" style="padding:15px;">EPS zu PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/gif-to-PDF/" style="padding:15px;">GIF zu PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Konvertieren Sie SVG in Rasterbilder BMP, PNG, JPG" %}}

Der Konvertierungsprozess von SVG ist derselbe, SVG-Datei laden, relevante Bildspeicheroptionen verwenden und die Save-Methode aufrufen. Die Bild-API bietet [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) zum Festlegen von PageWidth, PageHeight und Rasterbildern, die ihre VectorRasterizationOptions-Eigenschaft zum Initialisieren und Abrufen von SVGRasterizationOptions-Optionen verwenden. 

{{% blocks/products/pf/feature-page-code h3="C#-Code für SVG zu Rasterbildern" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG zu BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG zu JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/de/net/conversion/SVG-to-png/" style="padding:15px;">SVG zu PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Alle unterstützten Bildformate zum Konvertieren von" %}}
Nachfolgend finden Sie eine vollständige Liste der Bildformate, in die Sie konvertieren können:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/apng/" style="padding:15px;">Konvertieren von APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/bmp/" style="padding:15px;">Konvertieren von BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/dib/" style="padding:15px;">Konvertieren von DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/dicom/" style="padding:15px;">Konvertieren von DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/djvu/" style="padding:15px;">Konvertieren von DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/dng/" style="padding:15px;">Konvertieren von DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/emf/" style="padding:15px;">Konvertieren von EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/emz/" style="padding:15px;">Konvertieren von EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/gif/" style="padding:15px;">Konvertieren von GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/jpeg2000/" style="padding:15px;">Konvertieren von JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/jp2/" style="padding:15px;">Konvertieren von JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/j2k/" style="padding:15px;">Konvertieren von J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/jpg/" style="padding:15px;">Konvertieren von JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/jpeg/" style="padding:15px;">Konvertieren von JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/png/" style="padding:15px;">Konvertieren von PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/tga/" style="padding:15px;">Konvertieren von TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/tif/" style="padding:15px;">Konvertieren von TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/tiff/" style="padding:15px;">Konvertieren von TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/webp/" style="padding:15px;">Konvertieren von WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/wmf/" style="padding:15px;">Konvertieren von WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/wmz/" style="padding:15px;">Konvertieren von WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/svg/" style="padding:15px;">Konvertieren von SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/svgz/" style="padding:15px;">Konvertieren von SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/eps/" style="padding:15px;">Konvertieren von EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/cdr/" style="padding:15px;">Konvertieren von CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/cmx/" style="padding:15px;">Konvertieren von CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/otg/" style="padding:15px;">Konvertieren von OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/odg/" style="padding:15px;">Konvertieren von ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/from/ico/" style="padding:15px;">Konvertieren von ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Alle unterstützten Bildformate zum Konvertieren" %}}
Nachfolgend finden Sie eine vollständige Liste der Bildformate, aus denen Sie konvertieren können:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/bmp/" style="padding:15px;">Konvertieren zu BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/gif/" style="padding:15px;">Konvertieren zu GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/dicom/" style="padding:15px;">Konvertieren zu DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/emf/" style="padding:15px;">Konvertieren zu EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/jpg/" style="padding:15px;">Konvertieren zu JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/jpeg/" style="padding:15px;">Konvertieren zu JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/jp2/" style="padding:15px;">Konvertieren zu JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/j2k/" style="padding:15px;">Konvertieren zu J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/jpeg2000/" style="padding:15px;">Konvertieren zu JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/png/" style="padding:15px;">Konvertieren zu PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/psd/" style="padding:15px;">Konvertieren zu PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/dxf/" style="padding:15px;">Konvertieren zu DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/svg/" style="padding:15px;">Konvertieren zu SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/tiff/" style="padding:15px;">Konvertieren zu TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/webp/" style="padding:15px;">Konvertieren zu WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/wmf/" style="padding:15px;">Konvertieren zu WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/pdf/" style="padding:15px;">Konvertieren zu PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/html/" style="padding:15px;">Konvertieren zu HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/emz/" style="padding:15px;">Konvertieren zu EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/wmz/" style="padding:15px;">Konvertieren zu WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/tga/" style="padding:15px;">Konvertieren zu TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/svgz/" style="padding:15px;">Konvertieren zu SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/canvas/" style="padding:15px;">Konvertieren zu CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/ico/" style="padding:15px;">Konvertieren zu ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/de/net/conversion/to/apng/" style="padding:15px;">Konvertieren zu APNG</a></div>
                </div>
        </div>
    </div>
</div>

