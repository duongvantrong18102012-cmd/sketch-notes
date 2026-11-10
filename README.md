# 📝 Ghi Chú — Sổ Phác Thảo (Sketch Notes)

> *"Một bản phác thảo được hoàn thiện trên giấy — tối giản, hoài cổ nhưng đầy cá tính."*

Chào mừng bạn đến với **Ghi Chú**, một ứng dụng web ghi chú cá nhân được thiết kế theo phong cách **Monochrome Sketch Brutalism**. 

Đây không chỉ là một công cụ lưu trữ văn bản thông thường, mà là một trải nghiệm thị giác mô phỏng lại cảm giác viết lách trên trang giấy vẽ với nét bút mực thô mộc.

---

## 🎨 Triết Lý Thiết Kế (Design Language)

Ứng dụng tuân thủ nghiêm ngặt các nguyên tắc thiết kế để mang lại cảm giác chân thực nhất:

*   **Đơn sắc (Monochrome):** Chỉ sử dụng 3 màu chủ đạo: Đen (`#141414`), Trắng (`#fcfcfa`), và Xám nhạt. Tuyệt đối không có màu sặc sỡ hay gradient.
*   **Nét vẽ tay (Sketch):** Đường viền (border) sắc nét, hơi thô, kết hợp cùng hiệu ứng đổ bóng cứng (hard drop-shadow) không làm mờ (blur).
*   **Chất liệu giấy (Paper Texture):** Nền trắng có lưới kẻ mảnh (grid) cùng hiệu ứng nhiễu hạt (noise overlay) tạo cảm giác như đang nhìn vào một trang giấy thật.
*   **Typography:** Sử dụng font chữ `Space Mono` và `IBM Plex Mono` mang hơi hướng máy đánh chữ (typewriter), tăng cảm giác hoài niệm.
*   **Bố cục (Layout):** Các thẻ ghi chú (note cards) được đặt ngẫu nhiên với độ nghiêng nhẹ, như những mẩu giấy được ghim lên bảng.

---

## ✨ Tính Năng Nổi Bật

*   **📌 Tạo & Chỉnh sửa linh hoạt:** Thêm ghi chú mới hoặc nhấn vào thẻ bất kỳ để mở trình soạn thảo (Editor).
*   **💾 Lưu trữ cục bộ (Local Storage):** Mọi dữ liệu được lưu trực tiếp trên trình duyệt của bạn. Không cần máy chủ, không cần đăng nhập, tải lại trang không mất dữ liệu.
*   **🔍 Tìm kiếm nhanh:** Thanh tìm kiếm giúp lọc ghi chú theo tiêu đề hoặc nội dung ngay lập tức.
*   **⌨️ Phím tắt tiện lợi:**
    *   `Ctrl / Cmd + K`: Nhảy nhanh đến thanh tìm kiếm.
    *   `Ctrl / Cmd + Enter`: Lưu ghi chú ngay khi đang gõ.
    *   `Esc`: Đóng trình soạn thảo.
*   **🗑️ Xóa an toàn:** Có hộp thoại xác nhận trước khi xóa vĩnh viễn ghi chú.

---

## 🚀 Cách Trải Nghiệm (Live Demo)

Ứng dụng đã được thiết lập để chạy trực tiếp trên **GitHub Pages**. Bạn có thể sử dụng ngay lập tức mà không cần cài đặt:

👉 **[BẤM VÀO ĐÂY ĐỂ MỞ ỨNG DỤNG](https://duongvantrong18102012-cmd.github.io/sketch-notes/)**

*(Lưu ý: Nếu link trên chưa hoạt động, hãy vào phần **Settings** > **Pages** > chọn nhánh `main` và bấm **Save** để kích hoạt).*

---

## 🛠️ Công Nghệ Sử Dụng

Dự án được xây dựng cực kỳ nhẹ nhàng, tối ưu hiệu năng, chỉ gói gọn trong **một file HTML duy nhất**:

*   **HTML5:** Cấu trúc ngữ nghĩa.
*   **Vanilla CSS:** Xử lý toàn bộ layout, hiệu ứng bóng đổ, lưới giấy và typography (Không dùng framework).
*   **Vanilla JavaScript:** Xử lý logic CRUD (Thêm, Đọc, Sửa, Xóa) và tương tác với `localStorage`.

---

<p align="center">
  <i>Được thiết kế với nét mực đen và những trang giấy trắng.</i>
</p>
