# Personal Portfolio Website - Trần Lylyane

## 1. Giới thiệu dự án
Đây là website portfolio cá nhân được xây dựng bằng **HTML, CSS**, phục vụ mục đích giới thiệu bản thân, kỹ năng, dự án và thông tin liên hệ với nhà tuyển dụng.

Website có các phần chính:
- Hero: họ tên, vai trò nghề nghiệp, câu mô tả cá nhân.
- About: thông tin cá nhân, định hướng nghề nghiệp và kỹ năng chính.
- Projects: các dự án tiêu biểu, mô tả, hình ảnh minh họa và vai trò cá nhân.
- Skills/Experience: kỹ năng trình bày bằng thanh biểu đồ và thẻ thông tin.
- Contact: email, GitHub, LinkedIn và lời kêu gọi hành động.

## 2. Công nghệ sử dụng
- HTML5
- CSS3
- GitHub Codespaces
- GitHub Pages hoặc Vercel để triển khai

## 3. Công cụ AI đã sử dụng
Trong quá trình thực hiện, em sử dụng tối thiểu 02 công cụ AI:

### 3.1. ChatGPT
Mục đích sử dụng:
- Gợi ý bố cục website portfolio.
- Viết nội dung giới thiệu cá nhân, dự án và kỹ năng.
- Hỗ trợ tạo mã HTML/CSS.
- Gợi ý README và quy trình triển khai.

Ví dụ prompt:
```text
Bạn là một chuyên gia UI/UX kiêm lập trình viên Front-end cao cấp. Hãy giúp tôi lên kế hoạch và viết mã nguồn cho một website portfolio cá nhân lưu trữ trên GitHub, dành cho một sinh viên ngành Thiết kế đồ họa và Marketing.

Cấu trúc nội dung bắt buộc:

Hero Section: Hiển thị họ tên, vai trò (Graphic Designer & Marketer), và một câu slogan đậm chất cá nhân (ví dụ: "Blending aesthetics with strategy").

About Me: Giới thiệu bản thân, định hướng sự nghiệp sáng tạo và các kỹ năng cốt lõi.

Projects Gallery: Trình bày các dự án (ví dụ: branding cho tiệm bánh, UI/UX app học tập). Mỗi dự án gồm: Tên, mô tả ngắn, vai trò (Leader/Designer), và vị trí đặt hình ảnh minh họa.

Visual Skills: Trình bày kỹ năng (Figma, Photoshop, Branding) dưới dạng các thẻ thông tin (cards) hoặc sơ đồ trực quan, không dùng bảng biểu.

Contact: Thông tin liên hệ kèm nút kêu gọi hành động (Call to Action) như "Let's collaborate!".

Yêu cầu thiết kế & Kỹ thuật:

Phong cách: Hiện đại, tối giản nhưng có điểm nhấn. Sử dụng hệ màu sắc có sự tương phản tốt (ví dụ: Dark mode với các mảng màu pastel hoặc phong cách Neo-brutalism).

Typography: Sử dụng phông chữ không chân (Sans-serif) để tạo cảm giác chuyên nghiệp, dễ đọc.

Tính tương tác: Code phải có hiệu ứng hover cho các thẻ dự án và hiệu ứng chuyển động mượt mà (smooth scroll) hoặc hiệu ứng xuất hiện (fade-in) khi cuộn trang.

Responsive: Giao diện phải hiển thị hoàn hảo trên cả máy tính và điện thoại.

Định dạng đầu ra: Cung cấp mã HTML và CSS (hoặc Tailwind CSS) để tôi có thể triển khai ngay trên GitHub Pages.

Header Section:

Thiết kế một thanh điều hướng (Navigation Bar) cố định ở phía trên cùng (sticky) khi cuộn trang.

Bên trái là Logo (có thể là tên viết tắt cách điệu).

Bên phải là menu điều hướng gồm các mục: Giới thiệu, Dự án, Kỹ năng, Liên hệ.

Thêm một nút chuyển đổi Giao diện Sáng/Tối (Dark/Light Mode) ngay trên Header để tạo yếu tố tương tác.
```



## 3. Quá trình chỉnh sửa kết quả AI
Sau khi nhận kết quả từ AI, em không sử dụng trực tiếp mà đã chỉnh sửa theo các bước sau:

1. Chọn lại bố cục phù hợp với yêu cầu bài thi, gồm đủ Hero, About, Projects, Skills và Contact.
2. Điều chỉnh nội dung để thể hiện rõ định hướng cá nhân là Web Developer / UI Designer.
3. Chỉnh màu sắc sang phong cách riêng: xanh teal, xanh navy và vàng nhấn.
4. Viết lại CSS để website có giao diện responsive trên desktop, tablet và điện thoại.
5. Thêm JavaScript cho các yếu tố tương tác: dark mode, menu mobile và hiệu ứng xuất hiện khi cuộn trang.
6. Tối ưu README để trình bày rõ công cụ AI, prompt, quy trình chỉnh sửa và ý tưởng thiết kế.

## 4. Ý tưởng thiết kế tổng thể
Ý tưởng chính của website là xây dựng một portfolio cá nhân chuyên nghiệp, dễ đọc và thân thiện với nhà tuyển dụng. Màu xanh teal thể hiện sự sáng tạo và công nghệ, màu navy tạo cảm giác chuyên nghiệp, còn màu vàng dùng để nhấn mạnh các chi tiết quan trọng.

Phong cách thiết kế hướng đến sự tối giản, hiện đại, có khoảng trắng hợp lý và bố cục rõ ràng. Các phần nội dung được sắp xếp theo hành trình mà nhà tuyển dụng thường quan tâm: giới thiệu nhanh, thông tin cá nhân, dự án, kỹ năng và cuối cùng là liên hệ.

## 5. Tính năng nổi bật
- Giao diện responsive cho nhiều kích thước màn hình.
- Chế độ sáng/tối bằng JavaScript.
- Hiệu ứng hover cho nút và project card.
- Hiệu ứng reveal khi cuộn trang.
- Bố cục rõ ràng, dễ tiếp cận thông tin.

## 6. Hướng dẫn chạy dự án
Cách 1: Mở trực tiếp file `index.html` bằng trình duyệt.

Cách 2: Chạy bằng VS Code Live Server hoặc GitHub Codespaces.

## 7. Hướng dẫn triển khai GitHub Pages
1. Tạo repository mới trên GitHub.
2. Upload toàn bộ file dự án lên repository.
3. Vào **Settings** > **Pages**.
4. Chọn branch `main` và thư mục `/root`.
5. Lưu lại và chờ GitHub tạo link website.

## 8. Thông tin cần thay trước khi nộp
- Thay tên, mã sinh viên nếu cần.
- Thay link GitHub repository thật.
- Thay link website đã triển khai.
- Thay link LinkedIn thật nếu có.
- Nén file theo quy tắc: `<Mã sinh viên>_<Họ và tên>.zip`.

