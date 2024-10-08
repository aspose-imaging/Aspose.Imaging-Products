﻿---
title: Перетворіть JP2 на JPEG2000 за допомогою Java 
weight: 3920
url: /uk/java/conversion/jp2-to-jpeg2000/ 
lang: uk
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Зразок коду для перетворення JP2 у JPEG2000 Java. Використовуйте приклад коду API для пакетного перетворення файлів JP2 у JPEG2000 у будь-якій веб-програмі або програмі Java на основі комп’ютера.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Перетворіть JP2 на JPEG2000 за допомогою Java" h2="Перетворіть JP2 у JPEG2000 за допомогою власних API Java, не потребуючи будь-якого редактора зображень або сторонніх бібліотек." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG2000" pfName="Aspose.Imaging" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/uk/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/uk/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Домашня сторінка API" codeSamplesText="Зразки коду" liveDemosText="Живі демонстрації" downloadText="Завантажити" learnText="Документацiя" overviewText="Огляд" >}}

{{% blocks/products/pf/agp/content h2="Як перетворити JP2 на JPEG2000 за допомогою Java" %}}

Перетворення форматів файлів може здатися рутинним завданням, з яким стикаються графічні дизайнери. Проте недооцінювати його значення було б помилкою. Оцінка вашої роботи може залежати від того, наскільки швидко і ефективно ви вирішите це завдання. Як правило, оригінальні зображення потребують перетворення у формати, які краще підходять для друку або публікації в Інтернеті. Якщо вихідне зображення походить із графічного редактора, воно може бути у векторному форматі. У цьому випадку його потрібно растеризувати та перетворити на растровий формат для публікації. У вас є вибір: зберегти зображення в нестисненому форматі для оптимальної якості або конвертувати його у стиснутий формат без втрат, щоб зменшити розмір файлу. У певних контекстах, як-от веб-публікація, ви можете вибрати формати зі стисненням із втратами даних. Спеціально розроблені алгоритми стиснення даних зображення дозволяють значно зменшити розмір файлу, зберігаючи прийнятну якість зображення. Це полегшує швидке завантаження файлів зображень з Інтернету. Щоб перетворити JP2 на JPEG2000, ми будемо використовувати [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API, який є багатофункціональним, потужним і простим у використанні API для обробки зображень і перетворення для платформи Java. Ви можете завантажити його останню версію безпосередньо з [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) і встановити на своєму Maven на основі проекту, додавши такі конфігурації до pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторiй" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Залежність" offSpacer="true" %}}

```xml
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-imaging</artifactId>
<version>Version of aspose-imaging API</version>
<classifier>jdk16</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Кроки для перетворення JP2 у JPEG2000 за допомогою Java" %}}

{{% blocks/products/pf/agp/text %}}

Розробники можуть легко завантажити та перетворити файли JP2 у JPEG2000 лише за кілька рядків коду.

{{% /blocks/products/pf/agp/text %}}

+ Завантажити файл JP2 методом Image.load
+ Створіть і встановіть екземпляр необхідного підкласу ImageOptionsBase (наприклад, BmpOptions, PngOptions тощо)
+ Викличте метод Image.save
+ Передайте шлях до файлу з розширенням JPEG2000 і об’єкт класу ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системні вимоги" %}}

{{% blocks/products/pf/agp/text %}}

Перш ніж запускати код прикладу перетворення, переконайтеся, що у вас є такі передумови.

{{% /blocks/products/pf/agp/text %}}

+ Операційна система: Windows або Linux.
+ Середовище розробки: підтримує .NET Core 7 і вище, наприклад Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Безкоштовна програма для перетворення JP2 у JPEG2000"
        appName="Conversion"
        extension="JP2-to-JPEG2000"
        label1="Виберіть або перетягніть зображення JP2"
        label2="Виберіть формат і натисніть кнопку Конвертувати."
        label3="Натисніть кнопку «Завантажити», щоб завантажити зображення JPEG2000"
        checkFreeAppLabel="Перегляньте наші [демонстрації в прямому ефірі для перетворення JP2 у JPEG2000]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/JP2-to-JPEG2000)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Перетворити JP2 на JPEG2000 - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Що таке" whatIsFormat2="формат" readMoreFormat="Детальніше | JP2">}}
JPEG 2000 (JP2) — це система кодування зображень і сучасний стандарт стиснення зображень. Розроблений із використанням вейвлет-технології JPEG 2000 може кодувати вміст без втрат у будь-якій якості одночасно. Крім того, без суттєвого зниження ефективності кодування JPEG 2000 має можливість отримувати доступ і ефективно декодувати той самий вміст у різні інші роздільності та якості. Потоки коду в JPEG 2000 є значно масштабованими, маючи області інтересу, які забезпечують можливість просторового довільного доступу. Має до 16384 різноманітних компонентів із розмірами в терапікселях і точністю до 38 біт/зразок.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="Що таке" whatIsFormat2="формат" readMoreFormat="Детальніше | JPEG2000">}}
JPEG 2000 (JP2) — це система кодування зображень і сучасний стандарт стиснення зображень. Розроблений із використанням вейвлет-технології JPEG 2000 може кодувати вміст без втрат у будь-якій якості одночасно. Крім того, без суттєвого зниження ефективності кодування JPEG 2000 має можливість отримувати доступ і ефективно декодувати той самий вміст у різні інші роздільності та якості. Потоки коду в JPEG 2000 є значно масштабованими, маючи області інтересу, які забезпечують можливість просторового довільного доступу. Має до 16384 різноманітних компонентів із розмірами в терапікселях і точністю до 38 біт/зразок.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Інші підтримувані перетворення" subTitle="Використовуючи Java, можна легко конвертувати різні формати, зокрема." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-bmp/" name="BMP" description="Растрове зображення" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-gif/" name="GIF" description="Графічний формат обміну" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-dicom/" name="DICOM" description="Цифрові зображення та комунікації" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-emf/" name="EMF" description="Розширений формат метафайлу" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-jpg/" name="JPG" description="Об’єднана експертна група з фотографій" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-jpeg/" name="JPEG" description="Об’єднана експертна група з фотографій" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-j2k/" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-png/" name="PNG" description="Портативна мережева графіка" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-apng/" name="APNG" description="Анімована переносна мережева графіка" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-psd/" name="PSD" description="Документ Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-dxf/" name="DXF" description="Формат обміну малюнками або формат обміну малюнками," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-svg/" name="SVG" description="Масштабована векторна графіка" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-tiff/" name="TIFF" description="Формат зображення з тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-webp/" name="WEBP" description="Растрове веб-зображення" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-wmf/" name="WMF" description="Метафайл Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-pdf/" name="PDF" description="Портативний формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-html/" name="HTML" description="Полотно HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-emz/" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-wmz/" name="WMZ" description="Стиснена оболонка Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-svgz/" name="SVGZ" description="Стиснута версія файлу масштабованої векторної графіки (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-canvas/" name="CANVAS" description="Полотно HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/jp2-to-ico/" name="ICO" description="Значок Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
