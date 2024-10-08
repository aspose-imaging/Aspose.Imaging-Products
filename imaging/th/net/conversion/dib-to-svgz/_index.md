﻿---
title: แปลง DIB เป็น SVGZ ผ่าน C# 
weight: 3920
url: /th/net/conversion/dib-to-svgz/ 
lang: th
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: โค้ดตัวอย่างสำหรับการแปลง DIB ถึง SVGZ C# ใช้โค้ดตัวอย่าง API สำหรับไฟล์แบทช์ DIB เป็นการแปลง SVGZ ภายใน VB.NET, Asp.NET หรือแอปพลิเคชันที่ใช้ .NET
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="แปลง DIB เป็น SVGZ ผ่าน C#" h2="เปลี่ยน DIB เป็น SVGZ โดยใช้ API ดั้งเดิมของ .NET โดยไม่ต้องใช้โปรแกรมแก้ไขรูปภาพหรือไลบรารีของบุคคลที่สาม" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVGZ" pfName="Aspose.Imaging" subTitlepfName="สำหรับ .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="สำหรับ .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/th/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/th/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="หน้าแรกของ API" codeSamplesText="ตัวอย่างโค้ด" liveDemosText="การสาธิตสด" downloadText="ดาวน์โหลด" learnText="เรียนรู้" overviewText="ภาพรวม" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง DIB เป็น SVGZ โดยใช้ C#" %}}

การแปลงรูปแบบไฟล์อาจดูเหมือนเป็นงานประจำที่นักออกแบบกราฟิกต้องเผชิญ แต่การดูถูกความสำคัญของมันอาจเป็นความผิดพลาด การประเมินงานของคุณอาจขึ้นอยู่กับว่าคุณจัดการงานนี้ได้รวดเร็วและมีประสิทธิภาพเพียงใด โดยทั่วไปแล้ว รูปภาพต้นฉบับจำเป็นต้องแปลงเป็นรูปแบบที่เหมาะสำหรับการพิมพ์หรือการเผยแพร่ออนไลน์มากกว่า หากรูปภาพต้นฉบับมาจากโปรแกรมแก้ไขกราฟิก รูปภาพนั้นอาจอยู่ในรูปแบบเวกเตอร์ ในสถานการณ์นี้ จะต้องได้รับการแรสเตอร์และแปลงเป็นรูปแบบแรสเตอร์เพื่อวัตถุประสงค์ในการเผยแพร่ คุณมีทางเลือกในการบันทึกรูปภาพในรูปแบบที่ไม่บีบอัดเพื่อให้ได้คุณภาพที่ดีที่สุด หรือแปลงเป็นรูปแบบการบีบอัดแบบไม่สูญเสียข้อมูลเพื่อลดขนาดไฟล์ ในบางบริบท เช่น การเผยแพร่ทางเว็บ คุณสามารถเลือกรูปแบบการบีบอัดที่สูญเสียข้อมูลได้ อัลกอริธึมที่ออกแบบมาเป็นพิเศษสำหรับการบีบอัดข้อมูลภาพทำให้สามารถลดขนาดไฟล์ลงได้อย่างมาก ขณะเดียวกันก็รักษาคุณภาพของภาพที่ยอมรับได้ ช่วยให้ดาวน์โหลดไฟล์ภาพจากอินเทอร์เน็ตได้อย่างรวดเร็ว ในการแปลง DIB เป็น SVGZ เราจะใช้ [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API ซึ่งเป็น API การจัดการและการแปลงรูปภาพที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่ายสำหรับแพลตฟอร์ม C# เปิด [NuGet](https://www.nuget.org/packages/aspose.imaging) ตัวจัดการแพ็คเกจ ค้นหา
 ** Aspose.Imaging ** และติดตั้ง คุณสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง DIB เป็น SVGZ ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

นักพัฒนาสามารถโหลดและแปลงไฟล์ DIB เป็น SVGZ ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ DIB ด้วย Image.Load method
+ สร้างและตั้งค่าอินสแตนซ์ของคลาสย่อยที่จำเป็นของ ImageOptionsBase (เช่น BmpOptions, PngOptions เป็นต้น)
+ เรียกวิธี Image.Save
+ ส่งเส้นทางไฟล์ด้วยนามสกุล SVGZ และวัตถุของคลาส ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

ก่อนรันโค้ดตัวอย่างการแปลง ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

+ ระบบปฏิบัติการ: Windows หรือ Linux
+ สภาพแวดล้อมการพัฒนา: รองรับ .NET Core 7 และสูงกว่า เช่น Microsoft Visual Studio

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="แอปฟรีเพื่อแปลง DIB เป็น SVGZ"
        appName="Conversion"
        extension="DIB-to-SVGZ"
        label1="เลือกหรือลากและวาง DIB image"
        label2="เลือกรูปแบบแล้วคลิกปุ่มแปลง"
        label3="คลิกปุ่มดาวน์โหลดเพื่อดาวน์โหลด SVGZ ภาพ"
        checkFreeAppLabel="ตรวจสอบ [การสาธิตสดเพื่อแปลง DIB เป็น SVGZ]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/DIB-to-SVGZ)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="แปลง DIB เป็น SVGZ - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "c105a05d95529e2551aa29cd9dc8d8e8" "convert-dib-to-svgz.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="DIB" readMoreLink="https://docs.fileformat.com/image/dib/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม | DIB">}}
ไฟล์ DIB (Device Independent Bitmap) เป็นไฟล์ภาพแรสเตอร์ที่มีโครงสร้างคล้ายกับไฟล์ Bitmap มาตรฐาน (BMP) แต่มีส่วนหัวต่างกัน สามารถเปิดได้ด้วยแอพพลิเคชั่นเกือบทั้งหมดที่สามารถเปิดไฟล์ BMP มาตรฐานบน Windows เช่นเดียวกับ macOS DIB เป็นไฟล์ไบนารีและมีรูปแบบไฟล์ที่ซับซ้อนคล้ายกับ BMP
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVGZ" readMoreLink="https://docs.fileformat.com/image/svgz/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม | SVGZ">}}
ไฟล์ที่มีนามสกุล .svgz คือไฟล์ Scalable Vector Graphics (.SVG) เวอร์ชันบีบอัด มันถูกบีบอัดด้วยการบีบอัด gzip และมีข้อมูลในรูปแบบ XML ไฟล์ SVGZ รองรับความโปร่งใส การไล่ระดับสี ภาพเคลื่อนไหว และตัวกรอง ไฟล์ SVGZ มีขนาดเล็กกว่าเมื่อเปรียบเทียบกับไฟล์ SVG เริ่มต้น และขนาดไฟล์ที่ลดลงนี้ช่วยโอนไฟล์กราฟิกออนไลน์ นักออกแบบกราฟิกสร้างไฟล์ SVGZ โดยใช้เครื่องมือต่างๆ เช่น Adobe Illustrator, Corel PaintShop Pro และอื่นๆ อย่างไรก็ตาม ไฟล์ SVGZ สามารถสร้างได้ด้วยการเปิดใช้งานการบีบอัด GZip ในเซิร์ฟเวอร์ Apache ในขณะที่ส่งข้อมูลภาพออกไป
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="การใช้ C# จะทำให้สามารถแปลงรูปแบบต่างๆ ได้อย่างง่ายดายรวมถึง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-bmp/" name="BMP" description="รูปภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-dicom/" name="DICOM" description="การถ่ายภาพและการสื่อสารดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-emf/" name="EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-jpg/" name="JPG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-jpeg/" name="JPEG" description="กลุ่มผู้เชี่ยวชาญด้านการถ่ายภาพร่วม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-j2k/" name="J2K" description="ภาพบีบอัดเวฟเล็ต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-apng/" name="APNG" description="กราฟิกเครือข่ายแบบพกพาแบบเคลื่อนไหว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-psd/" name="PSD" description="เอกสาร Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-dxf/" name="DXF" description="Drawing Interchange Format หรือ Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-svg/" name="SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-tiff/" name="TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-webp/" name="WEBP" description="รูปภาพเว็บแรสเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-pdf/" name="PDF" description="รูปแบบเอกสารพกพา (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-html/" name="HTML" description="ผ้าใบ HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-emz/" name="EMZ" description="Windows บีบอัด Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-wmz/" name="WMZ" description="สกิน Windows Media Player ที่บีบอัด" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-tga/" name="TGA" description="Targa Graphic" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-svgz/" name="SVGZ" description="เวอร์ชันบีบอัดของไฟล์ Scalable Vector Graphics (.SVG)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-canvas/" name="CANVAS" description="ผ้าใบ HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/net/conversion/dib-to-ico/" name="ICO" description="ไอคอน Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
