0. “Lần gần nhất bạn không hiểu một phần bài là khi nào?”
Khoảng ba ngày trước, lúc mình học phần backpropagation trong môn Machine Learning. Mình hiểu ý tưởng chung là cập nhật trọng số để giảm loss, nhưng đến đoạn tính gradient qua nhiều layer thì mình không theo được nữa.

1. “Bạn đang cố hiểu hoặc làm được điều gì?”
Lúc đó mình đang cố hiểu cách tính đạo hàm từ loss ngược về từng layer để sau đó tự làm bài tập. Mục tiêu của mình không phải chỉ nhớ công thức mà là nhìn vào một network đơn giản rồi tự tính được gradient.

2. “Chỗ nào cụ thể làm bạn bị kẹt?”
Mình bị kẹt ở bước dùng chain rule. Slide nhảy khá nhanh từ công thức loss sang một chuỗi đạo hàm, nhưng mình không hiểu tại sao các đạo hàm lại được nhân với nhau theo thứ tự đó. Mình đọc lại đoạn đó khoảng ba lần nhưng vẫn không nối được các bước.

3. “Sau khi xử lý, bạn thấy nguyên nhân là gì?”
Sau đó mình mới nhận ra vấn đề chính không phải backpropagation mà là mình đã quên khá nhiều về chain rule của đạo hàm hàm hợp. Ban đầu mình cứ nghĩ mình không hiểu thuật toán backpropagation nên mình tìm video giải thích backpropagation, nhưng mấy video đầu tiên vẫn khó hiểu như cũ.

4. “Có phải bạn thiếu một kiến thức/bước nền nào không? Bạn phát hiện điều đó như thế nào?”
Có. Trong lúc xem một video khác, người dạy dừng lại và viết một ví dụ rất đơn giản về chain rule trước khi nói đến neural network. Đến đoạn đó mình mới nhận ra mình không giải thích được tại sao dy/dx lại được tách thành dy/du nhân du/dx. Mình quay lại xem lại chain rule khoảng 15–20 phút rồi mới quay lại phần backpropagation.

5. “Hay bạn chỉ cần ví dụ, cách giải thích khác, thêm bối cảnh hoặc hỏi người khác?”
Trong trường hợp đó mình cần cả kiến thức nền và một ví dụ đơn giản hơn. Chỉ đọc lại slide không giúp nhiều. Sau khi ôn chain rule, mình xem một ví dụ network chỉ có một neuron và tự viết từng bước đạo hàm ra giấy. Ví dụ đó giúp mình hiểu phần đang học hơn.

6. “Cách bạn đã dùng có giải quyết đúng nguyên nhân không?”
Khá đúng. Sau khi ôn lại chain rule và làm ví dụ đơn giản, mình quay lại bài tập ban đầu và làm được phần lớn các bước mà không cần nhìn lời giải. Nhưng mình vẫn phải kiểm tra lại một bước tính gradient vì chưa chắc dấu âm từ đâu ra.

7. “Có lần nào bạn thử ôn lại nhưng vẫn không hiểu không?”
Có. Trước đó mình từng học một phần về attention và nghĩ là mình thiếu kiến thức về matrix multiplication nên quay lại xem phần đó. Nhưng xem xong mình vẫn không hiểu attention. Sau đó hỏi một người bạn thì mới phát hiện mình đang nhầm ý nghĩa của query, key và value chứ không phải không biết nhân ma trận. Tức là lần đó mình tự đoán sai nguyên nhân nên ôn lại không giúp nhiều.
