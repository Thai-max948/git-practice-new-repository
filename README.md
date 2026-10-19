# Git Practice: README Repository

Dự án nhỏ để thực hành tạo một kho Git cục bộ, liên kết với GitHub và đồng bộ lịch sử mã nguồn.

## Các lệnh Git đã sử dụng

- `git init --initial-branch=main`: khởi tạo Git repository cục bộ và tạo nhánh chính `main`.
- `git status`: kiểm tra nhánh hiện tại, thay đổi trong thư mục làm việc và trạng thái staging.
- `git add README.md`: đưa README vào staging để chuẩn bị commit.
- `git commit -m "Add README.md file"`: lưu một phiên bản có mô tả vào lịch sử repository.
- `git remote add origin <URL>`: đặt tên `origin` cho địa chỉ repository GitHub để Git biết nơi đồng bộ.
- `git push -u origin main`: đẩy commit của nhánh `main` lên GitHub và thiết lập nhánh theo dõi mặc định.
- `git clone <URL>`: tạo một bản sao cục bộ từ repository từ xa.
- `git pull`: tải các commit mới và tích hợp chúng vào nhánh hiện tại.
- `git log --oneline`: xem lịch sử commit ở dạng ngắn gọn.

## Quy trình

1. Tạo repository trên GitHub.
2. Khởi tạo repository cục bộ và thêm `origin` trỏ tới GitHub.
3. Tạo hoặc cập nhật README, dùng `git add` để staging.
4. Dùng `git commit` để ghi lại phiên bản.
5. Dùng `git push` để đồng bộ lên GitHub.

Repository được dùng làm bài thực hành quản lý mã nguồn với Git.
