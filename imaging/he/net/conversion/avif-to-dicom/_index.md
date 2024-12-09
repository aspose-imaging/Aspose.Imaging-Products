﻿---
title: המר את AVIF ל-DICOM באמצעות C# 
weight: 3920
url: /he/net/conversion/avif-to-dicom/ 
lang: he
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: קוד לדוגמה עבור המרת AVIF ל-DICOM C#. השתמש בקוד לדוגמה של API עבור קבצי AVIF אצווה להמרה של DICOM בתוך VB.NET, Asp.NET או כל יישום מבוסס NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="המר את AVIF ל-DICOM באמצעות C#" h2="הפוך את AVIF ל-DICOM באמצעות ממשקי API מקוריים של .NET ללא צורך בעורך תמונות או ספריות של צד שלישי." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DICOM" pfName="Aspose.Imaging" subTitlepfName="עבור .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="עבור .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/he/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/he/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="בית API" codeSamplesText="דוגמאות קוד" liveDemosText="הדגמות חיות" downloadText="הורד" learnText="לִלמוֹד" overviewText="סקירה כללית" >}}

{{% blocks/products/pf/agp/content h2="כיצד להמיר AVIF ל-DICOM באמצעות C#" %}}

המרת פורמטים של קבצים עשויה להיראות כמו משימה שגרתית בה נתקלים מעצבים גרפיים. עם זאת, לזלזל בחשיבותו תהיה טעות. ההערכה של העבודה שלך עשויה להיות תלויה באיזו מהירות ואפקטיביות אתה מתמודד עם משימה זו. בדרך כלל, תמונות מקוריות זקוקות להמרה לפורמטים המתאימים יותר להדפסה או לפרסום מקוון. אם התמונה המקורית מקורה בעורך גרפי, ייתכן שהיא בפורמט וקטור. בתרחיש זה, יש לבצע רסטר ולהמיר אותו לפורמט רסטר למטרות פרסום. יש לך אפשרות לשמור את התמונה בפורמט לא דחוס לאיכות אופטימלית או להמיר אותה לפורמט דחוס ללא אובדן כדי להקטין את גודל הקובץ. בהקשרים מסוימים, כמו פרסום באינטרנט, אתה יכול לבחור בפורמטים דחוסים עם אובדן. אלגוריתמים שתוכננו במיוחד לדחיסת נתוני תמונה מאפשרים הפחתה משמעותית בגודל הקובץ תוך שמירה על איכות תמונה מקובלת. זה מקל על הורדות מהירות של קבצי תמונה מהאינטרנט. כדי להמיר את AVIF ל-DICOM, נשתמש [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API שהוא עשיר בתכונות, חזק וקל לשימוש למניפולציה והמרה של תמונות עבור פלטפורמת C#. פתח את מנהל החבילות [NuGet](https://www.nuget.org/packages/aspose.imaging), חפש את
 **Aspose.Imaging** והתקן. אתה יכול גם להשתמש בפקודה הבאה ממסוף מנהל החבילות.

{{% blocks/products/pf/agp/code-block title="קונסולת מנהל החבילות" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="שלבים להמרת AVIF ל-DICOM באמצעות C#" %}}

{{% blocks/products/pf/agp/text %}}

מפתחים יכולים לטעון ולהמיר בקלות קבצי AVIF ל-DICOM בכמה שורות קוד בלבד.

{{% /blocks/products/pf/agp/text %}}

+ טען קובץ AVIF בשיטת Image.Load
+ צור והגדר את המופע של תת-המעמד הנדרש של ImageOptionsBase (למשל BmpOptions, PngOptions וכו')
+ קרא לשיטת Image.Save
+ העברת נתיב קובץ עם סיומת DICOM ואובייקט של מחלקה ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

{{% blocks/products/pf/agp/text %}}

לפני הפעלת קוד ההמרה לדוגמה, ודא שיש לך את התנאים המוקדמים הבאים.

{{% /blocks/products/pf/agp/text %}}

+ מערכת הפעלה: ווינדוס או לינוקס.
+ סביבת פיתוח: תומך ב-.NET Core 7 ומעלה, כגון Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="אפליקציה חינמית להמרת AVIF ל-DICOM"
        appName="Conversion"
        extension="AVIF-to-DICOM"
        label1="בחר או גרור ושחרר תמונה AVIF"
        label2="בחר פורמט ולחץ על כפתור המר"
        label3="לחץ על כפתור הורד כדי להוריד תמונה DICOM"
        checkFreeAppLabel="בדוק את [הדגמות חיות להמרת AVIF ל-DICOM]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/AVIF-to-DICOM)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="המר את AVIF ל-DICOM - .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "0967b399090c5471f82f46f88b2c0626" "convert-avif-to-dicom.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד | AVIF">}}
AVIF הוא מפרט פורמט קובץ תמונה פתוח וללא תמלוגים לאחסון תמונות או רצפי תמונות דחוסים עם AV1 בפורמט מיכל HEIF.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד | DICOM">}}
DICOM הוא ראשי התיבות של Digital Imaging and Communications in Medicine ונוגע לתחום האינפורמטיקה הרפואית. DICOM הוא השילוב של הגדרת פורמט קובץ ופרוטוקול תקשורת רשת. DICOM משתמש בסיומת .DCM. .DCM קיים בשני פורמטים שונים, כלומר פורמט 1.x ופורמט 2.x. DCM Format 1.x זמין עוד בשתי גרסאות רגילות ומורחבות. DICOM משמש לשילוב של מכשירי הדמיה רפואיים כמו מדפסות, שרתים, סורקים וכו' של ספקים שונים ומכיל גם נתוני זיהוי של כל מטופל לייחודיות. ניתן לשתף קובצי DICOM בין שני צדדים אם הם מסוגלים לקבל נתוני תמונה בפורמט DICOM. חלק התקשורת של DICOM הוא פרוטוקול שכבת יישומים ומשתמש ב-TCP/IP כדי לתקשר בין ישויות. פרוטוקולי HTTP ו-HTTPS משמשים עבור שירותי האינטרנט של DICOM. גרסאות הנתמכות על ידי שירותי אינטרנט הן 1.0, 1.1, 2 ואילך.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="המרות נתמכות אחרות" subTitle="באמצעות C#, אפשר להמיר בקלות פורמטים שונים כולל." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-gif/" name="GIF" description="פורמט מחלף גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-dicom/" name="DICOM" description="הדמיה דיגיטלית ותקשורת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-emf/" name="EMF" description="פורמט Metafile משופר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-jpg/" name="JPG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-jpeg/" name="JPEG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-j2k/" name="J2K" description="תמונה דחוסה של Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-png/" name="PNG" description="גרפיקת רשת ניידת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-apng/" name="APNG" description="גרפיקת רשת ניידת מונפשת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-psd/" name="PSD" description="מסמך פוטושופ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-dxf/" name="DXF" description="Drawing Interchange Format, או Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-svg/" name="SVG" description="גרפיקה וקטורית ניתנת להרחבה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-tiff/" name="TIFF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-webp/" name="WEBP" description="תמונה ברשת רסטר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-pdf/" name="PDF" description="פורמט מסמך נייד (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-html/" name="HTML" description="קנבס HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-emz/" name="EMZ" description="Metafile משופר דחוס של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-wmz/" name="WMZ" description="עור דחוס של Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-tga/" name="TGA" description="טארגה גרפיקה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-svgz/" name="SVGZ" description="גרסה דחוסה של קובץ Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-canvas/" name="CANVAS" description="קנבס HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-ico/" name="ICO" description="סמל של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/net/conversion/avif-to-bmp/" name="BMP" description="תמונת מפת סיביות" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}