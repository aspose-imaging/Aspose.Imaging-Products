﻿---
title: แปลงเอกสาร SVG ผ่าน .NET 
weight: 3920
url: /th/net/dither/svg/ 
lang: th
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: ลองใช้ API เอกสารภายในองค์กรของเราไปยังไฟล์ Dither SVG บน .NET Framework, .NET Core, Windows Application, ASP.NET Web Application
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="กำหนด SVG ผ่าน C#" h2="สร้างแอป .NET ของคุณเองให้เป็นไฟล์  ปรับให้เรียบ SVG โดยใช้ API ฝั่งเซิร์ฟเวอร์" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName="สำหรับ .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="สำหรับ .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/th/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="หน้าแรก API" codeSamplesText="ตัวอย่างโค้ด" liveDemosText="การสาธิตสด" downloadText="ดาวน์โหลด" learnText="เรียนรู้">}}

{{% blocks/products/pf/agp/content h2="วิธีการ ปรับให้เรียบ SVG ไฟล์โดยใช้ C#" %}}

การเพิ่มประสิทธิภาพรูปภาพสำหรับตำแหน่งเว็บเป็นสิ่งสำคัญเพื่อให้มั่นใจว่าผู้ใช้จะได้รับประสบการณ์ที่ราบรื่น แนวทางหนึ่งในการเพิ่มประสิทธิภาพดังกล่าวเกี่ยวข้องกับการลดจานสีของรูปภาพ ซึ่งจะช่วยลดขนาดไฟล์และปรับปรุงเวลาในการโหลดหน้าเว็บ อย่างไรก็ตาม เพื่อป้องกันการรบกวนของการไล่ระดับสีที่ราบรื่นและการปรากฏของขอบเขตที่คมชัดในพื้นที่สีเดียว จึงจำเป็นอย่างยิ่งที่จะต้องใช้ฟังก์ชันการปรับให้เรียบของภาพ หรือที่เรียกว่า Dithering เทคนิคนี้ช่วยให้คุณสามารถควบคุม \"จุดรบกวน\" ให้กับรูปภาพหรือภาพถ่ายได้ ซึ่งในทางกลับกัน จะให้ผลเชิงบวกโดยการปรับการเปลี่ยนภาพภายในขอบเขตสีให้เรียบขึ้น และเพิ่มความน่าดึงดูดทางสายตาโดยรวมของภาพ เพื่อที่จะทำไฟล์ Dither SVG เราจะใช้ [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API ซึ่งเป็น API การจัดการและการแปลงรูปภาพที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม C# เปิด [NuGet](https://www.nuget.org/packages/aspose.imaging) ตัวจัดการแพ็คเกจ ค้นหา
 ** Aspose.Imaging ** และติดตั้ง คุณสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการปรับ SVGs ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

คุณต้องใช้ [aspose.imaging.dll](https://downloads.aspose.com/imaging/net) เพื่อลองใช้เวิร์กโฟลว์ต่อไปนี้ในสภาพแวดล้อมของคุณเอง

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ SVG ด้วยวิธี Image.Load
+ ภาพ Dither;
+ บันทึกภาพที่บีบอัดลงในแผ่นดิสก์ในรูปแบบที่รองรับโดย Aspose.Imaging

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging สำหรับ .NET ได้รับการสนับสนุนในระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Windows Application, ASP.NET Web Application
- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio
- Aspose.Imaging สำหรับ .NET ที่อ้างอิงในโครงการของคุณ

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="แปลงรูปภาพ SVG - .NET" offSpacer="" %}}

{{< gist "aspose-com-gists" "95e4108a2bc8cf2db6673c1225d3123a" "dither-images.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Imaging สำหรับ .NET API" %}}


Aspose.Imaging API เป็นโซลูชันการประมวลผลรูปภาพเพื่อสร้าง แก้ไข วาดหรือแปลงรูปภาพ (ภาพถ่าย) ภายในแอปพลิเคชัน นำเสนอ: การประมวลผลภาพข้ามแพลตฟอร์ม รวมถึงแต่ไม่จำกัดเพียงการแปลงระหว่างรูปแบบภาพต่างๆ (รวมถึงการประมวลผลภาพแบบหลายหน้าหรือหลายเฟรมแบบเดียวกัน) การปรับเปลี่ยน เช่น การวาด การทำงานกับภาพกราฟิกดั้งเดิม การแปลงภาพ (ปรับขนาด ครอบตัด พลิกและหมุน , ไบนารี, ระดับสีเทา, ปรับ), คุณสมบัติการจัดการภาพขั้นสูง (การกรอง, การแยกสี, การปิดบัง, การเดสก์) และกลยุทธ์การปรับหน่วยความจำให้เหมาะสม เป็นไลบรารีแบบสแตนด์อโลนและไม่ขึ้นกับซอฟต์แวร์ใด ๆ สำหรับการทำงานของรูปภาพ คุณสามารถเพิ่มคุณสมบัติการแปลงรูปภาพประสิทธิภาพสูงด้วย API ดั้งเดิมภายในโปรเจ็กต์ได้อย่างง่ายดาย สิ่งเหล่านี้เป็น API ภายในองค์กรที่เป็นส่วนตัว 100% และอิมเมจได้รับการประมวลผลที่เซิร์ฟเวอร์ของคุณ


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ปรับให้เรียบ SVGs ผ่าน Online App" sectionDescription="แปลงเอกสาร SVG โดยไปที่ [เว็บไซต์ Live Demos](https://products.aspose.app/imaging/image-Dither) การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="ไม่ต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัปโหลดไฟล์ SVG ของคุณและกดปุ่ม ปรับให้เรียบ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="รับลิงค์ดาวน์โหลดทันทีสำหรับไฟล์ผลลัพธ์" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม" >}}
ไฟล์ SVG เป็นไฟล์กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้ซึ่งใช้รูปแบบข้อความแบบ XML เพื่ออธิบายลักษณะที่ปรากฏของรูปภาพ คำว่า Scalable หมายถึงความจริงที่ว่า SVG สามารถปรับขนาดเป็นขนาดต่างๆ ได้โดยไม่สูญเสียคุณภาพใดๆ คำอธิบายตามข้อความของไฟล์ดังกล่าวทำให้ไม่ขึ้นกับความละเอียด เป็นรูปแบบหนึ่งที่ใช้กันมากที่สุดในการสร้างเว็บไซต์และพิมพ์กราฟิกเพื่อให้ได้ความสามารถในการปรับขนาด รูปแบบสามารถใช้ได้กับกราฟิกสองมิติเท่านั้น ไฟล์ SVG สามารถดู/เปิดได้ในเบราว์เซอร์สมัยใหม่เกือบทั้งหมด รวมถึง Chrome, Internet Explorer, Firefox และ Safari
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบ ปรับให้เรียบ ที่รองรับอื่นๆ" subTitle="เมื่อใช้ C# เราสามารถ ปรับให้เรียบ รูปแบบต่างๆ ได้อย่างง่ายดายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/apng/" name="APNG" description="กราฟิกเครือข่ายแบบพกพาแบบเคลื่อนไหว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/bmp/" name="BMP" description="รูปภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/ico/" name="ICO" description="ไอคอน Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/jpg/" name="JPG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/avif/" name="AVIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/jpeg/" name="JPEG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/dib/" name="DIB" description="บิตแมปอิสระของอุปกรณ์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/dicom/" name="DICOM" description="การถ่ายภาพและการสื่อสารดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/djvu/" name="DJVU" description="รูปแบบกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/dng/" name="DNG" description="ภาพกล้องดิจิตอล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/emf/" name="EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/emz/" name="EMZ" description="Windows บีบอัด Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/j2k/" name="J2K" description="ภาพบีบอัดเวฟเล็ต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/tiff/" name="TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/tif/" name="TIF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/webp/" name="WEBP" description="รูปภาพเว็บแรสเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/wmz/" name="WMZ" description="สกิน Windows Media Player ที่บีบอัด" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/eps/" name="EPS" description="ภาษา PostScript ที่ห่อหุ้ม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/cdr/" name="CDR" description="วาดภาพเวกเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/cmx/" name="CMX" description="รูปภาพ Corel Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/otg/" name="OTG" description="มาตรฐาน OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/dither/odg/" name="ODG" description="รูปแบบการวาด Apache OpenOffice" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
