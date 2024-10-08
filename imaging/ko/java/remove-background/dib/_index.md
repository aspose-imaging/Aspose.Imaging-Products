﻿---
title: Java을 통해 DIB 문서의 배경 제거 
weight: 3920
url: /ko/java/remove-background/dib/ 
lang: ko
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Java 애플리케이션의 DIB 파일에서 배경을 변경하려면 온프레미스 문서 API를 사용해 보세요.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java를 통해 DIB에서 배경 제거" h2="서버 측 API를 사용하여 DIB 파일에서 배경을 제거하는 고유한 Java 앱을 빌드합니다." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DIB" pfName="Aspose.Imaging" subTitlepfName="Java용" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ko/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API 홈" codeSamplesText="코드 샘플" liveDemosText="라이브 데모" downloadText="다운로드" learnText="배우다">}}

{{% blocks/products/pf/agp/content h2="Java을 사용하여 DIB 파일에서 배경을 제거하는 방법" %}}

이미지에서 배경을 제거하려면 전경 개체를 분리해야 하며, 이 작업에는 개체 인식이 필요합니다. DIB 형식의 사진 내 개체를 식별하기 위한 여러 가지 접근 방식이 있습니다. 균일한 색상 배경을 갖춘 단순한 이미지의 경우 자동 방법으로 충분합니다. 그러나 여러 개의 그림 또는 부분적으로 병합된 그림이 있는 사진의 경우 사전 마킹 개체가 필요합니다. 여기에는 제거할 직사각형 영역 및 객체 유형을 지정하는 작업이 포함됩니다. 복잡한 경우 Cloud API를 사용하면 자동 객체 감지가 가능합니다. Cloud API는 배경 제거를 위해 결과 윤곽을 활용하여 사진 내의 개체를 인식할 수 있는 클라우드 애플리케이션을 제공합니다. 제거 후 그림 뒤에 남겨진 가장자리를 부드럽게 처리하여 이미지 품질을 향상할 수 있습니다. DIB 파일에서 배경을 제거하기 위해 다음을 사용합니다. [자바용 Aspose.Imaging](https://products.aspose.com/imaging/java) 기능이 풍부하고 강력하며 사용하기쉬운 Java 플랫폼용 이미지 조작 및 변환 API인 API입니다. 에서 직접 최신 버전을 다운로드할 수 있습니다.[메이븐(https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) 다음 구성을 pom.xml에 추가하여 Maven 기반 프로젝트 내에 설치합니다.

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

{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DIB에서 배경을 제거하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

당신은 필요합니다 [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) 자신의 환경에서 다음 워크플로를 시도합니다.

{{% /blocks/products/pf/agp/text %}}

+ Image.load 메소드로 DIB 파일 로드
+ 배경 제거;
+ Aspose.Imaging 형식에서 지원하는 디스크에 이미지 저장

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

Java용 Aspose.Imaging은 모든 주요 운영 체제에서 지원됩니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 이상이 설치되어 있습니다.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DIB 이미지의 배경 제거 - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Java API용 Aspose.Imaging 정보" %}}


Aspose.Imaging API는 애플리케이션 내에서 이미지(사진)를 생성, 수정, 그리기 또는 변환하는 이미지 처리 솔루션입니다. 다양한 이미지 형식 간의 변환(균일한 다중 페이지 또는 다중 프레임 이미지 처리 포함), 그리기와 같은 수정, 그래픽 프리미티브 작업, 변환(크기 조정, 자르기, 뒤집기 및 회전)을 포함하되 이에 국한되지 않는 플랫폼 간 이미지 처리 , 이진화, 회색조, 조정), 고급 이미지 조작 기능(필터링, 디더링, 마스킹, 기울기 보정) 및 메모리 최적화 전략. 독립 실행형 라이브러리이며 이미지 작업을 위해 소프트웨어에 의존하지 않습니다. 프로젝트 내에서 기본 API를 사용하여 고성능 이미지 변환 기능을 쉽게 추가할 수 있습니다. 이는 100% 비공개 온프레미스 API이며 이미지는 서버에서 처리됩니다.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="온라인 앱을 통해 DIB에서 배경 제거" sectionDescription="[라이브 데모 웹사이트](https://products.aspose.app/imaging/remove-background)를 방문하여 DIB 문서의 배경을 제거하세요. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="아무것도 다운로드하거나 설정할 필요가 없습니다" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="코드를 작성할 필요가 없습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="DIB 파일을 업로드하고 \"지금 배경 제거\" 버튼을 누르세요." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="결과 파일에 대한 다운로드 링크를 즉시 가져옵니다." >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DIB" readMoreLink="https://docs.fileformat.com/image/dib/" whatIsFormat1="뭐가" whatIsFormat2="파일 형식" readMoreFormat="더 읽어보기" >}}
DIB(장치 독립 비트맵) 파일은 표준 비트맵 파일(BMP)과 구조가 유사하지만 헤더가 다른 래스터 이미지 파일입니다. Windows 및 macOS에서 표준 BMP 파일을 열 수 있는 거의 모든 응용 프로그램에서 열 수 있습니다. DIB는 바이너리 파일이며 BMP와 유사한 복잡한 파일 형식을 가지고 있습니다.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 배경 제거 형식" subTitle="Java을 사용하면 다음을 포함한 다양한 형식의 배경을 쉽게 제거할 수 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/apng/" name="APNG" description="애니메이션 휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/bmp/" name="BMP" description="비트맵 그림" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/ico/" name="ICO" description="윈도우 아이콘" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/jpg/" name="JPG" description="공동 사진 전문가 그룹" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/dicom/" name="DICOM" description="디지털 이미징 및 통신" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/djvu/" name="DJVU" description="그래픽 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/dng/" name="DNG" description="디지털 카메라 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/emf/" name="EMF" description="향상된 메타파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/emz/" name="EMZ" description="Windows 압축 확장 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/gif/" name="GIF" description="그래픽 교환 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/j2k/" name="J2K" description="웨이블릿 압축 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/png/" name="PNG" description="휴대용 네트워크 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/tiff/" name="TIFF" description="태그가 지정된 이미지 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/webp/" name="WEBP" description="래스터 웹 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/wmf/" name="WMF" description="마이크로소프트 윈도우 메타파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/wmz/" name="WMZ" description="압축된 Windows Media Player 스킨" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/tga/" name="TGA" description="타르가 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/svg/" name="SVG" description="확장 가능한 벡터 그래픽" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/eps/" name="EPS" description="캡슐화된 포스트스크립트 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/cdr/" name="CDR" description="벡터 드로잉 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/cmx/" name="CMX" description="Corel 교환 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/otg/" name="OTG" description="OpenDocument 표준" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/odg/" name="ODG" description="Apache OpenOffice 그리기 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ko/java/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
