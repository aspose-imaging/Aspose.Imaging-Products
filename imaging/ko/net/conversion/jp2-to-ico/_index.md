﻿---
title: C#를 통해 JP2을 ICO로 변환 
weight: 3920
url: /ko/net/conversion/jp2-to-ico/ 
lang: ko
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: JP2에서 ICO로의 C# 변환을 위한 샘플 코드입니다. VB.NET, Asp.NET 또는 모든 .NET 기반 응용 프로그램 내에서 일괄 JP2 파일을 ICO로 변환하는 API 예제 코드를 사용합니다.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#를 통해 JP2을 ICO로 변환" h2="이미지 편집기나 타사 라이브러리 없이 기본 .NET API를 사용하여 JP2을 ICO로 변환합니다." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ICO" pfName="Aspose.Imaging" subTitlepfName=".NET용" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ko/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ko/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다" overviewText="개요" >}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 JP2을 ICO로 변환하는 방법" %}}

파일 형식 변환은 그래픽 디자이너가 겪는 일상적인 작업처럼 보일 수 있습니다. 하지만 그 중요성을 과소평가하는 것은 실수입니다. 귀하의 작업에 대한 평가는 이 작업을 얼마나 신속하고 효과적으로 처리하는지에 따라 달라질 수 있습니다. 일반적으로 원본 이미지는 인쇄나 온라인 출판에 더 적합한 형식으로 변환해야 합니다. 원본 이미지가 그래픽 편집기에서 가져온 경우 벡터 형식일 수 있습니다. 이 시나리오에서는 게시 목적으로 래스터화하고 래스터 형식으로 변환해야 합니다. 최적의 품질을 위해 이미지를 압축되지 않은 형식으로 저장하거나 파일 크기를 줄이기 위해 무손실 압축 형식으로 변환할 수 있습니다. 웹 게시와 같은 특정 상황에서는 손실이 있는 압축 형식을 선택할 수 있습니다. 이미지 데이터 압축을 위해 특별히 설계된 알고리즘을 사용하면 허용 가능한 이미지 품질을 유지하면서 파일 크기를 크게 줄일 수 있습니다. 이를 통해 인터넷에서 이미지 파일을 빠르게 다운로드할 수 있습니다. JP2을 ICO로 변환하기 위해 다음을 사용합니다. [.NET용 Aspose.Imaging](https://products.aspose.com/imaging/net) 기능이 풍부하고 강력하며 사용하기 쉬운 C# 플랫폼용 이미지 조작 및 변환 API인 API입니다. 열려있는 [누겟](https://www.nuget.org/packages/aspose.imaging) 패키지 관리자, 검색 **아포즈.이미징** 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}



```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 JP2을 ICO로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

개발자는 몇 줄의 코드로 JP2 파일을 ICO로 쉽게 로드하고 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ Image.Load 메소드로 JP2 파일 로드
+ ImageOptionsBase의 필수 하위 클래스(예: BmpOptions, PngOptions 등)의 인스턴스 생성 및 설정
+ Image.Save 메서드 호출
+ ImageOptionsBase 클래스의 ICO 확장명 및 개체로 파일 경로 전달

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

변환 예제 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

+ 운영 체제: Windows 또는 Linux.
+ 개발 환경: Microsoft Visual Studio 등 .NET Core 7 이상을 지원합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="JP2을 ICO로 변환하는 무료 앱"
        appName="Conversion"
        extension="JP2-to-ICO"
        label1="JP2 이미지 선택 또는 드래그 앤 드롭"
        label2="형식을 선택하고 변환 버튼을 클릭하십시오"
        label3="다운로드 버튼을 클릭하여 ICO 이미지를 다운로드합니다."
        checkFreeAppLabel="를 확인하세요 [JP2을 ICO로 변환하는 라이브 데모]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/ko/conversion/JP2-to-ICO)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="JP2을 ICO로 변환 - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "d167f0c1dd15b076686df701892e6b1a" "convert-jp2-to-ico.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기 | JP2">}}
JPEG 2000(JP2)은 이미지 코딩 시스템이자 최첨단 이미지 압축 표준입니다. 웨이블릿 기술을 사용하여 설계된 JPEG 2000은 한 번에 모든 품질의 무손실 콘텐츠를 코딩할 수 있습니다. 게다가 JPEG 2000은 코딩 효율성에 있어 실질적인 불이익 없이 동일한 콘텐츠에 액세스하고 다양한 다른 해상도와 품질로 효과적으로 디코딩할 수 있는 기능을 가지고 있습니다. JPEG 2000의 코드 스트림은 공간 랜덤 액세스를 위한 기능을 제공하는 관심 영역을 갖도록 확장할 수 있습니다. 최대 16384개의 다양한 구성 요소를 테라픽셀 단위의 치수와 38비트/샘플의 정밀도까지 보유합니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="ICO" readMoreLink="https://docs.fileformat.com/image/ico/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기 | ICO">}}
ICO 파일 형식은 Microsoft Windows의 컴퓨터 아이콘에 대한 이미지 파일 형식입니다. ICO 파일에는 적절하게 크기를 조정할 수 있도록 여러 크기와 색상 깊이의 하나 이상의 작은 이미지가 포함되어 있습니다. Windows에서 바탕 화면, 시작 메뉴 또는 Windows 탐색기에서 사용자에게 아이콘을 표시하는 모든 실행 파일에는 ICO 형식의 아이콘이 있어야 합니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="C#을 사용하면 다음을 포함한 다양한 형식을 쉽게 변환할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-bmp/" name="BMP" description="비트맵 그림" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-gif/" name="GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-dicom/" name="DICOM" description="디지털 이미징 및 통신" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-emf/" name="EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-jpg/" name="JPG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-jpeg/" name="JPEG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-j2k/" name="J2K" description="웨이블릿 압축 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-png/" name="PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-apng/" name="APNG" description="애니메이션 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-psd/" name="PSD" description="포토샵 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-dxf/" name="DXF" description="도면 교환 형식 또는 도면 교환 형식," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-svg/" name="SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-tiff/" name="TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-webp/" name="WEBP" description="래스터 웹 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-wmf/" name="WMF" description="마이크로소프트 윈도우 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-pdf/" name="PDF" description="휴대용 문서 형식(PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-html/" name="HTML" description="HTML5 캔버스" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-emz/" name="EMZ" description="Windows 압축 확장 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-wmz/" name="WMZ" description="압축된 Windows Media Player 스킨" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-tga/" name="TGA" description="타르가 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-svgz/" name="SVGZ" description="확장 가능한 벡터 그래픽(.SVG) 파일의 압축 버전입니다." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-canvas/" name="CANVAS" description="HTML5 캔버스" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/conversion/jp2-to-ico/" name="ICO" description="윈도우 아이콘" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
