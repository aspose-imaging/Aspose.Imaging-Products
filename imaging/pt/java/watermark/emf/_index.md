﻿---
title: Documento de marca d'água EMF via Java 
weight: 3920
url: /pt/java/watermark/emf/ 
lang: pt
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Exemplo de código de conversão Java do formato EMF para o arquivo . Use este código de exemplo para converter EMF em  em qualquer aplicativo baseado em Java Web ou Desktop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Adicionar marca d'água de texto a EMF por meio de Java" h2="Crie seus próprios aplicativos Java para marcar arquivos EMF com marca d'água usando APIs do lado do servidor." logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="EMF" pfName="Aspose.Imaging" subTitlepfName="para Java" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Imaging" subTitlepfName="para Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-java.svg" apiHomeLink="/imaging/pt/java/" codeSamplesLink="https://github.com/aspose-imaging/Aspose.Imaging-for-Java/" liveDemosLink="https://products.aspose.app/imaging/family/" docsLink="https://docs.aspose.com/imaging/java/" installationsDocsLink="https://docs.aspose.com/imaging/java/" mavenRepoLink="https://repository.aspose.com/repo/com/aspose/aspose-imaging/" downloadAsLink="https://downloads.aspose.com/imaging/java/" learnAsLink="https://docs.aspose.com/imaging/java/" apiReference="" apiHomeText="Página inicial da API" codeSamplesText="Amostras de código" liveDemosText="Demonstrações ao vivo" downloadText="Download" learnText="Aprender">}}

{{% blocks/products/pf/agp/content h2="Como marcar o arquivo EMF com marca d'água usando Java" %}}

A marca d'água é uma ferramenta essencial para autores que buscam a máxima exposição de seu trabalho na internet. Colocar uma marca d'água em uma imagem serve não apenas para identificar sua fonte ou detentor dos direitos autorais, mas também para promover seu criador. Isso porque a assinatura contendo o nome do autor ou do recurso da internet é distribuída junto com uma cópia digital da imagem. As marcas d'água podem assumir a forma de texto com uma ampla variedade de fontes e podem ser posicionadas na borda da imagem. Quando a marca d'água é transparente, não atrapalha a visualização. Porém, caso o autor ou detentor dos direitos autorais deseje enfatizar seu nome, a marca d'água poderá sobrepor parcialmente a imagem. Para colocar marca d'água no arquivo de imagem EMF, usaremos [Aspose.Imaging for Java](https://products.aspose.com/imaging/java) API que é uma API de manipulação e conversão de imagens rica em recursos, poderosa e fácil de usar para plataforma Java. Você pode baixar sua versão mais recente diretamente de [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-imaging) e instale-o em seu projeto baseado em Maven adicionando as seguintes configurações ao pom.xml.

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

{{% blocks/products/pf/agp/feature-section-col title="Etapas para adicionar marca d'água a EMF via Java" %}}

{{% blocks/products/pf/agp/text %}}

Você precisa do [aspose-imaging-version-jdk16.jar](https://downloads.aspose.com/imaging/java) para experimentar o fluxo de trabalho a seguir em seu próprio ambiente.

{{% /blocks/products/pf/agp/text %}}

+ Carregar arquivo EMF com o método Image.load
+ Criar instância de Graphics a partir da imagem
+ Definir fonte, pincel e formato para texto de marca d'água
+ Desenhe marca d'água usando o método Graphics.drawString
+ Salvar imagem em disco no formato EMF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de sistema" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Imaging para Java é compatível com todos os principais sistemas operacionais. Apenas certifique-se de ter os seguintes pré-requisitos.

{{% /blocks/products/pf/agp/text %}}

- JDK 1.6 ou superior está instalado.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Imagem de marca d'água EMF - Java" offSpacer="" %}}

{{< gist "aspose-com-gists" "1ac443cce5aab9d32ad152570c716c05" "watermark-emf-image.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Sobre o Aspose.Imaging para a API Java" %}}


Aspose.Imaging API é uma solução de processamento de imagens para criar, modificar, desenhar ou converter imagens (fotos) dentro de aplicativos. Oferece: Processamento de imagem multiplataforma, incluindo, mas não limitado a, conversões entre vários formatos de imagem (incluindo processamento de imagem uniforme de várias páginas ou vários quadros), modificações como desenho, trabalho com primitivos gráficos, transformações (redimensionar, cortar, virar e girar , binarização, escala de cinza, ajuste), recursos avançados de manipulação de imagem (filtragem, pontilhamento, mascaramento, alinhamento) e estratégias de otimização de memória. É uma biblioteca autônoma e não depende de nenhum software para operações de imagem. Pode-se adicionar facilmente recursos de conversão de imagem de alto desempenho com APIs nativas nos projetos. Essas são APIs locais 100% privadas e as imagens são processadas em seus servidores.


    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Marca d'água EMF via aplicativo on-line" sectionDescription="Adicione marca d'água a documentos EMF visitando nosso [site de demonstrações ao vivo](https://products.aspose.app/imaging/watermark). A demonstração ao vivo tem os seguintes benefícios" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text="Não há necessidade de baixar ou configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text="Não há necessidade de escrever nenhum código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Basta enviar seu arquivo EMF, definir sua marca d'água e clicar no botão \"Adicionar\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text="Obtenha instantaneamente o link de download para o arquivo resultante" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="EMF" readMoreLink="https://docs.fileformat.com/image/emf/" whatIsFormat1="O que é" whatIsFormat2="Formato de arquivo" readMoreFormat="consulte Mais informação" >}}
O formato de metarquivo aprimorado (EMF) armazena imagens gráficas independentemente do dispositivo. Os metarquivos de EMF são compostos por registros de comprimento variável em ordem cronológica que podem renderizar a imagem armazenada após a análise em qualquer dispositivo de saída. Esses registros de comprimento variável podem ser definições de objetos incluídos, comandos para desenho e propriedades gráficas críticas para renderizar a imagem com precisão. Quando um dispositivo abre um metarquivo EMF usando seu próprio ambiente gráfico, as proporções, dimensões, cores e outras propriedades gráficas da imagem original permanecem as mesmas, independentemente da plataforma do dispositivo de abertura.
        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Outros formatos de marca d'água compatíveis" subTitle="Usando Java, pode-se facilmente marcar diferentes formatos, incluindo." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/bmp/" name="BMP" description="Imagem de bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/ico/" name="ICO" description="ícone do Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/dib/" name="DIB" description="Bitmap independente de dispositivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/dicom/" name="DICOM" description="Imagens e comunicações digitais" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/gif/" name="GIF" description="Formato de intercâmbio gráfico" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/jp2/" name="JP2" description="JPEG 2000" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/j2k/" name="J2K" description="Imagem Comprimida Wavelet" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/png/" name="PNG" description="Gráficos Portáteis de Rede" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/tiff/" name="TIFF" description="Formato de imagem marcada" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/webp/" name="WEBP" description="Imagem da Web Raster" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/wmf/" name="WMF" description="Meta-arquivo do Microsoft Windows" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="/imaging/pt/java/watermark/svg/" name="SVG" description="Gráficos vetoriais escalonáveis" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
