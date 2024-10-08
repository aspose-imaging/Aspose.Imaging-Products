﻿---
title: C#を介してDJVUをSVGに変換します 
weight: 3920
url: /ja/net/conversion/djvu-to-svg/ 
lang: ja
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: DJVUからSVGへのC＃変換のサンプルコード。 VB.NET、Asp.NET、または任意の.NETベースのアプリケーション内でのバッチDJVUファイルからSVGへの変換にAPIサンプルコードを使用します。
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#を介してDJVUをSVGに変換します" h2="画像エディタやサードパーティのライブラリを必要とせずに、ネイティブの.NET APIを使用してDJVUをSVGに変換します。" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName=".NET 用" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET 用" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ja/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ja/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="APIホーム" codeSamplesText="コードサンプル" liveDemosText="ライブデモ" downloadText="ダウンロード" learnText="学び" overviewText="概要" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してDJVUをSVGに変換する方法" %}}

ファイル形式の変換は、グラフィック デザイナーにとって日常的な作業のように思えるかもしれません。しかし、その重要性を過小評価するのは間違いです。あなたの仕事の評価は、このタスクにどれだけ迅速かつ効果的に取り組むかによって決まるかもしれません。通常、元の画像は、印刷またはオンライン公開に適した形式に変換する必要があります。元の画像がグラフィック エディターから作成された場合は、ベクター形式である可能性があります。このシナリオでは、公開のためにラスター化してラスター形式に変換する必要があります。最適な品質を得るために画像を非圧縮形式で保存するか、ファイル サイズを削減するために可逆圧縮形式に変換するかを選択できます。 Web パブリッシングなどの特定の状況では、非可逆圧縮形式を選択できます。画像データ圧縮用に特別に設計されたアルゴリズムにより、許容可能な画質を維持しながらファイル サイズを大幅に削減できます。これにより、インターネットからの画像ファイルの高速ダウンロードが容易になります。 DJVU を SVG に変換するには、次を使用します。 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) 機能が豊富で強力で使いやすいC＃プラットフォーム用の画像操作および変換APIであるAPI。開ける [NuGet](https://www.nuget.org/packages/aspose.imaging) パッケージマネージャー、検索 ** Aspose.Imaging ** とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title ="パッケージマネージャーコンソールコマンド" offSpacer = "true"%}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#を介してDJVUをSVGに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

開発者は、わずか数行のコードでDJVUファイルを簡単にロードしてSVGに変換できます。

{{% /blocks/products/pf/agp/text %}}

+ Image.Loadメソッドを使用してDJVUファイルをロードします
+ ImageOptionsBaseの必要なサブクラスのインスタンスを作成および設定します（例：BmpOptions、PngOptionsなど）
+ Image.Saveメソッドを呼び出します
+ SVG拡張子とImageOptionsBaseクラスのオブジェクトを含むファイルパスを渡します

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

変換サンプルコードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

+ オペレーティング システム: Windows または Linux。
+ 開発環境: Microsoft Visual Studio などの .NET Core 7 以降をサポートします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="DJVUをSVGに変換する無料アプリ"
        appName="Conversion"
        extension="DJVU-to-SVG"
        label1="DJVU画像を選択またはドラッグアンドドロップします"
        label2="フォーマットを選択し、[変換]ボタンをクリックします"
        label3="ダウンロードボタンをクリックして、SVG画像をダウンロードします"
        checkFreeAppLabel="を確認してください [DJVUをSVGに変換するライブデモ]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/ja/conversion/DJVU-to-SVG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="DJVUをSVGに変換します-.NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "7cd7d94813fb73fe141054272437f6ae" "convert-djvu-to-svg.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DJVU" readMoreLink="https://docs.fileformat.com/image/djvu/" whatIsFormat1="とは" whatIsFormat2="ファイル形式" readMoreFormat="続きを読む | DJVU">}}
DJVU と発音されるDjVuは、スキャンされたドキュメントや書籍、特にテキスト、図面、画像、写真の組み合わせを含むものを対象としたグラフィックファイル形式です。 AT＆T研究所によって開発されました。テキストと背景画像の画像レイヤー分離、プログレッシブローディング、算術符号化、非可逆圧縮などの複数の手法を使用します。 DJVUファイルには、圧縮された高品質のカラー画像、写真、テキスト、および図面を含めることができ、より少ないスペースで保存できるため、電子書籍、マニュアル、新聞、古代の文書などとしてWebで使用されます。
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="とは" whatIsFormat2="ファイル形式" readMoreFormat="続きを読む | SVG">}}
SVGファイルは、画像の外観を記述するためにXMLベースのテキスト形式を使用するScalable VectorGraphicsファイルです。スケーラブルという言葉は、SVGが品質を損なうことなくさまざまなサイズにスケーリングできるという事実を指します。このようなファイルのテキストベースの説明により、解像度に依存しなくなります。これは、スケーラビリティを実現するためにWebサイトや印刷グラフィックを構築するために最もよく使用される形式の1つです。ただし、この形式は2次元グラフィックスにのみ使用できます。 SVGファイルは、Chrome、Internet Explorer、Firefox、Safariを含むほとんどすべての最新のブラウザーで表示/開くことができます。
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="C#を使用すると、を含むさまざまな形式を簡単に変換できます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-bmp/" name="BMP" description="ビットマップ画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-gif/" name="GIF" description="グラフィカルな交換形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-dicom/" name="DICOM" description="デジタルイメージング＆コミュニケーション" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-emf/" name="EMF" description="強化されたメタファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-jpg/" name="JPG" description="共同写真専門家グループ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-jpeg/" name="JPEG" description="共同写真専門家グループ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-j2k/" name="J2K" description="ウェーブレット圧縮画像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-png/" name="PNG" description="ポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-apng/" name="APNG" description="アニメーション化されたポータブルネットワークグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-psd/" name="PSD" description="Photoshopドキュメント" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-dxf/" name="DXF" description="図面交換フォーマット、または図面交換フォーマット、" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-svg/" name="SVG" description="スケーラブルベクターグラフィックス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-tiff/" name="TIFF" description="タグ付き画像形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-webp/" name="WEBP" description="ラスターWebイメージ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-wmf/" name="WMF" description="MicrosoftWindowsメタファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-pdf/" name="PDF" description="ポータブルドキュメントフォーマット（PDF）" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-html/" name="HTML" description="HTML5キャンバス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-emz/" name="EMZ" description="Windows圧縮拡張メタファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-wmz/" name="WMZ" description="圧縮されたWindowsMediaPlayerスキン" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-tga/" name="TGA" description="タルガグラフィック" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-svgz/" name="SVGZ" description="スケーラブルベクターグラフィックス（.SVG）ファイルの圧縮バージョン。" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-canvas/" name="CANVAS" description="HTML5キャンバス" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ja/net/conversion/djvu-to-ico/" name="ICO" description="Windows アイコン" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
