﻿---
title: تصفية المستندات AVIF عبر Java 
weight: 3920
url: /ar/java/filter/avif/ 
lang: ar
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: جرب واجهات برمجة تطبيقات المستندات المحلية الخاصة بنا لتصفية ملفات AVIF على .NET Framework و .NET Core و Windows Application و ASP.NET Web Application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="تصفية AVIF عبر Java" h2="أنشئ تطبيقات Java الخاصة بك لتصفية ملفات AVIF باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="AVIF" pfName="Aspose.Imaging" subTitlepfName="لـ Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="لـ Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/ar/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="صفحة API الرئيسية" codeSamplesText="عينات التعليمات البرمجية" liveDemosText="العروض التوضيحية الحية" downloadText="تحميل" learnText="يتعلم">}}

{{% blocks/products/pf/agp/content h2="كيفية تصفية الملفات AVIF باستخدام Java" %}}

حتى الصورة الأكثر مثالية يمكن تحسينها بشكل أكبر أو تحويلها إلى عمل فني مختلف تمامًا وفريد ​​من نوعه. قم بتطبيق المرشحات لتحقيق مجموعة واسعة من تأثيرات الصورة. على سبيل المثال، يمكنك زيادة حدة الصورة أو، على العكس من ذلك، إضافة تمويه أو تلطيفها أو إزالة تشويش اللون. تعد المرشحات أيضًا لا تقدر بثمن عندما ترغب في إضفاء التفرد على صورتك. لتحقيق ذلك، قم بتطبيق التأثير المطلوب أو الجمع بين تأثيرات مختلفة. يتيح لك هذا الأسلوب تحسين التدرجات اللونية، وإزالة الضوضاء، وفي نفس الوقت تعزيز حدة حواف الكائنات في الصورة. من أجل تصفية ملفات AVIF، سنستخدم [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API وهي واجهة برمجة تطبيقات لمعالجة الصور وتحويلها غنية بالميزات وقوية وسهلة الاستخدام لمنصة Java الأساسية. يمكنك تنزيل أحدث إصدار له مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) وتثبيته داخل Maven الخاص بك مشروع قائم على أساس إضافة التكوينات التالية إلى ملف pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تصفية AVIF s عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

أنت بحاجة إلى [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) لتجربة سير العمل التالي في بيئتك الخاصة.

{{% /blocks/products/pf/agp/text %}}

+ تحميل ملفات AVIF بطريقة Image.Load
+ تصفية الصور.
+ حفظ الصورة المضغوطة على القرص بتنسيق Aspose.Imaging المدعوم

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for Java مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- تم تثبيت JDK 1.6 أو أعلى.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="تصفية الصور AVIF - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "62fbf25d357f9630abcc20d79d5947b2" "filter-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.Imaging Java API" %}}


Aspose.Imaging API هو حل لمعالجة الصور لإنشاء أو تعديل أو رسم أو تحويل الصور (الصور) داخل التطبيقات. يوفر: معالجة الصور عبر الأنظمة الأساسية ، بما في ذلك على سبيل المثال لا الحصر ، التحويلات بين تنسيقات الصور المختلفة (بما في ذلك معالجة الصور متعددة الصفحات أو متعددة الإطارات) ، والتعديلات مثل الرسم ، والعمل مع الرسوم الأولية ، والتحويلات (تغيير الحجم ، والقص ، والوجه والتدوير ، وثنائي ، وتدرج رمادي ، وضبط) ، وميزات معالجة الصور المتقدمة (الترشيح ، والتردد ، والإخفاء ، والتكديس) ، واستراتيجيات تحسين الذاكرة. إنها مكتبة قائمة بذاتها ولا تعتمد على أي برنامج لعمليات الصور. يمكن للمرء بسهولة إضافة ميزات تحويل الصور عالية الأداء باستخدام واجهات برمجة التطبيقات الأصلية داخل المشاريع. هذه واجهات برمجة تطبيقات داخلية خاصة بنسبة 100٪ وتتم معالجة الصور على خوادمك.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="تصفية AVIF عبر تطبيق عبر الإنترنت" sectionDescription="تصفية مستندات AVIF من خلال زيارة [Live Demos website](https://products.aspose.app/imaging/image-Filter). يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="لا حاجة لكتابة أي كود" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="ما عليك سوى تحميل ملفات AVIF واضغط على الزر منقي" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="احصل على الفور على رابط التنزيل للملف الناتج" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="ما هو" whatIsFormat2="تنسيق الملف" readMoreFormat="اقرأ أكثر" >}}

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات المرشح المدعومة الأخرى" subTitle="باستخدام Java ، يمكن للمرء بسهولة تصفية التنسيقات المختلفة بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/apng/" name="APNG" description="رسومات الشبكة المحمولة المتحركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/bmp/" name="BMP" description="صورة نقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/ico/" name="ICO" description="رمز Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/dib/" name="DIB" description="صورة نقطية مستقلة عن الجهاز" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/dicom/" name="DICOM" description="التصوير الرقمي والاتصالات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/djvu/" name="DJVU" description="تنسيق الرسومات" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/dng/" name="DNG" description="صورة الكاميرا الرقمية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/emf/" name="EMF" description="تنسيق ملف التعريف المحسن" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/emz/" name="EMZ" description="ملف تعريف محسن مضغوط لـ Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/gif/" name="GIF" description="تنسيق التبادل الرسومي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/j2k/" name="J2K" description="صورة مضغوطة Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/png/" name="PNG" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/tiff/" name="TIFF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/tif/" name="TIF" description="تنسيق الصورة الموسومة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/webp/" name="WEBP" description="صورة الويب النقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/wmf/" name="WMF" description="ملف تعريف Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/wmz/" name="WMZ" description="غلاف Windows Media Player المضغوط" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/tga/" name="TGA" description="تارجا جرافيك" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/svg/" name="SVG" description="الرسومات المتجهات قابلة لل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/eps/" name="EPS" description="لغة PostScript مغلفة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/cdr/" name="CDR" description="ناقلات رسم الصورة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/cmx/" name="CMX" description="كوريل تبادل الصورة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/otg/" name="OTG" description="معيار OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/ar/java/filter/odg/" name="ODG" description="تنسيق رسم Apache OpenOffice" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}