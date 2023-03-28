# stock-prediction-with-variety-of-methods
### Thử nghiệm so sánh ứng dụng của Phân tích kỹ thuật, Machine learning và Deep learning vào dự đoán giá chứng khoán
**Thông tin chung:**

**Tên đề tài:** Thử nghiệm so sánh ứng dụng của Phân tích kỹ thuật, Machine learning và Deep learning vào dự đoán giá chứng khoán

**Ngôn ngữ lập trình:** Python

**Nền tảng lập trình:** Jupyter Notebook

**Các thư viên sử dụng:** yfinance, prophet, tensorflow, numpy, pandas, matplotlib, seaborn, re, csv, statsmodel, sklearn, datetime, warnings, keras.

**Các file nằm trong thư mục:**
+ file ipynb: Stock Prediction Models.ipynb (file source code chính)
+ file pdf: Report Paper.pdf (file diễn giải và trình bài kết quả nghiên cứu)
+ file csv: microsoft_data.csv (file dữ liệu)

**Giới thiệu:**

Trong đề tài này, nhiều mô hình khác nhau sẽ được sử dụng để dự báo giá Đóng cửa điều chỉnh cho dữ liệu giá cổ phiếu của Tập đoàn Microsoft. Từ các chỉ số phân tích kỹ thuật đơn giản
(như đường Trung bình động – Moving Average), thuật toán Hồi quy tuyến tính (Linear Regression), các mô hình máy học từ đơn giản (k-Nearest Neighbor) đến phức tạp hơn (Prophet),
và đến cuối cùng là thuật toán học sâu (LSTM - Long Short-Term Memory). Các phương pháp sẽ được ứng dụng lần lượt và so sánh kết quả để tìm ra được đâu là mô hình mang lại hiệu quả
tối ưu nhất.

**Dữ liệu:**

Dữ liệu trong bài làm là dữ liệu giá đóng cửa điều chỉnh của Tập đoàn Microsoft, với interval cho mỗi điểm dữ liệu là 1 ngày, được lấy trong giai đoạn từ ngày 01/01/2010 đến ngày
10/01/2023 (là thời điểm mới nhất). Dữ liệu được lấy trực tiếp từ Yahoo Finance thông qua API của yfinance.

*Các mô hình trong bài làm có thể được áp dụng đối với bất kỳ dữ liệu cổ phiếu nào được niêm yết công khai.*
