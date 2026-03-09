# He-thong-goi-y-san-pham
# **1. GIỚI THIỆU VẤN ĐỀ**
## **1.1. Tổng quan vấn đề**
Trong bối cảnh quá tải thông tin của thương mại điện tử, hệ thống gợi ý đóng vai trò quan trọng giúp cá nhân hóa trải nghiệm và tối ưu doanh thu. Đề tài tập trung xây dựng mô hình dựa trên hành vi khách hàng (`view`, `cart`, `purchase`) và thuộc tính sản phẩm để đưa ra những đề xuất chính xác nhất.
## **1.2. Mục tiêu**
Mục tiêu chính của đề tài là xây dựng và so sánh các phương pháp gợi ý khác nhau để tìm ra mô hình tốt nhất cho tập dữ liệu:
### **1.2.1. Content-Based Filtering (Lọc dựa trên nội dung)**
* Xây dựng mô hình gợi ý các sản phẩm tương tự dựa trên đặc điểm của chính sản phẩm đó (như loại hàng, thương hiệu, giá cả).

* Sử dụng các kỹ thuật như **TfidfVectorizer** để xử lý dữ liệu văn bản từ thuộc tính sản phẩm.
### **1.2.2. Collaborative Filtering (Lọc cộng tác)**
* Tận dụng hành vi của cộng đồng người dùng (user-item interaction) để đưa ra gợi ý.

* Áp dụng các thuật toán như Matrix Factorization (SVD) hoặc các thư viện chuyên dụng như `implicit` để xử lý dữ liệu phản hồi ẩn (implicit feedback) từ các sự kiện như xem hoặc thêm vào giỏ hàng.

### **1.2.3. Hybrid Reecommender (Hệ thống gợi ý lai)**
Kết hợp ưu điểm của cả hai phương pháp trên nhằm khắc phục các hạn chế như vấn đề "người dùng mới/sản phẩm mới" (Cold Start) và nâng cao độ chính xác tổng thể của hệ thống.
