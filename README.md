# Secure File Eraser

## Overview
Secure File Eraser is a powerful tool designed to permanently delete files from your system using military-grade erasing algorithms. This application provides a user-friendly interface for securely erasing files, ensuring that sensitive data cannot be recovered. This tool is essential for individuals and organizations that prioritize data security and privacy.

## Features
- **Multi-Phase Erasing**: The application employs an eight-phase erasing process to ensure complete data destruction, making it nearly impossible for any recovery software to retrieve the deleted files.
- **User-Friendly Interface**: Built with Tkinter, the application offers an intuitive GUI for easy file selection and erasure, allowing users to navigate the tool effortlessly.
- **Language Support**: Available in English, Vietnamese, Japanese, Chinese, and Korean, with the option to switch between languages, making it accessible to a wider audience.

## Importance of Secure File Deletion
When files are deleted from a computer, they are not truly erased; instead, the space they occupied is marked as available for new data. This means that the original data can often be recovered using specialized software. Secure File Eraser addresses this issue by overwriting the data multiple times, ensuring that it cannot be recovered by any means.

## Algorithms
The Secure File Eraser utilizes the following eight-phase algorithm for secure file deletion:

1. **Phase 1**: The file is divided into five parts, each overwritten with random characters. This initial step ensures that the original data is obscured, making it difficult for recovery tools to identify the original content.
   
2. **Phase 2**: The file is merged and overwritten with different random characters. This further complicates any potential recovery efforts by introducing additional randomness to the data.

3. **Phase 3**: The entire file is overwritten with a single random character, reinforcing the destruction of the original data. This step ensures that even if recovery tools attempt to analyze the file structure, they will only find a uniform character.

4. **Phase 4**: The file is overwritten with the byte `1`, adding another layer of complexity to the data recovery process. This step is crucial as it ensures that the data is not only obscured but also replaced with a known value.

5. **Phase 5**: The file is overwritten with a repeating pattern of `10`, which helps to obscure the data structure. This pattern introduces a recognizable sequence that further complicates recovery attempts.

6. **Phase 6**: The file is overwritten with a repeating pattern of `0110`, ensuring that the original data cannot be reconstructed. This step reinforces the previous phases by adding another layer of complexity.

7. **Phase 7**: The file is overwritten with the byte `0`, completing the overwriting process. This final step ensures that the data is replaced with a known value, making recovery virtually impossible.

8. **Phase 8**: The TRIM command is sent to optimize data deletion on SSDs, and the file is deleted. This step is crucial for ensuring that the SSD can effectively manage the deleted data, preventing any remnants from being recoverable.

# Công Cụ Xóa An Toàn

## Tổng Quan
Công Cụ Xóa An Toàn là một công cụ mạnh mẽ được thiết kế để xóa vĩnh viễn các tệp từ hệ thống của bạn bằng cách sử dụng các thuật toán xóa cấp độ quân sự. Ứng dụng này cung cấp giao diện thân thiện với người dùng để xóa tệp an toàn, đảm bảo rằng dữ liệu nhạy cảm không thể được khôi phục. Công cụ này rất cần thiết cho các cá nhân và tổ chức ưu tiên bảo mật và quyền riêng tư dữ liệu.

## Tính Năng
- **Xóa Nhiều Giai Đoạn**: Ứng dụng sử dụng quy trình xóa tám giai đoạn để đảm bảo tiêu hủy hoàn toàn dữ liệu, khiến cho bất kỳ phần mềm phục hồi nào cũng không thể khôi phục các tệp đã xóa.
- **Giao Diện Thân Thiện**: Được xây dựng bằng Tkinter, ứng dụng cung cấp GUI trực quan cho việc chọn và xóa tệp dễ dàng, cho phép người dùng điều hướng công cụ một cách dễ dàng.
- **Hỗ Trợ Ngôn Ngữ**: Có sẵn bằng tiếng Anh, tiếng Việt, tiếng Nhật, tiếng Trung và tiếng Hàn, với tùy chọn chuyển đổi giữa các ngôn ngữ, giúp công cụ dễ tiếp cận hơn với nhiều đối tượng.

## Tầm Quan Trọng của Việc Xóa Tệp An Toàn
Khi các tệp bị xóa khỏi máy tính, chúng không thực sự bị xóa; thay vào đó, không gian mà chúng chiếm giữ được đánh dấu là có sẵn cho dữ liệu mới. Điều này có nghĩa là dữ liệu gốc thường có thể được phục hồi bằng cách sử dụng phần mềm chuyên dụng. Công Cụ Xóa An Toàn giải quyết vấn đề này bằng cách ghi đè dữ liệu nhiều lần, đảm bảo rằng nó không thể được khôi phục bằng bất kỳ phương tiện nào.

## Thuật Toán
Công Cụ Xóa An Toàn sử dụng thuật toán xóa an toàn với tám giai đoạn như sau:

1. **Giai Đoạn 1**: Tệp được chia thành năm phần, mỗi phần được ghi đè bằng ký tự ngẫu nhiên. Bước khởi đầu này đảm bảo rằng dữ liệu gốc bị che khuất, làm cho các công cụ phục hồi khó xác định nội dung gốc.
   
2. **Giai Đoạn 2**: Tệp được gộp lại và ghi đè bằng các ký tự ngẫu nhiên khác nhau. Điều này làm phức tạp thêm bất kỳ nỗ lực phục hồi nào bằng cách giới thiệu thêm sự ngẫu nhiên vào dữ liệu.

3. **Giai Đoạn 3**: Toàn bộ tệp được ghi đè bằng một ký tự ngẫu nhiên duy nhất, củng cố việc tiêu hủy dữ liệu gốc. Bước này đảm bảo rằng ngay cả khi các công cụ phục hồi cố gắng phân tích cấu trúc tệp, chúng chỉ tìm thấy một ký tự đồng nhất.

4. **Giai Đoạn 4**: Tệp được ghi đè bằng byte `1`, thêm một lớp phức tạp cho quá trình phục hồi dữ liệu. Bước này rất quan trọng vì nó đảm bảo rằng dữ liệu không chỉ bị che khuất mà còn được thay thế bằng một giá trị đã biết.

5. **Giai Đoạn 5**: Tệp được ghi đè bằng mẫu lặp lại `10`, giúp che khuất cấu trúc dữ liệu. Mẫu này giới thiệu một chuỗi có thể nhận biết, làm cho các nỗ lực phục hồi thêm phức tạp.

6. **Giai Đoạn 6**: Tệp được ghi đè bằng mẫu lặp lại `0110`, đảm bảo rằng dữ liệu gốc không thể được tái tạo. Bước này củng cố các giai đoạn trước bằng cách thêm một lớp phức tạp khác.

7. **Giai Đoạn 7**: Tệp được ghi đè bằng byte `0`, hoàn thành quá trình ghi đè. Bước cuối cùng này đảm bảo rằng dữ liệu được thay thế bằng một giá trị đã biết, làm cho việc phục hồi gần như không thể.

8. **Giai Đoạn 8**: Lệnh TRIM được gửi để tối ưu hóa việc xóa dữ liệu trên SSD và tệp được xóa. Bước này rất quan trọng để đảm bảo rằng SSD có thể quản lý hiệu quả dữ liệu đã xóa, ngăn chặn bất kỳ dấu vết nào có thể được phục hồi.
