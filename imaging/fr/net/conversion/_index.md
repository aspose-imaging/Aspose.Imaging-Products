
---
title: Conversion des formats d'images C# 
weight: 3920
url: /fr/net/conversion/ 
lang: fr
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Convertissez les formats d'image, de photo et d'image populaires via la bibliothèque .NET. Convertir en PSD, PDF, GIF, JPG, SVG, y compris HTML5 Canvas avec quelques lignes de code C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversion de fichiers image via C#" h2="Convertissez les formats d'image, les métafichiers, WebP, Svg, Apng pour créer des applications de traitement d'image avancées multiplateformes basées sur .NET." downloadText="Télécharger" >}}

{{% blocks/products/pf/feature-page-summary %}}

L'API d'image .NET facilite les fonctionnalités avancées de traitement et de rendu d'image pour les programmeurs. Les développeurs peuvent l'intégrer pour convertir des images raster et vectorielles, y compris des photos et des images en PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF et d'autres formats d'image . L'API traite non seulement de la conversion des fichiers, mais également de la conversion des images en noir et blanc et en niveaux de gris, de la conversion des calques d'image GIF, etc.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir une image en bitmap BMP, JPG, PNG" %}}

À l'aide de l'API d'image C #, la conversion inter-format est aussi simple que de simplement changer l'extension du format souhaité. Voici quelques cas génériques tels que **image en bmp**, **image en jpg**, **image en png** et les développeurs peuvent facilement améliorer leur format spécifique. Le processus consiste à charger l'image source via [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Créez un objet de cible [options de format d'image](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) pour tous les paramètres spécifiques. Enfin, appelez la [Save Method](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) en transmettant le fichier cible avec le chemin et les options d'enregistrement en tant que paramètre.

{{% blocks/products/pf/feature-page-code h3="Code C# pour l'inter-conversion d'images" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/apng-to-bmp/" style="padding:15px;">APNG à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/dib-to-bmp/" style="padding:15px;">DIB à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM à BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/dng-to-bmp/" style="padding:15px;">DNG à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/emf-to-bmp/" style="padding:15px;">EMF à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/eps-to-bmp/" style="padding:15px;">EPS à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/gif-to-bmp/" style="padding:15px;">GIF à BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Conversion d'image raster en PDF" %}}

Le processus de conversion des images raster en PDF est le même que celui de la conversion inter-images, sauf que l'API fournit [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) pour des paramètres PDF spécifiques . Les programmeurs peuvent facilement l'améliorer pour leurs besoins spécifiques.

{{% blocks/products/pf/feature-page-code h3="Code pour la conversion d'images raster en PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/apng-to-PDF/" style="padding:15px;">APNG à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/odg-to-PDF/" style="padding:15px;">ODG à PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/otg-to-PDF/" style="padding:15px;">OTG à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/png-to-PDF/" style="padding:15px;">PNG à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/svg-to-PDF/" style="padding:15px;">SVG à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/eps-to-PDF/" style="padding:15px;">EPS à PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/gif-to-PDF/" style="padding:15px;">GIF à PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Convertir SVG en images raster BMP, PNG, JPG" %}}

Le processus de conversion de SVG est le même, chargez le fichier SVG, utilisez les options d'enregistrement d'image pertinentes et appelez la méthode Save. L'API d'image fournit [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) pour définir PageWidth, PageHeight et les images raster utilisent leur propriété VectorRasterizationOptions pour l'initialisation et l'obtention des options SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="Code C# pour SVG en images raster" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG à BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG à JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/fr/net/conversion/SVG-to-png/" style="padding:15px;">SVG à PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Tous les images formats pris en charge à partir desquels convertir" %}}
Vous trouverez ci-dessous la liste complète des formats d'image vers lesquels vous pouvez convertir :
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/apng/" style="padding:15px;">Convertir à partir de APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/bmp/" style="padding:15px;">Convertir à partir de BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/dib/" style="padding:15px;">Convertir à partir de DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/dicom/" style="padding:15px;">Convertir à partir de DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/djvu/" style="padding:15px;">Convertir à partir de DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/dng/" style="padding:15px;">Convertir à partir de DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/emf/" style="padding:15px;">Convertir à partir de EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/emz/" style="padding:15px;">Convertir à partir de EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/gif/" style="padding:15px;">Convertir à partir de GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/jpeg2000/" style="padding:15px;">Convertir à partir de JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/jp2/" style="padding:15px;">Convertir à partir de JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/j2k/" style="padding:15px;">Convertir à partir de J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/jpg/" style="padding:15px;">Convertir à partir de JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/jpeg/" style="padding:15px;">Convertir à partir de JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/png/" style="padding:15px;">Convertir à partir de PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/tga/" style="padding:15px;">Convertir à partir de TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/tif/" style="padding:15px;">Convertir à partir de TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/tiff/" style="padding:15px;">Convertir à partir de TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/webp/" style="padding:15px;">Convertir à partir de WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/wmf/" style="padding:15px;">Convertir à partir de WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/wmz/" style="padding:15px;">Convertir à partir de WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/svg/" style="padding:15px;">Convertir à partir de SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/svgz/" style="padding:15px;">Convertir à partir de SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/eps/" style="padding:15px;">Convertir à partir de EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/cdr/" style="padding:15px;">Convertir à partir de CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/cmx/" style="padding:15px;">Convertir à partir de CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/otg/" style="padding:15px;">Convertir à partir de OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/odg/" style="padding:15px;">Convertir à partir de ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/from/ico/" style="padding:15px;">Convertir à partir de ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Tous les formats d'image pris en charge pour convertir" %}}
Vous trouverez ci-dessous la liste complète des formats d'image à partir desquels vous pouvez convertir :
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/bmp/" style="padding:15px;">Convertir en BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/gif/" style="padding:15px;">Convertir en GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/dicom/" style="padding:15px;">Convertir en DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/emf/" style="padding:15px;">Convertir en EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/jpg/" style="padding:15px;">Convertir en JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/jpeg/" style="padding:15px;">Convertir en JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/jp2/" style="padding:15px;">Convertir en JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/j2k/" style="padding:15px;">Convertir en J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/jpeg2000/" style="padding:15px;">Convertir en JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/png/" style="padding:15px;">Convertir en PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/psd/" style="padding:15px;">Convertir en PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/dxf/" style="padding:15px;">Convertir en DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/svg/" style="padding:15px;">Convertir en SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/tiff/" style="padding:15px;">Convertir en TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/webp/" style="padding:15px;">Convertir en WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/wmf/" style="padding:15px;">Convertir en WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/pdf/" style="padding:15px;">Convertir en PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/html/" style="padding:15px;">Convertir en HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/emz/" style="padding:15px;">Convertir en EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/wmz/" style="padding:15px;">Convertir en WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/tga/" style="padding:15px;">Convertir en TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/svgz/" style="padding:15px;">Convertir en SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/canvas/" style="padding:15px;">Convertir en CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/ico/" style="padding:15px;">Convertir en ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/fr/net/conversion/to/apng/" style="padding:15px;">Convertir en APNG</a></div>
                </div>
        </div>
    </div>
</div>

