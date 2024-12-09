﻿---
title: Преобразование AVIF в SVG с помощью Java 
weight: 3920
url: /ru/java/conversion/avif-to-svg/ 
lang: ru
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Пример кода для преобразования AVIF в SVG Java. Используйте пример кода API для пакетного преобразования файлов AVIF в SVG в любом веб-приложении или приложении для настольных ПК на основе Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Преобразование AVIF в SVG с помощью Java" h2="Преобразуйте AVIF в SVG с помощью собственных API-интерфейсов Java, не прибегая к редактору изображений или сторонним библиотекам." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ru/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ru/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Главная страница API" codeSamplesText="Примеры кода" liveDemosText="Online примеры" downloadText="Скачать" learnText="Документация" overviewText="Обзор" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать AVIF в SVG с помощью Java" %}}

Казалось бы, преобразование форматов файлов — обыденная задача, с которой сталкивается каждый графический дизайнер. Однако не стоит пренебрегать важностью ее решения. От того, насколько быстро и качественно вы ее решите, может зависеть оценка вашей работы. Для полученных исходных изображений, как правило, требуется их конвертация в другие форматы — более подходящие для целей печати или публикации в Интернете. Исходное изображение, подготовленное в графическом редакторе, может быть также в векторном формате. В этом случае для публикации его нужно растеризовать и конвертировать в растровый формат. Сохранить изображение можно в формате без сжатия для наилучшего качества или преобразовать его в формат со сжатием без потерь, чтобы уменьшить размер файла. Для некоторых целей, например, публикации на интернет-сайте, доступна конвертация в форматы со сжатием с потерями. Специально разработанные алгоритмы сжатия данных для изображений позволяют (при сохранении приемлемого качества изображения) значительно уменьшать размер файла, что обеспечивает быструю загрузку файлов изображений из Интернета. Чтобы преобразовать AVIF в SVG, мы будем использовать [Aspose.Imaging для Java](https://products.aspose.com/imaging/java) API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования изображений для платформы Java. Вы можете скачать его последнюю версию прямо с [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Зависимость" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию AVIF в SVG через Java" %}}

{{% blocks/products/pf/agp/text %}}

Разработчики могут легко загружать и преобразовывать файлы AVIF в SVG, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+ Загрузить файл AVIF методом Image.load
+ Создайте и установите экземпляр требуемого подкласса ImageOptionsBase (например, BmpOptions, PngOptions и т. д.)
+ Вызвать метод Image.save
+ Передать путь к файлу с расширением SVG и объектом класса ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Прежде чем запускать код примера преобразования, убедитесь, что выполнены следующие предварительные условия:

{{% /blocks/products/pf/agp/text %}}

+ Операционная система Windows или Linux.
+ Среда разработки поддерживающая .NET Core 7 и выше, например Microsoft Visual Studio.
  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Бесплатное приложение для конвертации изображений AVIF в SVG"
        appName="Conversion"
        extension="AVIF-to-SVG"
        label1="Выберите или перетащите мышью изображение формата AVIF"
        label2="Выберите формат и нажмите кнопку `Конвертировать`"
        label3="Нажмите кнопку `Скачать` для скачивания SVG изображения"
        checkFreeAppLabel="Посмотрите наши [примеры для конвертации AVIF в SVG]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/ru/conversion/AVIF-to-SVG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Преобразование AVIF в SVG - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="Чем является" whatIsFormat2="формат" readMoreFormat="Читать далее | AVIF">}}
AVIF — это открытая спецификация формата файлов изображений, не требующая лицензионных отчислений, для хранения изображений или последовательностей изображений, сжатых с помощью AV1, в формате контейнера HEIF.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="Чем является" whatIsFormat2="формат" readMoreFormat="Читать далее | SVG">}}
Файлы SVG представляют собой файлы масштабируемой векторной графики, которые используют текстовый формат на основе XML для описания внешнего вида изображения. Слово «масштабируемый» относится к тому факту, что SVG можно масштабировать до разных размеров без потери качества. Текстовое описание таких файлов делает их независимыми от разрешения. Это один из наиболее часто используемых форматов для создания веб-сайтов и печатной графики для достижения масштабируемости. Однако этот формат можно использовать только для двумерной графики. Файлы SVG можно просматривать/открывать практически во всех современных браузерах, включая Chrome, Internet Explorer, Firefox и Safari.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Используя Java, можно легко конвертировать различные форматы, в том числе:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-gif/" name="GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-dicom/" name="DICOM" description="Цифровая визуализация и связь" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-emf/" name="EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-jpg/" name="JPG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-jpeg/" name="JPEG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-j2k/" name="J2K" description="Сжатое изображение вейвлета" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-png/" name="PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-apng/" name="APNG" description="Анимированная портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-psd/" name="PSD" description="Документ Фотошоп" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-dxf/" name="DXF" description="Формат обмена чертежами или Формат обмена чертежами," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-svg/" name="SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-tiff/" name="TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-webp/" name="WEBP" description="Растровое веб-изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-wmf/" name="WMF" description="Метафайл Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-pdf/" name="PDF" description="Переносимый формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-html/" name="HTML" description="Холст HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-emz/" name="EMZ" description="Сжатый расширенный метафайл Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-wmz/" name="WMZ" description="Сжатая оболочка проигрывателя Windows Media" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-tga/" name="TGA" description="Тарга Графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-svgz/" name="SVGZ" description="Сжатая версия файла масштабируемой векторной графики (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-canvas/" name="CANVAS" description="Холст HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-ico/" name="ICO" description="Значок Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/conversion/avif-to-bmp/" name="BMP" description="Растровое изображение" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}