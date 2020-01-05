# DataScienceFinalProject
Predict book's rating

Câu hỏi: Dự đoán xem cuốn sách có tốt hay không mà không cần đọc nó

Nguồn dữ liệu: 

Sách hay: https://www.goodreads.com/list/show/264.Books_That_Everyone_Should_Read_At_Least_Once

Sách dở: https://www.goodreads.com/list/show/23974

Số dòng:

Train: 3598

Test: 1919

Số cột: 5 (Genre, format, number of pages, language, good)

Output: Good (True or False)

Tiền xử lý:

Trong lúc thu nhập dữ liệu: Đổi số trang từ string sang int, thế các chỗ trống ở cột num_of_pages bằng 0

Sau khi thu thập dữ liệu:

Bỏ cột title và author
Điền vào chỗ trống bằng SimpleImputer (Most frequent vì các cột có dạng dữ liệu string)
Dùng OneHotEncoder

Phân tích

Thuật toán: MLPClassifer
Layer Sizes: 10, 20, 30, 40, 50, 60
Alpha: 0.0001, 0.1, 1, 10, 100, 1000



