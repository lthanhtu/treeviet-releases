<p align="center">
  <img src="screenshots/icon.png" width="96" alt="GitTreeViet">
</p>

<h1 align="center">GitTreeViet</h1>
<p align="center">Git client nhẹ và nhanh cho macOS, Windows và Linux<br>A light, fast Git client for macOS, Windows and Linux</p>

<p align="center">
  <a href="#download"><b>⬇ Tải về / Download</b></a>
</p>

<a id="download"></a>

## ⬇ Tải về / Download

| Hệ điều hành / OS | File cài / Installer |
|---|---|
| **macOS** (Apple Silicon + Intel, 11+) | [GitTreeViet-macOS-universal.dmg](../../releases/latest/download/GitTreeViet-macOS-universal.dmg) |
| **Windows 10/11** x64 | [GitTreeViet-Windows-x64-setup.exe](../../releases/latest/download/GitTreeViet-Windows-x64-setup.exe) · [.msi](../../releases/latest/download/GitTreeViet-Windows-x64.msi) |
| **Linux** x64 — Ubuntu/Debian | [GitTreeViet-Linux-x64.deb](../../releases/latest/download/GitTreeViet-Linux-x64.deb) |
| **Linux** x64 — mọi distro / any distro | [GitTreeViet-Linux-x64.AppImage](../../releases/latest/download/GitTreeViet-Linux-x64.AppImage) |

### Cài đặt / Install
- **macOS**: mở `.dmg`, kéo GitTreeViet vào *Applications*. Nếu macOS báo "không xác minh được nhà phát triển": chuột phải vào app → **Open** → **Open** (hoặc `xattr -dr com.apple.quarantine /Applications/GitTreeViet.app`).
- **Windows**: chạy `setup.exe`. Nếu SmartScreen hiện "Windows protected your PC": **More info** → **Run anyway**. Cần WebView2 (có sẵn trên Windows 10/11 mới).
- **Linux**: `sudo apt install ./GitTreeViet-Linux-x64.deb`, hoặc `chmod +x GitTreeViet-Linux-x64.AppImage && ./GitTreeViet-Linux-x64.AppImage` (cần FUSE). Nếu cửa sổ trắng trên máy NVIDIA: `WEBKIT_DISABLE_DMABUF_RENDERER=1`.
- Cần cài **Git** trên máy / requires **Git** installed.

## ✨ Tính năng / Features

- **Commit graph** nhanh với repo lớn (50.000+ commit): avatar tác giả, nhãn nhánh/tag, solo/ẩn nhánh, tìm commit, hover xem mọi nhánh trên một commit.
- **Diff** hai cột / một cột, tô màu từng chữ, bỏ qua khoảng trắng, diff ảnh, blame, lịch sử file, so sánh commit/nhánh.
- **Working tree**: stage/unstage từng file, từng hunk, từng dòng; commit, amend, sửa message commit cuối; stash.
- **Nhánh & remote**: checkout, tạo/đổi tên/xoá nhánh & tag, fetch/pull/push, quản lý remote, undo/redo, submodule, worktree.
- **Merge / Rebase**: kéo thả nhánh, giải quyết conflict 3 cột, interactive rebase, cherry-pick, revert, reset.
- **Profiles**: mỗi hồ sơ có danh tính Git, ký commit (GPG/SSH), SSH key & SSH config, tài khoản HTTPS (GitHub/GitLab/Bitbucket/Gitea) riêng — chuyển đổi tức thì.
- **Workspaces**: mở một thư mục cha, tự nhận diện và nhóm mọi repository bên trong.
- **Agents**: theo dõi các phiên AI coding agent dạng dòng lệnh trên từng worktree, tạo phiên mới chỉ với một cú bấm.

## 🖼 Ảnh chụp / Screenshots

![Màn hình chính](screenshots/main-dark.png)
![Diff hai cột](screenshots/diff-split.png)
![Giao diện sáng](screenshots/main-light.png)
![Workspaces](screenshots/welcome-workspaces.png)
![Agents](screenshots/agents.png)
![Profiles](screenshots/profiles.png)

## 🔑 Bản miễn phí & Pro / Free & Pro

- **Miễn phí**: dùng với repository công khai (public) và repository cục bộ.
- **Pro**: mở thêm repository riêng tư (private). Cần đăng nhập bằng email và **key bản quyền** do tác giả cấp; key gắn với email và có thời hạn sử dụng.
- Mua key / hỗ trợ: **gittreeviet@gmail.com**

### Chính sách mua key / Purchase policy
- Mua key chỉ bao gồm **key bản quyền và thời hạn sử dụng** ghi trên key.
- **Đã mua thì không hoàn tiền**.
- Key dùng cho cá nhân người mua, không chia sẻ hay bán lại.
- **Hỗ trợ**: lỗi ứng dụng và lỗi key (ví dụ không kích hoạt được) — tác giả sẽ sửa lỗi hoặc cấp lại key cho thời hạn còn lại.

A purchase grants a license key and its period of use only. **All sales are final — no refunds**. Support covers app bugs and faulty keys.

## 🔒 Quyền riêng tư / Privacy

GitTreeViet **không thu thập, không lưu trữ và không gửi dữ liệu của bạn** cho nhà phát hành: không telemetry, không thống kê, không theo dõi. Mọi dữ liệu (hồ sơ, cài đặt, token, key bản quyền) nằm trên máy bạn. Chi tiết: [PRIVACY.md](PRIVACY.md).

GitTreeViet **does not collect, store or send your data**: no telemetry, analytics or tracking. See [PRIVACY.md](PRIVACY.md).

## ⚖️ Giấy phép / License

© 2026 GitTreeViet · gittreeviet@gmail.com. Bạn được tải và sử dụng bản phát hành chính thức; không được sao chép, chỉnh sửa, phân phối lại hay dịch ngược. Xem [LICENSE](LICENSE).

You may download and use the official releases; copying, modifying, redistributing or reverse engineering is not permitted. See [LICENSE](LICENSE).
