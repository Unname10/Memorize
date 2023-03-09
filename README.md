# Memorize

## Ý tưởng về một ứng dụng bao gồm:

1. Tính năng:
    - Thêm, sửa, xóa, lưu thẻ, nhóm thẻ, đánh dấu yêu thích
    - Có các phần để ghi nhớ thẻ
        - Lật thể để học
        - Phát âm (nếu học từ vựng tiếng Anh)
        - Hiển thị danh sách các từ không bao gồm định nghĩa và ngược lại
        - Có thể lưu hình ảnh vảo từ
    - Có phần ôn tập
        - Viết các từ vựng dựa vào định nghĩa và ngược lại
        - Nối các thẻ giữa hai danh sách
        - Chọn định nghĩa hoặc từ đúng
        - Ôn tập bằng âm thanh (tùy chọn)
        - Làm kiểm tra trắc nghiệm
    - Thêm flashcard bằng hình ảnh
    - Khôi phục các flashcard đã bị xóa
2. Công cụ
    - Nhắc nhở ôn tập
    - Nhắc các từ (ưu tiên từ được đánh dấu yêu thích)
    - Nhắc nhở học theo thời gian - nội dung
3. Công nghệ
    - Firebase:
        - Tạo người dùng
        - Lưu trữ (Database)
    - React để build giao diện người dùng
    - Sử dụng một số api, library để tăng tính tiện lợi, đẹp mắt cho trang web, ứng dụng:
        - API của Google dịch (https://github.com/matheuss/google-translate-api)
        - Bootstrap (https://getbootstrap.com/)
        - ...
4. Có cả phiên bản Web và Mobile

## Trình tự thực hiện:

1. Lên ý tưởng, chuẩn bị các bản thiết kế cho phiên bản Web và Mobile của ứng dụng
2. Code giao diện phiên bản Web
    - Cài đặt Framework và các Lib cần thiết
    - Tiến hành code theo trình tự từng trang, từng Component một, có chuyển đổi giao diện sáng tối
        - Trang chủ (/)
        - Thư viện của bạn (/learn)
        - Cài đặt (/settings)
        - Thống kê (/statistic)
3. Code giao diện phiên bản Mobile
4. Test code và sửa lỗi
5. Sử dụng
