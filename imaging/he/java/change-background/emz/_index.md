﻿---
title: שנה רקע במסמכי EMZ באמצעות Java 
weight: 3920
url: /he/java/change-background/emz/ 
lang: he
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: נסה את ממשקי ה-API של מסמכים מקומיים כדי לשנות רקע מקבצי EMZ ביישום Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="שנה רקע ב-EMZ באמצעות Java" h2="בנה יישומי Java משלך כדי לשנות רקע בקבצי EMZ באמצעות ממשקי API בצד השרת." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMZ" pfName="Aspose.Imaging" subTitlepfName="עבור Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="עבור Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/he/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="בית API" codeSamplesText="דוגמאות קוד" liveDemosText="הדגמות חיות" downloadText="הורד" learnText="לִלמוֹד">}}

{{% blocks/products/pf/agp/content h2="כיצד לשנות רקע בקבצים EMZ באמצעות Java" %}}

לעתים קרובות, השגת התמונה האידיאלית דורשת שינוי הרקע. כדי להשיג את אפקט התמונה הרצוי בפורמט EMZ, יש לבודד אובייקטים בחזית משאר התמונה. זיהוי אובייקטים אוטומטי אפשרי אם הרקע אחיד. אם הרקע של התמונה אינו אחיד או הפרדת אובייקטים מאתגרת, מומלץ לסמן מראש את התמונה. זה כרוך בזיהוי אזורים מלבניים בתוך התמונה שבהם שוכנים האובייקטים המיועדים וציון סוגיהם. ניתן לעשות זאת באופן ידני או אוטומטי באמצעות תכונת זיהוי האובייקטים של Cloud API. לאחר בחירת אובייקט והסרת רקע מקורי, ניתן להחיל רקע חדש או ליישם שקיפות. כדי לשנות רקע בקבצים EMZ, נשתמש [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API שהוא עשיר בתכונות, חזק וקל לשימוש למניפולציה והמרה של תמונות עבור פלטפורמת Java. אתה יכול להוריד את הגרסה האחרונה שלו ישירות מ-[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ולהתקין אותה בתוך ה-Maven שלך פרויקט מבוסס על ידי הוספת התצורות הבאות לקובץ pom.xml.

{{% blocks/products/pf/agp/code-block title="מאגר" offSpacer="true" %}}

``` xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="תלות" offSpacer="true" %}}

``` xml
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-imaging</artifactId>
<version>version of aspose-imaging API</version>
<classifier>jdk16</classifier>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="שלבים לשינוי הרקע ב-EMZ באמצעות Java" %}}

{{% blocks/products/pf/agp/text %}}

אתה צריך את [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) כדי לנסות את זרימת העבודה הבאה בסביבה שלך.

{{% /blocks/products/pf/agp/text %}}

+ טען קבצים EMZ בשיטת Image.load
+ שנה רקע;
+ שמור תמונה לדיסק בפורמט הנתמך על ידי Aspose.Imaging

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging עבור Java נתמך בכל מערכות ההפעלה העיקריות. רק ודא שיש לך את התנאים המוקדמים הבאים.

{{% /blocks/products/pf/agp/text %}}

- מותקן JDK 1.6 ומעלה.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="שנה רקע בתמונות EMZ - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="אודות Aspose.Imaging עבור API של Java" %}}


Aspose.Imaging API הוא פתרון לעיבוד תמונה ליצירה, שינוי, ציור או המרת תמונות (תמונות) בתוך יישומים. הוא מציע: עיבוד תמונה חוצה פלטפורמות, כולל אך לא רק המרות בין פורמטים שונים של תמונה (כולל עיבוד תמונה אחיד מרובה עמודים או ריבוי מסגרות), שינויים כגון ציור, עבודה עם פרימיטיבים גרפיים, טרנספורמציות (שינוי גודל, חיתוך, הפוך וסיבוב , בינאריזציה, גווני אפור, התאמה), תכונות מתקדמות של מניפולציה של תמונות (סינון, שיטוט, מיסוך, ביטול הטיה) ואסטרטגיות אופטימיזציה של זיכרון. זוהי ספרייה עצמאית ואינה תלויה בתוכנה כלשהי לפעולות תמונה. אפשר להוסיף בקלות תכונות המרת תמונה בעלות ביצועים גבוהים עם ממשקי API מקוריים בתוך פרויקטים. אלו הם 100% ממשקי API פרטיים מקומיים ותמונות מעובדות בשרתים שלך.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="שנה רקע ב-EMZ באמצעות אפליקציה מקוונת" sectionDescription="שנה רקע במסמכים של EMZ על ידי ביקור ב[אתר ההדגמות החיות] שלנו (https://products.aspose.app/imaging/remove-background). להדגמה החיה יש את היתרונות הבאים" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="אין צורך להוריד או להגדיר שום דבר" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="אין צורך לכתוב שום קוד" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="פשוט העלה את קבצי EMZ שלך ולחץ על הלחצן  שנה רקע עכשיו." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="קבל מיד את קישור ההורדה עבור הקובץ שנוצר" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMZ" readMoreLink="https://docs.fileformat.com/image/emz/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד" >}}
קובץ עם סיומת הקובץ EMZ הוא קובץ תמונה דחוס, המכונה באופן ספציפי יותר קובץ Windows Compressed Enhanced Metafile
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="נתמכים אחרים שנה פורמטי רקע" subTitle="באמצעות Java, אפשר לשנות בקלות רקע בפורמטים שונים כולל." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/apng/" name="APNG" description="גרפיקת רשת ניידת מונפשת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/bmp/" name="BMP" description="תמונת מפת סיביות" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/ico/" name="ICO" description="סמל של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/jpg/" name="JPG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/dib/" name="DIB" description="מפת סיביות בלתי תלויה בהתקן" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/dicom/" name="DICOM" description="הדמיה דיגיטלית ותקשורת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/djvu/" name="DJVU" description="פורמט גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/dng/" name="DNG" description="תמונת מצלמה דיגיטלית" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/emf/" name="EMF" description="פורמט Metafile משופר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/gif/" name="GIF" description="פורמט מחלף גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/j2k/" name="J2K" description="תמונה דחוסה של Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/png/" name="PNG" description="גרפיקת רשת ניידת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/tiff/" name="TIFF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/webp/" name="WEBP" description="תמונה ברשת רסטר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/wmz/" name="WMZ" description="עור דחוס של Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/tga/" name="TGA" description="טארגה גרפיקה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/svg/" name="SVG" description="גרפיקה וקטורית ניתנת להרחבה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/eps/" name="EPS" description="שפת PostScript מובלעת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/cdr/" name="CDR" description="תמונה של ציור וקטור" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/cmx/" name="CMX" description="תמונת Corel Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/otg/" name="OTG" description="OpenDocument Standard" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/odg/" name="ODG" description="Apache OpenOffice Draw Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/change-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
