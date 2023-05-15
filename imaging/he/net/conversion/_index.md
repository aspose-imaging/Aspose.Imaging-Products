
---
title: C# המרת פורמטים של תמונה 
weight: 3920
url: /he/net/conversion/ 
lang: he
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: המר פורמטים פופולריים של תמונה, תמונה, תמונה באמצעות ספריית NET. המר ל-PSD, PDF, GIF, JPG, SVG כולל HTML5 Canvas עם כמה שורות של קוד C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="המרת קבצי תמונה באמצעות C#" h2="המר פורמטים של תמונה, Metafiles, WebP, Svg, Apng לבניית יישומי עיבוד תמונה מתקדמים מבוססי NET חוצה פלטפורמות." downloadText="הורד" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API מאפשר את תכונות עיבוד התמונה והעיבוד המתקדמות עבור מתכנתים. מפתחים יכולים לשלב אותו כדי להמיר תמונות רסטר וקטוריות, כולל תמונות ותמונות ל-PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF ופורמטים אחרים של תמונה . API עוסק לא רק בהמרה של קבצים אלא גם בהמרת תמונות לגווני שחור ולבן ואפור, המרת שכבות תמונת GIF ועוד.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="המרת תמונה למפת סיביות BMP, JPG, PNG" %}}

שימוש ב-C# Image API, המרת פורמט בין היא קלה כמו רק לשנות את הסיומת של הפורמט הרצוי. הנה כמה מקרים גנריים כגון **תמונה ל-bmp**, **תמונה ל-jpg**, **תמונה ל-png** ומפתחים יכולים בקלות לשפר את הפורמט הספציפי שלהם. התהליך הוא טעינת תמונת המקור באמצעות [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). צור אובייקט יעד [אפשרויות פורמט תמונה](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions)עבור כל הגדרות ספציפיות.בסוף קרא] אתשיטת השמירה](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) על ידי העברת קובץ היעד עם אפשרויות הנתיב והשמירה כפרמטר.

{{% blocks/products/pf/feature-page-code h3="קוד C# להמרה בין תמונות" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/apng-to-bmp/" style="padding:15px;">APNG ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/dib-to-bmp/" style="padding:15px;">DIB ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM ל BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/dng-to-bmp/" style="padding:15px;">DNG ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/emf-to-bmp/" style="padding:15px;">EMF ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/eps-to-bmp/" style="padding:15px;">EPS ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/gif-to-bmp/" style="padding:15px;">GIF ל BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="המרת תמונת רסטר ל-PDF" %}}

תהליך המרת תמונות רסטר ל-PDF זהה לזה של המרה בין תמונות, אלא שה-API מספק [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) עבור הגדרות PDF ספציפיות . מתכנתים יכולים לשפר אותו בקלות לצרכים הספציפיים שלהם.

{{% blocks/products/pf/feature-page-code h3="קוד עבור המרת תמונות רסטר ל-PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/apng-to-PDF/" style="padding:15px;">APNG ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/odg-to-PDF/" style="padding:15px;">ODG ל PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/otg-to-PDF/" style="padding:15px;">OTG ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/png-to-PDF/" style="padding:15px;">PNG ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/svg-to-PDF/" style="padding:15px;">SVG ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/eps-to-PDF/" style="padding:15px;">EPS ל PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/gif-to-PDF/" style="padding:15px;">GIF ל PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="המר SVG לתמונות רסטר BMP, PNG, JPG" %}}

תהליך ההמרה של SVG זהה, טען קובץ SVG, השתמש באפשרויות שמירת התמונה הרלוונטיות וקריאה לשיטת השמירה. ממשק API של תמונה מספק [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) להגדרת תמונות PageWidth, PageHeight ורסטר השתמשו במאפיין VectorRasterizationOptions שלהם לאתחול ולקבלת אפשרויות SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="קוד C# עבור תמונות SVG לראסטר" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG ל BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG ל JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/he/net/conversion/SVG-to-png/" style="padding:15px;">SVG ל PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="כל הפורמטים הנתמכים להמרה" %}}
להלן מוצגת רשימה מלאה של פורמטים של תמונה, שתוכל להמיר ל:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/apng/" style="padding:15px;">המר מ APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/bmp/" style="padding:15px;">המר מ BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/dib/" style="padding:15px;">המר מ DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/dicom/" style="padding:15px;">המר מ DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/djvu/" style="padding:15px;">המר מ DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/dng/" style="padding:15px;">המר מ DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/emf/" style="padding:15px;">המר מ EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/emz/" style="padding:15px;">המר מ EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/gif/" style="padding:15px;">המר מ GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/jpeg2000/" style="padding:15px;">המר מ JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/jp2/" style="padding:15px;">המר מ JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/j2k/" style="padding:15px;">המר מ J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/jpg/" style="padding:15px;">המר מ JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/jpeg/" style="padding:15px;">המר מ JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/png/" style="padding:15px;">המר מ PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/tga/" style="padding:15px;">המר מ TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/tif/" style="padding:15px;">המר מ TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/tiff/" style="padding:15px;">המר מ TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/webp/" style="padding:15px;">המר מ WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/wmf/" style="padding:15px;">המר מ WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/wmz/" style="padding:15px;">המר מ WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/svg/" style="padding:15px;">המר מ SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/svgz/" style="padding:15px;">המר מ SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/eps/" style="padding:15px;">המר מ EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/cdr/" style="padding:15px;">המר מ CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/cmx/" style="padding:15px;">המר מ CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/otg/" style="padding:15px;">המר מ OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/odg/" style="padding:15px;">המר מ ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/from/ico/" style="padding:15px;">המר מ ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="כל פורמטי התמונה הנתמכים להמרה" %}}
להלן מוצגת רשימה מלאה של פורמטים של תמונה, שתוכל להמיר מ:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/bmp/" style="padding:15px;">להמיר ל BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/gif/" style="padding:15px;">להמיר ל GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/dicom/" style="padding:15px;">להמיר ל DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/emf/" style="padding:15px;">להמיר ל EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/jpg/" style="padding:15px;">להמיר ל JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/jpeg/" style="padding:15px;">להמיר ל JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/jp2/" style="padding:15px;">להמיר ל JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/j2k/" style="padding:15px;">להמיר ל J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/jpeg2000/" style="padding:15px;">להמיר ל JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/png/" style="padding:15px;">להמיר ל PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/psd/" style="padding:15px;">להמיר ל PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/dxf/" style="padding:15px;">להמיר ל DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/svg/" style="padding:15px;">להמיר ל SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/tiff/" style="padding:15px;">להמיר ל TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/webp/" style="padding:15px;">להמיר ל WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/wmf/" style="padding:15px;">להמיר ל WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/pdf/" style="padding:15px;">להמיר ל PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/html/" style="padding:15px;">להמיר ל HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/emz/" style="padding:15px;">להמיר ל EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/wmz/" style="padding:15px;">להמיר ל WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/tga/" style="padding:15px;">להמיר ל TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/svgz/" style="padding:15px;">להמיר ל SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/canvas/" style="padding:15px;">להמיר ל CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/ico/" style="padding:15px;">להמיר ל ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/he/net/conversion/to/apng/" style="padding:15px;">להמיר ל APNG</a></div>
                </div>
        </div>
    </div>
</div>

