# Secure File Eraser

## Overview
Secure File Eraser is a powerful tool designed to permanently delete files from your system using military-grade erasing algorithms. Developed by **Namtran5905**, this application provides a user-friendly interface for securely erasing files, ensuring that sensitive data cannot be recovered. This tool is essential for individuals and organizations that prioritize data security and privacy.

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

## Developer
This application was developed by **Namtran5905**, a passionate developer dedicated to creating tools that enhance data security and privacy. For more information, please contact the developer.

---

# Công Cụ Xóa An Toàn

## Tổng Quan
Công Cụ Xóa An Toàn là một công cụ mạnh mẽ được thiết kế để xóa vĩnh viễn các tệp từ hệ thống của bạn bằng cách sử dụng các thuật toán xóa cấp độ quân sự. Được phát triển bởi **Namtran5905**, ứng dụng này cung cấp giao diện thân thiện với người dùng để xóa tệp an toàn, đảm bảo rằng dữ liệu nhạy cảm không thể được khôi phục. Công cụ này rất cần thiết cho các cá nhân và tổ chức ưu tiên bảo mật và quyền riêng tư dữ liệu.

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

## Nhà Phát Triển
Ứng dụng này được phát triển bởi **Namtran5905**, một nhà phát triển đam mê tạo ra các công cụ nâng cao bảo mật và quyền riêng tư dữ liệu. Để biết thêm thông tin, vui lòng liên hệ với nhà phát triển.

---

# セキュアファイルイレーサー

## 概要
セキュアファイルイレーサーは、軍事レベルの消去アルゴリズムを使用して、システムからファイルを永久に削除するために設計された強力なツールです。 **Namtran5905**によって開発されたこのアプリケーションは、ファイルを安全に削除するためのユーザーフレンドリーなインターフェースを提供します。このツールは、データセキュリティとプライバシーを重視する個人や組織にとって不可欠です。

## 機能
- **マルチフェーズ消去**: アプリケーションは、完全なデータ破壊を保証するために8段階の消去プロセスを採用しています。
- **ユーザーフレンドリーなインターフェース**: Tkinterで構築されたこのアプリケーションは、ファイルの選択と消去を簡単に行える直感的なGUIを提供します。
- **言語サポート**: 英語、ベトナム語、日本語、中国語、韓国語で利用可能で、言語間の切り替えが可能です。

## 安全なファイル削除の重要性
ファイルがコンピュータから削除されると、実際には削除されず、代わりに占有していたスペースが新しいデータに使用可能としてマークされます。これは、元のデータが専門のソフトウェアを使用して復元される可能性があることを意味します。セキュアファイルイレーサーは、データを複数回上書きすることでこの問題に対処し、復元できないようにします。

## アルゴリズム
セキュアファイルイレーサーは、安全なファイル削除のために次の8段階のアルゴリズムを使用します：

1. **フェーズ1**: ファイルは5つの部分に分割され、それぞれがランダムな文字で上書きされます。この初期ステップは、元のデータを隠すことを保証し、復元ツールが元の内容を特定するのを難しくします。
   
2. **フェーズ2**: ファイルはマージされ、異なるランダムな文字で上書きされます。これにより、データに追加のランダム性が導入され、復元の試みがさらに複雑になります。

3. **フェーズ3**: ファイル全体が単一のランダムな文字で上書きされ、元のデータの破壊を強化します。このステップにより、復元ツールがファイル構造を分析しようとした場合でも、均一な文字しか見つからないことが保証されます。

4. **フェーズ4**: ファイルはバイト`1`で上書きされ、データ復元プロセスにさらに複雑さを加えます。このステップは、データが隠されるだけでなく、既知の値で置き換えられることを保証します。

5. **フェーズ5**: ファイルは繰り返しパターン`10`で上書きされ、データ構造を隠すのに役立ちます。このパターンは、復元の試みをさらに複雑にする認識可能なシーケンスを導入します。

6. **フェーズ6**: ファイルは繰り返しパターン`0110`で上書きされ、元のデータが再構築できないようにします。このステップは、前のフェーズを強化し、さらに複雑さを加えます。

7. **フェーズ7**: ファイルはバイト`0`で上書きされ、上書きプロセスが完了します。この最終ステップは、データが既知の値で置き換えられることを保証し、復元をほぼ不可能にします。

8. **フェーズ8**: TRIMコマンドが送信され、SSD上のデータ削除が最適化され、ファイルが削除されます。このステップは、SSDが削除されたデータを効果的に管理できるようにするために重要です。

## 開発者
このアプリケーションは、データセキュリティとプライバシーを強化するツールを作成することに情熱を注ぐ**Namtran5905**によって開発されました。詳細については、開発者にお問い合わせください。

---

# 安全文件删除器

## 概述
安全文件删除器是一个强大的工具，旨在使用军用级别的删除算法永久删除系统中的文件。由**Namtran5905**开发的此应用程序提供了一个用户友好的界面，用于安全地删除文件，确保敏感数据无法恢复。此工具对于重视数据安全和隐私的个人和组织至关重要。

## 功能
- **多阶段删除**: 应用程序采用八阶段删除过程，以确保完全的数据销毁，使任何恢复软件几乎不可能检索已删除的文件。
- **用户友好的界面**: 使用Tkinter构建，应用程序提供直观的GUI，便于文件选择和删除，使用户能够轻松导航工具。
- **语言支持**: 提供英语、越南语、日语、中文和韩语，用户可以在语言之间切换，使其更易于更广泛的受众使用。

## 安全文件删除的重要性
当文件从计算机中删除时，它们并没有真正被删除; 相反，它们占用的空间被标记为可用于新数据。这意味着原始数据通常可以通过专门的软件恢复。安全文件删除器通过多次覆盖数据来解决此问题，确保无法以任何方式恢复。

## 算法
安全文件删除器使用以下八阶段算法进行安全文件删除：

1. **阶段1**: 文件被分成五个部分，每个部分用随机字符覆盖。这个初始步骤确保原始数据被遮蔽，使恢复工具难以识别原始内容。
   
2. **阶段2**: 文件被合并并用不同的随机字符覆盖。这进一步复杂化了任何潜在的恢复工作。

3. **阶段3**: 整个文件用单个随机字符覆盖，增强了原始数据的破坏。此步骤确保即使恢复工具试图分析文件结构，它们也只会找到一个均匀的字符。

4. **阶段4**: 文件用字节`1`覆盖，为数据恢复过程增加了另一层复杂性。此步骤至关重要，因为它确保数据不仅被遮蔽，而且被已知值替换。

5. **阶段5**: 文件用重复模式`10`覆盖，帮助遮蔽数据结构。此模式引入了一个可识别的序列，进一步复杂化恢复尝试。

6. **阶段6**: 文件用重复模式`0110`覆盖，确保原始数据无法重建。此步骤通过添加另一层复杂性来增强前面的阶段。

7. **阶段7**: 文件用字节`0`覆盖，完成覆盖过程。此最终步骤确保数据被已知值替换，使恢复几乎不可能。

8. **阶段8**: 发送TRIM命令以优化SSD上的数据删除，并删除文件。此步骤对于确保SSD能够有效管理已删除的数据至关重要。

## 开发者
此应用程序由**Namtran5905**开发，他是一位热衷于创建增强数据安全和隐私工具的开发者。如需更多信息，请联系开发者。
