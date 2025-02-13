# Secure File Eraser

## Tổng Quan
Secure File Eraser là một công cụ mạnh mẽ được thiết kế để xóa vĩnh viễn các tệp từ hệ thống của bạn. Ứng dụng này cung cấp giao diện thân thiện với người dùng để xóa tệp an toàn, đảm bảo rằng dữ liệu nhạy cảm không thể được khôi phục. Công cụ này rất cần thiết cho các cá nhân và tổ chức ưu tiên bảo mật và quyền riêng tư dữ liệu.

## Tính Năng
- **Xóa Nhiều Giai Đoạn**: Ứng dụng sử dụng quy trình xóa tám giai đoạn để đảm bảo tiêu hủy hoàn toàn dữ liệu, khiến cho bất kỳ phần mềm phục hồi nào cũng không thể khôi phục các tệp đã xóa.
- **Giao Diện Thân Thiện**: Được xây dựng bằng Tkinter, ứng dụng cung cấp GUI trực quan cho việc chọn và xóa tệp dễ dàng, cho phép người dùng điều hướng công cụ một cách dễ dàng.
- **Hỗ Trợ Ngôn Ngữ**: Có sẵn bằng tiếng Anh, tiếng Việt với tùy chọn chuyển đổi giữa các ngôn ngữ, giúp công cụ dễ tiếp cận hơn với nhiều đối tượng.

## Tầm Quan Trọng của Việc Xóa Tệp An Toàn
Khi các tệp bị xóa khỏi máy tính, chúng không thực sự bị xóa; thay vào đó, không gian mà chúng chiếm giữ được đánh dấu là có sẵn cho dữ liệu mới. Điều này có nghĩa là dữ liệu gốc thường có thể được phục hồi bằng cách sử dụng phần mềm chuyên dụng. Công Cụ Xóa An Toàn giải quyết vấn đề này bằng cách ghi đè dữ liệu nhiều lần, đảm bảo rằng nó không thể được khôi phục bằng bất kỳ phương tiện nào.

## Thuật Toán
Secure File Eraser sử dụng thuật toán xóa an toàn với tám giai đoạn như sau:

1. **Giai Đoạn 1**: Tệp được chia thành năm phần, mỗi phần được ghi đè bằng ký tự ngẫu nhiên. Bước khởi đầu này đảm bảo rằng dữ liệu gốc bị che khuất, làm cho các công cụ phục hồi khó xác định nội dung gốc.
   
2. **Giai Đoạn 2**: Tệp được gộp lại và ghi đè bằng các ký tự ngẫu nhiên khác nhau. Điều này làm phức tạp thêm bất kỳ nỗ lực phục hồi nào bằng cách giới thiệu thêm sự ngẫu nhiên vào dữ liệu.

3. **Giai Đoạn 3**: Toàn bộ tệp được ghi đè bằng một ký tự ngẫu nhiên duy nhất, củng cố việc tiêu hủy dữ liệu gốc. Bước này đảm bảo rằng ngay cả khi các công cụ phục hồi cố gắng phân tích cấu trúc tệp, chúng chỉ tìm thấy một ký tự đồng nhất.

4. **Giai Đoạn 4**: Tệp được ghi đè bằng byte `1`, thêm một lớp phức tạp cho quá trình phục hồi dữ liệu. Bước này rất quan trọng vì nó đảm bảo rằng dữ liệu không chỉ bị che khuất mà còn được thay thế bằng một giá trị đã biết.

5. **Giai Đoạn 5**: Tệp được ghi đè bằng mẫu lặp lại `10`, giúp che khuất cấu trúc dữ liệu. Mẫu này giới thiệu một chuỗi có thể nhận biết, làm cho các nỗ lực phục hồi thêm phức tạp.

6. **Giai Đoạn 6**: Tệp được ghi đè bằng mẫu lặp lại `0110`, đảm bảo rằng dữ liệu gốc không thể được tái tạo. Bước này củng cố các giai đoạn trước bằng cách thêm một lớp phức tạp khác.

7. **Giai Đoạn 7**: Tệp được ghi đè bằng byte `0`, hoàn thành quá trình ghi đè. Bước cuối cùng này đảm bảo rằng dữ liệu được thay thế bằng một giá trị đã biết, làm cho việc phục hồi gần như không thể.

8. **Giai Đoạn 8**: Lệnh TRIM được gửi để tối ưu hóa việc xóa dữ liệu trên SSD và tệp được xóa. Bước này rất quan trọng để đảm bảo rằng SSD có thể quản lý hiệu quả dữ liệu đã xóa, ngăn chặn bất kỳ dấu vết nào có thể được phục hồi.
