﻿---
title: מסמך סימן מים JP2 באמצעות Java 
weight: 3920
url: /he/java/watermark/jp2/ 
lang: he
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: קוד המרת Java לדוגמה עבור פורמט JP2 לקובץ . השתמש בקוד לדוגמה זה כדי להמיר את JP2 ל- בתוך כל יישום מבוסס Java אינטרנט או שולחני.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="הוסף סימן מים של טקסט ל-JP2 באמצעות Java" h2="בנה יישומי Java משלך לסימן מים של קבצי JP2 באמצעות ממשקי API בצד השרת." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JP2" pfName="Aspose.Imaging" subTitlepfName="עבור Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="עבור Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/he/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="בית API" codeSamplesText="דוגמאות קוד" liveDemosText="הדגמות חיות" downloadText="הורד" learnText="לִלמוֹד">}}

{{% blocks/products/pf/agp/content h2="כיצד לסמן מים בקובץ JP2 באמצעות Java" %}}

סימן מים הוא כלי חיוני לסופרים המחפשים חשיפה מקסימלית לעבודתם באינטרנט. הצבת סימן מים על תמונה משמשת לא רק לזיהוי המקור או בעל זכויות היוצרים שלה אלא גם לקידום היוצר שלה. הסיבה לכך היא שהחתימה המכילה את שם המחבר או את שם המשאב האינטרנטי מופצת לצד עותק דיגיטלי של התמונה. סימני מים יכולים ללבוש צורה של טקסט עם מגוון רחב של גופנים וניתן למקם אותם בקצה התמונה. כאשר סימן המים שקוף, הוא אינו משבש את הצפייה. עם זאת, אם המחבר או בעל זכויות היוצרים מעוניינים להדגיש את שמם, סימן המים עלול לחפוף חלקית לתמונה. כדי לסמן מים בקובץ התמונה JP2, נשתמש [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API שהוא עשיר בתכונות, חזק וקל לשימוש למניפולציה והמרה של תמונות עבור פלטפורמת Java. אתה יכול להוריד את הגרסה האחרונה שלו ישירות מ-[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ולהתקין אותה בתוך ה-Maven שלך פרויקט מבוסס על ידי הוספת התצורות הבאות לקובץ pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="שלבים להוספת סימן מים ל-JP2 באמצעות Java" %}}

{{% blocks/products/pf/agp/text %}}

אתה צריך את [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) כדי לנסות את זרימת העבודה הבאה בסביבה שלך.

{{% /blocks/products/pf/agp/text %}}

+ טען קובץ JP2 בשיטת Image.load
+ צור מופע של גרפיקה מהתמונה
+ הגדר גופן, מברשת ועיצוב עבור טקסט סימן מים
+ צייר סימן מים בשיטת Graphics.drawString
+ שמור תמונה לדיסק בפורמט JP2

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging עבור Java נתמך בכל מערכות ההפעלה העיקריות. רק ודא שיש לך את התנאים המוקדמים הבאים.

{{% /blocks/products/pf/agp/text %}}

- מותקן JDK 1.6 ומעלה.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="תמונת סימן מים JP2 - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "1ac443cce5aab9d32ad152570c716c05" "watermark-jp2-image.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="אודות Aspose.Imaging עבור API של Java" %}}


Aspose.Imaging API הוא פתרון לעיבוד תמונה ליצירה, שינוי, ציור או המרת תמונות (תמונות) בתוך יישומים. הוא מציע: עיבוד תמונה חוצה פלטפורמות, כולל אך לא רק המרות בין פורמטים שונים של תמונה (כולל עיבוד תמונה אחיד מרובה עמודים או ריבוי מסגרות), שינויים כגון ציור, עבודה עם פרימיטיבים גרפיים, טרנספורמציות (שינוי גודל, חיתוך, הפוך וסיבוב , בינאריזציה, גווני אפור, התאמה), תכונות מתקדמות של מניפולציה של תמונות (סינון, שיטוט, מיסוך, ביטול הטיה) ואסטרטגיות אופטימיזציה של זיכרון. זוהי ספרייה עצמאית ואינה תלויה בתוכנה כלשהי לפעולות תמונה. אפשר להוסיף בקלות תכונות המרת תמונה בעלות ביצועים גבוהים עם ממשקי API מקוריים בתוך פרויקטים. אלו הם 100% ממשקי API פרטיים מקומיים ותמונות מעובדות בשרתים שלך.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="סימן מים JP2 באמצעות אפליקציה מקוונת" sectionDescription="הוסף סימן מים למסמכים של JP2 על ידי ביקור ב[אתר האינטרנט של הדגמות חיות](https://products.aspose.app/imaging/watermark). להדגמה החיה יש את היתרונות הבאים" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="אין צורך להוריד או להגדיר שום דבר" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="אין צורך לכתוב שום קוד" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="פשוט העלה את קובץ JP2 שלך, הגדר את סימן המים שלך ולחץ על כפתור הוסף." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="קבל מיד את קישור ההורדה עבור הקובץ שנוצר" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד" >}}
JPEG 2000 (JP2) היא מערכת קידוד תמונה ותקן דחיסת תמונה מתקדם. עוצב, תוך שימוש בטכנולוגיית wavelet JPEG 2000 יכול לקודד תוכן ללא אובדן בכל איכות בבת אחת. יתרה מכך, ללא כל עונש משמעותי ביעילות הקידוד, ל-JPEG 2000 יש את היכולת לגשת ולפענח את אותו תוכן בצורה יעילה למגוון רזולוציות ואיכויות אחרות. זרמי הקוד ב-JPEG 2000 ניתנים להרחבה באופן משמעותי עם אזורי עניין המספקים את המתקן לגישה אקראית מרחבית. בעל עד 16384 רכיבים מגוונים עם המידות ב-terapixels, ודיוק שיכול להגיע ל-38 סיביות/דגימה.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="פורמטים נתמכים אחרים של סימון מים" subTitle="באמצעות Java, אפשר בקלות לסמן מים בפורמטים שונים כולל." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/bmp/" name="BMP" description="תמונת מפת סיביות" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/ico/" name="ICO" description="סמל של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/dib/" name="DIB" description="מפת סיביות בלתי תלויה בהתקן" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/dicom/" name="DICOM" description="הדמיה דיגיטלית ותקשורת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/emf/" name="EMF" description="פורמט Metafile משופר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/gif/" name="GIF" description="פורמט מחלף גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/j2k/" name="J2K" description="תמונה דחוסה של Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/png/" name="PNG" description="גרפיקת רשת ניידת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/tiff/" name="TIFF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/webp/" name="WEBP" description="תמונה ברשת רסטר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/watermark/svg/" name="SVG" description="גרפיקה וקטורית ניתנת להרחבה" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
