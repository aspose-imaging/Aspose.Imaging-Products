﻿---
title: המר את ODG ל-JPEG2000 באמצעות Java 
weight: 3920
url: /he/java/conversion/odg-to-jpeg2000/ 
lang: he
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: קוד לדוגמה עבור המרת Java מ-ODG ל-JPEG2000. השתמש בקוד לדוגמה של API עבור קבצי ODG אצווה להמרה של JPEG2000 בתוך כל יישום מבוסס Java אינטרנט או שולחני.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="המר את ODG ל-JPEG2000 באמצעות Java" h2="הפוך את ODG ל-JPEG2000 באמצעות ממשקי API מקוריים של Java ללא צורך בעורך תמונות או ספריות של צד שלישי." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG2000" pfName="Aspose.Imaging" subTitlepfName="עבור Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="עבור Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/he/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/he/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="בית API" codeSamplesText="דוגמאות קוד" liveDemosText="הדגמות חיות" downloadText="הורד" learnText="לִלמוֹד" overviewText="סקירה כללית" >}}

{{% blocks/products/pf/agp/content h2="כיצד להמיר ODG ל-JPEG2000 באמצעות Java" %}}

המרת פורמטים של קבצים עשויה להיראות כמו משימה שגרתית בה נתקלים מעצבים גרפיים. עם זאת, לזלזל בחשיבותו תהיה טעות. ההערכה של העבודה שלך עשויה להיות תלויה באיזו מהירות ואפקטיביות אתה מתמודד עם משימה זו. בדרך כלל, תמונות מקוריות זקוקות להמרה לפורמטים המתאימים יותר להדפסה או לפרסום מקוון. אם התמונה המקורית מקורה בעורך גרפי, ייתכן שהיא בפורמט וקטור. בתרחיש זה, יש לבצע רסטר ולהמיר אותו לפורמט רסטר למטרות פרסום. יש לך אפשרות לשמור את התמונה בפורמט לא דחוס לאיכות אופטימלית או להמיר אותה לפורמט דחוס ללא אובדן כדי להקטין את גודל הקובץ. בהקשרים מסוימים, כמו פרסום באינטרנט, אתה יכול לבחור בפורמטים דחוסים עם אובדן. אלגוריתמים שתוכננו במיוחד לדחיסת נתוני תמונה מאפשרים הפחתה משמעותית בגודל הקובץ תוך שמירה על איכות תמונה מקובלת. זה מקל על הורדות מהירות של קבצי תמונה מהאינטרנט. כדי להמיר את ODG ל-JPEG2000, נשתמש [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API שהוא עשיר בתכונות, חזק וקל לשימוש למניפולציה והמרה של תמונות עבור פלטפורמת Java. אתה יכול להוריד את הגרסה האחרונה שלו ישירות מ-[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ולהתקין אותה בתוך ה-Maven שלך פרויקט מבוסס על ידי הוספת התצורות הבאות לקובץ pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="שלבים להמרת ODG ל-JPEG2000 באמצעות Java" %}}

{{% blocks/products/pf/agp/text %}}

מפתחים יכולים לטעון ולהמיר בקלות קבצי ODG ל-JPEG2000 בכמה שורות קוד בלבד.

{{% /blocks/products/pf/agp/text %}}

+ טען קובץ ODG בשיטת Image.load
+ צור והגדר את המופע של תת-המעמד הנדרש של ImageOptionsBase (למשל BmpOptions, PngOptions וכו')
+ קרא לשיטת Image.save
+ העברת נתיב קובץ עם סיומת JPEG2000 ואובייקט של מחלקה ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

{{% blocks/products/pf/agp/text %}}

לפני הפעלת קוד ההמרה לדוגמה, ודא שיש לך את התנאים המוקדמים הבאים.

{{% /blocks/products/pf/agp/text %}}

+ מערכת הפעלה: ווינדוס או לינוקס.
+ סביבת פיתוח: תומך ב-.NET Core 7 ומעלה, כגון Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="אפליקציה חינמית להמרת ODG ל-JPEG2000"
        appName="Conversion"
        extension="ODG-to-JPEG2000"
        label1="בחר או גרור ושחרר תמונה ODG"
        label2="בחר פורמט ולחץ על כפתור המר"
        label3="לחץ על כפתור הורד כדי להוריד תמונה JPEG2000"
        checkFreeAppLabel="בדוק את [הדגמות חיות להמרת ODG ל-JPEG2000]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/ODG-to-JPEG2000)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="המר את ODG ל-JPEG2000 - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="ODG" readMoreLink="https://docs.fileformat.com/image/odg/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד | ODG">}}
פורמט הקובץ ODG משמש את יישום Draw של Apache OpenOffice לאחסון רכיבי ציור כתמונה וקטורית. הוא עוקב אחר מפרטי פורמט הקובץ מבוסס XML המתוארים על ידי Advancement of Structural Information Standards (OASIS). ODG מייצג שרטוטים כתמונות וקטוריות באמצעות נקודות, קווים ועיקולים. מלבד OpenOffice, LibreOffice ויישומים אחרים מספקים גם תמיכה לעבודה עם פורמט קובץ ODG. פורמטים אחרים הנתמכים על ידי OpenOffice, למשל, כוללים ODT, ODF, ODP ו-ODS.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="JPEG2000" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד | JPEG2000">}}
JPEG 2000 (JP2) היא מערכת קידוד תמונה ותקן דחיסת תמונה מתקדם. עוצב, תוך שימוש בטכנולוגיית wavelet JPEG 2000 יכול לקודד תוכן ללא אובדן בכל איכות בבת אחת. יתרה מכך, ללא כל עונש משמעותי ביעילות הקידוד, ל-JPEG 2000 יש את היכולת לגשת ולפענח את אותו תוכן בצורה יעילה למגוון רזולוציות ואיכויות אחרות. זרמי הקוד ב-JPEG 2000 ניתנים להרחבה באופן משמעותי עם אזורי עניין המספקים את המתקן לגישה אקראית מרחבית. בעל עד 16384 רכיבים מגוונים עם המידות ב-terapixels, ודיוק שיכול להגיע ל-38 סיביות/דגימה.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="המרות נתמכות אחרות" subTitle="באמצעות Java, אפשר להמיר בקלות פורמטים שונים כולל." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-bmp/" name="BMP" description="תמונת מפת סיביות" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-gif/" name="GIF" description="פורמט מחלף גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-dicom/" name="DICOM" description="הדמיה דיגיטלית ותקשורת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-emf/" name="EMF" description="פורמט Metafile משופר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-jpg/" name="JPG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-jpeg/" name="JPEG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-j2k/" name="J2K" description="תמונה דחוסה של Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-png/" name="PNG" description="גרפיקת רשת ניידת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-apng/" name="APNG" description="גרפיקת רשת ניידת מונפשת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-psd/" name="PSD" description="מסמך פוטושופ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-dxf/" name="DXF" description="Drawing Interchange Format, או Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-svg/" name="SVG" description="גרפיקה וקטורית ניתנת להרחבה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-tiff/" name="TIFF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-webp/" name="WEBP" description="תמונה ברשת רסטר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-pdf/" name="PDF" description="פורמט מסמך נייד (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-html/" name="HTML" description="קנבס HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-emz/" name="EMZ" description="Metafile משופר דחוס של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-wmz/" name="WMZ" description="עור דחוס של Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-tga/" name="TGA" description="טארגה גרפיקה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-svgz/" name="SVGZ" description="גרסה דחוסה של קובץ Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-canvas/" name="CANVAS" description="קנבס HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/java/conversion/odg-to-ico/" name="ICO" description="סמל של Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
