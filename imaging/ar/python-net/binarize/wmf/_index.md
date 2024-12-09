﻿---
title: WMF ثنائية الصور باستخدام Python 
weight: 3920
url: /ar/python-net/binarize/wmf/ 
lang: ar
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: كيفية استخدام Python للصور WMF وثنائية الصور على تطبيقات سطح المكتب والويب.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="استخدم Python لتنسيق الصور الثنائية WMF." h2="قم بإنشاء تطبيقات Python لدمج الصور والصور WMF عبر واجهات برمجة تطبيقات الخادم" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="WMF" pfName="Aspose.Imaging" subTitlepfName="لـ Python" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/ar/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="صفحة API الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم">}}

{{% blocks/products/pf/agp/content h2="كيفية ثنائية الصور والصور WMF باستخدام Python" %}}

كان إدخال التصوير الفوتوغرافي الملون بمثابة تحول محوري في مجال التصوير الفوتوغرافي. ومع ذلك، فإن جاذبية الصورة الكلاسيكية بالأبيض والأسود لا تزال قائمة. على الرغم من انتشار الكاميرات الملونة، لا يزال العديد من الأفراد يختارون تحويل صورهم إلى الأبيض والأسود. يتم تحقيق هذا التحويل عادةً من خلال عملية التحويل الثنائي، حيث يتم استبدال كل بكسل بقيمة ثنائية: "0" للأبيض و"1" للأسود. غالبًا ما تُستخدم الصور بالأبيض والأسود لأكثر من مجرد أغراض فنية، حيث تجد تطبيقًا عمليًا في سيناريوهات مثل طباعة الرسوم التوضيحية في منشورات مثل الكتب والصحف. ضمن مكتبة الرسومات Python، لديك القدرة على تعيين حد سطوع البكسل. تفترض البكسلات الموجودة أسفل هذه العتبة اللون الأسود، بينما تكتسب البكسلات الموجودة فوقها اللون الأبيض. تتوفر أيضًا تقنية الثنائية التكيفية، مع الأخذ في الاعتبار قيم البكسل المحيطة لإنشاء انتقالات سلسة بين حدود الألوان في الصورة بالأبيض والأسود الناتجة. لتنسيق ملفات WMF الثنائية، سوف نستخدمها [Aspose.Imaging for Python via .NET](/imaging/ar/python-net) API وهي واجهة برمجة تطبيقات غنية بالميزات وقوية وسهلة الاستخدام لمعالجة الصور وتحويلها لمنصة Python. يمكنك تثبيته باستخدام الأمر التالي من أمر النظام الخاص بك.

{{% blocks/products/pf/agp/code-block title = "سطر أوامر النظام" offSpacer = "true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات لثنائي WMF s عبر Python" %}}

{{% blocks/products/pf/agp/text %}}

أنت بحاجة إلى [aspose-imaging-python-net](https://pypi.org/project/aspose-imaging-python-net/) لتجربة سير العمل التالي في بيئتك الخاصة.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملفات WMF بطريقة Image.Load
+ ثنائيات الصور.
+ حفظ الصورة المضغوطة على القرص بتنسيق Aspose.Imaging المدعوم

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for Python مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows / Linux مع .NET Core Runtime.
- مدير حزم Python و PyPi.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ثنائية WMF الصور - Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "3fa6b0222e82664ed1216a1a2f5d3663" "binarize-images.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Imaging Python API" %}}


Aspose.Imaging API هو حل لمعالجة الصور لإنشاء أو تعديل أو رسم أو تحويل الصور (الصور) داخل التطبيقات. يوفر: معالجة الصور عبر الأنظمة الأساسية ، بما في ذلك على سبيل المثال لا الحصر ، التحويلات بين تنسيقات الصور المختلفة (بما في ذلك معالجة الصور متعددة الصفحات أو متعددة الإطارات) ، والتعديلات مثل الرسم ، والعمل مع الرسوم الأولية ، والتحويلات (تغيير الحجم ، والقص ، والوجه والتدوير ، وثنائي ، وتدرج رمادي ، وضبط) ، وميزات معالجة الصور المتقدمة (الترشيح ، والتردد ، والإخفاء ، والتكديس) ، واستراتيجيات تحسين الذاكرة. إنها مكتبة قائمة بذاتها ولا تعتمد على أي برنامج لعمليات الصور. يمكن للمرء بسهولة إضافة ميزات تحويل الصور عالية الأداء باستخدام واجهات برمجة التطبيقات الأصلية داخل المشاريع. هذه واجهات برمجة تطبيقات داخلية خاصة بنسبة 100٪ وتتم معالجة الصور على خوادمك.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="قم بترميز WMF ثنائياً عبر تطبيق عبر الإنترنت" sectionDescription="قم بترجمة مستندات WMF بشكل ثنائي من خلال زيارة [Live Demos website](https://products.aspose.app/imaging/image-Binarize). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="لا حاجة لكتابة أي كود" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="فقط قم بتحميل ملفات WMF واضغط على الزر الثنائي" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="احصل على الفور على رابط التنزيل للملف الناتج" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WMF" readMoreLink="https://docs.fileformat.com/image/wmf/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر" >}}
تمثل الملفات ذات الامتداد WMF Microsoft Windows Metafile (WMF) لتخزين بيانات الصور المتجهة وكذلك الصور النقطية. لكي تكون أكثر دقة ، تنتمي WMF إلى فئة تنسيق ملف متجه لتنسيقات ملفات الرسومات المستقلة عن الجهاز. تستخدم واجهة جهاز Windows الرسومية (GDI) الوظائف المخزنة في ملف WMF لعرض صورة على الشاشة. تم نشر إصدار محسن أكثر من WMF ، والمعروف باسم Enhanced Meta Files (EMF) ، في وقت لاحق مما يجعل التنسيق أكثر ثراءً بالميزات. من الناحية العملية ، تشبه WMF SVG.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات ثنائية أخرى مدعومة" subTitle="باستخدام Python ، يمكن للمرء بسهولة إنشاء ثنائيات تنسيقات مختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/bmp/" name="BMP" description="صورة نقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/ico/" name="ICO" description="رمز Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/dib/" name="DIB" description="صورة نقطية مستقلة عن الجهاز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/djvu/" name="DJVU" description="تنسيق الرسومات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/dng/" name="DNG" description="صورة الكاميرا الرقمية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/png/" name="PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/tif/" name="TIF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/tga/" name="TGA" description="تارجا جرافيك" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/eps/" name="EPS" description="لغة PostScript مغلفة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/cdr/" name="CDR" description="ناقلات رسم الصورة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/cmx/" name="CMX" description="كوريل تبادل الصورة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/otg/" name="OTG" description="معيار OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/odg/" name="ODG" description="تنسيق رسم Apache OpenOffice" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/binarize/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}