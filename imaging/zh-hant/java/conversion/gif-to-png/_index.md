---
title: 通過 Java 將 GIF 轉換為 PNG 
weight: 3920
url: /zh-hant/java/conversion/gif-to-png/ 
lang: zh-hant
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans
description: Sample code for GIF to PNG Java conversion. Use API example code for batch GIF files to PNG conversion within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通過 Java 將 GIF 轉換為 PNG" h2="使用原生 Java API 將 GIF 轉換為 PNG，無需任何圖像編輯器或第 3 方庫。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="Aspose.Imaging" subTitlepfName="Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/imaging/aspose_imaging-for-java.svg" apiHomeLink="https://products.aspose.com/imaging/zh-hant/java" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java" liveDemosLink="https://products.aspose.app/imaging/family" docsLink="https://docs.aspose.com/imaging/zh-hant/java" installationsDocsLink="https://docs.aspose.com/imaging/java" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java" learnAsLink="https://docs.aspose.com/imaging/java" apiReference="" apiHomeText="API 主頁" codeSamplesText="代碼示例" liveDemosText="現場演示" downloadText="下載" learnText="學習">}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 GIF 轉換為 PNG" %}}

為了將 GIF 轉換為 PNG，我們將使用
[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
API 是一個功能豐富、功能強大且易於使用的 Java 平台圖像處理和轉換 API。您可以直接從
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging)
並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 GIF 轉換為 PNG 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

開發人員只需幾行代碼即可輕鬆加載 GIF 文件並將其轉換為 PNG。

{{% /blocks/products/pf/agp/text %}}

+ Load GIF file with Image.load method
+ Create & set the instance of required subclass of ImageOptionsBase (e.g. BmpOptions, PngOptions, etc.)
+ Call the Image.save method
+ Pass file path with PNG extension & object of ImageOptionsBase class

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

在運行轉換示例代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- 已安裝 JDK 1.6 或更高版本。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="將 GIF 轉換為 PNG - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

{{< blocks/imaging-app-widget
        sectionTitle="將 GIF 轉換為 PNG 的免費應用程序"
        appName="Conversion"
        extension="GIF to PNG"
        label1="選擇或拖放 GIF 圖像"
        label2="選擇格式並單擊轉換按鈕"
        label3="點擊下載按鈕下載 PNG 圖像"
        checkFreeAppLabel="查看我們的 [將 GIF 轉換為 PNG 的現場演示]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/zh-hant/conversion/GIF-to-PNG)"
        showPreview="true">}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="GIF" readMoreLink="https://docs.fileformat.com/image/gif" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多">}}
A GIF or Graphical Interchange Format is a type of highly compressed image. Owned by Unisys, GIF uses the LZW compression algorithm that does not degrade the image quality. For each image GIF typically allow up to 8 bits per pixel and up to 256 colours are allowed across the image. In contrast to a JPEG image, which can display up to 16 million colours and fairly touches the limits of the human eye. Back when the internet emerged, GIFs remained the best choice because they required low bandwidth and compatible for the graphics that consume solid areas of colour. An animated GIF combines numerous images or frames into a single file and displays them in a sequence to generate an animated clip or a short video. The colour limitations are up to 256 for each frame and are likely to be the least suitable for reproducing other images and photographs with colour gradient.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多">}}
PNG, Portable Network Graphics, refers to a type of raster image file format that use loseless compression. This file format was created as a replacement of Graphics Interchange Format (GIF) and has no copyright limitations. However, PNG file format does not support animations. PNG file format supports loseless image compression that makes it popular among its users. With the passage of time, PNG has evolved as one of the mostly used image file format. Almost all Operating Systems have support for opening PNG files. For example, Microsoft Windows viewer has the capability to open PNG files as the OS has by default the support available as part of installation.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="使用 Java，可以輕鬆轉換不同的格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-bmp" name="BMP" description="Bitmap Picture" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-dicom" name="DICOM" description="Digital Imaging & Communications" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-emf" name="EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-jpg" name="JPG" description="Joint Photographic Experts Group" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-jpeg" name="JPEG" description="Joint Photographic Experts Group" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-jp2" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-j2k" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-png" name="PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-jpeg2000" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-apng" name="APNG" description="Animated Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-psd" name="PSD" description="Photoshop Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-dxf" name="DXF" description="Drawing Interchange Format, or Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-svg" name="SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-tiff" name="TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-webp" name="WEBP" description="Raster Web Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-wmf" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-pdf" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-html" name="HTML" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-emz" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-wmz" name="WMZ" description="Compressed Windows Media Player Skin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-tga" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-svgz" name="SVGZ" description="Compressed version of Scalable Vector Graphics (.SVG) file." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/gif-to-canvas" name="CANVAS" description="HTML5 Canvas" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
