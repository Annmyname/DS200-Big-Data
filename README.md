# Phát hiện Lừa đảo trong Đánh giá sử dụng Mạng nơ-ron Đồ thị (Graph Neural Networks)

## 🇻🇳 Tiếng Việt
### Trọng tâm Dự án

Dự án này giải quyết vấn đề **đánh giá lừa đảo (fraudulent reviews)** trên các nền tảng trực tuyến, một thách thức lớn trong việc duy trì tính toàn vẹn và sự tin cậy của hệ thống đánh giá. Mục tiêu là phát triển một hệ thống có khả năng nhận diện các hoạt động gian lận một cách hiệu quả.

### Phương pháp và Kết quả nổi bật

| Phương pháp | Bộ dữ liệu | Kết quả Chính |
| :--- | :--- | :--- |
| Triển khai và so sánh hai mô hình tiên tiến dựa trên **Mạng nơ-ron Đồ thị (GNN)**: **GraphSAGE** và **CARE-GNN**.  | Dữ liệu đánh giá **YelpChi dataset**. | 

Kết quả thí nghiệm chi tiết cho thấy khả năng của các mô hình GNN trong việc phân loại gian lận:
Mô hình	Accuracy	ROC-AUC	Recall Score	F1 Score
GraphSAGE	0.85	0.76	0.70	0.69
CARE-GNN	0.50	0.59	0.50	0.46
Mô hình **GraphSAGE** đạt độ chính xác (Accuracy) **0.85**. Cả hai mô hình đều cho thấy hiệu quả cao với Recall **> 0.65** và ROC-AUC **> 0.50** trong việc xác định các đánh giá gian lận. |

---
# Fraud Detection in Reviews using Graph Neural Networks
## 🇬🇧 English Version

### Project Focus

This project addresses the problem of **fraudulent reviews** on online platforms, a major challenge in maintaining the integrity and credibility of review systems. The goal is to develop an effective system capable of identifying fraudulent activities.

### Methodology and Key Results

| Methodology | Dataset | Key Results |
| :--- | :--- | :--- |
| Implemented and compared two advanced **Graph Neural Network (GNN)** models: **GraphSAGE** and **CARE-GNN**, for fraud detection. | **YelpChi dataset**. | The **GraphSAGE** model achieved an accuracy of **0.85**. Both models demonstrated high effectiveness with Recall scores **> 0.65** and ROC-AUC **> 0.50** in identifying fraudulent reviews. |
