# BÀI TẬP TỔNG HỢP: HỒ SƠ DỰ ÁN VÍ ĐIỆN TỬ "PAYKX"


---

## PHẦN 1: PHÂN TÍCH CƠ SỞ DỮ LIỆU ĐỐI SOÁT (EXCEL)

Trong bảng tính Excel quản lý giao dịch và biểu phí của ví điện tử "PayKX", việc tổ chức cấu trúc dữ liệu tuân thủ nghiêm ngặt các quy tắc cơ sở dữ liệu (Database) được phân tích như sau:

1. **Khái niệm Record (Bản ghi / Dòng):**
   * Mỗi một hàng trong bảng tính Excel đại diện cho một **Record** (bản ghi duy nhất) chứa toàn bộ thông tin chi tiết của một giao dịch cụ thể (Ví dụ: Giao dịch nạp tiền, chuyển tiền hoặc thanh toán dịch vụ của một sinh viên gồm: *Mã giao dịch, Mã người dùng, Tên người dùng, Số tiền, Trạng thái, Phí đối tác*).
2. **Khái niệm Field (Trường / Cột):**
   * Mỗi một cột trong bảng tính đại diện cho một **Field** (trường dữ liệu), mang một kiểu dữ liệu đồng nhất và mô tả một thuộc tính cụ thể của bản ghi (Ví dụ: Cột `Ma_Giao_Dich` lưu mã ID, cột `So_Tien` lưu giá trị số, cột `Trang_Thai` lưu giá trị văn bản).

---

## PHẦN 2: TRIỂN KHAI HỒ SƠ DỰ ÁN 3 BỘ PHẬN (WORD, EXCEL, POWERPOINT)

### 1. Phần Word: Cấu trúc Tài liệu SRS (Software Requirements Specification)
Tài liệu SRS độ dài 5 trang của hệ thống ví điện tử "PayKX" được thiết lập cấu trúc phân cấp chuẩn bằng Markdown:

# 📱 Tài liệu Đặc tả Yêu cầu Phần mềm (SRS) - Ví điện tử PayKX

## 1. Giới thiệu tổng quan
- 1.1 Mục đích dự án ví điện tử dành cho sinh viên.
- 1.2 Phạm vi hệ thống và đối tượng sử dụng (Sinh viên PTIT, Nhà trường, Đối tác liên kết).

## 2. Mô tả tính năng hoàn tiền (Cashback)
- 2.1 Cơ chế tích lũy điểm thưởng và hoàn tiền khi thanh toán học phí, dịch vụ học tập.
- 2.2 Luồng xử lý giao dịch hoàn tiền tự động theo thời gian thực.

## 3. Yêu cầu chức năng hệ thống (Functional Requirements)
- 3.1 Quản lý tài khoản và định danh sinh viên (eKYC).
- 3.2 Tích hợp cổng thanh toán liên ngân hàng và ví điện tử.
- 3.3 Hệ thống đối soát giao dịch tự động hàng tháng.

## 4. Yêu cầu phi chức năng
- 4.1 Bảo mật thông tin tài chính và mã hóa dữ liệu người dùng.
- 4.2 Hiệu năng xử lý giao dịch đạt tốc độ dưới 2 giây.

## 5. Phụ lục và Thuật ngữ kỹ thuật