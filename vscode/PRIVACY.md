# Chính sách quyền riêng tư — TreeViet for Git (VS Code extension)

*Cập nhật: 18/10/2026*

**TreeViet không thu thập, không lưu trữ và không gửi dữ liệu của bạn cho Nhà phát hành.** Extension không có telemetry, không thống kê sử dụng (analytics), không gửi báo cáo lỗi tự động, không quảng cáo và không theo dõi. Extension **không dùng telemetry của VS Code**. TreeViet không có máy chủ riêng để nhận dữ liệu của bạn.

## Dữ liệu nằm trên máy của bạn
Mọi dữ liệu do extension tạo ra chỉ được lưu trên máy chạy extension (với Remote SSH / WSL / container: máy đó) trong thư mục lưu trữ riêng mà VS Code cấp cho extension (global storage), và bị xoá khi bạn gỡ extension:
- Hồ sơ (profiles), cài đặt, danh sách repository gần đây, tab đang mở và workspace.
- SSH config riêng của từng hồ sơ và token tài khoản HTTPS (lưu trong tệp chỉ tài khoản người dùng trên máy đọc được).
- Key bản quyền và email kích hoạt — được **kiểm tra ngay trên máy**, không gửi đi đâu.
- Bộ nhớ đệm avatar và kết quả kiểm tra repository công khai/riêng tư.

Extension không đọc hay gửi nội dung mã nguồn của bạn đi đâu ngoài các thao tác Git do chính bạn thực hiện.

## Các kết nối mạng (đều do bạn chủ động, đi thẳng tới dịch vụ bạn dùng)
| Khi nào | Kết nối tới | Gửi gì |
|---|---|---|
| Fetch / pull / push / clone, tự động fetch (có thể tắt) | Máy chủ Git của repository (GitHub, GitLab…) | Như lệnh `git` thông thường, dùng thông tin đăng nhập của bạn (credential helper, SSH agent; nếu cần, cơ chế đăng nhập Git sẵn có của VS Code) |
| Hiển thị avatar tác giả (có thể tắt trong Cài đặt) | GitHub / GitLab của repository; Gravatar | Email tác giả commit (tới GitHub/GitLab, kèm đăng nhập bạn đã có sẵn cho chính máy chủ đó, nếu có — tài khoản trong hồ sơ, thông tin HTTPS mà git trên máy đã lưu, hoặc tài khoản GitHub đã đăng nhập trong VS Code (chỉ github.com, lấy im lặng, không bao giờ hỏi đăng nhập) — để đọc được repository riêng tư); mã băm SHA-256 của email (tới Gravatar) |
| Bạn thêm tài khoản và bấm "Kiểm tra" token | API của nhà cung cấp bạn chọn | Token bạn nhập, chỉ để xác minh |
| Mở repository ở bản miễn phí | Máy chủ Git của repository | Kiểm tra ẩn danh repository có công khai không (không gửi thông tin đăng nhập) |
| Bạn bấm mở một liên kết | Trình duyệt của bạn | — |
| Bạn tạo phiên Agent | Công cụ dòng lệnh bạn chọn, chạy trong terminal của VS Code | Theo chính sách của công cụ đó — TreeViet không gửi gì |

Các dịch vụ trên (GitHub, GitLab, Gravatar…) có chính sách quyền riêng tư riêng của họ. Việc cài đặt và cập nhật extension do VS Code / chợ extension thực hiện theo chính sách của họ.

## Liên hệ
TreeViet · gittreeviet@gmail.com

---

# Privacy Policy — TreeViet for Git (VS Code extension)

**TreeViet does not collect, store or send your data to the Publisher.** There is no telemetry, no usage analytics, no automatic crash reporting, no ads and no tracking. The extension **does not use VS Code's telemetry**. TreeViet operates no server that receives your data.

All data the extension creates (profiles, settings, recent repositories, open tabs, workspaces, per-profile SSH config and HTTPS tokens, the license key and activation email, avatar and public/private-check caches) stays on the machine the extension runs on, in the storage folder VS Code assigns to the extension, and is removed when you uninstall it. License keys are verified locally.

The extension only connects to services you use, when you use them: your Git remotes (fetch/pull/push/clone, optional auto-fetch — with your own credentials); GitHub/GitLab and Gravatar for author avatars (optional — sends commit author emails, with a sign-in you already have for that same host if any: the profile's account, the HTTPS credential git already stores, or the GitHub account signed in to VS Code (github.com only, read silently, never prompts) / a SHA-256 email hash); a provider's API when you verify an account token; an anonymous check whether a repository is public (free plan); your browser when you open a link. Agent sessions run the command-line tool you choose in VS Code's terminal under that tool's own terms.

Contact: TreeViet · gittreeviet@gmail.com
