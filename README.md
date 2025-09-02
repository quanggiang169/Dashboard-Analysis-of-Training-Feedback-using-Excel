# Dự án: Phân tích Feedback Training & Dashboard Excel

## Giới thiệu

Dự án này tập trung vào việc **phân tích dữ liệu phản hồi từ học viên** và xây dựng một **dashboard động trong Excel**. Mục tiêu là giúp HR hoặc trainer **giám sát hiệu quả các khóa đào tạo bắt buộc** về an toàn lao động và sơ cấp cứu trong môi trường sản xuất, đồng thời **nhanh chóng nhận diện các vấn đề và điểm mạnh** của chương trình đào tạo.

Các file chính:  
- `Feedback_Raw_Data.xlsx`: dữ liệu gốc phản hồi của học viên sau mỗi khóa học.  
- `Training_Feedback_Dashboard.xlsx`: tổng hợp KPI và biểu đồ trực quan, hỗ trợ HR/trainer ra quyết định cải thiện chương trình đào tạo.

## Workflow tổng quan

1. **Chuyển đổi dữ liệu dạng chữ thành số hóa**  
   - Các câu trả lời đánh giá thỏa mãn được chuyển thành số để tính toán các chỉ số trung bình.  

2. **Khai thác dữ liệu dạng text từ phần bình luận**  
   - Tổng hợp các phản hồi mở từ học viên để nhận diện các ý kiến về nội dung khóa học, phương pháp giảng dạy, hoặc các khía cạnh khác của đào tạo.  

3. **Tính toán KPI và phân tích dữ liệu**  
   - Điểm thỏa mãn trung bình tổng thể của khóa đào tạo.  
   - Điểm thỏa mãn ở các khía cạnh cụ thể của đào tạo.  

4. **Vẽ dashboard trực quan**  
   - Pivot Table và biểu đồ (Bar chart, Pie chart) hiển thị KPI theo lớp và toàn bộ khóa học.  
   - Dashboard trả lời các câu hỏi chính:  
     - Nhìn chung độ thỏa mãn của khóa đào tạo thế nào?   
     - Khía cạnh nào cần cải thiện?  
     - Điểm thỏa mãn ở các khía cạnh đào tạo ra sao?
     - Feedback nhận được là gì, cụ thể ra sao?
