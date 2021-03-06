---
title: 通过 Java 将 DIB 转换为 PNG 
weight: 3920
url: /zh-hans/java/conversion/dib-to-png/ 
lang: zh-hans
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans
description: Sample code for DIB to PNG Java conversion. Use API example code for batch DIB files to PNG conversion within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通过 Java 将 DIB 转换为 PNG" h2="使用原生 Java API 将 DIB 转换为 PNG，无需任何图像编辑器或第 3 方库。" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="Aspose.Imaging" subTitlepfName="Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/imaging/aspose_imaging-for-java.svg" apiHomeLink="https://products.aspose.com/imaging/zh-hans/java" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java" liveDemosLink="https://products.aspose.app/imaging/family" docsLink="https://docs.aspose.com/imaging/zh-hans/java" installationsDocsLink="https://docs.aspose.com/imaging/java" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java" learnAsLink="https://docs.aspose.com/imaging/java" apiReference="" apiHomeText="API 主页" codeSamplesText="代码示例" liveDemosText="现场演示" downloadText="下载" learnText="学习">}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 DIB 转换为 PNG" %}}

为了将 DIB 转换为 PNG，我们将使用
[Aspose.Imaging for Java](https://products.aspose.com/imaging/java)
API 是一个功能丰富、功能强大且易于使用的 Java 平台图像处理和转换 API。您可以直接从
[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging)
并通过将以下配置添加到 pom.xml 将其安装在基于 Maven 的项目中。

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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 DIB 转换为 PNG 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

开发人员只需几行代码即可轻松加载 DIB 文件并将其转换为 PNG。

{{% /blocks/products/pf/agp/text %}}

+ Load DIB file with Image.load method
+ Create & set the instance of required subclass of ImageOptionsBase (e.g. BmpOptions, PngOptions, etc.)
+ Call the Image.save method
+ Pass file path with PNG extension & object of ImageOptionsBase class

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

在运行转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 已安装 JDK 1.6 或更高版本。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="将 DIB 转换为 PNG - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}

{{< blocks/imaging-app-widget
        sectionTitle="将 DIB 转换为 PNG 的免费应用程序"
        appName="Conversion"
        extension="DIB to PNG"
        label1="选择或拖放 DIB 图像"
        label2="选择格式并单击转换按钮"
        label3="点击下载按钮下载 PNG 图像"
        checkFreeAppLabel="查看我们的 [将 DIB 转换为 PNG 的现场演示]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/zh-hans/conversion/DIB-to-PNG)"
        showPreview="true">}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DIB" readMoreLink="https://docs.fileformat.com/image/dib" whatIsFormat1="什么是" whatIsFormat2="文件格式" readMoreFormat="阅读更多">}}
DIB（设备独立位图）文件是一种光栅图像文件，其结构类似于标准位图文件 (BMP)，但具有不同的标题。几乎所有可以在 Windows 和 macOS 上打开标准 BMP 文件的应用程序都可以打开它。 DIB 是二进制文件，具有类似于 BMP 的复杂文件格式。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png" whatIsFormat1="什么是" whatIsFormat2="文件格式" readMoreFormat="阅读更多">}}
PNG，便携式网络图形，是指一种使用无损压缩的光栅图像文件格式。此文件格式是作为图形交换格式 (GIF) 的替代品而创建的，没有版权限制。但是，PNG 文件格式不支持动画。 PNG文件格式支持无损图像压缩，使其在用户中很受欢迎。随着时间的推移，PNG 已经发展成为最常用的图像文件格式之一。几乎所有操作系统都支持打开 PNG 文件。例如，Microsoft Windows 查看器能够打开 PNG 文件，因为操作系统默认支持作为安装的一部分。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="使用 Java，可以轻松转换不同的格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-bmp" name="BMP" description="位图图片" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-gif" name="GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-dicom" name="DICOM" description="数码影像与通讯" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-emf" name="EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-jpg" name="JPG" description="联合摄影专家组" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-jpeg" name="JPEG" description="联合摄影专家组" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-jp2" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-j2k" name="J2K" description="小波压缩图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-jpeg2000" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-png" name="PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-apng" name="APNG" description="动画便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-psd" name="PSD" description="Photoshop 文档" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-dxf" name="DXF" description="图纸交换格式，或图纸交换格式，" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-svg" name="SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-tiff" name="TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-webp" name="WEBP" description="光栅 Web 图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-wmf" name="WMF" description="微软视窗元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-pdf" name="PDF" description="便携式文档格式 (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-html" name="HTML" description="HTML5 画布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-emz" name="EMZ" description="Windows 压缩增强元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-wmz" name="WMZ" description="压缩的 Windows Media Player 皮肤" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-tga" name="TGA" description="塔加图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-svgz" name="SVGZ" description="可缩放矢量图形 (.SVG) 文件的压缩版本。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/dib-to-canvas" name="CANVAS" description="HTML5 画布" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
