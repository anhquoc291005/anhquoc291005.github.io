# CV trực tuyến của Anh Quoc

Website GitHub Pages tại [anhquoc291005.github.io](https://anhquoc291005.github.io/).

## Chỉnh sửa CV

- Sửa [index.md](index.md) trên GitHub để cập nhật nội dung từng mục. GitHub Pages sẽ xuất bản lại sau khi lưu vào nhánh `main`.
- Đổi tiêu đề trang trong [_config.yml](_config.yml) và phần mở đầu của [index.md](index.md) nếu muốn dùng tên khác.
- Ảnh đại diện lấy từ hồ sơ GitHub. Nếu muốn dùng ảnh riêng, lưu ảnh vào `assets/` và thay đường dẫn tương ứng trong [index.md](index.md).
- Để thêm CV PDF, tải tệp lên đúng đường dẫn `assets/cv.pdf`. Menu, phần giới thiệu và mục **CV** sẽ tự liên kết tới tệp sau khi GitHub Pages cập nhật.

## Thêm kinh nghiệm và dự án

Trong mục **Kinh nghiệm và học vấn**, đặt thời gian trên dòng đầu, rồi thêm vị trí, đơn vị và mô tả. Giữ dòng `{: .experience-list }` ngay sau mục cuối của danh sách.

```markdown
MM/YYYY – Hiện tại
: **Vị trí · Tên đơn vị**
  Mô tả công việc và kết quả của bạn.
```

Trong mục **Dự án**, dùng tiêu đề cấp ba cho từng dự án, sau đó mô tả phần bạn làm và thêm các liên kết liên quan. Có thể lưu ảnh hoặc video vào `media/` và báo cáo hoặc bài báo vào `papers/`, giống cách repo mẫu chia tệp.

```markdown
### Tên dự án

Mô tả bài toán, phần việc của bạn và kết quả.

[Mã nguồn](https://github.com/TEN-TAI-KHOAN/TEN-DU-AN) · [Video demo](./media/demo.mp4) · [Báo cáo PDF](./papers/bao-cao.pdf)

![Mô tả ảnh dự án](./media/du-an.jpg)
{: .project-media }
```

Trang dùng theme Minima của Jekyll. Nội dung nằm trong Markdown, định dạng trong [assets/main.scss](assets/main.scss).
