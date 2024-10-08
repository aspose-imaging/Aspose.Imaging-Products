﻿---
title: Удалить фон в документах EMZ с помощью Java 
weight: 3920
url: /ru/java/remove-background/emz/ 
lang: ru
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Попробуйте наши локальные API-интерфейсы для документов, чтобы изменить фон из файлов EMZ в приложении Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Удалить фон из EMZ с помощью Java" h2="Создавайте собственные приложения Java для удаления фона из файлов EMZ с помощью серверных API" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMZ" pfName="Aspose.Imaging" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ru/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Главная страница" codeSamplesText="Примеры кода" liveDemosText="Online примеры" downloadText="Скачать" learnText="Документация">}}

{{% blocks/products/pf/agp/content h2="Как удалить фон в файлах EMZ с помощью Java" %}}

Удаление фона с изображения - операция, требующая определения объектов на переднем плане. Есть несколько путей определения объектов на фотографии в формате EMZ. В самом простом случае можно воспользоваться автоматическим методом, который работает для несложных изображений с равномерным фоном. Если на фотографии находятся несколько фигур или фигуры местами сливаются с фоном, то воспользуйтесь методом предварительной разметки объектов и заранее укажите прямоугольные области и тип объектов, которые необходимо выделить. В сложном случае, для автоматического определения объектов, можно воспользоваться Cloud API. Через Cloud API доступно облачное приложение, которое позволяет распознавать объекты на фотографии и использовать полученный контур для удаления фона. Края, оставшихся после удаления фона фигур, можно сгладить для улучшения качества полученного изображения. Чтобы удалить фон в файлах EMZ, мы будем использовать [Aspose.Imaging для Java](https://products.aspose.com/imaging/java) API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования изображений для платформы Java. Вы можете скачать его последнюю версию прямо с [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Действия по удалению фона из EMZ с помощью Java" %}}

{{% blocks/products/pf/agp/text %}}

Вам нужно [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java), чтобы попробовать следующий рабочий процесс в вашей собственной среде.

{{% /blocks/products/pf/agp/text %}}

+ Загрузить файлы EMZ с помощью метода Image.load
+ Удалить фон;
+ Сохранение изображения на диск в поддерживаемом Aspose.Imaging формате

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging для Java поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки:

{{% /blocks/products/pf/agp/text %}}

- Установлен JDK 1.6 или выше.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Удалить фон в изображениях EMZ - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Об Aspose.Imaging for Java API" %}}


Aspose.Imaging API — это решение для обработки изображений, позволяющее создавать, изменять, рисовать или конвертировать изображения и фотографии в приложениях. Он предлагает: кросс-платформенную обработку изображений, включая, помимо прочего, преобразования между различными форматами изображений (включая единую многостраничную или многокадровую обработку изображений), модификации, такие как рисование, работа с графическими примитивами, преобразования (изменение размера, обрезка, отражение и поворот), бинаризация, оттенки серого, настройка яркости, контрастности, расширенные функции обработки изображений (фильтрация, дизеринг, маскирование, устранение перекоса) и стратегии оптимизации памяти. Это автономная библиотека, которая не зависит от какого-либо программного обеспечения для операций с изображениями. Можно легко добавить в проекты высокопроизводительные функции преобразования изображений с помощью собственных API. Это 100% частные локальные API, а изображения обрабатываются на ваших серверах.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Удалить фон в EMZ с помощью онлайн-приложения" sectionDescription="Удалите фон в документах EMZ, посетив наш [веб-сайт Live Demos](https://products.aspose.app/imaging/remove-background). Online примеры имеют следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файлы EMZ и нажмите кнопку «Удалить фон сейчас»." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Мгновенно получить ссылку для скачивания результирующего файла" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMZ" readMoreLink="https://docs.fileformat.com/image/emz/" whatIsFormat1="Чем является" whatIsFormat2="формат" readMoreFormat="Читать далее" >}}
Файл с расширением EMZ представляет собой сжатый файл изображения, более конкретно называемый файлом сжатого расширенного метафайла Windows.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы удаления фона" subTitle="С помощью Java можно легко удалить фон из разных форматов, в том числе." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/apng/" name="APNG" description="Анимированная портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/bmp/" name="BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/ico/" name="ICO" description="Значок Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/jpg/" name="JPG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/dib/" name="DIB" description="Независимое от устройства растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/dicom/" name="DICOM" description="Цифровая визуализация и связь" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/djvu/" name="DJVU" description="Графический формат" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/dng/" name="DNG" description="Изображение цифровой камеры" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/emf/" name="EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/gif/" name="GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/j2k/" name="J2K" description="Сжатое изображение вейвлета" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/png/" name="PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/tiff/" name="TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/webp/" name="WEBP" description="Растровое веб-изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/wmf/" name="WMF" description="Метафайл Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/wmz/" name="WMZ" description="Сжатая оболочка проигрывателя Windows Media" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/tga/" name="TGA" description="Тарга Графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/svg/" name="SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/eps/" name="EPS" description="Инкапсулированный язык PostScript" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/cdr/" name="CDR" description="Векторный рисунок изображения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/cmx/" name="CMX" description="Обмен изображениями Corel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/otg/" name="OTG" description="Стандарт OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/odg/" name="ODG" description="Формат отрисовки Apache OpenOffice" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
