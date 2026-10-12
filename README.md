# Kho App IPA

![Icon repo](https://i.imgur.com/0qP4rvM.jpeg)

Nguồn ứng dụng IPA để thêm vào ESign và các trình đọc nguồn JSON tương thích.

## Thêm nguồn

Trong mục nguồn ứng dụng của ESign, thêm URL:

```text
https://tomqtx11.github.io/kho-app-ipa/repo.json
```

Link JSON dự phòng:

```text
https://raw.githubusercontent.com/Tomqtx11/kho-app-ipa/main/repo.json
```

## Ứng dụng

| Tên | Mô tả | Bundle ID | Phiên bản trong IPA | iOS tối thiểu |
| --- | --- | --- | --- | --- |
| Arena of Valor | Map Menu | `com.ngame.allstar.eu` | `1.64.11768514` | 13.0 |

- File IPA: **229,040,646 byte**.
- [Tải trực tiếp từ GitHub Releases](https://github.com/Tomqtx11/kho-app-ipa/releases/download/aov-1.64.11768514/Arena-of-Valor-EU.ipa).
- [Link MediaFire gốc](https://www.mediafire.com/file/55c6fe01mis12u7/com.ngame.allstar.eu_1.64.1.7_und3fined.ipa/file).
- SHA-256: `6693de61ca44334aff937edd2f6fa3ed8e2d31b0038f6b74361a2884815c26c3`.

Thông tin bundle ID, phiên bản và iOS tối thiểu được đọc từ `Info.plist` trong IPA. Tên file gốc ghi `1.64.1.7`, nhưng phiên bản bên trong IPA là `1.64.11768514`. Ngày trong JSON là ngày thêm phiên bản vào nguồn.

Link GitHub Releases được dùng trong `downloadURL` để tránh phụ thuộc vào link tải MediaFire được tạo theo phiên. Nguồn chỉ cung cấp danh sách và file IPA; ký và cài đặt được thực hiện trong app ký của bạn. Khả năng đọc nguồn của CSign chưa được kiểm tra trên thiết bị.

## Cập nhật nguồn

Tải IPA mới lên GitHub Releases, sau đó cập nhật mục tương ứng trong `repo.json`. Giữ thông tin phiên bản, dung lượng và link tải ở cấp app khớp với phần tử mới nhất trong `versions`.

Không thêm token, chứng chỉ hoặc khóa riêng vào repository.
