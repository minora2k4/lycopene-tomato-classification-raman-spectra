## 📌 Project Summary

**[EN]**  
This project is conducted as a **Bachelor’s Graduation Thesis** at the  
**University of Science – Vietnam National University, Hanoi (VNU-HUS)**.

It presents a **comprehensive and closed-loop research pipeline** for **quantifying and classifying lycopene content in tomatoes** by integrating **Raman spectroscopy** with **machine learning models**.  
The study follows an **interdisciplinary approach** combining **Physics, Chemistry, and Data Science**, covering all stages from theoretical background, experimental measurement setup, data acquisition and preprocessing, to model optimization and evaluation.

A Raman spectral dataset was constructed for the tomato cultivar **“Tomato VA 390”**, cultivated in the Hanoi area. Ground-truth lycopene labels were determined using standard **UV–Vis chemical analysis**, while Raman spectra were collected using a **532 nm excitation laser**. Thanks to the resonance Raman effect, characteristic lycopene peaks around **1156 cm⁻¹** and **1510 cm⁻¹** were clearly observed directly on fresh tomato samples without destructive treatment, demonstrating the feasibility of **rapid, non-invasive measurement**.

From a data processing and modeling perspective, the thesis applies spectral preprocessing and uses **SHAP** to identify key Raman regions associated with lycopene. Guided by SHAP analysis, a **controlled data augmentation strategy around regions of interest** was introduced to mitigate data scarcity and improve model robustness.  
Three machine learning models—**Logistic Regression, SVM, and XGBoost**—were evaluated. Results indicate that under limited but well-processed spectral data conditions, the **linear Logistic Regression model achieves the best performance**, with **Balanced Accuracy = 0.8333** and **F1-Macro = 0.8413**. This suggests a strong linear relationship between Raman scattering intensity and lycopene concentration, consistent with fundamental spectroscopic principles.

> **Workflow:**  
> Preprocessing → Default-parameter models → SHAP-based region selection → Data augmentation around ROIs → Grid-search optimized models  
>
> **Note:** All source code files in this repository include **Vietnamese comments** for academic and educational purposes.

---

## 📌 Tóm tắt dự án

**[VI]**  
Đây là **khóa luận tốt nghiệp Cử nhân** được thực hiện tại  
**Trường Đại học Khoa học Tự nhiên – Đại học Quốc gia Hà Nội (ĐHQGHN)**.

Khóa luận trình bày một **quy trình nghiên cứu toàn diện và khép kín** nhằm **định lượng và phân loại hàm lượng lycopene trong quả cà chua** thông qua việc kết hợp **công nghệ quang phổ Raman** với **các mô hình học máy**. Nghiên cứu được triển khai theo hướng **liên ngành giữa Vật lý, Hóa học và Khoa học dữ liệu**, bao phủ đầy đủ các giai đoạn từ cơ sở lý thuyết, thiết lập hệ đo, thu thập và xử lý dữ liệu, cho đến tối ưu hóa và đánh giá mô hình.

Bộ dữ liệu quang phổ Raman được xây dựng cho giống cà chua **“Tomato VA 390”** trồng tại khu vực Hà Nội. Nhãn hàm lượng lycopene được xác định bằng phương pháp **UV–Vis tiêu chuẩn**, trong khi tín hiệu Raman được thu nhận với **nguồn laser kích thích 532 nm**. Nhờ hiệu ứng cộng hưởng Raman, các đỉnh phổ đặc trưng của lycopene tại khoảng **1156 cm⁻¹** và **1510 cm⁻¹** được quan sát rõ ràng ngay trên mẫu quả tươi, không cần xử lý phá hủy, khẳng định tính khả thi của phương pháp đo nhanh và không xâm lấn.

Về xử lý dữ liệu và mô hình hóa, khóa luận áp dụng quy trình tiền xử lý phổ và sử dụng **SHAP** để xác định các vùng phổ quan trọng liên quan đến lycopene. Dựa trên các vùng quan tâm này, chiến lược **tăng cường dữ liệu có kiểm soát** được triển khai nhằm khắc phục tình trạng khan hiếm dữ liệu và nâng cao độ ổn định của mô hình.  
Ba mô hình học máy gồm **Hồi quy Logistic, SVM và XGBoost** được so sánh. Kết quả cho thấy trong điều kiện dữ liệu phổ có kích thước nhỏ nhưng được xử lý hợp lý, **mô hình Hồi quy Logistic cho hiệu năng tốt nhất**, đạt **Balanced Accuracy = 0.8333** và **F1-Macro = 0.8413**, phản ánh mối quan hệ tuyến tính mạnh giữa cường độ tán xạ Raman và hàm lượng lycopene, phù hợp với các nguyên lý quang phổ học cơ bản.

> **Quy trình thực hiện:**  
> Tiền xử lý → Huấn luyện mô hình với tham số mặc định → SHAP xác định vùng quan tâm → Tăng cường dữ liệu quanh vùng quan tâm → Tối ưu mô hình bằng Grid Search  
>
> **Lưu ý:** Toàn bộ các file mã nguồn trong repository đều có **comment bằng tiếng Việt**, phục vụ mục đích học thuật và đào tạo.
