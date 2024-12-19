# Handwritten Digit Recognition

## Mô Tả
Ứng dụng nhận dạng chữ số viết tay sử dụng phương pháp K-Nearest Neighbors (kNN). Người dùng có thể vẽ chữ số trên một bảng vẽ, và ứng dụng sẽ dự đoán chữ số đó. Chương trình sử dụng dữ liệu huấn luyện từ hình ảnh các chữ số viết tay và áp dụng mô hình kNN để dự đoán.

## Các Thành Phần Chính:
1. **Tkinter**: Thư viện giao diện người dùng cho phép người dùng vẽ chữ số viết tay.
2. **OpenCV**: Được sử dụng để xử lý và chuyển đổi hình ảnh.
3. **PIL (Python Imaging Library)**: Dùng để xử lý hình ảnh vẽ.
4. **Scikit-learn**: Dùng cho mô hình K-Nearest Neighbors (kNN) để nhận dạng chữ số.
5. **Matplotlib**: Được sử dụng để hiển thị các hình ảnh hoặc đồ thị nếu cần.

## Cài Đặt
1. Cài đặt các thư viện yêu cầu:
   ```bash
   pip install numpy opencv-python pillow scikit-learn matplotlib
Cài đặt Tkinter (nếu chưa có sẵn trên hệ thống):
Trên Ubuntu/Debian:
bash
Sao chép mã
sudo apt-get install python3-tk
Trên Windows, Tkinter đã được cài sẵn với Python.
Sử Dụng
Chạy ứng dụng:
Sau khi cài đặt tất cả các thư viện cần thiết, bạn chỉ cần chạy script Python chính:

bash
Sao chép mã
python app.py
Vẽ chữ số:

Sử dụng chuột để vẽ chữ số trên khung vẽ.
Dự đoán:

Sau khi vẽ, nhấn vào nút "Check" để hệ thống dự đoán chữ số bạn đã vẽ.
Kết quả sẽ được hiển thị ngay trên giao diện.
Cấu hình giá trị k:

Bạn có thể thay đổi giá trị "k" của mô hình kNN bằng cách nhập vào ô đầu vào và nhấn nút "Set".
Xóa khung vẽ:

Nhấn nút "Clear" để xóa khung vẽ và bắt đầu lại.
Các Tính Năng
Nhận dạng chữ số viết tay sử dụng mô hình K-Nearest Neighbors.
Cung cấp khả năng thay đổi giá trị "k" để tối ưu hóa độ chính xác của mô hình.
Giao diện người dùng đơn giản với Tkinter cho phép vẽ và nhận dạng trực tiếp.
