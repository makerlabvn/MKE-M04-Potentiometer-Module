# Mạch biến trở MKE-M04 potentiometer module

## Giới thiệu

Mạch biến trở MKE-M04 potentiometer module trả ra giá trị điện áp Analog tuyến tính với góc của trục xoay biến trở giúp bạn có thể ghi nhận và xử lý thông tin một cách chính xác nhất, ứng dụng trong các dạng điều khiển tăng giảm giá trị.

Mạch biến trở MKE-M04 potentiometer module thuộc hệ sinh thái phần cứng Robotics MakerEdu nên có thể sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....với chuẩn kết nối Connector XH2.54 thông dụng.

## Thông số kỹ thuật

- Điện áp hoạt động: 5VDC
- Chuẩn giao tiếp: Analog
- Điện áp giao tiếp: 0~3.3VDC
- Trả ra giá trị điện áp Analog tuyến tính với góc của trục xoay biến trở.
- Sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm giao tiếp ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, - Micro:bit,....
- Bổ sung thêm các thiết kế ổn định, chống nhiễu.
- Chuẩn kết nối: connector XH2.54 3Pins
- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các [mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.](https://wiki.makerlab.vn/index.php/MakerEdu)

## Hình ảnh sản phẩm

![MKE_M04_Potentiometer](/image/MKE_M04_Potentiometer_01.jpg)

![MKE_M04_Potentiometer](/image/MKE_M04_Potentiometer_02.jpg)

## Kích thước sản phẩm

![MKE_M04_Potentiometer](/image/MKE_M04_Potentiometer_03.jpg)

## Các chân tín hiệu

- GND:	Chân cấp nguồn âm 0VDC
- 5V:	Chân cấp nguồn dương 5VDC
- SIG:	Chân tín hiệu ngõ ra Analog Out

## Hướng dẫn sử dụng

### Các thiết bị sử dụng trong bài hướng dẫn:

#### Arduino:
- [Mạch Vietduino Uno (Arduino Uno Compatible)](https://github.com/makerlabvn/Vietduino-Uno)
- [Mạch MakerEdu Shield for Arduino](https://github.com/makerlabvn/MakerEdu-Shield-for-Arduino)
- [Mạch màn hình LCD1602 I2C Display Module](https://github.com/makerlabvn/MKE-M07-LCD1602-I2C-Display-Module)

#### mBlock:

- [Mạch MakerEdu Creator (Arduino Uno Compatible)](https://github.com/makerlabvn/MakerEdu-Creator)
- [Mạch màn hình LCD1602 I2C Display Module](https://github.com/makerlabvn/MKE-M07-LCD1602-I2C-Display-Module)

#### Micro:bit:

- Mạch Micro:bit V2 hoặc các phiên bản tương thích.
- [Mạch MakerEdu Shield for Micro:bit](https://github.com/makerlabvn/MakerEdu-Shield-for-Microbit)
- [Mạch màn hình LCD1602 I2C Display Module](https://github.com/makerlabvn/MKE-M07-LCD1602-I2C-Display-Module)

### Hướng dẫn sử dụng với Arduino (Code C)
- Tải và cài đặt [phần mềm Arduino tại đây.](https://www.arduino.cc/en/software)
- Trong Tools / Library Manager, tìm và cài đặt bộ thư viện tổng hợp "MAKERLABVN" by MakerLab.vn
- Mở chương trình mẫu tại File / Examples / MAKERLABVN / Sensor / MKE-M04_Potentiometer hoặc [tải chương trình mẫu tại đây](https://github.com/makerlabvn/makerlabvnlib/tree/main/examples/Module/MKE-M04_Potentiometer)
- Chọn board là Arduino Uno (mạch Vietduino Uno tương thích với Arduino Uno), chọn đúng cổng COM Port của mạch và tiến hành nạp chương trình.
- Kết nối mạch Vietduino Uno với MakerEdu Shield, kết nối biến trở tại cổng [A2] và màn hình LCD vào cổng [I2C] trên MakerEdu Shield, cấp nguồn qua cổng USB của Vietduino Uno để thấy chương trình hoạt động.

### Hướng dẫn lập trình với mBlock (kéo thả khối)

- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device "MakerEdu Creator" by MakerEduVN
- Thêm Extension "Upload Mode Broadcast" by mBlock Official
- Thêm Extension "MakerEdu Hardware" by MakerEduVN
- Mở [chương trình mẫu tại đây](https://github.com/makerlabvn/MKE-M04-Potentiometer-Module/tree/main/mBlock5), kết nối MakerEdu Creator với máy tính và nạp chương trình.
- Kết nối biến trở với cổng [A2] và màn hình LCD vào cổng [I2C] trên MakerEdu Creator, cấp nguồn qua cổng USB của MakerEdu Creator để thấy chương trình hoạt động.


### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động phần mềm MakeCode theo hướng dẫn.
- Cài đặt Extension MakerEdu Hardware trên MadeCode theo đường link sau: [https://github.com/makerlabvn/MakerEdu_Hardware](https://github.com/makerlabvn/MakerEdu_Hardware)
- Mở [chương trình mẫu tại đây](https://github.com/makerlabvn/MKE-M04-Potentiometer-Module/tree/main/microbit), kết nối Micro:bit với máy tính và nạp chương trình.
- Kết nối mạch Micro:bit với MakerEdu Shield, kết nối biến trở tại cổng [P1] và màn hình LCD vào cổng [I2C] trên MakerEdu Shield, cấp nguồn qua cổng USB của MakerEdu Shield để thấy chương trình hoạt động.

## Hỗ trợ và liên hệ:

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm tại các [nhà phân phối của MakerLab](https://www.makerlab.vn/nha-phan-phoi/).
