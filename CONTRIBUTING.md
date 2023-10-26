# Hướng dẫn đóng góp

Chào mừng bạn đến với dự án của chúng tôi và cảm ơn vì bạn quyết định đóng góp vào sự phát triển của nó. Dưới đây là hướng dẫn chi tiết về cách đóng góp và quy trình thực hiện.

## 1. Fork Repo

Trước tiên, bạn cần tạo một bản sao của kho lưu trữ của chúng tôi vào tài khoản GitHub của bạn. Điều này có thể được thực hiện bằng cách nhấn vào nút "Fork" ở góc trên bên phải của trang repo của chúng tôi. Sau đó, bạn sẽ có một bản sao của dự án trong tài khoản GitHub cá nhân của bạn.

## 2. Clone Repo

Sao chép repo đã fork về máy tính của bạn bằng cách sử dụng URL repo của bạn:

```bash
git clone <URL của repo bạn đã fork>
cd <tên repo>
```

## 3. Tạo và kiểm tra nhánh

Trước khi bạn thực hiện bất kỳ thay đổi nào, hãy tạo một nhánh mới để làm việc:

```bash
git checkout -b ten-nhanh-moi
```

## 4. Thực hiện thay đổi

Bây giờ, bạn có thể thực hiện các thay đổi bạn muốn đóng góp. Xin vui lòng tuân thủ theo các quy tắc và hướng dẫn về mã lệnh và cấu trúc dự án của chúng tôi.

## 5. Commit và Push

Sau khi bạn đã thực hiện các thay đổi, sử dụng các lệnh sau để commit và đẩy chúng lên repo của bạn:

```bash
git add .
git commit -m "Mô tả thay đổi của bạn"
git push origin ten-nhanh-moi
```

## 6. Tạo Pull Request

Trở lại trang repo gốc trên GitHub của chúng tôi. Bạn sẽ thấy thông báo về nhánh mới mà bạn đã đẩy lên. Nhấn vào nút "Compare & pull request". Hãy cung cấp mô tả chi tiết về các thay đổi của bạn và nhấn "Create pull request".

## 7. Xem xét và Merge

Chúng tôi sẽ xem xét Pull Request của bạn và thảo luận về nó. Nếu mọi thứ ok, chúng tôi sẽ hợp nhất nó vào dự án gốc.

## 8. Cảm ơn!

Cảm ơn bạn đã đóng góp vào dự án của chúng tôi. Sự đóng góp của bạn đóng một vai trò quan trọng trong việc phát triển dự án và làm cho nó tốt hơn. Nếu bạn có bất kỳ câu hỏi hoặc cần sự giúp đỡ, hãy liên hệ với chúng tôi qua các cách mà chúng tôi đã liệt kê trong tệp README hoặc qua trang Issues của dự án.

Hãy bắt đầu và chúng ta cùng làm việc để tạo ra điều tuyệt vời!
