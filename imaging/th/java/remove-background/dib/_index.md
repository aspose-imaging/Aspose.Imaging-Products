﻿---
title: ลบพื้นหลังในเอกสาร DIB ผ่าน Java 
weight: 3920
url: /th/java/remove-background/dib/ 
lang: th
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: ลองใช้ API เอกสารภายในองค์กรของเราเพื่อเปลี่ยนพื้นหลังจากไฟล์ DIB บนแอปพลิเคชัน Java
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ลบพื้นหลังจาก DIB ผ่าน Java" h2="สร้างแอป Java ของคุณเองเพื่อลบพื้นหลังออกจากไฟล์ DIB โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DIB" pfName="Aspose.Imaging" subTitlepfName="สำหรับ Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="สำหรับ Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/th/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="หน้าแรก API" codeSamplesText="ตัวอย่างโค้ด" liveDemosText="การสาธิตสด" downloadText="ดาวน์โหลด" learnText="เรียนรู้">}}

{{% blocks/products/pf/agp/content h2="วิธีลบพื้นหลังในไฟล์ DIB โดยใช้ Java" %}}

การลบพื้นหลังออกจากรูปภาพเกี่ยวข้องกับการแยกวัตถุเบื้องหน้า ซึ่งเป็นงานที่ต้องมีการรับรู้วัตถุ มีหลายวิธีในการระบุวัตถุภายในภาพถ่ายในรูปแบบ DIB สำหรับรูปภาพธรรมดาที่มีพื้นหลังสีสม่ำเสมอ วิธีการแบบอัตโนมัติก็เพียงพอแล้ว อย่างไรก็ตาม สำหรับภาพถ่ายที่มีหลายภาพหรือรวมบางส่วนเข้าด้วยกัน จำเป็นต้องมีการมาร์กวัตถุล่วงหน้า ซึ่งเกี่ยวข้องกับการระบุขอบเขตสี่เหลี่ยมและประเภทวัตถุสำหรับการลบออก ในกรณีที่ซับซ้อน Cloud API จะเปิดใช้งานการตรวจจับวัตถุอัตโนมัติ Cloud API มอบแอปพลิเคชันระบบคลาวด์ที่สามารถจดจำวัตถุภายในภาพถ่าย โดยใช้ประโยชน์จากรูปทรงผลลัพธ์สำหรับการลบพื้นหลัง หลังการลบออก ขอบที่ทิ้งไว้ตามตัวเลขสามารถปรับให้เรียบได้เพื่อเพิ่มคุณภาพของภาพ เพื่อลบพื้นหลังในไฟล์ DIB เราจะใช้ [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API ซึ่งเป็น API การแปลงและการแปลงรูปภาพที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม Java คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) และติดตั้งภายใน Maven ของคุณ - ตามโครงการโดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการลบพื้นหลังจาก DIB ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

คุณต้องมี [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) เพื่อลองใช้เวิร์กโฟลว์ต่อไปนี้ในสภาพแวดล้อมของคุณเอง

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ DIB ด้วยวิธี Image.load
+ ลบพื้นหลัง;
+ บันทึกภาพลงแผ่นดิสก์ในรูปแบบที่รองรับโดย Aspose.Imaging

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging สำหรับ Java ได้รับการสนับสนุนในระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- ติดตั้ง JDK 1.6 หรือสูงกว่า

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ลบพื้นหลังในรูปภาพ DIB - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Imaging สำหรับ Java API" %}}


Aspose.Imaging API เป็นโซลูชันการประมวลผลรูปภาพเพื่อสร้าง แก้ไข วาดหรือแปลงรูปภาพ (ภาพถ่าย) ภายในแอปพลิเคชัน นำเสนอ: การประมวลผลภาพข้ามแพลตฟอร์ม รวมถึงแต่ไม่จำกัดเพียงการแปลงระหว่างรูปแบบภาพต่างๆ (รวมถึงการประมวลผลภาพแบบหลายหน้าหรือหลายเฟรมแบบเดียวกัน) การปรับเปลี่ยน เช่น การวาด การทำงานกับภาพกราฟิกดั้งเดิม การแปลงภาพ (ปรับขนาด ครอบตัด พลิกและหมุน , ไบนารี, ระดับสีเทา, ปรับ), คุณสมบัติการจัดการภาพขั้นสูง (การกรอง, การแยกสี, การปิดบัง, การเดสก์) และกลยุทธ์การปรับหน่วยความจำให้เหมาะสม เป็นไลบรารีแบบสแตนด์อโลนและไม่ขึ้นกับซอฟต์แวร์ใด ๆ สำหรับการทำงานของรูปภาพ คุณสามารถเพิ่มคุณสมบัติการแปลงรูปภาพประสิทธิภาพสูงด้วย API ดั้งเดิมภายในโปรเจ็กต์ได้อย่างง่ายดาย สิ่งเหล่านี้เป็น API ภายในองค์กรที่เป็นส่วนตัว 100% และอิมเมจได้รับการประมวลผลที่เซิร์ฟเวอร์ของคุณ


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ลบพื้นหลังใน DIB ผ่านแอปออนไลน์" sectionDescription="ลบพื้นหลังในเอกสาร DIB โดยไปที่ [เว็บไซต์ Live Demos](https://products.aspose.app/imaging/remove-background) การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="ไม่ต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัปโหลดไฟล์ DIB แล้วกดปุ่ม ลบพื้นหลังทันที" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="รับลิงค์ดาวน์โหลดทันทีสำหรับไฟล์ผลลัพธ์" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DIB" readMoreLink="https://docs.fileformat.com/image/dib/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม" >}}
ไฟล์ DIB (Device Independent Bitmap) เป็นไฟล์ภาพแรสเตอร์ที่มีโครงสร้างคล้ายกับไฟล์ Bitmap มาตรฐาน (BMP) แต่มีส่วนหัวต่างกัน สามารถเปิดได้ด้วยแอพพลิเคชั่นเกือบทั้งหมดที่สามารถเปิดไฟล์ BMP มาตรฐานบน Windows เช่นเดียวกับ macOS DIB เป็นไฟล์ไบนารีและมีรูปแบบไฟล์ที่ซับซ้อนคล้ายกับ BMP
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบการลบพื้นหลังอื่น ๆ ที่รองรับ" subTitle="เมื่อใช้ Java ผู้ใช้จะลบพื้นหลังออกจากรูปแบบต่างๆ ได้อย่างง่ายดาย เช่น" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/apng/" name="APNG" description="กราฟิกเครือข่ายแบบพกพาแบบเคลื่อนไหว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/bmp/" name="BMP" description="รูปภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/ico/" name="ICO" description="ไอคอน Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/jpg/" name="JPG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/dicom/" name="DICOM" description="การถ่ายภาพและการสื่อสารดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/djvu/" name="DJVU" description="รูปแบบกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/dng/" name="DNG" description="ภาพกล้องดิจิตอล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/emf/" name="EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/emz/" name="EMZ" description="Windows บีบอัด Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/j2k/" name="J2K" description="ภาพบีบอัดเวฟเล็ต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/tiff/" name="TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/webp/" name="WEBP" description="รูปภาพเว็บแรสเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/wmz/" name="WMZ" description="สกิน Windows Media Player ที่บีบอัด" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/svg/" name="SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/eps/" name="EPS" description="ภาษา PostScript ที่ห่อหุ้ม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/cdr/" name="CDR" description="วาดภาพเวกเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/cmx/" name="CMX" description="รูปภาพ Corel Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/otg/" name="OTG" description="มาตรฐาน OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/odg/" name="ODG" description="รูปแบบการวาด Apache OpenOffice" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/java/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
