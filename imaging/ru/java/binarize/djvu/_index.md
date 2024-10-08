﻿---
title: Бинаризация DJVU изображений с помощью Java 
weight: 3920
url: /ru/java/binarize/djvu/ 
lang: ru
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Попробуйте наши локальные API-интерфейсы документов для бинаризации файлов изображений DJVU в .NET Framework, .NET Core, приложении Windows, веб-приложении ASP.NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Бинаризация изображений DJVU с помощью Java" h2="Создавайте собственные приложения Java для бинаризации файлов изображений DJVU с помощью серверных API" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DJVU" pfName="Aspose.Imaging" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ru/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Главная страница" codeSamplesText="Примеры кода" liveDemosText="Online примеры" downloadText="Скачать" learnText="Документация">}}

{{% blocks/products/pf/agp/content h2="Как бинаризировать файлы DJVU с помощью Java" %}}

Изобретение цветной пленки стало прорывом в мире фотографии. Однако классическое фотоискусство ассоциируется именно с черно-белым изображением. Несмотря на широкие технические возможности, благодаря которым фотокамера способна отразить все богатство цвета, многие делают выбор не в пользу многоцветности и трансформируют снимки в черно-белый вариант. В таком случается применяется функция преобразования (бинаризация - binarizarion), при которой все пиксели заменяются на бинарные значения: \"0\" - для белого, \"1\" - для черного цвета. В иных случаях преобразование необходимо не в художественных целях, а из практических соображений: например, для подготовки к печати черно-белых иллюстраций в книгах или газетах. Используя графическую библиотеку Java, можно выбрать порог яркости пикселя. При значении  яркости пикселя ниже порогового он станет черным, при превышении — белым. Также возможно применить адаптивный метод бинаризации, при котором учитываются значения пикселей в окружающей области. В этом случае переходы между границами цвета на полученном черно-белом изображении будут более плавными. Чтобы бинаризировать файлы DJVU, мы будем использовать [Aspose.Imaging для Java](https://products.aspose.com/imaging/java) API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования изображений для платформы Java. Вы можете скачать его последнюю версию прямо с [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Шаги по бинаризации DJVU с помощью Java" %}}

{{% blocks/products/pf/agp/text %}}

Вам нужно [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java), чтобы попробовать следующий рабочий процесс в вашей собственной среде.

{{% /blocks/products/pf/agp/text %}}

+ загрузите файлы DJVU с помощью метода Image.Load;
+ бинаризируйте изображение;
+ сохраните изображение на диск в поддерживаемом Aspose.Imaging формате.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging для Java поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки:

{{% /blocks/products/pf/agp/text %}}

- Установлен JDK 1.6 или выше.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Бинаризация изображений DJVU - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "daac19b481878f17e5e6caadd16bb490" "binarize-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Об Aspose.Imaging for Java API" %}}


Aspose.Imaging API — это решение для обработки изображений, позволяющее создавать, изменять, рисовать или конвертировать изображения и фотографии в приложениях. Он предлагает: кросс-платформенную обработку изображений, включая, помимо прочего, преобразования между различными форматами изображений (включая единую многостраничную или многокадровую обработку изображений), модификации, такие как рисование, работа с графическими примитивами, преобразования (изменение размера, обрезка, отражение и поворот), бинаризация, оттенки серого, настройка яркости, контрастности, расширенные функции обработки изображений (фильтрация, дизеринг, маскирование, устранение перекоса) и стратегии оптимизации памяти. Это автономная библиотека, которая не зависит от какого-либо программного обеспечения для операций с изображениями. Можно легко добавить в проекты высокопроизводительные функции преобразования изображений с помощью собственных API. Это 100% частные локальные API, а изображения обрабатываются на ваших серверах.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Бинаризация DJVU через онлайн-приложение" sectionDescription="Бинаризируйте изображения DJVU, посетив наш [веб-сайт Live Demos](https://products.aspose.app/imaging/image-Binarize) Online примеры имеют следующие преимущества" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Не нужно ничего скачивать или настраивать" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Нет необходимости писать какой-либо код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Просто загрузите файлы DJVU и нажмите кнопку \"Бинаризовать сейчас\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Мгновенно получить ссылку для скачивания результирующего файла" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu/" whatIsFormat1="Чем является" whatIsFormat2="формат" readMoreFormat="Читать далее" >}}
DjVu, произносится как дежа вю, представляет собой формат графических файлов, предназначенный для отсканированных документов и книг, особенно тех, которые содержат комбинацию текста, рисунков, изображений и фотографий. Он был разработан AT&T Labs. Он использует несколько методов, таких как разделение слоя изображения текста и фоновых изображений, прогрессивная загрузка, арифметическое кодирование и сжатие с потерями для битональных изображений. Поскольку файл DJVU может содержать сжатые, но высококачественные цветные изображения, фотографии, текст и рисунки и может занимать меньше места, он используется в Интернете в качестве электронных книг, руководств, газет, древних документов и т. д.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы бинаризации" subTitle="Используя Java, можно легко бинаризировать различные форматы, в том числе:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/apng/" name="APNG" description="Анимированная портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/bmp/" name="BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/ico/" name="ICO" description="Значок Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/jpg/" name="JPG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/jpeg/" name="JPEG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/dib/" name="DIB" description="Независимое от устройства растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/dicom/" name="DICOM" description="Цифровая визуализация и связь" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/dng/" name="DNG" description="Изображение цифровой камеры" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/emf/" name="EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/emz/" name="EMZ" description="Сжатый расширенный метафайл Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/gif/" name="GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/j2k/" name="J2K" description="Сжатое изображение вейвлета" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/png/" name="PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/tiff/" name="TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/tif/" name="TIF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/webp/" name="WEBP" description="Растровое веб-изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/wmf/" name="WMF" description="Метафайл Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/wmz/" name="WMZ" description="Сжатая оболочка проигрывателя Windows Media" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/tga/" name="TGA" description="Тарга Графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/svg/" name="SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/eps/" name="EPS" description="Инкапсулированный язык PostScript" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/cdr/" name="CDR" description="Векторный рисунок изображения" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/cmx/" name="CMX" description="Обмен изображениями Corel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/otg/" name="OTG" description="Стандарт OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/odg/" name="ODG" description="Формат отрисовки Apache OpenOffice" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/java/binarize/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
