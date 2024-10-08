﻿---
title: Konwertuj DJVU na SVG przez C# 
weight: 3920
url: /pl/net/conversion/djvu-to-svg/ 
lang: pl
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Przykładowy kod konwersji DJVU do SVG C#. Użyj przykładowego kodu API dla plików wsadowych DJVU do konwersji SVG w ramach VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Konwertuj DJVU na SVG przez C#" h2="Przekształć DJVU w SVG za pomocą natywnych interfejsów API .NET bez konieczności używania edytora obrazów lub bibliotek innych firm." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName="dla .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="dla .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/pl/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/pl/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="Strona główna API" codeSamplesText="Próbki kodu" liveDemosText="Prezentacje na żywo" downloadText="Ściągnij" learnText="Uczyć się" overviewText="Przegląd" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować DJVU na SVG za pomocą C#" %}}

Konwersja formatów plików może wydawać się rutynowym zadaniem grafików. Błędem byłoby jednak niedocenianie jego znaczenia. Ocena Twojej pracy może zależeć od tego, jak szybko i skutecznie poradzisz sobie z tym zadaniem. Zazwyczaj oryginalne obrazy wymagają konwersji do formatów lepiej dostosowanych do druku lub publikacji w Internecie. Jeśli oryginalny obraz pochodzi z edytora graficznego, może być w formacie wektorowym. W tym scenariuszu należy go zrastrować i przekonwertować na format rastrowy na potrzeby publikacji. Masz możliwość zapisania obrazu w formacie nieskompresowanym w celu uzyskania optymalnej jakości lub przekonwertowania go na format skompresowany bezstratnie w celu zmniejszenia rozmiaru pliku. W niektórych kontekstach, np. przy publikowaniu w Internecie, można wybrać formaty skompresowane stratnie. Specjalnie zaprojektowane algorytmy kompresji danych obrazu pozwalają na znaczne zmniejszenie rozmiaru pliku przy zachowaniu akceptowalnej jakości obrazu. Ułatwia to szybkie pobieranie plików obrazów z Internetu. Aby przekonwertować DJVU na SVG, użyjemy [Aspose.Imaging dla .NET](https://products.aspose.com/imaging/net) API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu interfejsem API do obróbki i konwersji obrazów dla platformy C#. Otwarty [NuGet](https://www.nuget.org/packages/aspose.imaging) menedżer pakietów, szukaj **Aspose.Obrazowanie** i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}



```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować DJVU na SVG za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

Programiści mogą łatwo ładować i konwertować pliki DJVU na SVG w zaledwie kilku linijkach kodu.

{{% /blocks/products/pf/agp/text %}}

+ Załaduj plik DJVU za pomocą metody Image.Load
+ Utwórz i ustaw instancję wymaganej podklasy ImageOptionsBase (np. BmpOptions, PngOptions itp.)
+ Wywołaj metodę Image.Save
+ Przekaż ścieżkę pliku z rozszerzeniem SVG i obiektem klasy ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

Przed uruchomieniem przykładowego kodu konwersji upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

+ System operacyjny: Windows lub Linux.
+ Środowisko programistyczne: obsługuje .NET Core 7 i nowsze wersje, takie jak Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Darmowa aplikacja do konwersji DJVU na SVG"
        appName="Conversion"
        extension="DJVU-to-SVG"
        label1="Wybierz lub przeciągnij i upuść obraz DJVU"
        label2="Wybierz format i kliknij przycisk Konwertuj"
        label3="Kliknij przycisk Pobierz, aby pobrać obraz SVG"
        checkFreeAppLabel="Sprawdź nasze [prezentacje na żywo, aby przekonwertować DJVU na SVG]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/pl/conversion/DJVU-to-SVG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Konwertuj DJVU na SVG - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "7cd7d94813fb73fe141054272437f6ae" "convert-djvu-to-svg.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej | DJVU">}}
DjVu, wymawiane jako DJVU, to format plików graficznych przeznaczony dla zeskanowanych dokumentów i książek, zwłaszcza zawierających kombinację tekstu, rysunków, obrazów i fotografii. Został opracowany przez AT&T Labs. Wykorzystuje wiele technik, takich jak separacja warstw obrazu tekstu i obrazów tła, ładowanie progresywne, kodowanie arytmetyczne i kompresja stratna dla obrazów dwukolorowych. Ponieważ plik DJVU może zawierać skompresowane, ale wysokiej jakości kolorowe obrazy, zdjęcia, tekst i rysunki, i może być zapisany na mniejszej przestrzeni, dlatego jest używany w Internecie jako e-booki, podręczniki, gazety, starożytne dokumenty itp.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="Co jest" whatIsFormat2="Format pliku" readMoreFormat="Czytaj więcej | SVG">}}
Pliki SVG to skalowalne pliki grafiki wektorowej, które wykorzystują format tekstowy oparty na XML do opisywania wyglądu obrazu. Słowo Skalowalny odnosi się do faktu, że SVG można skalować do różnych rozmiarów bez utraty jakości. Opis tekstowy takich plików czyni je niezależnymi od rozdzielczości. Jest to jeden z najczęściej używanych formatów do budowy stron internetowych i grafiki drukowanej w celu uzyskania skalowalności. Format ten może być jednak używany tylko do grafiki dwuwymiarowej. Pliki SVG można przeglądać/otwierać w prawie wszystkich nowoczesnych przeglądarkach, w tym Chrome, Internet Explorer, Firefox i Safari.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Za pomocą C# można łatwo konwertować różne formaty, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-bmp/" name="BMP" description="Obraz bitmapowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-gif/" name="GIF" description="Graficzny format wymiany" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-dicom/" name="DICOM" description="Obrazowanie cyfrowe i komunikacja" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-emf/" name="EMF" description="Ulepszony format metapliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-jpg/" name="JPG" description="Wspólna Grupa Ekspertów Fotograficznych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-jpeg/" name="JPEG" description="Wspólna Grupa Ekspertów Fotograficznych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-j2k/" name="J2K" description="Skompresowany obraz falkowy" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-png/" name="PNG" description="Przenośna Grafika Sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-apng/" name="APNG" description="Animowana przenośna grafika sieciowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-psd/" name="PSD" description="Dokument Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-dxf/" name="DXF" description="Format wymiany rysunków lub format wymiany rysunków," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-svg/" name="SVG" description="Skalowalna Grafika wektorowa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-tiff/" name="TIFF" description="Oznaczony format obrazu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-webp/" name="WEBP" description="Obraz rastrowy w sieci Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-wmf/" name="WMF" description="Metaplik Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-pdf/" name="PDF" description="Przenośny format dokumentu (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-html/" name="HTML" description="Płótno HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-emz/" name="EMZ" description="Rozszerzony metaplik skompresowany w systemie Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-wmz/" name="WMZ" description="Skompresowana skórka Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-tga/" name="TGA" description="Targa grafika" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-svgz/" name="SVGZ" description="Skompresowana wersja pliku Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-canvas/" name="CANVAS" description="Płótno HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pl/net/conversion/djvu-to-ico/" name="ICO" description="Ikona Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
