﻿---
title: تحويل الصور TGA إلى PSD باستخدام Python 
weight: 3920
url: /ar/python-net/conversion/tga-to-psd/ 
lang: ar
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: كيفية استخدام Python لتحويل الصور والصور من TGA إلى PSD على تطبيقات سطح المكتب والويب.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="استخدم Python لتحويل الصور من TGA إلى PSD." h2="إنشاء تطبيقات Python لتحويل الصور والصور TGA إلى PSD عبر واجهات برمجة تطبيقات الخادم" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PSD" pfName="Aspose.Imaging" subTitlepfName="لـ Python" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/ar/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ar/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="واجهة برمجة التطبيقات الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم" overviewText="ملخص" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل TGA إلى PSD الصور والصور باستخدام Python" %}}

يعد تحويل ملفات الصور من تنسيق إلى آخر مهمة شائعة يواجهها كل مصمم جرافيك. لا تؤثر الكفاءة والتميز في تحويل الملفات على سرعة الإنجاز فحسب، بل تلعب أيضًا دورًا حاسمًا في تقييم جودة العمل بشكل عام. وفيما يتعلق بمصادر الصور، فإنها كثيرا ما تتطلب التحويل إلى صيغ بديلة أكثر ملاءمة للطباعة أو التوزيع عبر الإنترنت. من المرجح أن تكون الصورة التي تم إنشاؤها في محرر رسومي بتنسيق متجه. في مثل هذه الحالات، لنشر موقع الويب، يجب أن يخضع لعملية التنقيط ويتم حفظه بتنسيق نقطي. لديك خيار تحويل الصورة بتنسيق غير مضغوط للحصول على جودة فائقة أو حفظها بتنسيق مضغوط بدون فقدان البيانات لتقليل حجم الملف. بالنسبة للسيناريوهات التي يكون فيها تقليل حجم الملف أمرًا إلزاميًا، كما هو الحال في تطبيقات مواقع الويب، هناك إمكانية التحويل إلى تنسيقات ضغط مع فقدان البيانات. يمكن لخوارزميات ضغط البيانات المتخصصة للصور أن تقلل حجم الملف بشكل كبير مع الحفاظ على جودة الصورة المقبولة، مما يضمن تحميل الصور بسرعة. لتحويل الصور والصور من TGA إلى PSD، سوف نقوم بتوظيف [Aspose.Imaging for Python via .NET](/imaging/ar/python-net) API وهي واجهة برمجة تطبيقات غنية بالميزات وقوية وسهلة الاستخدام لمعالجة الصور وتحويلها لمنصة Python. يمكنك تثبيته باستخدام الأمر التالي من أمر النظام الخاص بك.

{{% blocks/products/pf/agp/code-block title = "سطر أوامر النظام" offSpacer = "true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل TGA إلى PSD عبر Python" %}}

{{% blocks/products/pf/agp/text %}}

يمكن للمطورين بسهولة تحميل وتحويل ملفات TGA إلى PSD في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف TGA بطريقة Image.Load
+ إنشاء وتعيين مثيل الفئة الفرعية المطلوبة من ImageOptionsBase (مثل BmpOptions و PngOptions وما إلى ذلك)
+ استدعاء طريقة حفظ الصورة
+ قم بتمرير مسار الملف بامتداد PSD وكائن من فئة ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

قبل تشغيل رمز مثال التحويل ، تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

+ نظام التشغيل: ويندوز أو لينكس.
+ بيئة التطوير: يدعم .NET Core 7 والإصدارات الأحدث، مثل Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="تطبيق مجاني لتحويل TGA إلى PSD"
        appName="Conversion"
        extension="TGA-to-PSD"
        label1="حدد صورة TGA أو اسحبها وأفلتها"
        label2="اختر التنسيق وانقر فوق الزر تحويل"
        label3="انقر فوق الزر تنزيل لتنزيل صورة PSD"
        checkFreeAppLabel="تحقق من [العروض التوضيحية المباشرة لتحويل TGA إلى PSD]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/TGA-to-PSD)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="تحويل TGA إلى PSD - Python" offSpacer="true" %}}

{{< gist "aspose-com-gists" "e1d418ed58a1f4598f259e62914511d4" "convert-image-to-other-format.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="TGA" readMoreLink="https://docs.fileformat.com/image/tga/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | TGA">}}
Truevision TGA ، الذي يشار إليه غالبًا باسم TARGA ، هو تنسيق ملف رسومات نقطية تم إنشاؤه بواسطة Truevision Inc. (الآن جزء من Avid Technology). كان هذا هو التنسيق الأصلي للوحات TARGA و VISTA ، والتي كانت أول بطاقات رسومية لأجهزة الكمبيوتر المتوافقة مع IBM لدعم عرض Highcolor / truecolor.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PSD" readMoreLink="https://docs.fileformat.com/image/psd/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | PSD">}}
يمثل PSD ، Photoshop Document ، تنسيق ملف Adobe Photoshop الأصلي المستخدم لتصميم الرسومات وتطويرها. قد تتضمن ملفات PSD طبقات الصورة وطبقات الضبط وأقنعة الطبقة والتعليقات التوضيحية ومعلومات الملف والكلمات الأساسية والعناصر الأخرى الخاصة بـ Photoshop.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="باستخدام Python ، يمكن للمرء بسهولة تحويل التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-bmp/" name="BMP" description="صورة نقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-png/" name="PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-psd/" name="PSD" description="وثيقة فوتوشوب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-dxf/" name="DXF" description="تنسيق تبادل الرسم ، أو تنسيق تبادل الرسم ،" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-wmf/" name="WMF" description="ملف تعريف Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-pdf/" name="PDF" description="تنسيق المستندات المحمولة (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-html/" name="HTML" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-svgz/" name="SVGZ" description="إصدار مضغوط من ملف Scalable Vector Graphics .SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-canvas/" name="CANVAS" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/python-net/conversion/tga-to-ico/" name="ICO" description="رمز Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
