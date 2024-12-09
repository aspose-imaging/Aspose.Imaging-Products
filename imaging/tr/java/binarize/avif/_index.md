﻿---
title: AVIF belgelerini Java aracılığıyla ikili hale getirin 
weight: 3920
url: /tr/java/binarize/avif/ 
lang: tr
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: AVIF dosyalarını .NET Framework, .NET Core, Windows Uygulaması, ASP.NET Web Uygulamasında Binarize etmek için Şirket İçi belge API'lerimizi deneyin.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="AVIF'leri Java aracılığıyla ikili hale getirin" h2="Sunucu tarafı API'lerini kullanarak AVIF dosyalarını Binarize etmek için kendi Java uygulamalarınızı oluşturun." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="AVIF" pfName="Aspose.Imaging" subTitlepfName="Java için" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="Java için" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/tr/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="API Ana Sayfası" codeSamplesText="Kod örnekleri" liveDemosText="Canlı Demolar" downloadText="İndirmek" learnText="Öğrenmek">}}

{{% blocks/products/pf/agp/content h2="Java Kullanarak AVIF Dosyalarını Binarize Etme" %}}

Renkli filmin icadı fotoğrafçılık alanında önemli bir dönüm noktası oldu. Ancak klasik fotoğrafçılık doğası gereği siyah beyaz görüntülerle bağlantılıdır. Kameraların tüm renk yelpazesini yakalamaya yönelik kapsamlı teknik yeteneklerine rağmen, birçok kişi monokromu tercih ederek fotoğraflarını siyah beyaza dönüştürüyor. Bu gibi durumlarda, tüm pikselleri ikili değerlere dönüştüren bir ikilileştirme işlevi devreye girer: beyaz için \"0\" ve siyah için \"1\". Diğer senaryolarda, bu dönüşüm sanatsal seçimlerden değil, kitap veya gazetelerde basılmak üzere siyah beyaz illüstrasyonlar hazırlamak gibi pratik tercihlerden kaynaklanıyor. Java grafik kitaplığını kullanarak bir piksel parlaklık eşiği belirleyebilirsiniz. Parlaklık değeri bu eşiğin altında olan pikseller siyaha, üstünde olanlar ise beyaza dönüşecektir. Alternatif olarak çevredeki piksel değerlerini dikkate alan uyarlanabilir bir ikilileştirme yöntemini kullanabilirsiniz. Bu yaklaşım, ortaya çıkan siyah beyaz görüntüde renk sınırları arasında daha yumuşak geçişler sağlar. AVIF dosyalarını Binarize etmek için şunu kullanacağız: [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) Java platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir görüntü işleme ve dönüştürme API'si olan API. En son sürümünü doğrudan adresinden indirebilirsiniz. [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

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

{{% blocks/products/pf/agp/feature-section-col title="AVIF'leri Java aracılığıyla İkilileştirme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

ihtiyacın var [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) aşağıdaki iş akışını kendi ortamınızda denemek için

{{% /blocks/products/pf/agp/text %}}

+ AVIF dosyalarını Image.Load yöntemiyle yükleyin
+ Görüntüleri ikili hale getirin;
+ Sıkıştırılmış görüntüyü Aspose.Imaging formatında diske kaydedin

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging for Java tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 veya üstü yüklü.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="AVIF görüntüleri ikili hale getirin - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "daac19b481878f17e5e6caadd16bb490" "binarize-images.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Java API için Aspose.Imaging Hakkında" %}}


Aspose.Imaging API, uygulamalar içinde görüntüleri (fotoğrafları) oluşturmak, değiştirmek, çizmek veya dönüştürmek için kullanılan bir görüntü işleme çözümüdür. Şunları sunar: Çeşitli görüntü formatları (tek tip çok sayfalı veya çok çerçeveli görüntü işleme dahil) arasındaki dönüştürmeler dahil ancak bunlarla sınırlı olmamak üzere çapraz platform Görüntü işleme, çizim, grafik temel öğeleriyle çalışma, dönüştürmeler (yeniden boyutlandırma, kırpma, çevirme ve döndürme) gibi değişiklikler , ikilileştirme, gri tonlama, ayarlama), gelişmiş görüntü işleme özellikleri (filtreleme, renk taklidi, maskeleme, eğrilik düzeltme) ve bellek optimizasyon stratejileri. Bu bağımsız bir kitaplıktır ve görüntü işlemleri için herhangi bir yazılıma bağlı değildir. Projelere yerel API'ler ile yüksek performanslı görüntü dönüştürme özellikleri kolayca eklenebilir. Bunlar %100 özel şirket içi API'lerdir ve görüntüler sunucularınızda işlenir.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="AVIF'leri Çevrimiçi Uygulama ile Binarize edin" sectionDescription="[Canlı Demolar web sitemizi](https://products.aspose.app/imaging/image-Binarize) ziyaret ederek AVIF belgelerini Binarize edin. Canlı demo aşağıdaki avantajlara sahiptir" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Herhangi bir kod yazmaya gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Sadece AVIF dosyalarınızı yükleyin ve \"Şimdi İkilileştir\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Ortaya çıkan dosyanın indirme bağlantısını anında alın" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="Nedir" whatIsFormat2="Dosya formatı" readMoreFormat="Daha fazla oku" >}}

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Binarize Formatları" subTitle="Java kullanarak, dahil olmak üzere farklı formatları kolayca Binarize edebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/apng/" name="APNG" description="Hareketli Taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/bmp/" name="BMP" description="Bitmap Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/ico/" name="ICO" description="Windows simgesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/jpg/" name="JPG" description="Birleşmiş Fotoğraf Uzmanları Grubu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/jpeg/" name="JPEG" description="Birleşmiş Fotoğraf Uzmanları Grubu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/dib/" name="DIB" description="Cihazdan Bağımsız Bit Eşlem" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/dicom/" name="DICOM" description="Dijital Görüntüleme ve İletişim" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/djvu/" name="DJVU" description="Grafik Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/dng/" name="DNG" description="Dijital Kamera Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/emf/" name="EMF" description="Gelişmiş Meta Dosyası Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/emz/" name="EMZ" description="Windows Sıkıştırılmış Gelişmiş Meta Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/gif/" name="GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/j2k/" name="J2K" description="Dalgacık Sıkıştırılmış Görüntü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/png/" name="PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/tiff/" name="TIFF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/tif/" name="TIF" description="Etiketli Görüntü Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/webp/" name="WEBP" description="Raster Web Resmi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/wmf/" name="WMF" description="Microsoft Windows Meta Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/wmz/" name="WMZ" description="Sıkıştırılmış Windows Media Player Dış Görünümü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/tga/" name="TGA" description="Targa Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/svg/" name="SVG" description="ölçeklendirilebilir Vektör Grafiği" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/eps/" name="EPS" description="Kapsüllenmiş PostScript Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/cdr/" name="CDR" description="Vektör Çizim Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/cmx/" name="CMX" description="Corel Exchange Görüntüsü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/otg/" name="OTG" description="OpenDocument Standardı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/tr/java/binarize/odg/" name="ODG" description="Apache OpenOffice Çizim Formatı" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}