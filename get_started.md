# Bắt đầu thôi nào!

Dưới đây là các bước để tạo một dự án từ Visual Studio Code (VSCode), chứa một bài viết, và sau đó đẩy nó lên GitHub:

## Tạo một thư mục mới cho dự án của bạn:
* Mở Terminal trong VSCode (`View -> Terminal`).
* Tạo một thư mục mới bằng cách sử dụng lệnh mkdir, ví dụ: `mkdir my_project`.
* Di chuyển vào thư mục mới vừa tạo bằng lệnh cd, ví dụ: `cd my_project`.
## Tạo một bài viết mới:
* Trong thư mục dự án, tạo một tệp mới cho bài viết của bạn, ví dụ: `get_stated.md`
* Mở tệp này và bắt đầu viết bài của bạn.
## Khởi tạo một kho lưu trữ Git:
* Trong Terminal, khởi tạo một kho lưu trữ Git mới bằng lệnh `git init`.
## Thêm và commit bài viết của bạn:
* Thêm tệp bài viết vào kho lưu trữ Git bằng lệnh `git add get_stated.md`.
* Commit thay đổi của bạn bằng lệnh `git commit -m "Add my first article"`.
## Tạo một kho lưu trữ trên GitHub:
* Đi đến trang GitHub của bạn và tạo một kho lưu trữ mới.
* Đảm bảo rằng bạn không chọn tùy chọn “*Initialize this repository with a README*” vì bạn đã khởi tạo một kho lưu trữ trên máy tính cục bộ của bạn.
## Đẩy dự án của bạn lên GitHub:
* Trên trang của kho lưu trữ mới trên GitHub, sao chép URL dưới dạng “**HTTPS**”.
* Trở lại Terminal trong VSCode, thêm URL này như một remote bằng lệnh `git remote add origin YOUR_GITHUB_REPO_URL`.
* Cuối cùng, đẩy dự án của bạn lên GitHub bằng lệnh `git push -u origin master`.

Vậy là bạn đã tạo và đẩy một dự án chứa một bài viết lên GitHub từ VSCode! Hãy nhớ thay `YOUR_GITHUB_REPO_URL` bằng `URL` thực tế của kho lưu trữ GitHub của bạn. Chúc bạn thành công! 😊 (Nguồn: Copilot)
