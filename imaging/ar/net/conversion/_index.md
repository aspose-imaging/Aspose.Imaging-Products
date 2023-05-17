
---
title: C # تحويل تنسيقات الصور 
weight: 3920
url: /ar/net/conversion/ 
lang: ar
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: قم بتحويل تنسيقات الصور والصور والصور الشائعة عبر مكتبة .NET. قم بالتحويل إلى PSD و PDF و GIF و JPG و SVG بما في ذلك HTML5 Canvas مع بضعة أسطر من كود C #.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل ملفات الصور عبر C #" h2="تحويل تنسيقات الصور ، ملفات التعريف ، WebP ، Svg ، Apng لبناء تطبيقات معالجة الصور المتقدمة عبر الأنظمة الأساسية القائمة على .NET." downloadText="تحميل" >}}

{{% blocks/products/pf/feature-page-summary %}}

تسهل .NET Image API للمبرمجين معالجة الصور المتقدمة وتقديم الميزات. يمكن للمطورين دمجها لتحويل الصور النقطية والمتجهة ، بما في ذلك الصور والصور إلى PSD و PDF و GIF و PNG و DICOM و SVG و JPG و JPEG2000 و APNG و BMP و TIFF و HTML5 CANVAS و WEBP و WMF و EMF وتنسيقات الصور الأخرى . لا تتعامل API مع تحويل الملفات فحسب ، بل تتعامل أيضًا مع تحويل الصور إلى الأسود والأبيض والرمادي ، وتحويل طبقات صور GIF والمزيد.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل الصورة إلى صورة نقطية BMP و JPG و PNG" %}}

باستخدام C # Image API ، يكون تحويل التنسيق البيني سهلاً مثل مجرد تغيير امتداد التنسيق المطلوب. في ما يلي بعض الحالات العامة مثل **image to bmp**، **image to jpg**، **image to png** ويمكن للمطورين تحسين التنسيق الخاص بهم بسهولة. يتم تحميل الصورة المصدر عبر [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). قم بإنشاء   ك ائنالهدف خيارات  تن [image options](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) لأي إعدادات محددة. أخيرًا ، قم باستدعاء [Save Method](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) عن طريق تمرير الملف الهدف مع المسار وخيارات الحفظ كمعامل.

{{% blocks/products/pf/feature-page-code h3="كود C # للتحويل البيني للصور" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/apng-to-bmp/" style="padding:15px;">APNG إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/dib-to-bmp/" style="padding:15px;">DIB إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM إلى BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/dng-to-bmp/" style="padding:15px;">DNG إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/emf-to-bmp/" style="padding:15px;">EMF إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/eps-to-bmp/" style="padding:15px;">EPS إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/gif-to-bmp/" style="padding:15px;">GIF إلى BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="صورة نقطية لتحويل PDF" %}}

عملية تحويل الصور النقطية إلى PDF مماثلة للتحويل البيني للصور ، باستثناء أن واجهة برمجة التطبيقات توفر [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) لإعدادات PDF محددة . يمكن للمبرمجين تحسينه بسهولة لتلبية احتياجاتهم الخاصة.

{{% blocks/products/pf/feature-page-code h3="رمز لتحويل الصور النقطية إلى PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/apng-to-PDF/" style="padding:15px;">APNG إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/odg-to-PDF/" style="padding:15px;">ODG إلى PDF</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/otg-to-PDF/" style="padding:15px;">OTG إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/png-to-PDF/" style="padding:15px;">PNG إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/svg-to-PDF/" style="padding:15px;">SVG إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/eps-to-PDF/" style="padding:15px;">EPS إلى PDF</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/gif-to-PDF/" style="padding:15px;">GIF إلى PDF</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="تحويل SVG إلى صور نقطية BMP و PNG و JPG" %}}

عملية تحويل SVG هي نفسها ، قم بتحميل ملف SVG ، واستخدم خيارات حفظ الصورة ذات الصلة واستدعاء طريقة Save. توفر Image API [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) لتعيين PageWidth و PageHeight والصور النقطية تستخدم خاصية VectorRasterizationOptions الخاصة بها للتهيئة والحصول على خيارات SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="C # رمز لـ SVG إلى صور نقطية" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG إلى BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG إلى JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/ar/net/conversion/SVG-to-png/" style="padding:15px;">SVG إلى PNG</a></p>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="جميع تنسيقات الصور المدعومة للتحويل منا" %}}
فيما يلي قائمة كاملة بتنسيقات الصور التي يمكنك التحويل إليها:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/apng/" style="padding:15px;">تحويل من APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/bmp/" style="padding:15px;">تحويل من BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/dib/" style="padding:15px;">تحويل من DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/dicom/" style="padding:15px;">تحويل من DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/djvu/" style="padding:15px;">تحويل من DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/dng/" style="padding:15px;">تحويل من DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/emf/" style="padding:15px;">تحويل من EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/emz/" style="padding:15px;">تحويل من EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/gif/" style="padding:15px;">تحويل من GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/jpeg2000/" style="padding:15px;">تحويل من JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/jp2/" style="padding:15px;">تحويل من JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/j2k/" style="padding:15px;">تحويل من J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/jpg/" style="padding:15px;">تحويل من JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/jpeg/" style="padding:15px;">تحويل من JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/png/" style="padding:15px;">تحويل من PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/tga/" style="padding:15px;">تحويل من TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/tif/" style="padding:15px;">تحويل من TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/tiff/" style="padding:15px;">تحويل من TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/webp/" style="padding:15px;">تحويل من WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/wmf/" style="padding:15px;">تحويل من WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/wmz/" style="padding:15px;">تحويل من WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/svg/" style="padding:15px;">تحويل من SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/svgz/" style="padding:15px;">تحويل من SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/eps/" style="padding:15px;">تحويل من EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/cdr/" style="padding:15px;">تحويل من CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/cmx/" style="padding:15px;">تحويل من CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/otg/" style="padding:15px;">تحويل من OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/odg/" style="padding:15px;">تحويل من ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/from/ico/" style="padding:15px;">تحويل من ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="جميع تنسيقات الصور المدعومة للتحويل إلى" %}}
فيما يلي قائمة كاملة بتنسيقات الصور التي يمكنك التحويل منها:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/bmp/" style="padding:15px;">حول الى BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/gif/" style="padding:15px;">حول الى GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/dicom/" style="padding:15px;">حول الى DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/emf/" style="padding:15px;">حول الى EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/jpg/" style="padding:15px;">حول الى JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/jpeg/" style="padding:15px;">حول الى JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/jp2/" style="padding:15px;">حول الى JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/j2k/" style="padding:15px;">حول الى J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/jpeg2000/" style="padding:15px;">حول الى JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/png/" style="padding:15px;">حول الى PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/psd/" style="padding:15px;">حول الى PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/dxf/" style="padding:15px;">حول الى DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/svg/" style="padding:15px;">حول الى SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/tiff/" style="padding:15px;">حول الى TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/webp/" style="padding:15px;">حول الى WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/wmf/" style="padding:15px;">حول الى WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/pdf/" style="padding:15px;">حول الى PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/html/" style="padding:15px;">حول الى HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/emz/" style="padding:15px;">حول الى EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/wmz/" style="padding:15px;">حول الى WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/tga/" style="padding:15px;">حول الى TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/svgz/" style="padding:15px;">حول الى SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/canvas/" style="padding:15px;">حول الى CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/ico/" style="padding:15px;">حول الى ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/ar/net/conversion/to/apng/" style="padding:15px;">حول الى APNG</a></div>
                </div>
        </div>
    </div>
</div>

