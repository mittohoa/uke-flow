# UkeFlow — trang giới thiệu

Trang tải và giới thiệu ứng dụng **UkeFlow**, app học ukulele bằng tiếng Việt
cho Android.

👉 **[Xem trang / tải app](https://mittohoa.github.io/uke-flow/)**

## Repo này chứa gì

| | |
|---|---|
| `index.html` | Toàn bộ trang, một file, song ngữ Việt/Anh. Không phụ thuộc CDN, không script bên ngoài. |
| `screenshots/` | Ảnh chụp từ máy Android thật, đã chuyển WebP 440px (139 KB cho cả 10 ảnh). |
| Releases | File `.apk` để cài đặt. |

Mã nguồn ứng dụng nằm ở repo riêng và **chưa công khai**. Repo này chỉ là trang
giới thiệu và nơi phát hành file cài.

## Tải app

Vào [trang phát hành](https://github.com/mittohoa/uke-flow/releases/latest) hoặc
tải thẳng:

- [`ukeflow-arm64-v8a.apk`](https://github.com/mittohoa/uke-flow/releases/latest/download/ukeflow-arm64-v8a.apk)
  — hầu hết máy từ 2017 trở đi
- [`ukeflow-armeabi-v7a.apk`](https://github.com/mittohoa/uke-flow/releases/latest/download/ukeflow-armeabi-v7a.apk)
  — máy cũ 32-bit

Yêu cầu Android 6.0 trở lên.

## Đăng bản mới

Tên file trong mỗi bản phát hành **giữ nguyên không kèm số phiên bản**, để link
`releases/latest/download/…` trên trang luôn trỏ tới bản mới nhất mà không phải
sửa HTML:

```bash
gh release create v1.1.0 \
  dist/ukeflow-arm64-v8a.apk \
  dist/ukeflow-armeabi-v7a.apk \
  --title "UkeFlow 1.1.0" --notes "..."
```

Nhớ sửa số phiên bản hiển thị trong `index.html` (ba chỗ: nút tải, dòng dưới
nút, và footer).

## Liên hệ

mittohoa@gmail.com
