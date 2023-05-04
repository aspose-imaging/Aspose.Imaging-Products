
---
title: C# bildformatskonvertering 
weight: 3920
url: /sv/net/conversion 
lang: sv
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Konvertera populära bild-, foto- och bildformat via .NET-biblioteket. Konvertera till PSD, PDF, GIF, JPG, SVG inklusive HTML5 Canvas med några rader C#-kod.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertering av bildfiler via C#" h2="Konvertera bildformat, metafiler, WebP, Svg, Apng för att bygga plattformsoberoende .NET-baserade avancerade bildbehandlingsapplikationer." downloadText="Ladda ner" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API underlättar avancerade bildbehandlings- och renderingsfunktioner för programmerare. Utvecklare kan integrera den för att konvertera raster- och vektorbilder, inklusive foton och bilder till PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF och andra bildformat . API hanterar inte bara konvertering av filer utan handlar också om att konvertera bilder till svartvitt och gråskala, konvertera GIF-bildlager och mer.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertera bild till bitmapp BMP, JPG, PNG" %}}

Genom att använda C# Image API, är Inter-formatkonvertering lika enkelt som att bara ändra förlängningen av det önskade formatet. Här är några allmänna fall som **bild till bmp**, **bild till jpg**, **bild till png** och utvecklare kan enkelt förbättra för sitt specifika format. Processen är att ladda källbilden via [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Skapa ett målobjekt [bildformatalternativ](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) för alla specifika inställningar. Anropa slutligen [Save Method](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) genom att skicka målfilen med sökväg och Spara alternativ som parameter.

{{% blocks/products/pf/feature-page-code h3="C#-kod för interkonvertering av bilder" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/apng-to-bmp/" style="padding:15px;">APNG till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/dib-to-bmp/" style="padding:15px;">DIB till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM till BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/dng-to-bmp/" style="padding:15px;">DNG till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/emf-to-bmp/" style="padding:15px;">EMF till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/eps-to-bmp/" style="padding:15px;">EPS till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/gif-to-bmp/" style="padding:15px;">GIF till BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Rasterbild till PDF-konvertering" %}}

Processen för att konvertera rasterbilder till PDF är densamma som för interkonvertering av bilder, förutom att API tillhandahåller [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) för specifika PDF-inställningar . Programmerare kan enkelt förbättra den för deras specifika behov.

{{% blocks/products/pf/feature-page-code h3="Kod för konvertering av rasterbilder till PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/apng-to-PDF/" style="padding:15px;">APNG till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/odg-to-PDF/" style="padding:15px;">ODG till PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/otg-to-PDF/" style="padding:15px;">OTG till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/png-to-PDF/" style="padding:15px;">PNG till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/svg-to-PDF/" style="padding:15px;">SVG till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/eps-to-PDF/" style="padding:15px;">EPS till PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/gif-to-PDF/" style="padding:15px;">GIF till PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Konvertera SVG till rasterbilder BMP, PNG, JPG" %}}

Konverteringsprocessen för SVG är densamma, Ladda SVG-fil, Använd relevanta bildsparalternativ och anrop Spara-metoden. Bild-API tillhandahåller [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) för att ställa in PageWidth, PageHeight och rasterbilder använder deras VectorRasterizationOptions-egenskap för initiering och för att få SvgRasterizationOptions-alternativ. 

{{% blocks/products/pf/feature-page-code h3="C#-kod för SVG till rasterbilder" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG till BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG till JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/sv/net/conversion/SVG-to-png/" style="padding:15px;">SVG till PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Alla bilder format som stöds att konvertera från" %}}
Nedan presenteras en fullständig lista över bildformat som du kan konvertera till:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/apng" style="padding:15px;">Konvertera från APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/bmp" style="padding:15px;">Konvertera från BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/dib" style="padding:15px;">Konvertera från DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/dicom" style="padding:15px;">Konvertera från DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/djvu" style="padding:15px;">Konvertera från DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/dng" style="padding:15px;">Konvertera från DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/emf" style="padding:15px;">Konvertera från EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/emz" style="padding:15px;">Konvertera från EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/gif" style="padding:15px;">Konvertera från GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/jpeg2000" style="padding:15px;">Konvertera från JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/jp2" style="padding:15px;">Konvertera från JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/j2k" style="padding:15px;">Konvertera från J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/jpg" style="padding:15px;">Konvertera från JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/jpeg" style="padding:15px;">Konvertera från JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/png" style="padding:15px;">Konvertera från PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/tga" style="padding:15px;">Konvertera från TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/tif" style="padding:15px;">Konvertera från TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/tiff" style="padding:15px;">Konvertera från TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/webp" style="padding:15px;">Konvertera från WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/wmf" style="padding:15px;">Konvertera från WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/wmz" style="padding:15px;">Konvertera från WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/svg" style="padding:15px;">Konvertera från SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/svgz" style="padding:15px;">Konvertera från SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/eps" style="padding:15px;">Konvertera från EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/cdr" style="padding:15px;">Konvertera från CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/cmx" style="padding:15px;">Konvertera från CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/otg" style="padding:15px;">Konvertera från OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/odg" style="padding:15px;">Konvertera från ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/from/ico" style="padding:15px;">Konvertera från ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Alla bildformat som stöds att konvertera till" %}}
Nedan presenteras en fullständig lista över bildformat som du kan konvertera från:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/bmp" style="padding:15px;">Konvertera till BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/gif" style="padding:15px;">Konvertera till GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/dicom" style="padding:15px;">Konvertera till DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/emf" style="padding:15px;">Konvertera till EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/jpg" style="padding:15px;">Konvertera till JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/jpeg" style="padding:15px;">Konvertera till JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/jp2" style="padding:15px;">Konvertera till JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/j2k" style="padding:15px;">Konvertera till J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/jpeg2000" style="padding:15px;">Konvertera till JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/png" style="padding:15px;">Konvertera till PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/psd" style="padding:15px;">Konvertera till PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/dxf" style="padding:15px;">Konvertera till DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/svg" style="padding:15px;">Konvertera till SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/tiff" style="padding:15px;">Konvertera till TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/webp" style="padding:15px;">Konvertera till WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/wmf" style="padding:15px;">Konvertera till WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/pdf" style="padding:15px;">Konvertera till PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/html" style="padding:15px;">Konvertera till HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/emz" style="padding:15px;">Konvertera till EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/wmz" style="padding:15px;">Konvertera till WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/tga" style="padding:15px;">Konvertera till TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/svgz" style="padding:15px;">Konvertera till SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/canvas" style="padding:15px;">Konvertera till CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/ico" style="padding:15px;">Konvertera till ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/sv/net/conversion/to/apng" style="padding:15px;">Konvertera till APNG</a></div>
                </div>
        </div>
    </div>
</div>

