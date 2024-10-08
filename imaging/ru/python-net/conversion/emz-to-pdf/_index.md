﻿---
title: Использование Python для преобразования EMZ в PDF 
weight: 3920
url: /ru/python-net/conversion/emz-to-pdf/ 
lang: ru
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Как использовать Python для преобразования или конвертации изображений и фотографий из формата EMZ в PDF в настольных и веб приложениях.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Используйте Python для преобразования изображений EMZ в PDF" h2="Конвертируйте EMZ изображения и фотографии в формат PDF с использованием собственных Python приложений и серверных API" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.Imaging" subTitlepfName="для Python" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="для Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/ru/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ru/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="Главная страница API" codeSamplesText="Примеры кода" liveDemosText="Online примеры" downloadText="Скачать" learnText="Документация" overviewText="Обзор" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать изображение EMZ в PDF используя библиотеку для Python" %}}

Конвертация форматов файлов — это рутинная задача, с которой регулярно сталкивается любой, кто работает с изображениями и фотографиями. От скорости и качества преобразования файлов зависят и сроки выполнения, и оценки результатов работы. Что касается полученных исходных изображений, то часто требуется их преобразование в другие форматы, более подходящие для печати на бумажных носителях или для распространения в Интернете. Изображение, подготовленное в графическом редакторе будет, возможно, в векторном формате. В таком случае, для размещения на сайте его необходимо растеризовать и сохранить в растровом формате. Вы можете сохранить изображение в формате без сжатия, чтобы добиться лучшего качества, или же конвертировать его в формат со сжатием без потерь, чтобы уменьшить размер файла. Для некоторых случаев, когда важно уменьшить размер файла, например, для веб сайтов, доступна конвертация в форматы со сжатием с потерями. Специальные алгоритмы сжатия данных для изображений позволяют значительно уменьшить размер файла при сохранении приемлемого качества изображения, обеспечивая тем самым быструю загрузку изображений. Для преобразования изображений и фотографий из формата EMZ в PDF мы воспользуемся [Aspose.Imaging for Python via .NET](/imaging/ru/python-net) API, который представляет собой многофункциональный, мощный и простой в использовании API для обработки и преобразования изображений для платформы Python. Вы можете установить его, используя следующую команду из вашей системной командной консоли:

{{% blocks/products/pf/agp/code-block title="Системная командная строка" offSpacer="true" %}}

```CS
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию EMZ в PDF через Python" %}}

{{% blocks/products/pf/agp/text %}}

Разработчики могут легко загружать и преобразовывать файлы EMZ в PDF, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+ загрузите файл EMZ методом Image.Load;
+ создайте и установите экземпляр требуемого подкласса ImageOptionsBase (например, BmpOptions, PngOptions и т. д.);
+ вызовите метод Image.Save;
+ передайте путь к файлу с расширением PDF и объект класса ImageOptionsBase.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Прежде чем запускать код примера преобразования, убедитесь, что выполнены следующие предварительные условия:

{{% /blocks/products/pf/agp/text %}}

+ Операционная система Windows или Linux.
+ Среда разработки поддерживающая .NET Core 7 и выше, например Microsoft Visual Studio.
  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Бесплатное приложение для конвертации изображений EMZ в PDF"
        appName="Conversion"
        extension="EMZ-to-PDF"
        label1="Выберите или перетащите мышью изображение формата EMZ"
        label2="Выберите формат и нажмите кнопку `Конвертировать`"
        label3="Нажмите кнопку `Скачать` для скачивания PDF изображения"
        checkFreeAppLabel="Посмотрите наши [примеры для конвертации EMZ в PDF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/ru/conversion/EMZ-to-PDF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Преобразование EMZ в PDF - Python" offSpacer="true" %}}

{{< gist "aspose-com-gists" "e1d418ed58a1f4598f259e62914511d4" "convert-image-to-other-format.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="EMZ" readMoreLink="https://docs.fileformat.com/image/emz/" whatIsFormat1="Чем является" whatIsFormat2="формат" readMoreFormat="Читать далее | EMZ">}}
Файл с расширением EMZ представляет собой сжатый файл изображения, более конкретно называемый файлом сжатого расширенного метафайла Windows.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" whatIsFormat1="Чем является" whatIsFormat2="формат" readMoreFormat="Читать далее | PDF">}}
Portable Document Format (PDF) — это тип документа, созданный Adobe еще в 1990-х годах. Цель этого формата файла состояла в том, чтобы ввести стандарт для представления документов и других справочных материалов в формате, который не зависит от прикладного программного обеспечения, аппаратного обеспечения, а также операционной системы. Формат файла PDF имеет полную возможность содержать такую ​​информацию, как текст, изображения, гиперссылки, поля форм, мультимедийные материалы, цифровые подписи, вложения, метаданные, геопространственные функции и 3D-объекты, которые могут стать частью исходного документа.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Используя Python, можно легко конвертировать различные форматы, в том числе:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-bmp/" name="BMP" description="Растровое изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-gif/" name="GIF" description="Графический формат обмена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-dicom/" name="DICOM" description="Цифровая визуализация и связь" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-emf/" name="EMF" description="Расширенный формат метафайла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-jpg/" name="JPG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-jpeg/" name="JPEG" description="Объединенная группа экспертов по фотографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-j2k/" name="J2K" description="Сжатое изображение вейвлета" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-png/" name="PNG" description="Портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-apng/" name="APNG" description="Анимированная портативная сетевая графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-psd/" name="PSD" description="Документ Фотошоп" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-dxf/" name="DXF" description="Формат обмена чертежами или Формат обмена чертежами," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-svg/" name="SVG" description="Масштабируемая векторная графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-tiff/" name="TIFF" description="Формат изображения с тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-webp/" name="WEBP" description="Растровое веб-изображение" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-wmf/" name="WMF" description="Метафайл Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-pdf/" name="PDF" description="Переносимый формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-html/" name="HTML" description="Холст HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-wmz/" name="WMZ" description="Сжатая оболочка проигрывателя Windows Media" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-tga/" name="TGA" description="Тарга Графика" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-svgz/" name="SVGZ" description="Сжатая версия файла масштабируемой векторной графики (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-canvas/" name="CANVAS" description="Холст HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ru/python-net/conversion/emz-to-ico/" name="ICO" description="Значок Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
