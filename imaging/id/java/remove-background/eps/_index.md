﻿---
title: Hapus latar belakang dalam dokumen EPS melalui Java 
weight: 3920
url: /id/java/remove-background/eps/ 
lang: id
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Coba API dokumen Lokal kami untuk mengubah latar belakang dari file EPS di Aplikasi Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Hapus latar belakang dari EPS melalui Java" h2="Buat aplikasi Java Anda sendiri untuk Menghapus latar belakang dari file EPS menggunakan API sisi server." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EPS" pfName="Aspose.Imaging" subTitlepfName="untuk Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="untuk Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/id/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Beranda API" codeSamplesText="Contoh kode" liveDemosText="Demo Langsung" downloadText="Unduh" learnText="Mempelajari">}}

{{% blocks/products/pf/agp/content h2="Cara menghapus latar belakang di File EPS Menggunakan Java" %}}

Menghapus latar belakang dari suatu gambar melibatkan isolasi objek latar depan, sebuah tugas yang memerlukan pengenalan objek. Terdapat berbagai pendekatan untuk mengidentifikasi objek dalam foto dalam format EPS. Untuk gambar sederhana yang menampilkan latar belakang warna seragam, metode otomatis sudah cukup. Namun, untuk foto dengan beberapa atau sebagian gambar yang digabungkan, penandaan awal pada objek menjadi diperlukan. Ini melibatkan penentuan wilayah persegi panjang dan tipe objek yang akan dihapus. Dalam kasus yang rumit, Cloud API memungkinkan deteksi objek otomatis. Cloud API menyediakan aplikasi cloud yang mampu mengenali objek dalam foto, memanfaatkan kontur yang dihasilkan untuk menghilangkan latar belakang. Pasca-penghapusan, tepian yang ditinggalkan gambar dapat diperhalus untuk meningkatkan kualitas gambar. Untuk menghapus latar belakang pada file EPS, kami akan menggunakan [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API yang kaya fitur, kuat dan mudah digunakan manipulasi gambar dan konversi API untuk platform Java. Anda dapat mengunduh versi terbarunya langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Menghapus latar belakang dari EPS melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

Anda membutuhkan [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) untuk mencoba alur kerja berikut di lingkungan Anda sendiri.

{{% /blocks/products/pf/agp/text %}}

+ Muat file EPS dengan metode Image.load
+ Hapus latar belakang;
+ Simpan gambar ke disk dalam format Aspose.Imaging yang didukung

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging untuk Java didukung di semua sistem operasi utama. Pastikan saja Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 atau lebih tinggi diinstal.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Hapus latar belakang dalam gambar EPS - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Tentang Aspose.Imaging untuk Java API" %}}


Aspose.Imaging API adalah solusi pemrosesan gambar untuk membuat, memodifikasi, menggambar, atau mengonversi gambar (foto) dalam aplikasi. Menawarkan: pemrosesan gambar lintas platform, termasuk tetapi tidak terbatas pada konversi antara berbagai format gambar (termasuk pemrosesan gambar multi-halaman atau multi-bingkai yang seragam), modifikasi seperti menggambar, bekerja dengan grafik primitif, transformasi (mengubah ukuran, memotong, membalik & memutar , binarisasi, skala abu-abu, sesuaikan), fitur manipulasi gambar lanjutan (pemfilteran, dithering, masking, deskewing), dan strategi pengoptimalan memori. Ini adalah perpustakaan mandiri dan tidak bergantung pada perangkat lunak apa pun untuk operasi gambar. Seseorang dapat dengan mudah menambahkan fitur konversi gambar berkinerja tinggi dengan API asli dalam proyek. Ini adalah 100% API lokal pribadi dan gambar diproses di server Anda.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Hapus latar belakang dalam EPS melalui Aplikasi Online" sectionDescription="Hapus latar belakang dalam dokumen EPS dengan mengunjungi [situs web Live Demos](https://products.aspose.app/imaging/remove-background) kami. Demo langsung memiliki manfaat sebagai berikut" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Tidak perlu mengunduh atau mengatur apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Tidak perlu menulis kode apa pun" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Cukup unggah file EPS Anda dan tekan tombol \"Hapus latar belakang sekarang\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Langsung dapatkan tautan unduhan untuk file yang dihasilkan" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EPS" readMoreLink="https://docs.fileformat.com/image/eps/" whatIsFormat1="Apa" whatIsFormat2="Format Berkas" readMoreFormat="Baca selengkapnya" >}}
File dengan ekstensi EPS pada dasarnya menggambarkan program bahasa Encapsulated PostScript yang menggambarkan tampilan satu halaman. Nama "Encapsulated" karena dapat dimasukkan atau dienkapsulasi dalam deskripsi halaman bahasa PostScript lain. Format file berbasis skrip ini dapat berisi kombinasi teks, grafik, dan gambar. File EPS dapat menyertakan gambar pratinjau bitmap yang dienkapsulasi di dalam untuk ditampilkan oleh aplikasi yang dapat membuka file tersebut. File EPS dapat dikonversi ke format gambar standar seperti JPG, PNG, TIFF dan PDF menggunakan aplikasi yang berbeda mis. Adobe Ilustrator, Photoshop dan PaintShop Pro. Karena kerentanan keamanan dalam file EPS, Office 2016, Office 2013, Office 2010, dan Office 365 telah menonaktifkan kemampuan untuk menyisipkan file EPS ke dalam dokumen Office.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Format Hapus Latar Belakang Lainnya yang Didukung" subTitle="Menggunakan Java, seseorang dapat dengan mudah menghapus latar belakang dari berbagai format termasuk." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/apng/" name="APNG" description="Grafik Jaringan Portabel Animasi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/bmp/" name="BMP" description="Gambar Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/ico/" name="ICO" description="ikon Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/jpg/" name="JPG" description="Kelompok Ahli Fotografi Bersama" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/dib/" name="DIB" description="Bitmap Independen Perangkat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/dicom/" name="DICOM" description="Pencitraan & Komunikasi Digital" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/djvu/" name="DJVU" description="Format Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/dng/" name="DNG" description="Gambar Kamera Digital" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/emf/" name="EMF" description="Format Metafile yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/emz/" name="EMZ" description="Metafile Terkompresi Windows yang Ditingkatkan" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/gif/" name="GIF" description="Format Pertukaran Grafis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/j2k/" name="J2K" description="Gambar Terkompresi Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/png/" name="PNG" description="Grafik Jaringan Portabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/tiff/" name="TIFF" description="Format Gambar yang Ditandai" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/webp/" name="WEBP" description="Gambar Web Raster" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/wmf/" name="WMF" description="Metafile Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/wmz/" name="WMZ" description="Kulit Windows Media Player Terkompresi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/tga/" name="TGA" description="Grafis Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/svg/" name="SVG" description="Grafik Vektor Skalabel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/cdr/" name="CDR" description="Gambar Gambar Vektor" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/cmx/" name="CMX" description="Corel Exchange Gambar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/otg/" name="OTG" description="Standar Dokumen Terbuka" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/odg/" name="ODG" description="Format Undian Apache OpenOffice" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/id/java/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
