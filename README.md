# Depth Information Reconstruction Project

## Mô tả

Dự án này sử dụng các cặp ảnh stereo (trái/phải) để tái tạo bản đồ độ sâu (depth map) của cảnh vật. Bằng cách áp dụng các kỹ thuật thị giác máy tính (Computer Vision), chương trình cho phép bạn xác định thông tin hình học 3D từ ảnh 2D.

## Tính năng

* Đọc và xử lý các cặp ảnh stereo (ví dụ: `Aloe_left_1.png`, `Aloe_right_1.png`)
* Căn chỉnh và tính toán disparity map từ ảnh trái và phải
* Tái tạo bản đồ độ sâu từ disparity
* Hiển thị trực quan thông tin độ sâu qua Jupyter Notebook (`DepthInformationReconstruction.ipynb`)

## Công nghệ sử dụng

* Python 3.x
* OpenCV
* NumPy
* Matplotlib
* Jupyter Notebook

## Tệp quan trọng

* `DepthInformationReconstruction.ipynb`: Notebook chính cho xử lý và hiển thị bản đồ độ sâu
* `Aloe_left_1.png`, `Aloe_right_1.png`, `right.png`: Các ảnh đầu vào để xử lý stereo

## Cách sử dụng

1. Cài đặt các thư viện cần thiết:

   ```bash
   pip install opencv-python numpy matplotlib
   ```
2. Mở tệp notebook:

   ```bash
   jupyter notebook DepthInformationReconstruction.ipynb
   ```
3. Thực thi các ô trong notebook để:

   * Tải ảnh stereo
   * Tính toán disparity
   * Hiển thị bản đồ độ sâu

## Ghi chú

* Ảnh stereo cần được chụp từ hai góc nhìn khác nhau của cùng một cảnh để đảm bảo tính chính xác khi tái tạo độ sâu.
* Chất lượng ảnh và việc căn chỉnh ảnh ảnh hưởng lớn đến kết quả.

## Bản quyền

Bộ ảnh ví dụ được sử dụng trong dự án chỉ nhằm mục đích học tập và minh họa kỹ thuật xử lý ảnh stereo.
