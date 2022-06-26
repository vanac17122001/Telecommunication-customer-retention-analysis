# Đồ án kết thúc học phần : Data mining 
## Đề tài :  Telecommunication-customer-retention-analysis
### Thành viên nhóm : 
1. Cao Anh Văn 
2. Trần Văn Duy 
3. Trần Công Trường
4. Nguyễn Duy Phước 
### Giới thiệu về đề tài 
- **Mục đích** :
  + Câu hỏi nghiên cứu của nhóm là dự đoán các khách hàng có khả năng rời đi cao nhất dựa trên các dịch vụ, thông tin các nhân của khách hàng. 
  + Output của bài toán là biến “Churn” mang giá trị “yes” hoặc “no” cho thấy quyết định có rời đi hay không của khách hàng.
- **Các model mà nhóm sử dụng** :
  + Các bài toán được sử dụng trong mô hình là: K-NN, random forest, Decision tree, Logistic Regression.
- **Các thuộc tính của tập dữ liệu** :
1.	CustomerID: id của mỗi khách hàng.
2.	Gender: giới tính  ( male, female).
3.	SeniorCitizen: người cao tuổi (0,1).
4.	Partner: Có cộng sự hay không ( yes, no).
5.	Dependents: Có người phụ thuộc hay không ( yes, no).
6.	tenure: số tháng ở lại với công ty.
7.	PhoneService: có sử dụng dịch vụ điện thoại hay không ( yes, no).
8.	MultipleLines: có nhiều đường dây hay không ( yes, no, no phone).
9.	InternetService: nhà cung cấp dịch vụ điện thoại (DSL, có, không).
10.	Online Security : Cho biết liệu khách hàng có đăng ký dịch vụ bảo mật trực tuyến bổ sung do công ty cung cấp hay không (yes, no).
11.	OnlineBackup: dịch vụ sao lưu online ( yes, no, no internet ).
12.	DeviceProtection: dịch vụ bảo vệ thiết bị ( yes, no , no internet).
13.	TechSupport: hỗ trợ kĩ thuật ( yes, no , no internet).
14.	StreamingTV: truyền hình trực tuyến ( yes, no, no internet).
15.	Contract: Cho biết loại hợp đồng hiện tại của khách hàng : Month-to-Month, One Year, Two Year.
16.	StreamingMovies: xem phim trực tuyến ( yes, no , no internet).
17.	PaperlessBilling: thanh toán trực tuyến ( yes, no) .
18.	PaymentMethod: phương thức thanh toán.
19.	Monthly Charges: thanh toán hằng tháng.
20.	TotalCharges: tổng thanh toán.
21.	Churn: quyết định rời đi hay tiếp tục sử dụng dịch vụ ( yes, no).
