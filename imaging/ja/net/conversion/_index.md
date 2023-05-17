
---
title: C# イメージ形式の変換 
weight: 3920
url: /ja/net/conversion/ 
lang: ja
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: .NET ライブラリを介して一般的な画像、写真、画像形式を変換します。数行の C# コードで HTML5 Canvas を含む PSD、PDF、GIF、JPG、SVG に変換します。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C# による画像ファイルの変換" h2="画像形式、メタファイル、WebP、Svg、Apng を変換して、クロスプラットフォームの .NET ベースの高度な画像処理アプリケーションを構築します。" downloadText="ダウンロード" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API は、プログラマー向けの高度な画像処理およびレンダリング機能を容易にします。開発者はそれを統合して、写真や画像を含むラスターおよびベクター画像を PSD、PDF、GIF、PNG、DICOM、SVG、JPG、JPEG2000、APNG、BMP、TIFF、HTML5 CANVAS、WEBP、WMF、EMF、およびその他の画像形式に変換できます。 . API は、ファイルの変換だけでなく、画像を白黒とグレースケールに変換したり、GIF 画像レイヤーを変換したりします。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="画像をビットマップ BMP、JPG、PNG に変換" %}}

C# Image API を使用すると、必要な形式の拡張子を変更するだけの簡単な Inter 形式変換が可能です。ここでは、**イメージから bmp**、**イメージから jpg**、**イメージから png** などのいくつかの一般的なケースを示します。開発者は、特定の形式に合わせて簡単に拡張できます。プロセスは、[Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load) を介してソース イメージをロードします。特定の設定に対して、ターゲット [画像形式オプション](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) のオブジェクトを作成します。最後に、[保存メソッド](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) を呼び出します。ターゲット ファイルにパスと保存オプションをパラメーターとして渡します。

{{% blocks/products/pf/feature-page-code h3="画像の相互変換用の C# コード" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/apng-to-bmp/" style="padding:15px;">APNG に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/dib-to-bmp/" style="padding:15px;">DIB に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM に BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/dng-to-bmp/" style="padding:15px;">DNG に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/emf-to-bmp/" style="padding:15px;">EMF に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/eps-to-bmp/" style="padding:15px;">EPS に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/gif-to-bmp/" style="padding:15px;">GIF に BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="ラスター画像から PDF への変換" %}}

ラスター イメージを PDF に変換するプロセスは、イメージの相互変換と同じですが、特定の PDF 設定に対して API が [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) を提供する点が異なります。 .プログラマーは、特定のニーズに合わせて簡単に拡張できます。

{{% blocks/products/pf/feature-page-code h3="ラスター イメージから PDF への変換のコード" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/apng-to-PDF/" style="padding:15px;">APNG に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/odg-to-PDF/" style="padding:15px;">ODG に PDF</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/otg-to-PDF/" style="padding:15px;">OTG に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/png-to-PDF/" style="padding:15px;">PNG に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/svg-to-PDF/" style="padding:15px;">SVG に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/eps-to-PDF/" style="padding:15px;">EPS に PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/gif-to-PDF/" style="padding:15px;">GIF に PDF</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="SVG をラスター画像に変換 BMP、PNG、JPG" %}}

SVG の変換プロセスは同じです。SVG ファイルを読み込み、関連する画像保存オプションを使用し、Save メソッドを呼び出します。 Image API は、PageWidth、PageHeight を設定するための [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) を提供し、ラスター イメージは初期化と SvgRasterizationOptions オプションの取得に VectorRasterizationOptions プロパティを使用します。 

{{% blocks/products/pf/feature-page-code h3="SVG からラスター イメージへの C# コード" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG に BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG に JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ja/net/conversion/SVG-to-png/" style="padding:15px;">SVG に PNG</a></p>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="변환을 위해 지원되는 모든 형식" %}}
以下に、変換できる画像形式の完全なリストを示します。
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/apng/" style="padding:15px;">変換元 APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/bmp/" style="padding:15px;">変換元 BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/dib/" style="padding:15px;">変換元 DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/dicom/" style="padding:15px;">変換元 DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/djvu/" style="padding:15px;">変換元 DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/dng/" style="padding:15px;">変換元 DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/emf/" style="padding:15px;">変換元 EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/emz/" style="padding:15px;">変換元 EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/gif/" style="padding:15px;">変換元 GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/jpeg2000/" style="padding:15px;">変換元 JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/jp2/" style="padding:15px;">変換元 JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/j2k/" style="padding:15px;">変換元 J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/jpg/" style="padding:15px;">変換元 JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/jpeg/" style="padding:15px;">変換元 JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/png/" style="padding:15px;">変換元 PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/tga/" style="padding:15px;">変換元 TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/tif/" style="padding:15px;">変換元 TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/tiff/" style="padding:15px;">変換元 TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/webp/" style="padding:15px;">変換元 WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/wmf/" style="padding:15px;">変換元 WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/wmz/" style="padding:15px;">変換元 WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/svg/" style="padding:15px;">変換元 SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/svgz/" style="padding:15px;">変換元 SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/eps/" style="padding:15px;">変換元 EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/cdr/" style="padding:15px;">変換元 CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/cmx/" style="padding:15px;">変換元 CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/otg/" style="padding:15px;">変換元 OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/odg/" style="padding:15px;">変換元 ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/from/ico/" style="padding:15px;">変換元 ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="変換先としてサポートされているすべての画像形式" %}}
以下に、変換可能な画像形式の完全なリストを示します。
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/bmp/" style="padding:15px;">に変換 BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/gif/" style="padding:15px;">に変換 GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/dicom/" style="padding:15px;">に変換 DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/emf/" style="padding:15px;">に変換 EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/jpg/" style="padding:15px;">に変換 JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/jpeg/" style="padding:15px;">に変換 JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/jp2/" style="padding:15px;">に変換 JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/j2k/" style="padding:15px;">に変換 J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/jpeg2000/" style="padding:15px;">に変換 JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/png/" style="padding:15px;">に変換 PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/psd/" style="padding:15px;">に変換 PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/dxf/" style="padding:15px;">に変換 DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/svg/" style="padding:15px;">に変換 SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/tiff/" style="padding:15px;">に変換 TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/webp/" style="padding:15px;">に変換 WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/wmf/" style="padding:15px;">に変換 WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/pdf/" style="padding:15px;">に変換 PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/html/" style="padding:15px;">に変換 HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/emz/" style="padding:15px;">に変換 EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/wmz/" style="padding:15px;">に変換 WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/tga/" style="padding:15px;">に変換 TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/svgz/" style="padding:15px;">に変換 SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/canvas/" style="padding:15px;">に変換 CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/ico/" style="padding:15px;">に変換 ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ja/net/conversion/to/apng/" style="padding:15px;">に変換 APNG</a></div>
                </div>
        </div>
    </div>
</div>

