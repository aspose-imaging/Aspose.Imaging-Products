﻿---
title: تحويل PNG إلى EMF عبر C# 
weight: 3920
url: /ar/net/conversion/png-to-emf/ 
lang: ar
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: نموذج رمز لـ PNG لتحويل EMF C#. استخدم رمز مثال API لملفات الدُفعات PNG لتحويل EMF داخل VB.NET أو Asp.NET أو أي تطبيق مستند إلى .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="تحويل PNG إلى EMF عبر C#" h2="قم بتحويل PNG إلى EMF باستخدام واجهات برمجة تطبيقات .NET أصلية دون الحاجة إلى أي محرر صور أو مكتبات تابعة لجهات خارجية." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="Aspose.Imaging" subTitlepfName="لـ .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ar/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ar/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="واجهة برمجة التطبيقات الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم" overviewText="ملخص" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل PNG إلى EMF باستخدام C#" %}}

قد يبدو تحويل تنسيقات الملفات بمثابة مهمة روتينية يواجهها مصممو الجرافيك. ومع ذلك، فإن التقليل من أهميتها سيكون خطأً. قد يعتمد تقييم عملك على مدى سرعة وفعالية تعاملك مع هذه المهمة. عادةً، تحتاج الصور الأصلية إلى التحويل إلى تنسيقات أكثر ملاءمة للطباعة أو النشر عبر الإنترنت. إذا كانت الصورة الأصلية مأخوذة من محرر رسومي، فقد تكون بتنسيق متجه. في هذا السيناريو، يجب أن يتم تنقيطه وتحويله إلى تنسيق نقطي لأغراض النشر. لديك خيار حفظ الصورة بتنسيق غير مضغوط للحصول على أفضل جودة أو تحويلها إلى تنسيق مضغوط بدون فقدان البيانات لتقليل حجم الملف. في سياقات معينة، مثل النشر على الويب، يمكنك اختيار التنسيقات المضغوطة التي قد تتعرض للفقدان. تسمح الخوارزميات المصممة خصيصًا لضغط بيانات الصورة بتقليل حجم الملف بشكل كبير مع الحفاظ على جودة الصورة المقبولة. وهذا يسهل تنزيل ملفات الصور بسرعة من الإنترنت. لتحويل PNG إلى EMF، سنستخدم [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) واجهة برمجة التطبيقات (API) وهي واجهة برمجة تطبيقات لمعالجة الصور وتحويلها غنية بالميزات وقوية وسهلة الاستخدام لمنصة C#. افتح مدير الحزم [NuGet](https://www.nuget.org/packages/aspose.imaging) ، وابحث عن
 **Aspose.Imaging** وتركيب. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزمة" offSpacer="true" %}}
```cs
PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل PNG إلى EMF عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

يمكن للمطورين بسهولة تحميل وتحويل ملفات PNG إلى EMF في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف PNG بطريقة Image.Load
+ إنشاء وتعيين مثيل الفئة الفرعية المطلوبة من ImageOptionsBase (مثل BmpOptions و PngOptions وما إلى ذلك)
+ استدعاء طريقة حفظ الصورة
+ قم بتمرير مسار الملف بامتداد EMF وكائن من فئة ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

قبل تشغيل رمز مثال التحويل ، تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

+ نظام التشغيل: ويندوز أو لينكس.
+ بيئة التطوير: يدعم .NET Core 7 والإصدارات الأحدث، مثل Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="تطبيق مجاني لتحويل PNG إلى EMF"
        appName="Conversion"
        extension="PNG-to-EMF"
        label1="حدد صورة PNG أو اسحبها وأفلتها"
        label2="اختر التنسيق وانقر فوق الزر تحويل"
        label3="انقر فوق الزر تنزيل لتنزيل صورة EMF"
        checkFreeAppLabel="تحقق من [العروض التوضيحية المباشرة لتحويل PNG إلى EMF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/PNG-to-EMF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="تحويل PNG إلى EMF - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "6013edc0c1b050c2c0bc2e34da7f3263" "convert-png-to-emf.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | PNG">}}
يشير PNG ، Portable Network Graphics ، إلى نوع من تنسيق ملف الصور النقطية الذي يستخدم ضغطًا بلا فقدان. تم إنشاء تنسيق الملف هذا كبديل لتنسيق تبادل الرسومات (GIF) وليس له قيود على حقوق النشر. ومع ذلك ، لا يدعم تنسيق ملف PNG الرسوم المتحركة. يدعم تنسيق ملف PNG ضغط الصور بدون فقدان مما يجعله شائعًا بين مستخدميه. مع مرور الوقت ، تطورت PNG كواحدة من أكثر تنسيقات ملفات الصور استخدامًا. تدعم جميع أنظمة التشغيل تقريبًا فتح ملفات PNG. على سبيل المثال ، يمتلك عارض Microsoft Windows القدرة على فتح ملفات PNG لأن نظام التشغيل لديه افتراضيًا الدعم المتاح كجزء من التثبيت.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | EMF">}}
يخزن تنسيق ملف التعريف المحسن (EMF) الصور الرسومية بشكل مستقل عن الجهاز. تتكون ملفات تعريف EMF من سجلات متغيرة الطول بترتيب زمني يمكن أن تعرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. يمكن أن تكون هذه السجلات ذات الطول المتغير تعريفات للكائنات المغلقة وأوامر للرسم وخصائص للرسومات ضرورية لتقديم الصورة بدقة. عندما يفتح جهاز ملف تعريف EMF باستخدام بيئة الرسومات الخاصة به ، تظل النسب والأبعاد والألوان وخصائص الرسوم الأخرى للصورة الأصلية كما هي بغض النظر عن النظام الأساسي للجهاز المفتوح.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="باستخدام C# ، يمكن للمرء بسهولة تحويل التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-bmp/" name="BMP" description="صورة نقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-psd/" name="PSD" description="وثيقة فوتوشوب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-dxf/" name="DXF" description="تنسيق تبادل الرسم ، أو تنسيق تبادل الرسم ،" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-wmf/" name="WMF" description="ملف تعريف Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-pdf/" name="PDF" description="تنسيق المستندات المحمولة (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-html/" name="HTML" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-tga/" name="TGA" description="تارجا جرافيك" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-svgz/" name="SVGZ" description="إصدار مضغوط من ملف Scalable Vector Graphics .SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-canvas/" name="CANVAS" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/conversion/png-to-ico/" name="ICO" description="رمز Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
