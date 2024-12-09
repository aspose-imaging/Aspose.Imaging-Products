﻿---
title: Binarize tài liệu AVIF qua Java 
weight: 3920
url: /vi/java/binarize/avif/ 
lang: vi
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Thử các API tài liệu On-Premise của chúng tôi để Binarize các tệp AVIF trên .NET Framework, .NET Core, Windows Application, ASP.NET Web Application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Binarize AVIF s qua Java" h2="Tạo ứng dụng Java của riêng bạn để Binarize các tệp AVIF bằng cách sử dụng API phía máy chủ." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="AVIF" pfName="Aspose.Imaging" subTitlepfName="cho Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="cho Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/vi/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Trang chủ API" codeSamplesText="Mẫu mã" liveDemosText="Bản trình diễn trực tiếp" downloadText="Tải xuống" learnText="Học hỏi">}}

{{% blocks/products/pf/agp/content h2="Cách Binarize AVIF Tệp bằng Java" %}}

Việc phát minh ra phim màu đánh dấu một cột mốc quan trọng trong lĩnh vực nhiếp ảnh. Tuy nhiên, nhiếp ảnh cổ điển vốn gắn liền với hình ảnh đen trắng. Bất chấp khả năng kỹ thuật sâu rộng của máy ảnh để thu được toàn bộ dải màu, nhiều người vẫn chọn chế độ đơn sắc, chuyển ảnh của họ thành đen trắng. Trong những trường hợp như vậy, chức năng nhị phân hóa sẽ hoạt động, chuyển đổi tất cả pixel thành giá trị nhị phân: \"0\" cho màu trắng và \"1\" cho màu đen. Trong các trường hợp khác, sự chuyển đổi này không được thúc đẩy bởi các lựa chọn nghệ thuật mà là những lựa chọn thực tế, như chuẩn bị các hình minh họa đen trắng để in trên sách hoặc báo. Sử dụng thư viện đồ họa Java, bạn có thể chỉ định ngưỡng độ sáng pixel. Các pixel có giá trị độ sáng dưới ngưỡng này sẽ trở thành màu đen, trong khi các pixel ở trên sẽ trở thành màu trắng. Ngoài ra, bạn có thể sử dụng phương pháp nhị phân thích ứng để xem xét các giá trị pixel ở khu vực xung quanh. Cách tiếp cận này mang lại sự chuyển tiếp mượt mà hơn giữa các ranh giới màu trong hình ảnh đen trắng thu được. Để nhị phân hóa các tệp AVIF, chúng tôi sẽ sử dụng [Aspose.Imaging cho Java] (https://products.aspose.com/imaging/java) API là một API chuyển đổi và thao tác hình ảnh giàu tính năng, mạnh mẽ và dễ sử dụng cho nền tảng Java. Bạn có thể tải xuống phiên bản mới nhất của nó trực tiếp từ [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) và cài đặt nó trong dự án dựa trên Maven của bạn bằng cách thêm các cấu hình sau vào pom.xml.

{{% blocks/products/pf/agp/code-block title="Kho" offSpacer="true"%}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block%}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true"%}}

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

{{% blocks/products/pf/agp/feature-section-col title="Các bước để Binarize AVIF qua Java" %}}

{{% blocks/products/pf/agp/text %}}

Bạn cần [aspose-images-version-jdk16.jar] (https://downloads.aspose.com/imaging/java) để thử quy trình làm việc sau trong môi trường của riêng bạn.

{{% /blocks/products/pf/agp/text %}}

+ Tải tệp AVIF bằng phương pháp Image.Load
+ Binarize hình ảnh;
+ Lưu hình ảnh nén vào đĩa ở định dạng Aspose.Imaging được hỗ trợ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging cho Java được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Đã cài đặt JDK 1.6 trở lên.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Binarize AVIF hình ảnh - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "daac19b481878f17e5e6caadd16bb490" "binarize-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.Imaging cho API Java" %}}


Aspose.Imaging API là một giải pháp xử lý hình ảnh để tạo, sửa đổi, vẽ hoặc chuyển đổi hình ảnh (ảnh) trong các ứng dụng. Nó cung cấp: xử lý hình ảnh đa nền tảng, bao gồm nhưng không giới hạn ở chuyển đổi giữa các định dạng hình ảnh khác nhau (bao gồm xử lý hình ảnh nhiều trang hoặc nhiều khung hình đồng nhất), các sửa đổi như vẽ, làm việc với đồ họa nguyên thủy, chuyển đổi (thay đổi kích thước, cắt, lật và xoay , binarization, thang độ xám, điều chỉnh), các tính năng thao tác hình ảnh nâng cao (lọc, phối màu, tạo mặt nạ, giải mã) và các chiến lược tối ưu hóa bộ nhớ. Đây là một thư viện độc lập và không phụ thuộc vào bất kỳ phần mềm nào cho các thao tác hình ảnh. Người ta có thể dễ dàng thêm các tính năng chuyển đổi hình ảnh hiệu suất cao với các API gốc trong các dự án. Đây là các API tại chỗ 100% riêng tư và hình ảnh được xử lý tại máy chủ của bạn.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Binarize AVIF qua Ứng dụng Trực tuyến" sectionDescription="Binarize các tài liệu AVIF bằng cách truy cập [trang web Bản trình diễn trực tiếp] của chúng tôi (https://products.aspose.app/imaging/image-Binarize). Bản demo trực tiếp có những lợi ích sau" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Không cần viết bất kỳ mã nào" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Chỉ cần tải lên các tệp AVIF của bạn và nhấn nút \"Binarize now \"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Nhận ngay liên kết tải xuống cho tệp kết quả" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="Những gì là" whatIsFormat2="Định dạng tệp" readMoreFormat="Đọc thêm" >}}

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng Binarize được hỗ trợ khác" subTitle="Sử dụng Java, người ta có thể dễ dàng Binarize các định dạng khác nhau bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/apng/" name="APNG" description="Đồ họa mạng di động hoạt hình" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/bmp/" name="BMP" description="Ảnh bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/ico/" name="ICO" description="Biểu tượng Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/jpg/" name="JPG" description="Nhóm chuyên gia nhiếp ảnh chung" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/jpeg/" name="JPEG" description="Nhóm chuyên gia nhiếp ảnh chung" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/dib/" name="DIB" description="Bản đồ bit độc lập với thiết bị" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/dicom/" name="DICOM" description="Hình ảnh & Truyền thông Kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/djvu/" name="DJVU" description="Định dạng đồ họa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/dng/" name="DNG" description="Hình ảnh máy ảnh kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/emf/" name="EMF" description="Định dạng siêu tệp nâng cao" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/emz/" name="EMZ" description="Siêu tệp nâng cao được nén của Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/gif/" name="GIF" description="Định dạng trao đổi đồ họa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/j2k/" name="J2K" description="Hình ảnh nén Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/png/" name="PNG" description="Biểu đồ minh họa mạng lưới không dây" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/tiff/" name="TIFF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/tif/" name="TIF" description="Định dạng hình ảnh được gắn thẻ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/webp/" name="WEBP" description="Raster Hình ảnh Web" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/wmz/" name="WMZ" description="Giao diện Windows Media Player được nén" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/tga/" name="TGA" description="Đồ họa Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/svg/" name="SVG" description="Đồ họa vector có thể mở rộng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/eps/" name="EPS" description="Ngôn ngữ PostScript được đóng gói" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/cdr/" name="CDR" description="Hình ảnh Bản vẽ Véc tơ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/cmx/" name="CMX" description="Hình ảnh trao đổi Corel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/otg/" name="OTG" description="Tiêu chuẩn OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/vi/java/binarize/odg/" name="ODG" description="Apache OpenOffice Draw Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}