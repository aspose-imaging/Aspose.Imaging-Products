﻿---
title: تحويل AVIF إلى BMP عبر C# 
weight: 3920
url: /ar/net/conversion/avif-to-bmp/ 
lang: ar
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: نموذج رمز لـ AVIF لتحويل BMP C#. استخدم رمز مثال API لملفات الدُفعات AVIF لتحويل BMP داخل VB.NET أو Asp.NET أو أي تطبيق مستند إلى .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="تحويل AVIF إلى BMP عبر C#" h2="قم بتحويل AVIF إلى BMP باستخدام واجهات برمجة تطبيقات .NET أصلية دون الحاجة إلى أي محرر صور أو مكتبات تابعة لجهات خارجية." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="Aspose.Imaging" subTitlepfName="لـ .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ar/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ar/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="واجهة برمجة التطبيقات الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم" overviewText="ملخص" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل AVIF إلى BMP باستخدام C#" %}}

قد يبدو تحويل تنسيقات الملفات بمثابة مهمة روتينية يواجهها مصممو الجرافيك. ومع ذلك، فإن التقليل من أهميتها سيكون خطأً. قد يعتمد تقييم عملك على مدى سرعة وفعالية تعاملك مع هذه المهمة. عادةً، تحتاج الصور الأصلية إلى التحويل إلى تنسيقات أكثر ملاءمة للطباعة أو النشر عبر الإنترنت. إذا كانت الصورة الأصلية مأخوذة من محرر رسومي، فقد تكون بتنسيق متجه. في هذا السيناريو، يجب أن يتم تنقيطه وتحويله إلى تنسيق نقطي لأغراض النشر. لديك خيار حفظ الصورة بتنسيق غير مضغوط للحصول على أفضل جودة أو تحويلها إلى تنسيق مضغوط بدون فقدان البيانات لتقليل حجم الملف. في سياقات معينة، مثل النشر على الويب، يمكنك اختيار التنسيقات المضغوطة التي قد تتعرض للفقدان. تسمح الخوارزميات المصممة خصيصًا لضغط بيانات الصورة بتقليل حجم الملف بشكل كبير مع الحفاظ على جودة الصورة المقبولة. وهذا يسهل تنزيل ملفات الصور بسرعة من الإنترنت. لتحويل AVIF إلى BMP، سنستخدم [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) واجهة برمجة التطبيقات (API) وهي واجهة برمجة تطبيقات لمعالجة الصور وتحويلها غنية بالميزات وقوية وسهلة الاستخدام لمنصة C#. افتح مدير الحزم [NuGet](https://www.nuget.org/packages/aspose.imaging) ، وابحث عن
 **Aspose.Imaging** وتركيب. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزمة" offSpacer="true" %}}
```cs
PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل AVIF إلى BMP عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

يمكن للمطورين بسهولة تحميل وتحويل ملفات AVIF إلى BMP في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف AVIF بطريقة Image.Load
+ إنشاء وتعيين مثيل الفئة الفرعية المطلوبة من ImageOptionsBase (مثل BmpOptions و PngOptions وما إلى ذلك)
+ استدعاء طريقة حفظ الصورة
+ قم بتمرير مسار الملف بامتداد BMP وكائن من فئة ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

قبل تشغيل رمز مثال التحويل ، تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

+ نظام التشغيل: ويندوز أو لينكس.
+ بيئة التطوير: يدعم .NET Core 7 والإصدارات الأحدث، مثل Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="تطبيق مجاني لتحويل AVIF إلى BMP"
        appName="Conversion"
        extension="AVIF-to-BMP"
        label1="حدد صورة AVIF أو اسحبها وأفلتها"
        label2="اختر التنسيق وانقر فوق الزر تحويل"
        label3="انقر فوق الزر تنزيل لتنزيل صورة BMP"
        checkFreeAppLabel="تحقق من [العروض التوضيحية المباشرة لتحويل AVIF إلى BMP]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/AVIF-to-BMP)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="تحويل AVIF إلى BMP - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "0967b399090c5471f82f46f88b2c0626" "convert-avif-to-bmp.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | AVIF">}}
AVIF هو تنسيق ملف صور مفتوح وخالٍ من حقوق الملكية لتخزين الصور أو تسلسلات الصور المضغوطة باستخدام AV1 في تنسيق حاوية HEIF.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="BMP" readMoreLink="https://docs.fileformat.com/image/bmp/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | BMP">}}
الملفات ذات الامتداد .BMP تمثل ملفات الصور النقطية المستخدمة لتخزين الصور الرقمية للصور النقطية. هذه الصور مستقلة عن محول الرسومات وتسمى أيضًا تنسيق ملف الصورة النقطية المستقلة عن الجهاز (DIB). يخدم هذا الاستقلال غرض فتح الملف على منصات متعددة مثل Microsoft Windows و Mac. يمكن لملف BMP تخزين البيانات كصور رقمية ثنائية الأبعاد بتنسيق أحادي اللون بالإضافة إلى تنسيق الألوان بأعماق ألوان مختلفة.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="باستخدام C# ، يمكن للمرء بسهولة تحويل التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-png/" name="PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-psd/" name="PSD" description="وثيقة فوتوشوب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-dxf/" name="DXF" description="تنسيق تبادل الرسم ، أو تنسيق تبادل الرسم ،" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-wmf/" name="WMF" description="ملف تعريف Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-pdf/" name="PDF" description="تنسيق المستندات المحمولة (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-html/" name="HTML" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-tga/" name="TGA" description="تارجا جرافيك" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-svgz/" name="SVGZ" description="إصدار مضغوط من ملف Scalable Vector Graphics .SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-canvas/" name="CANVAS" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-ico/" name="ICO" description="رمز Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/avif-to-bmp/" name="BMP" description="صورة نقطية" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
