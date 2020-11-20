# lab21 - Xây dựng ứng dụng cho người mới bắt đầu

## Giới thiệu về các widget
Trong thiết kế giao diện người dùng, đối với Flutter thì mọi thành phần giao diện đều được gọi là widget (vật dụng), một giao diện người dùng được tạo bởi các widget lồng vào nhau. Nếu tưởng tượng bức tranh xếp bằng lego thì mỗi mảnh ghép lego là một vật dụng (widget).
Các widget mô tả chế độ xem ở mỗi trạng thái khác nhau những thay đổi cần thiết ở mỗi trạng thái sẽ được vẽ lại để làm mới giao diện.
### Thực hiện
Sinh viên hãy tạo một flutter project và đặt tên là lab21. Sau đó xóa hết các nội dung ở tệp ```lib > main.dart``` rồi viết vào mã sau đây để bắt đầu với một giao diện trống rỗng. Từ đó, sinh viên hãy thêm các thành phần giao diện vào theo gợi ý ở các đoạn mã được liệt kê trong bài thực hành này. Biên dịch và xem kết quả, chụp kết quả cho vào tệp README.md của project rồi đẩy toàn bộ lên github của mình.
**Tệp main.dart ban đầu**
```dart
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        /// Các thành phần giao diện sẽ được thêm vào ở đây
      ),
    );
  }
}
```
Sinh viên hãy tiếp tục hành thực hành theo tài liệu ở đây https://flutter.dev/docs/development/ui/widgets-intro

Sau mỗi lần thực hiện thành công hãy commit và push lên github của cá nhân
