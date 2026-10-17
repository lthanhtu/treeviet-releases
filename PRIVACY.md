# Chính sách quyền riêng tư — TreeViet

*Cập nhật: 17/10/2026*

**TreeViet không thu thập, không lưu trữ và không gửi dữ liệu của bạn cho Nhà phát hành.** Ứng dụng không có telemetry, không thống kê sử dụng (analytics), không gửi báo cáo lỗi tự động, không quảng cáo và không theo dõi. TreeViet không có máy chủ riêng để nhận dữ liệu của bạn.

## Dữ liệu nằm trên máy của bạn
Mọi dữ liệu do ứng dụng tạo ra chỉ được lưu trên máy của bạn và bạn có thể xoá bất kỳ lúc nào:
- Hồ sơ (profiles), cài đặt, danh sách repository gần đây và workspace.
- SSH config riêng của từng hồ sơ và token tài khoản HTTPS (lưu trong tệp chỉ tài khoản người dùng trên máy đọc được).
- Key bản quyền và email kích hoạt — được **kiểm tra ngay trên máy**, không gửi đi đâu.
- Bộ nhớ đệm avatar.

Ứng dụng không đọc hay gửi nội dung mã nguồn của bạn đi đâu ngoài các thao tác Git do chính bạn thực hiện.

## Các kết nối mạng (đều do bạn chủ động, đi thẳng tới dịch vụ bạn dùng)
| Khi nào | Kết nối tới | Gửi gì |
|---|---|---|
| Fetch / pull / push / clone, tự động fetch (có thể tắt) | Máy chủ Git của repository (GitHub, GitLab…) | Như lệnh `git` thông thường, dùng thông tin đăng nhập của bạn |
| Hiển thị avatar tác giả (có thể tắt trong Cài đặt) | GitHub / GitLab của repository; Gravatar | Email tác giả commit (tới GitHub/GitLab, kèm thông tin đăng nhập HTTPS mà git trên máy đã lưu cho chính máy chủ đó, nếu có — để đọc được repository riêng tư); mã băm SHA-256 của email (tới Gravatar) |
| Bạn thêm tài khoản và bấm "Kiểm tra" token | API của nhà cung cấp bạn chọn | Token bạn nhập, chỉ để xác minh |
| Mở repository ở bản miễn phí | Máy chủ Git của repository | Kiểm tra ẩn danh repository có công khai không (không gửi thông tin đăng nhập) |
| Bạn bấm mở một liên kết | Trình duyệt của bạn | — |

Các dịch vụ trên (GitHub, GitLab, Gravatar…) có chính sách quyền riêng tư riêng của họ.

## Liên hệ
gittreeviet@gmail.com

---

# Privacy Policy — TreeViet

**TreeViet does not collect, store or send your data to the Publisher.** There is no telemetry, no usage analytics, no automatic crash reporting, no ads and no tracking. TreeViet operates no server that receives your data.

All data the app creates (profiles, settings, recent repositories, workspaces, per-profile SSH config and HTTPS tokens, the license key and activation email, avatar cache) stays on your device. License keys are verified locally.

The app only connects to services you use, when you use them: your Git remotes (fetch/pull/push/clone, optional auto-fetch); GitHub/GitLab and Gravatar for author avatars (optional — sends commit author emails, with the HTTPS credential git already stores for that same host if any, / a SHA-256 email hash); a provider's API when you verify an account token; an anonymous check whether a repository is public (free plan); and your browser when you open a link.

Contact: gittreeviet@gmail.com
