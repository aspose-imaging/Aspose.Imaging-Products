﻿---
title: 通過 .NET 刪除 CMX 文檔中的背景 
weight: 3920
url: /zh-hant/net/remove-background/cmx/ 
lang: zh-hant
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: 嘗試使用我們的本地文檔 API 來刪除 .NET Framework、.NET Core、Windows 應用程序、ASP.NET Web 應用程序上 CMX 文件中的背景。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通過 C# 從 CMX 中刪除背景" h2="構建您自己的 .NET 應用程序以使用服務器端 API 從 CMX 文件中刪除背景。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="CMX" pfName="Aspose.Imaging" subTitlepfName=".NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/zh-hant/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API 主頁" codeSamplesText="代碼示例" liveDemosText="現場演示" downloadText="下載" learnText="學習">}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 刪除 CMX 文件中的背景" %}}

從圖像中去除背景涉及隔離前景對象，這是一項需要對象識別的任務。存在多種方法來識別 CMX 格式照片中的對象。對於具有統一顏色背景的簡單圖像，自動方法就足夠了。然而，對於具有多個或部分合併人物的照片，預先標記對象就變得必要。這涉及指定要刪除的矩形區域和對像類型。在復雜的情況下，Cloud API 可以實現自動對象檢測。 Cloud API 提供了一個雲應用程序，能夠識別照片中的對象，利用生成的輪廓來去除背景。去除後，可以平滑圖形留下的邊緣以提高圖像質量。為了刪除 CMX 文件中的背景，我們將使用 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API 是一個功能豐富、功能強大且易於使用的 C# 平台圖像處理和轉換 API。打開 [NuGet](https://www.nuget.org/packages/aspose.imaging) 包管理器，搜索 **Aspose.Imaging** 並安裝。您也可以從包管理器控制台使用以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 從 CMX 中刪除背景的步驟" %}}

{{% blocks/products/pf/agp/text %}}

你需要 [aspose.imaging.dll](https://downloads.aspose.com/imaging/net) 在您自己的環境中嘗試以下工作流程。

{{% /blocks/products/pf/agp/text %}}

+ 使用 Image.Load 方法加載 CMX 文件
+ 移除背景；
+ 以 Aspose.Imaging 支持的格式將圖像保存到光盤

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

所有主要操作系統都支持 .NET 的 Aspose.Imaging。只需確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或與 .NET Framework、.NET Core、Windows 應用程序、ASP.NET Web 應用程序兼容的操作系統。
- Microsoft Visual Studio 等開發環境。
- Aspose.Imaging for .NET 在您的項目中引用。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="刪除 CMX 圖像中的背景 - .NET" offSpacer="" %}}

{{< gist "aspose-com-gists" "c28d7d7f7dff39444751b5724d5ba14a" "remove-change-background-generic-examples.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 .NET API 的 Aspose.Imaging" %}}


Aspose.Imaging API 是一種圖像處理解決方案，用於在應用程序中創建、修改、繪製或轉換圖像（照片）。它提供：跨平台的圖像處理，包括但不限於各種圖像格式之間的轉換（包括統一的多頁或多幀圖像處理）、繪圖等修改、使用圖形基元、轉換（調整大小、裁剪、翻轉和旋轉） 、二值化、灰度、調整）、高級圖像處理功能（過濾、抖動、遮罩、去偏斜）和內存優化策略。它是一個獨立的庫，不依賴任何軟件進行圖像操作。可以在項目中使用原生 API 輕鬆添加高性能圖像轉換功能。這些是 100% 私有的本地 API，圖像在您的服務器上處理。


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="通過在線應用刪除 CMX 中的背景" sectionDescription="通過訪問我們的 [Live Demos 網站](https://products.aspose.app/imaging/remove-background) 移除 CMX 文檔中的背景。 現場演示有以下好處" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="無需下載或設置任何東西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="無需編寫任何代碼" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="只需上傳您的 CMX 文件並點擊“立即刪除背景”按鈕" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="立即獲取生成文件的下載鏈接" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="CMX" readMoreLink="https://docs.fileformat.com/image/cmx/" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多" >}}
帶有 CMX 擴展名的文件是 Corel Exchange 圖像文件格式，CorelSuite 應用程序用作演示文稿。它包含作為矢量圖形的圖像數據以及描述圖像的元數據。 CMX 文件可由 CorelDraw、Corel Presentations、Paint Shop Pro 和某些版本的 Adob​​e Illustrator 打開。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的刪除背景格式" subTitle="使用 C#，可以輕鬆地從不同格式中刪除背景，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/apng/" name="APNG" description="動畫便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/bmp/" name="BMP" description="位圖圖片" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/ico/" name="ICO" description="窗口圖標" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/jpg/" name="JPG" description="聯合攝影專家組" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/dib/" name="DIB" description="設備無關位圖" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/dicom/" name="DICOM" description="數碼影像與通訊" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/djvu/" name="DJVU" description="圖形格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/dng/" name="DNG" description="數碼相機圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/emf/" name="EMF" description="增強的元文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/emz/" name="EMZ" description="Windows 壓縮增強元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/gif/" name="GIF" description="圖形交換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/j2k/" name="J2K" description="小波壓縮圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/png/" name="PNG" description="便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/tiff/" name="TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/webp/" name="WEBP" description="光柵網絡圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/wmf/" name="WMF" description="微軟視窗元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/wmz/" name="WMZ" description="壓縮的 Windows Media Player 皮膚" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/tga/" name="TGA" description="塔加圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/svg/" name="SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/eps/" name="EPS" description="封裝的 PostScript 語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/cdr/" name="CDR" description="矢量繪圖圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/otg/" name="OTG" description="開放文檔標準" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/odg/" name="ODG" description="Apache OpenOffice 繪圖格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/net/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
