﻿---
title: Konvertuoti AVIF į JP2 naudojant Java 
weight: 3920
url: /lt/java/conversion/avif-to-jp2/ 
lang: lt
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: „Java“ konvertavimo AVIF į JP2 pavyzdys. Naudokite API pavyzdinį kodą paketiniams AVIF failams konvertuoti į JP2 bet kurioje žiniatinklio ar darbalaukio Java pagrįstoje programoje.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konvertuoti AVIF į JP2 naudojant Java" h2="Paverskite AVIF į JP2 naudodami savąsias Java API, nereikalaujant jokios vaizdų rengyklės ar trečiųjų šalių bibliotekų." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JP2" pfName="Aspose.Imaging" subTitlepfName="skirta Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="skirta Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/lt/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/lt/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API pagrindinis puslapis" codeSamplesText="Kodo pavyzdžiai" liveDemosText="Tiesioginės demonstracinės versijos" downloadText="parsisiųsti" learnText="Mokytis" overviewText="Apžvalga" >}}

{{% blocks/products/pf/agp/content h2="Kaip konvertuoti AVIF į JP2 naudojant Java" %}}

Failų formatų konvertavimas gali atrodyti kaip įprasta užduotis, su kuria susiduria grafikos dizaineriai. Tačiau neįvertinti jo reikšmės būtų klaida. Jūsų darbo įvertinimas gali priklausyti nuo to, kaip greitai ir efektyviai sprendžiate šią užduotį. Paprastai originalius vaizdus reikia konvertuoti į formatus, geriau tinkančius spausdinti ar skelbti internete. Jei originalus vaizdas kilęs iš grafinės redagavimo priemonės, jis gali būti vektorinio formato. Pagal šį scenarijų jis turi būti rastrizuotas ir konvertuotas į rastrinį formatą publikavimo tikslais. Galite pasirinkti išsaugoti vaizdą nesuspaustu formatu, kad pasiektumėte optimalią kokybę, arba konvertuoti jį į be nuostolių suglaudintą formatą, kad sumažintumėte failo dydį. Tam tikrais atvejais, pvz., leidyboje žiniatinklyje, galite pasirinkti suglaudintus formatus su nuostolingais. Specialiai sukurti vaizdo duomenų glaudinimo algoritmai leidžia žymiai sumažinti failo dydį išsaugant priimtiną vaizdo kokybę. Tai palengvina greitą vaizdo failų atsisiuntimą iš interneto. Norėdami konvertuoti AVIF į JP2, naudosime [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API, kuri yra daug funkcijų, galinga ir lengvai naudojama vaizdo manipuliavimo ir konvertavimo API, skirta Java platformai. Naujausią jos versiją galite atsisiųsti tiesiai iš [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ir įdiekite jį savo Maven pagrįstame projekte, pridėdami toliau nurodytas konfigūracijas prie pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Priklausomybė" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Veiksmai konvertuoti AVIF į JP2 naudojant Java" %}}

{{% blocks/products/pf/agp/text %}}

Kūrėjai gali lengvai įkelti ir konvertuoti AVIF failus į JP2 naudodami tik kelias kodo eilutes.

{{% /blocks/products/pf/agp/text %}}

+ Įkelkite AVIF failą naudodami Image.load metodą
+ Sukurkite ir nustatykite reikiamo „ImageOptionsBase“ poklasio egzempliorių (pvz., „BmpOptions“, „PngOptions“ ir kt.)
+ Iškvieskite Image.save metodą
+ Perduokite failo kelią su plėtiniu JP2 ir „ImageOptionsBase“ klasės objektu

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistemos reikalavimai" %}}

{{% blocks/products/pf/agp/text %}}

Prieš paleisdami konversijos pavyzdžio kodą, įsitikinkite, kad turite šias būtinas sąlygas.

{{% /blocks/products/pf/agp/text %}}

+ Operacinė sistema: Windows arba Linux.
+ Kūrimo aplinka: palaiko .NET Core 7 ir naujesnę versiją, pvz., Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Nemokama programa konvertuoti AVIF į JP2"
        appName="Conversion"
        extension="AVIF-to-JP2"
        label1="Pasirinkite arba nuvilkite AVIF vaizdą"
        label2="Pasirinkite formatą ir spustelėkite mygtuką Konvertuoti"
        label3="Spustelėkite mygtuką Atsisiųsti, kad atsisiųstumėte JP2 vaizdą"
        checkFreeAppLabel="Peržiūrėkite mūsų [tiesiogines demonstracines versijas, kaip konvertuoti AVIF į JP2]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/lt/conversion/AVIF-to-JP2)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konvertuoti AVIF į JP2 – Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | AVIF">}}
AVIF ir atvērta bezatlīdzības attēla faila formāta specifikācija ar AV1 saspiestu attēlu vai attēlu secību glabāšanai HEIF konteinera formātā.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Kas yra" whatIsFormat2="Failo formatas" readMoreFormat="Skaityti daugiau | JP2">}}
JPEG 2000 (JP2) yra vaizdo kodavimo sistema ir pažangiausias vaizdo glaudinimo standartas. Sukurtas, naudojant banglečių technologiją, JPEG 2000 gali iš karto užkoduoti bet kokios kokybės turinį be nuostolių. Be to, be jokios didelės nuobaudos dėl kodavimo efektyvumo, JPEG 2000 turi galimybę pasiekti ir efektyviai iššifruoti tą patį turinį į daugybę kitų skiriamųjų gebų ir savybių. JPEG 2000 kodo srautai yra labai keičiami, nes yra dominančių regionų, kurie suteikia galimybę atsitiktinei erdvinei prieigai. Turi iki 16384 įvairių komponentų, kurių matmenys yra terapikseliais, o tikslumas gali siekti 38 bitus/pavyzdį.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Kitos palaikomos konversijos" subTitle="Naudodami Java galite lengvai konvertuoti įvairius formatus, įskaitant." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-gif/" name="GIF" description="Grafinis mainų formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-dicom/" name="DICOM" description="Skaitmeninis vaizdas ir ryšiai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-emf/" name="EMF" description="Patobulintas metafailo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-jpg/" name="JPG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-jpeg/" name="JPEG" description="Jungtinė fotografijos ekspertų grupė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-j2k/" name="J2K" description="„Wavelet“ suspaustas vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-png/" name="PNG" description="Nešiojamoji tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-apng/" name="APNG" description="Animuota nešiojama tinklo grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-psd/" name="PSD" description="Photoshop dokumentas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-dxf/" name="DXF" description="Brėžinio mainų formatas arba brėžinių mainų formatas," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-svg/" name="SVG" description="Keičiama vektorinė grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-tiff/" name="TIFF" description="Pažymėtas vaizdo formatas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-webp/" name="WEBP" description="Rastrinis žiniatinklio vaizdas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-wmf/" name="WMF" description="Microsoft Windows metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-pdf/" name="PDF" description="Nešiojamo dokumento formatas (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-html/" name="HTML" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-emz/" name="EMZ" description="„Windows“ suspaustas patobulintas metafailas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-wmz/" name="WMZ" description="Suspausta Windows Media Player oda" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-svgz/" name="SVGZ" description="Suglaudinta Scalable Vector Graphics (.SVG) failo versija." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-canvas/" name="CANVAS" description="HTML5 drobė" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-ico/" name="ICO" description="Windows piktograma" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/lt/java/conversion/avif-to-bmp/" name="BMP" description="Bitmap paveikslėlis" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}