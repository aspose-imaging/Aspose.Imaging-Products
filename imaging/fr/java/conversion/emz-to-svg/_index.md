﻿---
title: Convertir EMZ en SVG via Java 
weight: 3920
url: /fr/java/conversion/emz-to-svg/ 
lang: fr
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Exemple de code pour la conversion Java EMZ vers SVG. Utilisez un exemple de code d'API pour la conversion par lots de fichiers EMZ en SVG dans n'importe quelle application Java Web ou de bureau.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convertir EMZ en SVG via Java" h2="Transformez EMZ en SVG à l'aide des API natives Java sans avoir besoin d'un éditeur d'images ou de bibliothèques tierces." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="SVG" pfName="Aspose.Imaging" subTitlepfName="pour Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="pour Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/fr/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/fr/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Accueil API" codeSamplesText="Exemples de code" liveDemosText="Démos en direct" downloadText="Télécharger" learnText="Apprendre" overviewText="Aperçu" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir EMZ en SVG en utilisant Java" %}}

La conversion de formats de fichiers peut sembler une tâche routinière rencontrée par les graphistes. Pourtant, sous-estimer son importance serait une erreur. L'évaluation de votre travail peut dépendre de la rapidité et de l'efficacité avec lesquelles vous vous acquittez de cette tâche. En règle générale, les images originales doivent être converties dans des formats mieux adaptés à l'impression ou à la publication en ligne. Si l'image originale provient d'un éditeur graphique, elle peut être au format vectoriel. Dans ce scénario, il doit être pixellisé et converti au format raster à des fins de publication. Vous avez le choix d'enregistrer l'image dans un format non compressé pour une qualité optimale ou de la convertir dans un format compressé sans perte pour réduire la taille du fichier. Dans certains contextes, comme la publication Web, vous pouvez opter pour des formats compressés avec perte. Des algorithmes spécialement conçus pour la compression des données d'image permettent une réduction significative de la taille du fichier tout en préservant une qualité d'image acceptable. Cela facilite les téléchargements rapides de fichiers d’images à partir d’Internet. Afin de convertir EMZ en SVG, nous utiliserons [Aspose.Imaging pour Java](https://products.aspose.com/imaging/java) API qui est une API de manipulation et de conversion d'images riche en fonctionnalités, puissante et facile à utiliser pour la plate-forme Java. Vous pouvez télécharger sa dernière version directement depuis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au fichier pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```xml
<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dépendance" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir EMZ en SVG via Java" %}}

{{% blocks/products/pf/agp/text %}}

Les développeurs peuvent facilement charger et convertir des fichiers EMZ en SVG en quelques lignes de code seulement.

{{% /blocks/products/pf/agp/text %}}

+ Charger le fichier EMZ avec la méthode Image.load
+ Créer et définir l'instance de la sous-classe requise de ImageOptionsBase (par exemple, BmpOptions, PngOptions, etc.)
+ Appelez la méthode Image.save
+ Passer le chemin du fichier avec l'extension SVG et l'objet de la classe ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

Avant d'exécuter l'exemple de code de conversion, assurez-vous que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

+ Système d'exploitation : Windows ou Linux.
+ Environnement de développement : prend en charge .NET Core 7 et supérieur, tel que Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Application gratuite pour convertir EMZ en SVG"
        appName="Conversion"
        extension="EMZ-to-SVG"
        label1="Sélectionnez ou faites glisser et déposez l'image EMZ"
        label2="Choisissez le format et cliquez sur le bouton Convertir"
        label3="Cliquez sur le bouton Télécharger pour télécharger l'image SVG"
        checkFreeAppLabel="Consultez nos [démos en direct pour convertir EMZ en SVG]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/fr/conversion/EMZ-to-SVG)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Convertir EMZ en SVG - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="EMZ" readMoreLink="https://docs.fileformat.com/image/emz/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite | EMZ">}}
Un fichier avec l'extension de fichier EMZ est un fichier image compressé, plus spécifiquement appelé fichier de métafichier amélioré compressé Windows.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="SVG" readMoreLink="https://docs.fileformat.com/image/svg/" whatIsFormat1="Qu'est-ce que" whatIsFormat2="Format de fichier" readMoreFormat="Lire la suite | SVG">}}
Les fichiers SVG sont des fichiers graphiques vectoriels évolutifs qui utilisent un format de texte basé sur XML pour décrire l'apparence de l'image. Le mot Scalable fait référence au fait que le SVG peut être mis à l'échelle à différentes tailles sans perte de qualité. La description textuelle de ces fichiers les rend indépendants de la résolution. C'est l'un des formats les plus utilisés pour créer des sites Web et des graphiques d'impression afin d'atteindre l'évolutivité. Le format ne peut cependant être utilisé que pour les graphiques en deux dimensions. Les fichiers SVG peuvent être visualisés/ouverts dans presque tous les navigateurs modernes, y compris Chrome, Internet Explorer, Firefox et Safari.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="En utilisant Java, on peut facilement convertir différents formats, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-bmp/" name="BMP" description="Image bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-gif/" name="GIF" description="Format d'échange graphique" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-dicom/" name="DICOM" description="Imagerie numérique et communications" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-emf/" name="EMF" description="Format de métafichier amélioré" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-jpg/" name="JPG" description="Groupe mixte d'experts photographiques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-jpeg/" name="JPEG" description="Groupe mixte d'experts photographiques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-j2k/" name="J2K" description="Image compressée en ondelettes" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-png/" name="PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-apng/" name="APNG" description="Graphiques de réseau portables animés" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-psd/" name="PSD" description="Document Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-dxf/" name="DXF" description="Format d'échange de dessin, ou Format d'échange de dessin," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-svg/" name="SVG" description="Image Vectorielle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-tiff/" name="TIFF" description="Format d'image balisé" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-webp/" name="WEBP" description="Image Web raster" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-wmf/" name="WMF" description="Métafichier Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-pdf/" name="PDF" description="Format de document portable (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-html/" name="HTML" description="Canevas HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-wmz/" name="WMZ" description="Skin du lecteur Windows Media compressé" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-tga/" name="TGA" description="Graphique Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-svgz/" name="SVGZ" description="Version compressée du fichier Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-canvas/" name="CANVAS" description="Canevas HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/fr/java/conversion/emz-to-ico/" name="ICO" description="Icône Windows" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
