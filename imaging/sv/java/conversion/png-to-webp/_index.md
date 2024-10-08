﻿---
title: Konvertera PNG till WEBP via Java 
weight: 3920
url: /sv/java/conversion/png-to-webp/ 
lang: sv
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Exempelkod för Java-konvertering från PNG till WEBP. Använd API-exempelkod för batch-PNG-filer till WEBP-konvertering inom alla Java-baserade webb- eller skrivbordsapplikationer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertera PNG till WEBP via Java" h2="Förvandla PNG till WEBP med inbyggda Java API:er utan att behöva någon bildredigerare eller tredjepartsbibliotek." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="WEBP" pfName="Aspose.Imaging" subTitlepfName="för Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="för Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/sv/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/sv/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API Hem" codeSamplesText="Kodprover" liveDemosText="Livedemos" downloadText="Ladda ner" learnText="Lära sig" overviewText="Översikt" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar PNG till WEBP med Java" %}}

Att konvertera filformat kan verka som en rutinuppgift för grafiska designers. Ändå skulle det vara ett misstag att underskatta dess betydelse. Utvärderingen av ditt arbete kan bero på hur snabbt och effektivt du tar dig an denna uppgift. Vanligtvis behöver originalbilder konverteras till format som är bättre lämpade för utskrift eller onlinepublicering. Om originalbilden kommer från en grafisk editor kan den vara i vektorformat. I det här scenariot måste det rastreras och konverteras till ett rasterformat för publiceringsändamål. Du kan välja att spara bilden i ett okomprimerat format för optimal kvalitet eller konvertera den till ett förlustfritt komprimerat format för att minska filstorleken. I vissa sammanhang, som webbpublicering, kan du välja komprimerade format med förlust. Speciellt utformade algoritmer för bilddatakomprimering tillåter en betydande minskning av filstorleken samtidigt som acceptabel bildkvalitet bevaras. Detta underlättar snabb nedladdning av bildfiler från internet. För att konvertera PNG till WEBP använder vi [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API som är ett funktionsrikt, kraftfullt och lättanvänt API för bildmanipulation och konvertering för Java-plattformen. Du kan ladda ner den senaste versionen direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) och installera den i din Maven -baserat projekt genom att lägga till följande konfigurationer till pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera PNG till WEBP via Java" %}}

{{% blocks/products/pf/agp/text %}}

Utvecklare kan enkelt ladda och konvertera PNG-filer till WEBP på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

+ Ladda PNG-filen med metoden Image.load
+ Skapa och ställ in instansen av nödvändig underklass av ImageOptionsBase (t.ex. BmpOptions, PngOptions, etc.)
+ Anropa metoden Image.save
+ Skicka filsökväg med tillägget WEBP och objekt i klassen ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

Innan du kör koden för konverteringsexempel, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

+ Operativsystem: Windows eller Linux.
+ Utvecklingsmiljö: Stöder .NET Core 7 och högre, såsom Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Gratis app för att konvertera PNG till WEBP"
        appName="Conversion"
        extension="PNG-to-WEBP"
        label1="Välj eller dra och släpp PNG-bild"
        label2="Välj format och klicka på knappen Konvertera"
        label3="Klicka på knappen Ladda ned för att ladda ner WEBP-bild"
        checkFreeAppLabel="Kolla in våra [live-demos för att konvertera PNG till WEBP]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/PNG-to-WEBP)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertera PNG till WEBP - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" whatIsFormat1="Vad är" whatIsFormat2="Filformat" readMoreFormat="Läs mer | PNG">}}
PNG, Portable Network Graphics, hänvisar till en typ av rasterbildsfilformat som använder förlustfri komprimering. Det här filformatet skapades som en ersättning för Graphics Interchange Format (GIF) och har inga upphovsrättsliga begränsningar. PNG-filformat stöder dock inte animationer. PNG-filformatet stöder förlustfri bildkomprimering som gör det populärt bland sina användare. Med tidens gång har PNG utvecklats till ett av de mest använda bildfilformaten. Nästan alla operativsystem har stöd för att öppna PNG-filer. Till exempel har Microsoft Windows Viewer förmågan att öppna PNG-filer eftersom operativsystemet som standard har stödet tillgängligt som en del av installationen.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WEBP" readMoreLink="https://docs.fileformat.com/image/webp/" whatIsFormat1="Vad är" whatIsFormat2="Filformat" readMoreFormat="Läs mer | WEBP">}}
WebP, introducerat av Google, är ett modernt rasterwebbbildsfilformat som är baserat på förlustfri och förlustfri komprimering. Den ger samma bildkvalitet samtidigt som den minskar bildstorleken avsevärt. Eftersom de flesta webbsidor använder bilder som effektiv representation av data, resulterar användningen av WebP-bilder på webbsidor i snabbare inläsning av webbsidor. Enligt Google är WebP-förlustfria bilder 26 % mindre i storlek jämfört med PNG-bilder, medan WebP-förlustfria bilder är 25-34 % mindre än jämförbara JPEG-bilder. Bilder jämförs baserat på SSIM-indexet (Structural Similarity) mellan WebP och andra bildfilformat. WebP är ett systerprojekt av WebM multimediacontainerformat.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Med hjälp av Java kan man enkelt konvertera olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-bmp/" name="BMP" description="Bitmap bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-gif/" name="GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-dicom/" name="DICOM" description="Digital bildbehandling och kommunikation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-emf/" name="EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-jpg/" name="JPG" description="Förenade Fotografers Expert Grupp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-jpeg/" name="JPEG" description="Förenade Fotografers Expert Grupp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-j2k/" name="J2K" description="Wavelet komprimerad bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-apng/" name="APNG" description="Animerad bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-psd/" name="PSD" description="Photoshop-dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-dxf/" name="DXF" description="Drawing Interchange Format, eller Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-svg/" name="SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-tiff/" name="TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-webp/" name="WEBP" description="Raster webbbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-wmf/" name="WMF" description="Microsoft Windows metafil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-pdf/" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-html/" name="HTML" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-emz/" name="EMZ" description="Windows komprimerad förbättrad metafil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-wmz/" name="WMZ" description="Komprimerat Windows Media Player-skal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-tga/" name="TGA" description="Targa grafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-svgz/" name="SVGZ" description="Komprimerad version av Scalable Vector Graphics-fil (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-canvas/" name="CANVAS" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/java/conversion/png-to-ico/" name="ICO" description="Windows-ikonen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
