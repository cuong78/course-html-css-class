# 📚 Khóa Học HTML & CSS - Từ Cơ Bản Đến Nâng Cao

![HTML & CSS](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-blue?style=for-the-badge)

> Khóa học toàn diện về HTML & CSS, được thiết kế đặc biệt cho người mới bắt đầu với các ví dụ thực tế, giao diện trực quan và dễ hiểu.

---

## 🎯 Mục Tiêu Khóa Học

Khóa học này sẽ giúp bạn:

### HTML (Session 1):

- ✅ Nắm vững các thẻ HTML cơ bản và nâng cao
- ✅ Hiểu rõ cấu trúc và ngữ nghĩa của HTML5
- ✅ Làm việc với Forms, Tables, Lists một cách chuyên nghiệp
- ✅ Tối ưu hóa hình ảnh, video, audio cho web
- ✅ Sử dụng Emmet để viết code nhanh hơn 5-10 lần
- ✅ Hiểu về Semantic HTML cho SEO và Accessibility

### CSS (Session 2):

- ✅ Hiểu các cách chèn CSS vào HTML
- ✅ Làm chủ hệ thống màu sắc (Color System)
- ✅ Sử dụng thành thạo các CSS Selectors
- ✅ Nắm vững các đơn vị CSS (px, rem, em, %, vw, vh)
- ✅ Áp dụng CSS để tạo giao diện đẹp mắt và responsive

---

## 📂 Cấu Trúc Dự Án

```
html+css/
│
├── Session01_HTML/                          # 📘 HTML - Nền Tảng Web
│   ├── 01_html-basics/
│   │   └── index.html                       # Các thẻ cơ bản (h1-h6, p, a, img, video, audio)
│   │
│   ├── 02_html-list-types/
│   │   └── list_example.html                # Danh sách (ol, ul, dl)
│   │
│   ├── 03_html-tables/
│   │   └── table_example.html               # Bảng dữ liệu với ví dụ thực tế
│   │
│   ├── 04_html-forms-and-inputs/
│   │   ├── form.html                        # Form đăng nhập cơ bản
│   │   └── form2.html                       # Form đăng ký nâng cao
│   │
│   ├── 05_html-layout-with-div-span/
│   │   └── div_example.html                 # Bố cục với div và span
│   │
│   ├── 06_html-semantic-elements/
│   │   ├── semantic_example.html            # Semantic HTML nâng cao
│   │   └── div_example_semantic.html        # So sánh div vs semantic
│   │
│   ├── 07_emmet-tips-and-tricks/
│   │   └── emmet.html                       # Emmet shortcuts
│   │
│   └── assets/                              # Tài nguyên media
│       ├── babythree1.webp
│       ├── babythree2.jpeg
│       ├── video.mp4
│       ├── video.webm
│       ├── video_cover.png
│       ├── audio.mp3
│       └── audio.ogg
│
├── Session02_CSS/                           # 🎨 CSS - Tạo Kiểu Giao Diện
│   ├── 01_css-insertion-methods/
│   │   └── index.html                       # Các cách chèn CSS (inline, internal, external)
│   │
│   ├── 02_css-color-system/
│   │   └── index.html                       # Hệ thống màu sắc (HEX, RGB, HSL, Color System)
│   │
│   ├── 03_css-basic-selectors/
│   │   └── index.html                       # Bộ chọn CSS (type, class, id, descendant, AND, OR)
│   │
│   └── 04_css-units/
│       └── index.html                       # Đơn vị CSS (px, rem, em, %, vw, vh)
│
└── README.md                                # File này
```

---

## 📖 Nội Dung Chi Tiết

## 📘 SESSION 1: HTML - Nền Tảng Web

### 1️⃣ **HTML Basics** - Các Thẻ HTML Cơ Bản

**📍 File:** `Session01_HTML/01_html-basics/index.html`

**Nội dung học:**

- Thẻ tiêu đề (`<h1>` - `<h6>`) và tầm quan trọng với SEO
- Đoạn văn (`<p>`) và định dạng text
- Liên kết (`<a>`) với các thuộc tính: `href`, `target`, `title`, `download`
- Hình ảnh (`<img>`) và tối ưu hóa với định dạng WebP
- Video (`<video>`) với nhiều source và poster
- Audio (`<audio>`) với multiple formats

**Kiến thức nổi bật:**

- ⚡ Tối ưu hình ảnh bằng WebP để giảm 30-50% dung lượng
- 🎬 Sử dụng nhiều định dạng video để tương thích đa trình duyệt
- 🔗 Bảo mật liên kết với `rel="noreferrer noopener"`
- 📱 Responsive media với thuộc tính width, height

---

### 2️⃣ **HTML List Types** - Các Loại Danh Sách

**📍 File:** `Session01_HTML/02_html-list-types/list_example.html`

**Nội dung học:**

- Ordered List (`<ol>`) với types: `1`, `a`, `A`, `I`, `i`
- Unordered List (`<ul>`) với types: `circle`, `disc`, `square`
- Description List (`<dl>`, `<dt>`, `<dd>`)
- Danh sách lồng nhau (nested lists)

**Ứng dụng thực tế:**

- 📝 Tạo menu điều hướng
- 📋 Liệt kê sản phẩm, features
- 📄 Tạo FAQ và glossary
- 🗂️ Table of contents

---

### 3️⃣ **HTML Tables** - Bảng Dữ Liệu

**📍 File:** `Session01_HTML/03_html-tables/table_example.html`

**Nội dung học:**

- Cấu trúc bảng: `<table>`, `<tr>`, `<th>`, `<td>`
- Phân vùng: `<thead>`, `<tbody>`, `<tfoot>`
- Caption: `<caption>`
- Scope: `row`, `col` (accessibility)
- Gộp ô: `colspan`, `rowspan`
- Colgroup: `<colgroup>`, `<col>` (styling)

**3 Ví dụ thực tế có CSS:**

1. 📊 Bảng điểm học sinh
2. 🍜 Bảng món ăn truyền thống Tết
3. 💰 Bảng lãi suất ngân hàng

**Kỹ năng đạt được:**

- 📈 Trình bày dữ liệu chuyên nghiệp
- 🎨 Tạo kiểu cho bảng với CSS
- ♿ Accessibility với `scope` và `caption`

---

### 4️⃣ **HTML Forms** - Làm Việc Với Forms

**📍 Files:**

- `Session01_HTML/04_html-forms-and-inputs/form.html` (Cơ bản)
- `Session01_HTML/04_html-forms-and-inputs/form2.html` (Nâng cao)

**form.html** - Form đăng nhập cơ bản:

- Input types: `email`, `password`
- Checkbox: `remember me`
- Button submit
- Validation cơ bản

**form2.html** - Form đăng ký phức tạp:

- Text input với `size`, `placeholder`, `required`
- Textarea với `spellcheck`
- Radio buttons cho lựa chọn đơn
- Select dropdown
- Number input với `min`, `max`, `step`
- Datalist cho tự động hoàn thành
- Buttons: `submit`, `reset`
- Fieldset và Legend

**Kiến thức quan trọng:**

- 🔐 Phân biệt `id` và `name`
- ✅ HTML5 Validation với `required`, `pattern`
- 📝 UX tốt với `placeholder` và `label`
- ⌨️ Accessibility với `for` attribute

---

### 5️⃣ **HTML Layout** - Bố Cục Với Div & Span

**📍 File:** `Session01_HTML/05_html-layout-with-div-span/div_example.html`

**Nội dung học:**

- Sử dụng `<div>` để nhóm block-level elements
- Sử dụng `<span>` để nhóm inline elements
- Phân biệt `class` và `id`
- Tạo bố cục cơ bản: header, content, footer
- CSS styling cho layout

**Best Practices:**

- 🎯 Đặt tên class có ý nghĩa (semantic)
- 🏗️ Phân tích bố cục trước khi code
- ⚠️ Không lạm dụng div (div-soup)
- 📦 Sử dụng BEM naming convention

---

### 6️⃣ **Semantic HTML** - HTML Ngữ Nghĩa

**📍 Files:**

- `Session01_HTML/06_html-semantic-elements/semantic_example.html`
- `Session01_HTML/06_html-semantic-elements/div_example_semantic.html`

**Nội dung học:**

- `<header>` - Phần đầu trang/section
- `<nav>` - Navigation menu
- `<main>` - Nội dung chính (duy nhất)
- `<section>` - Phần nội dung có chủ đề
- `<article>` - Nội dung độc lập, tái sử dụng được
- `<aside>` - Nội dung phụ, sidebar
- `<footer>` - Phần chân trang/section

**Lợi ích Semantic HTML:**

- 🚀 Tăng SEO (Search Engine Optimization)
- ♿ Cải thiện Accessibility (Screen readers)
- 📱 Dễ responsive và maintain
- 🧹 Code sạch, dễ đọc, dễ hiểu
- 👥 Team collaboration tốt hơn

---

### 7️⃣ **Emmet** - Viết Code Nhanh Hơn 10 Lần

**📍 File:** `Session01_HTML/07_emmet-tips-and-tricks/emmet.html`

**Nội dung học:**

- Tạo thẻ nhanh: gõ tên thẻ + `Tab`
- Lặp lại thẻ: `div*3`
- Tạo cấu trúc lồng nhau: `header>nav>ul>li*3`
- Thêm thuộc tính: `input[type="radio"]*3`
- Thêm class: `.content`
- Thêm id: `#header`
- Tạo phần tử anh em: `h1+h2+p`
- Text content: `p{Hello World}`
- Numbering: `li.item$*5`

**Lợi ích:**

- ⚡ Tăng tốc độ code lên 5-10 lần
- 🎯 Giảm lỗi cú pháp
- 💪 Tăng năng suất làm việc
- 🧠 Giảm tải cho não bộ

---

## 🎨 SESSION 2: CSS - Tạo Kiểu Giao Diện

### 1️⃣ **CSS Insertion Methods** - Các Cách Chèn CSS

**📍 File:** `Session02_CSS/01_css-insertion-methods/index.html`

**Nội dung học:**

- **Inline CSS**: Style trực tiếp trên element
- **Internal CSS**: Style trong thẻ `<style>`
- **External CSS**: File `.css` riêng biệt

**So sánh và khi nào dùng:**

- 🚫 Inline: Tránh dùng, khó maintain
- ⚠️ Internal: Chỉ dùng cho single page
- ✅ External: Best practice, dễ maintain, cache được

---

### 2️⃣ **CSS Color System** - Hệ Thống Màu Sắc

**📍 File:** `Session02_CSS/02_css-color-system/index.html`

**Nội dung học:**

- **Tên màu** (Color Names): 140 màu cơ bản
- **HEX**: `#RRGGBB` - Phổ biến nhất
- **RGB**: `rgb(r, g, b)` - Dễ hiểu
- **RGBA**: `rgba(r, g, b, a)` - Có độ trong suốt
- **HSL**: `hsl(h, s, l)` - Trực quan nhất

**Color System - 5 Nhóm Màu:**

1. **Neutral Colors** (60-70%): Màu nền, văn bản
2. **Primary Colors** (20-30%): Màu chủ đạo brand
3. **Secondary Colors**: Màu phụ bổ trợ
4. **Accent Colors**: Màu nhấn, CTA
5. **Utility Colors**: Success, Warning, Error, Info

**Tính năng đặc biệt:**

- 🎨 Demo trực quan tất cả color formats
- 🔄 So sánh HEX vs RGB vs HSL
- 📊 Color palette với 5 nhóm màu
- 🔗 Links tới color tools (Coolors, Adobe Color, UI Colors)

---

### 3️⃣ **CSS Basic Selectors** - Bộ Chọn CSS Cơ Bản

**📍 File:** `Session02_CSS/03_css-basic-selectors/index.html`

**6 Loại Selector Quan Trọng:**

1. **Type Selector**: `p { }` - Chọn tất cả thẻ `<p>`
2. **Class Selector**: `.classname { }` - Chọn theo class
3. **ID Selector**: `#idname { }` - Chọn theo ID (duy nhất)
4. **Descendant Selector**: `.parent .child { }` - Chọn con cháu
5. **AND Selector**: `.button.primary { }` - Phải có CẢ 2 class
6. **Group Selector**: `h1, h2, h3 { }` - Nhóm nhiều selector

**Tính năng đặc biệt:**

- ✅ Demo trực quan "Được chọn" vs "Không được chọn"
- 📊 Bảng so sánh tất cả selectors
- ⚠️ Phân biệt rõ `.a.b` vs `.a .b`
- 🎯 Best practices và common mistakes

---

### 4️⃣ **CSS Units** - Đơn Vị CSS

**📍 File:** `Session02_CSS/04_css-units/index.html`

**6 Đơn Vị Quan Trọng:**

**Tuyệt Đối:**

1. **px (Pixel)**: Cố định, không đổi

**Tương Đối:** 2. **rem**: Dựa trên `font-size` của `<html>` (1rem = 16px mặc định) 3. **em**: Dựa trên `font-size` của thẻ cha 4. **%**: Dựa trên kích thước thẻ cha 5. **vw**: 1vw = 1% chiều rộng viewport 6. **vh**: 1vh = 1% chiều cao viewport

**Tính năng đặc biệt:**

- 📏 Visual bars cho từng đơn vị
- 🔄 Demo responsive với vw/vh (resize browser để thấy)
- 📊 Bảng so sánh đầy đủ
- 💡 Best practices: Nên dùng / Tránh dùng
- 🧮 Công thức chuyển đổi (px ↔ rem)
- 🎮 Hướng dẫn thử nghiệm với DevTools

---

## 🛠️ Công Nghệ & Tools Sử Dụng

### Core:

- **HTML5** - Cấu trúc trang web semantic
- **CSS3** - Styling hiện đại với Flexbox, Grid
- **Emmet** - Fast coding với abbreviations

### Optimization:

- **WebP** - Định dạng ảnh tối ưu (giảm 30-50% dung lượng)
- **Multiple Video Formats** - MP4 + WebM cho compatibility

### Design Resources:

- **Color Tools**: Coolors.co, Adobe Color, UI Colors
- **Typography**: Google Fonts
- **Icons**: Font Awesome, Heroicons

---

## 🚀 Cách Sử Dụng

### Yêu cầu:

- ✅ Trình duyệt web hiện đại (Chrome, Firefox, Edge, Safari)
- ✅ Code editor: **VS Code** (khuyến nghị)
- ✅ Extensions (optional):
  - Live Server
  - Auto Rename Tag
  - Emmet (built-in)
  - Prettier

### Chạy dự án:

**Cách 1: Trực tiếp**

```bash
# Double click vào bất kỳ file .html nào
```

**Cách 2: Live Server (Khuyến nghị)**

```bash
# 1. Cài đặt Live Server extension trong VS Code
# 2. Right-click vào file HTML → "Open with Live Server"
# 3. Browser tự động mở và reload khi save
```

**Cách 3: Command Line**

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (install: npm install -g http-server)
http-server

# Sau đó mở: http://localhost:8000
```

### Lộ trình học đề xuất:

#### 📘 Week 1-2: HTML Foundations

```
Session01_HTML/
  ├── 01_html-basics/           → Ngày 1-2
  ├── 02_html-list-types/       → Ngày 3
  ├── 03_html-tables/           → Ngày 4-5
  ├── 04_html-forms-and-inputs/ → Ngày 6-8
  ├── 05_html-layout-with-div-span/ → Ngày 9
  ├── 06_html-semantic-elements/    → Ngày 10-11
  └── 07_emmet-tips-and-tricks/     → Ngày 12
```

#### 🎨 Week 3: CSS Fundamentals

```
Session02_CSS/
  ├── 01_css-insertion-methods/ → Ngày 13
  ├── 02_css-color-system/      → Ngày 14-15
  ├── 03_css-basic-selectors/   → Ngày 16-17
  └── 04_css-units/             → Ngày 18-19
```

#### 🚀 Week 4: Practice & Projects

```
  → Ngày 20-21: Review tất cả concepts
  → Ngày 22-28: Build mini projects
```

---

## 📝 Ghi Chú Quan Trọng

### Tối Ưu Hóa Media:

**Hình ảnh:**

- ✅ Sử dụng WebP thay vì JPG/PNG (giảm 30-50% dung lượng)
- ✅ Tool: [Cloudinary Image to WebP](https://cloudinary.com/tools/image-to-webp)
- ✅ Luôn có fallback cho trình duyệt cũ
- ✅ Sử dụng `srcset` cho responsive images

**Video:**

- ✅ Multiple formats: MP4 (widely supported) + WebM (smaller size)
- ✅ Thêm `poster` attribute cho thumbnail
- ✅ Sử dụng `preload="metadata"` để tối ưu loading

**Audio:**

- ✅ Multiple formats: MP3 + OGG
- ✅ Compress với bitrate phù hợp (128kbps cho speech)

### Best Practices:

**HTML:**

1. ✅ Luôn có `<!DOCTYPE html>`
2. ✅ Set `lang` attribute: `<html lang="vi">`
3. ✅ Luôn có `<meta charset="UTF-8">`
4. ✅ Responsive meta tag: `<meta name="viewport">`
5. ✅ Semantic HTML > div soup
6. ✅ Alt text cho tất cả images
7. ✅ Validate HTML: [W3C Validator](https://validator.w3.org/)

**CSS:**

1. ✅ External CSS > Internal > Inline
2. ✅ Sử dụng `rem` cho font-size và spacing
3. ✅ Mobile-first approach
4. ✅ Avoid `!important` (chỉ dùng khi thật sự cần)
5. ✅ Naming convention: BEM hoặc đồng nhất
6. ✅ Group related properties
7. ✅ Comment cho complex code

**Naming:**

- ✅ Files: `kebab-case.html` (chữ thường, dấu gạch ngang)
- ✅ Classes: `.kebab-case` hoặc `.camelCase`
- ✅ IDs: `#camelCase` hoặc `#kebab-case`
- ✅ Tránh tiếng Việt có dấu
- ✅ Tên có ý nghĩa, mô tả đúng chức năng

---

## 💡 Tips Cho Học Viên

### Học Tập Hiệu Quả:

1. 📅 **Thực hành mỗi ngày** - Code ít nhất 1 giờ/ngày
2. 📖 **Đọc kỹ comments** - Mỗi file có giải thích chi tiết
3. 🔬 **Thử nghiệm** - Thay đổi code và xem kết quả
4. 🔍 **DevTools là bạn** - F12 để inspect và debug
5. 📝 **Ghi chú** - Viết lại những gì học được
6. 🤝 **Hỏi đáp** - Đừng ngại hỏi khi không hiểu
7. 💪 **Luyện tập** - Làm lại các bài tập nhiều lần

### Công Cụ Hỗ Trợ:

- 🔧 **Chrome DevTools** - Inspect, debug, test responsive
- 🎨 **Color Picker** - Trong VS Code hoặc browser
- 📏 **Rulers & Guides** - Extensions trong VS Code
- 🖼️ **Lorem Picsum** - Placeholder images
- 📝 **Lorem Ipsum** - Placeholder text

### Kỹ Năng Cần Rèn:

1. 👀 **Quan sát** - Phân tích các website thực tế
2. 🎯 **Problem-solving** - Debug và fix errors
3. 📱 **Responsive thinking** - Nghĩ về mobile-first
4. ♿ **Accessibility** - Luôn nghĩ đến người dùng khuyết tật
5. 🚀 **Performance** - Optimize từ đầu

---

## 📚 Tài Nguyên Bổ Sung

### Học HTML & CSS:

- 📖 [MDN Web Docs](https://developer.mozilla.org/) - Tài liệu chính thức, đầy đủ nhất
- 🎓 [W3Schools](https://www.w3schools.com/) - Tutorial và examples
- 🎨 [CSS-Tricks](https://css-tricks.com/) - Tips và tricks nâng cao
- 📺 [Kevin Powell](https://www.youtube.com/@KevinPowell) - CSS YouTube channel
- 📺 [Traversy Media](https://www.youtube.com/@TraversyMedia) - Web dev tutorials

### Công Cụ Hữu Ích:

**Development:**

- 🔍 [Can I Use](https://caniuse.com/) - Kiểm tra browser compatibility
- ✅ [HTML Validator](https://validator.w3.org/) - Validate HTML
- ✅ [CSS Validator](https://jigsaw.w3.org/css-validator/) - Validate CSS
- 📝 [Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/) - Emmet shortcuts

**Design & Colors:**

- 🎨 [Coolors](https://coolors.co/) - Color palette generator
- 🎨 [Adobe Color](https://color.adobe.com/) - Color wheel
- 🎨 [UI Colors](https://uicolors.app/generate) - Tailwind color generator
- 🌈 [HTML Color Codes](https://htmlcolorcodes.com/) - Color picker

**Images & Media:**

- 🖼️ [Unsplash](https://unsplash.com/) - Free high-quality images
- 🖼️ [Pexels](https://www.pexels.com/) - Free stock photos & videos
- 🎬 [Cloudinary](https://cloudinary.com/) - Image/video optimization
- 📐 [Squoosh](https://squoosh.app/) - Image compression

### Thực Hành:

- 💪 [Frontend Mentor](https://www.frontendmentor.io/) - Real-world challenges
- ✏️ [CodePen](https://codepen.io/) - Online code editor
- 🎮 [CSS Diner](https://flukeout.github.io/) - CSS selector game
- 🐸 [Flexbox Froggy](https://flexboxfroggy.com/) - Learn Flexbox
- 🌱 [Grid Garden](https://cssgridgarden.com/) - Learn CSS Grid

### Community:

- 💬 [Stack Overflow](https://stackoverflow.com/) - Q&A
- 💬 [Dev.to](https://dev.to/) - Developer community
- 💬 [Reddit r/webdev](https://www.reddit.com/r/webdev/) - Web dev discussions

---

## 🤝 Đóng Góp

Nếu bạn phát hiện lỗi hoặc muốn đóng góp thêm ví dụ:

1. 🍴 Fork repository này
2. 🌿 Tạo branch mới:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. 💾 Commit changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. 📤 Push lên branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. 🎯 Tạo Pull Request

### Đóng Góp Được Chào Đón:

- ✨ Thêm examples mới
- 🐛 Fix bugs
- 📝 Cải thiện documentation
- 🌍 Dịch sang tiếng Anh
- 🎨 Cải thiện UI/UX của demos
- 💡 Thêm tips & tricks

---

## 📧 Liên Hệ

Nếu có câu hỏi hoặc cần hỗ trợ, vui lòng liên hệ:

- 🐙 **GitHub:** [@cuong78](https://github.com/cuong78)
- 📁 **Repository:** [course-html-css-class](https://github.com/cuong78/course-html-css-class)
- 👤 **Facebook:** [Anh Cường](https://www.facebook.com/ang.cuong.77)
- 💬 **Zalo:** Quét mã QR bên dưới để kết nối

<div align="center">
  <img src="./Session01_HTML/assets/zalo.jpg" alt="Zalo QR Code" width="300"/>
  <p><i>Quét mã QR để kết bạn Zalo và nhận hỗ trợ</i></p>
</div>

---

## 📜 License

Dự án này được tạo ra cho **mục đích giáo dục**.

- ✅ Bạn có thể tự do sử dụng cho mục đích học tập
- ✅ Có thể chia sẻ với bạn bè, đồng nghiệp
- ✅ Có thể fork và customize cho nhu cầu riêng
- ⚠️ Vui lòng ghi nguồn khi chia sẻ

---

## ⭐ Kết Luận

Khóa học này được thiết kế với mục tiêu giúp bạn:

- 🎯 **Nắm vững nền tảng** HTML & CSS từ cơ bản đến nâng cao
- 💼 **Chuẩn bị sẵn sàng** cho các dự án web thực tế
- 🚀 **Tự tin bước vào** thế giới Web Development
- 🎓 **Có portfolio** để apply công việc frontend developer
- 🌟 **Tư duy responsive** và accessibility từ đầu

### 📈 Lộ Trình Tiếp Theo:

Sau khi hoàn thành khóa này, bạn có thể tiếp tục:

1. **CSS Advanced**: Flexbox, Grid, Animations, Transitions
2. **Responsive Design**: Media Queries, Mobile-first approach
3. **CSS Frameworks**: Bootstrap, Tailwind CSS
4. **Preprocessors**: Sass, Less
5. **JavaScript**: DOM Manipulation, Events, ES6+
6. **Version Control**: Git & GitHub
7. **Build Tools**: npm, Webpack, Vite
8. **Frameworks**: React, Vue, Angular

---

## 🎉 Cảm Ơn & Chúc Mừng!

Cảm ơn bạn đã chọn khóa học này!

💪 Hãy nhớ rằng: **"The best way to learn is by doing"**

🚀 Bắt đầu coding ngay hôm nay và đừng ngại mắc lỗi!

---

<div align="center">

### Made with ❤️ for Vietnamese Learners

**⭐ Nếu thấy hữu ích, hãy star repository này! ⭐**

[![GitHub stars](https://img.shields.io/github/stars/cuong78/course-html-css-class?style=social)](https://github.com/cuong78/course-html-css-class)

**Happy Coding! 👨‍💻👩‍💻**

</div>

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
- **Facebook:** [Anh Cương](https://www.facebook.com/ang.cuong.77)
- **Zalo:** Quét mã QR bên dưới để kết nối

<div align="center">
  <img src="./assets/zalo.jpg" alt="Zalo QR Code" width="300"/>
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
