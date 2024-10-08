﻿---
title: Konwertuj JP2 na BMP przez C# 
weight: 3920
url: /pl/net/conversion/jp2-to-bmp/ 
lang: pl
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Przykładowy kod konwersji JP2 do BMP C#. Użyj przykładowego kodu API dla plików wsadowych JP2 do konwersji BMP w ramach VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konwertuj JP2 na BMP przez C#" h2="Przekształć JP2 w BMP za pomocą natywnych interfejsów API .NET bez konieczności używania edytora obrazów lub bibliotek innych firm." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="Aspose.Imaging" subTitlepfName="dla .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="dla .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/pl/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/pl/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się" overviewText="Przegląd" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować JP2 na BMP za pomocą C#" %}}

Konwersja formatów plików może wydawać się rutynowym zadaniem grafików. Błędem byłoby jednak niedocenianie jego znaczenia. Ocena Twojej pracy może zależeć od tego, jak szybko i skutecznie poradzisz sobie z tym zadaniem. Zazwyczaj oryginalne obrazy wymagają konwersji do formatów lepiej dostosowanych do druku lub publikacji w Internecie. Jeśli oryginalny obraz pochodzi z edytora graficznego, może być w formacie wektorowym. W tym scenariuszu należy go zrastrować i przekonwertować na format rastrowy na potrzeby publikacji. Masz możliwość zapisania obrazu w formacie nieskompresowanym w celu uzyskania optymalnej jakości lub przekonwertowania go na format skompresowany bezstratnie w celu zmniejszenia rozmiaru pliku. W niektórych kontekstach, np. przy publikowaniu w Internecie, można wybrać formaty skompresowane stratnie. Specjalnie zaprojektowane algorytmy kompresji danych obrazu pozwalają na znaczne zmniejszenie rozmiaru pliku przy zachowaniu akceptowalnej jakości obrazu. Ułatwia to szybkie pobieranie plików obrazów z Internetu. Aby przekonwertować JP2 na BMP, użyjemy [Aspose.Imaging dla .NET](https://products.aspose.com/imaging/net) API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API do obróbki i konwersji obrazów dla platformy C#. Otwarty [NuGet](https://www.nuget.org/packages/aspose.imaging) menedżer pakietów, szukaj **Aspose.Obrazowanie** i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}



```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować JP2 na BMP za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

Programiści mogą łatwo ładować i konwertować pliki JP2 na BMP w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik JP2 za pomocą metody Image.Load
+ Utwórz i ustaw instancję wymaganej podklasy ImageOptionsBase (np. BmpOptions, PngOptions itp.)
+ Wywołaj metodę Image.Save
+ Przekaż ścieżkę pliku z rozszerzeniem BMP i obiektem klasy ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Przed uruchomieniem przykładowego kodu konwersji upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

+ System operacyjny: Windows lub Linux.
+ Środowisko programistyczne: obsługuje .NET Core 7 i nowsze wersje, takie jak Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Darmowa aplikacja do konwersji JP2 na BMP"
        appName="Conversion"
        extension="JP2-to-BMP"
        label1="Wybierz lub przeciągnij i upuść obraz JP2"
        label2="Wybierz format i kliknij przycisk Konwertuj"
        label3="Kliknij przycisk Pobierz, aby pobrać obraz BMP"
        checkFreeAppLabel="Sprawdź nasze [prezentacje na żywo, aby przekonwertować JP2 na BMP]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/pl/conversion/JP2-to-BMP)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konwertuj JP2 na BMP - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "d167f0c1dd15b076686df701892e6b1a" "convert-jp2-to-bmp.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej | JP2">}}
JPEG 2000 (JP2) to system kodowania obrazu i najnowocześniejszy standard kompresji obrazu. Zaprojektowany przy użyciu technologii wavelet JPEG 2000 może kodować bezstratne treści w dowolnej jakości na raz. Co więcej, bez znaczącej utraty wydajności kodowania, JPEG 2000 ma możliwość dostępu i efektywnego dekodowania tej samej treści w różnych innych rozdzielczościach i jakościach. Strumienie kodu w JPEG 2000 są znacznie skalowalne, posiadając obszary zainteresowania, które zapewniają możliwość przestrzennego dostępu losowego. Posiada do 16384 różnych komponentów o wymiarach w terapikselach i precyzji, która może sięgać nawet 38 bitów na próbkę.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej | BMP">}}
Pliki o rozszerzeniu .BMP reprezentują pliki obrazów bitmapowych, które są używane do przechowywania cyfrowych obrazów bitmapowych. Obrazy te są niezależne od karty graficznej i są również nazywane formatem plików mapy bitowej niezależnej od urządzenia (DIB). Ta niezależność służy do otwierania pliku na wielu platformach, takich jak Microsoft Windows i Mac. Format pliku BMP może przechowywać dane jako dwuwymiarowe obrazy cyfrowe zarówno w formacie monochromatycznym, jak i kolorowym z różnymi głębiami kolorów.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Za pomocą C# można łatwo konwertować różne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-bmp/" name="BMP" description="Obraz bitmapowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-gif/" name="GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-dicom/" name="DICOM" description="Obrazowanie cyfrowe i komunikacja" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-emf/" name="EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-jpg/" name="JPG" description="Wspólna Grupa Ekspertów Fotograficznych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-jpeg/" name="JPEG" description="Wspólna Grupa Ekspertów Fotograficznych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-j2k/" name="J2K" description="Skompresowany obraz falkowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-png/" name="PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-apng/" name="APNG" description="Animowana przenośna grafika sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-psd/" name="PSD" description="Dokument Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-dxf/" name="DXF" description="Format wymiany rysunków lub format wymiany rysunków," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-svg/" name="SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-tiff/" name="TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-webp/" name="WEBP" description="Obraz rastrowy w sieci Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-wmf/" name="WMF" description="Metaplik Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-pdf/" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-html/" name="HTML" description="Płótno HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-emz/" name="EMZ" description="Rozszerzony metaplik skompresowany w systemie Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-wmz/" name="WMZ" description="Skompresowana skórka Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-svgz/" name="SVGZ" description="Skompresowana wersja pliku Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-canvas/" name="CANVAS" description="Płótno HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/jp2-to-ico/" name="ICO" description="Ikona Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
