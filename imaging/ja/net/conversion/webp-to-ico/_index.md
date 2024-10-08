﻿---
title: C#を介してWEBPをICOに変換します 
weight: 3920
url: /ja/net/conversion/webp-to-ico/ 
lang: ja
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: WEBPからICOへのC＃変換のサンプルコード。 VB.NET、Asp.NET、または任意の.NETベースのアプリケーション内でのバッチWEBPファイルからICOへの変換にAPIサンプルコードを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#を介してWEBPをICOに変換します" h2="画像エディタやサードパーティのライブラリを必要とせずに、ネイティブの.NET APIを使用してWEBPをICOに変換します。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ICO" pfName="Aspose.Imaging" subTitlepfName=".NET 用" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET 用" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ja/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ja/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="APIホーム" codeSamplesText="コードサンプル" liveDemosText="ライブデモ" downloadText="ダウンロード" learnText="学び" overviewText="概要" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してWEBPをICOに変換する方法" %}}

ファイル形式の変換は、グラフィック デザイナーにとって日常的な作業のように思えるかもしれません。しかし、その重要性を過小評価するのは間違いです。あなたの仕事の評価は、このタスクにどれだけ迅速かつ効果的に取り組むかによって決まるかもしれません。通常、元の画像は、印刷またはオンライン公開に適した形式に変換する必要があります。元の画像がグラフィック エディターから作成された場合は、ベクター形式である可能性があります。このシナリオでは、公開のためにラスター化してラスター形式に変換する必要があります。最適な品質を得るために画像を非圧縮形式で保存するか、ファイル サイズを削減するために可逆圧縮形式に変換するかを選択できます。 Web パブリッシングなどの特定の状況では、非可逆圧縮形式を選択できます。画像データ圧縮用に特別に設計されたアルゴリズムにより、許容可能な画質を維持しながらファイル サイズを大幅に削減できます。これにより、インターネットからの画像ファイルの高速ダウンロードが容易になります。 WEBP を ICO に変換するには、次を使用します。 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) 機能が豊富で強力で使いやすいC＃プラットフォーム用の画像操作および変換APIであるAPI。開ける [NuGet](https://www.nuget.org/packages/aspose.imaging) パッケージマネージャー、検索 ** Aspose.Imaging ** とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title ="パッケージマネージャーコンソールコマンド" offSpacer = "true"%}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#を介してWEBPをICOに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

開発者は、わずか数行のコードでWEBPファイルを簡単にロードしてICOに変換できます。

{{% /blocks/products/pf/agp/text %}}

+ Image.Loadメソッドを使用してWEBPファイルをロードします
+ ImageOptionsBaseの必要なサブクラスのインスタンスを作成および設定します（例：BmpOptions、PngOptionsなど）
+ Image.Saveメソッドを呼び出します
+ ICO拡張子とImageOptionsBaseクラスのオブジェクトを含むファイルパスを渡します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

+ オペレーティング システム: Windows または Linux。
+ 開発環境: Microsoft Visual Studio などの .NET Core 7 以降をサポートします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="WEBPをICOに変換する無料アプリ"
        appName="Conversion"
        extension="WEBP-to-ICO"
        label1="WEBP画像を選択またはドラッグアンドドロップします"
        label2="フォーマットを選択し、[変換]ボタンをクリックします"
        label3="ダウンロードボタンをクリックして、ICO画像をダウンロードします"
        checkFreeAppLabel="を確認してください [WEBPをICOに変換するライブデモ]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/ja/conversion/WEBP-to-ICO)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="WEBPをICOに変換します-.NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "693590fa27d4fe2d795cc7fbcf5cbd64" "convert-webp-to-ico.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="WEBP" readMoreLink="https://docs.fileformat.com/image/webp/" whatIsFormat1="とは" whatIsFormat2="ファイル形式" readMoreFormat="続きを読む | WEBP">}}
Googleによって導入されたWebPは、可逆および非可逆圧縮に基づく最新のラスターWeb画像ファイル形式です。画像サイズを大幅に縮小しながら、同じ画質を提供します。ほとんどのWebページはデータの効果的な表現として画像を使用するため、WebページでWebP画像を使用すると、Webページの読み込みが速くなります。 Googleによると、WebPの損失のない画像はPNGと比較してサイズが26％小さく、WebPの損失のある画像は同等のJPEG画像よりも25〜34％小さくなっています。画像は、WebPと他の画像ファイル形式の間の構造的類似性（SSIM）インデックスに基づいて比較されます。 WebPは、WebMマルチメディアコンテナ形式の姉妹プロジェクトです。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ICO" readMoreLink="https://docs.fileformat.com/image/ico/" whatIsFormat1="とは" whatIsFormat2="ファイル形式" readMoreFormat="続きを読む | ICO">}}
ICO ファイル形式は、Microsoft Windows のコンピューター アイコンのイメージ ファイル形式です。 ICO ファイルには、適切にスケーリングできるように、複数のサイズと色深度の 1 つまたは複数の小さな画像が含まれています。 Windows では、ユーザー、デスクトップ、スタート メニュー、または Windows エクスプローラーにアイコンを表示するすべての実行可能ファイルは、アイコンを ICO 形式で保持する必要があります。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="C#を使用すると、を含むさまざまな形式を簡単に変換できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-bmp/" name="BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-gif/" name="GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-dicom/" name="DICOM" description="デジタルイメージング＆コミュニケーション" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-emf/" name="EMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-jpg/" name="JPG" description="共同写真専門家グループ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-jpeg/" name="JPEG" description="共同写真専門家グループ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-j2k/" name="J2K" description="ウェーブレット圧縮画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-png/" name="PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-apng/" name="APNG" description="アニメーション化されたポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-psd/" name="PSD" description="Photoshopドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-dxf/" name="DXF" description="図面交換フォーマット、または図面交換フォーマット、" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-svg/" name="SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-tiff/" name="TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-wmf/" name="WMF" description="MicrosoftWindowsメタファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-pdf/" name="PDF" description="ポータブルドキュメントフォーマット（PDF）" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-html/" name="HTML" description="HTML5キャンバス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-emz/" name="EMZ" description="Windows圧縮拡張メタファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-wmz/" name="WMZ" description="圧縮されたWindowsMediaPlayerスキン" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-tga/" name="TGA" description="タルガグラフィック" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-svgz/" name="SVGZ" description="スケーラブルベクターグラフィックス（.SVG）ファイルの圧縮バージョン。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-canvas/" name="CANVAS" description="HTML5キャンバス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/webp-to-ico/" name="ICO" description="Windows アイコン" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
