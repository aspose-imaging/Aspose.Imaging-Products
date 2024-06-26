﻿---
title: Конвертируйте HEIC в WEBP с помощью C# 
weight: 3920
url: /ru/adapters/net/heic-to-webp/ 
lang: ru
langdirlevel: 2
locales: ja,it,zh-hant,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hans,ar,hi,th,sv,cs,uk,he
description: Использование Aspose.Imaging.Heic.Adapter для конвертации изображений и документов на C#. Пример кода API для пакетного преобразования файлов HEIC в WEBP в любом приложении на основе .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Конвертация файлов HEIC в WEBP с помощью адаптера на C#" h2="Преобразуйте HEIC в документы WEBP с помощью собственных API-интерфейсов .NET без необходимости использования какого-либо редактора изображений" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="WEBP" pfName="Aspose.Imaging" subTitlepfName="для .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="APNG" >}}


{{< blocks/products/pf/main-container pfName="Aspose.Imaging Adapter" subTitlepfName="для .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/imaging/images/imaging/aspose_imaging-for-net.svg" apiHomeLink="/imaging/ru/adapters/net/" docsLink="https://reference.aspose.com/imaging/adapters/net/aspose.imaging.heic.adapter/" installationsDocsLink="https://reference.aspose.com/imaging/adapters/net/aspose.imaging.heic.adapter/" nugetLink="https://www.nuget.org/packages/aspose.imaging" nugetPackageName="" downloadAsLink="https://www.nuget.org/packages/Aspose.Imaging.Heic.Adapter/" learnAsLink="https://reference.aspose.com/imaging/adapters/net/aspose.imaging.heic.adapter/" apiReference="" apiHomeText="Главная страница API" downloadText="Скачать" learnText="Документация" overviewText="Обзор" >}}

{{% blocks/products/pf/agp/content h2="Как конвертировать HEIC в WEBP с помощью C#" %}}

<p align="justify" style="font-size:18px;text-indent:50px;">Преобразование форматов файлов является популярной задачей в различных сферах, и сегодня изменить один формат на другой так же просто, как сделать онлайн-запрос. Однако для профессиональных дизайнеров крайне важно иметь надежный инструмент, который быстро и эффективно выполняет конвертацию, особенно между форматами изображений и документов. Зачастую представление изображения в виде документа или, наоборот, преобразование документа в растровое изображение является нетривиальной задачей, с которой не справляются стандартные редакторы.</p>

<p align="justify" style="font-size:18px;text-indent:50px;">Выберите библиотеку Aspose.Imaging.Heic.Adapter для .NET, специально созданную для обработки и преобразования изображений. Этот незаменимый инструмент обладает следующими ключевыми особенностями:</p>

<ul style="font-size:18px;">
<li>Облегчает преобразование между различными форматами изображений и документов.</li>
<li>Обеспечивает автоматизацию без необходимости использования стороннего программного обеспечения для редактирования графики.</li>
<li>Предлагает надежный .NET API для бесшовных преобразований.</li>
<li>Удобный интерфейс доступный на C#.</li>
<li>Поддерживает популярные форматы HEIC и WEBP.</li>
</ul>

<p align="justify" style="font-size:18px;text-indent:50px;">Чтобы преобразовать HEIC в WEBP, мы будем использовать <a href="https://products.aspose.com/imaging/adapters/net">Aspose.Imaging.Heic.Adapter</a> API — многофункциональный, мощный и простой в использовании API для обработки и преобразования изображений для платформы C#. Откройте <a href="https://www.nuget.org/packages/Aspose.Imaging.Heic.Adapter">Nuget</a> диспетчер пакетов, найдите Aspose.Imaging.Heic.Adapter и установите. Вы также можете использовать следующую команду из консоли диспетчера пакетов:</p>

{{% blocks/products/pf/agp/code-block title="Консольная команда диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Imaging.Heic.Adapter

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию HEIC в WEBP с помощью C#" %}}

{{% blocks/products/pf/agp/text %}}

Разработчики могут легко загружать и конвертировать файлы HEIC в WEBP всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

+ Выполните инициализацию адаптера, с помощью метода Register(), эта операция выполняется единоразово.
+ Загрузите требуемый HEIC файл с помощью метода Aspose.Imaging.Image.Load().
+ Создайте необходимый экземпляр класса опций сохранения для формата WEBP и задайте необходимые свойства.
+ Выполните сохранение файла WEBP с помощью метода Aspose.Imaging.Image.Save(), в котором в качестве параметров необходимо задать путь к файлу или поток, а так же опции сохранения.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

Прежде чем запускать пример кода преобразования, убедитесь, что у вас выполнены следующие предварительные условия:

{{% /blocks/products/pf/agp/text %}}

+ Операционная система Windows или Linux.
+ Среда разработки поддерживающая .NET Core 7 и выше, например Microsoft Visual Studio.
  

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Преобразование HEIC в WEBP – .NET" offSpacer="true" %}}

{{< gist "aspose-com-gists" "00995eb3d72fecb3c21506b888ee8c10" "heic-to-webp.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}
