
---
title: Chuyển đổi định dạng hình ảnh Java 
weight: 3920
url: /vi/java/conversion 
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
		<div class="row other-converters">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/apng-to-bmp/">APNG đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/cdr-to-bmp/">CDR đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/dib-to-bmp/">DIB đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/dicom-to-bmp/">DICOM đến BMP</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/djvu-to-bmp/">DJVU đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/dng-to-bmp/">DNG đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/emf-to-bmp/">EMF đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/emz-to-bmp/">EMZ đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/eps-to-bmp/">EPS đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/gif-to-bmp/">GIF đến BMP</a>
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
		<div class="row other-converters">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/apng-to-PSD/">APNG đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/jpeg-to-PSD/">JPEG đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/bmp-to-PSD/">BMP đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/odg-to-PSD/">ODG đến PSD</a>
		   </div>
 		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/otg-to-PSD/">OTG đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/png-to-PSD/">PNG đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/svg-to-PSD/">SVG đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/emz-to-PSD/">EMZ đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/eps-to-PSD/">EPS đến PSD</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/gif-to-PSD/">GIF đến PSD</a>
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
		<div class="row other-converters">
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/CDR-to-bmp/">CDR đến BMP</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/CDR-to-jpeg/">CDR đến JPEG</a>
		   </div>
		   <div class="col-md-2 other-converter remove-lp remove-rp">
		      <a href="/imaging/vi/java/conversion/CDR-to-png/">CDR đến PNG</a>
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
		<div class="row other-converters">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/apng" >chuyển đổi từ APNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/bmp" >chuyển đổi từ BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/dib" >chuyển đổi từ DIB</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/dicom" >chuyển đổi từ DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/djvu" >chuyển đổi từ DJVU</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/dng" >chuyển đổi từ DNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/emf" >chuyển đổi từ EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/emz" >chuyển đổi từ EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/gif" >chuyển đổi từ GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jpeg2000" >chuyển đổi từ JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jp2" >chuyển đổi từ JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/j2k" >chuyển đổi từ J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jpg" >chuyển đổi từ JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/jpeg" >chuyển đổi từ JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/png" >chuyển đổi từ PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/tga" >chuyển đổi từ TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/tif" >chuyển đổi từ TIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/tiff" >chuyển đổi từ TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/webp" >chuyển đổi từ WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/wmf" >chuyển đổi từ WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/wmz" >chuyển đổi từ WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/svg" >chuyển đổi từ SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/svgz" >chuyển đổi từ SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/eps" >chuyển đổi từ EPS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/cdr" >chuyển đổi từ CDR</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/cmx" >chuyển đổi từ CMX</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/otg" >chuyển đổi từ OTG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/odg" >chuyển đổi từ ODG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/from/ico" >chuyển đổi từ ICO</a></div>
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
		<div class="row other-converters">
		    <div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/bmp" >Chuyển đổi sang BMP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/gif" >Chuyển đổi sang GIF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/dicom" >Chuyển đổi sang DICOM</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/emf" >Chuyển đổi sang EMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jpg" >Chuyển đổi sang JPG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jpeg" >Chuyển đổi sang JPEG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jp2" >Chuyển đổi sang JP2</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/j2k" >Chuyển đổi sang J2K</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/jpeg2000" >Chuyển đổi sang JPEG2000</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/png" >Chuyển đổi sang PNG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/psd" >Chuyển đổi sang PSD</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/dxf" >Chuyển đổi sang DXF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/svg" >Chuyển đổi sang SVG</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/tiff" >Chuyển đổi sang TIFF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/webp" >Chuyển đổi sang WEBP</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/wmf" >Chuyển đổi sang WMF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/pdf" >Chuyển đổi sang PDF</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/html" >Chuyển đổi sang HTML</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/emz" >Chuyển đổi sang EMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/wmz" >Chuyển đổi sang WMZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/tga" >Chuyển đổi sang TGA</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/svgz" >Chuyển đổi sang SVGZ</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/canvas" >Chuyển đổi sang CANVAS</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/ico" >Chuyển đổi sang ICO</a></div>
<div class='col-md-2 other-converter remove-lp remove-rp'><a href="/imaging/vi/java/conversion/to/apng" >Chuyển đổi sang APNG</a></div>
                </div>
        </div>
    </div>
</div>

