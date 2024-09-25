I'm new at coding and I would like copy facebook app comment section where the send icon is part of the textarea and positioned at the right end.

I have experimented with the following code but when I type in the textarea, it overlaps under the send icon. And also the icon does not stay at the bottom but instead stays on top when I type many texts.
 do not use Ionic but here is the general idea. You wrap the input and the icon in a container div that will look like the input field. You use calc(100% - 25px) to set the size of the textarea and position: absolute; with bottom: 10px; to keep the icon at the bottom.
 https://chuyengiakholanh.com/gioi-thieu/
 
TCold chuyên thiết kế, lắp đặt kho lạnh, kho lạnh mini, kho đông lạnh, kho cấp đông, kho lạnh bảo quản Vắc Xin và các dịch vụ thiết kế, bảo trì, sửa chữa, lắp đặt kho lạnh công nghiệp trên toàn quốc.
Kho lạnh 10 khối mang lại nhiều ưu điểm vượt trội, đặc biệt phù hợp cho các doanh nghiệp vừa và nhỏ hoặc hộ gia đình có nhu cầu bảo quản thực phẩm, nông sản với số lượng lớn. https://chuyengiakholanh.com/kho-lanh/kho-lanh-10m3/
Kho lạnh 20m3 được kiểm nghiệm thông qua phòng thí nghiệm phát triển sản phẩm Tcold và hoàn thành xuất sắc các bài kiểm thử, đạt độ bền và duy trì tuổi thọ máy rất lâu. https://chuyengiakholanh.com/kho-lanh/kho-lanh-20m3/
TCold có thể giải quyết các yêu cầu của khách hàng về lắp đặt kho lạnh mini thiết kế theo yêu cầu riêng. https://chuyengiakholanh.com/kho-lanh/kho-lanh-mini/
Kho lạnh cấp đông là một giải pháp bảo quản thực phẩm hiệu quả, được ứng dụng rộng rãi trong nhiều ngành công nghiệp. Dưới đây là những ưu điểm nổi bật của loại kho lạnh cấp đông: https://chuyengiakholanh.com/kho-lanh/kho-lanh-cap-dong/
