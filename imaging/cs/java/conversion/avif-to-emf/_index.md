﻿---
title: Převést AVIF na EMF přes Java 
weight: 3920
url: /cs/java/conversion/avif-to-emf/ 
lang: cs
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Ukázkový kód pro konverzi AVIF na EMF Java. Použijte ukázkový kód API pro dávkový převod souborů AVIF na EMF v jakékoli webové nebo desktopové aplikaci založené na Javě.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Převést AVIF na EMF přes Java" h2="Transformujte AVIF na EMF pomocí nativních Java API, aniž byste potřebovali editor obrázků nebo knihovny třetích stran." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="Aspose.Imaging" subTitlepfName="pro Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="pro Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/cs/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/cs/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Domovská stránka API" codeSamplesText="Ukázky kódu" liveDemosText="Živá ukázka" downloadText="Stažení" learnText="Učit se" overviewText="Přehled" >}}

{{% blocks/products/pf/agp/content h2="Jak převést AVIF na EMF pomocí Java" %}}

Převod formátů souborů se může zdát jako rutinní úkol, se kterým se grafici setkávají. Přesto by bylo chybou podceňovat jeho význam. Hodnocení vaší práce může záviset na tom, jak rychle a efektivně se s tímto úkolem vypořádáte. Původní obrázky obvykle vyžadují převod do formátů, které jsou vhodnější pro tisk nebo online publikaci. Pokud původní obrázek pochází z grafického editoru, může být ve vektorovém formátu. V tomto scénáři musí být rastrován a převeden na rastrový formát pro účely publikování. Máte na výběr, zda chcete uložit obrázek v nekomprimovaném formátu pro optimální kvalitu, nebo jej převést do bezztrátového komprimovaného formátu pro zmenšení velikosti souboru. V určitých kontextech, jako je publikování na webu, se můžete rozhodnout pro ztrátové komprimované formáty. Speciálně navržené algoritmy pro kompresi obrazových dat umožňují výrazné snížení velikosti souboru při zachování přijatelné kvality obrazu. To usnadňuje rychlé stahování obrazových souborů z internetu. Abychom převedli AVIF na EMF, použijeme [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API, které je funkčně bohaté, výkonné a snadno použitelné rozhraní API pro manipulaci a konverzi obrázků pro platformu Java. Jeho nejnovější verzi si můžete stáhnout přímo z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) a nainstalovat do svého Maven -založený projekt přidáním následujících konfigurací do souboru pom.xml.

{{% blocks/products/pf/agp/code-block title="Úložiště" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Závislost" offSpacer="true" %}}

```xml
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu AVIF na EMF prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

Vývojáři mohou snadno načíst a převést soubory AVIF do formátu EMF pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

+ Načtěte soubor AVIF pomocí metody Image.load
+ Vytvořte a nastavte instanci požadované podtřídy ImageOptionsBase (např. BmpOptions, PngOptions atd.)
+ Zavolejte metodu Image.save
+ Předat cestu k souboru s příponou EMF a objektem třídy ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

Před spuštěním ukázkového kódu konverze se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

+ Operační systém: Windows nebo Linux.
+ Vývojové prostředí: Podporuje .NET Core 7 a vyšší, jako je Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Bezplatná aplikace pro převod AVIF na EMF"
        appName="Conversion"
        extension="AVIF-to-EMF"
        label1="Vyberte nebo přetáhněte obrázek AVIF"
        label2="Vyberte formát a klikněte na tlačítko Převést"
        label3="Kliknutím na tlačítko Stáhnout stáhnete obrázek ve formátu EMF"
        checkFreeAppLabel="Podívejte se na naše [živé ukázky k převodu AVIF na EMF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/AVIF-to-EMF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Převést AVIF na EMF – Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="co je" whatIsFormat2="Formát souboru" readMoreFormat="Přečtěte si více | AVIF">}}
AVIF je otevřená specifikace formátu souboru obrázků bez licenčních poplatků pro ukládání obrázků nebo sekvencí obrázků komprimovaných pomocí AV1 ve formátu kontejneru HEIF.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" whatIsFormat1="co je" whatIsFormat2="Formát souboru" readMoreFormat="Přečtěte si více | EMF">}}
Enhanced metafile format (EMF) ukládá grafické obrázky nezávisle na zařízení. Metasoubory EMF se skládají ze záznamů s proměnnou délkou v chronologickém pořadí, které mohou vykreslit uložený obraz po analýze na libovolném výstupním zařízení. Tyto záznamy s proměnnou délkou mohou být definice uzavřených objektů, příkazy pro kreslení a grafické vlastnosti, které jsou důležité pro přesné vykreslení obrazu. Když zařízení otevře metasoubor EMF pomocí vlastního grafického prostředí, proporce, rozměry, barvy a další grafické vlastnosti původního obrázku zůstanou stejné bez ohledu na platformu otevíracího zařízení.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Pomocí Java lze snadno převádět různé formáty včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-gif/" name="GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-dicom/" name="DICOM" description="Digitální zobrazování a komunikace" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-emf/" name="EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-jpg/" name="JPG" description="Společná skupina fotografických expertů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-jpeg/" name="JPEG" description="Společná skupina fotografických expertů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-j2k/" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-png/" name="PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-apng/" name="APNG" description="Animovaná přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-psd/" name="PSD" description="Dokument Photoshopu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-dxf/" name="DXF" description="Výměnný formát výkresů nebo formát výměny výkresů," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-svg/" name="SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-tiff/" name="TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-webp/" name="WEBP" description="Rastrový webový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-pdf/" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-html/" name="HTML" description="HTML5 plátno" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-emz/" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-wmz/" name="WMZ" description="Komprimovaný vzhled Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-tga/" name="TGA" description="Grafika Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-svgz/" name="SVGZ" description="Komprimovaná verze souboru Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-canvas/" name="CANVAS" description="HTML5 plátno" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-ico/" name="ICO" description="ikona Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/java/conversion/avif-to-bmp/" name="BMP" description="Bitmapový obrázek" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}