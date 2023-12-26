PHÂN MỀM HỖ TRỢ DỊCH CÁC NGÔN NGỮ

# NGUỒN GỐC Ý TƯỞNG:
- Mã nguồn chuyển hình ảnh sang dạng văn bản đa ngôn ngữ: Pytesseract
- link gitgub: https://github.com/tesseract-ocr/tesseract
- Mã nguồn hỗ trợ chuyển đổi các văn bản dạng hình ảnh sang dạng văn bản đối với rất nhiều các loại ngôn ngữ khác nhau trên thế giới
- Mã nguồn được thiết kế bằng ngôn ngữ java , c++
- Thuật toán sử dụng trong pytesseract:
+ OCR Engine: Sử dụng một cấu trúc mô hình LSTM (Long Short-Term Memory) cho việc nhận diện ký tự.
+ Quá trình Pre-processing: Các bước tiền xử lý hình ảnh để cải thiện chất lượng và chuẩn bị cho việc nhận diện văn bản.
+ Segmentation Algorithms: Các thuật toán phân đoạn để phân chia hình ảnh thành các phần văn bản, ký tự hoặc từ riêng biệt.
# Ý TƯỞNG THIẾT KẾ:
- Dịch các văn bản giữa các ngôn ngữ khác nhau
- Dịch được văn bản khi sử dụng dữ liệu đầu vào là 1 hình ảnh
- Dịch được văn bản khi chúng ta nói trực tiếp với phần mềm
- Lưu được kết quả sau khi dịch
  
