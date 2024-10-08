﻿---
title: Konvertuoti AVIF į CANVAS naudojant C# 
weight: 3920
url: /lt/net/conversion/avif-to-canvas/ 
lang: lt
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: C# konvertavimo iš AVIF į CANVAS pavyzdinis kodas. Naudokite API pavyzdinį kodą paketiniams AVIF failams konvertuoti į CANVAS VB.NET, Asp.NET arba bet kurioje .NET pagrįstoje programoje.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertuoti AVIF į CANVAS naudojant C#" h2="Paverskite AVIF į CANVAS naudodami savąsias .NET API, nereikalaujant jokios vaizdų rengyklės ar trečiųjų šalių bibliotekų." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="CANVAS" pfName="Aspose.Imaging" subTitlepfName="skirta .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="skirta .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/lt/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/lt/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API pagrindinis puslapis" codeSamplesText="Kodo pavyzdžiai" liveDemosText="Tiesioginės demonstracinės versijos" downloadText="parsisiųsti" learnText="Mokytis" overviewText="Apžvalga" >}}

{{% blocks/products/pf/agp/content h2="Kaip konvertuoti AVIF į CANVAS naudojant C#" %}}

Failų formatų konvertavimas gali atrodyti kaip įprasta užduotis, su kuria susiduria grafikos dizaineriai. Tačiau neįvertinti jo reikšmės būtų klaida. Jūsų darbo įvertinimas gali priklausyti nuo to, kaip greitai ir efektyviai sprendžiate šią užduotį. Paprastai originalius vaizdus reikia konvertuoti į formatus, geriau tinkančius spausdinti ar skelbti internete. Jei originalus vaizdas kilęs iš grafinės redagavimo priemonės, jis gali būti vektorinio formato. Pagal šį scenarijų jis turi būti rastrizuotas ir konvertuotas į rastrinį formatą publikavimo tikslais. Galite pasirinkti išsaugoti vaizdą nesuspaustu formatu, kad pasiektumėte optimalią kokybę, arba konvertuoti jį į be nuostolių suglaudintą formatą, kad sumažintumėte failo dydį. Tam tikrais atvejais, pvz., leidyboje žiniatinklyje, galite pasirinkti suglaudintus formatus su nuostolingais. Specialiai sukurti vaizdo duomenų glaudinimo algoritmai leidžia žymiai sumažinti failo dydį išsaugant priimtiną vaizdo kokybę. Tai palengvina greitą vaizdo failų atsisiuntimą iš interneto. Norėdami konvertuoti AVIF į CANVAS, naudosime [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API, kuri yra daug funkcijų, galinga ir lengvai naudojama vaizdo apdorojimo ir konvertavimo API, skirta C# platformai. Atviras [NuGet](https://www.nuget.org/packages/aspose.imaging) paketų tvarkyklė, ieškokite **Aspose.Imaging** ir įdiegti. Taip pat galite naudoti šią komandą iš paketų tvarkyklės konsolės.

{{% blocks/products/pf/agp/code-block title="Paketų tvarkytuvės konsolės komanda" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Veiksmai konvertuoti AVIF į CANVAS naudojant C#" %}}

{{% blocks/products/pf/agp/text %}}

Kūrėjai gali lengvai įkelti ir konvertuoti AVIF failus į CANVAS naudodami tik kelias kodo eilutes.

{{% /blocks/products/pf/agp/text %}}

+ Įkelkite AVIF failą naudodami Image.Load metodą
+ Sukurkite ir nustatykite reikiamo „ImageOptionsBase“ poklasio egzempliorių (pvz., „BmpOptions“, „PngOptions“ ir kt.)
+ Iškvieskite Image.Save metodą
+ Perduokite failo kelią su CANVAS plėtiniu ir ImageOptionsBase klasės objektu

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistemos reikalavimai" %}}

{{% blocks/products/pf/agp/text %}}

Prieš paleisdami konversijos pavyzdžio kodą, įsitikinkite, kad turite šias būtinas sąlygas.

{{% /blocks/products/pf/agp/text %}}

+ Operacinė sistema: Windows arba Linux.
+ Kūrimo aplinka: palaiko .NET Core 7 ir naujesnę versiją, pvz., Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Nemokama programa konvertuoti AVIF į CANVAS"
        appName="Conversion"
        extension="AVIF-to-CANVAS"
        label1="Pasirinkite arba nuvilkite AVIF vaizdą"
        label2="Pasirinkite formatą ir spustelėkite mygtuką Konvertuoti"
        label3="Spustelėkite mygtuką Atsisiųsti, kad atsisiųstumėte CANVAS vaizdą"
        checkFreeAppLabel="Peržiūrėkite mūsų [tiesiogines demonstracines versijas, kaip konvertuoti AVIF į CANVAS]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/lt/conversion/AVIF-to-CANVAS)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertuoti AVIF į CANVAS – .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "0967b399090c5471f82f46f88b2c0626" "convert-avif-to-canvas.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | AVIF">}}
AVIF ir atvērta bezatlīdzības attēla faila formāta specifikācija ar AV1 saspiestu attēlu vai attēlu secību glabāšanai HEIF konteinera formātā.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="CANVAS" readMoreLink="https://docs.fileformat.com/web/html/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | CANVAS">}}
HTML (Hyper Text Markup Language) yra tinklalapių plėtinys, sukurtas rodyti naršyklėse. Žinomas kaip žiniatinklio kalba, HTML išsivystė atsižvelgiant į naujus informacijos reikalavimus, kurie turi būti rodomi kaip tinklalapių dalis. Naujausias variantas žinomas kaip HTML 5, suteikiantis daug lankstumo dirbant su kalba. HTML puslapiai gaunami iš serverio, kuriame jie yra talpinami, arba gali būti įkeliami ir iš vietinės sistemos. Kiekvienas HTML puslapis yra sudarytas iš HTML elementų, tokių kaip formos, tekstas, vaizdai, animacija, nuorodos ir tt Šie elementai vaizduojami tokiomis žymomis kaip img, a, p ir keletas kitų, kur kiekviena žyma turi pradžią ir pabaigą. Jis taip pat gali įterpti programas, parašytas skriptų kalbomis, pvz., JavaScript ir Style Sheets (CSS), kad būtų galima pateikti bendrą išdėstymą.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Kitos palaikomos konversijos" subTitle="Naudodami C# galite lengvai konvertuoti įvairius formatus, įskaitant." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-gif/" name="GIF" description="Grafinis mainų formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-dicom/" name="DICOM" description="Skaitmeninis vaizdas ir ryšiai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-emf/" name="EMF" description="Patobulintas metafailo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-jpg/" name="JPG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-jpeg/" name="JPEG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-j2k/" name="J2K" description="„Wavelet“ suspaustas vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-png/" name="PNG" description="Nešiojamoji tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-apng/" name="APNG" description="Animuota nešiojama tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-psd/" name="PSD" description="Photoshop dokumentas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-dxf/" name="DXF" description="Brėžinio mainų formatas arba brėžinių mainų formatas," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-svg/" name="SVG" description="Keičiama vektorinė grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-tiff/" name="TIFF" description="Pažymėtas vaizdo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-webp/" name="WEBP" description="Rastrinis žiniatinklio vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-wmf/" name="WMF" description="Microsoft Windows metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-pdf/" name="PDF" description="Nešiojamo dokumento formatas (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-html/" name="HTML" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-emz/" name="EMZ" description="„Windows“ suspaustas patobulintas metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-wmz/" name="WMZ" description="Suspausta Windows Media Player oda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-svgz/" name="SVGZ" description="Suglaudinta Scalable Vector Graphics (.SVG) failo versija." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-canvas/" name="CANVAS" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-ico/" name="ICO" description="Windows piktograma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/net/conversion/avif-to-bmp/" name="BMP" description="Bitmap paveikslėlis" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
