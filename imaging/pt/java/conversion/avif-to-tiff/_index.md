﻿---
title: Converter AVIF para TIFF via Java 
weight: 3920
url: /pt/java/conversion/avif-to-tiff/ 
lang: pt
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Código de exemplo para conversão Java de AVIF para TIFF. Use o código de exemplo da API para arquivos em lote AVIF para conversão TIFF em qualquer aplicativo baseado em Java da Web ou Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Converter AVIF para TIFF via Java" h2="Transforme AVIF em TIFF usando APIs Java nativas sem precisar de nenhum editor de imagens ou bibliotecas de terceiros." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="Aspose.Imaging" subTitlepfName="para Java" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="para Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/pt/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/pt/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Página inicial da API" codeSamplesText="Amostras de código" liveDemosText="Demonstrações ao vivo" downloadText="Download" learnText="Aprender" overviewText="Visão geral" >}}

{{% blocks/products/pf/agp/content h2="Como converter AVIF para TIFF usando Java" %}}

A conversão de formatos de arquivo pode parecer uma tarefa rotineira encontrada pelos designers gráficos. No entanto, subestimar a sua importância seria um erro. A avaliação do seu trabalho pode depender da rapidez e eficácia com que você realiza essa tarefa. Normalmente, as imagens originais precisam ser convertidas em formatos mais adequados para impressão ou publicação online. Se a imagem original for proveniente de um editor gráfico, ela poderá estar em formato vetorial. Neste cenário, ele deve ser rasterizado e convertido em formato raster para fins de publicação. Você tem a opção de salvar a imagem em um formato descompactado para obter qualidade ideal ou convertê-la em um formato compactado sem perdas para reduzir o tamanho do arquivo. Em certos contextos, como publicação na web, você pode optar por formatos compactados com perdas. Algoritmos especialmente projetados para compactação de dados de imagem permitem uma redução significativa no tamanho do arquivo, preservando ao mesmo tempo uma qualidade de imagem aceitável. Isso facilita downloads rápidos de arquivos de imagem da Internet. Para converter AVIF em TIFF, usaremos [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API que é uma API de manipulação e conversão de imagens rica em recursos, poderosa e fácil de usar para plataforma Java. Você pode baixar sua versão mais recente diretamente de [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```xml
<repositório>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para converter AVIF em TIFF via Java" %}}

{{% blocks/products/pf/agp/text %}}

Os desenvolvedores podem facilmente carregar e converter arquivos AVIF para TIFF em apenas algumas linhas de código.

{{% /blocks/products/pf/agp/text %}}

+ Carregar arquivo AVIF com o método Image.load
+ Crie e defina a instância da subclasse necessária de ImageOptionsBase (por exemplo, BmpOptions, PngOptions, etc.)
+ Chame o método Image.save
+ Passe o caminho do arquivo com a extensão TIFF e o objeto da classe ImageOptionsBase

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

Antes de executar o código de exemplo de conversão, verifique se você tem os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

+ Sistema operacional: Windows ou Linux.
+ Ambiente de desenvolvimento: Suporta .NET Core 7 e superior, como Microsoft Visual Studio.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/imaging-app-widget
        sectionTitle="Aplicativo gratuito para converter AVIF para TIFF"
        appName="Conversion"
        extension="AVIF-to-TIFF"
        label1="Selecione ou arraste e solte a imagem AVIF"
        label2="Escolha o formato e clique no botão Converter"
        label3="Clique no botão Download para baixar a imagem TIFF"
        checkFreeAppLabel="Confira nossas [demonstrações ao vivo para converter AVIF em TIFF]"
        checkFreeAppLabelUrl="(https://products.aspose.app/imaging/pt/conversion/AVIF-to-TIFF)"
        showPreview="true">}}

{{% blocks/products/pf/agp/code-block title="Converter {Formato1} para {Formato2} - Java" offSpacer="true" %}}

{{< gist "aspose-com-gists" "74b9cf26c193cd103f69194c2bbe0984" "convert-image-to-other-format.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/about-file-section >}}
       
        {{< blocks/products/pf/agp/about-file-text fileFormat="AVIF" readMoreLink="https://docs.fileformat.com/image/avif/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação | AVIF">}}
AVIF é uma especificação de formato de ficheiro de imagem aberto e isento de royalties para armazenar imagens ou sequências de imagens comprimidas com AV1 no formato de contentor HEIF.
        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação | TIFF">}}
TIFF ou TIF, Tagged Image File Format, representa imagens raster que se destinam ao uso em uma variedade de dispositivos que estão em conformidade com este padrão de formato de arquivo. Ele é capaz de descrever dados de imagem de dois níveis, tons de cinza, cores de paleta e cores em vários espaços de cores. Ele suporta esquemas de compactação com e sem perdas para escolher entre espaço e tempo para aplicativos que usam o formato. O formato é extensível e passou por várias revisões que permitem a inclusão de uma quantidade ilimitada de informações privadas ou de finalidade especial. O formato não depende da máquina e está livre de limites como processador, sistema operacional ou sistemas de arquivos.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="Usando Java, pode-se converter facilmente diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-gif/" name="GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-dicom/" name="DICOM" description="Imagens e comunicações digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-emf/" name="EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-jpg/" name="JPG" description="Grupo Conjunto de Especialistas em Fotografia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-jpeg/" name="JPEG" description="Grupo Conjunto de Especialistas em Fotografia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-j2k/" name="J2K" description="Imagem Comprimida Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-jpeg2000/" name="JPEG2000" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-png/" name="PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-apng/" name="APNG" description="Gráficos de rede portátil animados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-psd/" name="PSD" description="Documento do Photoshop" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-dxf/" name="DXF" description="Formato de intercâmbio de desenho, ou formato de intercâmbio de desenho," >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-svg/" name="SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-tiff/" name="TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-webp/" name="WEBP" description="Imagem da Web Raster" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-wmf/" name="WMF" description="Meta-arquivo do Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-pdf/" name="PDF" description="Formato de Documento Portátil (PDF)" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-html/" name="HTML" description="Tela HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-emz/" name="EMZ" description="Meta-arquivo aprimorado compactado do Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-wmz/" name="WMZ" description="Skin compactada do Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-tga/" name="TGA" description="Gráfico Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-svgz/" name="SVGZ" description="Versão compactada do arquivo Scalable Vector Graphics (.SVG)." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-canvas/" name="CANVAS" description="Tela HTML5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-ico/" name="ICO" description="ícone do Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/conversion/avif-to-bmp/" name="BMP" description="Imagem de bitmap" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}