﻿---
title: 通過 Java 將 EMF 轉換為 DICOM 
weight: 3920
url: /zh-hant/java/conversion/emf-to-dicom/ 
lang: zh-hant
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: EMF 到 DICOM Java 轉換的示例代碼。使用 API 示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 EMF 文件批量轉換為 DICOM。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="通過 Java 將 EMF 轉換為 DICOM" h2="使用原生 Java API 將 EMF 轉換為 DICOM，無需任何圖像編輯器或第 3 方庫。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DICOM" pfName="Aspose.Imaging" subTitlepfName="Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/zh-hant/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/zh-hant/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API首頁" codeSamplesText="代碼示例" liveDemosText="現場演示" downloadText="下載" learnText="學習" overviewText="概述" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 EMF 轉換為 DICOM" %}}

轉換文件格式似乎是圖形設計師遇到的例行任務。然而，低估其重要性將是一個錯誤。對您工作的評估可能取決於您處理這項任務的速度和效率。通常，原始圖像需要轉換為更適合打印或在線出版的格式。如果原始圖像來自圖形編輯器，則它可能是矢量格式。在這種情況下，必須對其進行柵格化並轉換為柵格格式以用於發布目的。您可以選擇以未壓縮格式保存圖像以獲得最佳質量，或將其轉換為無損壓縮格式以減小文件大小。在某些情況下，例如網絡發布，您可以選擇有損壓縮格式。專門設計的圖像數據壓縮算法可以顯著減小文件大小，同時保持可接受的圖像質量。這有利於從互聯網上快速下載圖像文件。為了將 EMF 轉換為 DICOM，我們將使用 [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API 是一個功能豐富、功能強大 易於使用的 Java 平台圖像處理和轉換 API。您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 EMF 轉換為 DICOM 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

開發人員只需幾行代碼即可輕鬆加載 EMF 文件並將其轉換為 DICOM。

{{% /blocks/products/pf/agp/text %}}

+ 使用 Image.load 方法加載 EMF 文件
+ 創建和設置 ImageOptionsBase 所需子類的實例（例如 BmpOptions、PngOptions 等）
+ 調用 Image.save 方法
+ 傳遞帶有 DICOM 擴展名的文件路徑和 ImageOptionsBase 類的對象

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

在運行轉換示例代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

+ 作業系統：Windows 或Linux。
+ 開發環境：支援.NET Core 7及更高版本，例如Microsoft Visual Studio。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="將 EMF 轉換為 DICOM 的免費應用程序"
        appName="Conversion"
        extension="EMF-to-DICOM"
        label1="選擇或拖放 EMF 圖像"
        label2="選擇格式並單擊轉換按鈕"
        label3="點擊下載按鈕下載 DICOM 圖像"
        checkFreeAppLabel="查看我們的 [將 EMF 轉換為 DICOM 的現場演示]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/zh-hant/conversion/EMF-to-DICOM)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="將 EMF 轉換為 DICOM - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多 | EMF">}}
增強型元文件格式 (EMF) 獨立於設備存儲圖形圖像。 EMF 的元文件由按時間順序排列的可變長度記錄組成，可以在任何輸出設備上解析後呈現存儲的圖像。這些可變長度記錄可以是封閉對象的定義、繪圖命令和對準確渲染圖像至關重要的圖形屬性。當設備使用自己的圖形環境打開 EMF 圖元文件時，無論打開設備平台如何，原始圖像的比例、尺寸、顏色和其他圖形屬性都保持不變。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="什麼是" whatIsFormat2="文件格式" readMoreFormat="閱讀更多 | DICOM">}}
DICOM 是 Digital Imaging and Communications in Medicine 的首字母縮寫詞，屬於醫學信息學領域。 DICOM 是文件格式定義和網絡通信協議的結合。 DICOM 使用 .DCM 擴展名。 .DCM 以兩種不同的格式存在，即格式 1.x 和格式 2.x。 DCM Format 1.x 還提供兩個普通版本和擴展版本。 DICOM 用於集成來自不同供應商的打印機、服務器、掃描儀等醫療成像設備，還包含每個患者的唯一識別數據。如果 DICOM 文件能夠接收 DICOM 格式的圖像數據，則它們可以在兩方之間共享。 DICOM的通信部分是應用層協議，實體之間使用TCP/IP進行通信。 HTTP 和 HTTPS 協議用於 DICOM 的 Web 服務。 Web 服務支持的版本是 1.0、1.1、2 或更高版本。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="使用 Java，可以輕鬆轉換不同的格式，包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-bmp/" name="BMP" description="位圖圖片" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-gif/" name="GIF" description="圖形交換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-dicom/" name="DICOM" description="數碼影像與通訊" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-jpg/" name="JPG" description="聯合攝影專家組" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-jpeg/" name="JPEG" description="聯合攝影專家組" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-j2k/" name="J2K" description="小波壓縮圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-png/" name="PNG" description="便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-apng/" name="APNG" description="動畫便攜式網絡圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-psd/" name="PSD" description="Photoshop 文檔" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-dxf/" name="DXF" description="圖紙交換格式，或圖紙交換格式，" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-svg/" name="SVG" description="可縮放矢量圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-tiff/" name="TIFF" description="標記圖像格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-webp/" name="WEBP" description="光柵網絡圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-wmf/" name="WMF" description="微軟視窗元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-pdf/" name="PDF" description="便攜式文檔格式 (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-html/" name="HTML" description="HTML5 畫布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-emz/" name="EMZ" description="Windows 壓縮增強元文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-wmz/" name="WMZ" description="壓縮的 Windows Media Player 皮膚" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-tga/" name="TGA" description="塔加圖形" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-svgz/" name="SVGZ" description="可縮放矢量圖形 (.SVG) 文件的壓縮版本。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-canvas/" name="CANVAS" description="HTML5 畫布" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/zh-hant/java/conversion/emf-to-ico/" name="ICO" description="窗口圖標" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
