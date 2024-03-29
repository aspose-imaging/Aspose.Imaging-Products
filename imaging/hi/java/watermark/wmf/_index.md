﻿---
title: Java के माध्यम से वॉटरमार्क WMF दस्तावेज़ 
weight: 3920
url: /hi/java/watermark/wmf/ 
lang: hi
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: WMF प्रारूप के लिए  फ़ाइल के लिए नमूना जावा रूपांतरण कोड। किसी भी वेब या डेस्कटॉप जावा आधारित एप्लिकेशन में WMF को  में बदलने के लिए इस उदाहरण कोड का उपयोग करें।
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java के माध्यम से टेक्स्ट वॉटरमार्क को WMF में जोड़ें" h2="सर्वर-साइड API का उपयोग करके WMF फ़ाइलों को वॉटरमार्क करने के लिए अपने स्वयं के Java ऐप्स बनाएं।" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="WMF" pfName="Aspose.Imaging" subTitlepfName="Java के लिए" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java के लिए" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/hi/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="एपीआई होम" codeSamplesText="कोड नमूने" liveDemosText="लाइव डेमो" downloadText="डाउनलोड" learnText="सीखना">}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके WMF फ़ाइल को वॉटरमार्क कैसे करें" %}}

इंटरनेट पर अपने काम के लिए अधिकतम प्रदर्शन चाहने वाले लेखकों के लिए वॉटरमार्क एक आवश्यक उपकरण है। किसी छवि पर वॉटरमार्क लगाने से न केवल उसके स्रोत या कॉपीराइट धारक की पहचान होती है, बल्कि उसके निर्माता का प्रचार भी होता है। ऐसा इसलिए है क्योंकि लेखक का नाम या इंटरनेट संसाधन का नाम वाला हस्ताक्षर छवि की डिजिटल प्रतिलिपि के साथ वितरित किया जाता है। वॉटरमार्क फ़ॉन्ट की एक विस्तृत श्रृंखला के साथ टेक्स्ट का रूप ले सकते हैं और छवि के किनारे पर स्थित हो सकते हैं। जब वॉटरमार्क पारदर्शी होता है, तो यह देखने में बाधा नहीं डालता है। हालाँकि, यदि लेखक या कॉपीराइट धारक अपने नाम पर ज़ोर देना चाहता है, तो वॉटरमार्क छवि को आंशिक रूप से ओवरलैप कर सकता है। WMF छवि फ़ाइल को वॉटरमार्क करने के लिए, हम इसका उपयोग करेंगे [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API जो एक सुविधा संपन्न, शक्तिशाली और जावा प्लेटफॉर्म के लिए छवि हेरफेर और रूपांतरण एपीआई का उपयोग करने में आसान है। आप इसका नवीनतम संस्करण सीधे [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) से डाउनलोड कर सकते हैं और इसे अपने मावेन में इंस्टॉल कर सकते हैं -आधारित परियोजना pom.xml में निम्नलिखित विन्यास जोड़कर।

{{% blocks/products/pf/agp/code-block title="रिपॉजिटरी" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="true" %}}

```xml
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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से WMF में वॉटरमार्क जोड़ने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

अपने स्वयं के वातावरण में निम्नलिखित वर्कफ़्लो को आज़माने के लिए आपको [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) की आवश्यकता होगी।

{{% /blocks/products/pf/agp/text %}}

+ लोड WMF फ़ाइल Image.load विधि के साथ
+ छवि से ग्राफिक्स का उदाहरण बनाएं
+ वॉटरमार्क टेक्स्ट के लिए फ़ॉन्ट, ब्रश और प्रारूप को परिभाषित करें
+ ग्राफिक्स.ड्रास्ट्रिंग विधि का उपयोग करके वॉटरमार्क बनाएं
+ छवि को WMF प्रारूप में डिस्क में सहेजें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for Java सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 या उच्चतर स्थापित है।

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="वॉटरमार्क WMF इमेज - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "1ac443cce5aab9d32ad152570c716c05" "watermark-wmf-image.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.Imaging for Java API . के बारे में" %}}


Aspose.Imaging API अनुप्रयोगों के भीतर छवियों (फ़ोटो) को बनाने, संशोधित करने, आकर्षित करने या परिवर्तित करने के लिए एक छवि प्रसंस्करण समाधान है। यह प्रदान करता है: क्रॉस-प्लेटफ़ॉर्म छवि प्रसंस्करण, जिसमें विभिन्न छवि प्रारूपों (समान बहु-पृष्ठ या बहु-फ़्रेम छवि प्रसंस्करण सहित) के बीच रूपांतरण शामिल हैं, लेकिन इन्हीं तक सीमित नहीं है, ड्राइंग जैसे संशोधन, ग्राफिक प्राइमेटिव के साथ काम करना, परिवर्तन (आकार बदलना, फसल करना, फ्लिप करना और घुमाना) , बिनाराइज़ेशन, ग्रेस्केल, एडजस्ट), उन्नत छवि हेरफेर सुविधाएँ (फ़िल्टरिंग, डिथरिंग, मास्किंग, डेस्क्यूइंग), और मेमोरी ऑप्टिमाइज़ेशन रणनीतियाँ। यह एक स्टैंडअलोन लाइब्रेरी है और इमेज ऑपरेशंस के लिए किसी सॉफ्टवेयर पर निर्भर नहीं है। परियोजनाओं के भीतर देशी एपीआई के साथ आसानी से उच्च-प्रदर्शन छवि रूपांतरण सुविधाएँ जोड़ सकते हैं। ये 100% निजी ऑन-प्रिमाइसेस एपीआई हैं और छवियों को आपके सर्वर पर संसाधित किया जाता है।


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="वॉटरमार्क WMF ऑनलाइन ऐप के माध्यम से" sectionDescription="हमारी [लाइव डेमो वेबसाइट](https://products.aspose.app/imaging/watermark) पर जाकर WMF दस्तावेज़ों में वॉटरमार्क जोड़ें। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="कोई कोड लिखने की जरूरत नहीं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="बस अपनी WMF फ़ाइल अपलोड करें, अपना वॉटरमार्क सेट करें और जोड़ें बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="परिणामी फ़ाइल के लिए तुरंत डाउनलोड लिंक प्राप्त करें" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="WMF" readMoreLink="https://docs.fileformat.com/image/wmf/" whatIsFormat1="क्या है" whatIsFormat2="फाइल का प्रारूप" readMoreFormat="अधिक पढ़ें" >}}
WMF एक्सटेंशन वाली फाइलें वेक्टर के साथ-साथ बिटमैप-फॉर्मेट इमेज डेटा को स्टोर करने के लिए माइक्रोसॉफ्ट विंडोज मेटाफाइल (WMF) का प्रतिनिधित्व करती हैं। अधिक सटीक होने के लिए, WMF ग्राफ़िक्स फ़ाइल स्वरूपों की वेक्टर फ़ाइल स्वरूप श्रेणी से संबंधित है जो डिवाइस स्वतंत्र है। विंडोज ग्राफिकल डिवाइस इंटरफेस (जीडीआई) स्क्रीन पर एक छवि प्रदर्शित करने के लिए डब्लूएमएफ फाइल में संग्रहीत कार्यों का उपयोग करता है। WMF का एक अधिक उन्नत संस्करण, जिसे एन्हांस्ड मेटा फाइल्स (EMF) के रूप में जाना जाता है, बाद में प्रकाशित किया गया था जो प्रारूप को अधिक सुविधा संपन्न बनाता है। व्यावहारिक रूप से, WMF SVG के समान हैं।
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित वॉटरमार्किंग प्रारूप" subTitle="Java का उपयोग करके, कोई भी व्यक्ति आसानी से विभिन्न प्रारूपों को वॉटरमार्क कर सकता है, जिसमें शामिल हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/bmp/" name="BMP" description="बिटमैप चित्र" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/ico/" name="ICO" description="विंडोज आइकन" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/dib/" name="DIB" description="डिवाइस स्वतंत्र बिटमैप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/dicom/" name="DICOM" description="डिजिटल इमेजिंग और संचार" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/emf/" name="EMF" description="उन्नत मेटाफ़ाइल प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/gif/" name="GIF" description="ग्राफिकल इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/jp2/" name="JP2" description="जेपीईजी 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/j2k/" name="J2K" description="तरंगिका संपीड़ित छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/png/" name="PNG" description="पोर्टेबल नेटवर्क ग्राफ़िक्स" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/tiff/" name="TIFF" description="टैग की गई छवि प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/webp/" name="WEBP" description="रेखापुंज वेब छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/hi/java/watermark/svg/" name="SVG" description="स्केलेबल वेक्टर ग्राफिक्स" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
