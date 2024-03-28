---
title: Cố định chiều cao ảnh woocommerce
tags: wordpress css
---

 Vào Appearance > Theme File Editor


![](https://i.ibb.co/xYZ0W6Q/68f06e8b9c8d.png)


Tìm đến theme Child, mở file style.css
![](https://i.ibb.co/9GNzWb9/a800a81afa06.png)

Paste code sau đây vào, 

```
.woocommerce ul.products li.product a img { height: 300px !important; margin-bottom: 0 !important; object-fit: contain !important; }
```

Chỗ 300  có thể thay bằng con số khác tùy thuộc vào chiều cao mong muốn

Lưu lại, xóa tất cả các cache (nếu có)
