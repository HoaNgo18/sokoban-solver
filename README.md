# Sokoban Solver

Trò chơi Sokoban cổ điển được viết bằng Python, tích hợp thuật toán AI (BFS và A*) để tự động giải quyết các màn chơi.

## Yêu cầu hệ thống
- Python 3.x
- Thư viện Pygame

## Cài đặt

1. Đảm bảo bạn đã cài đặt Python.
2. Cài đặt thư viện Pygame bằng lệnh sau:

```bash
pip install pygame
```

## Cách chạy game

Mở terminal tại thư mục chứa dự án và chạy lệnh:

```bash
python sokoban.py
```

Sau khi game khởi động, nhập số thứ tự màn chơi (Level) từ **1 đến 50** vào hộp thoại và nhấn Enter.

## Tính năng nổi bật

* **Tự chơi (Auto-solve):** Hỗ trợ tìm đường đi ngắn nhất bằng thuật toán BFS hoặc tối ưu hóa bằng A*.
* **Phát hiện bế tắc (Deadlock Detection):** Game tự động nhận biết khi hộp bị kẹt vào góc và dừng tìm kiếm để tiết kiệm thời gian.
* **Hoàn tác (Undo):** Cho phép quay lại trạng thái trước nếu đi sai.
* **Bản đồ tùy chỉnh:** Dữ liệu các màn chơi được lưu trong file `levels`, bạn có thể thêm màn chơi mới theo định dạng chuẩn.
