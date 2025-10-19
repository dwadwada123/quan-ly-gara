# Đồ án môn học SOF1021: Phần mềm Quản lý Gara Sửa chữa 🚗

Đây là repository lưu trữ toàn bộ tài liệu cho đồ án môn học Nhập môn Kỹ thuật Phần mềm (SOF1021), được thực hiện bởi Nhóm 4.

## Giới thiệu

Trong bối cảnh nhu cầu sử dụng và bảo dưỡng phương tiện giao thông ngày càng gia tăng, các gara sửa chữa đóng vai trò rất quan trọng. Tuy nhiên, tại nhiều gara, việc quản lý thông tin khách hàng, lịch hẹn, dịch vụ sửa chữa và chi phí vẫn còn thủ công, dễ dẫn đến nhầm lẫn và làm giảm hiệu quả hoạt động.

Dự án **"Ứng dụng Quản Lý Gara Sửa Chữa"** nhằm mục đích xây dựng một hệ thống đơn giản, trực quan giúp số hóa các quy trình nghiệp vụ cốt lõi, từ đó nâng cao hiệu quả hoạt động của gara.

## Thành viên Nhóm 4 👥

| Họ và tên          | MSSV    |
| ------------------ | ------- |
| Trần Lê Quốc Dũng  | PD11563 |
| Trần Vũ Phong      | PD11581 |
| Phạm Đức Anh Tài   | PD11720 |
| Trần Tâm           | PD11941 |

## Chức năng chính ✨

Hệ thống tập trung vào các nhóm chức năng cốt lõi để phục vụ toàn bộ quy trình vận hành của một gara sửa chữa:

* **Quản lý Khách hàng & Xe:** Lưu trữ thông tin chi tiết của khách hàng và các xe sở hữu, tra cứu lịch sử sửa chữa.
* **Tiếp nhận & Theo dõi Dịch vụ:** Tạo phiếu tiếp nhận xe, ghi nhận tình trạng ban đầu, lên lịch hẹn và cập nhật trạng thái công việc.
* **Quản lý Kho Phụ tùng:** Quản lý danh mục phụ tùng và tự động trừ kho khi vật tư được sử dụng.
* **Lập hóa đơn & Thanh toán:** Tự động tính toán chi phí dịch vụ, tạo và in hóa đơn chi tiết, ghi nhận các phương thức thanh toán.
* **Báo cáo & Thống kê:** Xuất báo cáo doanh thu, thống kê các dịch vụ và phụ tùng phổ biến.
* **Quản lý Nhân sự & Phân quyền:** Quản lý thông tin nhân viên và phân quyền truy cập hệ thống theo từng vai trò cụ thể.

## Công nghệ & Kiến trúc 🏗️

Dự án được thiết kế theo **Kiến trúc Phân tầng 3 Lớp (3-Tier Layered Architecture)** để đảm bảo tính linh hoạt, dễ bảo trì và khả năng mở rộng.

* **Tầng Trình bày (Presentation Tier):** Giao diện người dùng (UI) hoạt động trên đa nền tảng.
* **Tầng Logic Nghiệp vụ (Logic Tier):** "Bộ não" của hệ thống, xử lý tất cả các quy tắc nghiệp vụ.
* **Tầng Dữ liệu (Data Tier):** Chịu trách nhiệm lưu trữ và truy xuất toàn bộ dữ liệu.

## Cấu trúc Repository

Toàn bộ tài liệu của dự án được tổ chức trong repository này theo cấu trúc sau:
/
  Assignment_Nhom4_SOF1021.docx
  TaiLieuPhanTich/
    Lab1_PhanTichBaiToan.docx
    Lab2_PhanTichYeuCau.docx
    Lab3_TaiLieuSRS.docx
  ThietKeHeThong/
    Lab4_ThietKeUseCase.docx
    Lab5_ThietKeKienTruc.docx
    Lab6_ThietKeUML.docx
  TaiLieuKiemThu/
    Lab7_KiemThuPhanMem.docx
  QuanLyDuAn/
    Lab8_QuanLyDuAn.docx
  README.md

## Cách sử dụng

Toàn bộ tài liệu của dự án từ giai đoạn phân tích yêu cầu, thiết kế hệ thống, kiểm thử cho đến quản lý dự án đều được lưu trữ trong các thư mục tương ứng. Báo cáo tổng hợp cuối kỳ nằm ở file `Assignment_Nhom4_SOF1021.docx`.
