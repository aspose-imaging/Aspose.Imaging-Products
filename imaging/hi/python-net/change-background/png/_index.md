﻿---
title: PNG छवियाँ पृष्ठभूमि परिवर्तन Python के साथ 
weight: 3920
url: /hi/python-net/change-background/png/ 
lang: hi
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: डेस्कटॉप और वेब अनुप्रयोगों पर PNG छवियों और फ़ोटो पृष्ठभूमि परिवर्तन के लिए Python का उपयोग कैसे करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="PNG छवियों की पृष्ठभूमि में बदलाव के लिए Python का उपयोग करें" h2="सर्वर API के माध्यम से PNG छवियों और फ़ोटो की पृष्ठभूमि बदलने के लिए Python ऐप्स बनाएं" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PNG" pfName="Aspose.Imaging" subTitlepfName="Python के लिए" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Python के लिए" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-python-net.svg" apiHomeLink="/imaging/hi/python-net/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Python-net/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/python-net/" installationsDocsLink="https://docs.aspose.com/imaging/python-net/" pipLink="https://pypi.org/project/aspose-imaging-python-net/" downloadAsLink="https://downloads.aspose.com/imaging/python-net/" learnAsLink="https://docs.aspose.com/imaging/python-net/" apiReference="" apiHomeText="एपीआई होम" codeSamplesText="कोड नमूने" liveDemosText="लाइव डेमो" downloadText="डाउनलोड" learnText="सीखना">}}

{{% blocks/products/pf/agp/content h2="Python के साथ PNG छवियों और फ़ोटो की पृष्ठभूमि कैसे बदलें" %}}

प्रायः किसी छवि को PNG में संपादित करते समय उसकी पृष्ठभूमि बदलने की आवश्यकता उत्पन्न हो जाती है। प्रारंभिक चरण में फोटो के भीतर अग्रभूमि वस्तुओं का चयन करना और पृष्ठभूमि के लिए जिम्मेदार क्षेत्रों को अलग करने के लिए उन्हें बाकी छवि से अलग करना शामिल है। जब पृष्ठभूमि एक समान क्षेत्र बनाती है, तो ऑब्जेक्ट आकृतियाँ स्वचालित रूप से स्थापित की जा सकती हैं। हालाँकि, यदि फोटो अनियमित पृष्ठभूमि प्रदर्शित करता है या पृष्ठभूमि से वांछित वस्तु को अलग करने में जटिलताएँ उत्पन्न होती हैं, तो प्रारंभिक छवि अंकन विधि को नियोजित करने की सलाह दी जाती है। इसमें फोटो के भीतर आयताकार क्षेत्रों का चयन करना शामिल है जहां प्रत्याशित वस्तुएं स्थित हैं और उनके प्रकार को निर्दिष्ट करना है। ऐसी कार्रवाइयों को स्वचालित ऑब्जेक्ट डिटेक्शन के लिए क्लाउड एपीआई के माध्यम से मैन्युअल रूप से निष्पादित या सुविधाजनक बनाया जा सकता है। वस्तुओं के चयन और मूल पृष्ठभूमि को हटाने के बाद, आपके पास एक नई पृष्ठभूमि पेश करने या उसे पारदर्शी बनाने का विकल्प होता है। किसी छवि की पृष्ठभूमि को PNG प्रारूप में संशोधित करने के लिए, हम इसका उपयोग करेंगे [Aspose.Imaging for Python via .NET](/imaging/hi/python-net) एपीआई जो कि पायथन प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान छवि हेरफेर और रूपांतरण एपीआई है। आप इसे अपने सिस्टम कमांड से निम्नलिखित कमांड का उपयोग करके इंस्टॉल कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="द सिस्टम कमांड लाइन" offSpacer="true" %}}

```cs
>> pip install aspose-imaging-python-net
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Python के माध्यम से PNGs में पृष्ठभूमि बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

आपको [aspose-imaging-python-net](https://pypi.org/project/aspose-imaging-python-net/) की जरूरत है ताकि आप अपने खुद के माहौल में नीचे दिए गए वर्कफ़्लो को आज़मा सकें।

{{% /blocks/products/pf/agp/text %}}

+ लोड PNG छवि के साथ फ़ाइलें। लोड विधि
+ पृष्ठभूमि बदलें;
+ Aspose द्वारा समर्थित डिस्क में छवि सहेजें। इमेजिंग प्रारूप

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for Python सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज/लिनक्स .NET कोर रनटाइम के साथ।
- पायथन और PyPi पैकेज मैनेजर।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PNG छवियों में पृष्ठभूमि बदलें - Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "291380aac991e0869dbabba3e60f5225" "remove-change-background-generic-examples.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Imaging for Python API . के बारे में" %}}


Aspose.Imaging API अनुप्रयोगों के भीतर छवियों (फ़ोटो) को बनाने, संशोधित करने, आकर्षित करने या परिवर्तित करने के लिए एक छवि प्रसंस्करण समाधान है। यह प्रदान करता है: क्रॉस-प्लेटफ़ॉर्म छवि प्रसंस्करण, जिसमें विभिन्न छवि प्रारूपों (समान बहु-पृष्ठ या बहु-फ़्रेम छवि प्रसंस्करण सहित) के बीच रूपांतरण शामिल हैं, लेकिन इन्हीं तक सीमित नहीं है, ड्राइंग जैसे संशोधन, ग्राफिक प्राइमेटिव के साथ काम करना, परिवर्तन (आकार बदलना, फसल करना, फ्लिप करना और घुमाना) , बिनाराइज़ेशन, ग्रेस्केल, एडजस्ट), उन्नत छवि हेरफेर सुविधाएँ (फ़िल्टरिंग, डिथरिंग, मास्किंग, डेस्क्यूइंग), और मेमोरी ऑप्टिमाइज़ेशन रणनीतियाँ। यह एक स्टैंडअलोन लाइब्रेरी है और इमेज ऑपरेशंस के लिए किसी सॉफ्टवेयर पर निर्भर नहीं है। परियोजनाओं के भीतर देशी एपीआई के साथ आसानी से उच्च-प्रदर्शन छवि रूपांतरण सुविधाएँ जोड़ सकते हैं। ये 100% निजी ऑन-प्रिमाइसेस एपीआई हैं और छवियों को आपके सर्वर पर संसाधित किया जाता है।


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="ऑनलाइन ऐप के द्वारा PNGs में पृष्ठभूमि बदलें" sectionDescription="हमारी [लाइव डेमो वेबसाइट](https://products.aspose.app/imaging/remove-background) पर जाकर PNG दस्तावेज़ों में पृष्ठभूमि बदलें। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="कोई कोड लिखने की जरूरत नहीं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="बस अपनी PNG फ़ाइलें अपलोड करें और अब पृष्ठभूमि बदलें बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="परिणामी फ़ाइल के लिए तुरंत डाउनलोड लिंक प्राप्त करें" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="PNG" readMoreLink="https://docs.fileformat.com/image/png/" whatIsFormat1="क्या है" whatIsFormat2="फाइल का प्रारूप" readMoreFormat="अधिक पढ़ें" >}}
पीएनजी, पोर्टेबल नेटवर्क ग्राफिक्स, एक प्रकार के रेखापुंज छवि फ़ाइल स्वरूप को संदर्भित करता है जो दोषरहित संपीड़न का उपयोग करता है। यह फ़ाइल स्वरूप ग्राफ़िक्स इंटरचेंज फ़ॉर्मेट (GIF) के प्रतिस्थापन के रूप में बनाया गया था और इसकी कोई कॉपीराइट सीमा नहीं है। हालाँकि, PNG फ़ाइल स्वरूप एनिमेशन का समर्थन नहीं करता है। पीएनजी फ़ाइल स्वरूप दोषरहित छवि संपीड़न का समर्थन करता है जो इसे अपने उपयोगकर्ताओं के बीच लोकप्रिय बनाता है। समय बीतने के साथ, पीएनजी ज्यादातर उपयोग की जाने वाली छवि फ़ाइल प्रारूप में से एक के रूप में विकसित हुआ है। लगभग सभी ऑपरेटिंग सिस्टम में पीएनजी फाइलें खोलने के लिए सपोर्ट होता है। उदाहरण के लिए, माइक्रोसॉफ्ट विंडोज व्यूअर में पीएनजी फाइलों को खोलने की क्षमता है क्योंकि ओएस के पास डिफ़ॉल्ट रूप से इंस्टॉलेशन के हिस्से के रूप में उपलब्ध समर्थन है।
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित परिवर्तन पृष्ठभूमि प्रारूप" subTitle="Python का उपयोग करके, कोई भी व्यक्ति विभिन्न स्वरूपों में पृष्ठभूमि को आसानी से बदल सकता है, जिसमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/apng/" name="APNG" description="एनिमेटेड पोर्टेबल नेटवर्क ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/bmp/" name="BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/ico/" name="ICO" description="विंडोज आइकन" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/jpg/" name="JPG" description="फ़ोटोग्राफ़ी संबंधी विशेषज्ञों का संयुक्त समूह" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/dib/" name="DIB" description="डिवाइस स्वतंत्र बिटमैप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/dicom/" name="DICOM" description="डिजिटल इमेजिंग और संचार" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/djvu/" name="DJVU" description="ग्राफिक्स प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/dng/" name="DNG" description="डिजिटल कैमरा छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/emf/" name="EMF" description="उन्नत मेटाफ़ाइल प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/emz/" name="EMZ" description="विंडोज कम्प्रेस्ड एन्हांस्ड मेटाफाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/gif/" name="GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/jp2/" name="JP2" description="जेपीईजी 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/j2k/" name="J2K" description="तरंगिका संपीड़ित छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/tiff/" name="TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/webp/" name="WEBP" description="रेखापुंज वेब छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/wmf/" name="WMF" description="माइक्रोसॉफ्ट विंडोज मेटाफाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/wmz/" name="WMZ" description="संपीड़ित विंडोज मीडिया प्लेयर त्वचा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/tga/" name="TGA" description="टार्गा ग्राफिक" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/svg/" name="SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/eps/" name="EPS" description="एनकैप्सुलेटेड पोस्टस्क्रिप्ट भाषा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/cdr/" name="CDR" description="वेक्टर ड्राइंग छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/cmx/" name="CMX" description="कोरल एक्सचेंज इमेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/otg/" name="OTG" description="OpenDocument मानक" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/odg/" name="ODG" description="अपाचे ओपनऑफिस ड्रा प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/python-net/change-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}