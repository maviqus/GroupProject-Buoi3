Giải thích về xung đột merge

1) Vì sao conflict xảy ra?
- Conflict xảy ra khi hai (hoặc nhiều) contributor sửa cùng một phần của cùng một file (thường là cùng một dòng hoặc vùng code) trên hai branch khác nhau. Git không thể tự động quyết định nên giữ thay đổi nào nếu cả hai thay đổi đều sửa cùng một nội dung.

2) Cách hạn chế conflict
- Phân công rõ ràng: mỗi thành viên chịu trách nhiệm cho phần riêng (tôi là nhóm trưởng, các thành viên chỉ làm phần của mình), tránh sửa chồng lấn vào cùng một dòng.
- Pull thường xuyên: cập nhật nhánh của bạn từ nhánh chính (git pull/rebase) trước khi bắt đầu làm việc hoặc tạo PR.
- Tạo file/section riêng: nếu có thể, tách công việc thành file riêng hoặc sections rõ ràng.
- Thực hiện thay đổi nhỏ, commit thường xuyên: commit nhỏ giúp dễ rebase và review.
- Sử dụng feature flags hoặc config riêng: để cho phép code đồng thời tồn tại.

