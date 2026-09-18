# 🤖 Complete A.I. & Machine Learning, Data Science Bootcamp

Repository quản lý lộ trình học tập, tài liệu nghiên cứu, bài tập thực hành và toàn bộ đồ án (Milestone Projects) từ khóa học **Complete A.I. & Machine Learning, Data Science Bootcamp** (Zero To Mastery - Andrei Neagoie & Daniel Bourke) trên Udemy.

---

## 📌 Tổng quan mục tiêu

- **Mục tiêu thời gian:** 2,5 tháng (10 tuần).
- **Cường độ học:** 2 – 3 giờ / ngày (~15 – 21 giờ / tuần | Tổng cộng ~180 – 210 giờ).
- **Mục tiêu kỹ năng:** Thành thạo quy trình Data Science (Numpy, Pandas, Matplotlib), mô hình học máy (Scikit-Learn), học sâu cơ bản (TensorFlow 2) và hoàn thiện 2 Capstone Projects chuẩn Portfolio.

---

## 🧭 Lộ trình chi tiết 2,5 Tháng (10 Tuần | 2–3h/ngày)

### 🗓️ Tuần 1: Khởi động, Môi trường & Nền tảng Tư duy
* **Thời lượng:** ~15–18 giờ (2–3h/ngày)
* **Nội dung:**
  - **Section 1 - 4:** Giới thiệu, Tư duy giải quyết vấn đề với Machine Learning Framework 6 bước (Problem Definition, Data, Evaluation, Features, Modelling, Experimentation).
  - **Section 5:** Thiết lập môi trường thực hành: Anaconda, Conda Environment, Jupyter Notebook, kết nối VS Code.
  - *(Dành cho người mới Python):* Lướt nhanh Section 17 & 18 nếu cần củng cố cú pháp danh sách, hàm, dict, OOP cơ bản.
* **Mục tiêu đầu ra:** Môi trường Conda chạy ổn định trên máy tính, kết nối thành công với VS Code, tạo commit đầu tiên lên GitHub.

---

### 🗓️ Tuần 2: Xử lý dữ liệu với Pandas & Tính toán số học NumPy
* **Thời lượng:** ~15–20 giờ (2–3h/ngày)
* **Nội dung:**
  - **Section 6: Pandas Data Analysis:** Series, DataFrame, nhập xuất file CSV/Excel, quan sát dữ liệu (`.describe()`, `.info()`), lọc dữ liệu với `.loc` / `.iloc`, nhóm dữ liệu (`groupby`), xử lý giá trị khuyết thiếu (missing data).
  - **Section 7: NumPy:** Mảng N-chiều (`ndarray`), Datatypes, thao tác slicing, indexing, phép toán ma trận, vectorization, Random seed.
* **Mục tiêu đầu ra:** Hoàn thành 2 notebooks `pandas_practice.ipynb` và `numpy_practice.ipynb`.

---

### 🗓️ Tuần 3: Trực quan hóa dữ liệu (Matplotlib) & EDA thực chiến
* **Thời lượng:** ~15–18 giờ (2–3h/ngày)
* **Nội dung:**
  - **Section 8: Matplotlib:** Kiến trúc Object-Oriented (Figure & Axes), Line plot, Scatter plot, Bar chart, Histogram, Subplots, tùy chỉnh style và lưu biểu đồ.
  - **Mini EDA Project:** Tự chọn một dataset bất kỳ từ Kaggle để thực hành làm sạch, trích xuất thông tin thống kê và trực quan hóa phân phối dữ liệu.
* **Mục tiêu đầu ra:** Đẩy notebook hoàn chỉnh về EDA trực quan lên thư mục `03-matplotlib-visualization/`.

---

### 🗓️ Tuần 4: Nền tảng Scikit-Learn (Phần 1: Chuẩn bị & Huấn luyện)
* **Thời lượng:** ~18–21 giờ (2.5–3h/ngày)
* **Nội dung:**
  - **Section 9 (Nửa đầu):** Luồng làm việc chuẩn của Scikit-Learn:
    - Chuẩn bị dữ liệu: Tách Feature ($X$) & Label ($y$), `train_test_split`.
    - Chuyển đổi dữ liệu dạng chữ thành số (`OneHotEncoder`, `ColumnTransformer`).
    - Điền dữ liệu thiếu bằng `SimpleImputer`.
    - Chọn thuật toán phù hợp (Scikit-Learn Algorithm Cheat-sheet).
    - Huấn luyện mô hình Phân loại (Classification) & Hồi quy (Regression).
* **Mục tiêu đầu ra:** Hiểu và tự viết pipeline tiền xử lý dữ liệu chuẩn không bị rò rỉ dữ liệu (data leakage).

---

### 🗓️ Tuần 5: Nền tảng Scikit-Learn (Phần 2: Đánh giá & Tinh chỉnh siêu tham số)
* **Thời lượng:** ~18–21 giờ (2.5–3h/ngày)
* **Nội dung:**
  - **Section 9 (Nửa sau) & Section 10:**
    - Đánh giá mô hình: Cross-validation, Confusion Matrix, Precision, Recall, F1-Score, ROC-AUC (Phân loại); MAE, MSE, $R^2$ (Hồi quy).
    - Tối ưu hóa siêu tham số (Hyperparameter Tuning): Thủ công, `RandomizedSearchCV`, `GridSearchCV`.
    - Lưu và tải mô hình với thư viện `joblib`.
    - Tạo Scikit-Learn Pipeline kết hợp tiền xử lý và mô hình hóa trong một dòng lệnh.
* **Mục tiêu đầu ra:** Notebook tổng hợp toàn bộ các kỹ thuật đánh giá và pipeline tối ưu trong `04-scikit-learn/`.

---

### 🗓️ Tuần 6: Milestone Project 1 – Phân loại dự đoán bệnh tim (Heart Disease)
* **Thời lượng:** ~18–20 giờ (2.5–3h/ngày)
* **Nội dung:**
  - **Section 11:** Triển khai một dự án Machine Learning từ đầu đến cuối (End-to-End Classification Project):
    - Định nghĩa bài toán phân loại nhị phân dựa trên dữ liệu lâm sàng.
    - Khám phá tương quan giữa các chỉ số sức khỏe và nguy cơ mắc bệnh (EDA).
    - So sánh đồng thời nhiều mô hình: Logistic Regression, K-Nearest Neighbors, Random Forest.
    - Tinh chỉnh mô hình tốt nhất với GridSearchCV, phân tích độ quan trọng của các biến (Feature Importance).
* **Mục tiêu đầu ra:** Hoàn thiện thư mục `05-milestone-project-1-heart-disease/` gồm notebook code chi tiết và báo cáo tóm tắt các chỉ số.

---

### 🗓️ Tuần 7: Milestone Project 2 – Dự đoán giá thiết bị đấu giá (Bulldozer Prices)
* **Thời lượng:** ~18–20 giờ (2.5–3h/ngày)
* **Nội dung:**
  - **Section 12:** Dự đoán chuỗi thời gian & Hồi quy (Time Series Regression):
    - Kỹ thuật phân tích đặc trưng thời gian (Feature Engineering: bóc tách năm, tháng, ngày, quý từ cột mốc thời gian).
    - Xử lý bộ dữ liệu lớn với hơn 400.000 dòng dữ liệu.
    - Đánh giá theo thước đo độ lỗi RMSLE (Root Mean Squared Log Error).
    - Giảm tải bộ nhớ và rút ngắn thời gian huấn luyện mô hình.
* **Mục tiêu đầu ra:** Hoàn thành project hồi quy `06-milestone-project-2-bulldozer-prices/` trên GitHub.

---

### 🗓️ Tuần 8: Kỹ nghệ Dữ liệu & Nhập môn Deep Learning với TensorFlow 2
* **Thời lượng:** ~18–20 giờ (2.5–3h/ngày)
* **Nội dung:**
  - **Section 13: Data Engineering:** Khái niệm ETL, luồng dữ liệu lớn, tổng quan kiến trúc dữ liệu.
  - **Section 14 (Phần 1): Deep Learning Basics:**
    - Khái niệm mạng nơ-ron nhân tạo (ANN), hàm kích hoạt (Activation functions), hàm mất mát (Loss functions), bộ tối ưu (Optimizers).
    - Xây dựng mô hình tuần tự cơ bản với Keras/TensorFlow.
* **Mục tiêu đầu ra:** Viết và huấn luyện được mạng nơ-ron nhiều lớp đầu tiên trên TensorFlow.

---

### 🗓️ Tuần 9: Transfer Learning & Thị giác máy tính (Computer Vision)
* **Thời lượng:** ~18–21 giờ (2.5–3h/ngày)
* **Nội dung:**
  - **Section 14 (Phần 2):**
    - Mạng nơ-ron tích chập (Convolutional Neural Networks - CNN) cơ bản.
    - Kỹ thuật **Transfer Learning**: Sử dụng lại các kiến trúc mạng đã được huấn luyện sẵn (Pre-trained models) để phân loại ảnh với độ chính xác cao mà không cần tài nguyên phần cứng lớn.
* **Mục tiêu đầu ra:** Notebook huấn luyện bài toán phân loại hình ảnh hoàn chỉnh lưu trong `07-deep-learning-tensorflow/`.

---

### 🗓️ Tuần 10: Kỹ năng Trình bày, Portfolio & Tối ưu hóa GitHub
* **Thời lượng:** ~15–18 giờ (2–3h/ngày)
* **Nội dung:**
  - **Section 15:** Nghệ thuật truyền tải kết quả (Storytelling & Communication) cho các bên liên quan không rành kỹ thuật.
  - **Section 16, 19, 20, 21:** Lời khuyên nghề nghiệp, định hướng toán học thống kê nâng cao và các bước phát triển tiếp theo.
  - **Hoàn thiện Portfolio:** Dọn dẹp code, thêm chú thích Markdown, hoàn thành toàn bộ checklist tiến độ bên dưới.
* **Mục tiêu đầu ra:** Một kho tài nguyên cá nhân hoàn chỉnh, chuyên nghiệp trên GitHub sẵn sàng đưa vào CV/LinkedIn.

---

## 📊 Bảng theo dõi tiến độ (Course Tracker)

Đánh dấu `[x]` vào từng mục sau khi hoàn thành bài học và commit code lên GitHub:

### Giai đoạn 1: Khởi động & Nền tảng
- [x] **Section 1: Introduction** *(5/5 bài | 16 phút)*
- [x] **Section 2: Machine Learning 101** *(11/11 bài | 45 phút)*
- [x] **Section 3: Machine Learning and Data Science Framework** *(15/15 bài | 1 giờ 08 phút)*
- [x] **Section 4: The 2 Paths** *(3/3 bài | 4 phút)*
- [ ] **Section 5: Data Science Environment Setup** *(2/13 bài | 1 giờ 48 phút)*

### Giai đoạn 2: Phân tích & Trực quan hóa dữ liệu
- [ ] **Section 6: Pandas: Data Analysis** *(0/15 bài | 1 giờ 39 phút)*
- [ ] **Section 7: NumPy** *(0/19 bài | 2 giờ 11 phút)*
- [ ] **Section 8: Matplotlib: Plotting and Data Visualization** *(0/20 bài | 2 giờ 18 phút)*

### Giai đoạn 3: Machine Learning với Scikit-Learn & Dự án thực tế
- [ ] **Section 9: Scikit-learn: Creating Machine Learning Models** *(0/52 bài | 7 giờ 56 phút)*
- [ ] **Section 10: Supervised Learning: Classification + Regression** *(0/1 bài | 1 phút)*
- [ ] **Section 11: Milestone Project 1: Supervised Learning (Classification - Heart Disease)** *(0/25 bài | 3 giờ 37 phút)*
- [ ] **Section 12: Milestone Project 2: Supervised Learning (Time Series Data - Bulldozer Prices)** *(0/21 bài | 3 giờ 13 phút)*
- [ ] **Section 13: Data Engineering** *(0/13 bài | 58 phút)*

### Giai đoạn 4: Deep Learning & Định hướng sự nghiệp
- [ ] **Section 14: Neural Networks: Deep Learning, Transfer Learning and TensorFlow 2** *(0/44 bài | 7 giờ 08 phút)*
- [ ] **Section 15: Storytelling + Communication: How To Present Your Work** *(0/8 bài | 27 phút)*
- [ ] **Section 16: Career Advice + Extra Bits** *(0/14 bài | 1 giờ 27 phút)*

### Giai đoạn 5: Phần bổ trợ
- [ ] **Section 17: Learn Python (Cơ bản)** *(0/49 bài | 4 giờ 11 phút)*
- [ ] **Section 18: Learn Python Part 2 (Nâng cao)** *(0/51 bài | 4 giờ 49 phút)*
- [ ] **Section 19: Extra: Learn Advanced Statistics and Mathematics** *(0/1 bài | 1 phút)*
- [ ] **Section 20: Where To Go From Here?** *(0/5 bài | 4 phút)*
- [ ] **Section 21: BONUS SECTION** *(0/1 bài | 1 phút)*

---

## 🗂️ Cấu trúc thư mục kho lưu trữ (Repository Structure)

```text
ztm-ai-ml-bootcamp/
│
├── 01-framework-and-setup/             # Ghi chú Framework ML 6 bước và cấu hình Conda
├── 02-numpy-pandas/                    # Notebooks thực hành Series, DataFrame & Vectorization
├── 03-matplotlib-visualization/        # Trực quan hóa dữ liệu (scatter, bar, hist, subplots)
├── 04-scikit-learn/                    # Quy trình tiền xử lý, huấn luyện, đánh giá & tuning
│
├── 05-milestone-project-1-heart-disease/
│   ├── data/                           # Bộ dữ liệu lâm sàng dự đoán bệnh tim
│   ├── heart-disease-prediction.ipynb  # Pipeline phân loại hoàn chỉnh (Classification)
│   └── README.md                       # Tóm tắt kết quả, ma trận nhầm lẫn & F1-score
│
├── 06-milestone-project-2-bulldozer-prices/
│   ├── data/                           # Dữ liệu đấu giá thiết bị công trình (Kaggle)
│   ├── bulldozer-price-regression.ipynb# Xử lý chuỗi thời gian & hồi quy đánh giá RMSLE
│   └── README.md
│
├── 07-deep-learning-tensorflow/        # Xây dựng mạng nơ-ron và mô hình Transfer Learning
│
├── .gitignore                          # Loại bỏ checkpoints, file rác và dữ liệu nặng
└── README.md                           # Trang tổng quan lộ trình học
```

---

## 💻 Thiết lập môi trường học tập

### 1. Khởi tạo môi trường Conda

```bash
# Tạo môi trường với Python 3.10
conda create -n ml-bootcamp python=3.10 -y

# Kích hoạt môi trường
conda activate ml-bootcamp

# Cài đặt các thư viện lõi
conda install numpy pandas matplotlib scikit-learn jupyter -y
pip install tensorflow
```

### 2. Sử dụng trên VS Code
1. Mở thư mục bài học trong VS Code: `code .`
2. Mở file `.ipynb` bất kỳ.
3. Nhấp vào nút **Select Kernel** ở góc trên bên phải màn hình và chọn `ml-bootcamp (Python 3.10)`.

---

## 👤 Tác giả

- **Học viên:** [@trungnguyen2411](https://github.com/trungnguyen2411)
- **Khóa học:** Complete A.I. & Machine Learning, Data Science Bootcamp (Zero To Mastery).