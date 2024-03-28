---
title: Tên method không giống với điều nó làm
tags: other devdoc til
---

Đọc mấy tên method muốn lộn mề. Ví dụ method `json()` của object `Response`, nghe cứ tưởng là convert ra JSON?! Thực chất là nó **nhận** dữ liệu JSON rồi convert ra object.

Method `getType()` của object `ClipboardItem`, không phải là để lấy type của item, vì lấy type thì có cái property `ClipboardItem.types` rồi. Còn cái method `getType()` thì thực chất **nhận** tên type rồi trả về cái blob.

Hài.
