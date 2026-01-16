# Dự Đoán Doanh Thu Quán Nước (Beverage Shop Revenue Prediction)

# Giới thiệu (Introduction)
Đây là bài tập lớn môn Học Máy Thống Kê, tập trung vào việc áp dụng các thuật toán Machine Learning để phân tích và dự đoán doanh thu của cửa hàng đồ uống. 

Mục tiêu của dự án là xây dựng mô hình giúp chủ cửa hàng có thể ước tính doanh thu dựa trên các yếu tố như: thời tiết, ngày cuối tuần, sự kiện đặc biệt và các chương trình khuyến mãi.

# Tính năng chính (Key Features)
* Xử lý dữ liệu (Data Cleaning): Xử lý các giá trị bị thiếu (Missing values), loại bỏ nhiễu.
* Phân tích dữ liệu (EDA): Trực quan hóa sự tương quan giữa doanh thu và các yếu tố bên ngoài (Thời tiết, nhiệt độ, ngày lễ...).
* Mô hình hóa (Modeling): Xây dựng và huấn luyện mô hình dự đoán (Linear Regression, Random Forest, v.v...).
* Đánh giá: Kiểm tra độ chính xác của mô hình trên tập dữ liệu thực tế.

# Công nghệ sử dụng (Tech Stack)
* Ngôn ngữ: Python
* IDE: Jupyter Notebook / VS Code
* Thư viện chính:
    * `Pandas`, `NumPy`: Xử lý và phân tích dữ liệu bảng.
    * `Matplotlib`, `Seaborn`: Vẽ biểu đồ trực quan hóa.
    * `Scikit-learn`: Xây dựng các mô hình học máy.

# Kết quả (Results)
* Mô hình đã xác định được các yếu tố ảnh hưởng mạnh nhất đến doanh thu là: Sự kiện, Khuyến mại,... 
* Độ chính xác (Accuracy/R2 Score) đạt được trên tập kiểm thử: ~90 %
