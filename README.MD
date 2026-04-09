Dựa trên nội dung file báo cáo bạn cung cấp , mình viết lại **README.md** cho dự án (ngắn gọn, chuẩn để đưa GitHub/CV):

---

# 🍷 Wine Quality Analysis & Prediction

## 📌 Giới thiệu

Dự án tập trung phân tích đặc tính hóa học của rượu vang và xây dựng mô hình Machine Learning nhằm dự đoán chất lượng rượu dựa trên dữ liệu định lượng.

## 🎯 Mục tiêu

* Phân tích dữ liệu (EDA) để hiểu đặc trưng và mối quan hệ giữa các biến
* Áp dụng các kỹ thuật giảm chiều (PCA)
* Thực hiện phân cụm (KMeans) để khám phá cấu trúc dữ liệu
* Xây dựng mô hình Neural Network (MLP) để dự đoán chất lượng rượu
* Triển khai ứng dụng dự đoán bằng Streamlit

## 📊 Dataset

* File: `wine_100k_generated.csv`
* Quy mô: ~100,000 mẫu, 16 thuộc tính
* Không có giá trị thiếu

## ⚙️ Công nghệ sử dụng

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Scikit-learn (KMeans, PCA, MLPClassifier)
* Streamlit (Web App)

## 🔍 Các bước thực hiện

### 1. Exploratory Data Analysis (EDA)

* Phân tích phân phối dữ liệu
* Kiểm tra tương quan (Pearson)
* Phát hiện dữ liệu mất cân bằng

### 2. Clustering (KMeans)

* Áp dụng Elbow & Silhouette để chọn số cụm
* Phân cụm dữ liệu và phân tích đặc trưng từng cluster

### 3. Dimensionality Reduction (PCA)

* Chuẩn hóa dữ liệu
* Giảm từ 15 chiều xuống 2–7 chiều
* Giữ ~80% thông tin với 7 thành phần chính

### 4. Classification (Neural Network)

* Sử dụng MLPClassifier
* Chia dữ liệu train/test (70/30)
* Tuning hyperparameters để tối ưu mô hình

### 5. So sánh mô hình

* Case 1: Dữ liệu gốc
* Case 2: PCA (2 chiều)
* Case 3: PCA (3 chiều)

## 📈 Kết quả

* Accuracy đạt ~91% với mô hình tối ưu
* Các biến quan trọng: alcohol, density, color_intensity
* PCA giúp giảm chiều nhưng có thể làm giảm độ chính xác nếu giảm quá mạnh

## 🚀 Ứng dụng

* Xây dựng web app bằng Streamlit
* Cho phép nhập dữ liệu → dự đoán chất lượng rượu

## 👥 Nhóm thực hiện

* Nhóm 5 – DHHTTT19BTT

## 📌 Kết luận

Dự án cho thấy việc kết hợp EDA, PCA, KMeans và Neural Network giúp hiểu rõ dữ liệu và xây dựng mô hình dự đoán hiệu quả. Mô hình MLP đạt độ chính xác cao và có thể ứng dụng thực tế.

---

Nếu bạn muốn, mình có thể **viết bản README chuyên nghiệp hơn (chuẩn GitHub xịn, có badge, folder structure, cách chạy code, demo UI)** để bạn đưa thẳng vào CV hoặc portfolio 👍
