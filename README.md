# 📚 Khóa Học HTML & CSS - Từ Cơ Bản Đến Nâng Cao

![HTML & CSS](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

> Khóa học toàn diện về HTML & CSS, được thiết kế đặc biệt cho người mới bắt đầu với các ví dụ thực tế và dễ hiểu.

---

## 🎯 Mục Tiêu Khóa Học

Khóa học này sẽ giúp bạn:

- ✅ Nắm vững các thẻ HTML cơ bản và nâng cao
- ✅ Hiểu rõ cấu trúc và ngữ nghĩa của HTML5
- ✅ Làm việc với Forms, Tables, Lists
- ✅ Tối ưu hóa hình ảnh, video, audio cho web
- ✅ Áp dụng CSS để tạo giao diện đẹp mắt
- ✅ Sử dụng Emmet để viết code nhanh hơn
- ✅ Hiểu về Semantic HTML cho SEO tốt hơn

---

## 📂 Cấu Trúc Dự Án

```
html+css/
│
├── index.html                    # Bài học về các thẻ cơ bản (h1-h6, p, a, img, video, audio)
├── emmet.html                    # Hướng dẫn sử dụng Emmet để code nhanh
├── form.html                     # Form đăng nhập cơ bản
├── form2.html                    # Form đăng ký hội fan bóng đá (nâng cao)
├── list_example.html             # Các loại danh sách (ol, ul, dl)
├── table_example.html            # Bảng dữ liệu với các ví dụ thực tế
├── div_example.html              # Sử dụng div và span để bố cục
├── div_example_semantic.html     # Semantic HTML (header, nav, main, section, article, aside, footer)
├── semantic_example.html         # Ví dụ nâng cao về Semantic HTML
│
└── assets/                       # Thư mục chứa tài nguyên
    ├── babythree1.webp          # Hình ảnh mẫu
    ├── babythree2.jpeg          # Hình ảnh mẫu
    ├── video.mp4                # Video mẫu
    ├── video.webm               # Video tối ưu
    ├── video_cover.png          # Thumbnail video
    ├── audio.mp3                # Audio mẫu
    └── audio.ogg                # Audio tối ưu
```

---

## 📖 Nội Dung Từng Bài Học

### 1️⃣ **index.html** - Các Thẻ HTML Cơ Bản

**Nội dung học:**

- Thẻ tiêu đề (`<h1>` - `<h6>`)
- Đoạn văn (`<p>`)
- Liên kết (`<a>`) với các thuộc tính: `href`, `target`, `title`, `download`
- Hình ảnh (`<img>`) và tối ưu hóa với định dạng WebP
- Video (`<video>`) với nhiều source và poster
- Audio (`<audio>`)

**Kiến thức nổi bật:**

- ⚡ Tối ưu hình ảnh bằng WebP để giảm dung lượng
- 🎬 Sử dụng nhiều định dạng video để tương thích đa trình duyệt
- 🔗 Bảo mật liên kết với `rel="noreferrer noopener"`

---

### 2️⃣ **emmet.html** - Viết Code Nhanh Với Emmet

**Nội dung học:**

- Tạo thẻ nhanh: gõ tên thẻ + `Tab`
- Lặp lại thẻ: `div*3`
- Tạo cấu trúc lồng nhau: `header>nav>ul>li*3`
- Thêm thuộc tính: `input[type="radio"]*3`
- Thêm class: `.content`
- Thêm id: `#header`
- Tạo phần tử anh em: `h1+h2+p`

**Lợi ích:**

- ⚡ Tăng tốc độ code lên 5-10 lần
- 🎯 Giảm lỗi cú pháp
- 💪 Tăng năng suất làm việc

---

### 3️⃣ **form.html & form2.html** - Làm Việc Với Forms

**form.html** - Form đăng nhập cơ bản:

- Input types: `email`, `password`
- Checkbox: `remember me`
- Button submit

**form2.html** - Form đăng ký phức tạp:

- Text input với `size`, `placeholder`, `required`
- Textarea với `spellcheck`
- Radio buttons cho giới tính
- Select dropdown cho vị trí đá
- Number input với `min`, `max`, `step`
- Datalist cho tự động hoàn thành
- Buttons: `submit`, `reset`

**Kiến thức quan trọng:**

- 🔐 Sự khác nhau giữa `id` và `name`
- ✅ Validation với `required`
- 📝 UX tốt với `placeholder` và `label`

---

### 4️⃣ **list_example.html** - Các Loại Danh Sách

**Nội dung học:**

- Ordered List (`<ol>`) với types: `1`, `a`, `A`, `I`, `i`
- Unordered List (`<ul>`) với types: `circle`, `disc`, `square`
- Description List (`<dl>`, `<dt>`, `<dd>`)
- Danh sách lồng nhau

**Ứng dụng thực tế:**

- 📝 Tạo menu điều hướng
- 📋 Liệt kê sản phẩm
- 📄 Tạo FAQ

---

### 5️⃣ **table_example.html** - Bảng Dữ Liệu

**Nội dung học:**

- Cấu trúc bảng: `<table>`, `<tr>`, `<th>`, `<td>`
- Phân vùng: `<thead>`, `<tbody>`, `<tfoot>`
- Caption: `<caption>`
- Scope: `row`, `col`
- Gộp ô: `colspan`, `rowspan`
- Colgroup: `<colgroup>`, `<col>`

**3 Ví dụ thực tế:**

1. Bảng điểm học sinh
2. Bảng món ăn truyền thống Tết
3. Bảng lãi suất ngân hàng

**Kỹ năng đạt được:**

- 📊 Trình bày dữ liệu chuyên nghiệp
- 🎨 Tạo kiểu cho bảng với CSS
- ♿ Accessibility với `scope`

---

### 6️⃣ **div_example.html** - Bố Cục Với Div

**Nội dung học:**

- Sử dụng `<div>` để nhóm các phần tử
- Phân biệt `class` và `id`
- Sử dụng `<span>` cho inline styling
- Tạo bố cục cơ bản: header, content, footer

**Best Practices:**

- 🎯 Đặt tên class có ý nghĩa
- 🏗️ Phân tích bố cục trước khi code
- ⚠️ Không lạm dụng div

---

### 7️⃣ **semantic_example.html & div_example_semantic.html** - Semantic HTML

**Nội dung học:**

- `<header>` - Phần đầu trang
- `<nav>` - Điều hướng
- `<main>` - Nội dung chính
- `<section>` - Phần nội dung riêng biệt
- `<article>` - Bài viết độc lập
- `<aside>` - Nội dung phụ
- `<footer>` - Phần chân trang

**Lợi ích Semantic HTML:**

- 🚀 Tăng SEO
- ♿ Cải thiện accessibility
- 📱 Dễ responsive
- 🧹 Code sạch và dễ bảo trì

---

## 🛠️ Công Nghệ Sử Dụng

- **HTML5** - Cấu trúc trang web
- **CSS3** - Tạo kiểu và bố cục
- **Emmet** - Tăng tốc độ viết code
- **WebP** - Tối ưu hình ảnh
- **Semantic HTML** - Cải thiện SEO

---

## 🚀 Cách Sử Dụng

### Yêu cầu:

- Trình duyệt web hiện đại (Chrome, Firefox, Edge, Safari)
- Code editor (VS Code khuyến nghị)
- Extension Live Server (tùy chọn)

### Chạy dự án:

1. **Clone hoặc tải dự án về máy**
2. **Mở file HTML bất kỳ bằng trình duyệt**

   - Cách 1: Double click vào file `.html`
   - Cách 2: Chuột phải > Open with > Browser
   - Cách 3: Sử dụng Live Server trong VS Code

3. **Học theo thứ tự đề xuất:**
   ```
   index.html
   → emmet.html
   → list_example.html
   → table_example.html
   → form.html
   → form2.html
   → div_example.html
   → semantic_example.html
   → div_example_semantic.html
   ```

---

## 📝 Ghi Chú Quan Trọng

### Tối Ưu Hóa Media:

- **Hình ảnh:** Chuyển đổi sang WebP tại [Cloudinary Image to WebP](https://cloudinary.com/tools/image-to-webp)
- **Video:** Sử dụng nhiều định dạng (mp4, webm) cho tương thích
- **Audio:** Cung cấp cả mp3 và ogg

### Best Practices:

1. ✅ Luôn sử dụng `alt` cho thẻ `<img>`
2. ✅ Thêm `meta viewport` cho responsive
3. ✅ Sử dụng Semantic HTML thay vì div
4. ✅ Validate HTML tại [W3C Validator](https://validator.w3.org/)
5. ✅ Đặt tên file và folder bằng tiếng Anh, không dấu

## 💡 Tips Cho Học Viên

1. **Thực hành mỗi ngày** - Code ít nhất 30 phút/ngày
2. **Đọc kỹ comments** - Mỗi file đều có giải thích chi tiết
3. **Thử nghiệm** - Thay đổi code và xem kết quả
4. **Sử dụng DevTools** - Inspect elements để học cách web hoạt động
5. **Tham khảo MDN** - [MDN Web Docs](https://developer.mozilla.org/) là nguồn tài liệu tốt nhất

---

## 📚 Tài Nguyên Bổ Sung

### Học HTML & CSS:

- [MDN Web Docs](https://developer.mozilla.org/)
- [W3Schools](https://www.w3schools.com/)
- [CSS-Tricks](https://css-tricks.com/)

### Công Cụ Hữu Ích:

- [Can I Use](https://caniuse.com/) - Kiểm tra tương thích trình duyệt
- [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)
- [HTML Validator](https://validator.w3.org/)

### Thực Hành:

- [Frontend Mentor](https://www.frontendmentor.io/)
- [CodePen](https://codepen.io/)
- [JSFiddle](https://jsfiddle.net/)

---

## 🤝 Đóng Góp

Nếu bạn phát hiện lỗi hoặc muốn đóng góp thêm ví dụ, vui lòng:

1. Fork dự án này
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên branch (`git push origin feature/AmazingFeature`)
5. Tạo Pull Request

---

## 📧 Liên Hệ

Nếu có câu hỏi hoặc cần hỗ trợ, vui lòng liên hệ:

- **GitHub:** [@cuong78](https://github.com/cuong78)
- **Repository:** [course-html-css-class](https://github.com/cuong78/course-html-css-class)
- **Facebook:** [Anh Cường](https://www.facebook.com/ang.cuong.77)
- **Zalo:** Quét mã QR bên dưới để kết nối

<div align="center">
  <img src="https://i.imgur.com/your-qr-image.png" alt="Zalo QR Code" width="300"/>
  <p><i>Quét mã QR để kết bạn Zalo</i></p>
</div>

---

## 📜 License

Dự án này được tạo ra cho mục đích giáo dục. Bạn có thể tự do sử dụng và chia sẻ với điều kiện ghi nguồn.

---

## ⭐ Kết Luận

Khóa học này được thiết kế với mục tiêu giúp bạn:

- 🎯 Nắm vững nền tảng HTML & CSS
- 💼 Chuẩn bị cho các dự án thực tế
- 🚀 Tự tin bước vào thế giới Web Development

**Chúc bạn học tập thành công! 🎉**

---

<div align="center">
  
**Made with ❤️ for Vietnamese Learners**

⭐ Nếu thấy hữu ích, hãy star repository này nhé! ⭐

</div>
