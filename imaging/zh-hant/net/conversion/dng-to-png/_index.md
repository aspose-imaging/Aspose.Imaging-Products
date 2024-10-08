﻿---
title: 通過 C# 將 DNG 轉換為 PNG 
weight: 3920
url: /zh-hant/net/conversion/dng-to-png/ 
lang: zh-hant
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: DNG 到 PNG C# 轉換的示例代碼。使用 API 示例代碼在 VB.NET、Asp.NET 或任何基於 .NET 的應用程序中將 DNG 文件批量轉換為 PNG。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通過 C# 將 DNG 轉換為 PNG" h2="使用原生 .NET API 將 DNG 轉換為 PNG，無需任何圖像編輯器或第 3 方庫。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="Aspose.Imaging" subTitlepfName=".NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/zh-hant/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/zh-hant/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API首頁" codeSamplesText="代碼示例" liveDemosText="現場演示" downloadText="下載" learnText="學習" overviewText="概述" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 將 DNG 轉換為 PNG" %}}

轉換文件格式似乎是圖形設計師遇到的例行任務。然而，低估其重要性將是一個錯誤。對您工作的評估可能取決於您處理這項任務的速度和效率。通常，原始圖像需要轉換為更適合打印或在線出版的格式。如果原始圖像來自圖形編輯器，則它可能是矢量格式。在這種情況下，必須對其進行柵格化並轉換為柵格格式以用於發布目的。您可以選擇以未壓縮格式保存圖像以獲得最佳質量，或將其轉換為無損壓縮格式以減小文件大小。在某些情況下，例如網絡發布，您可以選擇有損壓縮格式。專門設計的圖像數據壓縮算法可以顯著減小文件大小，同時保持可接受的圖像質量。這有利於從互聯網上快速下載圖像文件。為了將 DNG 轉換為 PNG，我們將使用 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API 是一個功能豐富、功能強大且易於使用的 C# 平台圖像處理和轉換 API。打開 [NuGet](https://www.nuget.org/packages/aspose.imaging) 包管理器，搜索 **Aspose.Imaging** 並安裝。您也可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 將 DNG 轉換為 PNG 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

開發人員只需幾行代碼即可輕鬆加載 DNG 文件並將其轉換為 PNG。

{{% /blocks/products/pf/agp/text %}}

+ 使用 Image.Load 方法加載 DNG 文件
+ 創建和設置 ImageOptionsBase 所需子類的實例（例如 BmpOptions、PngOptions 等）
+ 調用 Image.Save 方法
+ 傳遞帶有 PNG 擴展名的文件路徑和 ImageOptionsBase 類的對象

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

在運行轉換示例代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

+ 作業系統：Windows 或Linux。
+ 開發環境：支援.NET Core 7及更高版本，例如Microsoft Visual Studio。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="將 DNG 轉換為 PNG 的免費應用程序"
        appName="Conversion"
        extension="DNG-to-PNG"
        label1="選擇或拖放 DNG 圖像"
        label2="選擇格式並單擊轉換按鈕"
        label3="點擊下載按鈕下載 PNG 圖像"
        checkFreeAppLabel="查看我們的 [將 DNG 轉換為 PNG 的現場演示]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/zh-hant/conversion/DNG-to-PNG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="將 DNG 轉換為 PNG - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "61a66808ddf0e2e9ba60c4e6e8c576c2" "convert-dng-to-png.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DNG" readMoreLink="https://docs.fileformat.com/image/dng/" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多 | DNG">}}
DNG 是一種用於存儲原始文件的數碼相機圖像格式。它是由 Adob​​e 於 2004 年 9 月開發的。它基本上是為數碼攝影而開發的。 DNG 是 TIFF/EP 標準格式的擴展，大量使用元數據。為了輕鬆靈活地處理來自數碼相機的原始數據和藝術控制，攝影師選擇相機原始文件。 JPEG 和 TIFF 格式存儲由相機處理的圖像，因此在這些格式中沒有太大的更改空間。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多 | PNG">}}
PNG，便攜式網絡圖形，是指一種使用無損壓縮的光柵圖像文件格式。此文件格式是作為圖形交換格式 (GIF) 的替代品而創建的，沒有版權限制。但是，PNG 文件格式不支持動畫。 PNG文件格式支持無損圖像壓縮，使其在用戶中很受歡迎。隨著時間的推移，PNG 已經發展成為最常用的圖像文件格式之一。幾乎所有操作系統都支持打開 PNG 文件。例如，Microsoft Windows 查看器能夠打開 PNG 文件，因為操作系統默認支持作為安裝的一部分。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="使用 C#，可以輕鬆轉換不同的格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-bmp/" name="BMP" description="位圖圖片" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-gif/" name="GIF" description="圖形交換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-dicom/" name="DICOM" description="數碼影像與通訊" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-emf/" name="EMF" description="增強的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-jpg/" name="JPG" description="聯合攝影專家組" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-jpeg/" name="JPEG" description="聯合攝影專家組" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-j2k/" name="J2K" description="小波壓縮圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-png/" name="PNG" description="便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-apng/" name="APNG" description="動畫便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-psd/" name="PSD" description="Photoshop 文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-dxf/" name="DXF" description="圖紙交換格式，或圖紙交換格式，" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-svg/" name="SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-tiff/" name="TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-webp/" name="WEBP" description="光柵網絡圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-wmf/" name="WMF" description="微軟視窗元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-pdf/" name="PDF" description="便攜式文檔格式 (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-html/" name="HTML" description="HTML5 畫布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-emz/" name="EMZ" description="Windows 壓縮增強元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-wmz/" name="WMZ" description="壓縮的 Windows Media Player 皮膚" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-tga/" name="TGA" description="塔加圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-svgz/" name="SVGZ" description="可縮放矢量圖形 (.SVG) 文件的壓縮版本。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-canvas/" name="CANVAS" description="HTML5 畫布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/conversion/dng-to-ico/" name="ICO" description="窗口圖標" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
