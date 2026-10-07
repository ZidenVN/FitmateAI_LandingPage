# Fitmate - Nền Tảng Sức Khỏe & Huấn Luyện Viên Cá Nhân
> **Dự án khởi nghiệp công nghệ môn học EXE201 - Đại học FPT**

---

## 🎯 Mục tiêu đồ án & Đáp ứng 3 Outcomes môn EXE201

1. **Outcome 1 (40%) - MVP Sản Phẩm:**
   - Landing page hoạt động tương tác thời gian thực, mô phỏng đầy đủ trải nghiệm ứng dụng Fitmate.
   - Hỗ trợ luồng mô phỏng tải file cài đặt **Fitmate APK (Android)** cho tester và hội đồng chấm điểm.

2. **Outcome 2 (20%) - Customer Acquisition Plan (CAP):**
   - Kênh chuyển đổi trực tiếp trên Landing page cho chiến dịch marketing (Facebook, TikTok, phát tờ rơi, sự kiện offline).
   - Tích hợp form thu thập thông tin khách hàng tiềm năng (Lead Generation), phân loại theo nhu cầu (Giảm mỡ, Tăng cơ, Ăn sạch, Thuê PT).

3. **Outcome 3 (40%) - Khách Hàng Đạt Được (Acquired Customers):**
   - Tích hợp hệ thống quản trị dữ liệu khách hàng đăng ký (Lead Management Console) lưu trực tiếp trên trình duyệt (`localStorage`).
   - Cung cấp tính năng **Xuất tệp CSV báo cáo danh sách khách hàng** (`Ctrl + Shift + L` hoặc bấm nút dưới Footer) để nộp minh chứng khách hàng cho giảng viên.

---

## ⚡ Các Tính Năng Interactive Nổi Bật Trên Landing Page

- **Máy quét món ăn AI (Phần 4):**
  - Chuyển đổi linh hoạt giữa các món ăn Việt Nam (Phở Bò, Cơm Tấm, Salad Ức Gà, Bún Bò Huế) hoặc tải ảnh món ăn từ máy tính.
  - Hiệu ứng quét laser AI trong thời gian thực.
  - Điều chỉnh khẩu phần (0.5x, 1.0x, 1.5x, 2.0x) tự động tính toán lại Calo, Đạm, Tinh bột, Chất béo.
  - Bấm **"Xác nhận và lưu vào nhật ký"** sẽ cập nhật ngay vào widget calo ở đầu trang và bắn thông báo Toast.

- **Phòng tập trực tiếp & Bộ đếm thời gian (Phần 5):**
  - Đồng hồ đếm ngược thời gian nghỉ (Rest timer) có nút Bắt đầu, Tạm dừng, +15s.
  - Danh sách hiệp tập có thể click trực tiếp để chuyển trạng thái: `✓ Hoàn thành`, `⏳ Đang nghỉ`, `▶ Chờ tập`.
  - Tùy chỉnh nhanh mức tạ (+/- 2.5kg) và số rep (+/- 1 rep).
  - Nút **"Hoàn thành buổi tập"** cập nhật chuỗi Streak.

- **Khám phá & Đặt lịch Huấn luyện viên (PT Booking) (Phần 6):**
  - Bộ lọc PT theo chuyên môn: Tất cả, Tăng cơ, Giảm mỡ, HLV Nữ, Calisthenics.
  - Modal đặt lịch 4 bước minh bạch: Chọn ngày, chọn khung giờ trống (Sáng/Chiều/Tối), điền thông tin và xuất mã đặt chỗ kèm chi phí niêm yết.

- **Bảng tin cộng đồng (Phần 7):**
  - Thả tim tương tác (tăng/giảm số lượt thích).
  - Album ảnh chuyển tiếp 3 tấm (Next/Prev + Dots).
  - Khung bình luận (Comment drawer): xem bình luận và gửi bình luận mới với phản hồi tức thì.
  - Nút chia sẻ bài viết (Sao chép liên kết vào Clipboard).

- **Trợ lý AI tiếng Việt (Phần 8):**
  - Trò chuyện trực tiếp: người dùng có thể gõ câu hỏi bất kỳ hoặc bấm các gợi ý nhanh (Bữa phụ trước tập, Tính TDEE, Dinh dưỡng trứng gà, Thực đơn sinh viên).
  - Hiệu ứng AI suy nghĩ và phản hồi chi tiết, khoa học, gần gũi với ẩm thực Việt.
  - Chuyển đổi qua lại giữa các chủ đề trò chuyện trong lịch sử.

- **Đăng ký trải nghiệm Beta & Quản trị Leads (Phần 10, 13 & Footer):**
  - Chuyển đổi chu kỳ thanh toán Tháng / Năm (Tiết kiệm 20%).
  - Form đăng ký nhận mã VIP Beta Pass.
  - Phím tắt `Ctrl + Shift + L` mở **Bảng điều khiển khách hàng EXE201** để xem và xuất file CSV nộp bài.

---

## 🚀 Hướng Dẫn Chạy & Triển Khai

### Cách 1: Chạy trực tiếp (Không cần cài đặt thêm)
- Click đúp vào file `d:\FPT\EXE201\index.html` để mở ngay trên trình duyệt (Chrome, Edge, Brave, Cốc Cốc). Toàn bộ chức năng tương tác đều hoạt động 100%.

### Cách 2: Chạy Dev Server với Vite (Khuyên dùng)
```bash
# Di chuyển vào thư mục EXE201
cd d:\FPT\EXE201

# Chạy server phát triển cục bộ
npm run dev
```
Trình duyệt sẽ mở tại địa chỉ: `http://localhost:5174` (hoặc IP mạng nội bộ để test trên điện thoại).

### Cách 3: Build & Deploy lên Vercel / Netlify / GitHub Pages
```bash
npm run build
```
Thư mục `dist/` sẵn sàng để bạn kéo thả lên Vercel hoặc Netlify để có đường link online gửi cho người dùng và nộp bài môn EXE201!
