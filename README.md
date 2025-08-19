📌 Giới thiệu

Dự án HR Attrition Analytics tập trung phân tích dữ liệu nhân sự nhằm tìm hiểu đặc điểm hồ sơ nhân viên, đo lường tỷ lệ nghỉ việc (Attrition Rate), xác định các yếu tố ảnh hưởng đến việc nhân viên rời bỏ tổ chức và đưa ra đề xuất cải thiện. Dữ liệu được tiền xử lý bằng Python để đảm bảo sạch và nhất quán, sau đó được trực quan hóa bằng Power BI để tạo ra dashboard hỗ trợ ra quyết định cho phòng Nhân sự và Ban lãnh đạo.

⚙️ Quy trình

Tiền xử lý dữ liệu (Python Notebook)

Kiểm tra và xử lý giá trị thiếu.

Chỉnh sửa cột Company Tenure  phù hợp với logic thực tế.

Xuất dữ liệu đã làm sạch sang định dạng CSV để dùng cho Power BI.

Phân tích & Trực quan hóa (Power BI)

Trang Overview: KPI chính (Attrition Rate, số lượng nhân viên), phân bổ nhân viên theo độ tuổi, giới tính, trình độ, bộ phận.

Trang Attrition Details: so sánh nhóm nhân viên ở lại và rời đi theo thu nhập, thâm niên, số lần thăng chức, khoảng cách đi làm.

Trang Risk Factors: phân tích tỷ lệ nghỉ việc theo Work-Life Balance, Overtime, Job Satisfaction, Job Level.

Trang Recommendations (tùy chọn): đề xuất hành động cải thiện dựa trên insight.

💡 Insight rút ra

Nhân viên Entry-level có tỷ lệ nghỉ việc cao hơn hẳn so với Mid-level và Senior.

Work-Life Balance kém và Overtime thường xuyên là hai yếu tố nổi bật làm tăng rủi ro nghỉ việc.

Nhân viên rời đi thường có thu nhập thấp hơn, ít cơ hội thăng tiến, và thời gian gắn bó với công ty ngắn.

Nhóm nhân viên có hiệu suất tốt nhưng không được ghi nhận/đánh giá cao cũng thể hiện tỷ lệ nghỉ việc cao.

📊 Từ những insight này, tổ chức nên tập trung vào:

Cải thiện trải nghiệm của nhân viên Entry-level (mentorship, đào tạo, cơ hội thăng tiến).

Giảm thiểu tình trạng làm thêm giờ, cân bằng công việc – cuộc sống.

Tăng cường ghi nhận và khen thưởng nhân viên để giữ chân nhân tài.

**Dashboard**

<img width="1185" height="747" alt="image" src="https://github.com/user-attachments/assets/62dd5efb-61cb-4645-a292-d444e3616f57" />
<img width="1179" height="737" alt="image" src="https://github.com/user-attachments/assets/5e61782f-c9a5-4ad8-96d2-aa8392c8193a" />

