﻿---
title: Konvertuoti BMP į TIFF naudojant C# 
weight: 3920
url: /lt/net/conversion/bmp-to-tiff/ 
lang: lt
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: C# konvertavimo iš BMP į TIFF pavyzdinis kodas. Naudokite API pavyzdinį kodą paketiniams BMP failams konvertuoti į TIFF VB.NET, Asp.NET arba bet kurioje .NET pagrįstoje programoje.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertuoti BMP į TIFF naudojant C#" h2="Paverskite BMP į TIFF naudodami savąsias .NET API, nereikalaujant jokios vaizdų rengyklės ar trečiųjų šalių bibliotekų." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="Aspose.Imaging" subTitlepfName="skirta .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="skirta .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/lt/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/lt/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API pagrindinis puslapis" codeSamplesText="Kodo pavyzdžiai" liveDemosText="Tiesioginės demonstracinės versijos" downloadText="parsisiųsti" learnText="Mokytis" overviewText="Apžvalga" >}}

{{% blocks/products/pf/agp/content h2="Kaip konvertuoti BMP į TIFF naudojant C#" %}}

Failų formatų konvertavimas gali atrodyti kaip įprasta užduotis, su kuria susiduria grafikos dizaineriai. Tačiau neįvertinti jo reikšmės būtų klaida. Jūsų darbo įvertinimas gali priklausyti nuo to, kaip greitai ir efektyviai sprendžiate šią užduotį. Paprastai originalius vaizdus reikia konvertuoti į formatus, geriau tinkančius spausdinti ar skelbti internete. Jei originalus vaizdas kilęs iš grafinės redagavimo priemonės, jis gali būti vektorinio formato. Pagal šį scenarijų jis turi būti rastrizuotas ir konvertuotas į rastrinį formatą publikavimo tikslais. Galite pasirinkti išsaugoti vaizdą nesuspaustu formatu, kad pasiektumėte optimalią kokybę, arba konvertuoti jį į be nuostolių suglaudintą formatą, kad sumažintumėte failo dydį. Tam tikrais atvejais, pvz., leidyboje žiniatinklyje, galite pasirinkti suglaudintus formatus su nuostolingais. Specialiai sukurti vaizdo duomenų glaudinimo algoritmai leidžia žymiai sumažinti failo dydį išsaugant priimtiną vaizdo kokybę. Tai palengvina greitą vaizdo failų atsisiuntimą iš interneto. Norėdami konvertuoti BMP į TIFF, naudosime [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API, kuri yra daug funkcijų, galinga ir lengvai naudojama vaizdo apdorojimo ir konvertavimo API, skirta C# platformai. Atviras [NuGet](https://www.nuget.org/packages/aspose.imaging) paketų tvarkyklė, ieškokite **Aspose.Imaging** ir įdiegti. Taip pat galite naudoti šią komandą iš paketų tvarkyklės konsolės.

{{% blocks/products/pf/agp/code-block title="Paketų tvarkytuvės konsolės komanda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Veiksmai konvertuoti BMP į TIFF naudojant C#" %}}

{{% blocks/products/pf/agp/text %}}

Kūrėjai gali lengvai įkelti ir konvertuoti BMP failus į TIFF naudodami tik kelias kodo eilutes.

{{% /blocks/products/pf/agp/text %}}

+ Įkelkite BMP failą naudodami Image.Load metodą
+ Sukurkite ir nustatykite reikiamo „ImageOptionsBase“ poklasio egzempliorių (pvz., „BmpOptions“, „PngOptions“ ir kt.)
+ Iškvieskite Image.Save metodą
+ Perduokite failo kelią su TIFF plėtiniu ir ImageOptionsBase klasės objektu

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistemos reikalavimai" %}}

{{% blocks/products/pf/agp/text %}}

Prieš paleisdami konversijos pavyzdžio kodą, įsitikinkite, kad turite šias būtinas sąlygas.

{{% /blocks/products/pf/agp/text %}}

+ Operacinė sistema: Windows arba Linux.
+ Kūrimo aplinka: palaiko .NET Core 7 ir naujesnę versiją, pvz., Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Nemokama programa konvertuoti BMP į TIFF"
        appName="Conversion"
        extension="BMP-to-TIFF"
        label1="Pasirinkite arba nuvilkite BMP vaizdą"
        label2="Pasirinkite formatą ir spustelėkite mygtuką Konvertuoti"
        label3="Spustelėkite mygtuką Atsisiųsti, kad atsisiųstumėte TIFF vaizdą"
        checkFreeAppLabel="Peržiūrėkite mūsų [tiesiogines demonstracines versijas, kaip konvertuoti BMP į TIFF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/lt/conversion/BMP-to-TIFF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertuoti BMP į TIFF – .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "6ec855304907234b26961df70f13afb0" "convert-bmp-to-tiff.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | BMP">}}
Failai, kurių plėtinys yra .BMP, yra taškinio vaizdo failai, naudojami taškinio formato skaitmeniniams vaizdams saugoti. Šie vaizdai nepriklauso nuo grafikos adapterio ir taip pat vadinami nepriklausomu bitmap (DIB) failo formatu. Ši nepriklausomybė skirta atidaryti failą keliose platformose, pvz., „Microsoft Windows“ ir „Mac“. BMP failo formatas gali saugoti duomenis kaip dvimačius skaitmeninius vaizdus tiek nespalvotu, tiek spalvotu formatu su įvairiu spalvų gyliu.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | TIFF">}}
TIFF arba TIF, Tagged Image File Format, reiškia rastrinius vaizdus, ​​kurie yra skirti naudoti įvairiuose įrenginiuose, kurie atitinka šį failo formato standartą. Jis gali apibūdinti dviejų lygių, pilkų tonų, paletės spalvų ir pilnų spalvų vaizdo duomenis keliose spalvų erdvėse. Jis palaiko nuostolingo ir be nuostolių glaudinimo schemas, kad būtų galima pasirinkti tarp vietos ir laiko programoms, naudojančioms formatą. Formatas yra išplečiamas ir buvo keletą kartų peržiūrėtas, todėl galima įtraukti neribotą kiekį privačios ar specialios paskirties informacijos. Formatas nepriklauso nuo įrenginio ir nėra ribojamas, pvz., procesoriaus, operacinės sistemos ar failų sistemų.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Kitos palaikomos konversijos" subTitle="Naudodami C# galite lengvai konvertuoti įvairius formatus, įskaitant." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-gif/" name="GIF" description="Grafinis mainų formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-dicom/" name="DICOM" description="Skaitmeninis vaizdas ir ryšiai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-emf/" name="EMF" description="Patobulintas metafailo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-jpg/" name="JPG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-jpeg/" name="JPEG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-j2k/" name="J2K" description="„Wavelet“ suspaustas vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-png/" name="PNG" description="Nešiojamoji tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-apng/" name="APNG" description="Animuota nešiojama tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-psd/" name="PSD" description="Photoshop dokumentas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-dxf/" name="DXF" description="Brėžinio mainų formatas arba brėžinių mainų formatas," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-svg/" name="SVG" description="Keičiama vektorinė grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-tiff/" name="TIFF" description="Pažymėtas vaizdo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-webp/" name="WEBP" description="Rastrinis žiniatinklio vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-wmf/" name="WMF" description="Microsoft Windows metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-pdf/" name="PDF" description="Nešiojamo dokumento formatas (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-html/" name="HTML" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-emz/" name="EMZ" description="„Windows“ suspaustas patobulintas metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-wmz/" name="WMZ" description="Suspausta Windows Media Player oda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-svgz/" name="SVGZ" description="Suglaudinta Scalable Vector Graphics (.SVG) failo versija." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-canvas/" name="CANVAS" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/bmp-to-ico/" name="ICO" description="Windows piktograma" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
