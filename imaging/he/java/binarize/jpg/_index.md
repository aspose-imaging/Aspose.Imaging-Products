﻿---
title: בצע בינאריזה של מסמכים ב-JPG באמצעות Java 
weight: 3920
url: /he/java/binarize/jpg/ 
lang: he
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: נסה את ממשקי ה-API של מסמכים מקומיים כדי לשלב קבצי JPG ב-.NET Framework, .NET Core, Windows Application, ASP.NET Web Application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="בינאריזה של JPG באמצעות Java" h2="בנה יישומי Java משלך כדי לשלב קבצים JPG באמצעות ממשקי API בצד השרת." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPG" pfName="Aspose.Imaging" subTitlepfName="עבור Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="עבור Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/he/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="בית API" codeSamplesText="דוגמאות קוד" liveDemosText="הדגמות חיות" downloadText="הורד" learnText="לִלמוֹד">}}

{{% blocks/products/pf/agp/content h2="כיצד לבצע בינאריזה של קבצים JPG באמצעות Java" %}}

המצאת הסרט הצבעוני סימנה אבן דרך משמעותית בתחום הצילום. עם זאת, צילום קלאסי מקושר מטבעו לדימויים בשחור-לבן. למרות היכולות הטכניות הנרחבות של מצלמות ללכוד את כל ספקטרום הצבעים, אנשים רבים בוחרים במונוכרום, והופכים את התמונות שלהם לשחור ולבן. במקרים כאלה, נכנסת לפעולה פונקציית בינאריזציה, הממירה את כל הפיקסלים לערכים בינאריים: \"0\" ללבן ו\"1\" לשחור. בתרחישים אחרים, ההמרה הזו אינה מונעת מבחירות אמנותיות אלא מבחירות מעשיות, כמו הכנת איורים בשחור-לבן להדפסה בספרים או בעיתונים. באמצעות ספריית הגרפיקה Java, אתה יכול להגדיר סף בהירות פיקסלים. פיקסלים עם ערכי בהירות מתחת לסף זה יהפכו לשחורים, בעוד אלו שמעליו יהפכו לבנים. לחלופין, אתה יכול להשתמש בשיטת בינאריזציה אדפטיבית השוקלת את ערכי הפיקסלים באזור שמסביב. גישה זו מביאה למעברים חלקים יותר בין גבולות צבע בתמונה בשחור-לבן המתקבלת. על מנת לשלב קבצים ב-JPG, נשתמש [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API שהוא עשיר בתכונות, חזק וקל לשימוש למניפולציה והמרה של תמונות עבור פלטפורמת Java. אתה יכול להוריד את הגרסה האחרונה שלו ישירות מ-[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ולהתקין אותה בתוך ה-Maven שלך פרויקט מבוסס על ידי הוספת התצורות הבאות לקובץ pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="שלבים לעיבוד בינארי של JPG באמצעות Java" %}}

{{% blocks/products/pf/agp/text %}}

אתה צריך את [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) כדי לנסות את זרימת העבודה הבאה בסביבה שלך.

{{% /blocks/products/pf/agp/text %}}

+ טען קבצים JPG בשיטת Image.Load
+ בינאריזה של תמונות;
+ שמור תמונה דחוסה לדיסק בפורמט הנתמך על ידי Aspose.Imaging

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging עבור Java נתמך בכל מערכות ההפעלה העיקריות. רק ודא שיש לך את התנאים המוקדמים הבאים.

{{% /blocks/products/pf/agp/text %}}

- מותקן JDK 1.6 ומעלה.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="בינאריזה של תמונות JPG - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "daac19b481878f17e5e6caadd16bb490" "binarize-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="אודות Aspose.Imaging עבור API של Java" %}}


Aspose.Imaging API הוא פתרון לעיבוד תמונה ליצירה, שינוי, ציור או המרת תמונות (תמונות) בתוך יישומים. הוא מציע: עיבוד תמונה חוצה פלטפורמות, כולל אך לא רק המרות בין פורמטים שונים של תמונה (כולל עיבוד תמונה אחיד מרובה עמודים או ריבוי מסגרות), שינויים כגון ציור, עבודה עם פרימיטיבים גרפיים, טרנספורמציות (שינוי גודל, חיתוך, הפוך וסיבוב , בינאריזציה, גווני אפור, התאמה), תכונות מתקדמות של מניפולציה של תמונות (סינון, שיטוט, מיסוך, ביטול הטיה) ואסטרטגיות אופטימיזציה של זיכרון. זוהי ספרייה עצמאית ואינה תלויה בתוכנה כלשהי לפעולות תמונה. אפשר להוסיף בקלות תכונות המרת תמונה בעלות ביצועים גבוהים עם ממשקי API מקוריים בתוך פרויקטים. אלו הם 100% ממשקי API פרטיים מקומיים ותמונות מעובדות בשרתים שלך.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="בצע בינאריזה של JPG באמצעות אפליקציה מקוונת" sectionDescription="בצע בינאריזה של מסמכים ב-JPG על ידי ביקור ב[אתר האינטרנט של הדגמות חיות](https://products.aspose.app/imaging/image-Binarize). להדגמה החיה יש את היתרונות הבאים" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="אין צורך להוריד או להגדיר שום דבר" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="אין צורך לכתוב שום קוד" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="פשוט העלה את קבצי JPG שלך ולחץ על הלחצן בינאריזציה עכשיו." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="קבל מיד את קישור ההורדה עבור הקובץ שנוצר" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JPG" readMoreLink="https://docs.fileformat.com/image/jpg/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד" >}}
JPEG הוא סוג של פורמט תמונה שנשמר בשיטת הדחיסה המאבדת. תמונת הפלט, כתוצאה מדחיסה, היא פשרה בין גודל האחסון ואיכות התמונה. משתמשים יכולים להתאים את רמת הדחיסה כדי להשיג את רמת האיכות הרצויה ובו בזמן להקטין את גודל האחסון. איכות התמונה מושפעת באופן זניח אם מוחלת דחיסה של 10:1 על התמונה. ככל שערך הדחיסה גבוה יותר, כך הירידה באיכות התמונה גבוהה יותר.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="פורמטים בינאריים נתמכים אחרים" subTitle="באמצעות Java, אפשר לשלב בקלות פורמטים שונים כולל." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/apng/" name="APNG" description="גרפיקת רשת ניידת מונפשת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/bmp/" name="BMP" description="תמונת מפת סיביות" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/ico/" name="ICO" description="סמל של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/jpeg/" name="JPEG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/dib/" name="DIB" description="מפת סיביות בלתי תלויה בהתקן" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/dicom/" name="DICOM" description="הדמיה דיגיטלית ותקשורת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/djvu/" name="DJVU" description="פורמט גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/dng/" name="DNG" description="תמונת מצלמה דיגיטלית" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/emf/" name="EMF" description="פורמט Metafile משופר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/emz/" name="EMZ" description="Metafile משופר דחוס של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/gif/" name="GIF" description="פורמט מחלף גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/j2k/" name="J2K" description="תמונה דחוסה של Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/png/" name="PNG" description="גרפיקת רשת ניידת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/tiff/" name="TIFF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/tif/" name="TIF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/webp/" name="WEBP" description="תמונה ברשת רסטר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/wmz/" name="WMZ" description="עור דחוס של Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/tga/" name="TGA" description="טארגה גרפיקה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/svg/" name="SVG" description="גרפיקה וקטורית ניתנת להרחבה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/eps/" name="EPS" description="שפת PostScript מובלעת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/cdr/" name="CDR" description="תמונה של ציור וקטור" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/cmx/" name="CMX" description="תמונת Corel Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/otg/" name="OTG" description="OpenDocument Standard" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/odg/" name="ODG" description="Apache OpenOffice Draw Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/binarize/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
