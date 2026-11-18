# To-Do List - Ứng dụng Quản lý Công việc Cá nhân

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Course](https://img.shields.io/badge/Course-QTDA__CNTT-blue)
![Team](https://img.shields.io/badge/Members-4-orange)

## 📖 Giới thiệu dự án

**To-Do List** là một ứng dụng web gọn nhẹ giúp người dùng ghi chú, phân loại và theo dõi tiến độ các công việc cần làm hằng ngày. Dự án được xây dựng trong khuôn khổ học phần **Quản trị dự án Công nghệ thông tin** (Lớp 67KTPM1 - Trường Đại học Thủy lợi) nhằm áp dụng thực tế quy trình quản lý mã nguồn, phân chia công việc nhóm và theo dõi tiến độ trên nền tảng GitHub.

---

## 🎯 Mục tiêu dự án

### 1. Mục tiêu về sản phẩm (Product Goals)

- Xây dựng giao diện web trực quan, thân thiện, cho phép người dùng thêm mới, đánh dấu hoàn thành và xóa công việc nhanh chóng.
- Đảm bảo ứng dụng hoạt động ổn định, phản hồi tức thì trên các trình duyệt web phổ biến mà không cần cài đặt phức tạp.

### 2. Mục tiêu về quản trị dự án & quy trình làm việc (Project Management Goals)

- Thiết lập và vận hành thành thạo kho lưu trữ mã nguồn (Repository) và bảng quản lý công việc (GitHub Projects).
- Thực hành quy trình làm việc nhóm chuẩn trên Git: phân chia nhánh (`branch`), tạo `Issues`, thực hiện `Pull Request` và rà soát mã nguồn (`Code Review`) trước khi gộp vào nhánh chính (`main`).
- Phân bổ nhiệm vụ rõ ràng, đảm bảo tiến độ hoàn thành đúng hạn của từng thành viên.

---

## 👥 Thành viên nhóm & Phân công vai trò

| STT | Họ và tên                               | Vai trò                                       | Nhiệm vụ chính                                                                                                                                                                                                                                                                                     |
| :-: | :-------------------------------------- | :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  1  | **Nguyễn Thị Hằng** _(MSV: 2451160772)_ | **Nhóm trưởng (Project Manager / Tech Lead)** | - Khởi tạo Repository, thiết lập GitHub Projects và mời thành viên.<br>- Lập kế hoạch, phân chia task (Issues) và theo dõi tiến độ chung.<br>- Thiết kế kiến trúc thư mục, rà soát (Review) và gộp code (`Merge Pull Request`) vào nhánh `main`.<br>- Viết tài liệu tổng quan dự án (`README.md`). |
|  2  | **Phạm Thị Khánh Hòa**                  | **Phát triển Giao diện (Frontend Developer)** | - Thiết kế bố cục và xây dựng cấu trúc trang web (`index.html`).<br>- Định dạng giao diện, màu sắc và tối ưu trải nghiệm người dùng (`CSS`).<br>- Tạo nhánh tính năng giao diện và gửi Pull Request.                                                                                               |
|  3  | **Vi Thị Thúy Ngân**                    | **Phát triển Chức năng (Logic Developer)**    | - Xây dựng các hàm xử lý logic bằng `JavaScript` (thêm công việc, đánh dấu hoàn thành, xóa công việc).<br>- Xử lý kiểm tra dữ liệu đầu vào (Validation) tránh nhập rỗng.<br>- Tạo nhánh tính năng xử lý và gửi Pull Request.                                                                       |
|  4  | **Vũ Thu Thủy**                         | **Kiểm thử & Tài liệu (QA / Tester & Doc)**   | - Lập kịch bản kiểm thử (Test cases) và kiểm tra lỗi giao diện, chức năng trên các trình duyệt.<br>- Báo cáo lỗi qua tab `Issues` trên GitHub.<br>- Tổng hợp báo cáo tiến độ và hoàn thiện tài liệu hướng dẫn sử dụng.                                                                             |

---

## 🛠 Công nghệ & Công cụ sử dụng

- **Ngôn ngữ lập trình:** HTML5, CSS3, JavaScript (Vanilla JS)
- **Quản lý mã nguồn & Dự án:** Git, GitHub, GitHub Projects
- **Công cụ phát triển:** Visual Studio Code

---

## 🚀 Hướng dẫn cài đặt và chạy dự án

1. **Clone repository về máy cá nhân:**
   ```bash
   git clone [https://github.com/nguyennhang416/QTDA_CNTT.git](https://github.com/nguyennhang416/QTDA_CNTT.git)
   ```
