# Bảng Mạch Phát Triển Tối Thiểu STM32F030F4P6

Đây là 1 bo mạch giá rẻ nhát thuộc họ STM32 có thể thấy ở Việt Nam, khoảng 25k ở trên Shopee được bán bởi các shop Trung Quốc. 

Bo mạch sử dụng vi điểu khiển STM30F030F4P6.

Bo mach có 1 nhược điểm rất lớn là bộ nhớ flash chỉ 16kb. Việc khởi tạo các thiết bị ngoại vi sẽ chiếm khoảng 7kb, 1 chương trình blink led đơn giản sẽ tốn từ 9-15kb tùy theo IDE :GO,ARDUINO,KeilC,IAR,STM32CUBE,... 

Đây là giải pháp tiết kiệm bộ nhớ trên Arduino IDE : U(S)ART support chọn disable UART và optimize chọn * with LTO , nó sẽ giúp bản tiết kiệm kha khá bộ nhớ flash. mình thường lưa chọn : Smallest with LTO

Rất mong các bác có giải pháp tiết kiệm bộ nhớ trên các IDE khác có thể chia sẻ.

Khuyến khích mua BluePill STM32F103C8T6 giá chỉ khoảng 36k được bán bởi các shop Trung Quốc hoặc board STM32F030K6T6 giá 30k với bộ nhớ flash 32kb-gấp đôi 16kb trên bản F030F4P6 được phát triển bởi AEShop th

1 số hình ảnh tham khảo :
