﻿---
title: DICOM ลายน้ำรูปภาพพร้อม Python 
weight: 3920
url: /th/python-net/watermark/dicom/ 
lang: th
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: วิธีใช้ Python สำหรับรูปภาพ DICOM และลายน้ำรูปภาพบนเดสก์ท็อปและเว็บแอปพลิเคชัน
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="ใช้ Python สำหรับ DICOM ลายน้ำรูปภาพ" h2="สร้างแอป Python เพื่อใส่ลายน้ำ DICOM รูปภาพและรูปภาพผ่าน Server API" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DICOM" pfName="Aspose.Imaging" subTitlepfName="สำหรับ Python" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="สำหรับ Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/th/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="หน้าแรก API" codeSamplesText="ตัวอย่างโค้ด" liveDemosText="การสาธิตสด" downloadText="ดาวน์โหลด" learnText="เรียนรู้">}}

{{% blocks/products/pf/agp/content h2="วิธีใส่ลายน้ำ DICOM รูปภาพและภาพถ่ายด้วย Python" %}}

การรวมลายน้ำเป็นวิธีที่ดีเยี่ยมสำหรับผู้เขียนในการเพิ่มการมองเห็นแบรนด์ของตนทั่วทั้งพื้นที่อินเทอร์เน็ต เมื่อนำไปใช้กับรูปภาพ ลายน้ำไม่เพียงแต่ทำหน้าที่เป็นตัวระบุแหล่งที่มาหรือผู้ถือลิขสิทธิ์เท่านั้น แต่ยังเป็นเครื่องมือส่งเสริมการขายที่มีประสิทธิภาพสำหรับผู้แต่งหรือแพลตฟอร์มออนไลน์อีกด้วย เนื่องจากลายน้ำ ไม่ว่าจะเป็นชื่อผู้เขียนหรือโลโก้ที่โดดเด่น จะถูกกระจายไปพร้อมกับการทำซ้ำทางดิจิทัลทุกครั้งของรูปภาพ ตัวเลือกลายน้ำประกอบด้วยข้อความในแบบอักษรต่างๆ รอบขอบของภาพ โลโก้แบบกึ่งโปร่งใสจะไม่ขัดขวางการมองเห็นภาพหรือภาพถ่าย หากผู้เขียนหรือผู้ถือลิขสิทธิ์เห็นว่าจำเป็นต้องเน้นชื่อของตน ลายน้ำอาจซ้อนทับรูปภาพบางส่วน หากต้องการเพิ่มลายน้ำลงในรูปภาพ DICOM เราจะใช้ [Aspose.Imaging สำหรับ Python ผ่าน .NET](/imaging/th/python-net) API ซึ่งเป็น API การจัดการรูปภาพและการแปลงที่มีคุณลักษณะหลากหลาย ทรงพลัง และใช้งานง่ายสำหรับแพลตฟอร์ม Python คุณสามารถติดตั้งได้โดยใช้คำสั่งต่อไปนี้จากคำสั่งระบบของคุณ

{{% blocks/products/pf/agp/code-block title="บรรทัดคำสั่งของระบบ" offSpacer="true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการเพิ่มลายน้ำให้กับ DICOM ผ่าน Python" %}}

{{% blocks/products/pf/agp/text %}}

คุณต้องใช้ [aspose-imaging-python-net](https://pypi.org/project/aspose-imaging-python-net/) เพื่อลองใช้เวิร์กโฟลว์ต่อไปนี้ในสภาพแวดล้อมของคุณเอง

{{% /blocks/products/pf/agp/text %}}

+ โหลดไฟล์ DICOM ด้วย Image.Load method
+ สร้างอินสแตนซ์ของกราฟิกจาก Image
+ กำหนดแบบอักษร แปรง และรูปแบบสำหรับข้อความลายน้ำ
+ วาดลายน้ำโดยใช้วิธี Graphics.DrawString
+ บันทึกภาพลงแผ่นดิสก์ในรูปแบบ DICOM

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging สำหรับ Python ได้รับการสนับสนุนในระบบปฏิบัติการหลักทั้งหมด เพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows / Linux พร้อม .NET Core Runtime
- ตัวจัดการแพ็คเกจ Python และ PyPi

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ภาพลายน้ำ DICOM - Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "38cbe119e343dfaeed1ac9975acb46fe" "watermark-dicom-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="เกี่ยวกับ Aspose.Imaging สำหรับ Python API" %}}


Aspose.Imaging API เป็นโซลูชันการประมวลผลรูปภาพเพื่อสร้าง แก้ไข วาดหรือแปลงรูปภาพ (ภาพถ่าย) ภายในแอปพลิเคชัน นำเสนอ: การประมวลผลภาพข้ามแพลตฟอร์ม รวมถึงแต่ไม่จำกัดเพียงการแปลงระหว่างรูปแบบภาพต่างๆ (รวมถึงการประมวลผลภาพแบบหลายหน้าหรือหลายเฟรมแบบเดียวกัน) การปรับเปลี่ยน เช่น การวาด การทำงานกับภาพกราฟิกดั้งเดิม การแปลงภาพ (ปรับขนาด ครอบตัด พลิกและหมุน , ไบนารี, ระดับสีเทา, ปรับ), คุณสมบัติการจัดการภาพขั้นสูง (การกรอง, การแยกสี, การปิดบัง, การเดสก์) และกลยุทธ์การปรับหน่วยความจำให้เหมาะสม เป็นไลบรารีแบบสแตนด์อโลนและไม่ขึ้นกับซอฟต์แวร์ใด ๆ สำหรับการทำงานของรูปภาพ คุณสามารถเพิ่มคุณสมบัติการแปลงรูปภาพประสิทธิภาพสูงด้วย API ดั้งเดิมภายในโปรเจ็กต์ได้อย่างง่ายดาย สิ่งเหล่านี้เป็น API ภายในองค์กรที่เป็นส่วนตัว 100% และอิมเมจได้รับการประมวลผลที่เซิร์ฟเวอร์ของคุณ


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ลายน้ำ DICOM ผ่านแอปออนไลน์" sectionDescription="เพิ่มลายน้ำให้กับเอกสาร DICOM โดยไปที่ [เว็บไซต์ Live Demos](https://products.aspose.app/imaging/watermark) การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไรเลย" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="ไม่ต้องเขียนโค้ดใดๆ" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="เพียงอัปโหลดไฟล์ DICOM ตั้งค่าลายน้ำแล้วกดปุ่ม เพิ่ม" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="รับลิงค์ดาวน์โหลดทันทีสำหรับไฟล์ผลลัพธ์" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="คืออะไร" whatIsFormat2="รูปแบบไฟล์" readMoreFormat="อ่านเพิ่มเติม" >}}
DICOM ย่อมาจาก Digital Imaging and Communications in Medicine และเกี่ยวข้องกับสาขาสารสนเทศทางการแพทย์ DICOM คือการรวมกันของคำจำกัดความรูปแบบไฟล์และโปรโตคอลการสื่อสารเครือข่าย DICOM ใช้ส่วนขยาย .DCM .DCM มีอยู่ในรูปแบบที่แตกต่างกันสองรูปแบบ ได้แก่ รูปแบบ 1.x และรูปแบบ 2.x รูปแบบ DCM 1.x มีให้ใช้งานเพิ่มเติมในสองเวอร์ชันปกติและแบบขยาย DICOM ใช้สำหรับการรวมอุปกรณ์ภาพทางการแพทย์ เช่น เครื่องพิมพ์ เซิร์ฟเวอร์ สแกนเนอร์ ฯลฯ จากผู้จำหน่ายต่างๆ และยังมีข้อมูลประจำตัวของผู้ป่วยแต่ละรายเพื่อความเป็นเอกลักษณ์ ไฟล์ DICOM สามารถแชร์ระหว่างสองฝ่ายได้หากสามารถรับข้อมูลภาพในรูปแบบ DICOM ได้ ส่วนการสื่อสารของ DICOM คือโปรโตคอลเลเยอร์แอปพลิเคชัน และใช้ TCP/IP เพื่อสื่อสารระหว่างเอนทิตี โปรโตคอล HTTP และ HTTPS ใช้สำหรับบริการเว็บของ DICOM เวอร์ชันที่รองรับโดยบริการเว็บคือ 1.0, 1.1, 2 หรือใหม่กว่า
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบลายน้ำอื่น ๆ ที่รองรับ" subTitle="การใช้ Python จะทำให้เราสามารถใส่ลายน้ำรูปแบบต่างๆ ได้อย่างง่ายดาย เช่น" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/bmp/" name="BMP" description="รูปภาพบิตแมป" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/ico/" name="ICO" description="ไอคอน Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/dib/" name="DIB" description="บิตแมปอิสระของอุปกรณ์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/emf/" name="EMF" description="รูปแบบไฟล์ Metafile ที่ปรับปรุงแล้ว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/gif/" name="GIF" description="รูปแบบการแลกเปลี่ยนกราฟิก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/j2k/" name="J2K" description="ภาพบีบอัดเวฟเล็ต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/png/" name="PNG" description="กราฟิกเครือข่ายแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/tiff/" name="TIFF" description="รูปแบบภาพที่ติดแท็ก" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/webp/" name="WEBP" description="รูปภาพเว็บแรสเตอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/th/python-net/watermark/svg/" name="SVG" description="กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
