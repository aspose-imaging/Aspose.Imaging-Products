﻿---
title: Konvertering av bilder från ODG till PDF med Python 
weight: 3920
url: /sv/python-net/conversion/odg-to-pdf/ 
lang: sv
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Hur man använder Python för konvertering av bilder och foton från ODG till PDF på skrivbord och webbapplikationer.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Använd Python för bildkonvertering från ODG till PDF" h2="Skapa Python-appar för att konvertera ODG till PDF-bilder och foton via server-API:er" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.Imaging" subTitlepfName="för Python" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="för Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/sv/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/sv/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="API Hem" codeSamplesText="Kodprover" liveDemosText="Livedemos" downloadText="Ladda ner" learnText="Lära sig" overviewText="Översikt" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar ODG till PDF bilder och foton med Python" %}}

Konvertering av bildfiler från ett format till ett annat är en vanlig uppgift för alla grafiska designers. Effektiviteten och förträffligheten i att konvertera filer påverkar inte bara slutförandets hastighet utan spelar också en avgörande roll för att bedöma den övergripande arbetskvaliteten. När det gäller bildkällorna kräver de ofta omvandling till alternativa format som är mer lämpade för utskrift eller onlinedistribution. En bild skapad i en grafisk editor är sannolikt i vektorformat. I sådana fall, för webbplatspublicering, måste den genomgå rastrering och sparas i ett rasterformat. Du har möjlighet att konvertera bilden till ett okomprimerat format för överlägsen kvalitet eller spara den till ett förlustfritt komprimerat format för att minimera filstorleken. För scenarier där filstorleksminskning är obligatorisk, som i webbplatsapplikationer, finns möjligheten att konvertera till förlustformat komprimering. Specialiserade datakomprimeringsalgoritmer för bilder kan avsevärt minska filstorleken samtidigt som den upprätthåller acceptabel bildkvalitet, vilket säkerställer snabb bildladdning. För att konvertera bilder och foton från ODG till PDF kommer vi att använda [Aspose.Imaging for Python via .NET](/imaging/sv/python-net) API som är ett funktionsrikt, kraftfullt och lättanvänt API för bildmanipulation och konvertering för Python-plattformen. Du kan installera det med följande kommando från ditt systemkommando.

{{% blocks/products/pf/agp/code-block title="Systemets kommandorad" offSpacer="true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera ODG till PDF via Python" %}}

{{% blocks/products/pf/agp/text %}}

Utvecklare kan enkelt ladda och konvertera ODG-filer till PDF på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

+ Ladda ODG-fil med Image.Load-metoden
+ Skapa och ställ in instansen av nödvändig underklass av ImageOptionsBase (t.ex. BmpOptions, PngOptions, etc.)
+ Anropa Image.Save-metoden
+ Skicka filsökväg med tillägget PDF och objekt i klassen ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

Innan du kör koden för konverteringsexempel, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

+ Operativsystem: Windows eller Linux.
+ Utvecklingsmiljö: Stöder .NET Core 7 och högre, såsom Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Gratis app för att konvertera ODG till PDF"
        appName="Conversion"
        extension="ODG-to-PDF"
        label1="Välj eller dra och släpp ODG-bild"
        label2="Välj format och klicka på knappen Konvertera"
        label3="Klicka på knappen Ladda ned för att ladda ner PDF-bild"
        checkFreeAppLabel="Kolla in våra [live-demos för att konvertera ODG till PDF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/ODG-to-PDF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertera ODG till PDF - Python" offSpacer="true" %}}

{{< gist "aspose-com-gists" "e1d418ed58a1f4598f259e62914511d4" "convert-image-to-other-format.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="ODG" readMoreLink="https://docs.fileformat.com/image/odg/" whatIsFormat1="Vad är" whatIsFormat2="Filformat" readMoreFormat="Läs mer | ODG">}}
ODG-filformatet används av Apache OpenOffices Draw-applikation för att lagra ritelement som en vektorbild. Den följer de XML-baserade filformatspecifikationerna som beskrivs av Advancement of Structural Information Standards (OASIS). ODG representerar ritningar som vektorbilder med hjälp av punkter, linjer och kurvor. Förutom OpenOffice ger LibreOffice och andra applikationer även stöd för att arbeta med ODG-filformat. Andra format som stöds av OpenOffice, till exempel, inkluderar ODT, ODF, ODP och ODS.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Vad är" whatIsFormat2="Filformat" readMoreFormat="Läs mer | PDF">}}
Portable Document Format (PDF) är en typ av dokument som skapades av Adobe redan på 1990-talet. Syftet med detta filformat var att införa en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. PDF-filformatet har full förmåga att innehålla information som text, bilder, hyperlänkar, formulärfält, rich media, digitala signaturer, bilagor, metadata, geospatiala funktioner och 3D-objekt i det som kan bli en del av källdokumentet.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Med hjälp av Python kan man enkelt konvertera olika format inklusive." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-bmp/" name="BMP" description="Bitmap bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-gif/" name="GIF" description="Grafiskt utbytesformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-dicom/" name="DICOM" description="Digital bildbehandling och kommunikation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-emf/" name="EMF" description="Förbättrat metafilformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-jpg/" name="JPG" description="Förenade Fotografers Expert Grupp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-jpeg/" name="JPEG" description="Förenade Fotografers Expert Grupp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-j2k/" name="J2K" description="Wavelet komprimerad bild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-png/" name="PNG" description="Bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-apng/" name="APNG" description="Animerad bärbar nätverksgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-psd/" name="PSD" description="Photoshop-dokument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-dxf/" name="DXF" description="Drawing Interchange Format, eller Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-svg/" name="SVG" description="Skalbar vektorgrafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-tiff/" name="TIFF" description="Taggad bildformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-webp/" name="WEBP" description="Raster webbbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-wmf/" name="WMF" description="Microsoft Windows metafil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-pdf/" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-html/" name="HTML" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-emz/" name="EMZ" description="Windows komprimerad förbättrad metafil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-wmz/" name="WMZ" description="Komprimerat Windows Media Player-skal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-tga/" name="TGA" description="Targa grafik" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-svgz/" name="SVGZ" description="Komprimerad version av Scalable Vector Graphics-fil (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-canvas/" name="CANVAS" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/sv/python-net/conversion/odg-to-ico/" name="ICO" description="Windows-ikonen" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
