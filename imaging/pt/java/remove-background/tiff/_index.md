﻿---
title: Remova o plano de fundo em documentos TIFF via Java 
weight: 3920
url: /pt/java/remove-background/tiff/ 
lang: pt
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Experimente nossas APIs de documentos no local para alterar o plano de fundo de arquivos TIFF no aplicativo Java.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Remova o plano de fundo de TIFFs via Java" h2="Crie seus próprios aplicativos Java para remover o plano de fundo de arquivos TIFF usando APIs do lado do servidor." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="TIFF" pfName="Aspose.Imaging" subTitlepfName="para Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="para Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/pt/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Página inicial da API" codeSamplesText="Amostras de código" liveDemosText="Demonstrações ao vivo" downloadText="Download" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Como remover o plano de fundo em arquivos TIFF usando Java" %}}

Remover o fundo de uma imagem envolve isolar objetos em primeiro plano, uma tarefa que requer o reconhecimento de objetos. Existem várias abordagens para identificar objetos em uma foto no formato TIFF. Para imagens simples com fundo de cor uniforme, um método automático é suficiente. Porém, para fotos com figuras múltiplas ou parcialmente mescladas, torna-se necessária a pré-marcação dos objetos. Isto envolve a especificação de regiões retangulares e tipos de objetos para remoção. Em casos complexos, a API Cloud permite a detecção automática de objetos. A API Cloud fornece um aplicativo em nuvem capaz de reconhecer objetos em fotos, aproveitando os contornos resultantes para remoção de fundo. Após a remoção, as bordas deixadas pelas figuras podem ser suavizadas para melhorar a qualidade da imagem. Para remover o fundo dos arquivos TIFF, usaremos [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API que é uma API de manipulação e conversão de imagens rica em recursos, poderosa e fácil de usar para plataforma Java. Você pode baixar sua versão mais recente diretamente de [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para remover o plano de fundo de TIFFs via Java" %}}

{{% blocks/products/pf/agp/text %}}

Você precisa do [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) para experimentar o fluxo de trabalho a seguir em seu próprio ambiente.

{{% /blocks/products/pf/agp/text %}}

+ Carregar arquivos TIFF com o método Image.load
+ Remover fundo;
+ Salve a imagem no disco no formato suportado pelo Aspose.Imaging

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging para Java é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 ou superior está instalado.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Remover plano de fundo em imagens TIFF - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "26a3ef7a80fab1d53054422a388087a2" "remove-change-background-generic-examples.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre o Aspose.Imaging para a API Java" %}}


Aspose.Imaging API é uma solução de processamento de imagens para criar, modificar, desenhar ou converter imagens (fotos) dentro de aplicativos. Oferece: Processamento de imagem multiplataforma, incluindo, mas não limitado a, conversões entre vários formatos de imagem (incluindo processamento de imagem uniforme de várias páginas ou vários quadros), modificações como desenho, trabalho com primitivos gráficos, transformações (redimensionar, cortar, virar e girar , binarização, escala de cinza, ajuste), recursos avançados de manipulação de imagem (filtragem, pontilhamento, mascaramento, alinhamento) e estratégias de otimização de memória. É uma biblioteca autônoma e não depende de nenhum software para operações de imagem. Pode-se adicionar facilmente recursos de conversão de imagem de alto desempenho com APIs nativas nos projetos. Essas são APIs locais 100% privadas e as imagens são processadas em seus servidores.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Remova o plano de fundo em TIFFs por meio do aplicativo on-line" sectionDescription="Remova o plano de fundo em documentos TIFF visitando nosso [site de demonstrações ao vivo](https://products.aspose.app/imaging/remove-background). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Não há necessidade de escrever nenhum código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta enviar seus arquivos TIFF e clicar no botão \"Remover plano de fundo agora\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Obtenha instantaneamente o link de download para o arquivo resultante" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="TIFF" readMoreLink="https://docs.fileformat.com/image/tiff/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação" >}}
TIFF ou TIF, Tagged Image File Format, representa imagens raster que se destinam ao uso em uma variedade de dispositivos que estão em conformidade com este padrão de formato de arquivo. Ele é capaz de descrever dados de imagem de dois níveis, tons de cinza, cores de paleta e cores em vários espaços de cores. Ele suporta esquemas de compactação com e sem perdas para escolher entre espaço e tempo para aplicativos que usam o formato. O formato é extensível e passou por várias revisões que permitem a inclusão de uma quantidade ilimitada de informações privadas ou de finalidade especial. O formato não depende da máquina e está livre de limites como processador, sistema operacional ou sistemas de arquivos.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros Formatos de Fundo de Remoção Suportados" subTitle="Usando Java, pode-se remover facilmente o plano de fundo de diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/apng/" name="APNG" description="Gráficos de rede portátil animados" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/bmp/" name="BMP" description="Imagem de bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/ico/" name="ICO" description="ícone do Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/jpg/" name="JPG" description="Grupo Conjunto de Especialistas em Fotografia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/dib/" name="DIB" description="Bitmap independente de dispositivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/dicom/" name="DICOM" description="Imagens e comunicações digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/djvu/" name="DJVU" description="Formato gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/dng/" name="DNG" description="Imagem de câmera digital" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/emf/" name="EMF" description="Formato de metarquivo aprimorado" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/emz/" name="EMZ" description="Meta-arquivo aprimorado compactado do Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/gif/" name="GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/j2k/" name="J2K" description="Imagem Comprimida Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/png/" name="PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/webp/" name="WEBP" description="Imagem da Web Raster" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/wmf/" name="WMF" description="Meta-arquivo do Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/wmz/" name="WMZ" description="Skin compactada do Windows Media Player" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/tga/" name="TGA" description="Gráfico Targa" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/svg/" name="SVG" description="Gráficos vetoriais escalonáveis" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/eps/" name="EPS" description="Linguagem PostScript Encapsulada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/cdr/" name="CDR" description="Imagem de desenho vetorial" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/cmx/" name="CMX" description="Imagem do Corel Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/otg/" name="OTG" description="Padrão OpenDocument" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/odg/" name="ODG" description="Formato de desenho do Apache OpenOffice" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/remove-background/avif/" name="AVIF" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
