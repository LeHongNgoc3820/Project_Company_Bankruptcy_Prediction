**Project_Company_Bankruptcy_Prediction**
# Application of machine learning models to predict company bankruptcy
[Chi tiết bài viết](
**Dưới đây là nội dung tóm tắt**

Dự báo về vỡ nợ của công ty được sử dụng trong các lĩnh vực khác nhau trên toàn nền kinh tế. Các tập đoàn có thể chẩn đoán tình trạng hiện tại của họ dựa trên các mô hình dự đoán và thiết lập các chiến lược của họ. Các nhà điều hành có thể điều hành doanh nghiệp của họ ổn định hơn bằng cách quản lý các chỉ số chính ảnh hưởng đến rủi ro vỡ nợ của công ty. Các nhà đầu tư có thể sửa đổi chiến lược của họ và cải thiện danh mục đầu tư của họ bằng cách kiểm tra khả năng vỡ nợ của công ty. Ngoài ra, các chính phủ có thể thiết lập các chính sách an toàn vĩ mô và cải thiện các quy định tài chính liên quan bằng cách sử dụng các dự đoán vỡ nợ của công ty. Theo những cách này, các mô hình dự đoán vỡ nợ giúp thiết kế và cải thiện hệ thống tài chính. Ngoài ra, bằng cách sử dụng các thuật toán học máy và mô hình thống kê, các dự đoán vỡ nợ của công ty là ưu tiên hàng đầu của kỹ thuật tài chính tiên tiến. Cuộc khủng hoảng tài chính toàn cầu gần đây và sự gia tăng rủi ro tín dụng càng làm nổi bật tầm quan trọng của lĩnh vực này. Do tầm quan trọng của chúng, các dự đoán vỡ nợ của công ty đã được nghiên cứu rộng rãi.

Trong bài phân tích này, một số kết quả quan trọng được tìm thấy như sau:
+ Đề tài sử dụng các mô hình Machine Learning để đưa ra mô hình tốt nhất cho dự báo phá sản tại các công ty.
+ Mô hình tốt nhất đưa ra là **Logistic Regression Model**. Mặc dù ANN có accuracy có độ chính xác rất cao (auc = 92.7%). Tuy nhiên, ANN model tốn thời gian thực hiện và chạy model hơn, do đó, Logistic Regression là lựa chọn tối ưu nhất được đề xuất.
+ Độ chính xác của mô hình xây dựng được là **92.7 %**.
+ Ngoài ra, **top 10 features** có tác động lớn đến Bankruptcy gồm:
    + Continuous interest rate (after tax),
    + Persistent EPS in the Last Four Seasons
    + Per Share Net profit before tax (Yuan ¥)
    + Debt ratio %
    + Net worth/Assets
    + Borrowing dependency
    + Net profit before tax/Paid-in capital
    + Net Income to Total Assets
    + Net Income to Stockholder's Equity
    + Equity to Liability
    
Tóm lại, việc xây dựng mô hình để dự đoán rủi ro vỡ nợ (hay rủi ro phá sản) là rất quan trọng đối với mỗi doanh nghiệp. Do đó, khi thực hiện dự báo vỡ nợ doanh nghiệp, cần lựa chọn một phương pháp phù hợp để có thể cung cấp thông tin phù hợp cho mục đích dự báo, đòi hỏi phải hiểu cặn kẽ về cách sử dụng phù hợp của từng phương pháp.

**Hướng mở trong tương lai, có thể kết hợp thêm các model Machine Learning khác như `Gradient Boosted Tree`, `AdaBoost`, `Light GBM` để đưa ra model với độ chính xác cao hơn.**
