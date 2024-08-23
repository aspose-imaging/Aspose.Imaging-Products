
---
title: Chuyển đổi định dạng hình ảnh Java 
weight: 3920
url: /vi/java/conversion/ 
lang: vi
langdirlevel: 2
locales: zh-hans,ja,it,ru,de,es,fr,nl,id,lt,pl,pt,vi,tr,ko,zh-hant,ar,hi,th,sv,cs,uk,he
description: Chuyển đổi các tập tin ảnh, ảnh, ảnh thông dụng qua thư viện Java. Chuyển đổi sang PDF, GIF, PSD, JPG, Dxf, SVG bao gồm HTML5 Canvas.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Chuyển đổi tệp hình ảnh qua Java" h2="Chuyển đổi các định dạng Hình ảnh, Siêu tệp, WebP, SVG, APNG để xây dựng các ứng dụng Java đa nền tảng." downloadText="Tải xuống" >}}

{{% blocks/products/pf/feature-page-summary %}}

Đối với bất kỳ ứng dụng xử lý hình ảnh nâng cao nào, Java Image API tạo điều kiện cho các nhà phát triển tạo, tải, thao tác hoặc kết xuất hình ảnh mà không cần bất kỳ yêu cầu nào về trình chỉnh sửa hình ảnh. Nó có thể chuyển đổi hình ảnh vector & raster, bao gồm ảnh và hình ảnh sang PSD, PDF, GIF, PNG, DICOM, DXF, SVG, JPG, JPEG2000, APNG, BMP, TIFF, HTML5 CANVAS, WMF, EMF, WEBP và các định dạng hình ảnh khác. API cung cấp phương pháp phân chia nhị phân và thang độ xám để chuyển đổi hình ảnh sang màu đen trắng và thang độ xám cũng như chuyển đổi đồ họa tài liệu mở, hệ màu RGB sang CMYK và hơn thế nữa.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi giữa các tệp hình ảnh" %}}

Sử dụng Java Image API, chuyển đổi Inter rất đơn giản và các nhà phát triển chỉ phải viết một vài dòng mã hóa cho bất kỳ trường hợp nào bao gồm **image thành jpg**, **image thành bmp**, **image sang png** v.v. API cung cấp [Image.load](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#load-java.lang.String-) để tải hình ảnh. Chỉ định các tùy chọn hình ảnh có liên quan từ [ImageOptionsBase](https://apireference.aspose.com/imaging/java/com.aspose.imaging/ImageOptionsBase) và gọi phương thức lưu với tệp hình ảnh đầu ra và các tùy chọn dưới dạng tham số.

{{% blocks/products/pf/feature-page-code h3="Mã Java để chuyển đổi giữa các hình ảnh" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "inter-conversion-of-image-files.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/apng-to-bmp/" style="padding:15px;">APNG đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/cdr-to-bmp/" style="padding:15px;">CDR đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/dib-to-bmp/" style="padding:15px;">DIB đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/dicom-to-bmp/" style="padding:15px;">DICOM đến BMP</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/djvu-to-bmp/" style="padding:15px;">DJVU đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/dng-to-bmp/" style="padding:15px;">DNG đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/emf-to-bmp/" style="padding:15px;">EMF đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/emz-to-bmp/" style="padding:15px;">EMZ đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/eps-to-bmp/" style="padding:15px;">EPS đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/gif-to-bmp/" style="padding:15px;">GIF đến BMP</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi ảnh Raster sang PSD" %}}

Quá trình chuyển đổi hình ảnh raster sang PSD giống như quá trình chuyển đổi giữa các hình ảnh, ngoại trừ API cung cấp [PsdOptions](https://apireference.aspose.com/imaging/java/com.aspose.imaging.imageoptions/PsdOptions) cho cụ thể Cài đặt PSD. Các lập trình viên có thể dễ dàng nâng cao nó cho các nhu cầu cụ thể của họ.

{{% blocks/products/pf/feature-page-code h3="Mã Java để chuyển đổi hình ảnh Raster sang PSD" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "raster-images-to-psd-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/apng-to-PSD/" style="padding:15px;">APNG đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/jpeg-to-PSD/" style="padding:15px;">JPEG đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/bmp-to-PSD/" style="padding:15px;">BMP đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/odg-to-PSD/" style="padding:15px;">ODG đến PSD</a></p>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/otg-to-PSD/" style="padding:15px;">OTG đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/png-to-PSD/" style="padding:15px;">PNG đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/svg-to-PSD/" style="padding:15px;">SVG đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/emz-to-PSD/" style="padding:15px;">EMZ đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/eps-to-PSD/" style="padding:15px;">EPS đến PSD</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/gif-to-PSD/" style="padding:15px;">GIF đến PSD</a></p>
		   </div>
		</div>
	</div>
    </div>
</div>

{{% blocks/products/pf/feature-page-section  h2="Chuyển đổi Corel Draw CDR thành Hình ảnh" %}}

Quá trình chuyển đổi CDR gần như giống nhau, Tải tệp CDR, Sử dụng các tùy chọn lưu ảnh có liên quan và gọi phương thức Lưu. API hình ảnh cung cấp [VectorRasterizationOptions](https://apireference.aspose.com/imaging/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions) để thiết lập các thông số bắt buộc. Và các Tùy chọn rasterization này có thể được coi là các tùy chọn hình ảnh cần thiết cho cài đặt của chúng. Fianlly gọi phương thức lưu. 

{{% blocks/products/pf/feature-page-code h3="Mã Java cho CDR thành hình ảnh" %}}

{{< gist "aspose-com-gists" "ebf2f529d09d9aa4b63d97e274be4793" "convert-cdr-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

<div class="container-fluid productfamilypage bg-gray">
    <div class="convertypes bg-gray agp-content section">
        <div class="container">
		<div class="row other-converters" style="gap: 10px;font-size: 19px;text-align:center;">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/CDR-to-bmp/" style="padding:15px;">CDR đến BMP</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/CDR-to-jpeg/" style="padding:15px;">CDR đến JPEG</a></p>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <p><a href="/imaging/vi/java/conversion/CDR-to-png/" style="padding:15px;">CDR đến PNG</a></p>
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
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/apng/" style="padding:15px;">chuyển đổi từ APNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/bmp/" style="padding:15px;">chuyển đổi từ BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/dib/" style="padding:15px;">chuyển đổi từ DIB</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/dicom/" style="padding:15px;">chuyển đổi từ DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/djvu/" style="padding:15px;">chuyển đổi từ DJVU</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/dng/" style="padding:15px;">chuyển đổi từ DNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/emf/" style="padding:15px;">chuyển đổi từ EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/emz/" style="padding:15px;">chuyển đổi từ EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/gif/" style="padding:15px;">chuyển đổi từ GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jpeg2000/" style="padding:15px;">chuyển đổi từ JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jp2/" style="padding:15px;">chuyển đổi từ JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/j2k/" style="padding:15px;">chuyển đổi từ J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jpg/" style="padding:15px;">chuyển đổi từ JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jpeg/" style="padding:15px;">chuyển đổi từ JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/png/" style="padding:15px;">chuyển đổi từ PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/tga/" style="padding:15px;">chuyển đổi từ TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/tif/" style="padding:15px;">chuyển đổi từ TIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/tiff/" style="padding:15px;">chuyển đổi từ TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/webp/" style="padding:15px;">chuyển đổi từ WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/wmf/" style="padding:15px;">chuyển đổi từ WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/wmz/" style="padding:15px;">chuyển đổi từ WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/svg/" style="padding:15px;">chuyển đổi từ SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/svgz/" style="padding:15px;">chuyển đổi từ SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/eps/" style="padding:15px;">chuyển đổi từ EPS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/cdr/" style="padding:15px;">chuyển đổi từ CDR</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/cmx/" style="padding:15px;">chuyển đổi từ CMX</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/otg/" style="padding:15px;">chuyển đổi từ OTG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/odg/" style="padding:15px;">chuyển đổi từ ODG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/ico/" style="padding:15px;">chuyển đổi từ ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/avif/" style="padding:15px;">chuyển đổi từ AVIF</a></div>
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
		    <div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/bmp/" style="padding:15px;">Chuyển đổi sang BMP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/gif/" style="padding:15px;">Chuyển đổi sang GIF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/dicom/" style="padding:15px;">Chuyển đổi sang DICOM</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/emf/" style="padding:15px;">Chuyển đổi sang EMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jpg/" style="padding:15px;">Chuyển đổi sang JPG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jpeg/" style="padding:15px;">Chuyển đổi sang JPEG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jp2/" style="padding:15px;">Chuyển đổi sang JP2</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/j2k/" style="padding:15px;">Chuyển đổi sang J2K</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jpeg2000/" style="padding:15px;">Chuyển đổi sang JPEG2000</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/png/" style="padding:15px;">Chuyển đổi sang PNG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/psd/" style="padding:15px;">Chuyển đổi sang PSD</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/dxf/" style="padding:15px;">Chuyển đổi sang DXF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/svg/" style="padding:15px;">Chuyển đổi sang SVG</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/tiff/" style="padding:15px;">Chuyển đổi sang TIFF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/webp/" style="padding:15px;">Chuyển đổi sang WEBP</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/wmf/" style="padding:15px;">Chuyển đổi sang WMF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/pdf/" style="padding:15px;">Chuyển đổi sang PDF</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/html/" style="padding:15px;">Chuyển đổi sang HTML</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/emz/" style="padding:15px;">Chuyển đổi sang EMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/wmz/" style="padding:15px;">Chuyển đổi sang WMZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/tga/" style="padding:15px;">Chuyển đổi sang TGA</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/svgz/" style="padding:15px;">Chuyển đổi sang SVGZ</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/canvas/" style="padding:15px;">Chuyển đổi sang CANVAS</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/ico/" style="padding:15px;">Chuyển đổi sang ICO</a></div>
<div class='col-md-3 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/apng/" style="padding:15px;">Chuyển đổi sang APNG</a></div>
                </div>
        </div>
    </div>
</div>

