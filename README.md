
# NodeFlow

NodeFlow là một công cụ quản lý workflow, cho phép người dùng tạo, chỉnh sửa và kết nối các node để tự động hóa các quy trình công việc. Dự án hỗ trợ giao diện kéo thả và sử dụng PySide6 để xây dựng giao diện người dùng.

## Cài đặt

### Yêu cầu

- Python 3.6 hoặc phiên bản cao hơn
- PySide6

### Cài đặt

1. Clone dự án về máy:
   ```
   git clone https://github.com/truongpv2606/NodeFlow.git
   cd NodeFlow
   ```

2. Tạo môi trường ảo (tuỳ chọn nhưng khuyến nghị):
   ```
   python -m venv .venv
   source .venv/bin/activate  # Trên Windows, use `.venv\Scripts\activate`
   ```

3. Cài đặt các thư viện cần thiết:
   ```
   pip install -r requirements.txt
   ```

## Cách sử dụng

1. Chạy ứng dụng:
   ```
   python nodeflow.py
   ```

2. Sử dụng giao diện kéo thả để tạo và kết nối các node. Các node có thể đại diện cho các bước trong quy trình làm việc của bạn.

## Các tính năng chính

- **Tạo và quản lý workflow**: Dễ dàng tạo và chỉnh sửa các quy trình tự động hóa.
- **Kéo thả các node**: Giao diện kéo thả giúp người dùng dễ dàng kết nối các node và điều chỉnh quy trình.
- **Tùy chỉnh các node**: Hỗ trợ nhiều loại node với các chức năng khác nhau để phù hợp với các nhu cầu tự động hóa.

## Giới hạn

- Dự án đang trong giai đoạn phát triển và có thể có một số lỗi nhỏ.
- Cần có PySide6 và các thư viện phụ thuộc khác để chạy dự án.

## Đóng góp

Chúng tôi hoan nghênh mọi đóng góp! Bạn có thể gửi Pull Request hoặc tạo issue nếu gặp bất kỳ lỗi nào.

## Giấy phép

Dự án này được cấp phép theo Giấy phép MIT - xem [LICENSE](LICENSE) để biết chi tiết.
