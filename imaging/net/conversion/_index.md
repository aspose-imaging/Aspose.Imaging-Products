---
title: C# Image Formats Conversion
url: /net/conversion/
description: Convert popular image, photo, picture formats via .NET library. Convert to PSD, PDF, GIF, JPG,  SVG including HTML5 Canvas with few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Image Files Conversion Via C#" h2="Convert Image formats, Metafiles, WebP, Svg, Apng to build cross-platform .NET based advance image processing applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API facilitates the advanced image processing and rendering features for programmers. Developers can integrate it to convert raster & vector images, including photos and pictures to PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP,  WMF, EMF and other image formats. API not only deals with conversion of files but also deals converting images to black n white and grayscale, convert GIF image layers and more.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Image to Bitmap BMP, JPG, PNG" %}}

Using C# Image API, Inter format conversion is as easy as just changing the extension of the desired format. Here are few generic cases such as **image to bmp**, **image to jpg**, **image to png** and developers can easily enhance for their specific format. Process is load the source image via [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Create an object of target [image format options](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) for any specific settings. Finally call the [Save Method](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) by passing the target file with path and Saving options as parameter.

{{% blocks/products/pf/feature-page-code h3="C# Code for Inter Conversion of Images" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-inter-conversion-of-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="apng-to-bmp cdr-to-bmp dib-to-bmp dicom-to-bmp djvu-to-bmp dng-to-bmp emf-to-bmp emz-to-bmp eps-to-bmp gif-to-bmp" >}}

{{% blocks/products/pf/feature-page-section  h2="Raster Image to PDF Conversion" %}}

Process of converting raster images to PDF is same as of inter conversion of images, except that API provides [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) for specific PDF settings. Programmers can easily enhance it for their specific needs.

{{% blocks/products/pf/feature-page-code h3="C# Code for Raster Images to PDF Conversion" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="apng-to-pdf jpeg-to-pdf bmp-to-pdf odg-to-pdf otg-to-pdf png-to-pdf svg-to-pdf emz-to-pdf eps-to-pdf gif-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert SVG to Raster Images BMP, PNG, JPG" %}}

Conversion process of SVG is same, Load SVG file, Use relevant image saving options and calling the Save method. Image API provides [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) for setting PageWidth, PageHeight and raster images use their VectorRasterizationOptions property for initialization and getting SvgRasterizationOptions options. 

{{% blocks/products/pf/feature-page-code h3="C# Code for SVG to Raster Images" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="bmp-to-svg jpeg-to-svg png-to-svg" >}}