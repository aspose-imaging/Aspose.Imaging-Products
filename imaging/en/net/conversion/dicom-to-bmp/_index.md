﻿---
title: Convert images DICOM to BMP via C# 
weight: 3920
url: /net/conversion/dicom-to-bmp/ 
lang: en
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Sample code for DICOM to BMP C# image conversion. Use API example code for batch DICOM files to BMP conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert images DICOM to BMP via C#" h2="Transform images DICOM into BMP using native .NET APIs without needing any image editor or 3rd-party libraries" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="Aspose.Imaging" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API Home" codeSamplesText="Code samples" liveDemosText="Live Demos" downloadText="Download" learnText="Learn" overviewText="Overview" >}}

{{% blocks/products/pf/agp/content h2="How to Convert DICOM to BMP Using C#" %}}

Converting file formats may seem like a routine task encountered by graphic designers. Yet, underestimating its significance would be a mistake. The evaluation of your work might depend on how swiftly and effectively you tackle this task. Typically, original images need conversion into formats better suited for printing or online publication. If the original image originates from a graphic editor, it might be in vector format. In this scenario, it must be rasterized and converted to a raster format for publishing purposes. You have the choice to save the image in an uncompressed format for optimal quality or convert it to a lossless compressed format to reduce file size. In certain contexts, like web publishing, you can opt for lossy compressed formats. Specially designed algorithms for image data compression permit a significant reduction in file size while preserving acceptable image quality. This facilitates fast image file downloads from the internet. In order to convert DICOM to BMP, we'll use [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API which is a feature-rich, powerful and easy to use image manipulation and conversion API for C# platform. Open [NuGet](https://www.nuget.org/packages/aspose.imaging) package manager, search for
 **Aspose.Imaging** and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert DICOM to BMP via C#" %}}

{{% blocks/products/pf/agp/text %}}

Developers can easily load & convert DICOM files to BMP in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

+ load DICOM file with Image.Load method;
+ create & set the instance of required subclass of ImageOptionsBase (e.g. BmpOptions, PngOptions, etc.);
+ call the Image.Save method;
+ pass file path with BMP extension & object of ImageOptionsBase class.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Before running the conversion example code, make sure that you have the following prerequisites:

{{% /blocks/products/pf/agp/text %}}

+ Operating system: Windows or Linux.
+ Development environment: Supports .NET Core 7 and higher, such as Microsoft Visual Studio.
  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Free App to Convert DICOM to BMP"
        appName="Conversion"
        extension="DICOM-to-BMP"
        label1="Select or drag and drop DICOM image"
        label2="Choose format and click Convert button"
        label3="Click Download button to download BMP image"
        checkFreeAppLabel="Check our [live demos to convert DICOM to BMP]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/DICOM-to-BMP)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Convert DICOM to BMP - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "d2556ab69aeedafc6cf8c7c569c46075" "convert-dicom-to-bmp.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More | DICOM">}}
DICOM is the acronym for Digital Imaging and Communications in Medicine and pertains to the field of Medical Informatics. DICOM is the combination of file format definition and a network communications protocol. DICOM uses the .DCM extension. .DCM exist in two different formats i.e. format 1.x and format 2.x. DCM Format 1.x is further available in two versions normal and extended. DICOM is used for the integration of medical imaging devices like printers, servers, scanners etc from various vendors and also contains identification data of each patient for uniqueness. DICOM files can be shared between two parties if they are capable of receiving image data in DICOM format. The communication part of DICOM is application layer protocol and uses TCP/IP to communicate between entities. HTTP and HTTPS protocols are used for the web services of DICOM. Versions supported by web services are 1.0, 1.1, 2 or later.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" whatIsFormat1="What is" whatIsFormat2="File Format" readMoreFormat="Read More | BMP">}}
Files having extension .BMP represent Bitmap Image files that are used to store bitmap digital images. These images are independent of graphics adapter and are also called device independent bitmap (DIB) file format. This independency serves the purpose of opening the file on multiple platforms such as Microsoft Windows and Mac. The BMP file format can store data as two-dimensional digital images  in both monochrome as well as color format with various colour depths.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Conversions" subTitle="Using C#, one can easily convert different formats including:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-bmp/" name="BMP" description="Bitmap Picture" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-gif/" name="GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-emf/" name="EMF" description="Enhanced Metafile Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-jpg/" name="JPG" description="Joint Photographic Experts Group" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-jpeg/" name="JPEG" description="Joint Photographic Experts Group" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-j2k/" name="J2K" description="Wavelet Compressed Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-png/" name="PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-apng/" name="APNG" description="Animated Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-psd/" name="PSD" description="Photoshop Document" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-dxf/" name="DXF" description="Drawing Interchange Format, or Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-svg/" name="SVG" description="Scalable Vector Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-tiff/" name="TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-webp/" name="WEBP" description="Raster Web Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-pdf/" name="PDF" description="Portable Document Format (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-html/" name="HTML" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-emz/" name="EMZ" description="Windows Compressed Enhanced Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-wmz/" name="WMZ" description="Compressed Windows Media Player Skin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-svgz/" name="SVGZ" description="Compressed version of Scalable Vector Graphics (.SVG) file." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-canvas/" name="CANVAS" description="HTML5 Canvas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/net/conversion/dicom-to-ico/" name="ICO" description="Windows icon" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
