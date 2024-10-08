﻿---
title: Konvertera WEBP till TIFF via Java 
weight: 3920
url: /sv/java/conversion/webp-to-tiff/ 
lang: sv
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Exempelkod för Java-konvertering från WEBP till TIFF. Använd API-exempelkod för batch-WEBP-filer till TIFF-konvertering inom alla Java-baserade webb- eller skrivbordsapplikationer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertera WEBP till TIFF via Java" h2="Förvandla WEBP till TIFF med inbyggda Java API:er utan att behöva någon bildredigerare eller tredjepartsbibliotek." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="Aspose.Imaging" subTitlepfName="för Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="för Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/sv/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/sv/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API Hem" codeSamplesText="Kodprover" liveDemosText="Livedemos" downloadText="Ladda ner" learnText="Lära sig" overviewText="Översikt" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar WEBP till TIFF med Java" %}}

Att konvertera filformat kan verka som en rutinuppgift för grafiska designers. Ändå skulle det vara ett misstag att underskatta dess betydelse. Utvärderingen av ditt arbete kan bero på hur snabbt och effektivt du tar dig an denna uppgift. Vanligtvis behöver originalbilder konverteras till format som är bättre lämpade för utskrift eller onlinepublicering. Om originalbilden kommer från en grafisk editor kan den vara i vektorformat. I det här scenariot måste det rastreras och konverteras till ett rasterformat för publiceringsändamål. Du kan välja att spara bilden i ett okomprimerat format för optimal kvalitet eller konvertera den till ett förlustfritt komprimerat format för att minska filstorleken. I vissa sammanhang, som webbpublicering, kan du välja komprimerade format med förlust. Speciellt utformade algoritmer för bilddatakomprimering tillåter en betydande minskning av filstorleken samtidigt som acceptabel bildkvalitet bevaras. Detta underlättar snabb nedladdning av bildfiler från internet. För att konvertera WEBP till TIFF använder vi [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API som är ett funktionsrikt, kraftfullt och lättanvänt API för bildmanipulation och konvertering för Java-plattformen. Du kan ladda ner den senaste versionen direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) och installera den i din Maven -baserat projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

``` xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroende" offSpacer="true" %}}

``` xml
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-imaging</artifactId>
<version>version of aspose-imaging API</version>
<classifier>jdk16</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera WEBP till TIFF via Java" %}}

{{% blocks/products/pf/agp/text %}}

Utvecklare kan enkelt ladda och konvertera WEBP-filer till TIFF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

+ Ladda WEBP-filen med metoden Image.load
+ Skapa och ställ in instansen av nödvändig underklass av ImageOptionsBase (t.ex. BmpOptions, PngOptions, etc.)
+ Anropa metoden Image.save
+ Skicka filsökväg med tillägget TIFF och objekt i klassen ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

Innan du kör koden för konverteringsexempel, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

+ Operativsystem: Windows eller Linux.
+ Utvecklingsmiljö: Stöder .NET Core 7 och högre, såsom Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Gratis app för att konvertera WEBP till TIFF"
        appName="Conversion"
        extension="WEBP-to-TIFF"
        label1="Välj eller dra och släpp WEBP-bild"
        label2="Välj format och klicka på knappen Konvertera"
        label3="Klicka på knappen Ladda ned för att ladda ner TIFF-bild"
        checkFreeAppLabel="Kolla in våra [live-demos för att konvertera WEBP till TIFF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/WEBP-to-TIFF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertera WEBP till TIFF - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WEBP" readMoreLink="https://docs.fileformat.com/image/webp/" whatIsFormat1="Vad är" whatIsFormat2="Filformat" readMoreFormat="Läs mer | WEBP">}}
WebP, introducerat av Google, är ett modernt rasterwebbbildsfilformat som är baserat på förlustfri och förlustfri komprimering. Den ger samma bildkvalitet samtidigt som den minskar bildstorleken avsevärt. Eftersom de flesta webbsidor använder bilder som effektiv representation av data, resulterar användningen av WebP-bilder på webbsidor i snabbare inläsning av webbsidor. Enligt Google är WebP-förlustfria bilder 26 % mindre i storlek jämfört med PNG-bilder, medan WebP-förlustfria bilder är 25-34 % mindre än jämförbara JPEG-bilder. Bilder jämförs baserat på SSIM-indexet (Structural Similarity) mellan WebP och andra bildfilformat. WebP är ett systerprojekt av WebM multimediacontainerformat.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" whatIsFormat1="Vad är" whatIsFormat2="Filformat" readMoreFormat="Läs mer | TIFF">}}
TIFF eller TIF, Tagged Image File Format, representerar rasterbilder som är avsedda för användning på en mängd olika enheter som överensstämmer med denna filformatstandard. Den kan beskriva bilevel-, gråskala-, palett-färg- och fullfärgsbilddata i flera färgrymder. Den stöder såväl förlustfria som förlustfria komprimeringssystem för att välja mellan utrymme och tid för applikationer som använder formatet. Formatet är utbyggbart och har genomgått flera revisioner som gör det möjligt att inkludera en obegränsad mängd privat eller specialinformation. Formatet är inte maskinberoende och är fritt från gränser som processor, operativsystem eller filsystem.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Med hjälp av Java kan man enkelt konvertera olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-bmp/" name="BMP" description="Bitmap bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-gif/" name="GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-dicom/" name="DICOM" description="Digital bildbehandling och kommunikation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-emf/" name="EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-jpg/" name="JPG" description="Förenade Fotografers Expert Grupp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-jpeg/" name="JPEG" description="Förenade Fotografers Expert Grupp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-j2k/" name="J2K" description="Wavelet komprimerad bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-png/" name="PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-apng/" name="APNG" description="Animerad bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-psd/" name="PSD" description="Photoshop-dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-dxf/" name="DXF" description="Drawing Interchange Format, eller Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-svg/" name="SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-tiff/" name="TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-wmf/" name="WMF" description="Microsoft Windows metafil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-pdf/" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-html/" name="HTML" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-emz/" name="EMZ" description="Windows komprimerad förbättrad metafil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-wmz/" name="WMZ" description="Komprimerat Windows Media Player-skal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-tga/" name="TGA" description="Targa grafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-svgz/" name="SVGZ" description="Komprimerad version av Scalable Vector Graphics-fil (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-canvas/" name="CANVAS" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/webp-to-ico/" name="ICO" description="Windows-ikonen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
