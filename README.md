# CV Online - Hoàng Ngọc Anh

Trang CV trực tuyến của Hoàng Ngọc Anh - Kỹ sư phát triển phần mềm FullStack.

## 🌐 Demo

Bạn có thể xem CV trực tuyến tại: `https://[username].github.io/[repository-name]`

## 🚀 Cách deploy trên GitHub Pages

### Bước 1: Fork hoặc Clone repository
```bash
git clone https://github.com/[your-username]/[repository-name].git
cd [repository-name]
```

### Bước 2: Push code lên GitHub repository của bạn
```bash
git add .
git commit -m "Add CV HTML page"
git push origin main
```

### Bước 3: Cấu hình GitHub Pages
1. Vào repository trên GitHub
2. Click vào tab **Settings**
3. Scroll xuống phần **Pages** (ở sidebar bên trái)
4. Trong **Source**, chọn **Deploy from a branch**
5. Chọn branch **main** và folder **/ (root)**
6. Click **Save**

### Bước 4: Truy cập trang web
Sau vài phút, trang CV sẽ có thể truy cập tại:
`https://[your-username].github.io/[repository-name]`

## 📱 Tính năng

- ✅ **Responsive Design**: Tối ưu cho mọi thiết bị (desktop, tablet, mobile)
- ✅ **Modern UI**: Sử dụng Tailwind CSS cho giao diện hiện đại
- ✅ **SEO Friendly**: Cấu trúc HTML semantic tốt cho SEO
- ✅ **Fast Loading**: Sử dụng CDN cho Tailwind CSS và Font Awesome
- ✅ **Professional Layout**: Thiết kế chuyên nghiệp, dễ đọc

## 🛠️ Công nghệ sử dụng

- **HTML5**: Cấu trúc semantic
- **Tailwind CSS**: Styling và responsive design
- **Font Awesome**: Icons chuyên nghiệp
- **GitHub Pages**: Hosting miễn phí

## 📝 Cấu trúc file

```
CV2/
├── index.html          # File CV chính
├── README.md          # Hướng dẫn (file này)
├── plan.md           # Kế hoạch phát triển
├── 0001.png          # Hình ảnh CV gốc (trang 1)
└── 0002.png          # Hình ảnh CV gốc (trang 2)
```

## 🎨 Tùy chỉnh

### Thay đổi thông tin cá nhân
Chỉnh sửa file `index.html` và cập nhật các thông tin:
- Tên, chức vụ
- Thông tin liên lạc
- Kinh nghiệm làm việc
- Kỹ năng
- Học vấn
- Chứng chỉ

### Thay đổi màu sắc
Màu sắc được định nghĩa trong Tailwind config:
```javascript
colors: {
    'orange-custom': '#FF8C42',
    'blue-light': '#A8DADC',
    'blue-custom': '#457B9D',
}
```

### Thêm ảnh đại diện
Thay thế placeholder image bằng ảnh thật:
```html
<img src="path/to/your/avatar.jpg" alt="Hoàng Ngọc Anh" class="w-full h-full object-cover">
```

## 📞 Liên hệ

- **Email**: hoangngocann98@gmail.com
- **Phone**: 0337207999
- **Location**: Quận Đống Đa, TP Hà Nội

## 📄 License

Dự án này được phát hành dưới MIT License - xem file [LICENSE](LICENSE) để biết chi tiết.

---

**Lưu ý**: Đây là CV cá nhân, vui lòng không sử dụng thông tin cá nhân cho mục đích khác mà không có sự đồng ý. 