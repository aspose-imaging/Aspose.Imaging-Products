﻿---
title: DICOM belgelerindeki arka planı Java aracılığıyla kaldırın 
weight: 3920
url: /tr/java/remove-background/dicom/ 
lang: tr
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Java Uygulamasında DICOM dosyalarından arka planı değiştirmek için Şirket İçi belge API'lerimizi deneyin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Java aracılığıyla DICOM'lerden arka planı kaldırın" h2="Sunucu tarafı API'lerini kullanarak DICOM dosyalarından arka planı kaldırmak için kendi Java uygulamalarınızı oluşturun." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="DICOM" pfName="Aspose.Imaging" subTitlepfName="Java için" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java için" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/tr/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API Ana Sayfası" codeSamplesText="Kod örnekleri" liveDemosText="Canlı Demolar" downloadText="İndirmek" learnText="Öğrenmek">}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak DICOM Dosyalarında arka plan nasıl kaldırılır" %}}

Bir görüntüden arka planı kaldırmak, ön plandaki nesnelerin yalıtılmasını içerir; bu, nesne tanımayı gerektiren bir görevdir. DICOM biçimindeki bir fotoğraftaki nesneleri tanımlamak için birden fazla yaklaşım mevcuttur. Tek tip renkli bir arka plana sahip basit görüntüler için otomatik bir yöntem yeterlidir. Ancak birden fazla veya kısmen birleştirilmiş figürlerin yer aldığı fotoğraflar için nesnelerin önceden işaretlenmesi gerekli hale gelir. Bu, kaldırılacak dikdörtgen bölgelerin ve nesne türlerinin belirtilmesini içerir. Karmaşık durumlarda Cloud API, otomatik nesne algılamayı mümkün kılar. Cloud API, fotoğraflardaki nesneleri tanıyabilen ve arka planın kaldırılması için ortaya çıkan konturlardan yararlanabilen bir bulut uygulaması sağlar. Çıkarma sonrasında şekillerin geride bıraktığı kenarlar görüntü kalitesini artırmak için yumuşatılabilir. DICOM dosyalarındaki arka planı kaldırmak için şunu kullanacağız: [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) Java platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir görüntü işleme ve dönüştürme API'si olan API. En son sürümünü doğrudan adresinden indirebilirsiniz. [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bağımlılık" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla DICOM'lerden arka planı kaldırma adımları" %}}

{{% blocks/products/pf/agp/text %}}

ihtiyacın var [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) aşağıdaki iş akışını kendi ortamınızda denemek için

{{% /blocks/products/pf/agp/text %}}

+ DICOM dosyalarını Image.load yöntemiyle yükleyin
+ Arka planı kaldır;
+ Resmi Aspose.Imaging formatında diske kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for Java tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 veya üstü yüklü.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DICOM resimlerdeki arka planı kaldırın - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Java API için Aspose.Imaging Hakkında" %}}


Aspose.Imaging API, uygulamalar içinde görüntüleri (fotoğrafları) oluşturmak, değiştirmek, çizmek veya dönüştürmek için kullanılan bir görüntü işleme çözümüdür. Şunları sunar: Çeşitli görüntü formatları (tek tip çok sayfalı veya çok çerçeveli görüntü işleme dahil) arasındaki dönüştürmeler dahil ancak bunlarla sınırlı olmamak üzere çapraz platform Görüntü işleme, çizim, grafik temel öğeleriyle çalışma, dönüştürmeler (yeniden boyutlandırma, kırpma, çevirme ve döndürme) gibi değişiklikler , ikilileştirme, gri tonlama, ayarlama), gelişmiş görüntü işleme özellikleri (filtreleme, renk taklidi, maskeleme, eğrilik düzeltme) ve bellek optimizasyon stratejileri. Bu bağımsız bir kitaplıktır ve görüntü işlemleri için herhangi bir yazılıma bağlı değildir. Projelere yerel API'ler ile yüksek performanslı görüntü dönüştürme özellikleri kolayca eklenebilir. Bunlar %100 özel şirket içi API'lerdir ve görüntüler sunucularınızda işlenir.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Çevrimiçi Uygulama aracılığıyla DICOM'lerdeki arka planı kaldırın" sectionDescription="[Canlı Demolar web sitemizi](https://products.aspose.app/imaging/remove-background) ziyaret ederek DICOM belgelerindeki arka planı kaldırın. Canlı demo aşağıdaki avantajlara sahiptir" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Herhangi bir kod yazmaya gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="DICOM dosyalarınızı yükleyin ve \"Arka planı şimdi kaldır\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Ortaya çıkan dosyanın indirme bağlantısını anında alın" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="DICOM" readMoreLink="https://docs.fileformat.com/image/dicom/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Daha fazla oku" >}}
DICOM, Tıpta Dijital Görüntüleme ve İletişimin kısaltmasıdır ve Tıp Bilişimi alanıyla ilgilidir. DICOM, dosya formatı tanımı ve bir ağ iletişim protokolünün birleşimidir. DICOM, .DCM uzantısını kullanır. .DCM, 1.x biçimi ve 2.x biçimi olmak üzere iki farklı biçimde bulunur. DCM Format 1.x ayrıca normal ve genişletilmiş iki versiyonda mevcuttur. DICOM, çeşitli satıcılara ait yazıcılar, sunucular, tarayıcılar vb. tıbbi görüntüleme cihazlarının entegrasyonu için kullanılır ve ayrıca benzersizlik için her hastanın kimlik verilerini içerir. DICOM dosyaları, DICOM formatında görüntü verilerini alabiliyorlarsa, iki taraf arasında paylaşılabilir. DICOM'un iletişim kısmı, uygulama katmanı protokolüdür ve varlıklar arasında iletişim kurmak için TCP/IP kullanır. DICOM'un web hizmetleri için HTTP ve HTTPS protokolleri kullanılır. Web servisleri tarafından desteklenen sürümler 1.0, 1.1, 2 veya üstüdür.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Arka Plan Biçimlerini Kaldır" subTitle="Java kullanarak, arka planı da dahil olmak üzere farklı biçimlerden kolayca kaldırabilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/apng/" name="APNG" description="Hareketli Taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/bmp/" name="BMP" description="Bitmap Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/ico/" name="ICO" description="Windows simgesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/jpg/" name="JPG" description="Birleşmiş Fotoğraf Uzmanları Grubu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/dib/" name="DIB" description="Cihazdan Bağımsız Bit Eşlem" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/djvu/" name="DJVU" description="Grafik Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/dng/" name="DNG" description="Dijital Kamera Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/emf/" name="EMF" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/emz/" name="EMZ" description="Windows Sıkıştırılmış Gelişmiş Meta Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/gif/" name="GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/j2k/" name="J2K" description="Dalgacık Sıkıştırılmış Görüntü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/png/" name="PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/tiff/" name="TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/webp/" name="WEBP" description="Raster Web Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/wmf/" name="WMF" description="Microsoft Windows Meta Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/wmz/" name="WMZ" description="Sıkıştırılmış Windows Media Player Dış Görünümü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/tga/" name="TGA" description="Targa Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/svg/" name="SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/eps/" name="EPS" description="Kapsüllenmiş PostScript Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/cdr/" name="CDR" description="Vektör Çizim Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/cmx/" name="CMX" description="Corel Exchange Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/otg/" name="OTG" description="OpenDocument Standardı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/odg/" name="ODG" description="Apache OpenOffice Çizim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
