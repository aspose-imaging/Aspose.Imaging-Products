﻿---
title: تحويل AVIF إلى EMF عبر Java 
weight: 3920
url: /ar/java/conversion/avif-to-emf/ 
lang: ar
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: نموذج رمز لـ AVIF إلى EMF تحويل Java. استخدم رمز مثال API لملفات الدُفعة AVIF لتحويل EMF داخل أي تطبيق يستند إلى Web أو Desktop Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="تحويل AVIF إلى EMF عبر Java" h2="قم بتحويل AVIF إلى EMF باستخدام واجهات برمجة تطبيقات Java أصلية دون الحاجة إلى أي محرر صور أو مكتبات تابعة لجهات خارجية." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="Aspose.Imaging" subTitlepfName="لـ Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ar/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/ar/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="واجهة برمجة التطبيقات الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم" overviewText="ملخص" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل AVIF إلى EMF باستخدام Java" %}}

قد يبدو تحويل تنسيقات الملفات بمثابة مهمة روتينية يواجهها مصممو الجرافيك. ومع ذلك، فإن التقليل من أهميتها سيكون خطأً. قد يعتمد تقييم عملك على مدى سرعة وفعالية تعاملك مع هذه المهمة. عادةً، تحتاج الصور الأصلية إلى التحويل إلى تنسيقات أكثر ملاءمة للطباعة أو النشر عبر الإنترنت. إذا كانت الصورة الأصلية مأخوذة من محرر رسومي، فقد تكون بتنسيق متجه. في هذا السيناريو، يجب أن يتم تنقيطه وتحويله إلى تنسيق نقطي لأغراض النشر. لديك خيار حفظ الصورة بتنسيق غير مضغوط للحصول على أفضل جودة أو تحويلها إلى تنسيق مضغوط بدون فقدان البيانات لتقليل حجم الملف. في سياقات معينة، مثل النشر على الويب، يمكنك اختيار التنسيقات المضغوطة التي قد تتعرض للفقدان. تسمح الخوارزميات المصممة خصيصًا لضغط بيانات الصورة بتقليل حجم الملف بشكل كبير مع الحفاظ على جودة الصورة المقبولة. وهذا يسهل تنزيل ملفات الصور بسرعة من الإنترنت. لتحويل AVIF إلى EMF، سنستخدم [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API وهي واجهة برمجة تطبيقات لمعالجة الصور وتحويلها غنية بالميزات وقوية وسهلة الاستخدام لمنصة Java الأساسية. يمكنك تنزيل أحدث إصدار له مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) وتثبيته داخل Maven الخاص بك مشروع قائم على أساس إضافة التكوينات التالية إلى ملف pom.xml.

{{%blocks/products/pf/agp/code-block title ="Repository" offSpacer = "true" %}}

```xml
<repository>
<id> AsposeJavaAPI </id>
<name> Aspose Java API </name>
<url> https://repository.aspose.com/repo/ </url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title = "التبعية" offSpacer = "true" %}}

```xml
<dependency>
<groupId> com.aspose </groupId>
<artifactId>aspose-imaging</artifactId>
<version>version of aspose-imaging API</version>
<classifier>jdk16</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل AVIF إلى EMF عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

يمكن للمطورين بسهولة تحميل وتحويل ملفات AVIF إلى EMF في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملف AVIF بطريقة Image.load
+ إنشاء وتعيين مثيل الفئة الفرعية المطلوبة من ImageOptionsBase (مثل BmpOptions و PngOptions وما إلى ذلك)
+ استدعاء طريقة Image.save
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
        sectionTitle="تطبيق مجاني لتحويل AVIF إلى EMF"
        appName="Conversion"
        extension="AVIF-to-EMF"
        label1="حدد صورة AVIF أو اسحبها وأفلتها"
        label2="اختر التنسيق وانقر فوق الزر تحويل"
        label3="انقر فوق الزر تنزيل لتنزيل صورة EMF"
        checkFreeAppLabel="تحقق من [العروض التوضيحية المباشرة لتحويل AVIF إلى EMF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/AVIF-to-EMF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="تحويل AVIF إلى EMF - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | AVIF">}}
AVIF هو تنسيق ملف صور مفتوح وخالٍ من حقوق الملكية لتخزين الصور أو تسلسلات الصور المضغوطة باستخدام AV1 في تنسيق حاوية HEIF.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر | EMF">}}
يخزن تنسيق ملف التعريف المحسن (EMF) الصور الرسومية بشكل مستقل عن الجهاز. تتكون ملفات تعريف EMF من سجلات متغيرة الطول بترتيب زمني يمكن أن تعرض الصورة المخزنة بعد التحليل على أي جهاز إخراج. يمكن أن تكون هذه السجلات ذات الطول المتغير تعريفات للكائنات المغلقة وأوامر للرسم وخصائص للرسومات ضرورية لتقديم الصورة بدقة. عندما يفتح جهاز ملف تعريف EMF باستخدام بيئة الرسومات الخاصة به ، تظل النسب والأبعاد والألوان وخصائص الرسوم الأخرى للصورة الأصلية كما هي بغض النظر عن النظام الأساسي للجهاز المفتوح.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="باستخدام Java ، يمكن للمرء بسهولة تحويل التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-png/" name="PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-psd/" name="PSD" description="وثيقة فوتوشوب" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-dxf/" name="DXF" description="تنسيق تبادل الرسم ، أو تنسيق تبادل الرسم ،" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-wmf/" name="WMF" description="ملف تعريف Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-pdf/" name="PDF" description="تنسيق المستندات المحمولة (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-html/" name="HTML" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-tga/" name="TGA" description="تارجا جرافيك" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-svgz/" name="SVGZ" description="إصدار مضغوط من ملف Scalable Vector Graphics .SVG" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-canvas/" name="CANVAS" description="قماش HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-ico/" name="ICO" description="رمز Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/conversion/avif-to-bmp/" name="BMP" description="صورة نقطية" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
