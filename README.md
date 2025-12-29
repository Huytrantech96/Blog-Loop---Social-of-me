Đây là nội dung file README.md được thiết kế chuyên nghiệp, đầy đủ thông tin và trình bày đẹp mắt để bạn có thể đưa lên GitHub. Nó bao gồm cả giới thiệu dự án, tính năng và hướng dẫn cài đặt.

🚀 Loop App - TFT Video & Image Sharing Social Network
Loop App là một nền tảng mạng xã hội thu nhỏ dành cho cộng đồng chơi TFT (Đấu Trường Chân Lý). Ứng dụng cho phép người dùng chia sẻ hình ảnh, video highlight từ Youtube và đặc biệt là tích hợp hệ thống Crawl tự động dữ liệu từ các cao thủ TFT thế giới.

✨ Tính năng nổi bật
📱 Đối với người dùng
Giao diện Mobile-First: Thiết kế tối ưu cho điện thoại với trải nghiệm vuốt chạm mượt mà.

Chia sẻ đa phương tiện: Hỗ trợ đăng ảnh trực tiếp (từ file hoặc clipboard) và nhúng video Youtube.

Khám phá: Hệ thống lưới (Grid) hiển thị bài viết thông minh và đẹp mắt.

Trình xem video: Xem trực tiếp video Youtube ngay trong ứng dụng mà không cần chuyển trang.

Hồ sơ thành viên: Theo dõi bài viết của từng thành viên trong cộng đồng.

PWA Ready: Có khả năng cài đặt như một ứng dụng trên màn hình điện thoại.

🤖 Hệ thống tự động (Bot)
Auto-Crawl: Tự động quét và lấy video mới nhất từ các kênh Youtube của cao thủ (như Mortdog, Bebe871...).

Chống trùng lặp: Thuật toán kiểm tra ID thông minh đảm bảo không bao giờ đăng trùng bài viết.

Quản trị viên (Admin): Trang quản lý bài viết riêng biệt giúp kiểm soát nội dung và xóa bài dễ dàng.

🛠 Công nghệ sử dụng
Backend: PHP (Không cần database SQL - sử dụng JSON để lưu trữ linh hoạt).

Frontend: HTML5, CSS3 (Modern Flexbox & Grid), JavaScript (ES6+).

API: YouTube Data API v3.

Lưu trữ: JSON (Dễ dàng di chuyển và sao lưu).

🚀 Hướng dẫn cài đặt
1. Yêu cầu hệ thống
Máy chủ hỗ trợ PHP 7.4 trở lên.

Quyền ghi file (Write Permission) cho thư mục chứa các file .json.

2. Cấu trúc thư mục
Plaintext

📂 Loop-App
 ├── index.php         # Trang chủ & Giao diện người dùng
 ├── admin.php         # Trang quản trị bài viết
 ├── auto_crawl.php    # Script chạy tự động lấy video
 ├── posts.json        # Nơi lưu trữ bài viết (Tự động tạo)
 ├── users.json        # Nơi lưu trữ thành viên (Tự động tạo)
 └── manifest.json     # Cấu hình PWA (Ứng dụng mobile)
3. Cấu hình Bot tự động
Để bot hoạt động, hãy mở file auto_crawl.php và điền thông tin:

PHP

$apiKey = 'AIzaSy...';         // API Key từ Google Cloud
$channelId = 'UC...';          // ID kênh Youtube muốn theo dõi
🔒 Bảo mật & Tối ưu
Chống Zoom & Bôi đen: Giao diện được khóa để tạo cảm giác giống ứng dụng di động thật.

Bảo vệ Admin: Trang quản trị yêu cầu mật khẩu để truy cập.

Xử lý hình ảnh: Hỗ trợ dán ảnh (Paste) trực tiếp từ bộ nhớ tạm.

📝 Giấy phép
Dự án được phát hành dưới giấy phép MIT License. Bạn có thể tự do sử dụng và phát triển thêm.

🤝 Liên hệ
Nếu bạn có bất kỳ câu hỏi nào hoặc muốn đóng góp cho dự án, hãy mở một Issue hoặc thực hiện Pull Request.

Phát triển bởi Huyhut
