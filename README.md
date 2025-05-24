# 🧠 Ứng dụng AI chẩn đoán bệnh ung thư vú

Dự án sử dụng các thuật toán học máy để xây dựng mô hình phân loại khối u vú là **lành tính (Benign)** hay **ác tính (Malignant)** dựa trên bộ dữ liệu chuẩn `Breast Cancer Wisconsin (Diagnostic)`.

## 🚀 Mục tiêu
- Phát hiện sớm nguy cơ ung thư vú nhằm hỗ trợ bác sĩ và bệnh nhân đưa ra quyết định điều trị kịp thời.
- So sánh hiệu quả giữa các mô hình học máy: `Naïve Bayes`, `Random Forest`, và `Logistic Regression`.

## 📊 Dữ liệu sử dụng
- **Nguồn**: UCI Machine Learning Repository  
- **Đặc điểm**: 569 mẫu, 30 đặc trưng mô tả các thuộc tính hình học và thống kê của tế bào vú.

## 🛠️ Các bước thực hiện
1. Tiền xử lý và chuẩn hóa dữ liệu bằng `StandardScaler`.
2. Huấn luyện mô hình:
   - Gaussian Naïve Bayes
   - Random Forest Classifier
   - Logistic Regression
3. Đánh giá mô hình bằng các chỉ số:
   - Accuracy
   - Precision
   - Recall
   - F1-Score

## 📈 Kết quả
| Mô hình            | Accuracy | Recall |
|--------------------|----------|--------|
| Naïve Bayes        | 92.4%    | 90%    |
| Random Forest      | 96.5%    | 95%    |
| Logistic Regression| **97.7%**| **95%**|

👉 **Logistic Regression** cho kết quả tốt nhất về cả độ chính xác và độ nhạy.

*Dự án thuộc môn Nhập môn Trí tuệ nhân tạo, Trường ĐH Khoa học Tự nhiên – ĐHQGHN.*

