
---
title: Chuyển đổi định dạng hình ảnh C # 
weight: 3920
url: /vi/net/conversion/ 
lang: vi
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Chuyển đổi các định dạng ảnh, ảnh, ảnh thông dụng qua thư viện .NET. Chuyển đổi sang PSD, PDF, GIF, JPG, SVG bao gồm HTML5 Canvas với vài dòng mã C #.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi tệp hình ảnh qua C #" h2="Chuyển đổi các định dạng Hình ảnh, Siêu tệp, WebP, Svg, Apng để xây dựng các ứng dụng xử lý hình ảnh tiên tiến dựa trên .NET đa nền tảng." downloadText="Tải xuống" >}}

{{% blocks/products/pf/feature-page-summary %}}

.NET Image API hỗ trợ các tính năng kết xuất và xử lý hình ảnh nâng cao cho các lập trình viên. Các nhà phát triển có thể tích hợp nó để chuyển đổi hình ảnh raster & vector, bao gồm ảnh và hình ảnh sang PSD, PDF, GIF, PNG, DICOM, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WEBP, WMF, EMF và các định dạng hình ảnh khác . API không chỉ giải quyết việc chuyển đổi tệp mà còn giải quyết việc chuyển đổi hình ảnh sang màu đen trắng và thang độ xám, chuyển đổi các lớp ảnh GIF và hơn thế nữa.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi hình ảnh sang Bitmap BMP, JPG, PNG" %}}

Sử dụng C # Image API, chuyển đổi định dạng Inter dễ dàng như chỉ cần thay đổi phần mở rộng của định dạng mong muốn. Dưới đây là một số trường hợp chung chung như **image thành bmp**, **image thành jpg**, **image thành png** và các nhà phát triển có thể dễ dàng nâng cao cho định dạng cụ thể của họ. Quá trình được tải hình ảnh nguồn qua [Image.Load](https://apireference.aspose.com/imaging/net/aspose.imaging/image/methods/load). Tạo một đối tượng đích [tùy chọn định dạng hình ảnh](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions) cho bất kỳ cài đặt cụ thể nào. Cuối cùng gọi [Phương pháp Lưu](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) bằng cách chuyển tệp đích với đường dẫn và tùy chọn Lưu dưới dạng tham số.

{{% blocks/products/pf/feature-page-code h3="Mã C # để chuyển đổi giữa các hình ảnh" %}}

{{< gist "aspose-com-gists" "4f45746500932351190aa24726cc4544" "convert-image-to-other-format.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/apng-to-bmp/" style="padding:15px;">APNG đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/cdr-to-bmp/" style="padding:15px;">CDR đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/dib-to-bmp/" style="padding:15px;">DIB đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/dicom-to-bmp/" style="padding:15px;">DICOM đến BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/djvu-to-bmp/" style="padding:15px;">DJVU đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/dng-to-bmp/" style="padding:15px;">DNG đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/emf-to-bmp/" style="padding:15px;">EMF đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/emz-to-bmp/" style="padding:15px;">EMZ đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/eps-to-bmp/" style="padding:15px;">EPS đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/gif-to-bmp/" style="padding:15px;">GIF đến BMP</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi hình ảnh sang PDF nhanh hơn" %}}

Quá trình chuyển đổi hình ảnh raster sang PDF giống như quá trình chuyển đổi giữa các hình ảnh, ngoại trừ API cung cấp [PdfOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/pdfoptions) cho các cài đặt PDF cụ thể . Các lập trình viên có thể dễ dàng nâng cao nó cho các nhu cầu cụ thể của họ.

{{% blocks/products/pf/feature-page-code h3="Mã để chuyển đổi hình ảnh Raster sang PDF" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "raster-images-to-pdf-conversion.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/apng-to-PDF/" style="padding:15px;">APNG đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/jpeg-to-PDF/" style="padding:15px;">JPEG đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/bmp-to-PDF/" style="padding:15px;">BMP đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/odg-to-PDF/" style="padding:15px;">ODG đến PDF</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/otg-to-PDF/" style="padding:15px;">OTG đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/png-to-PDF/" style="padding:15px;">PNG đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/svg-to-PDF/" style="padding:15px;">SVG đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/emz-to-PDF/" style="padding:15px;">EMZ đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/eps-to-PDF/" style="padding:15px;">EPS đến PDF</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/gif-to-PDF/" style="padding:15px;">GIF đến PDF</a>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi SVG sang Raster Hình ảnh BMP, PNG, JPG" %}}

Quá trình chuyển đổi SVG cũng giống như vậy, Tải tệp SVG, Sử dụng các tùy chọn lưu ảnh có liên quan và gọi phương thức Lưu. Image API cung cấp [SvgRasterizationOptions](https://apireference.aspose.com/imaging/net/aspose.imaging.imageoptions/svgrasterizationoptions) để thiết lập hình ảnh PageWidth, PageHeight và raster sử dụng thuộc tính VectorRasterizationOptions để khởi tạo và nhận các tùy chọn SvgRasterizationOptions. 

{{% blocks/products/pf/feature-page-code h3="Mã C # cho hình ảnh SVG to Raster" %}}

{{< gist "aspose-com-gists" "6b74208a46515ca7c2613e245f7bff6b" "convert-svg-to-raster-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/SVG-to-bmp/" style="padding:15px;">SVG đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/SVG-to-jpeg/" style="padding:15px;">SVG đến JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/net/conversion/SVG-to-png/" style="padding:15px;">SVG đến PNG</a>
		   </div>		   
		</div>
	</div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Tất cả các định dạng hình ảnh được hỗ trợ để chuyển đổi từ" %}}
Dưới đây là danh sách đầy đủ các định dạng hình ảnh mà bạn có thể chuyển đổi sang:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
                <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/apng/" style="padding:15px;">chuyển đổi từ APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/bmp/" style="padding:15px;">chuyển đổi từ BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/dib/" style="padding:15px;">chuyển đổi từ DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/dicom/" style="padding:15px;">chuyển đổi từ DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/djvu/" style="padding:15px;">chuyển đổi từ DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/dng/" style="padding:15px;">chuyển đổi từ DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/emf/" style="padding:15px;">chuyển đổi từ EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/emz/" style="padding:15px;">chuyển đổi từ EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/gif/" style="padding:15px;">chuyển đổi từ GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/jpeg2000/" style="padding:15px;">chuyển đổi từ JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/jp2/" style="padding:15px;">chuyển đổi từ JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/j2k/" style="padding:15px;">chuyển đổi từ J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/jpg/" style="padding:15px;">chuyển đổi từ JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/jpeg/" style="padding:15px;">chuyển đổi từ JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/png/" style="padding:15px;">chuyển đổi từ PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/tga/" style="padding:15px;">chuyển đổi từ TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/tif/" style="padding:15px;">chuyển đổi từ TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/tiff/" style="padding:15px;">chuyển đổi từ TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/webp/" style="padding:15px;">chuyển đổi từ WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/wmf/" style="padding:15px;">chuyển đổi từ WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/wmz/" style="padding:15px;">chuyển đổi từ WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/svg/" style="padding:15px;">chuyển đổi từ SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/svgz/" style="padding:15px;">chuyển đổi từ SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/eps/" style="padding:15px;">chuyển đổi từ EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/cdr/" style="padding:15px;">chuyển đổi từ CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/cmx/" style="padding:15px;">chuyển đổi từ CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/otg/" style="padding:15px;">chuyển đổi từ OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/odg/" style="padding:15px;">chuyển đổi từ ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/from/ico/" style="padding:15px;">chuyển đổi từ ICO</a></div>
                </div>
        </div>
    </div>
</div>
<br/>

{{% blocks/products/pf/feature-page-section  h2="Tất cả các định dạng hình ảnh được hỗ trợ để chuyển đổi sang" %}}
Dưới đây là danh sách đầy đủ các định dạng hình ảnh mà bạn có thể chuyển đổi từ:
{{% /blocks/products/pf/feature-page-section %}}
<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
	        <hr style="margin-left:-20px;"/>
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/bmp/" style="padding:15px;">Chuyển đổi sang BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/gif/" style="padding:15px;">Chuyển đổi sang GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/dicom/" style="padding:15px;">Chuyển đổi sang DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/emf/" style="padding:15px;">Chuyển đổi sang EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/jpg/" style="padding:15px;">Chuyển đổi sang JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/jpeg/" style="padding:15px;">Chuyển đổi sang JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/jp2/" style="padding:15px;">Chuyển đổi sang JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/j2k/" style="padding:15px;">Chuyển đổi sang J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/jpeg2000/" style="padding:15px;">Chuyển đổi sang JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/png/" style="padding:15px;">Chuyển đổi sang PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/psd/" style="padding:15px;">Chuyển đổi sang PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/dxf/" style="padding:15px;">Chuyển đổi sang DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/svg/" style="padding:15px;">Chuyển đổi sang SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/tiff/" style="padding:15px;">Chuyển đổi sang TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/webp/" style="padding:15px;">Chuyển đổi sang WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/wmf/" style="padding:15px;">Chuyển đổi sang WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/pdf/" style="padding:15px;">Chuyển đổi sang PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/html/" style="padding:15px;">Chuyển đổi sang HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/emz/" style="padding:15px;">Chuyển đổi sang EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/wmz/" style="padding:15px;">Chuyển đổi sang WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/tga/" style="padding:15px;">Chuyển đổi sang TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/svgz/" style="padding:15px;">Chuyển đổi sang SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/canvas/" style="padding:15px;">Chuyển đổi sang CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/ico/" style="padding:15px;">Chuyển đổi sang ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/net/conversion/to/apng/" style="padding:15px;">Chuyển đổi sang APNG</a></div>
                </div>
        </div>
    </div>
</div>

