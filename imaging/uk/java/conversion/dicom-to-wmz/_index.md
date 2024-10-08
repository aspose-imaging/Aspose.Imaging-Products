﻿---
title: Перетворіть DICOM на WMZ за допомогою Java 
weight: 3920
url: /uk/java/conversion/dicom-to-wmz/ 
lang: uk
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Зразок коду для перетворення DICOM у WMZ Java. Використовуйте приклад коду API для пакетного перетворення файлів DICOM у WMZ у будь-якій веб-програмі або програмі Java на основі комп’ютера.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Перетворіть DICOM на WMZ за допомогою Java" h2="Перетворіть DICOM у WMZ за допомогою власних API Java, не потребуючи будь-якого редактора зображень або сторонніх бібліотек." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="WMZ" pfName="Aspose.Imaging" subTitlepfName="для Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="для Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/uk/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/uk/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Домашня сторінка API" codeSamplesText="Зразки коду" liveDemosText="Живі демонстрації" downloadText="Завантажити" learnText="Документацiя" overviewText="Огляд" >}}

{{% blocks/products/pf/agp/content h2="Як перетворити DICOM на WMZ за допомогою Java" %}}

Перетворення форматів файлів може здатися рутинним завданням, з яким стикаються графічні дизайнери. Проте недооцінювати його значення було б помилкою. Оцінка вашої роботи може залежати від того, наскільки швидко і ефективно ви вирішите це завдання. Як правило, оригінальні зображення потребують перетворення у формати, які краще підходять для друку або публікації в Інтернеті. Якщо вихідне зображення походить із графічного редактора, воно може бути у векторному форматі. У цьому випадку його потрібно растеризувати та перетворити на растровий формат для публікації. У вас є вибір: зберегти зображення в нестисненому форматі для оптимальної якості або конвертувати його у стиснутий формат без втрат, щоб зменшити розмір файлу. У певних контекстах, як-от веб-публікація, ви можете вибрати формати зі стисненням із втратами даних. Спеціально розроблені алгоритми стиснення даних зображення дозволяють значно зменшити розмір файлу, зберігаючи прийнятну якість зображення. Це полегшує швидке завантаження файлів зображень з Інтернету. Щоб перетворити DICOM на WMZ, ми будемо використовувати [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API, який є багатофункціональним, потужним і простим у використанні API для обробки зображень і перетворення для платформи Java. Ви можете завантажити його останню версію безпосередньо з [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) і встановити на своєму Maven на основі проекту, додавши такі конфігурації до pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Кроки для перетворення DICOM у WMZ за допомогою Java" %}}

{{% blocks/products/pf/agp/text %}}

Розробники можуть легко завантажити та перетворити файли DICOM у WMZ лише за кілька рядків коду.

{{% /blocks/products/pf/agp/text %}}

+ Завантажити файл DICOM методом Image.load
+ Створіть і встановіть екземпляр необхідного підкласу ImageOptionsBase (наприклад, BmpOptions, PngOptions тощо)
+ Викличте метод Image.save
+ Передайте шлях до файлу з розширенням WMZ і об’єкт класу ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системні вимоги" %}}

{{% blocks/products/pf/agp/text %}}

Перш ніж запускати код прикладу перетворення, переконайтеся, що у вас є такі передумови.

{{% /blocks/products/pf/agp/text %}}

+ Операційна система: Windows або Linux.
+ Середовище розробки: підтримує .NET Core 7 і вище, наприклад Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Безкоштовна програма для перетворення DICOM у WMZ"
        appName="Conversion"
        extension="DICOM-to-WMZ"
        label1="Виберіть або перетягніть зображення DICOM"
        label2="Виберіть формат і натисніть кнопку Конвертувати."
        label3="Натисніть кнопку «Завантажити», щоб завантажити зображення WMZ"
        checkFreeAppLabel="Перегляньте наші [демонстрації в прямому ефірі для перетворення DICOM у WMZ]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/DICOM-to-WMZ)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Перетворити DICOM на WMZ - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="Що таке" whatIsFormat2="формат" readMoreFormat="Детальніше | DICOM">}}
DICOM — це абревіатура від Digital Imaging and Communications in Medicine і відноситься до галузі медичної інформатики. DICOM — це поєднання визначення формату файлу та протоколу мережевого зв’язку. DICOM використовує розширення .DCM. .DCM існує у двох різних форматах, тобто форматі 1.x і форматі 2.x. Формат DCM 1.x також доступний у двох версіях: звичайній і розширеній. DICOM використовується для інтеграції медичних пристроїв візуалізації, таких як принтери, сервери, сканери тощо від різних постачальників, а також містить ідентифікаційні дані кожного пацієнта для унікальності. Файли DICOM можуть використовуватися між двома сторонами, якщо вони здатні отримувати дані зображення у форматі DICOM. Комунікаційна частина DICOM є протоколом прикладного рівня та використовує TCP/IP для зв’язку між об’єктами. Для веб-служб DICOM використовуються протоколи HTTP і HTTPS. Веб-службами підтримуються версії 1.0, 1.1, 2 або новіші.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WMZ" readMoreLink="https://docs.fileformat.com/image/wmz/" whatIsFormat1="Що таке" whatIsFormat2="формат" readMoreFormat="Детальніше | WMZ">}}
WMZ — це розширення файлу для формату файлу оболонки, який/для/використовується медіапрогравачем Windows. WMZ-файл – це в основному заархівований файл WMF у форматі XML.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Інші підтримувані перетворення" subTitle="Використовуючи Java, можна легко конвертувати різні формати, зокрема." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-bmp/" name="BMP" description="Растрове зображення" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-gif/" name="GIF" description="Графічний формат обміну" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-emf/" name="EMF" description="Розширений формат метафайлу" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-jpg/" name="JPG" description="Об’єднана експертна група з фотографій" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-jpeg/" name="JPEG" description="Об’єднана експертна група з фотографій" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-j2k/" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-png/" name="PNG" description="Портативна мережева графіка" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-apng/" name="APNG" description="Анімована переносна мережева графіка" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-psd/" name="PSD" description="Документ Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-dxf/" name="DXF" description="Формат обміну малюнками або формат обміну малюнками," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-svg/" name="SVG" description="Масштабована векторна графіка" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-tiff/" name="TIFF" description="Формат зображення з тегами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-webp/" name="WEBP" description="Растрове веб-зображення" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-wmf/" name="WMF" description="Метафайл Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-pdf/" name="PDF" description="Портативний формат документа (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-html/" name="HTML" description="Полотно HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-emz/" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-wmz/" name="WMZ" description="Стиснена оболонка Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-svgz/" name="SVGZ" description="Стиснута версія файлу масштабованої векторної графіки (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-canvas/" name="CANVAS" description="Полотно HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/uk/java/conversion/dicom-to-ico/" name="ICO" description="Значок Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
