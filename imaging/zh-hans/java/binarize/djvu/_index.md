﻿---
title: 通过 Java 对 DJVU 文档进行二值化 
weight: 3920
url: /zh-hans/java/binarize/djvu/ 
lang: zh-hans
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: 尝试使用我们的本地文档 API 对 .NET Framework、.NET Core、Windows 应用程序、ASP.NET Web 应用程序上的 DJVU 文件进行二进制化。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通过 Java 对 DJVU 进行二值化" h2="构建您自己的 Java 应用程序以使用服务器端 API 二进制化 DJVU 文件。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DJVU" pfName="Aspose.Imaging" subTitlepfName="Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/zh-hans/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API 主页" codeSamplesText="代码示例" liveDemosText="现场演示" downloadText="下载" learnText="学习">}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 二进制化 DJVU 文件" %}}

彩色胶片的发明标志着摄影领域的一个重要里程碑。然而，古典摄影本质上与黑白图像有关。尽管相机具有广泛的技术能力来捕捉全光谱的颜色，但许多人选择单色，将他们的照片变成黑白。在这种情况下，二值化函数发挥作用，将所有像素转换为二进制值：“0”表示白色，“1”表示黑色。在其他情况下，这种转换不是由艺术选择驱动的，而是由实际选择驱动的，例如准备用于在书籍或报纸上印刷的黑白插图。使用 Java 图形库，您可以指定像素亮度阈值。亮度值低于该阈值的像素将变为黑色，而高于该阈值的像素将变为白色。或者，您可以采用自适应二值化方法来考虑周围区域的像素值。这种方法可以使生成的黑白图像中颜色边界之间的过渡更加平滑。为了二值化 DJVU 文件，我们将使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API 是一个功能丰富、功能强大 易于使用的 Java 平台图像处理和转换 API。您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging)
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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 对 DJVU 进行二值化的步骤" %}}

{{% blocks/products/pf/agp/text %}}

你需要 [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) 在您自己的环境中尝试以下工作流程。

{{% /blocks/products/pf/agp/text %}}

+ 使用 Image.Load 方法加载 DJVU 文件
+二值化图像；
+ 以 Aspose.Imaging 支持的格式将压缩图像保存到光盘

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

所有主要操作系统都支持 Java 的 Aspose.Imaging。只需确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 已安装 JDK 1.6 或更高版本。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="二值化 DJVU 图像 - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "daac19b481878f17e5e6caadd16bb490" "binarize-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="关于 Java API 的 Aspose.Imaging" %}}


Aspose.Imaging API 是一种图像处理解决方案，用于在应用程序中创建、修改、绘制或转换图像（照片）。它提供：跨平台的图像处理，包括但不限于各种图像格式之间的转换（包括统一的多页或多帧图像处理）、绘图等修改、使用图形基元、转换（调整大小、裁剪、翻转和旋转） 、二值化、灰度、调整）、高级图像处理功能（过滤、抖动、遮罩、去偏斜）和内存优化策略。它是一个独立的库，不依赖任何软件进行图像操作。可以在项目中使用原生 API 轻松添加高性能图像转换功能。这些是 100% 私有的本地 API，图像在您的服务器上处理。


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="通过在线应用对 DJVU 进行二值化" sectionDescription="通过访问我们的 [Live Demos 网站](https://products.aspose.app/imaging/image-Binarize) 对 DJVU 文档进行二进制化。 现场演示有以下好处" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="无需下载或设置任何东西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="无需编写任何代码" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上传您的 DJVU 文件并点击 \"Binarize now\" 按钮" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="立即获取生成文件的下载链接" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu/" whatIsFormat1="什么是" whatIsFormat2="文件格式" readMoreFormat="阅读更多" >}}
DjVu，发音为 DJVU ，是一种图形文件格式，用于扫描文档和书籍，尤其是包含文本、绘图、图像和照片组合的文档和书籍。它是由 AT&T 实验室开发的。它使用多种技术，例如文本和背景图像的图像层分离、渐进式加载、算术编码和双色调图像的有损压缩。由于 DJVU 文件可以包含压缩但高质量的彩色图像、照片、文本和绘图，因此可以保存在更小的空间中，因此它在网络上用作电子书、手册、报纸、古代文件等。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的二值化格式" subTitle="使用 Java，可以轻松地对不同的格式进行二进制化，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/apng/" name="APNG" description="动画便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/bmp/" name="BMP" description="位图图片" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/ico/" name="ICO" description="窗口图标" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/jpg/" name="JPG" description="联合摄影专家组" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/jpeg/" name="JPEG" description="联合摄影专家组" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/dib/" name="DIB" description="设备无关位图" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/dicom/" name="DICOM" description="数码影像与通讯" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/dng/" name="DNG" description="数码相机图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/emf/" name="EMF" description="增强的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/emz/" name="EMZ" description="Windows 压缩增强元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/gif/" name="GIF" description="图形交换格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/j2k/" name="J2K" description="小波压缩图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/png/" name="PNG" description="便携式网络图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/tiff/" name="TIFF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/tif/" name="TIF" description="标记图像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/webp/" name="WEBP" description="光栅 Web 图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/wmf/" name="WMF" description="微软视窗元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/wmz/" name="WMZ" description="压缩的 Windows Media Player 皮肤" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/tga/" name="TGA" description="塔加图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/svg/" name="SVG" description="可缩放矢量图形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/eps/" name="EPS" description="封装的 PostScript 语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/cdr/" name="CDR" description="矢量绘图图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/cmx/" name="CMX" description="Corel 交换图像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/otg/" name="OTG" description="开放文档标准" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/odg/" name="ODG" description="Apache OpenOffice 绘图格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hans/java/binarize/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
