﻿---
title: Python을 사용하여 EMZ에서 DICOM로 이미지 변환 
weight: 3920
url: /ko/python-net/conversion/emz-to-dicom/ 
lang: ko
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: 데스크탑 및 웹 애플리케이션에서 EMZ에서 DICOM 이미지 및 사진 변환을 위해 Python을 사용하는 방법.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="EMZ에서 DICOM 이미지로 변환하려면 Python을 사용하세요." h2="서버 API를 통해 EMZ을 DICOM 이미지 및 사진으로 변환하는 Python 앱을 만듭니다." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DICOM" pfName="Aspose.Imaging" subTitlepfName="Python용" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Python용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/ko/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ko/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다" overviewText="개요" >}}

{{% blocks/products/pf/agp/content h2="Python를 사용하여 EMZ을 DICOM 이미지 및 사진으로 변환하는 방법" %}}

한 형식에서 다른 형식으로 이미지 파일을 변환하는 것은 모든 그래픽 디자이너가 겪는 일반적인 작업입니다. 파일 변환의 효율성과 우수성은 완료 속도에 영향을 미칠 뿐만 아니라 전반적인 작업 품질을 평가하는 데 중요한 역할을 합니다. 이미지 소스의 경우 인쇄나 온라인 배포에 더 적합한 대체 형식으로 변환해야 하는 경우가 많습니다. 그래픽 편집기에서 만든 이미지는 벡터 형식일 가능성이 높습니다. 이러한 경우 웹 사이트 게시를 위해서는 래스터화를 거쳐 래스터 형식으로 저장되어야 합니다. 우수한 품질을 위해 이미지를 압축되지 않은 형식으로 변환하거나 무손실 압축 형식으로 저장하여 파일 크기를 최소화할 수 있는 옵션이 있습니다. 웹 사이트 애플리케이션과 같이 파일 크기 축소가 필수인 시나리오의 경우 손실 압축 형식으로 변환할 가능성이 있습니다. 이미지용 특수 데이터 압축 알고리즘은 허용 가능한 이미지 품질을 유지하면서 파일 크기를 크게 줄여 신속한 이미지 로딩을 보장합니다. 이미지와 사진을 EMZ에서 DICOM로 변환하려면 다음을 사용합니다. [Aspose.Imaging for Python via .NET](/imaging/ko/python-net) API는 기능이 풍부하고 강력하며 사용하기 쉬운 Python 플랫폼용 이미지 조작 및 변환 API입니다. 시스템 명령에서 다음 명령을 사용하여 설치할 수 있습니다.

{{% blocks/products/pf/agp/code-block title="시스템 명령줄" offSpacer="true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Python을 통해 EMZ을 DICOM로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

개발자는 몇 줄의 코드로 EMZ 파일을 DICOM로 쉽게 로드하고 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

+ Image.Load 메소드로 EMZ 파일 로드
+ ImageOptionsBase의 필수 하위 클래스(예: BmpOptions, PngOptions 등)의 인스턴스 생성 및 설정
+ Image.Save 메서드 호출
+ ImageOptionsBase 클래스의 DICOM 확장명 및 개체로 파일 경로 전달

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

변환 예제 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

+ 운영 체제: Windows 또는 Linux.
+ 개발 환경: Microsoft Visual Studio 등 .NET Core 7 이상을 지원합니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="EMZ을 DICOM로 변환하는 무료 앱"
        appName="Conversion"
        extension="EMZ-to-DICOM"
        label1="EMZ 이미지 선택 또는 드래그 앤 드롭"
        label2="형식을 선택하고 변환 버튼을 클릭하십시오"
        label3="다운로드 버튼을 클릭하여 DICOM 이미지를 다운로드합니다."
        checkFreeAppLabel="를 확인하세요 [EMZ을 DICOM로 변환하는 라이브 데모]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/ko/conversion/EMZ-to-DICOM)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="EMZ을 DICOM로 변환 - Python" offSpacer="true" %}}

{{< gist "aspose-com-gists" "e1d418ed58a1f4598f259e62914511d4" "convert-image-to-other-format.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="EMZ" readMoreLink="https://docs.fileformat.com/image/emz/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기 | EMZ">}}
EMZ 파일 확장자를 가진 파일은 압축된 이미지 파일이며, 보다 구체적으로 Windows Compressed Enhanced Metafile 파일이라고 합니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기 | DICOM">}}
DICOM은 Digital Imaging and Communications in Medicine의 약자로 의료 정보학 분야와 관련이 있습니다. DICOM은 파일 형식 정의와 네트워크 통신 프로토콜의 조합입니다. DICOM은 .DCM 확장자를 사용합니다. .DCM은 형식 1.x와 형식 2.x의 두 가지 형식으로 존재합니다. DCM 형식 1.x는 일반 및 확장의 두 가지 버전으로 추가로 제공됩니다. DICOM은 다양한 공급업체의 프린터, 서버, 스캐너 등과 같은 의료 영상 장치의 통합에 사용되며 고유성을 위해 각 환자의 식별 데이터도 포함합니다. DICOM 파일은 DICOM 형식의 이미지 데이터를 수신할 수 있는 경우 두 당사자 간에 공유할 수 있습니다. DICOM의 통신 부분은 응용 계층 프로토콜이며 TCP/IP를 사용하여 엔터티 간에 통신합니다. HTTP 및 HTTPS 프로토콜은 DICOM의 웹 서비스에 사용됩니다. 웹 서비스에서 지원하는 버전은 1.0, 1.1, 2 이상입니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="Python을 사용하면 다음을 포함한 다양한 형식을 쉽게 변환할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-bmp/" name="BMP" description="비트맵 그림" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-gif/" name="GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-dicom/" name="DICOM" description="디지털 이미징 및 통신" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-emf/" name="EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-jpg/" name="JPG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-jpeg/" name="JPEG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-j2k/" name="J2K" description="웨이블릿 압축 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-png/" name="PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-apng/" name="APNG" description="애니메이션 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-psd/" name="PSD" description="포토샵 문서" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-dxf/" name="DXF" description="도면 교환 형식 또는 도면 교환 형식," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-svg/" name="SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-tiff/" name="TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-webp/" name="WEBP" description="래스터 웹 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-wmf/" name="WMF" description="마이크로소프트 윈도우 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-pdf/" name="PDF" description="휴대용 문서 형식(PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-html/" name="HTML" description="HTML5 캔버스" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-wmz/" name="WMZ" description="압축된 Windows Media Player 스킨" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-tga/" name="TGA" description="타르가 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-svgz/" name="SVGZ" description="확장 가능한 벡터 그래픽(.SVG) 파일의 압축 버전입니다." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-canvas/" name="CANVAS" description="HTML5 캔버스" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/python-net/conversion/emz-to-ico/" name="ICO" description="윈도우 아이콘" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
