# 💌 Thiệp Cưới Online - Kiều Thu Hà & Nguyễn Hoàng Thiên Bình

Trang web thiệp cưới online phong cách **Vườn Hoa (Botanical Sage Garden)** thanh lịch, lãng mạn, được tối ưu hoàn toàn cho điện thoại di động (**Mobile-first**) và thiết kế chuẩn web tĩnh để triển khai hoàn toàn miễn phí trên **GitHub Pages (`github.io`)**.

---

## 🌿 Điểm nổi bật
- **Tone màu Botanical:** Xanh sage (`#4f633a`), lá olive, khung vòm nghệ thuật (*arch shapes*) và họa tiết hoa ép thảo mộc.
- **Tối ưu Mobile:** Giao diện co giãn mượt mà theo từng kích cỡ màn hình smartphone (iPhone, Samsung...), menu trượt tiện lợi, nút bấm to bản dễ thao tác cho cả người lớn tuổi.
- **Hiệu ứng cánh hoa & lá rơi:** Chuyển động lướt nhẹ nhàng, tạo cảm giác thơ mộng.
- **Lịch cưới & Đếm ngược:** Tờ lịch tháng 11/2026 với ngày **28** được khoanh vòng lá thảo mộc; đồng hồ đếm ngược từng giây đến giờ lành (09:00 ngày 28/11/2026).
- **Nhạc nền lãng mạn:** Tích hợp bài hát *Beautiful in White* (Shane Filan) kèm đĩa xoay phát nhạc ở góc màn hình.
- **Album ảnh kỷ niệm:** Khung ảnh vòm cong so le, hỗ trợ phóng to (Lightbox) và vuốt chạm chuyển ảnh trên điện thoại.
- **Bản đồ chỉ đường:** Tích hợp liên kết Google Maps dẫn đường trực tiếp đến tư gia Nhà Gái tại Thôn Trung Hưng, xã Hợp Thịnh, thành phố Bắc Ninh.
- **Sổ lưu bút & Xác nhận tham dự:** Khách có thể nhập lời chúc và xác nhận tham dự, tự động lưu và hiển thị ngay trên trang.

---

## 📁 Cấu trúc thư mục
```text
ThiepCuoi/
├── index.html              # Trang chủ thiệp cưới
├── css/
│   └── style.css           # Toàn bộ CSS phong cách Vườn Hoa & Responsive Mobile
├── js/
│   └── main.js             # Logic đếm ngược, hiệu ứng lá bay, phát nhạc, lightbox, RSVP
├── audio/
│   ├── beautiful-in-white.mp3  # Nhạc nền chính (Beautiful in White)
│   └── wedding-music.mp3       # Nhạc nền dự phòng (Canon in D)
├── img/
│   ├── hero-banner.jpg     # Ảnh bìa chính
│   ├── bride.jpg           # Chân dung cô dâu Thu Hà
│   ├── groom_front.jpg     # Chân dung chú rể Thiên Bình
│   └── ...                 # Các ảnh trong Album kỷ niệm
└── README.md
```

---

## 🚀 Hướng dẫn xem trước trên máy tính (Local)
Mở ứng dụng **Terminal** tại thư mục này và chạy lệnh:
```bash
python3 -m http.server 8088
```
Sau đó mở trình duyệt truy cập: **[http://localhost:8088](http://localhost:8088)**

---

## 🌐 Hướng dẫn đưa lên GitHub Pages (`github.io`)

### Bước 1: Khởi tạo Git và Commit
Trong thư mục `ThiepCuoi`, chạy các lệnh sau:
```bash
git init
git add .
git commit -m "Thiệp cưới online Kiều Thu Hà & Nguyễn Hoàng Thiên Bình"
```

### Bước 2: Tạo Repository trên GitHub và đẩy mã nguồn lên
1. Vào [GitHub](https://github.com/new) tạo một repository mới (ví dụ đặt tên là `ThiepCuoi` hoặc `damcuoi-haco`).
2. Chọn chế độ **Public**.
3. Chạy lệnh liên kết và đẩy code lên:
```bash
git branch -M main
git remote add origin https://github.com/<tai-khoan-cua-ban>/ThiepCuoi.git
git push -u origin main
```

### Bước 3: Bật GitHub Pages
1. Trên trang repository vừa tạo ở GitHub, vào mục **Settings** (Cài đặt) -> chọn thẻ **Pages** ở thanh menu bên trái.
2. Tại mục **Build and deployment** -> **Branch**:
   - Chọn nhánh **`main`**
   - Thư mục chọn **`/(root)`**
   - Bấm **Save**.
3. Chờ khoảng 1 - 2 phút, GitHub sẽ cung cấp link trang web thiệp cưới có dạng:
   **`https://<tai-khoan-cua-ban>.github.io/ThiepCuoi/`**

Bạn có thể gửi đường link này qua Zalo, Messenger hoặc tạo mã QR in lên thiệp giấy gửi đến bạn bè, người thân!
