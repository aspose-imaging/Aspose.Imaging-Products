
---
title: C# 이미지 형식 변환 
weight: 3920
url: /ko/net/conversion/ 
lang: ko
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: .NET 라이브러리를 통해 인기 있는 이미지, 사진, 그림 형식을 변환합니다. 몇 줄의 C# 코드로 HTML5 Canvas를 포함한 PSD, PDF, GIF, JPG, SVG로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C#을 통한 이미지 파일 변환" h2="이미지 형식, 메타파일, WebP, Svg, Apng를 변환하여 플랫폼 간 .NET 기반 고급 이미지 처리 응용 프로그램을 구축합니다." downloadText="다운로드" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API는 프로그래머를 위한 고급 이미지 처리 및 렌더링 기능을 용이하게 합니다. 개발자는 이를 통합하여 사진과 그림을 포함한 래스터 및 벡터 이미지를 PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF 및 기타 이미지 형식으로 변환할 수 있습니다. . API는 파일 변환을 처리할 뿐만 아니라 이미지를 흑백 및 회색조로 변환하고 GIF 이미지 레이어를 변환하는 등의 작업을 처리합니다.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="이미지를 비트맵 BMP, JPG, PNG로 변환" %}}

C# Image API를 사용하면 원하는 형식의 확장자를 변경하는 것만으로 Inter 형식 변환이 쉽습니다. 다음은 **image to bmp**, **image to jpg**, **image to png**와 같은 몇 가지 일반적인 경우이며 개발자는 특정 형식에 맞게 쉽게 향상할 수 있습니다. [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load)를 통해 소스 이미지를 로드하는 과정입니다. 특정 설정에 대한 대상 [이미지 형식 옵션](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions)의 개체를 만듭니다. 마지막으로 경로 및 저장 옵션을 매개변수로 대상 파일을 전달하여 [저장 방법](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)을 호출합니다.

{{% blocks/products/pf/feature-page-code h3="이미지의 상호 변환을 위한 C# 코드" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/apng-to-bmp/" style="padding:15px;">APNG 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/dib-to-bmp/" style="padding:15px;">DIB 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM 에게 BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/dng-to-bmp/" style="padding:15px;">DNG 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/emf-to-bmp/" style="padding:15px;">EMF 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/eps-to-bmp/" style="padding:15px;">EPS 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/gif-to-bmp/" style="padding:15px;">GIF 에게 BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="래스터 이미지를 PDF로 변환" %}}

래스터 이미지를 PDF로 변환하는 프로세스는 API가 특정 PDF 설정에 대해 [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions)를 제공한다는 점을 제외하고 이미지 상호 변환과 동일합니다. . 프로그래머는 특정 요구 사항에 맞게 쉽게 향상시킬 수 있습니다.

{{% blocks/products/pf/feature-page-code h3="래스터 이미지를 PDF로 변환하는 코드" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/apng-to-PDF/" style="padding:15px;">APNG 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/odg-to-PDF/" style="padding:15px;">ODG 에게 PDF</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/otg-to-PDF/" style="padding:15px;">OTG 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/png-to-PDF/" style="padding:15px;">PNG 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/svg-to-PDF/" style="padding:15px;">SVG 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/eps-to-PDF/" style="padding:15px;">EPS 에게 PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/gif-to-PDF/" style="padding:15px;">GIF 에게 PDF</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="SVG를 래스터 이미지 BMP, PNG, JPG로 변환" %}}

SVG의 변환 과정은 동일하며 SVG 파일을 로드하고 관련 이미지 저장 옵션을 사용하고 Save 메소드를 호출합니다. Image API는 PageWidth, PageHeight 및 래스터 이미지를 설정하기 위해 [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions)를 제공하며, 래스터 이미지는 초기화 및 SvgRasterizationOptions 옵션 가져오기를 위해 VectorRasterizationOptions 속성을 사용합니다. 

{{% blocks/products/pf/feature-page-code h3="SVG를 래스터 이미지로 변환하는 C# 코드" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG 에게 JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/net/conversion/SVG-to-png/" style="padding:15px;">SVG 에게 PNG</a></p>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="변환할 이미지 지원되는 모든 형식" %}}
다음은 변환할 수 있는 이미지 형식의 전체 목록입니다.
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/apng/" style="padding:15px;">다음에서 변환 APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/bmp/" style="padding:15px;">다음에서 변환 BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/dib/" style="padding:15px;">다음에서 변환 DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/dicom/" style="padding:15px;">다음에서 변환 DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/djvu/" style="padding:15px;">다음에서 변환 DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/dng/" style="padding:15px;">다음에서 변환 DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/emf/" style="padding:15px;">다음에서 변환 EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/emz/" style="padding:15px;">다음에서 변환 EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/gif/" style="padding:15px;">다음에서 변환 GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/jpeg2000/" style="padding:15px;">다음에서 변환 JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/jp2/" style="padding:15px;">다음에서 변환 JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/j2k/" style="padding:15px;">다음에서 변환 J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/jpg/" style="padding:15px;">다음에서 변환 JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/jpeg/" style="padding:15px;">다음에서 변환 JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/png/" style="padding:15px;">다음에서 변환 PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/tga/" style="padding:15px;">다음에서 변환 TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/tif/" style="padding:15px;">다음에서 변환 TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/tiff/" style="padding:15px;">다음에서 변환 TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/webp/" style="padding:15px;">다음에서 변환 WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/wmf/" style="padding:15px;">다음에서 변환 WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/wmz/" style="padding:15px;">다음에서 변환 WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/svg/" style="padding:15px;">다음에서 변환 SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/svgz/" style="padding:15px;">다음에서 변환 SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/eps/" style="padding:15px;">다음에서 변환 EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/cdr/" style="padding:15px;">다음에서 변환 CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/cmx/" style="padding:15px;">다음에서 변환 CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/otg/" style="padding:15px;">다음에서 변환 OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/odg/" style="padding:15px;">다음에서 변환 ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/from/ico/" style="padding:15px;">다음에서 변환 ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="변환할 지원되는 모든 이미지 형식" %}}
다음은 변환할 수 있는 이미지 형식의 전체 목록입니다.
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/bmp/" style="padding:15px;">로 변환하다 BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/gif/" style="padding:15px;">로 변환하다 GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/dicom/" style="padding:15px;">로 변환하다 DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/emf/" style="padding:15px;">로 변환하다 EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/jpg/" style="padding:15px;">로 변환하다 JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/jpeg/" style="padding:15px;">로 변환하다 JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/jp2/" style="padding:15px;">로 변환하다 JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/j2k/" style="padding:15px;">로 변환하다 J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/jpeg2000/" style="padding:15px;">로 변환하다 JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/png/" style="padding:15px;">로 변환하다 PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/psd/" style="padding:15px;">로 변환하다 PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/dxf/" style="padding:15px;">로 변환하다 DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/svg/" style="padding:15px;">로 변환하다 SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/tiff/" style="padding:15px;">로 변환하다 TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/webp/" style="padding:15px;">로 변환하다 WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/wmf/" style="padding:15px;">로 변환하다 WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/pdf/" style="padding:15px;">로 변환하다 PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/html/" style="padding:15px;">로 변환하다 HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/emz/" style="padding:15px;">로 변환하다 EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/wmz/" style="padding:15px;">로 변환하다 WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/tga/" style="padding:15px;">로 변환하다 TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/svgz/" style="padding:15px;">로 변환하다 SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/canvas/" style="padding:15px;">로 변환하다 CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/ico/" style="padding:15px;">로 변환하다 ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/net/conversion/to/apng/" style="padding:15px;">로 변환하다 APNG</a></div>
                </div>
        </div>
    </div>
</div>

