﻿---
title: .NET के माध्यम से EPS दस्तावेज़ों में पृष्ठभूमि निकालें 
weight: 3920
url: /hi/net/remove-background/eps/ 
lang: hi
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: .NET Framework, .NET Core, Windows एप्लिकेशन, ASP.NET वेब एप्लिकेशन पर EPS फाइलों में पृष्ठभूमि को हटाने के लिए हमारे ऑन-प्रिमाइसेस दस्तावेज़ API को आज़माएं।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="C# के माध्यम से EPSs से पृष्ठभूमि निकालें" h2="सर्वर-साइड API का उपयोग करके EPS फ़ाइलों से पृष्ठभूमि निकालने के लिए अपने स्वयं के .NET ऐप्स बनाएं।" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="EPS" pfName="Aspose.Imaging" subTitlepfName=".NET के लिए" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName=".NET के लिए" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/hi/net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-.NET/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/net/" installationsDocsLink="https://docs.aspose.com/imaging/net/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/imaging/net/" learnAsLink="https://docs.aspose.com/imaging/net/" apiReference="" apiHomeText="एपीआई होम" codeSamplesText="कोड नमूने" liveDemosText="लाइव डेमो" downloadText="डाउनलोड" learnText="सीखना">}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके EPS फ़ाइलों में पृष्ठभूमि कैसे निकालें" %}}

किसी छवि से पृष्ठभूमि हटाने में अग्रभूमि वस्तुओं को अलग करना शामिल है, एक ऐसा कार्य जिसके लिए वस्तु को पहचानने की आवश्यकता होती है। EPS प्रारूप में एक फोटो के भीतर वस्तुओं की पहचान करने के लिए कई दृष्टिकोण मौजूद हैं। एक समान रंग की पृष्ठभूमि वाली सरल छवियों के लिए, एक स्वचालित विधि पर्याप्त है। हालाँकि, एकाधिक या आंशिक रूप से मर्ज की गई आकृतियों वाली तस्वीरों के लिए, वस्तुओं को पूर्व-चिह्नित करना आवश्यक हो जाता है। इसमें हटाने के लिए आयताकार क्षेत्रों और ऑब्जेक्ट प्रकारों को निर्दिष्ट करना शामिल है। जटिल मामलों में, क्लाउड एपीआई स्वचालित ऑब्जेक्ट पहचान को सक्षम बनाता है। क्लाउड एपीआई एक क्लाउड एप्लिकेशन प्रदान करता है जो तस्वीरों के भीतर वस्तुओं को पहचानने में सक्षम है, पृष्ठभूमि हटाने के लिए परिणामी रूपरेखा का लाभ उठाता है। हटाने के बाद, छवि गुणवत्ता बढ़ाने के लिए आकृतियों द्वारा छोड़े गए किनारों को चिकना किया जा सकता है। EPS फ़ाइलों में पृष्ठभूमि हटाने के लिए, हम इसका उपयोग करेंगे [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net) API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान छवि हेरफेर और C# प्लेटफॉर्म के लिए रूपांतरण API है। [NuGet](https://www.nuget.org/packages/aspose.imaging) पैकेज मैनेजर खोलें, खोजें
 **Aspose.Imaging** और इंस्टॉल करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज प्रबंधक कंसोल कमांड" offSpacer="true" %}} 

```cs

PM> Install-Package Aspose.Imaging

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से EPSs से पृष्ठभूमि हटाने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

आपको अपने परिवेश में निम्न वर्कफ़्लो आज़माने के लिए [aspose.imaging.dll](https://downloads.aspose.com/imaging/net) की आवश्यकता होगी।

{{% /blocks/products/pf/agp/text %}}

+ लोड EPS छवि के साथ फ़ाइलें। लोड विधि
+ पृष्ठभूमि निकालें;
+ Aspose द्वारा समर्थित डिस्क में छवि सहेजें। इमेजिंग प्रारूप

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज या .NET फ्रेमवर्क, .NET कोर, विंडोज एप्लीकेशन, एएसपी.नेट वेब एप्लीकेशन के साथ संगत ओएस।
- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल।
- Aspose.Imaging for .NET आपके प्रोजेक्ट में संदर्भित है।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="EPS इमेज में बैकग्राउंड हटाएं - .NET" offSpacer="" %}}

{{< gist "aspose-com-gists" "c28d7d7f7dff39444751b5724d5ba14a" "remove-change-background-generic-examples.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Imaging for .NET API . के बारे में" %}}


Aspose.Imaging API अनुप्रयोगों के भीतर छवियों (फ़ोटो) को बनाने, संशोधित करने, आकर्षित करने या परिवर्तित करने के लिए एक छवि प्रसंस्करण समाधान है। यह प्रदान करता है: क्रॉस-प्लेटफ़ॉर्म छवि प्रसंस्करण, जिसमें विभिन्न छवि प्रारूपों (समान बहु-पृष्ठ या बहु-फ़्रेम छवि प्रसंस्करण सहित) के बीच रूपांतरण शामिल हैं, लेकिन इन्हीं तक सीमित नहीं है, ड्राइंग जैसे संशोधन, ग्राफिक प्राइमेटिव के साथ काम करना, परिवर्तन (आकार बदलना, फसल करना, फ्लिप करना और घुमाना) , बिनाराइज़ेशन, ग्रेस्केल, एडजस्ट), उन्नत छवि हेरफेर सुविधाएँ (फ़िल्टरिंग, डिथरिंग, मास्किंग, डेस्क्यूइंग), और मेमोरी ऑप्टिमाइज़ेशन रणनीतियाँ। यह एक स्टैंडअलोन लाइब्रेरी है और इमेज ऑपरेशंस के लिए किसी सॉफ्टवेयर पर निर्भर नहीं है। परियोजनाओं के भीतर देशी एपीआई के साथ आसानी से उच्च-प्रदर्शन छवि रूपांतरण सुविधाएँ जोड़ सकते हैं। ये 100% निजी ऑन-प्रिमाइसेस एपीआई हैं और छवियों को आपके सर्वर पर संसाधित किया जाता है।


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन ऐप के द्वारा EPSs में पृष्ठभूमि हटाएं" sectionDescription="हमारी [लाइव डेमो वेबसाइट](https://products.aspose.app/imaging/remove-background) पर जाकर EPS दस्तावेज़ों की पृष्ठभूमि हटाएं। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="कोई कोड लिखने की जरूरत नहीं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="बस अपनी EPS फ़ाइलें अपलोड करें और अभी पृष्ठभूमि हटाएं बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="परिणामी फ़ाइल के लिए तुरंत डाउनलोड लिंक प्राप्त करें" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EPS" readMoreLink="https://docs.fileformat.com/image/eps/" whatIsFormat1="क्या है" whatIsFormat2="फाइल का प्रारूप" readMoreFormat="अधिक पढ़ें" >}}
ईपीएस एक्सटेंशन वाली फाइलें अनिवार्य रूप से एक एनकैप्सुलेटेड पोस्टस्क्रिप्ट भाषा प्रोग्राम का वर्णन करती हैं जो एक पृष्ठ की उपस्थिति का वर्णन करती है। नाम "एनकैप्सुलेटेड" क्योंकि इसे किसी अन्य पोस्टस्क्रिप्ट भाषा पृष्ठ विवरण में शामिल या इनकैप्सुलेट किया जा सकता है। इस स्क्रिप्ट आधारित फ़ाइल स्वरूप में टेक्स्ट, ग्राफिक्स और छवियों का कोई भी संयोजन हो सकता है। ईपीएस फाइलों में एक बिटमैप पूर्वावलोकन छवि शामिल हो सकती है जो ऐसी फाइलों को खोलने वाले अनुप्रयोगों द्वारा प्रदर्शित करने के लिए अंदर समझाया गया है। ईपीएस फाइलों को विभिन्न अनुप्रयोगों का उपयोग करके मानक छवि प्रारूपों जैसे जेपीजी, पीएनजी, टीआईएफएफ और पीडीएफ में परिवर्तित किया जा सकता है। एडोब इलस्ट्रेटर, फोटोशॉप और पेंटशॉप प्रो। EPS फ़ाइलों में सुरक्षा भेद्यता के कारण, Office 2016, Office 2013, Office 2010 और Office 365 ने EPS फ़ाइलों को Office दस्तावेज़ों में सम्मिलित करने की क्षमता को बंद कर दिया है।
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित पृष्ठभूमि प्रारूप निकालें" subTitle="C# का उपयोग करके, कोई भी व्यक्ति विभिन्न प्रारूपों से पृष्ठभूमि को आसानी से हटा सकता है, जिसमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/apng/" name="APNG" description="एनिमेटेड पोर्टेबल नेटवर्क ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/bmp/" name="BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/ico/" name="ICO" description="विंडोज आइकन" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/jpg/" name="JPG" description="फ़ोटोग्राफ़ी संबंधी विशेषज्ञों का संयुक्त समूह" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/dib/" name="DIB" description="डिवाइस स्वतंत्र बिटमैप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/dicom/" name="DICOM" description="डिजिटल इमेजिंग और संचार" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/djvu/" name="DJVU" description="ग्राफिक्स प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/dng/" name="DNG" description="डिजिटल कैमरा छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/emf/" name="EMF" description="उन्नत मेटाफ़ाइल प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/emz/" name="EMZ" description="विंडोज कम्प्रेस्ड एन्हांस्ड मेटाफाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/gif/" name="GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/jp2/" name="JP2" description="जेपीईजी 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/j2k/" name="J2K" description="तरंगिका संपीड़ित छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/png/" name="PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/tiff/" name="TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/webp/" name="WEBP" description="रेखापुंज वेब छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/wmf/" name="WMF" description="माइक्रोसॉफ्ट विंडोज मेटाफाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/wmz/" name="WMZ" description="संपीड़ित विंडोज मीडिया प्लेयर त्वचा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/tga/" name="TGA" description="टार्गा ग्राफिक" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/svg/" name="SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/cdr/" name="CDR" description="वेक्टर ड्राइंग छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/cmx/" name="CMX" description="कोरल एक्सचेंज इमेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/otg/" name="OTG" description="OpenDocument मानक" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/odg/" name="ODG" description="अपाचे ओपनऑफिस ड्रा प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/net/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
