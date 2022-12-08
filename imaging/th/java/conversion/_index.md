
---
title: การแปลงรูปแบบรูปภาพ Java 
weight: 3920
url: /th/java/conversion 
lang: th
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: แปลงไฟล์รูปภาพ รูปภาพ ไฟล์รูปภาพยอดนิยมผ่านไลบรารี Java แปลงเป็น PDF, GIF, PSD, JPG, Dxf, SVG รวมถึง HTML5 Canvas
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="การแปลงไฟล์รูปภาพผ่าน Java" h2="แปลงรูปแบบรูปภาพ, Metafiles, WebP, SVG, APNG เพื่อสร้างแอปพลิเคชัน Java ข้ามแพลตฟอร์ม" downloadText="ดาวน์โหลด" >}}

{{% blocks/products/pf/feature-page-summary %}}

สำหรับแอปพลิเคชันการประมวลผลภาพขั้นสูง Java Image API ช่วยให้นักพัฒนาสามารถสร้าง โหลด จัดการ หรือแสดงภาพโดยไม่ต้องมีโปรแกรมแก้ไขภาพใดๆ มันสามารถแปลงภาพเวกเตอร์และแรสเตอร์ รวมถึงภาพถ่ายและรูปภาพเป็น PSD, PDF, GIF, PNG, DICOM, DXF, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WMF, EMF, WEBP และรูปแบบภาพอื่นๆ API ให้วิธีการไบนารีและการปรับสเกลสีเทาในการแปลงภาพเป็นขาวดำและสีเทา เช่นเดียวกับการแปลงกราฟิกเอกสารแบบเปิด ระบบสี RGB เป็น CMYK และอื่นๆ

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="การแปลงไฟล์รูปภาพระหว่างกัน" %}}

การใช้ Java Image API การแปลง Inter ทำได้ง่ายและนักพัฒนาต้องเขียนโค้ดเพียงไม่กี่บรรทัดสำหรับกรณีใด ๆ รวมถึง **image to jpg**, **image to bmp**, **image to png** เป็นต้น API ให้ [Image.load](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#load-java.lang.String-) เพื่อโหลดภาพ ระบุตัวเลือกรูปภาพที่เกี่ยวข้องจาก [ImageOptionsBase](https://apireference.aspose.com/imaging/java/com.aspose.imaging/ImageOptionsBase) และเรียกวิธีการบันทึกด้วยไฟล์รูปภาพที่ส่งออกและตัวเลือกเป็นพารามิเตอร์

{{% blocks/products/pf/feature-page-code h3="รหัส Java สำหรับการแปลงระหว่างรูปภาพ" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "inter-conversion-of-image-files.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/apng-to-bmp/">APNG ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/cdr-to-bmp/">CDR ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/dib-to-bmp/">DIB ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/dicom-to-bmp/">DICOM ถึง BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/djvu-to-bmp/">DJVU ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/dng-to-bmp/">DNG ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/emf-to-bmp/">EMF ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/emz-to-bmp/">EMZ ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/eps-to-bmp/">EPS ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/gif-to-bmp/">GIF ถึง BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="ภาพแรสเตอร์เป็นการแปลง PSD" %}}

ขั้นตอนการแปลงภาพแรสเตอร์เป็น PSD จะเหมือนกับการแปลงระหว่างภาพ ยกเว้นว่า API จะให้ [PsdOptions](https://apireference.aspose.com/imaging/java/com.aspose.imaging.imageoptions/PsdOptions) เฉพาะทาง API การตั้งค่า PSD โปรแกรมเมอร์สามารถปรับปรุงได้อย่างง่ายดายสำหรับความต้องการเฉพาะของพวกเขา

{{% blocks/products/pf/feature-page-code h3="รหัส Java สำหรับรูปภาพแรสเตอร์เป็นการแปลง PSD" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "raster-images-to-psd-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/apng-to-PSD/">APNG ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/jpeg-to-PSD/">JPEG ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/bmp-to-PSD/">BMP ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/odg-to-PSD/">ODG ถึง PSD</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/otg-to-PSD/">OTG ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/png-to-PSD/">PNG ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/svg-to-PSD/">SVG ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/emz-to-PSD/">EMZ ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/eps-to-PSD/">EPS ถึง PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/gif-to-PSD/">GIF ถึง PSD</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="แปลง Corel Draw CDR เป็นรูปภาพ" %}}

ขั้นตอนการแปลงของ CDR เกือบจะเหมือนกัน โหลดไฟล์ CDR ใช้ตัวเลือกการบันทึกรูปภาพที่เกี่ยวข้อง และเรียกวิธีการบันทึก Image API มี [VectorRasterizationOptions](https://apireference.aspose.com/imaging/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions) สำหรับการตั้งค่าพารามิเตอร์ที่จำเป็น และตัวเลือกการแรสเตอร์เหล่านี้สามารถกำหนดตัวเลือกรูปภาพที่จำเป็นสำหรับการตั้งค่าได้ Fianlly เรียกวิธีการบันทึก 

{{% blocks/products/pf/feature-page-code h3="รหัส Java สำหรับ CDR เป็นรูปภาพ" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "convert-cdr-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/CDR-to-bmp/">CDR ถึง BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/CDR-to-jpeg/">CDR ถึง JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/th/java/conversion/CDR-to-png/">CDR ถึง PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="รูปแบบที่รองรับทั้งหมดที่จะแปลงจาก" %}}
ด้านล่างแสดงรายการรูปแบบทั้งหมดที่คุณสามารถแปลงจาก:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/apng" >แปลงจาก APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/bmp" >แปลงจาก BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/dib" >แปลงจาก DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/dicom" >แปลงจาก DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/djvu" >แปลงจาก DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/dng" >แปลงจาก DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/emf" >แปลงจาก EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/emz" >แปลงจาก EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/gif" >แปลงจาก GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/jpeg2000" >แปลงจาก JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/jp2" >แปลงจาก JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/j2k" >แปลงจาก J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/jpg" >แปลงจาก JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/jpeg" >แปลงจาก JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/png" >แปลงจาก PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/tga" >แปลงจาก TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/tif" >แปลงจาก TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/tiff" >แปลงจาก TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/webp" >แปลงจาก WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/wmf" >แปลงจาก WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/wmz" >แปลงจาก WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/svg" >แปลงจาก SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/svgz" >แปลงจาก SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/eps" >แปลงจาก EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/cdr" >แปลงจาก CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/cmx" >แปลงจาก CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/otg" >แปลงจาก OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/odg" >แปลงจาก ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/from/ico" >แปลงจาก ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="รูปแบบที่รองรับทั้งหมดที่จะแปลงเป็น" %}}
ด้านล่างแสดงรายการรูปแบบทั้งหมดที่คุณสามารถแปลงเป็น:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/bmp" >เปลี่ยนเป็น BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/gif" >เปลี่ยนเป็น GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/dicom" >เปลี่ยนเป็น DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/emf" >เปลี่ยนเป็น EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/jpg" >เปลี่ยนเป็น JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/jpeg" >เปลี่ยนเป็น JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/jp2" >เปลี่ยนเป็น JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/j2k" >เปลี่ยนเป็น J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/jpeg2000" >เปลี่ยนเป็น JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/png" >เปลี่ยนเป็น PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/psd" >เปลี่ยนเป็น PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/dxf" >เปลี่ยนเป็น DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/svg" >เปลี่ยนเป็น SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/tiff" >เปลี่ยนเป็น TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/webp" >เปลี่ยนเป็น WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/wmf" >เปลี่ยนเป็น WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/pdf" >เปลี่ยนเป็น PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/html" >เปลี่ยนเป็น HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/emz" >เปลี่ยนเป็น EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/wmz" >เปลี่ยนเป็น WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/tga" >เปลี่ยนเป็น TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/svgz" >เปลี่ยนเป็น SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/canvas" >เปลี่ยนเป็น CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/ico" >เปลี่ยนเป็น ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/th/java/conversion/to/apng" >เปลี่ยนเป็น APNG</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

