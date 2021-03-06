---
title: 通過 Java 將 JPEG 轉換為 WEBP 
weight: 3920
url: /zh-hant/java/conversion/jpeg-to-webp/ 
lang: zh-hant
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans
description: Sample code for JPEG to WEBP Java conversion. Use API example code for batch JPEG files to WEBP conversion within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通過 Java 將 JPEG 轉換為 WEBP" h2="使用原生 Java API 將 JPEG 轉換為 WEBP，無需任何圖像編輯器或第 3 方庫。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="WEBP" pfName="Aspose.Imaging" subTitlepfName="Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/imaging/aspose_imaging-for-java.svg" apiHomeLink="https://products.aspose.com/imaging/zh-hant/java" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java" liveDemosLink="https://products.aspose.app/imaging/family" docsLink="https://docs.aspose.com/imaging/zh-hant/java" installationsDocsLink="https://docs.aspose.com/imaging/java" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java" learnAsLink="https://docs.aspose.com/imaging/java" apiReference="" apiHomeText="API 主頁" codeSamplesText="代碼示例" liveDemosText="現場演示" downloadText="下載" learnText="學習">}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 JPEG 轉換為 WEBP" %}}

為了將 JPEG 轉換為 WEBP，我們將使用
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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 JPEG 轉換為 WEBP 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

開發人員只需幾行代碼即可輕鬆加載 JPEG 文件並將其轉換為 WEBP。

{{% /blocks/products/pf/agp/text %}}

+ Load JPEG file with Image.load method
+ Create & set the instance of required subclass of ImageOptionsBase (e.g. BmpOptions, PngOptions, etc.)
+ Call the Image.save method
+ Pass file path with WEBP extension & object of ImageOptionsBase class

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

在運行轉換示例代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- 已安裝 JDK 1.6 或更高版本。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="將 JPEG 轉換為 WEBP - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

{{< blocks/imaging-app-widget
        sectionTitle="將 JPEG 轉換為 WEBP 的免費應用程序"
        appName="Conversion"
        extension="JPEG to WEBP"
        label1="選擇或拖放 JPEG 圖像"
        label2="選擇格式並單擊轉換按鈕"
        label3="點擊下載按鈕下載 WEBP 圖像"
        checkFreeAppLabel="查看我們的 [將 JPEG 轉換為 WEBP 的現場演示]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/zh-hant/conversion/JPEG-to-WEBP)"
        showPreview="true">}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG" readMoreLink="https://docs.fileformat.com/image/jpeg" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多">}}
A JPEG is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Users can adjust the compression level to achieve the desired quality level while at the same time reduce the storage size. Image quality is negligibly affected if 10:1 compression is applied to the image. The higher the compression value, the higher the degradation in image quality.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WEBP" readMoreLink="https://docs.fileformat.com/image/webp" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多">}}
WebP, introduced by Google, is a modern raster web image file format that is based on lossless and lossy compression. It provides same image quality while considerably reducing the image size. Since most of the web pages use images as effective representation of data, the use of WebP images in web pages results in faster loading of web pages. As per Google, WebP lossless images are 26% smaller in size compared to PNGs, while WebP lossy images are 25-34% smaller than comparable JPEG images. Images are compared based on the Structural Similarity (SSIM) index between WebP and other image file formats. WebP is a sister project of WebM multimedia container format.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="使用 Java，可以輕鬆轉換不同的格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-bmp" name="BMP" description="Bitmap Picture" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-gif" name="GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-dicom" name="DICOM" description="Digital Imaging & Communications" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-emf" name="EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-jp2" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-j2k" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-jpeg2000" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-png" name="PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-apng" name="APNG" description="Animated Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-psd" name="PSD" description="Photoshop Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-dxf" name="DXF" description="Drawing Interchange Format, or Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-svg" name="SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-tiff" name="TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-webp" name="WEBP" description="Raster Web Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-wmf" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-pdf" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-html" name="HTML" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-emz" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-wmz" name="WMZ" description="Compressed Windows Media Player Skin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-tga" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-svgz" name="SVGZ" description="Compressed version of Scalable Vector Graphics (.SVG) file." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/jpeg-to-canvas" name="CANVAS" description="HTML5 Canvas" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
