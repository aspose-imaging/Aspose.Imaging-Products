﻿---
title: แปลง AVIF เป็น WEBP ผ่าน Java 
weight: 3920
url: /th/java/conversion/avif-to-webp/ 
lang: th
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: โค้ดตัวอย่างสำหรับการแปลง AVIF เป็น WEBP Java ใช้โค้ดตัวอย่าง API สำหรับไฟล์แบทช์ AVIF เป็นการแปลง WEBP ภายในแอปพลิเคชันที่ใช้ Java บนเว็บหรือเดสก์ท็อป
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="แปลง AVIF เป็น WEBP ผ่าน Java" h2="เปลี่ยน AVIF เป็น WEBP โดยใช้ API ดั้งเดิมของ Java โดยไม่ต้องใช้โปรแกรมแก้ไขรูปภาพหรือไลบรารีของบุคคลที่สาม" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="WEBP" pfName="Aspose.Imaging" subTitlepfName="สำหรับ Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="สำหรับ Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/th/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/th/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="หน้าแรกของ API" codeSamplesText="ตัวอย่างโค้ด" liveDemosText="การสาธิตสด" downloadText="ดาวน์โหลด" learnText="เรียนรู้" overviewText="ภาพรวม" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง AVIF เป็น WEBP โดยใช้ Java" %}}

การแปลงรูปแบบไฟล์อาจดูเหมือนเป็นงานประจำที่นักออกแบบกราฟิกต้องเผชิญ แต่การดูถูกความสำคัญของมันอาจเป็นความผิดพลาด การประเมินงานของคุณอาจขึ้นอยู่กับว่าคุณจัดการงานนี้ได้รวดเร็วและมีประสิทธิภาพเพียงใด โดยทั่วไปแล้ว รูปภาพต้นฉบับจำเป็นต้องแปลงเป็นรูปแบบที่เหมาะสำหรับการพิมพ์หรือการเผยแพร่ออนไลน์มากกว่า หากรูปภาพต้นฉบับมาจากโปรแกรมแก้ไขกราฟิก รูปภาพนั้นอาจอยู่ในรูปแบบเวกเตอร์ ในสถานการณ์นี้ จะต้องได้รับการแรสเตอร์และแปลงเป็นรูปแบบแรสเตอร์เพื่อวัตถุประสงค์ในการเผยแพร่ คุณมีทางเลือกในการบันทึกรูปภาพในรูปแบบที่ไม่บีบอัดเพื่อให้ได้คุณภาพที่ดีที่สุด หรือแปลงเป็นรูปแบบการบีบอัดแบบไม่สูญเสียข้อมูลเพื่อลดขนาดไฟล์ ในบางบริบท เช่น การเผยแพร่ทางเว็บ คุณสามารถเลือกรูปแบบการบีบอัดที่สูญเสียข้อมูลได้ อัลกอริธึมที่ออกแบบมาเป็นพิเศษสำหรับการบีบอัดข้อมูลภาพทำให้สามารถลดขนาดไฟล์ลงได้อย่างมาก ขณะเดียวกันก็รักษาคุณภาพของภาพที่ยอมรับได้ ช่วยให้ดาวน์โหลดไฟล์ภาพจากอินเทอร์เน็ตได้อย่างรวดเร็ว ในการแปลง AVIF เป็น WEBP เราจะใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API ซึ่งเป็น API การแปลงและการแปลงรูปภาพที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม Java คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) และติดตั้งภายใน Maven ของคุณ - ตามโครงการโดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง AVIF เป็น WEBP ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

นักพัฒนาสามารถโหลดและแปลงไฟล์ AVIF เป็น WEBP ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ AVIF ด้วยวิธี Image.load
+ สร้างและตั้งค่าอินสแตนซ์ของคลาสย่อยที่จำเป็นของ ImageOptionsBase (เช่น BmpOptions, PngOptions เป็นต้น)
+ เรียกวิธี Image.save
+ ส่งเส้นทางไฟล์ด้วยนามสกุล WEBP และวัตถุของคลาส ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

ก่อนรันโค้ดตัวอย่างการแปลง ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

+ ระบบปฏิบัติการ: Windows หรือ Linux
+ สภาพแวดล้อมการพัฒนา: รองรับ .NET Core 7 และสูงกว่า เช่น Microsoft Visual Studio

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="แอปฟรีเพื่อแปลง AVIF เป็น WEBP"
        appName="Conversion"
        extension="AVIF-to-WEBP"
        label1="เลือกหรือลากและวาง AVIF image"
        label2="เลือกรูปแบบแล้วคลิกปุ่มแปลง"
        label3="คลิกปุ่มดาวน์โหลดเพื่อดาวน์โหลด WEBP ภาพ"
        checkFreeAppLabel="ตรวจสอบ [การสาธิตสดเพื่อแปลง AVIF เป็น WEBP]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/AVIF-to-WEBP)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="แปลง AVIF เป็น WEBP - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม | AVIF">}}
AVIF เป็นข้อกำหนดรูปแบบไฟล์รูปภาพเปิดและปลอดค่าลิขสิทธิ์สำหรับจัดเก็บรูปภาพหรือลำดับภาพที่ถูกบีบอัดด้วย AV1 ในรูปแบบคอนเทนเนอร์ HEIF
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WEBP" readMoreLink="https://docs.fileformat.com/image/webp/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม | WEBP">}}
WebP ซึ่งเปิดตัวโดย Google เป็นรูปแบบไฟล์ภาพเว็บแรสเตอร์ที่ทันสมัยซึ่งใช้การบีบอัดแบบไม่สูญเสียข้อมูลและการสูญเสียข้อมูล ให้คุณภาพของภาพเท่าเดิมในขณะที่ลดขนาดภาพลงอย่างมาก เนื่องจากหน้าเว็บส่วนใหญ่ใช้รูปภาพเป็นตัวแทนข้อมูลที่มีประสิทธิภาพ การใช้รูปภาพ WebP ในหน้าเว็บส่งผลให้โหลดหน้าเว็บเร็วขึ้น ตาม Google รูปภาพที่ไม่สูญเสียของ WebP มีขนาดเล็กกว่า 26% เมื่อเทียบกับ PNG ในขณะที่รูปภาพที่สูญเสียของ WebP นั้นเล็กกว่าภาพ JPEG ที่เปรียบเทียบได้ 25-34% รูปภาพจะถูกเปรียบเทียบโดยอิงตามดัชนีความคล้ายคลึงกันของโครงสร้าง (SSIM) ระหว่าง WebP และรูปแบบไฟล์รูปภาพอื่นๆ WebP เป็นโครงการน้องสาวของรูปแบบคอนเทนเนอร์มัลติมีเดียของ WebM
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="การใช้ Java จะทำให้สามารถแปลงรูปแบบต่างๆ ได้อย่างง่ายดายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-dicom/" name="DICOM" description="การถ่ายภาพและการสื่อสารดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-emf/" name="EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-jpg/" name="JPG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-jpeg/" name="JPEG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-j2k/" name="J2K" description="ภาพบีบอัดเวฟเล็ต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-apng/" name="APNG" description="กราฟิกเครือข่ายแบบพกพาแบบเคลื่อนไหว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-psd/" name="PSD" description="เอกสาร Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-dxf/" name="DXF" description="Drawing Interchange Format หรือ Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-svg/" name="SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-tiff/" name="TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-webp/" name="WEBP" description="รูปภาพเว็บแรสเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-pdf/" name="PDF" description="รูปแบบเอกสารพกพา (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-html/" name="HTML" description="ผ้าใบ HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-emz/" name="EMZ" description="Windows บีบอัด Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-wmz/" name="WMZ" description="สกิน Windows Media Player ที่บีบอัด" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-svgz/" name="SVGZ" description="เวอร์ชันบีบอัดของไฟล์ Scalable Vector Graphics (.SVG)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-canvas/" name="CANVAS" description="ผ้าใบ HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-ico/" name="ICO" description="ไอคอน Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/conversion/avif-to-bmp/" name="BMP" description="รูปภาพบิตแมป" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
