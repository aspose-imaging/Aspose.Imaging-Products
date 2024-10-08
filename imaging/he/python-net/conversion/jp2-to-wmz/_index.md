﻿---
title: המרת תמונות JP2 ל-WMZ עם Python 
weight: 3920
url: /he/python-net/conversion/jp2-to-wmz/ 
lang: he
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: כיצד להשתמש ב-Python עבור המרת תמונות ותמונות מ-JP2 ל-WMZ ביישומי שולחן עבודה ואינטרנט.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="השתמש ב-Python עבור המרת תמונות JP2 ל-WMZ" h2="צור אפליקציות של Python כדי להמיר תמונות ותמונות JP2 ל-WMZ באמצעות ממשקי API של שרת" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="WMZ" pfName="Aspose.Imaging" subTitlepfName="עבור Python" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="עבור Python" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/he/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/he/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="בית API" codeSamplesText="דוגמאות קוד" liveDemosText="הדגמות חיות" downloadText="הורד" learnText="לִלמוֹד" overviewText="סקירה כללית" >}}

{{% blocks/products/pf/agp/content h2="כיצד להמיר תמונות ותמונות JP2 ל-WMZ באמצעות Python" %}}

המרת קובצי תמונה מפורמט אחד לאחר היא משימה נפוצה בה נתקל כל מעצב גרפי. היעילות והמצוינות בהמרת קבצים לא רק משפיעות על מהירות ההשלמה אלא גם ממלאות תפקיד מכריע בהערכת איכות העבודה הכוללת. לגבי מקורות התמונות, הם מחייבים לעתים קרובות להפוך לפורמטים חלופיים המתאימים יותר להדפסה או להפצה מקוונת. תמונה שנוצרה בעורך גרפי צפויה להיות בפורמט וקטור. במקרים כאלה, לצורך פרסום אתר אינטרנט, עליו לעבור רסטר ולהישמר בפורמט רסטר. יש לך אפשרות להמיר את התמונה בפורמט לא דחוס לאיכות מעולה או לשמור אותה בפורמט דחוס ללא אובדן כדי למזער את גודל הקובץ. עבור תרחישים שבהם הקטנת גודל הקובץ היא חובה, כמו ביישומי אתרים, קיימת אפשרות להמרה לפורמטי דחיסה חסרי אובדן. אלגוריתמים מיוחדים של דחיסת נתונים עבור תמונות יכולים להקטין משמעותית את גודל הקובץ תוך שמירה על איכות תמונה מקובלת, מה שמבטיח טעינת תמונה מהירה. כדי להמיר תמונות ותמונות מ-JP2 ל-WMZ, נשתמש [Aspose.Imaging for Python דרך NET](/imaging/he/python-net) API שהוא עשיר בתכונות, חזק וקל לשימוש למניפולציה והמרה של תמונות API עבור פלטפורמת Python. אתה יכול להתקין אותו באמצעות הפקודה הבאה מפקודת המערכת שלך.

{{% blocks/products/pf/agp/code-block title="שורת הפקודה של המערכת" offSpacer="true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="שלבים להמרת JP2 ל-WMZ באמצעות Python" %}}

{{% blocks/products/pf/agp/text %}}

מפתחים יכולים לטעון ולהמיר בקלות קבצי JP2 ל-WMZ בכמה שורות קוד בלבד.

{{% /blocks/products/pf/agp/text %}}

+ טען קובץ JP2 בשיטת Image.Load
+ צור והגדר את המופע של תת-המעמד הנדרש של ImageOptionsBase (למשל BmpOptions, PngOptions וכו')
+ קרא לשיטת Image.Save
+ העברת נתיב קובץ עם סיומת WMZ ואובייקט של מחלקה ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="דרישות מערכת" %}}

{{% blocks/products/pf/agp/text %}}

לפני הפעלת קוד ההמרה לדוגמה, ודא שיש לך את התנאים המוקדמים הבאים.

{{% /blocks/products/pf/agp/text %}}

+ מערכת הפעלה: ווינדוס או לינוקס.
+ סביבת פיתוח: תומך ב-.NET Core 7 ומעלה, כגון Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="אפליקציה חינמית להמרת JP2 ל-WMZ"
        appName="Conversion"
        extension="JP2-to-WMZ"
        label1="בחר או גרור ושחרר תמונה JP2"
        label2="בחר פורמט ולחץ על כפתור המר"
        label3="לחץ על כפתור הורד כדי להוריד תמונה WMZ"
        checkFreeAppLabel="בדוק את [הדגמות חיות להמרת JP2 ל-WMZ]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/conversion/JP2-to-WMZ)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="המר את JP2 ל-WMZ - Python" offSpacer="true" %}}

{{< gist "aspose-com-gists" "e1d418ed58a1f4598f259e62914511d4" "convert-image-to-other-format.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="JP2" readMoreLink="https://docs.fileformat.com/image/jp2/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד | JP2">}}
JPEG 2000 (JP2) היא מערכת קידוד תמונה ותקן דחיסת תמונה מתקדם. עוצב, תוך שימוש בטכנולוגיית wavelet JPEG 2000 יכול לקודד תוכן ללא אובדן בכל איכות בבת אחת. יתרה מכך, ללא כל עונש משמעותי ביעילות הקידוד, ל-JPEG 2000 יש את היכולת לגשת ולפענח את אותו תוכן בצורה יעילה למגוון רזולוציות ואיכויות אחרות. זרמי הקוד ב-JPEG 2000 ניתנים להרחבה באופן משמעותי עם אזורי עניין המספקים את המתקן לגישה אקראית מרחבית. בעל עד 16384 רכיבים מגוונים עם המידות ב-terapixels, ודיוק שיכול להגיע ל-38 סיביות/דגימה.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WMZ" readMoreLink="https://docs.fileformat.com/image/wmz/" whatIsFormat1="מה זה" whatIsFormat2="פורמט קובץ" readMoreFormat="קרא עוד | WMZ">}}
WMZ היא סיומת קובץ עבור פורמט קובץ סקין ב/עבור/בשימוש על ידי Windows Media Player. קובץ WMZ הוא בעצם קובץ WMF דחוס ב-XML.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="המרות נתמכות אחרות" subTitle="באמצעות Python, אפשר להמיר בקלות פורמטים שונים כולל." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-bmp/" name="BMP" description="תמונת מפת סיביות" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-gif/" name="GIF" description="פורמט מחלף גרפי" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-dicom/" name="DICOM" description="הדמיה דיגיטלית ותקשורת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-emf/" name="EMF" description="פורמט Metafile משופר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-jpg/" name="JPG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-jpeg/" name="JPEG" description="קבוצת מומחי צילום משותפת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-j2k/" name="J2K" description="תמונה דחוסה של Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-png/" name="PNG" description="גרפיקת רשת ניידת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-apng/" name="APNG" description="גרפיקת רשת ניידת מונפשת" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-psd/" name="PSD" description="מסמך פוטושופ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-dxf/" name="DXF" description="Drawing Interchange Format, או Drawing Exchange Format," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-svg/" name="SVG" description="גרפיקה וקטורית ניתנת להרחבה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-tiff/" name="TIFF" description="פורמט תמונה מתויג" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-webp/" name="WEBP" description="תמונה ברשת רסטר" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-wmf/" name="WMF" description="Microsoft Windows Metafile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-pdf/" name="PDF" description="פורמט מסמך נייד (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-html/" name="HTML" description="קנבס HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-emz/" name="EMZ" description="Metafile משופר דחוס של Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-wmz/" name="WMZ" description="עור דחוס של Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-tga/" name="TGA" description="טארגה גרפיקה" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-svgz/" name="SVGZ" description="גרסה דחוסה של קובץ Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-canvas/" name="CANVAS" description="קנבס HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/he/python-net/conversion/jp2-to-ico/" name="ICO" description="סמל של Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
