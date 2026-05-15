#  Machine Learning Fundamentals - Exercises & Implementation

Kho lưu trữ này chứa các bài tập thực hành về toán học bổ trợ và các khái niệm cốt lõi trong Machine Learning, bao gồm Đại số tuyến tính, Giải tích, Xác suất thống kê và thuật toán tối ưu.

##  Danh mục bài tập

### 1. Đại số tuyến tính (Linear Algebra)
* **Matrix Multiplication & Transpose:** Thực hiện nhân ma trận $XW$, hiểu về sự tương quan giữa các chiều (shape) và ý nghĩa của phép chuyển vị $X^T$.
* **Hadamard & Matrix Norms:** Phân biệt nhân từng phần tử (Hadamard) với nhân ma trận. Tính toán chuẩn $L_1, L_2$ (Frobenius) để đo lường độ lớn của ma trận.
* **Inverse Matrix:** Cách tính và kiểm tra ma trận nghịch đảo $M^{-1}M = I$.

### 2. Giải tích & Tối ưu hóa (Calculus & Optimization)
* **Derivatives & Chain Rule:** Tính đạo hàm các hàm cơ bản và áp dụng quy tắc chuỗi (Chain Rule) trong Backpropagation.
* **Partial Derivatives:** Tính đạo hàm riêng cho hàm nhiều biến, ứng dụng vào việc tính Gradient cho hàm mất mát MSE.
* **Gradient Descent:** Mô phỏng quá trình tối ưu hóa hàm số $f(x,y) = x^2 + y^2$, quan sát sự hội tụ về điểm cực tiểu toàn cục $(0,0)$.

### 3. Xác suất & Thống kê (Probability & Statistics)
* **Descriptive Statistics:** Tính toán Mean, Median, Variance và Standard Deviation để hiểu độ phân tán của dữ liệu.
* **Probability & Bayes' Theorem:** * Tính xác suất có điều kiện $P(A|B)$.
    * Xây dựng bộ phân loại Naive Bayes đơn giản để phân loại cảm xúc văn bản (Positive/Negative).
* **Distributions:** Làm việc với phân phối Bernoulli (email spam) và phân phối chuẩn Normal Distribution (quy tắc 68-95-99.7).
* **Correlation & Covariance:** Phân tích mối quan hệ giữa các đặc trưng (như điểm GRE và khả năng trúng tuyển) thông qua hệ số tương quan $\rho$.

### 4. Logistic Regression Implementation
* Triển khai hàm kích hoạt **Sigmoid**.
* Xây dựng hàm mất mát **Binary Cross-Entropy (BCE)**.
* Viết vòng lặp huấn luyện (Training Loop) bao gồm: Forward pass, tính Gradient và cập nhật trọng số.

##  Công cụ sử dụng
* **Ngôn ngữ:** Python 3.x
* **Thư viện:** * `NumPy`: Tính toán ma trận và đại số tuyến tính.
    * `SymPy`: Giải đạo hàm bằng ký hiệu toán học.
    * `SciPy`: Xử lý các phân phối xác suất thống kê.
    * `Matplotlib`: (Tùy chọn) Để trực quan hóa đồ thị hàm mất mát.

##  Nhận xét cá nhân
Qua các bài tập này, em đã hiểu rõ hơn về:
1. Cách toán học vận hành dưới "nắp capo" của các mô hình học máy.
2. Tại sao việc chuẩn hóa dữ liệu và chọn tốc độ học (Learning Rate) lại quan trọng.
3. Tầm quan trọng của việc kiểm tra độ tương quan giữa các biến trước khi xây dựng mô hình.

---
*Created by [TuanKiet3101] - 2025*
