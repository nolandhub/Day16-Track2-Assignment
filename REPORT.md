# Báo cáo Lab 16 - Cloud AI Benchmark

**Họ tên:** Đỗ Lê Thành Nhân
**MSHV:** 2A202600361


- **Môi trường:** Google Cloud Platform (GCP)

- **Phương án thực hiện:** CPU Instance (n2-standard-8) + LightGBM.

- **Lý do dùng CPU:** Do tài khoản mới (Free tier) chưa được cấp Quota GPU sau khi đã yêu cầu tăng hạn mức.

- **Nhận xét kết quả:** 
    - Mô hình LightGBM chạy cực nhanh trên CPU (Training ~1s).
    - Độ chính xác (Accuracy) đạt trên 99.9%, phù hợp cho bài toán Credit Card Fraud.
    - Chi phí vận hành thấp, phù hợp cho môi trường lab.
