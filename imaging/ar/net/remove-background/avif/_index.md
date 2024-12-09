﻿---
title: إزالة الخلفية في مستندات AVIF عبر .NET 
weight: 3920
url: /ar/net/remove-background/avif/ 
lang: ar
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: جرب واجهات برمجة تطبيقات المستندات المحلية الخاصة بنا لإزالة الخلفية في ملفات AVIF على .NET Framework و .NET Core و Windows Application و ASP.NET Web Application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="إزالة الخلفية من AVIF s عبر C#" h2="أنشئ تطبيقات .NET الخاصة بك لإزالة الخلفية من ملفات AVIF باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AVIF" pfName="Aspose.Imaging" subTitlepfName="لـ .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ar/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="صفحة API الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم">}}

{{% blocks/products/pf/agp/content h2="كيفية إزالة الخلفية في ملفات AVIF باستخدام C#" %}}

تتضمن إزالة الخلفية من الصورة عزل الكائنات الأمامية، وهي مهمة تتطلب التعرف على الكائنات. توجد طرق متعددة لتحديد الكائنات داخل الصورة بتنسيق AVIF. بالنسبة للصور البسيطة التي تتميز بخلفية ملونة موحدة، تكفي الطريقة التلقائية. ومع ذلك، بالنسبة للصور التي تحتوي على أشكال متعددة أو مدمجة جزئيًا، يصبح وضع علامات مسبقة على الكائنات ضروريًا. يتضمن ذلك تحديد المناطق المستطيلة وأنواع الكائنات المراد إزالتها. في الحالات المعقدة، تتيح Cloud API الكشف التلقائي عن الكائنات. توفر Cloud API تطبيقًا سحابيًا قادرًا على التعرف على الكائنات داخل الصور، والاستفادة من الخطوط الناتجة لإزالة الخلفية. بعد الإزالة، يمكن تنعيم الحواف التي خلفتها الأشكال لتحسين جودة الصورة. لإزالة الخلفية في ملفات AVIF، سنستخدم [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) واجهة برمجة التطبيقات (API) وهي واجهة برمجة تطبيقات لمعالجة الصور وتحويلها غنية بالميزات وقوية وسهلة الاستخدام لمنصة C#. افتح مدير الحزم [NuGet](https://www.nuget.org/packages/aspose.imaging) ، وابحث عن
 **Aspose.Imaging** وتركيب. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزمة" offSpacer="true" %}}
```cs
PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات إزالة الخلفية من AVIF s عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

أنت بحاجة إلى [aspose.imaging.dll](https://downloads.aspose.com/imaging/net) لتجربة سير العمل التالي في بيئتك الخاصة.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملفات AVIF بطريقة Image.Load
+ إزالة الخلفية ؛
+ حفظ الصورة على القرص بتنسيق Aspose.Imaging المدعوم

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for .NET مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework أو .NET Core أو Windows Application أو ASP.NET Web Application.
- بيئة التطوير مثل Microsoft Visual Studio.
- Aspose.Imaging for .NET المشار إليها في مشروعك.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="إزالة الخلفية في صور AVIF - .NET" offSpacer="" %}}

{{< gist "aspose-com-gists" "c28d7d7f7dff39444751b5724d5ba14a" "remove-change-background-generic-examples.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Imaging .NET API" %}}


Aspose.Imaging API هو حل لمعالجة الصور لإنشاء أو تعديل أو رسم أو تحويل الصور (الصور) داخل التطبيقات. يوفر: معالجة الصور عبر الأنظمة الأساسية ، بما في ذلك على سبيل المثال لا الحصر ، التحويلات بين تنسيقات الصور المختلفة (بما في ذلك معالجة الصور متعددة الصفحات أو متعددة الإطارات) ، والتعديلات مثل الرسم ، والعمل مع الرسوم الأولية ، والتحويلات (تغيير الحجم ، والقص ، والوجه والتدوير ، وثنائي ، وتدرج رمادي ، وضبط) ، وميزات معالجة الصور المتقدمة (الترشيح ، والتردد ، والإخفاء ، والتكديس) ، واستراتيجيات تحسين الذاكرة. إنها مكتبة قائمة بذاتها ولا تعتمد على أي برنامج لعمليات الصور. يمكن للمرء بسهولة إضافة ميزات تحويل الصور عالية الأداء باستخدام واجهات برمجة التطبيقات الأصلية داخل المشاريع. هذه واجهات برمجة تطبيقات داخلية خاصة بنسبة 100٪ وتتم معالجة الصور على خوادمك.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="قم بإزالة الخلفية في AVIF s عبر تطبيق عبر الإنترنت" sectionDescription="قم بإزالة الخلفية في مستندات AVIF من خلال زيارة [Live Demos website](https://products.aspose.app/imaging/remove-background). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="لا حاجة لكتابة أي كود" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="ما عليك سوى تحميل ملفات AVIF والضغط على الزر إزالة الخلفية الآن" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="احصل على الفور على رابط التنزيل للملف الناتج" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر" >}}

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="دعم إزالة تنسيقات الخلفية الأخرى" subTitle="باستخدام C# ، يمكن للمرء بسهولة إزالة الخلفية من التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/bmp/" name="BMP" description="صورة نقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/ico/" name="ICO" description="رمز Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/dib/" name="DIB" description="صورة نقطية مستقلة عن الجهاز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/djvu/" name="DJVU" description="تنسيق الرسومات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/dng/" name="DNG" description="صورة الكاميرا الرقمية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/png/" name="PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/wmf/" name="WMF" description="ملف تعريف Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/tga/" name="TGA" description="تارجا جرافيك" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/eps/" name="EPS" description="لغة PostScript مغلفة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/cdr/" name="CDR" description="ناقلات رسم الصورة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/cmx/" name="CMX" description="كوريل تبادل الصورة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/otg/" name="OTG" description="معيار OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/net/remove-background/odg/" name="ODG" description="تنسيق رسم Apache OpenOffice" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}