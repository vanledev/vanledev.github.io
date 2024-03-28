---
title: Hệ thập lục (gương mặt vàng trong làng có nhiều định dạng)
tags: data til
---

Dữ liệu nhị phân thì thân thiện với máy nhưng không thân thiện với người (thì rõ, 000110101010101010), sinh ra hệ thập lục phân Hexadecimal. Cách chuyển đổi thì như sau

Chia cái số nhị phân ra thành cụm 4

```
0101 	1110 	1011 	0101 	0010
```

Rồi convert từng cụm  bằng cách: Đếm từ phải qua, nếu chữ số là 0 thì bỏ qua, nếu là 1 thì cộng vào tổng một lượng là 2 mũ [vị trí của chữ số đó]

```
0101 = 2^0 + 0 + 2^2 = 5
```

Rồi đối chiếu với bảng quy đổi Hexadecimal: từ 0-9 thì để nguyên, từ 10-15 thì đổi thành A-B-C-D-E-F. Thì số trên ở hệ Hexadecimal là 

```
5
```

Đây cũng là lí do tại sao lại là thập lục (16) vì con số thập lục phân sinh ra bằng cách cắn đôi một con nhị phân 8 bit, nó chỉ có 4 chữ số.  Lớn nhất là 1111 

1111 = 2^0 + 2^1 + 2^2 + 2^3 = 1+2+4+8 = 15

15 thì đếm từ 0 đến 15 thì chỉ có 16 số thôi. Nên hệ thập lục phân chỉ cần 16 chữ số đại diện.

Also, con thập lục này nhìn dễ gây nhầm với hệ thập phân bình thường nên người ta nghĩ ra cách để định dạng nó, [mà mỗi ngôn ngữ mỗi môi trường lại định dạng một kiểu](https://en.wikipedia.org/wiki/Hexadecimal) mới vui

lúc thì `\x1B` lúc `0x1B` lúc `%20` (dấu cách trên trình duyệt) lúc `U+20AC` lúc `&#x2019;`



