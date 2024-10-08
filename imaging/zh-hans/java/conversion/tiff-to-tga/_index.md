﻿---
title: 通过 Java 将 TIFF 转换为 TGA 
weight: 3920
url: /zh-hans/java/conversion/tiff-to-tga/ 
lang: zh-hans
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: TIFF 到 TGA Java 转换的示例代码。在任何基于 Web 或桌面 Java 的应用程序中使用 API 示例代码将 TIFF 文件批量转换为 TGA。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通过 Java 将 TIFF 转换为 TGA" h2="使用原生 Java API 将 TIFF 转换为 TGA，无需任何图像编辑器或第 3 方库。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TGA" pfName="Aspose.Imaging" subTitlepfName="Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/zh-hans/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/zh-hans/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API主页" codeSamplesText="代码示例" liveDemosText="现场演示" downloadText="下载" learnText="学习" overviewText="概述" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 TIFF 转换为 TGA" %}}

转换文件格式似乎是图形设计师遇到的例行任务。然而，低估其重要性将是一个错误。对您工作的评估可能取决于您处理这项任务的速度和效率。通常，原始图像需要转换为更适合打印或在线出版的格式。如果原始图像来自图形编辑器，则它可能是矢量格式。在这种情况下，必须对其进行栅格化并转换为栅格格式以用于发布目的。您可以选择以未压缩格式保存图像以获得最佳质量，或将其转换为无损压缩格式以减小文件大小。在某些情况下，例如网络发布，您可以选择有损压缩格式。专门设计的图像数据压缩算法可以显着减小文件大小，同时保持可接受的图像质量。这有利于从互联网上快速下载图像文件。为了将 TIFF 转换为 TGA，我们将使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API 是一个功能丰富、功能强大 易于使用的 Java 平台图像处理和转换 API。您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging)
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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 TIFF 转换为 TGA 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

开发人员只需几行代码即可轻松加载 TIFF 文件并将其转换为 TGA。

{{% /blocks/products/pf/agp/text %}}

+ 使用 Image.load 方法加载 TIFF 文件
+ 创建和设置 ImageOptionsBase 所需子类的实例（例如 BmpOptions、PngOptions 等）
+ 调用 Image.save 方法
+ 传递带有 TGA 扩展名的文件路径和 ImageOptionsBase 类的对象

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

在运行转换示例代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

+ 操作系统：Windows 或Linux。
+ 开发环境：支持.NET Core 7及更高版本，例如Microsoft Visual Studio。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="将 TIFF 转换为 TGA 的免费应用程序"
        appName="Conversion"
        extension="TIFF-to-TGA"
        label1="选择或拖放 TIFF 图像"
        label2="选择格式并单击转换按钮"
        label3="点击下载按钮下载 TGA 图像"
        checkFreeAppLabel="查看我们的 [将 TIFF 转换为 TGA 的现场演示]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/zh-hans/conversion/TIFF-to-TGA)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="将 TIFF 转换为 TGA - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" whatIsFormat1="什么是" whatIsFormat2="文件格式" readMoreFormat="阅读更多 | TIFF">}}
TIFF 或 TIF，标记图像文件格式，表示用于在符合此文件格式标准的各种设备上使用的光栅图像。它能够在多个颜色空间中描述双层、灰度、调色板颜色和全彩色图像数据。它支持有损和无损压缩方案，以便为使用该格式的应用程序在空间和时间之间进行选择。该格式是可扩展的，并且经过多次修改，允许包含无限量的私人或特殊用途信息。该格式不依赖于机器，并且不受处理器、操作系统或文件系统等限制。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TGA" readMoreLink="https://docs.fileformat.com/image/tga/" whatIsFormat1="什么是" whatIsFormat2="文件格式" readMoreFormat="阅读更多 | TGA">}}
Truevision TGA，通常称为 TARGA，是由 Truevision Inc.（现为 Avid Technology 的一部分）创建的光栅图形文件格式。它是 TARGA 和 VISTA 板的原生格式，它们是 IBM 兼容 PC 上第一款支持高彩/真彩显示的显卡。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="使用 Java，可以轻松转换不同的格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-bmp/" name="BMP" description="位图图片" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-gif/" name="GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-dicom/" name="DICOM" description="数码影像与通讯" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-emf/" name="EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-jpg/" name="JPG" description="联合摄影专家组" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-jpeg/" name="JPEG" description="联合摄影专家组" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-j2k/" name="J2K" description="小波压缩图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-png/" name="PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-apng/" name="APNG" description="动画便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-psd/" name="PSD" description="Photoshop 文档" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-dxf/" name="DXF" description="图纸交换格式，或图纸交换格式，" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-svg/" name="SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-webp/" name="WEBP" description="光栅 Web 图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-wmf/" name="WMF" description="微软视窗元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-pdf/" name="PDF" description="便携式文档格式 (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-html/" name="HTML" description="HTML5 画布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-emz/" name="EMZ" description="Windows 压缩增强元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-wmz/" name="WMZ" description="压缩的 Windows Media Player 皮肤" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-tga/" name="TGA" description="塔加图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-svgz/" name="SVGZ" description="可缩放矢量图形 (.SVG) 文件的压缩版本。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-canvas/" name="CANVAS" description="HTML5 画布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/conversion/tiff-to-ico/" name="ICO" description="窗口图标" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
