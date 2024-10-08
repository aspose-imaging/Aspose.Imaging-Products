﻿---
title: Konvertuoti EMZ į SVG naudojant C# 
weight: 3920
url: /lt/net/conversion/emz-to-svg/ 
lang: lt
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: C# konvertavimo iš EMZ į SVG pavyzdinis kodas. Naudokite API pavyzdinį kodą paketiniams EMZ failams konvertuoti į SVG VB.NET, Asp.NET arba bet kurioje .NET pagrįstoje programoje.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertuoti EMZ į SVG naudojant C#" h2="Paverskite EMZ į SVG naudodami savąsias .NET API, nereikalaujant jokios vaizdų rengyklės ar trečiųjų šalių bibliotekų." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName="skirta .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="skirta .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/lt/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/lt/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API pagrindinis puslapis" codeSamplesText="Kodo pavyzdžiai" liveDemosText="Tiesioginės demonstracinės versijos" downloadText="parsisiųsti" learnText="Mokytis" overviewText="Apžvalga" >}}

{{% blocks/products/pf/agp/content h2="Kaip konvertuoti EMZ į SVG naudojant C#" %}}

Failų formatų konvertavimas gali atrodyti kaip įprasta užduotis, su kuria susiduria grafikos dizaineriai. Tačiau neįvertinti jo reikšmės būtų klaida. Jūsų darbo įvertinimas gali priklausyti nuo to, kaip greitai ir efektyviai sprendžiate šią užduotį. Paprastai originalius vaizdus reikia konvertuoti į formatus, geriau tinkančius spausdinti ar skelbti internete. Jei originalus vaizdas kilęs iš grafinės redagavimo priemonės, jis gali būti vektorinio formato. Pagal šį scenarijų jis turi būti rastrizuotas ir konvertuotas į rastrinį formatą publikavimo tikslais. Galite pasirinkti išsaugoti vaizdą nesuspaustu formatu, kad pasiektumėte optimalią kokybę, arba konvertuoti jį į be nuostolių suglaudintą formatą, kad sumažintumėte failo dydį. Tam tikrais atvejais, pvz., leidyboje žiniatinklyje, galite pasirinkti suglaudintus formatus su nuostolingais. Specialiai sukurti vaizdo duomenų glaudinimo algoritmai leidžia žymiai sumažinti failo dydį išsaugant priimtiną vaizdo kokybę. Tai palengvina greitą vaizdo failų atsisiuntimą iš interneto. Norėdami konvertuoti EMZ į SVG, naudosime [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API, kuri yra daug funkcijų, galinga ir lengvai naudojama vaizdo apdorojimo ir konvertavimo API, skirta C# platformai. Atviras [NuGet](https://www.nuget.org/packages/aspose.imaging) paketų tvarkyklė, ieškokite **Aspose.Imaging** ir įdiegti. Taip pat galite naudoti šią komandą iš paketų tvarkyklės konsolės.

{{% blocks/products/pf/agp/code-block title="Paketų tvarkytuvės konsolės komanda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Veiksmai konvertuoti EMZ į SVG naudojant C#" %}}

{{% blocks/products/pf/agp/text %}}

Kūrėjai gali lengvai įkelti ir konvertuoti EMZ failus į SVG naudodami tik kelias kodo eilutes.

{{% /blocks/products/pf/agp/text %}}

+ Įkelkite EMZ failą naudodami Image.Load metodą
+ Sukurkite ir nustatykite reikiamo „ImageOptionsBase“ poklasio egzempliorių (pvz., „BmpOptions“, „PngOptions“ ir kt.)
+ Iškvieskite Image.Save metodą
+ Perduokite failo kelią su SVG plėtiniu ir ImageOptionsBase klasės objektu

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistemos reikalavimai" %}}

{{% blocks/products/pf/agp/text %}}

Prieš paleisdami konversijos pavyzdžio kodą, įsitikinkite, kad turite šias būtinas sąlygas.

{{% /blocks/products/pf/agp/text %}}

+ Operacinė sistema: Windows arba Linux.
+ Kūrimo aplinka: palaiko .NET Core 7 ir naujesnę versiją, pvz., Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Nemokama programa konvertuoti EMZ į SVG"
        appName="Conversion"
        extension="EMZ-to-SVG"
        label1="Pasirinkite arba nuvilkite EMZ vaizdą"
        label2="Pasirinkite formatą ir spustelėkite mygtuką Konvertuoti"
        label3="Spustelėkite mygtuką Atsisiųsti, kad atsisiųstumėte SVG vaizdą"
        checkFreeAppLabel="Peržiūrėkite mūsų [tiesiogines demonstracines versijas, kaip konvertuoti EMZ į SVG]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/lt/conversion/EMZ-to-SVG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertuoti EMZ į SVG – .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "339fb6f6f36b878e48c3cf057f895589" "convert-emz-to-svg.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="EMZ" readMoreLink="https://docs.fileformat.com/image/emz/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | EMZ">}}
Failas su EMZ failo plėtiniu yra suspausto vaizdo failas, tiksliau vadinamas „Windows Compressed Enhanced Metafile“ failu
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | SVG">}}
SVG failai yra keičiamo dydžio vektorinės grafikos failai, kurie naudoja XML pagrįstą teksto formatą vaizdo išvaizdai apibūdinti. Žodis Scalable reiškia faktą, kad SVG galima keisti iki skirtingų dydžių neprarandant kokybės. Tekstinis tokių failų aprašymas daro juos nepriklausomus nuo skiriamosios gebos. Tai vienas iš dažniausiai naudojamų interneto svetainių kūrimo ir spausdinimo grafikos formatų, siekiant mastelio. Tačiau formatą galima naudoti tik dvimatei grafikai. SVG failus galima peržiūrėti / atidaryti beveik visose šiuolaikinėse naršyklėse, įskaitant Chrome, Internet Explorer, Firefox ir Safari.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Kitos palaikomos konversijos" subTitle="Naudodami C# galite lengvai konvertuoti įvairius formatus, įskaitant." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-bmp/" name="BMP" description="Bitmap paveikslėlis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-gif/" name="GIF" description="Grafinis mainų formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-dicom/" name="DICOM" description="Skaitmeninis vaizdas ir ryšiai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-emf/" name="EMF" description="Patobulintas metafailo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-jpg/" name="JPG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-jpeg/" name="JPEG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-j2k/" name="J2K" description="„Wavelet“ suspaustas vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-png/" name="PNG" description="Nešiojamoji tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-apng/" name="APNG" description="Animuota nešiojama tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-psd/" name="PSD" description="Photoshop dokumentas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-dxf/" name="DXF" description="Brėžinio mainų formatas arba brėžinių mainų formatas," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-svg/" name="SVG" description="Keičiama vektorinė grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-tiff/" name="TIFF" description="Pažymėtas vaizdo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-webp/" name="WEBP" description="Rastrinis žiniatinklio vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-wmf/" name="WMF" description="Microsoft Windows metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-pdf/" name="PDF" description="Nešiojamo dokumento formatas (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-html/" name="HTML" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-wmz/" name="WMZ" description="Suspausta Windows Media Player oda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-svgz/" name="SVGZ" description="Suglaudinta Scalable Vector Graphics (.SVG) failo versija." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-canvas/" name="CANVAS" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/emz-to-ico/" name="ICO" description="Windows piktograma" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
