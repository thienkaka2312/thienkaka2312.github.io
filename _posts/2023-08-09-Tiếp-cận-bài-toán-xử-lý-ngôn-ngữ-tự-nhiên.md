<h1 align="center"> <p>Tiếp cận một bài toán xử lý ngôn ngữ tự nhiên</p></h1>
Ngôn ngữ tự nhiên là ngôn ngữ mà con người giao tiếp với nhau hàng ngày. Thông qua ngôn ngữ con người có thể trao đổi thông tin với nhau và có thể hiểu được nhau. Nhưng máy tính không thể hiểu được ngôn ngữ của con người, chúng chỉ hiểu thông tin ở dạng bit. Vì thế để con người có thể giao tiếp với máy tính chúng ta cần xử lý chuyển đổi biểu diễn ngôn ngữ của chúng ta sang cách mà máy móc có thể hiểu được.

## Các bước cơ bản
Đầu vào của các bài toán xử lý ngôn ngữ tự nhiên thường ở dạng văn bản. Để giải quyết bài toán chúng ta cần xác định dạng bài toán : Phân loại văn bản, tóm tắt văn bản, dịch ngôn ngữ, trả lời câu hỏi ...

Hiện nay có 2 hướng chính để giải quyết các bài toán về xử lý ngôn ngữ tự nhiên đó là fine-tuning từ một mô hình ngôn ngữ lớn (LLMs) hoặc promt engineering.

Chúng ta sẽ bắt đầu bằng hướng fine-tuning. Fine-tuning là từ một pre-trained LLMs chúng ta sẽ training lại model đó trên dữ liệu của bài toán chúng ta cần làm.Lợi thế của fine-tuning là chúng ta không cần phải train lại model ngay từ đầu, mà sử dụng lại model đã được train ở trên một tập dữ liệu lớn, chúng ta chỉ cần phải update lại tham số của models để phù hợp với dữ liệu bài toán chúng ta cần giải quyết.
