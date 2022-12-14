# CS116.M12.KHCL
<!-- Banner -->
<p align="center">
  <a href="https://www.uit.edu.vn/" title="Trường Đại học Công nghệ Thông tin" style="border: none;">
    <img src="https://i.imgur.com/WmMnSRt.png" alt="Trường Đại học Công nghệ Thông tin | University of Information Technology">
  </a>
</p>

<h1 align="center"><b>LẬP TRÌNH PYTHON CHO MÁY HỌC</b></h>

## THÀNH VIÊN NHÓM
| STT    | MSSV          | Họ và Tên              |Chức Vụ    | Github                                                  | Email                   |
| ------ |:-------------:| ----------------------:|----------:|--------------------------------------------------------:|-------------------------:
| 1      | 20521642      | Phạm Thị Bích Nga      |           |[phamhibichnga](https://github.com/phamthibichnga9)      |20521642@gm.uit.edu.vn   |


## GIỚI THIỆU MÔN HỌC
* **Tên môn học:** Lập trình Python cho Máy học
* **Mã môn học:** CS116
* **Mã lớp:** C116.M12.KHCL
* **Năm học:** HK2 (2021 - 2022)
* **Giảng viên**: TS.Nguyễn Vinh Tiệp

## QUÁ TRÌNH
### Week 1: Làm quen với Python.
   1. [Tutorial Numpy.](Progress/Week_1/Tutorial_Numpy.ipynb) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;3. [Tutorial Matplotlib.](Progress/Week_1/Tutorial_Matplotlib.ipynb)
   2. [Tutorial Pandas.](Progress/Week_1/Tutorial_Pandas.ipynb) &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;4. [Tutorial Seaborn.](Progress/Week_1/Seaborn.ipynb)

### Week 2: Thống kê và Trực quan hoá dữ liệu trên bản đồ.
<table>
<tr>
  <td width='50%'>
    <img src='https://github.com/trong-khanh-1109/CS116.M12.KHCL/blob/ddb5fa11853bca660bb5c2b299f40a5e3a4109ae/Image/Week_2.png'></img>
  </td>
  <td>
    - Đặc điểm của dữ liệu có cấu trúc:</br>
    &emsp;&emsp;+ Có các trường(cột) có thuộc tính cố định</br>
    &emsp;&emsp;+ Ý nghĩa các trường không thay đổi</br>
    &emsp;&emsp;+ Dữ liệu thống nhất</br></br>
    - Dữ liệu bảng + Không gian (Geographic Information System)</br>
    &emsp;&emsp;+ Geographic: Polypoint, Polyline, Polygun</br>
  </td>
</tr>
  <table>
  
  - Bài tập: [Xử lý dữ liệu GIS](Progress/Week2/20521642_BichNga_GIS_data_Processing.ipynb) và [Hiện thị ranh giới các quận trên bản đồ.](Progress/Week_2/Hiển_thị_ranh_giới_quận_trên_bản_đồ.ipynb)
  
### Week 3: Phân tích hành vi click với KMeans.
  &emsp;&emsp;&emsp;&emsp;<img height=400 src='https://github.com/trong-khanh-1109/CS116.M12.KHCL/blob/86b5b5443b473b67e8f0eb98ec18d037b949e7ba/Image/week3.png'></img>
  
  - Bài tập: [Phân tích hành vi click của các quận của TP-HCM trên bản đồ.](Progress/Week_3/Phân_tích_hành_vi_click_với_KMeans.ipynb)

### Week 4: Principal Component Analysis.
  - Bài tập: [PCA normal.](Progress/Week_4/PCA_homework_normal.ipynb)

### Week 5: Use PCA for Logistic Regression.
  - Bài tập: [PCA và Logistic Regression để phân loại rượu.](Progress/Week_5/PCA_for_classification.ipynb)

### Week 6: Cassification Social Network Ads.
  - Bước 1: Đọc dữ liệu từ file .csv.
  - Bước 2: Phân chia dữ liệu thành tập train và tập test theo tỉ lệ 8:2.
  - Bước 3: Chuẩn hóa dữ liệu.
  - Bước 4: Khởi tạo và huấn luyện các mô hình.
  - Bước 5: Infer và đánh giá mô hình với độ đo accuracy.
  - Bước 6: Trực quan hóa kết quả của mô hình vừa huấn luyện.
  - Bài tập: [Cassification Social Network Ads.](Progress/Week_6/Cassification_Social_Network_Ads.ipynb)

### Week 7: Mô Hình Linear Regression Đơn Và Đa Biến.
  - Bài tập: [Linear Regression Đơn Và Đa Biến.](Progress/Week_7/Linear_Regression.ipynb)

### Week 8: Xây Dựng Mô Hình Mạng Neural Network.
  - Bước 1: Đọc dữ liệu từ file excel/csv.
  - Bước 2: Chuẩn hóa các cột dữ liệu thuộc dạng không có tình thứ tự (dữ liệu rời rạc) thành dạng `One Hot Encoding`.
  - Bước 4: Chuẩn hóa dữ liệu train bằng Standard Scaler.
  - Bước 5: Xây dựng mô hình Mạng Neural Network bằng thư viện Keras và lớp đối tượng Dense, Input - 6 neurons/ReLU - 6 neurons/ReLU - 1 neuron / sigmoid.
  - Bước 6: Huấn luyện mạng với thuật toán `Adam` sử dụng hàm độ lỗi `Binary Cross Entropy`.
  - Bước 7: Test và đánh giá kết quả.
  - Bước 8: Đánh giá độ chính xác bằng phương pháp `KFold Cross Validation` với k = 5.
  - Bài tập: [Xây Dựng Mô Hình Mạng Neural Network.](Progress/Week_8/Deep_Learning.ipynb)

### Week 9: Mạng CNN với kiến trúc MiniResNet.
  - Bài tập: [MNIST use MiniResNet](Progress/Week_9/CNN_MNIST.ipynb)

### Week 10: Parameters and Hyperparameter.
  - Bài tập: [Cài đặt Grip Search để tiểm Hyperparameter.](Progress/Week_10/Hyper_Parameter.ipynb)

### Week 11: Tìm hiểu và thực hành XGBoots.
  - Bài tập: [XGBoots.](Progress/Week_11/XGBoost.ipynb)

### Week 12: Mạng CNN với kiến trúc VGG16
  - Bài tập: [Trích xuất đặc trưng sử dụng VGG16.](Progress/Week_12/CNN_VGG16.ipynb)
