# Đề tài 1: Phân loại cảm xúc từ phản hồi của sinh viên

## Thành phần
- `De_tai_1_Phan_loai_cam_xuc.ipynb`: notebook EDA, tiền xử lý, huấn luyện và đánh giá.
- `student_feedback_dataset.csv`: dữ liệu được cung cấp.
- `Bao_cao_de_tai_1.docx`: bản thảo báo cáo.
- `requirements.txt`: thư viện cần thiết.

## Cách chạy
1. Cài Python 3.10 trở lên.
2. Chạy `pip install -r requirements.txt`.
3. Đặt CSV cùng thư mục notebook.
4. Mở notebook bằng Jupyter hoặc Google Colab và chạy lần lượt các cell.

## Thiết lập tái lập
- Test size: 20%.
- Random state: 42.
- Chia tập có stratify theo `sentiment_label`.
- Vectorizer được fit bên trong Pipeline chỉ trên tập train.

## Lưu ý
Kết quả cần được chạy lại trên môi trường thực tế trước khi nộp. Báo cáo trình bày kết quả thử nghiệm tham chiếu trên bộ dữ liệu được cung cấp.
