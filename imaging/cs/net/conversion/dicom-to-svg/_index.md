﻿---
title: Převést DICOM na SVG přes C# 
weight: 3920
url: /cs/net/conversion/dicom-to-svg/ 
lang: cs
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Ukázkový kód pro konverzi DICOM na SVG C#. Použijte ukázkový kód API pro dávkový převod souborů DICOM na SVG v rámci VB.NET, Asp.NET nebo jakékoli aplikace založené na .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Převést DICOM na SVG přes C#" h2="Transformujte DICOM na SVG pomocí nativních .NET API, aniž byste potřebovali editor obrázků nebo knihovny třetích stran." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName="pro .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="pro .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/cs/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/cs/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="Domovská stránka API" codeSamplesText="Ukázky kódu" liveDemosText="Živá ukázka" downloadText="Stažení" learnText="Učit se" overviewText="Přehled" >}}

{{% blocks/products/pf/agp/content h2="Jak převést DICOM na SVG pomocí C#" %}}

Převod formátů souborů se může zdát jako rutinní úkol, se kterým se grafici setkávají. Přesto by bylo chybou podceňovat jeho význam. Hodnocení vaší práce může záviset na tom, jak rychle a efektivně se s tímto úkolem vypořádáte. Původní obrázky obvykle vyžadují převod do formátů, které jsou vhodnější pro tisk nebo online publikaci. Pokud původní obrázek pochází z grafického editoru, může být ve vektorovém formátu. V tomto scénáři musí být rastrován a převeden na rastrový formát pro účely publikování. Máte na výběr, zda chcete uložit obrázek v nekomprimovaném formátu pro optimální kvalitu, nebo jej převést do bezztrátového komprimovaného formátu pro zmenšení velikosti souboru. V určitých kontextech, jako je publikování na webu, se můžete rozhodnout pro ztrátové komprimované formáty. Speciálně navržené algoritmy pro kompresi obrazových dat umožňují výrazné snížení velikosti souboru při zachování přijatelné kvality obrazu. To usnadňuje rychlé stahování obrazových souborů z internetu. Abychom převedli DICOM na SVG, použijeme [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API, které je funkčně bohaté, výkonné a snadno použitelné rozhraní API pro manipulaci a konverzi obrázků pro platformu C#. Otevřete správce balíčků [NuGet](https://www.nuget.org/packages/aspose.imaging), vyhledejte
 **Aspose.Imaging** a nainstalujte. Můžete také použít následující příkaz z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzole Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky k převodu DICOM na SVG prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

Vývojáři mohou snadno načíst a převést soubory DICOM do formátu SVG pomocí několika řádků kódu.

{{% /blocks/products/pf/agp/text %}}

+ Načtěte soubor DICOM pomocí metody Image.Load
+ Vytvořte a nastavte instanci požadované podtřídy ImageOptionsBase (např. BmpOptions, PngOptions atd.)
+ Zavolejte metodu Image.Save
+ Předat cestu k souboru s příponou SVG a objektem třídy ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

Před spuštěním ukázkového kódu konverze se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

+ Operační systém: Windows nebo Linux.
+ Vývojové prostředí: Podporuje .NET Core 7 a vyšší, jako je Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Bezplatná aplikace pro převod DICOM na SVG"
        appName="Conversion"
        extension="DICOM-to-SVG"
        label1="Vyberte nebo přetáhněte obrázek DICOM"
        label2="Vyberte formát a klikněte na tlačítko Převést"
        label3="Kliknutím na tlačítko Stáhnout stáhnete obrázek ve formátu SVG"
        checkFreeAppLabel="Podívejte se na naše [živé ukázky k převodu DICOM na SVG]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/DICOM-to-SVG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Převést DICOM na SVG – .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "d2556ab69aeedafc6cf8c7c569c46075" "convert-dicom-to-svg.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="co je" whatIsFormat2="Formát souboru" readMoreFormat="Přečtěte si více | DICOM">}}
DICOM je zkratka pro Digital Imaging and Communications in Medicine a týká se oblasti lékařské informatiky. DICOM je kombinací definice formátu souboru a síťového komunikačního protokolu. DICOM používá příponu .DCM. .DCM existuje ve dvou různých formátech, tj. formátu 1.xa formátu 2.x. DCM Format 1.x je dále k dispozici ve dvou verzích normální a rozšířené. DICOM se používá pro integraci lékařských zobrazovacích zařízení, jako jsou tiskárny, servery, skenery atd. od různých dodavatelů a také obsahuje identifikační údaje každého pacienta pro jedinečnost. Soubory DICOM lze sdílet mezi dvěma stranami, pokud jsou schopny přijímat obrazová data ve formátu DICOM. Komunikační částí DICOM je protokol aplikační vrstvy a ke komunikaci mezi entitami využívá TCP/IP. Pro webové služby DICOM se používají protokoly HTTP a HTTPS. Verze podporované webovými službami jsou 1.0, 1.1, 2 nebo novější.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="co je" whatIsFormat2="Formát souboru" readMoreFormat="Přečtěte si více | SVG">}}
Soubory SVG jsou soubory škálovatelné vektorové grafiky, které k popisu vzhledu obrázku používají textový formát založený na XML. Slovo Scalable odkazuje na skutečnost, že SVG lze škálovat na různé velikosti bez ztráty kvality. Textový popis těchto souborů je činí nezávislými na rozlišení. Je to jeden z nejčastěji používaných formátů pro tvorbu webových stránek a tiskové grafiky za účelem dosažení škálovatelnosti. Formát lze použít pouze pro dvourozměrnou grafiku. Soubory SVG lze prohlížet/otvírat téměř ve všech moderních prohlížečích včetně Chrome, Internet Explorer, Firefox a Safari.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="Pomocí C# lze snadno převádět různé formáty včetně." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-bmp/" name="BMP" description="Bitmapový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-gif/" name="GIF" description="Grafický výměnný formát" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-emf/" name="EMF" description="Vylepšený formát metasouborů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-jpg/" name="JPG" description="Společná skupina fotografických expertů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-jpeg/" name="JPEG" description="Společná skupina fotografických expertů" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-j2k/" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-png/" name="PNG" description="Přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-apng/" name="APNG" description="Animovaná přenosná síťová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-psd/" name="PSD" description="Dokument Photoshopu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-dxf/" name="DXF" description="Výměnný formát výkresů nebo formát výměny výkresů," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-svg/" name="SVG" description="Škálovatelná vektorová grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-tiff/" name="TIFF" description="Formát tagovaného obrázku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-webp/" name="WEBP" description="Rastrový webový obrázek" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-pdf/" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-html/" name="HTML" description="HTML5 plátno" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-emz/" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-wmz/" name="WMZ" description="Komprimovaný vzhled Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-tga/" name="TGA" description="Grafika Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-svgz/" name="SVGZ" description="Komprimovaná verze souboru Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-canvas/" name="CANVAS" description="HTML5 plátno" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/cs/net/conversion/dicom-to-ico/" name="ICO" description="ikona Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
