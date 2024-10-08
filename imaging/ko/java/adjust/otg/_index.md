﻿---
title: Java을 통해 OTG 문서 조정 
weight: 3920
url: /ko/java/adjust/otg/ 
lang: ko
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: .NET Framework, .NET Core, Windows 애플리케이션, ASP.NET 웹 애플리케이션에서 OTG 파일을 조정하려면 온프레미스 문서 API를 사용해 보세요.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java를 통해 OTG 조정" h2="서버 측 API를 사용하여 OTG 파일을 조정하는 고유한 Java 앱을 빌드하세요." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="OTG" pfName="Aspose.Imaging" subTitlepfName="Java용" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ko/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="Java을 사용하여 OTG 파일을 조정하는 방법" %}}

경험이 가장 많은 사진작가라도 촬영 중에 실수를 하거나 불리한 조명 조건에 직면할 수 있습니다. 이러한 상황은 이미지 결함으로 이어질 수 있지만, 나쁜 사진에도 기회가 있습니다. Java 라이브러리를 사용하면 밝기, 대비 및 색상 감마를 조정하여 이러한 문제를 프로그래밍 방식으로 수정할 수 있습니다. 사진이 너무 어두워지면 밝기를 높이면 어두운 부분이 밝아지고 이전에 숨겨진 세부 사항이 표시됩니다. 대비를 조정하면 밝은 부분과 어두운 부분의 차이가 증가하여 밝기 범위가 확장되어 향상된 이미지를 얻을 수 있습니다. 인공 조명 아래에서 사진을 촬영하여 원치 않는 색조가 나온 경우 색상 감마 조정을 활용하여 화이트 밸런스를 수정하세요. OTG 파일을 조정하기 위해 다음을 사용하겠습니다. [자바용 Aspose.Imaging](https://products.aspose.com/imaging/java) 기능이 풍부하고 강력하며 사용하기쉬운 Java 플랫폼용 이미지 조작 및 변환 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.[메이븐(https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

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

{{% blocks/products/pf/agp/feature-section-col title="Java을 통해 OTG을 조정하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

당신은 필요합니다 [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) 자신의 환경에서 다음 워크플로를 시도합니다.

{{% /blocks/products/pf/agp/text %}}

+ Image.Load 메서드로 OTG 파일 로드
+ 이미지 조정;
+ Aspose.Imaging 형식에서 지원하는 압축 이미지를 디스크에 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

Java용 Aspose.Imaging은 모든 주요 운영 체제에서 지원됩니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 이상이 설치되어 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OTG 이미지 조정 - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "822bcdd56fb7d62b05d9d0ad94cfba29" "adjust-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Java API용 Aspose.Imaging 정보" %}}


Aspose.Imaging API는 애플리케이션 내에서 이미지(사진)를 생성, 수정, 그리기 또는 변환하는 이미지 처리 솔루션입니다. 다양한 이미지 형식 간의 변환(균일한 다중 페이지 또는 다중 프레임 이미지 처리 포함), 그리기와 같은 수정, 그래픽 프리미티브 작업, 변환(크기 조정, 자르기, 뒤집기 및 회전)을 포함하되 이에 국한되지 않는 플랫폼 간 이미지 처리 , 이진화, 회색조, 조정), 고급 이미지 조작 기능(필터링, 디더링, 마스킹, 기울기 보정) 및 메모리 최적화 전략. 독립 실행형 라이브러리이며 이미지 작업을 위해 소프트웨어에 의존하지 않습니다. 프로젝트 내에서 기본 API를 사용하여 고성능 이미지 변환 기능을 쉽게 추가할 수 있습니다. 이는 100% 비공개 온프레미스 API이며 이미지는 서버에서 처리됩니다.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="온라인 앱을 통해 OTG 조정" sectionDescription="[라이브 데모 웹사이트](https://products.aspose.app/imaging/image-Adjust)를 방문하여 OTG 문서를 조정하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="아무것도 다운로드하거나 설정할 필요가 없습니다" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="코드를 작성할 필요가 없습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="OTG 파일을 업로드하고 \"지금 조정\" 버튼을 누르세요." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="결과 파일에 대한 다운로드 링크를 즉시 가져옵니다." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="OTG" readMoreLink="https://docs.fileformat.com/image/otg/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기" >}}
OTG 파일은 OASIS Office Applications 1.0 사양을 따르는 OpenDocument 표준을 사용하여 만든 도면 템플릿입니다. 파일 내용을 더욱 향상시키는 데 사용할 수 있는 벡터 이미지에 대한 그리기 요소의 기본 구성을 나타냅니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 조정 형식" subTitle="Java을 사용하면 다음을 포함한 다양한 형식을 쉽게 조정할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/apng/" name="APNG" description="애니메이션 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/bmp/" name="BMP" description="비트맵 그림" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/ico/" name="ICO" description="윈도우 아이콘" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/jpg/" name="JPG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/jpeg/" name="JPEG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/dib/" name="DIB" description="장치 독립 비트맵" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/dicom/" name="DICOM" description="디지털 이미징 및 통신" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/djvu/" name="DJVU" description="그래픽 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/dng/" name="DNG" description="디지털 카메라 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/emf/" name="EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/emz/" name="EMZ" description="Windows 압축 확장 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/gif/" name="GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/j2k/" name="J2K" description="웨이블릿 압축 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/png/" name="PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/tiff/" name="TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/tif/" name="TIF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/webp/" name="WEBP" description="래스터 웹 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/wmf/" name="WMF" description="마이크로소프트 윈도우 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/wmz/" name="WMZ" description="압축된 Windows Media Player 스킨" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/tga/" name="TGA" description="타르가 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/svg/" name="SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/eps/" name="EPS" description="캡슐화된 포스트스크립트 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/cdr/" name="CDR" description="벡터 드로잉 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/cmx/" name="CMX" description="Corel 교환 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/odg/" name="ODG" description="Apache OpenOffice 그리기 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/adjust/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
