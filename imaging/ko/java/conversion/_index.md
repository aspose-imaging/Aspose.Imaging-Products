
---
title: Java 이미지 형식 변환 
weight: 3920
url: /ko/java/conversion/ 
lang: ko
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Java 라이브러리를 통해 인기 있는 이미지, 사진, 그림 파일을 변환합니다. HTML5 Canvas를 포함한 PDF, GIF, PSD, JPG, Dxf, SVG로 변환합니다.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Java를 통한 이미지 파일 변환" h2="이미지 형식, 메타파일, WebP, SVG, APNG를 변환하여 플랫폼 간 Java 애플리케이션을 구축합니다." downloadText="다운로드" >}}

{{% blocks/products/pf/feature-page-summary %}}

모든 고급 이미지 처리 응용 프로그램의 경우 Java Image API를 사용하면 개발자가 이미지 편집기 요구 사항 없이 이미지를 생성, 로드, 조작 또는 렌더링할 수 있습니다. 사진과 그림을 포함한 벡터 및 래스터 이미지를 PSD, PDF, GIF, PNG, DICOM, DXF, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WMF, EMF, WEBP 및 기타 이미지 형식으로 변환할 수 있습니다. API는 이미지를 흑백 및 회색조로 변환하고 열린 문서 그래픽, RGB 컬러 시스템을 CMYK 등으로 변환하는 이진화 및 그레이스케일링 방법을 제공합니다.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="이미지 파일의 상호 변환" %}}

Java Image API를 사용하면 인터 변환이 간단하고 개발자는 **image to jpg**, **image to bmp**, **image to png** 등 어떤 경우에도 몇 줄의 코딩 라인만 작성하면 됩니다. API는 [Image.load](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#load-java.lang.String-) 이미지를 로드합니다. [ImageOptionsBase](https://apireference.aspose.com/imaging/java/com.aspose.imaging/ImageOptionsBase)에서 관련 이미지 옵션을 지정하고 출력 이미지 파일과 옵션을 매개변수로 사용하여 save 메소드를 호출합니다.

{{% blocks/products/pf/feature-page-code h3="이미지 상호 변환을 위한 Java 코드" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "inter-conversion-of-image-files.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/apng-to-bmp/" style="padding:15px;">APNG 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/cdr-to-bmp/" style="padding:15px;">CDR 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/dib-to-bmp/" style="padding:15px;">DIB 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/dicom-to-bmp/" style="padding:15px;">DICOM 에게 BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/djvu-to-bmp/" style="padding:15px;">DJVU 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/dng-to-bmp/" style="padding:15px;">DNG 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/emf-to-bmp/" style="padding:15px;">EMF 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/emz-to-bmp/" style="padding:15px;">EMZ 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/eps-to-bmp/" style="padding:15px;">EPS 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/gif-to-bmp/" style="padding:15px;">GIF 에게 BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="래스터 이미지를 PSD로 변환" %}}

래스터 이미지를 PSD로 변환하는 과정은 API가 특정 항목에 대해 [PsdOptions](https://apireference.aspose.com/imaging/java/com.aspose.imaging.imageoptions/PsdOptions)를 제공한다는 점을 제외하고는 이미지 상호 변환 과정과 동일합니다. PSD 설정. 프로그래머는 특정 요구 사항에 맞게 쉽게 향상시킬 수 있습니다.

{{% blocks/products/pf/feature-page-code h3="래스터 이미지를 PSD로 변환하기 위한 Java 코드" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "raster-images-to-psd-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/apng-to-PSD/" style="padding:15px;">APNG 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/jpeg-to-PSD/" style="padding:15px;">JPEG 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/bmp-to-PSD/" style="padding:15px;">BMP 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/odg-to-PSD/" style="padding:15px;">ODG 에게 PSD</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/otg-to-PSD/" style="padding:15px;">OTG 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/png-to-PSD/" style="padding:15px;">PNG 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/svg-to-PSD/" style="padding:15px;">SVG 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/emz-to-PSD/" style="padding:15px;">EMZ 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/eps-to-PSD/" style="padding:15px;">EPS 에게 PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/gif-to-PSD/" style="padding:15px;">GIF 에게 PSD</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Corel Draw CDR을 이미지로 변환" %}}

CDR의 변환 과정은 거의 동일하며, CDR 파일을 로드하고, 관련 이미지 저장 옵션을 사용하고, Save 메소드를 호출합니다. Image API는 필수 파라미터 설정을 위한 [VectorRasterizationOptions](https://apireference.aspose.com/imaging/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions)를 제공합니다. 그리고 이러한 래스터화 옵션은 설정에 필요한 이미지 옵션을 할당할 수 있습니다. 마지막으로 save 메소드를 호출합니다. 

{{% blocks/products/pf/feature-page-code h3="이미지에 대한 CDR을 위한 Java 코드" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "convert-cdr-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/CDR-to-bmp/" style="padding:15px;">CDR 에게 BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/CDR-to-jpeg/" style="padding:15px;">CDR 에게 JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ko/java/conversion/CDR-to-png/" style="padding:15px;">CDR 에게 PNG</a></p>
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
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/apng/" style="padding:15px;">다음에서 변환 APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/bmp/" style="padding:15px;">다음에서 변환 BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/dib/" style="padding:15px;">다음에서 변환 DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/dicom/" style="padding:15px;">다음에서 변환 DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/djvu/" style="padding:15px;">다음에서 변환 DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/dng/" style="padding:15px;">다음에서 변환 DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/emf/" style="padding:15px;">다음에서 변환 EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/emz/" style="padding:15px;">다음에서 변환 EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/gif/" style="padding:15px;">다음에서 변환 GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/jpeg2000/" style="padding:15px;">다음에서 변환 JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/jp2/" style="padding:15px;">다음에서 변환 JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/j2k/" style="padding:15px;">다음에서 변환 J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/jpg/" style="padding:15px;">다음에서 변환 JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/jpeg/" style="padding:15px;">다음에서 변환 JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/png/" style="padding:15px;">다음에서 변환 PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/tga/" style="padding:15px;">다음에서 변환 TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/tif/" style="padding:15px;">다음에서 변환 TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/tiff/" style="padding:15px;">다음에서 변환 TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/webp/" style="padding:15px;">다음에서 변환 WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/wmf/" style="padding:15px;">다음에서 변환 WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/wmz/" style="padding:15px;">다음에서 변환 WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/svg/" style="padding:15px;">다음에서 변환 SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/svgz/" style="padding:15px;">다음에서 변환 SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/eps/" style="padding:15px;">다음에서 변환 EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/cdr/" style="padding:15px;">다음에서 변환 CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/cmx/" style="padding:15px;">다음에서 변환 CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/otg/" style="padding:15px;">다음에서 변환 OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/odg/" style="padding:15px;">다음에서 변환 ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/ico/" style="padding:15px;">다음에서 변환 ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/from/avif/" style="padding:15px;">다음에서 변환 AVIF</a></div>
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
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/bmp/" style="padding:15px;">로 변환하다 BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/gif/" style="padding:15px;">로 변환하다 GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/dicom/" style="padding:15px;">로 변환하다 DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/emf/" style="padding:15px;">로 변환하다 EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/jpg/" style="padding:15px;">로 변환하다 JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/jpeg/" style="padding:15px;">로 변환하다 JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/jp2/" style="padding:15px;">로 변환하다 JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/j2k/" style="padding:15px;">로 변환하다 J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/jpeg2000/" style="padding:15px;">로 변환하다 JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/png/" style="padding:15px;">로 변환하다 PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/psd/" style="padding:15px;">로 변환하다 PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/dxf/" style="padding:15px;">로 변환하다 DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/svg/" style="padding:15px;">로 변환하다 SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/tiff/" style="padding:15px;">로 변환하다 TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/webp/" style="padding:15px;">로 변환하다 WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/wmf/" style="padding:15px;">로 변환하다 WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/pdf/" style="padding:15px;">로 변환하다 PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/html/" style="padding:15px;">로 변환하다 HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/emz/" style="padding:15px;">로 변환하다 EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/wmz/" style="padding:15px;">로 변환하다 WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/tga/" style="padding:15px;">로 변환하다 TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/svgz/" style="padding:15px;">로 변환하다 SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/canvas/" style="padding:15px;">로 변환하다 CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/ico/" style="padding:15px;">로 변환하다 ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ko/java/conversion/to/apng/" style="padding:15px;">로 변환하다 APNG</a></div>
                </div>
        </div>
    </div>
</div>

