# Phát hiện Lừa đảo trong Đánh giá sử dụng Mạng nơ-ron Đồ thị (Graph Neural Networks)

## 🇻🇳 Tiếng Việt

### 🎯 Trọng tâm Dự án

Dự án này giải quyết vấn đề **đánh giá lừa đảo (fraudulent reviews)** trên các nền tảng trực tuyến. Mục tiêu là phát triển một hệ thống có khả năng nhận diện các hoạt động gian lận một cách hiệu quả, bằng cách mô hình hóa mối quan hệ giữa người dùng, đánh giá và mặt hàng dưới dạng một **đồ thị (Graph)**, sử dụng Mạng nơ-ron Đồ thị (GNN).

### 🔬 Phương pháp và Kết quả Thí nghiệm

Chúng tôi đã triển khai và so sánh hiệu suất của hai mô hình GNN tiên tiến là **GraphSAGE** và **CARE-GNN** trên bộ dữ liệu đánh giá **YelpChi dataset**.

```html
<div align="center">
  <p>Kết quả thí nghiệm chi tiết cho thấy khả năng của các mô hình GNN trong việc phân loại gian lận:</p>

  | Mô hình | Accuracy | ROC-AUC | Recall Score | F1 Score |
  | :--- | :--- | :--- | :--- | :--- |
  | **GraphSAGE** | **0.85** | 0.76 | 0.70 | 0.69 |
  | **CARE-GNN** | 0.50 | 0.59 | 0.50 | 0.46 |
</div>
```

Mô hình **GraphSAGE** đã đạt được độ chính xác (Accuracy) cao nhất là **0.85** và cho thấy hiệu suất tổng thể tốt hơn trong việc xác định các đánh giá lừa đảo, với các chỉ số **Recall** và **F1-Score** đều vượt trội.

-----
# Fraud Detection in Reviews using Graph Neural Networks

## 🇬🇧 English Version

### 🎯 Project Focus

This project tackles the critical issue of **fraudulent reviews** on online platforms. The goal is to develop an effective system capable of identifying fraudulent activities by modeling the relationships between users, reviews, and items as a **Graph**, utilizing Graph Neural Networks (GNNs).

### 🔬 Methodology and Experimental Results

We implemented and compared the performance of two advanced GNN models: **GraphSAGE** and **CARE-GNN**, using the **YelpChi dataset** for fraud detection.

```html
<div align="center">
  <p>The detailed experimental results highlight the capabilities of the GNN models in fraud classification:</p>

  | Model | Accuracy | ROC-AUC | Recall Score | F1 Score |
  | :--- | :--- | :--- | :--- | :--- |
  | **GraphSAGE** | **0.85** | 0.76 | 0.70 | 0.69 |
  | **CARE-GNN** | 0.50 | 0.59 | 0.50 | 0.46 |
</div>
```

The **GraphSAGE** model achieved the highest overall accuracy of **0.85** and demonstrated superior general performance in identifying fraudulent reviews, with better **Recall** and **F1-Scores**.
