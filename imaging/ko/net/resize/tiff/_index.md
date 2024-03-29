﻿---
title: .NET을 통해 TIFF 문서 크기 조정 
weight: 3920
url: /ko/net/resize/tiff/ 
lang: ko
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: .NET Framework, .NET Core, Windows 애플리케이션, ASP.NET 웹 애플리케이션에서 TIFF 파일의 크기를 조정하려면 온프레미스 문서 API를 사용해 보세요.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C#을 통해 TIFF 크기 조정" h2="서버 측 API를 사용하여 TIFF 파일의 크기를 조정하는 고유한 .NET 앱을 빌드하세요." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="Aspose.Imaging" subTitlepfName=".NET용" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ko/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 TIFF 파일의 크기를 조정하는 방법" %}}

웹 사이트를 구축하는 것은 각 요소가 의미를 갖는 복잡한 노력입니다. 웹 페이지를 채우는 과정에서 중요한 측면은 이미지 크기 조정과 관련됩니다. 치수 크기를 조정하고 다양한 해상도로 이미지나 사진을 준비해야 하는 경우가 종종 있습니다. 예를 들어, 미리보기가 포함된 이미지 갤러리가 포함된 페이지에는 작은 축소판 파일이 필요한 반면, 기본 이미지를 표시하는 페이지에는 고해상도 버전이 필요합니다. 큰 파일의 경우 크기 조정은 총 픽셀 수를 줄이는 데 필수적이므로 이미지 품질을 크게 저하시키지 않으면서 파일 크기를 줄일 수 있습니다. 이미지 크기를 조정하는 동안 데이터 압축 정도를 선택하여 이미지 크기와 품질 간의 균형을 유지할 수도 있습니다. 이미지 크기가 줄어들면 인터넷에서 로딩 시간이 더 빨라지고 웹사이트에서의 사용자 탐색 경험이 향상됩니다. [.NET용 Aspose.Imaging](https://products.aspose.com/imaging/net) 기능이 풍부하고 강력하며 사용하기 쉬운 C# 플랫폼용 이미지 조작 및 변환 API인 API입니다. 열려있는 [누겟](https://www.nuget.org/packages/aspose.imaging) 패키지 관리자, 검색 **아포즈.이미징** 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}



```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#을 통해 TIFF 크기를 조정하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

당신은 필요합니다 [aspose.imaging.dll](https://downloads.aspose.com/imaging/net) 자신의 환경에서 다음 워크플로를 시도합니다.

{{% /blocks/products/pf/agp/text %}}

+ Image.Load 메소드로 TIFF 파일 로드
+ 이미지 크기 조정
+ Aspose.Imaging 형식에서 지원하는 크기 조정된 이미지를 디스크에 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

.NET용 Aspose.Imaging은 모든 주요 운영 체제에서 지원됩니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Windows 애플리케이션, ASP.NET 웹 애플리케이션과 호환되는 OS.
- Microsoft Visual Studio와 같은 개발 환경.
- 프로젝트에서 참조되는 .NET용 Aspose.Imaging.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TIFF 이미지 크기 조정 - .NET" offSpacer="" %}}

{{< gist "aspose-com-gists" "86c29f2c35c7c19a0ae65cea371ab3e5" "resize-bitmap-formats.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2=".NET API용 Aspose.Imaging 정보" %}}


Aspose.Imaging API는 애플리케이션 내에서 이미지(사진)를 생성, 수정, 그리기 또는 변환하는 이미지 처리 솔루션입니다. 다양한 이미지 형식 간의 변환(균일한 다중 페이지 또는 다중 프레임 이미지 처리 포함), 그리기와 같은 수정, 그래픽 프리미티브 작업, 변환(크기 조정, 자르기, 뒤집기 및 회전)을 포함하되 이에 국한되지 않는 플랫폼 간 이미지 처리 , 이진화, 회색조, 조정), 고급 이미지 조작 기능(필터링, 디더링, 마스킹, 기울기 보정) 및 메모리 최적화 전략. 독립 실행형 라이브러리이며 이미지 작업을 위해 소프트웨어에 의존하지 않습니다. 프로젝트 내에서 기본 API를 사용하여 고성능 이미지 변환 기능을 쉽게 추가할 수 있습니다. 이는 100% 비공개 온프레미스 API이며 이미지는 서버에서 처리됩니다.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="온라인 앱을 통해 TIFF 크기 조정" sectionDescription="[라이브 데모 웹사이트](https://products.aspose.app/imaging/image-resize)를 방문하여 TIFF 문서의 크기를 조정하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="아무것도 다운로드하거나 설정할 필요가 없습니다" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="코드를 작성할 필요가 없습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="TIFF 파일을 업로드하고 \"크기 조정\" 버튼을 누르세요." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="결과 파일에 대한 다운로드 링크를 즉시 가져옵니다." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기" >}}
TIFF 또는 TIF(Tagged Image File Format)는 이 파일 형식 표준을 준수하는 다양한 장치에서 사용하기 위한 래스터 이미지를 나타냅니다. 여러 색상 공간에서 이중 레벨, 회색조, 팔레트 색상 및 풀 컬러 이미지 데이터를 설명할 수 있습니다. 이 형식을 사용하는 응용 프로그램에 대해 공간과 시간 사이에서 선택하기 위해 손실 및 무손실 압축 방식을 지원합니다. 이 형식은 확장 가능하며 개인 정보 또는 특수 목적 정보를 무제한으로 포함할 수 있도록 여러 번 수정되었습니다. 형식은 시스템에 종속되지 않으며 프로세서, 운영 체제 또는 파일 시스템과 같은 범위에서 자유롭습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 크기 조정 형식" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/apng/" name="APNG" description="애니메이션 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/bmp/" name="BMP" description="비트맵 그림" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/ico/" name="ICO" description="윈도우 아이콘" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/jpg/" name="JPG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/cdr/" name="CDR" description="벡터 드로잉 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/cmx/" name="CMX" description="Corel 교환 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/dib/" name="DIB" description="장치 독립 비트맵" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/dicom/" name="DICOM" description="디지털 이미징 및 통신" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/djvu/" name="DJVU" description="그래픽 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/dng/" name="DNG" description="디지털 카메라 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/emf/" name="EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/eps/" name="EPS" description="캡슐화된 포스트스크립트 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/gif/" name="GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/j2k/" name="J2K" description="웨이블릿 압축 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/odg/" name="ODG" description="Apache OpenOffice 그리기 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/otg/" name="OTG" description="OpenDocument 표준" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/png/" name="PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/svg/" name="SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/webp/" name="WEBP" description="래스터 웹 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/net/resize/wmf/" name="WMF" description="마이크로소프트 윈도우 메타파일" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
