﻿---
title: Konwertuj WMZ na JP2 przez Java 
weight: 3920
url: /pl/java/conversion/wmz-to-jp2/ 
lang: pl
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Przykładowy kod konwersji WMZ na JP2 Java. Użyj przykładowego kodu API dla plików wsadowych WMZ do konwersji JP2 w dowolnej aplikacji internetowej lub opartej na Javie na komputery stacjonarne.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konwertuj WMZ na JP2 przez Java" h2="Przekształć WMZ w JP2 za pomocą natywnych interfejsów API Java bez konieczności używania edytora obrazów lub bibliotek innych firm." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JP2" pfName="Aspose.Imaging" subTitlepfName="dla Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="dla Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/pl/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/pl/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się" overviewText="Przegląd" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować WMZ na JP2 za pomocą Java" %}}

Konwersja formatów plików może wydawać się rutynowym zadaniem grafików. Błędem byłoby jednak niedocenianie jego znaczenia. Ocena Twojej pracy może zależeć od tego, jak szybko i skutecznie poradzisz sobie z tym zadaniem. Zazwyczaj oryginalne obrazy wymagają konwersji do formatów lepiej dostosowanych do druku lub publikacji w Internecie. Jeśli oryginalny obraz pochodzi z edytora graficznego, może być w formacie wektorowym. W tym scenariuszu należy go zrastrować i przekonwertować na format rastrowy na potrzeby publikacji. Masz możliwość zapisania obrazu w formacie nieskompresowanym w celu uzyskania optymalnej jakości lub przekonwertowania go na format skompresowany bezstratnie w celu zmniejszenia rozmiaru pliku. W niektórych kontekstach, np. przy publikowaniu w Internecie, można wybrać formaty skompresowane stratnie. Specjalnie zaprojektowane algorytmy kompresji danych obrazu pozwalają na znaczne zmniejszenie rozmiaru pliku przy zachowaniu akceptowalnej jakości obrazu. Ułatwia to szybkie pobieranie plików obrazów z Internetu. Aby przekonwertować WMZ na JP2, użyjemy [Aspose.Imaging dla Javy](https://products.aspose.com/imaging/java) API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API do obróbki i konwersji obrazów dla platformy Java. Możesz pobrać jego najnowszą wersję bezpośrednio z [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) i zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pom.xml.

{{% blocks/products/pf/agp/code-block title="Repozytorium" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować WMZ na JP2 za pomocą Java" %}}

{{% blocks/products/pf/agp/text %}}

Programiści mogą łatwo ładować i konwertować pliki WMZ na JP2 w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik WMZ za pomocą metody Image.load
+ Utwórz i ustaw instancję wymaganej podklasy ImageOptionsBase (np. BmpOptions, PngOptions itp.)
+ Wywołaj metodę Image.save
+ Przekaż ścieżkę pliku z rozszerzeniem JP2 i obiektem klasy ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Przed uruchomieniem przykładowego kodu konwersji upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

+ System operacyjny: Windows lub Linux.
+ Środowisko programistyczne: obsługuje .NET Core 7 i nowsze wersje, takie jak Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Darmowa aplikacja do konwersji WMZ na JP2"
        appName="Conversion"
        extension="WMZ-to-JP2"
        label1="Wybierz lub przeciągnij i upuść obraz WMZ"
        label2="Wybierz format i kliknij przycisk Konwertuj"
        label3="Kliknij przycisk Pobierz, aby pobrać obraz JP2"
        checkFreeAppLabel="Sprawdź nasze [prezentacje na żywo, aby przekonwertować WMZ na JP2]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/pl/conversion/WMZ-to-JP2)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konwertuj WMZ na JP2 - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WMZ" readMoreLink="https://docs.fileformat.com/image/wmz/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej | WMZ">}}
WMZ to rozszerzenie pliku dla formatu pliku skóry w/dla/używanego przez Windows Media Player. Plik WMZ to w zasadzie spakowany plik WMF w formacie XML.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej | JP2">}}
JPEG 2000 (JP2) to system kodowania obrazu i najnowocześniejszy standard kompresji obrazu. Zaprojektowany przy użyciu technologii wavelet JPEG 2000 może kodować bezstratne treści w dowolnej jakości na raz. Co więcej, bez znaczącej utraty wydajności kodowania, JPEG 2000 ma możliwość dostępu i efektywnego dekodowania tej samej treści w różnych innych rozdzielczościach i jakościach. Strumienie kodu w JPEG 2000 są znacznie skalowalne, posiadając obszary zainteresowania, które zapewniają możliwość przestrzennego dostępu losowego. Posiada do 16384 różnych komponentów o wymiarach w terapikselach i precyzji, która może sięgać nawet 38 bitów na próbkę.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Za pomocą Java można łatwo konwertować różne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-bmp/" name="BMP" description="Obraz bitmapowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-gif/" name="GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-dicom/" name="DICOM" description="Obrazowanie cyfrowe i komunikacja" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-emf/" name="EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-jpg/" name="JPG" description="Wspólna Grupa Ekspertów Fotograficznych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-jpeg/" name="JPEG" description="Wspólna Grupa Ekspertów Fotograficznych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-j2k/" name="J2K" description="Skompresowany obraz falkowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-png/" name="PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-apng/" name="APNG" description="Animowana przenośna grafika sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-psd/" name="PSD" description="Dokument Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-dxf/" name="DXF" description="Format wymiany rysunków lub format wymiany rysunków," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-svg/" name="SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-tiff/" name="TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-webp/" name="WEBP" description="Obraz rastrowy w sieci Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-wmf/" name="WMF" description="Metaplik Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-pdf/" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-html/" name="HTML" description="Płótno HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-emz/" name="EMZ" description="Rozszerzony metaplik skompresowany w systemie Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-svgz/" name="SVGZ" description="Skompresowana wersja pliku Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-canvas/" name="CANVAS" description="Płótno HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/java/conversion/wmz-to-ico/" name="ICO" description="Ikona Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
