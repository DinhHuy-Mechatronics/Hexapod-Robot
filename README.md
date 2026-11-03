# 🔗 **[Xem thêm tại trang của tôi](https://dinhhuy-mechatronics.github.io/HUY.MEC/#projects)**

# Dự án Robot Hexapod 18 Bậc Tự Do (18-DOF)

## Tổng quan
Kho lưu trữ này chứa các tài liệu thiết kế, tính toán cơ khí và mã nguồn điều khiển cho robot Hexapod 6 chân. Mỗi chân của robot có 3 bậc tự do (DOF), tổng cộng 18 DOF. Dự án tập trung vào tính toán và thiết kế cơ khí, đi dây điện, tích hợp servo với bộ điều khiển và phối hợp lập trình chuyển động các khớp.

## Phần cứng sử dụng
- **Vi điều khiển chính:** ESP32-C3
- **Driver điều khiển Servo:** 2 x PCA9685 (giao tiếp I2C)
- **Động cơ:** 18 x Servo

## Phần mềm & Công cụ
- **MATLAB:** Cung cấp các script để hỗ trợ dựng mô hình, kiểm tra động học (Forward/Inverse Kinematics) và thử nghiệm mô phỏng dáng đi trước khi chạy thực tế trên robot.
- **Firmware:** Lập trình C/C++ trên ESP32-C3 để nhận lệnh và điều khiển 18 servo thông qua 2 driver PCA9685.

## Cấu trúc công việc
1. **Thiết kế & Tính toán cơ khí:** Phân tích lực, tầm với và thiết kế khung vỏ.
2. **Đi dây & Tích hợp điện:** Quản lý nguồn và tín hiệu cho hệ thống 18 servo công suất cao cùng vi điều khiển.
3. **Động học & Mô phỏng:** Sử dụng MATLAB để tính toán quỹ đạo và mô phỏng.
4. **Điều khiển chuyển động:** Phát triển thuật toán tạo dáng đi (gait) và phối hợp chuyển động các khớp đồng bộ.

<p align="center">
  <img src="hexapod-robot-main/%E1%BA%A2nh%20minh%20h%E1%BB%8Da%203.jpg" alt="Hexapod Robot" width="700"/>
</p>


