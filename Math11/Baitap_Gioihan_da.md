---
title: "Bộ 400 bài tập Giới hạn và Hàm số liên tục – Toán 11"
subject: "Toán 11 – Kết nối tri thức"
tags:
  - toan-11
  - gioi-han
  - ham-so-lien-tuc
  - bai-tap
---

# BỘ BÀI TẬP GIỚI HẠN – TOÁN 11 (CÓ LỜI GIẢI CHI TIẾT)

> [!info] Cấu trúc và cách dùng
> - Gồm **20 dạng × 20 bài = 400 bài**; đánh số **D01.01 đến D20.20**.
> - Các bài trong mỗi dạng đi từ **nhận biết → thông hiểu → vận dụng** (bài 01–07, 08–14, 15–20).
> - Quy ước: nếu không chỉ rõ, giới hạn dãy số được xét khi $n\to+\infty$; mỗi biểu thức chỉ xét tại các điểm thuộc miền xác định.
> - Hai phiên bản có **đề, số thứ tự và thứ tự dạng hoàn toàn giống nhau**.
> - Tài liệu dùng `$...$`, `$$...$$` và Obsidian callout. Không sử dụng HTML để dàn trang.

**Tài liệu tham chiếu:** SGK Toán 11 tập 1 – *Kết nối tri thức với cuộc sống* (Bài 15, 16, 17); chuyên đề *Giới hạn và hàm số liên tục – Toán 11* đã cung cấp. **Các đề bài và lời giải dưới đây được biên soạn mới**, không phải chép nguyên văn tài liệu tham chiếu.

## Mục lục

- [[#Dạng 01. Giới hạn cơ bản và các phép toán với giới hạn|Dạng 01. Giới hạn cơ bản và các phép toán với giới hạn]]
- [[#Dạng 02. Phân thức đa thức theo n|Dạng 02. Phân thức đa thức theo n]]
- [[#Dạng 03. Dãy số chứa lũy thừa a^n|Dạng 03. Dãy số chứa lũy thừa a^n]]
- [[#Dạng 04. Căn thức: đưa lũy thừa của n ra ngoài căn|Dạng 04. Căn thức: đưa lũy thừa của n ra ngoài căn]]
- [[#Dạng 05. Căn thức: nhân liên hợp|Dạng 05. Căn thức: nhân liên hợp]]
- [[#Dạng 06. Định lí kẹp và dãy dao động|Dạng 06. Định lí kẹp và dãy dao động]]
- [[#Dạng 07. Cấp số nhân lùi vô hạn|Dạng 07. Cấp số nhân lùi vô hạn]]
- [[#Dạng 08. Tổng dãy số và dãy truy hồi|Dạng 08. Tổng dãy số và dãy truy hồi]]
- [[#Dạng 09. Thay trực tiếp và định lí giới hạn|Dạng 09. Thay trực tiếp và định lí giới hạn]]
- [[#Dạng 10. Khử 0/0: phân tích nhân tử bậc hai|Dạng 10. Khử 0/0: phân tích nhân tử bậc hai]]
- [[#Dạng 11. Khử 0/0: hằng đẳng thức bậc ba, bậc bốn|Dạng 11. Khử 0/0: hằng đẳng thức bậc ba, bậc bốn]]
- [[#Dạng 12. Khử 0/0: nhân liên hợp tại một điểm|Dạng 12. Khử 0/0: nhân liên hợp tại một điểm]]
- [[#Dạng 13. Khử 0/0: quy đồng phân thức|Dạng 13. Khử 0/0: quy đồng phân thức]]
- [[#Dạng 14. Giới hạn một bên và hàm số từng đoạn|Dạng 14. Giới hạn một bên và hàm số từng đoạn]]
- [[#Dạng 15. Giới hạn vô cực tại một điểm và xét dấu|Dạng 15. Giới hạn vô cực tại một điểm và xét dấu]]
- [[#Dạng 16. Phân thức đa thức khi x→±∞|Dạng 16. Phân thức đa thức khi x→±∞]]
- [[#Dạng 17. Căn thức khi x→±∞|Dạng 17. Căn thức khi x→±∞]]
- [[#Dạng 18. Bài toán tổng hợp, kẹp và dao động|Dạng 18. Bài toán tổng hợp, kẹp và dao động]]
- [[#Dạng 19. Tính liên tục tại một điểm và tìm tham số|Dạng 19. Tính liên tục tại một điểm và tìm tham số]]
- [[#Dạng 20. Liên tục trên khoảng, đoạn và tồn tại nghiệm|Dạng 20. Liên tục trên khoảng, đoạn và tồn tại nghiệm]]

---


# PHẦN A · GIỚI HẠN DÃY SỐ


## Dạng 01. Giới hạn cơ bản và các phép toán với giới hạn

> [!tip] Phương pháp trọng tâm
> Dựa vào các giới hạn chuẩn, cộng – trừ – nhân – chia đúng điều kiện; xét dấu khi kết quả vô cực.


### Bài D01.01 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{3}{n^1}\right)$.


**Lời giải chi tiết**

Vì $\frac{1}{n^1}$ tiến về $0$ khi $n\to+\infty$, nên

$$
\lim_{n\to +\infty}\left(\frac{3}{n^1}\right)=3\cdot0=0.
$$




### Bài D01.02 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{8}{n^2}\right)$.


**Lời giải chi tiết**

Vì $\frac{1}{n^2}$ tiến về $0$ khi $n\to+\infty$, nên

$$
\lim_{n\to +\infty}\left(\frac{8}{n^2}\right)=8\cdot0=0.
$$




### Bài D01.03 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{-6}{n^3}\right)$.


**Lời giải chi tiết**

Vì $\frac{1}{n^3}$ tiến về $0$ khi $n\to+\infty$, nên

$$
\lim_{n\to +\infty}\left(\frac{-6}{n^3}\right)=-6\cdot0=0.
$$




### Bài D01.04 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{5}{n^4}\right)$.


**Lời giải chi tiết**

Vì $\frac{1}{n^4}$ tiến về $0$ khi $n\to+\infty$, nên

$$
\lim_{n\to +\infty}\left(\frac{5}{n^4}\right)=5\cdot0=0.
$$




### Bài D01.05 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{-2}{n^5}\right)$.


**Lời giải chi tiết**

Vì $\frac{1}{n^5}$ tiến về $0$ khi $n\to+\infty$, nên

$$
\lim_{n\to +\infty}\left(\frac{-2}{n^5}\right)=-2\cdot0=0.
$$




### Bài D01.06 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(4 + \frac{3}{n}\right)$.


**Lời giải chi tiết**

Tách hằng số và phần nhỏ dần: $\frac{1}{n^1}$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(4 + \frac{3}{n}\right)=4+3\cdot0=4.
$$




### Bài D01.07 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(-2 + \frac{5}{n^{2}}\right)$.


**Lời giải chi tiết**

Tách hằng số và phần nhỏ dần: $\frac{1}{n^2}$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(-2 + \frac{5}{n^{2}}\right)=-2+5\cdot0=-2.
$$




### Bài D01.08 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(7 - \frac{4}{n^{3}}\right)$.


**Lời giải chi tiết**

Tách hằng số và phần nhỏ dần: $\frac{1}{n^3}$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(7 - \frac{4}{n^{3}}\right)=7-4\cdot0=7.
$$




### Bài D01.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(-5 - \frac{9}{n}\right)$.


**Lời giải chi tiết**

Tách hằng số và phần nhỏ dần: $\frac{1}{n^1}$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(-5 - \frac{9}{n}\right)=-5-9\cdot0=-5.
$$




### Bài D01.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(1 + \frac{11}{n^{4}}\right)$.


**Lời giải chi tiết**

Tách hằng số và phần nhỏ dần: $\frac{1}{n^4}$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(1 + \frac{11}{n^{4}}\right)=1+11\cdot0=1.
$$




### Bài D01.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(2 \cdot n^{2} + 1\right)$.


**Lời giải chi tiết**

Thành phần $n^2$ tăng không bị chặn; hằng số $1$ không đổi dấu tăng trưởng của hạng tử cao nhất.

$$
\lim_{n\to +\infty}\left(2 \cdot n^{2} + 1\right)=+\infty.
$$




### Bài D01.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(7 - 4 \cdot n^{3}\right)$.


**Lời giải chi tiết**

Thành phần $n^3$ tăng không bị chặn; hằng số $7$ không đổi dấu tăng trưởng của hạng tử cao nhất.

$$
\lim_{n\to +\infty}\left(7 - 4 \cdot n^{3}\right)=-\infty.
$$




### Bài D01.13 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(5 \cdot n - 2\right)$.


**Lời giải chi tiết**

Thành phần $n^1$ tăng không bị chặn; hằng số $-2$ không đổi dấu tăng trưởng của hạng tử cao nhất.

$$
\lim_{n\to +\infty}\left(5 \cdot n - 2\right)=+\infty.
$$




### Bài D01.14 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(8 - 3 \cdot n^{4}\right)$.


**Lời giải chi tiết**

Thành phần $n^4$ tăng không bị chặn; hằng số $8$ không đổi dấu tăng trưởng của hạng tử cao nhất.

$$
\lim_{n\to +\infty}\left(8 - 3 \cdot n^{4}\right)=-\infty.
$$




### Bài D01.15 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(6 \cdot n^{5}\right)$.


**Lời giải chi tiết**

Thành phần $n^5$ tăng không bị chặn; hằng số $0$ không đổi dấu tăng trưởng của hạng tử cao nhất.

$$
\lim_{n\to +\infty}\left(6 \cdot n^{5}\right)=+\infty.
$$




### Bài D01.16 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(3 + \left(\frac{1}{2}\right)^{n}\right)$.


**Lời giải chi tiết**

Có $\frac{1}{2}$ thỏa $|q|<1$, vì vậy $\frac{1}{2}^n\to0$; cộng với hằng số còn lại.

$$
\lim_{n\to +\infty}\left(3 + \left(\frac{1}{2}\right)^{n}\right)=0+(3)=3.
$$




### Bài D01.17 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\left(- \frac{1}{3}\right)^{n} + 2\right)$.


**Lời giải chi tiết**

Có $- \frac{1}{3}$ thỏa $|q|<1$, vì vậy $- \frac{1}{3}^n\to0$; cộng với hằng số còn lại.

$$
\lim_{n\to +\infty}\left(\left(- \frac{1}{3}\right)^{n} + 2\right)=0+(2)=2.
$$




### Bài D01.18 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\left(\frac{3}{4}\right)^{n} - 5\right)$.


**Lời giải chi tiết**

Có $\frac{3}{4}$ thỏa $|q|<1$, vì vậy $\frac{3}{4}^n\to0$; cộng với hằng số còn lại.

$$
\lim_{n\to +\infty}\left(\left(\frac{3}{4}\right)^{n} - 5\right)=0-5=-5.
$$




### Bài D01.19 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\left(- \frac{2}{5}\right)^{n} + 7\right)$.


**Lời giải chi tiết**

Có $- \frac{2}{5}$ thỏa $|q|<1$, vì vậy $- \frac{2}{5}^n\to0$; cộng với hằng số còn lại.

$$
\lim_{n\to +\infty}\left(\left(- \frac{2}{5}\right)^{n} + 7\right)=0+(7)=7.
$$




### Bài D01.20 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(-1 + \left(\frac{1}{10}\right)^{n}\right)$.


**Lời giải chi tiết**

Có $\frac{1}{10}$ thỏa $|q|<1$, vì vậy $\frac{1}{10}^n\to0$; cộng với hằng số còn lại.

$$
\lim_{n\to +\infty}\left(-1 + \left(\frac{1}{10}\right)^{n}\right)=0-1=-1.
$$




---


## Dạng 02. Phân thức đa thức theo n

> [!tip] Phương pháp trọng tâm
> Chia tử và mẫu cho lũy thừa n cao nhất; xét tương quan bậc và dấu hệ số đầu.


### Bài D02.01 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot n + 3}{5 \cdot n - 1}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n$; khi $n\to+\infty$, các số hạng $1/n$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot n + 3}{5 \cdot n - 1}\right)=\lim_{n\to+\infty}\frac{2+\frac{3}n}{5+\frac{-1}n}=\frac{2}{5}=\frac{2}{5}.
$$




### Bài D02.02 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 - 3 \cdot n}{4 \cdot n + 5}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n$; khi $n\to+\infty$, các số hạng $1/n$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 - 3 \cdot n}{4 \cdot n + 5}\right)=\lim_{n\to+\infty}\frac{-3+\frac{2}n}{4+\frac{5}n}=\frac{-3}{4}=- \frac{3}{4}.
$$




### Bài D02.03 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{6 \cdot n - 7}{2 \cdot n + 3}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n$; khi $n\to+\infty$, các số hạng $1/n$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{6 \cdot n - 7}{2 \cdot n + 3}\right)=\lim_{n\to+\infty}\frac{6+\frac{-7}n}{2+\frac{3}n}=\frac{6}{2}=3.
$$




### Bài D02.04 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{n + 5}{- 4 \cdot n - 1}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n$; khi $n\to+\infty$, các số hạng $1/n$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{n + 5}{- 4 \cdot n - 1}\right)=\lim_{n\to+\infty}\frac{1+\frac{5}n}{-4+\frac{-1}n}=\frac{1}{-4}=- \frac{1}{4}.
$$




### Bài D02.05 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{7 \cdot n + 9}{3 \cdot n + 8}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n$; khi $n\to+\infty$, các số hạng $1/n$ tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{7 \cdot n + 9}{3 \cdot n + 8}\right)=\lim_{n\to+\infty}\frac{7+\frac{9}n}{3+\frac{8}n}=\frac{7}{3}=\frac{7}{3}.
$$




### Bài D02.06 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot n + 1}{3 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc tử nhỏ hơn bậc mẫu. Chia cả tử và mẫu cho $n^2$: tử tiến về $0$, mẫu tiến về hệ số khác $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot n + 1}{3 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{\frac{2}n+\frac{1}{n^2}}{3+\frac1{n^2}}=0.
$$




### Bài D02.07 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{5 \cdot n - 7}{2 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc tử nhỏ hơn bậc mẫu. Chia cả tử và mẫu cho $n^2$: tử tiến về $0$, mẫu tiến về hệ số khác $0$.

$$
\lim_{n\to +\infty}\left(\frac{5 \cdot n - 7}{2 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{\frac{5}n+\frac{-7}{n^2}}{2+\frac1{n^2}}=0.
$$




### Bài D02.08 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{6 - 4 \cdot n}{8 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc tử nhỏ hơn bậc mẫu. Chia cả tử và mẫu cho $n^2$: tử tiến về $0$, mẫu tiến về hệ số khác $0$.

$$
\lim_{n\to +\infty}\left(\frac{6 - 4 \cdot n}{8 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{\frac{-4}n+\frac{6}{n^2}}{8+\frac1{n^2}}=0.
$$




### Bài D02.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{9 \cdot n + 1}{7 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc tử nhỏ hơn bậc mẫu. Chia cả tử và mẫu cho $n^2$: tử tiến về $0$, mẫu tiến về hệ số khác $0$.

$$
\lim_{n\to +\infty}\left(\frac{9 \cdot n + 1}{7 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{\frac{9}n+\frac{1}{n^2}}{7+\frac1{n^2}}=0.
$$




### Bài D02.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 - 3 \cdot n}{6 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc tử nhỏ hơn bậc mẫu. Chia cả tử và mẫu cho $n^2$: tử tiến về $0$, mẫu tiến về hệ số khác $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 - 3 \cdot n}{6 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{\frac{-3}n+\frac{2}{n^2}}{6+\frac1{n^2}}=0.
$$




### Bài D02.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot n^{3} + 3}{5 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Chia cho $n^2$; biểu thức có dạng gần $(2/5)n$. Vì $n\to+\infty$, dấu quyết định bởi $a/c$.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot n^{3} + 3}{5 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{2n+\frac{3}{n^2}}{5+\frac1{n^2}}=+\infty.
$$




### Bài D02.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{- 3 \cdot n^{3} - 1}{7 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Chia cho $n^2$; biểu thức có dạng gần $(-3/7)n$. Vì $n\to+\infty$, dấu quyết định bởi $a/c$.

$$
\lim_{n\to +\infty}\left(\frac{- 3 \cdot n^{3} - 1}{7 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{-3n+\frac{-1}{n^2}}{7+\frac1{n^2}}=-\infty.
$$




### Bài D02.13 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{8 \cdot n^{3} + 5}{1 - 2 \cdot n^{2}}\right)$.


**Lời giải chi tiết**

Chia cho $n^2$; biểu thức có dạng gần $(8/-2)n$. Vì $n\to+\infty$, dấu quyết định bởi $a/c$.

$$
\lim_{n\to +\infty}\left(\frac{8 \cdot n^{3} + 5}{1 - 2 \cdot n^{2}}\right)=\lim_{n\to+\infty}\frac{8n+\frac{5}{n^2}}{-2+\frac1{n^2}}=-\infty.
$$




### Bài D02.14 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 - 4 \cdot n^{3}}{1 - 3 \cdot n^{2}}\right)$.


**Lời giải chi tiết**

Chia cho $n^2$; biểu thức có dạng gần $(-4/-3)n$. Vì $n\to+\infty$, dấu quyết định bởi $a/c$.

$$
\lim_{n\to +\infty}\left(\frac{2 - 4 \cdot n^{3}}{1 - 3 \cdot n^{2}}\right)=\lim_{n\to+\infty}\frac{-4n+\frac{2}{n^2}}{-3+\frac1{n^2}}=+\infty.
$$




### Bài D02.15 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{5 \cdot n^{3} - 6}{4 \cdot n^{2} + 1}\right)$.


**Lời giải chi tiết**

Chia cho $n^2$; biểu thức có dạng gần $(5/4)n$. Vì $n\to+\infty$, dấu quyết định bởi $a/c$.

$$
\lim_{n\to +\infty}\left(\frac{5 \cdot n^{3} - 6}{4 \cdot n^{2} + 1}\right)=\lim_{n\to+\infty}\frac{5n+\frac{-6}{n^2}}{4+\frac1{n^2}}=+\infty.
$$




### Bài D02.16 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot n^{2} + n + 1}{3 \cdot n^{2} + n + 4}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n^2$ rồi bỏ các thành phần $1/n$, $1/n^2$ khi lấy giới hạn.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot n^{2} + n + 1}{3 \cdot n^{2} + n + 4}\right)=\lim_{n\to+\infty}\frac{2+\frac{1}n+\frac1{n^2}}{3+\frac1n+\frac4{n^2}}=\frac{2}{3}.
$$




### Bài D02.17 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{4 \cdot n^{2} - 2 \cdot n + 1}{5 \cdot n^{2} + n + 4}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n^2$ rồi bỏ các thành phần $1/n$, $1/n^2$ khi lấy giới hạn.

$$
\lim_{n\to +\infty}\left(\frac{4 \cdot n^{2} - 2 \cdot n + 1}{5 \cdot n^{2} + n + 4}\right)=\lim_{n\to+\infty}\frac{4+\frac{-2}n+\frac1{n^2}}{5+\frac1n+\frac4{n^2}}=\frac{4}{5}.
$$




### Bài D02.18 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{- 3 \cdot n^{2} + 4 \cdot n + 1}{7 \cdot n^{2} + n + 4}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n^2$ rồi bỏ các thành phần $1/n$, $1/n^2$ khi lấy giới hạn.

$$
\lim_{n\to +\infty}\left(\frac{- 3 \cdot n^{2} + 4 \cdot n + 1}{7 \cdot n^{2} + n + 4}\right)=\lim_{n\to+\infty}\frac{-3+\frac{4}n+\frac1{n^2}}{7+\frac1n+\frac4{n^2}}=- \frac{3}{7}.
$$




### Bài D02.19 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{6 \cdot n^{2} + 3 \cdot n + 1}{- 4 \cdot n^{2} + n + 4}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n^2$ rồi bỏ các thành phần $1/n$, $1/n^2$ khi lấy giới hạn.

$$
\lim_{n\to +\infty}\left(\frac{6 \cdot n^{2} + 3 \cdot n + 1}{- 4 \cdot n^{2} + n + 4}\right)=\lim_{n\to+\infty}\frac{6+\frac{3}n+\frac1{n^2}}{-4+\frac1n+\frac4{n^2}}=- \frac{3}{2}.
$$




### Bài D02.20 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{5 \cdot n^{2} + n + 1}{2 \cdot n^{2} + n + 4}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $n^2$ rồi bỏ các thành phần $1/n$, $1/n^2$ khi lấy giới hạn.

$$
\lim_{n\to +\infty}\left(\frac{5 \cdot n^{2} + n + 1}{2 \cdot n^{2} + n + 4}\right)=\lim_{n\to+\infty}\frac{5+\frac{1}n+\frac1{n^2}}{2+\frac1n+\frac4{n^2}}=\frac{5}{2}.
$$




---


## Dạng 03. Dãy số chứa lũy thừa a^n

> [!tip] Phương pháp trọng tâm
> Đưa về cùng lũy thừa và chia cho cơ số có trị tuyệt đối lớn nhất, đồng thời xét dấu.


### Bài D03.01 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot 2^{n} + 3 \cdot 3^{n}}{4 \cdot 2^{n} + 2 \cdot 3^{n}}\right)$.


**Lời giải chi tiết**

Do $3^n$ trội hơn $2^n$, chia tử và mẫu cho $3^n$. Vì $(2/3)^n\to0$ nên

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot 2^{n} + 3 \cdot 3^{n}}{4 \cdot 2^{n} + 2 \cdot 3^{n}}\right)=\lim_{n\to+\infty}\frac{3+2\left(\frac23\right)^n}{2+4\left(\frac23\right)^n}=\frac{3}{2}.
$$




### Bài D03.02 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{- 2 \cdot 2^{n} + 5 \cdot 3^{n}}{3 \cdot 2^{n} + 7 \cdot 3^{n}}\right)$.


**Lời giải chi tiết**

Do $3^n$ trội hơn $2^n$, chia tử và mẫu cho $3^n$. Vì $(2/3)^n\to0$ nên

$$
\lim_{n\to +\infty}\left(\frac{- 2 \cdot 2^{n} + 5 \cdot 3^{n}}{3 \cdot 2^{n} + 7 \cdot 3^{n}}\right)=\lim_{n\to+\infty}\frac{5-2\left(\frac23\right)^n}{7+3\left(\frac23\right)^n}=\frac{5}{7}.
$$




### Bài D03.03 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{4 \cdot 2^{n} + 2 \cdot 3^{n}}{2^{n} + 3 \cdot 3^{n}}\right)$.


**Lời giải chi tiết**

Do $3^n$ trội hơn $2^n$, chia tử và mẫu cho $3^n$. Vì $(2/3)^n\to0$ nên

$$
\lim_{n\to +\infty}\left(\frac{4 \cdot 2^{n} + 2 \cdot 3^{n}}{2^{n} + 3 \cdot 3^{n}}\right)=\lim_{n\to+\infty}\frac{2+4\left(\frac23\right)^n}{3+1\left(\frac23\right)^n}=\frac{2}{3}.
$$




### Bài D03.04 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{- 3 \cdot 2^{n} + 8 \cdot 3^{n}}{5 \cdot 2^{n} - 4 \cdot 3^{n}}\right)$.


**Lời giải chi tiết**

Do $3^n$ trội hơn $2^n$, chia tử và mẫu cho $3^n$. Vì $(2/3)^n\to0$ nên

$$
\lim_{n\to +\infty}\left(\frac{- 3 \cdot 2^{n} + 8 \cdot 3^{n}}{5 \cdot 2^{n} - 4 \cdot 3^{n}}\right)=\lim_{n\to+\infty}\frac{8-3\left(\frac23\right)^n}{-4+5\left(\frac23\right)^n}=-2.
$$




### Bài D03.05 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot 2^{n} + 3^{n}}{- 2 \cdot 2^{n} + 6 \cdot 3^{n}}\right)$.


**Lời giải chi tiết**

Do $3^n$ trội hơn $2^n$, chia tử và mẫu cho $3^n$. Vì $(2/3)^n\to0$ nên

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot 2^{n} + 3^{n}}{- 2 \cdot 2^{n} + 6 \cdot 3^{n}}\right)=\lim_{n\to+\infty}\frac{1+2\left(\frac23\right)^n}{6-2\left(\frac23\right)^n}=\frac{1}{6}.
$$




### Bài D03.06 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(3 \cdot 3^{n} + 2 \cdot 5^{n}\right)$.


**Lời giải chi tiết**

Đặt $5^n$ ra ngoài: $\frac{3}{5}$ có trị tuyệt đối nhỏ hơn $1$ nên lũy thừa của nó tiến về $0$. Phần trong ngoặc tiến về $2\ne0$.

$$
\lim_{n\to +\infty}\left(3 \cdot 3^{n} + 2 \cdot 5^{n}\right)=\lim_{n\to+\infty}5^n\left(2+3\left(\frac{3}{5}\right)^n\right)=+\infty.
$$




### Bài D03.07 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(4 \cdot 2^{n} - 3 \cdot 4^{n}\right)$.


**Lời giải chi tiết**

Đặt $4^n$ ra ngoài: $\frac{2}{4}$ có trị tuyệt đối nhỏ hơn $1$ nên lũy thừa của nó tiến về $0$. Phần trong ngoặc tiến về $-3\ne0$.

$$
\lim_{n\to +\infty}\left(4 \cdot 2^{n} - 3 \cdot 4^{n}\right)=\lim_{n\to+\infty}4^n\left(-3+4\left(\frac{2}{4}\right)^n\right)=-\infty.
$$




### Bài D03.08 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(5^{n} + 6 \cdot 7^{n}\right)$.


**Lời giải chi tiết**

Đặt $7^n$ ra ngoài: $\frac{5}{7}$ có trị tuyệt đối nhỏ hơn $1$ nên lũy thừa của nó tiến về $0$. Phần trong ngoặc tiến về $6\ne0$.

$$
\lim_{n\to +\infty}\left(5^{n} + 6 \cdot 7^{n}\right)=\lim_{n\to+\infty}7^n\left(6+1\left(\frac{5}{7}\right)^n\right)=+\infty.
$$




### Bài D03.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(- 3 \cdot 3^{n} + 2 \cdot 6^{n}\right)$.


**Lời giải chi tiết**

Đặt $6^n$ ra ngoài: $\frac{3}{6}$ có trị tuyệt đối nhỏ hơn $1$ nên lũy thừa của nó tiến về $0$. Phần trong ngoặc tiến về $2\ne0$.

$$
\lim_{n\to +\infty}\left(- 3 \cdot 3^{n} + 2 \cdot 6^{n}\right)=\lim_{n\to+\infty}6^n\left(2-3\left(\frac{3}{6}\right)^n\right)=+\infty.
$$




### Bài D03.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(- 2^{n} - 4 \cdot 5^{n}\right)$.


**Lời giải chi tiết**

Đặt $5^n$ ra ngoài: $\frac{2}{5}$ có trị tuyệt đối nhỏ hơn $1$ nên lũy thừa của nó tiến về $0$. Phần trong ngoặc tiến về $-4\ne0$.

$$
\lim_{n\to +\infty}\left(- 2^{n} - 4 \cdot 5^{n}\right)=\lim_{n\to+\infty}5^n\left(-4-1\left(\frac{2}{5}\right)^n\right)=-\infty.
$$




### Bài D03.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot 3^{n} + 1}{5^{n} + 1}\right)$.


**Lời giải chi tiết**

Cơ số lớn nhất là $5$. Chia cho $5^n$; vì $3/5<1$, mọi tỉ số lũy thừa còn lại tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot 3^{n} + 1}{5^{n} + 1}\right)=\lim_{n\to+\infty}\frac{2\left(\frac{3}{5}\right)^n+\frac{1}{5^n}}{1+\frac1{5^n}}=0.
$$




### Bài D03.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{4 \cdot 2^{n} + 3}{4^{n} + 1}\right)$.


**Lời giải chi tiết**

Cơ số lớn nhất là $4$. Chia cho $4^n$; vì $2/4<1$, mọi tỉ số lũy thừa còn lại tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{4 \cdot 2^{n} + 3}{4^{n} + 1}\right)=\lim_{n\to+\infty}\frac{4\left(\frac{2}{4}\right)^n+\frac{3}{4^n}}{1+\frac1{4^n}}=0.
$$




### Bài D03.13 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 - 2^{n}}{6^{n} + 1}\right)$.


**Lời giải chi tiết**

Cơ số lớn nhất là $6$. Chia cho $6^n$; vì $2/6<1$, mọi tỉ số lũy thừa còn lại tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 - 2^{n}}{6^{n} + 1}\right)=\lim_{n\to+\infty}\frac{-1\left(\frac{2}{6}\right)^n+\frac{2}{6^n}}{1+\frac1{6^n}}=0.
$$




### Bài D03.14 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{3 \cdot 5^{n} + 5}{7^{n} + 1}\right)$.


**Lời giải chi tiết**

Cơ số lớn nhất là $7$. Chia cho $7^n$; vì $5/7<1$, mọi tỉ số lũy thừa còn lại tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{3 \cdot 5^{n} + 5}{7^{n} + 1}\right)=\lim_{n\to+\infty}\frac{3\left(\frac{5}{7}\right)^n+\frac{5}{7^n}}{1+\frac1{7^n}}=0.
$$




### Bài D03.15 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot 4^{n} + 4}{9^{n} + 1}\right)$.


**Lời giải chi tiết**

Cơ số lớn nhất là $9$. Chia cho $9^n$; vì $4/9<1$, mọi tỉ số lũy thừa còn lại tiến về $0$.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot 4^{n} + 4}{9^{n} + 1}\right)=\lim_{n\to+\infty}\frac{2\left(\frac{4}{9}\right)^n+\frac{4}{9^n}}{1+\frac1{9^n}}=0.
$$




### Bài D03.16 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot \left(-1\right)^{n} + 1}{3 \cdot 3^{n} - 1}\right)$.


**Lời giải chi tiết**

Tử có trị tuyệt đối không quá $3$; mẫu tăng về $+\infty$ vì hệ số của $3^n$ là $3>0$. Theo nguyên lí kẹp,

$$
\left|\frac{2(-1)^n+1}{3\cdot3^n-1}\right|\le\frac{3}{3\cdot3^n-1}\xrightarrow[n\to+\infty]{}0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{2 \cdot \left(-1\right)^{n} + 1}{3 \cdot 3^{n} - 1}\right)=0.
$$




### Bài D03.17 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 - \left(-1\right)^{n}}{2 \cdot 3^{n} + 4}\right)$.


**Lời giải chi tiết**

Tử có trị tuyệt đối không quá $3$; mẫu tăng về $+\infty$ vì hệ số của $3^n$ là $2>0$. Theo nguyên lí kẹp,

$$
\left|\frac{-1(-1)^n+2}{2\cdot3^n+4}\right|\le\frac{3}{2\cdot3^n+4}\xrightarrow[n\to+\infty]{}0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{2 - \left(-1\right)^{n}}{2 \cdot 3^{n} + 4}\right)=0.
$$




### Bài D03.18 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{5 \cdot \left(-1\right)^{n}}{3^{n} - 2}\right)$.


**Lời giải chi tiết**

Tử có trị tuyệt đối không quá $5$; mẫu tăng về $+\infty$ vì hệ số của $3^n$ là $1>0$. Theo nguyên lí kẹp,

$$
\left|\frac{5(-1)^n+0}{1\cdot3^n-2}\right|\le\frac{5}{1\cdot3^n-2}\xrightarrow[n\to+\infty]{}0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{5 \cdot \left(-1\right)^{n}}{3^{n} - 2}\right)=0.
$$




### Bài D03.19 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{3 \cdot \left(-1\right)^{n} + 4}{5 \cdot 3^{n} + 7}\right)$.


**Lời giải chi tiết**

Tử có trị tuyệt đối không quá $7$; mẫu tăng về $+\infty$ vì hệ số của $3^n$ là $5>0$. Theo nguyên lí kẹp,

$$
\left|\frac{3(-1)^n+4}{5\cdot3^n+7}\right|\le\frac{7}{5\cdot3^n+7}\xrightarrow[n\to+\infty]{}0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{3 \cdot \left(-1\right)^{n} + 4}{5 \cdot 3^{n} + 7}\right)=0.
$$




### Bài D03.20 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{5 - 2 \cdot \left(-1\right)^{n}}{4 \cdot 3^{n} - 1}\right)$.


**Lời giải chi tiết**

Tử có trị tuyệt đối không quá $7$; mẫu tăng về $+\infty$ vì hệ số của $3^n$ là $4>0$. Theo nguyên lí kẹp,

$$
\left|\frac{-2(-1)^n+5}{4\cdot3^n-1}\right|\le\frac{7}{4\cdot3^n-1}\xrightarrow[n\to+\infty]{}0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{5 - 2 \cdot \left(-1\right)^{n}}{4 \cdot 3^{n} - 1}\right)=0.
$$




---


## Dạng 04. Căn thức: đưa lũy thừa của n ra ngoài căn

> [!tip] Phương pháp trọng tâm
> Vì n→+∞ nên n>0; dùng √(n²A)=n√A.


### Bài D04.01 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{4 \cdot n^{2} + 3 \cdot n + 1}}{n}\right)$.


**Lời giải chi tiết**

Vì $n>0$, đưa $n^2$ ra khỏi căn: $\sqrt{n^2A}=n\sqrt A$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{4 \cdot n^{2} + 3 \cdot n + 1}}{n}\right)=\lim_{n\to+\infty}\sqrt{4+\frac{3}n+\frac{1}{n^2}}=2.
$$




### Bài D04.02 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{9 \cdot n^{2} + 5 \cdot n + 2}}{n}\right)$.


**Lời giải chi tiết**

Vì $n>0$, đưa $n^2$ ra khỏi căn: $\sqrt{n^2A}=n\sqrt A$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{9 \cdot n^{2} + 5 \cdot n + 2}}{n}\right)=\lim_{n\to+\infty}\sqrt{9+\frac{5}n+\frac{2}{n^2}}=3.
$$




### Bài D04.03 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{16 \cdot n^{2} - 2 \cdot n + 5}}{n}\right)$.


**Lời giải chi tiết**

Vì $n>0$, đưa $n^2$ ra khỏi căn: $\sqrt{n^2A}=n\sqrt A$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{16 \cdot n^{2} - 2 \cdot n + 5}}{n}\right)=\lim_{n\to+\infty}\sqrt{16+\frac{-2}n+\frac{5}{n^2}}=4.
$$




### Bài D04.04 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{25 \cdot n^{2} + 9 \cdot n + 4}}{n}\right)$.


**Lời giải chi tiết**

Vì $n>0$, đưa $n^2$ ra khỏi căn: $\sqrt{n^2A}=n\sqrt A$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{25 \cdot n^{2} + 9 \cdot n + 4}}{n}\right)=\lim_{n\to+\infty}\sqrt{25+\frac{9}n+\frac{4}{n^2}}=5.
$$




### Bài D04.05 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{36 \cdot n^{2} - 7 \cdot n + 3}}{n}\right)$.


**Lời giải chi tiết**

Vì $n>0$, đưa $n^2$ ra khỏi căn: $\sqrt{n^2A}=n\sqrt A$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{36 \cdot n^{2} - 7 \cdot n + 3}}{n}\right)=\lim_{n\to+\infty}\sqrt{36+\frac{-7}n+\frac{3}{n^2}}=6.
$$




### Bài D04.06 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{4 \cdot n^{2} + n + 1}}{\sqrt{9 \cdot n^{2} + 2 \cdot n + 2}}\right)$.


**Lời giải chi tiết**

Đặt $n$ ra khỏi mỗi căn rồi triệt tiêu, sau đó xét các số hạng chứa $1/n$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{4 \cdot n^{2} + n + 1}}{\sqrt{9 \cdot n^{2} + 2 \cdot n + 2}}\right)=\lim_{n\to+\infty}\frac{\sqrt{4+\frac{1}n+\frac1{n^2}}}{\sqrt{9+\frac{2}n+\frac2{n^2}}}=\frac{2}{3}.
$$




### Bài D04.07 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{9 \cdot n^{2} - 5 \cdot n + 1}}{\sqrt{16 \cdot n^{2} + 3 \cdot n + 2}}\right)$.


**Lời giải chi tiết**

Đặt $n$ ra khỏi mỗi căn rồi triệt tiêu, sau đó xét các số hạng chứa $1/n$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{9 \cdot n^{2} - 5 \cdot n + 1}}{\sqrt{16 \cdot n^{2} + 3 \cdot n + 2}}\right)=\lim_{n\to+\infty}\frac{\sqrt{9+\frac{-5}n+\frac1{n^2}}}{\sqrt{16+\frac{3}n+\frac2{n^2}}}=\frac{3}{4}.
$$




### Bài D04.08 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{16 \cdot n^{2} + 2 \cdot n + 1}}{\sqrt{4 \cdot n^{2} - n + 2}}\right)$.


**Lời giải chi tiết**

Đặt $n$ ra khỏi mỗi căn rồi triệt tiêu, sau đó xét các số hạng chứa $1/n$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{16 \cdot n^{2} + 2 \cdot n + 1}}{\sqrt{4 \cdot n^{2} - n + 2}}\right)=\lim_{n\to+\infty}\frac{\sqrt{16+\frac{2}n+\frac1{n^2}}}{\sqrt{4+\frac{-1}n+\frac2{n^2}}}=2.
$$




### Bài D04.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{25 \cdot n^{2} + 7 \cdot n + 1}}{\sqrt{9 \cdot n^{2} + 2 \cdot n + 2}}\right)$.


**Lời giải chi tiết**

Đặt $n$ ra khỏi mỗi căn rồi triệt tiêu, sau đó xét các số hạng chứa $1/n$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{25 \cdot n^{2} + 7 \cdot n + 1}}{\sqrt{9 \cdot n^{2} + 2 \cdot n + 2}}\right)=\lim_{n\to+\infty}\frac{\sqrt{25+\frac{7}n+\frac1{n^2}}}{\sqrt{9+\frac{2}n+\frac2{n^2}}}=\frac{5}{3}.
$$




### Bài D04.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt{36 \cdot n^{2} + 5 \cdot n + 1}}{\sqrt{4 \cdot n^{2} + n + 2}}\right)$.


**Lời giải chi tiết**

Đặt $n$ ra khỏi mỗi căn rồi triệt tiêu, sau đó xét các số hạng chứa $1/n$.

$$
\lim_{n\to +\infty}\left(\frac{\sqrt{36 \cdot n^{2} + 5 \cdot n + 1}}{\sqrt{4 \cdot n^{2} + n + 2}}\right)=\lim_{n\to+\infty}\frac{\sqrt{36+\frac{5}n+\frac1{n^2}}}{\sqrt{4+\frac{1}n+\frac2{n^2}}}=3.
$$




### Bài D04.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{8 \cdot n^{3} + n}\right|} \cdot \operatorname{sign}{\left(8 \cdot n^{3} + n \right)}}{n}\right)$.


**Lời giải chi tiết**

Dùng $\sqrt[3]{n^3A}=n\sqrt[3]A$ (với $n>0$):

$$
\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{8 \cdot n^{3} + n}\right|} \cdot \operatorname{sign}{\left(8 \cdot n^{3} + n \right)}}{n}\right)=\lim_{n\to+\infty}\sqrt[3]{8+\frac{1}{n^2}}=2.
$$




### Bài D04.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{27 \cdot n^{3} + 4 \cdot n}\right|} \cdot \operatorname{sign}{\left(27 \cdot n^{3} + 4 \cdot n \right)}}{n}\right)$.


**Lời giải chi tiết**

Dùng $\sqrt[3]{n^3A}=n\sqrt[3]A$ (với $n>0$):

$$
\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{27 \cdot n^{3} + 4 \cdot n}\right|} \cdot \operatorname{sign}{\left(27 \cdot n^{3} + 4 \cdot n \right)}}{n}\right)=\lim_{n\to+\infty}\sqrt[3]{27+\frac{4}{n^2}}=3.
$$




### Bài D04.13 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{64 \cdot n^{3} - 3 \cdot n}\right|} \cdot \operatorname{sign}{\left(64 \cdot n^{3} - 3 \cdot n \right)}}{n}\right)$.


**Lời giải chi tiết**

Dùng $\sqrt[3]{n^3A}=n\sqrt[3]A$ (với $n>0$):

$$
\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{64 \cdot n^{3} - 3 \cdot n}\right|} \cdot \operatorname{sign}{\left(64 \cdot n^{3} - 3 \cdot n \right)}}{n}\right)=\lim_{n\to+\infty}\sqrt[3]{64+\frac{-3}{n^2}}=4.
$$




### Bài D04.14 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{125 \cdot n^{3} + 7 \cdot n}\right|} \cdot \operatorname{sign}{\left(125 \cdot n^{3} + 7 \cdot n \right)}}{n}\right)$.


**Lời giải chi tiết**

Dùng $\sqrt[3]{n^3A}=n\sqrt[3]A$ (với $n>0$):

$$
\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{125 \cdot n^{3} + 7 \cdot n}\right|} \cdot \operatorname{sign}{\left(125 \cdot n^{3} + 7 \cdot n \right)}}{n}\right)=\lim_{n\to+\infty}\sqrt[3]{125+\frac{7}{n^2}}=5.
$$




### Bài D04.15 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{216 \cdot n^{3} - 2 \cdot n}\right|} \cdot \operatorname{sign}{\left(216 \cdot n^{3} - 2 \cdot n \right)}}{n}\right)$.


**Lời giải chi tiết**

Dùng $\sqrt[3]{n^3A}=n\sqrt[3]A$ (với $n>0$):

$$
\lim_{n\to +\infty}\left(\frac{\sqrt[3]{\left|{216 \cdot n^{3} - 2 \cdot n}\right|} \cdot \operatorname{sign}{\left(216 \cdot n^{3} - 2 \cdot n \right)}}{n}\right)=\lim_{n\to+\infty}\sqrt[3]{216+\frac{-2}{n^2}}=6.
$$




### Bài D04.16 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{n + \sqrt{4 \cdot n^{2} + 5 \cdot n + 1}}{n}\right)$.


**Lời giải chi tiết**

Chia cả hai hạng tử của tử cho $n$ rồi tách căn như trên.

$$
\lim_{n\to +\infty}\left(\frac{n + \sqrt{4 \cdot n^{2} + 5 \cdot n + 1}}{n}\right)=\lim_{n\to+\infty}\left(\sqrt{4+\frac{5}n+\frac1{n^2}}+(1)\right)=3.
$$




### Bài D04.17 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{- 2 \cdot n + \sqrt{9 \cdot n^{2} + 3 \cdot n + 1}}{n}\right)$.


**Lời giải chi tiết**

Chia cả hai hạng tử của tử cho $n$ rồi tách căn như trên.

$$
\lim_{n\to +\infty}\left(\frac{- 2 \cdot n + \sqrt{9 \cdot n^{2} + 3 \cdot n + 1}}{n}\right)=\lim_{n\to+\infty}\left(\sqrt{9+\frac{3}n+\frac1{n^2}}-2\right)=1.
$$




### Bài D04.18 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{4 \cdot n + \sqrt{16 \cdot n^{2} - 3 \cdot n + 1}}{n}\right)$.


**Lời giải chi tiết**

Chia cả hai hạng tử của tử cho $n$ rồi tách căn như trên.

$$
\lim_{n\to +\infty}\left(\frac{4 \cdot n + \sqrt{16 \cdot n^{2} - 3 \cdot n + 1}}{n}\right)=\lim_{n\to+\infty}\left(\sqrt{16+\frac{-3}n+\frac1{n^2}}+(4)\right)=8.
$$




### Bài D04.19 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2 \cdot n + \sqrt{25 \cdot n^{2} + 6 \cdot n + 1}}{n}\right)$.


**Lời giải chi tiết**

Chia cả hai hạng tử của tử cho $n$ rồi tách căn như trên.

$$
\lim_{n\to +\infty}\left(\frac{2 \cdot n + \sqrt{25 \cdot n^{2} + 6 \cdot n + 1}}{n}\right)=\lim_{n\to+\infty}\left(\sqrt{25+\frac{6}n+\frac1{n^2}}+(2)\right)=7.
$$




### Bài D04.20 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{n + \sqrt{36 \cdot n^{2} - n + 1}}{n}\right)$.


**Lời giải chi tiết**

Chia cả hai hạng tử của tử cho $n$ rồi tách căn như trên.

$$
\lim_{n\to +\infty}\left(\frac{n + \sqrt{36 \cdot n^{2} - n + 1}}{n}\right)=\lim_{n\to+\infty}\left(\sqrt{36+\frac{-1}n+\frac1{n^2}}+(1)\right)=7.
$$




---


## Dạng 05. Căn thức: nhân liên hợp

> [!tip] Phương pháp trọng tâm
> Nhân chia biểu thức liên hợp để xử lí dạng ∞−∞ hoặc 0·∞.


### Bài D05.01 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} + 2 \cdot n + 1}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp; sau đó chia tử và mẫu cho $n>0$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} + 2 \cdot n + 1}\right)&=\lim_{n\to+\infty}\frac{2n+1}{\sqrt{n^2+2n+1}+n}\\&=\lim_{n\to+\infty}\frac{2+\frac{1}n}{\sqrt{1+\frac{2}n+\frac{1}{n^2}}+1}=1.\end{aligned}
$$




### Bài D05.02 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} + 4 \cdot n + 3}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp; sau đó chia tử và mẫu cho $n>0$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} + 4 \cdot n + 3}\right)&=\lim_{n\to+\infty}\frac{4n+3}{\sqrt{n^2+4n+3}+n}\\&=\lim_{n\to+\infty}\frac{4+\frac{3}n}{\sqrt{1+\frac{4}n+\frac{3}{n^2}}+1}=2.\end{aligned}
$$




### Bài D05.03 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} - 3 \cdot n + 10}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp; sau đó chia tử và mẫu cho $n>0$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} - 3 \cdot n + 10}\right)&=\lim_{n\to+\infty}\frac{-3n+10}{\sqrt{n^2-3n+10}+n}\\&=\lim_{n\to+\infty}\frac{-3+\frac{10}n}{\sqrt{1+\frac{-3}n+\frac{10}{n^2}}+1}=- \frac{3}{2}.\end{aligned}
$$




### Bài D05.04 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} + 6 \cdot n + 7}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp; sau đó chia tử và mẫu cho $n>0$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} + 6 \cdot n + 7}\right)&=\lim_{n\to+\infty}\frac{6n+7}{\sqrt{n^2+6n+7}+n}\\&=\lim_{n\to+\infty}\frac{6+\frac{7}n}{\sqrt{1+\frac{6}n+\frac{7}{n^2}}+1}=3.\end{aligned}
$$




### Bài D05.05 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} - 5 \cdot n + 12}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp; sau đó chia tử và mẫu cho $n>0$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- n + \sqrt{n^{2} - 5 \cdot n + 12}\right)&=\lim_{n\to+\infty}\frac{-5n+12}{\sqrt{n^2-5n+12}+n}\\&=\lim_{n\to+\infty}\frac{-5+\frac{12}n}{\sqrt{1+\frac{-5}n+\frac{12}{n^2}}+1}=- \frac{5}{2}.\end{aligned}
$$




### Bài D05.06 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 + \frac{3}{n} + \frac{2}{n^{2}}} - 1\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp bên trong ngoặc, $n$ ở ngoài sẽ triệt tiêu $1/n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 + \frac{3}{n} + \frac{2}{n^{2}}} - 1\right)\right)&=\lim_{n\to+\infty}\frac{3+\frac{2}n}{\sqrt{1+\frac{3}n+\frac{2}{n^2}}+1}\\&=\frac{3}2=\frac{3}{2}.\end{aligned}
$$




### Bài D05.07 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 + \frac{5}{n} + \frac{4}{n^{2}}} - 1\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp bên trong ngoặc, $n$ ở ngoài sẽ triệt tiêu $1/n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 + \frac{5}{n} + \frac{4}{n^{2}}} - 1\right)\right)&=\lim_{n\to+\infty}\frac{5+\frac{4}n}{\sqrt{1+\frac{5}n+\frac{4}{n^2}}+1}\\&=\frac{5}2=\frac{5}{2}.\end{aligned}
$$




### Bài D05.08 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 + \frac{8}{n} + \frac{5}{n^{2}}} - 1\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp bên trong ngoặc, $n$ ở ngoài sẽ triệt tiêu $1/n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 + \frac{8}{n} + \frac{5}{n^{2}}} - 1\right)\right)&=\lim_{n\to+\infty}\frac{8+\frac{5}n}{\sqrt{1+\frac{8}n+\frac{5}{n^2}}+1}\\&=\frac{8}2=4.\end{aligned}
$$




### Bài D05.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 - \frac{2}{n} + \frac{7}{n^{2}}} - 1\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp bên trong ngoặc, $n$ ở ngoài sẽ triệt tiêu $1/n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 - \frac{2}{n} + \frac{7}{n^{2}}} - 1\right)\right)&=\lim_{n\to+\infty}\frac{-2+\frac{7}n}{\sqrt{1+\frac{-2}n+\frac{7}{n^2}}+1}\\&=\frac{-2}2=-1.\end{aligned}
$$




### Bài D05.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 - \frac{4}{n} + \frac{12}{n^{2}}} - 1\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp bên trong ngoặc, $n$ ở ngoài sẽ triệt tiêu $1/n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(\sqrt{1 - \frac{4}{n} + \frac{12}{n^{2}}} - 1\right)\right)&=\lim_{n\to+\infty}\frac{-4+\frac{12}n}{\sqrt{1+\frac{-4}n+\frac{12}{n^2}}+1}\\&=\frac{-4}2=-2.\end{aligned}
$$




### Bài D05.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 2}\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp hiệu căn và $n$ rồi chia mẫu cho $n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 2}\right)\right)&=\lim_{n\to+\infty}\frac{2n}{\sqrt{n^2+2}+n}\\&=\lim_{n\to+\infty}\frac{2}{\sqrt{1+\frac{2}{n^2}}+1}=1.\end{aligned}
$$




### Bài D05.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 4}\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp hiệu căn và $n$ rồi chia mẫu cho $n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 4}\right)\right)&=\lim_{n\to+\infty}\frac{4n}{\sqrt{n^2+4}+n}\\&=\lim_{n\to+\infty}\frac{4}{\sqrt{1+\frac{4}{n^2}}+1}=2.\end{aligned}
$$




### Bài D05.13 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 6}\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp hiệu căn và $n$ rồi chia mẫu cho $n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 6}\right)\right)&=\lim_{n\to+\infty}\frac{6n}{\sqrt{n^2+6}+n}\\&=\lim_{n\to+\infty}\frac{6}{\sqrt{1+\frac{6}{n^2}}+1}=3.\end{aligned}
$$




### Bài D05.14 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 8}\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp hiệu căn và $n$ rồi chia mẫu cho $n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 8}\right)\right)&=\lim_{n\to+\infty}\frac{8n}{\sqrt{n^2+8}+n}\\&=\lim_{n\to+\infty}\frac{8}{\sqrt{1+\frac{8}{n^2}}+1}=4.\end{aligned}
$$




### Bài D05.15 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 10}\right)\right)$.


**Lời giải chi tiết**

Nhân liên hợp hiệu căn và $n$ rồi chia mẫu cho $n$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(n \cdot \left(- n + \sqrt{n^{2} + 10}\right)\right)&=\lim_{n\to+\infty}\frac{10n}{\sqrt{n^2+10}+n}\\&=\lim_{n\to+\infty}\frac{10}{\sqrt{1+\frac{10}{n^2}}+1}=5.\end{aligned}
$$




### Bài D05.16 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(- 2 \cdot n + \sqrt{4 \cdot n^{2} + 6 \cdot n}\right)$.


**Lời giải chi tiết**

Hai phần vô hạn cùng bậc triệt tiêu. Nhân liên hợp rồi đưa $n$ ra khỏi căn ở mẫu.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- 2 \cdot n + \sqrt{4 \cdot n^{2} + 6 \cdot n}\right)&=\lim_{n\to+\infty}\frac{6n}{\sqrt{4n^2+6n}+2n}\\&=\lim_{n\to+\infty}\frac{6}{\sqrt{4+\frac{6}n}+2}=\frac{3}{2}.\end{aligned}
$$




### Bài D05.17 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(- 3 \cdot n + \sqrt{9 \cdot n^{2} + 8 \cdot n}\right)$.


**Lời giải chi tiết**

Hai phần vô hạn cùng bậc triệt tiêu. Nhân liên hợp rồi đưa $n$ ra khỏi căn ở mẫu.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- 3 \cdot n + \sqrt{9 \cdot n^{2} + 8 \cdot n}\right)&=\lim_{n\to+\infty}\frac{8n}{\sqrt{9n^2+8n}+3n}\\&=\lim_{n\to+\infty}\frac{8}{\sqrt{9+\frac{8}n}+3}=\frac{4}{3}.\end{aligned}
$$




### Bài D05.18 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(- 4 \cdot n + \sqrt{16 \cdot n^{2} - 4 \cdot n}\right)$.


**Lời giải chi tiết**

Hai phần vô hạn cùng bậc triệt tiêu. Nhân liên hợp rồi đưa $n$ ra khỏi căn ở mẫu.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- 4 \cdot n + \sqrt{16 \cdot n^{2} - 4 \cdot n}\right)&=\lim_{n\to+\infty}\frac{-4n}{\sqrt{16n^2-4n}+4n}\\&=\lim_{n\to+\infty}\frac{-4}{\sqrt{16+\frac{-4}n}+4}=- \frac{1}{2}.\end{aligned}
$$




### Bài D05.19 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(- 5 \cdot n + \sqrt{25 \cdot n^{2} + 10 \cdot n}\right)$.


**Lời giải chi tiết**

Hai phần vô hạn cùng bậc triệt tiêu. Nhân liên hợp rồi đưa $n$ ra khỏi căn ở mẫu.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- 5 \cdot n + \sqrt{25 \cdot n^{2} + 10 \cdot n}\right)&=\lim_{n\to+\infty}\frac{10n}{\sqrt{25n^2+10n}+5n}\\&=\lim_{n\to+\infty}\frac{10}{\sqrt{25+\frac{10}n}+5}=1.\end{aligned}
$$




### Bài D05.20 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(- 6 \cdot n + \sqrt{36 \cdot n^{2} - 12 \cdot n}\right)$.


**Lời giải chi tiết**

Hai phần vô hạn cùng bậc triệt tiêu. Nhân liên hợp rồi đưa $n$ ra khỏi căn ở mẫu.

$$
\begin{aligned}\lim_{n\to +\infty}\left(- 6 \cdot n + \sqrt{36 \cdot n^{2} - 12 \cdot n}\right)&=\lim_{n\to+\infty}\frac{-12n}{\sqrt{36n^2-12n}+6n}\\&=\lim_{n\to+\infty}\frac{-12}{\sqrt{36+\frac{-12}n}+6}=-1.\end{aligned}
$$




---


## Dạng 06. Định lí kẹp và dãy dao động

> [!tip] Phương pháp trọng tâm
> Đánh giá trị tuyệt đối trước; phân biệt dao động có biên độ về 0 và dao động không có giới hạn.


### Bài D06.01 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{1\sin n}{n^1}\right)$.


**Lời giải chi tiết**

Từ $|\sin n|\le1$, suy ra biên độ tiến về $0$.

$$
0\le\left|\frac{1\sin n}{n^1}\right|\le\frac{1}{n^1}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{1\sin n}{n^1}\right)=0.
$$




### Bài D06.02 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{3\cos n}{n^2}\right)$.


**Lời giải chi tiết**

Từ $|\cos n|\le1$, suy ra biên độ tiến về $0$.

$$
0\le\left|\frac{3\cos n}{n^2}\right|\le\frac{3}{n^2}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{3\cos n}{n^2}\right)=0.
$$




### Bài D06.03 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{-5\sin (2n)}{n^2}\right)$.


**Lời giải chi tiết**

Từ $|\sin (2n)|\le1$, suy ra biên độ tiến về $0$.

$$
0\le\left|\frac{-5\sin (2n)}{n^2}\right|\le\frac{5}{n^2}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{-5\sin (2n)}{n^2}\right)=0.
$$




### Bài D06.04 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{7\cos (3n)}{n^3}\right)$.


**Lời giải chi tiết**

Từ $|\cos (3n)|\le1$, suy ra biên độ tiến về $0$.

$$
0\le\left|\frac{7\cos (3n)}{n^3}\right|\le\frac{7}{n^3}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{7\cos (3n)}{n^3}\right)=0.
$$




### Bài D06.05 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{2\sin (n^2)}{n^4}\right)$.


**Lời giải chi tiết**

Từ $|\sin (n^2)|\le1$, suy ra biên độ tiến về $0$.

$$
0\le\left|\frac{2\sin (n^2)}{n^4}\right|\le\frac{2}{n^4}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{2\sin (n^2)}{n^4}\right)=0.
$$




### Bài D06.06 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{1(-1)^n}{n^1}\right)$.


**Lời giải chi tiết**

Mặc dù $(-1)^n$ đổi dấu liên tục, trị tuyệt đối của nó bằng $1$.

$$
0\le\left|\frac{1(-1)^n}{n^1}\right|=\frac{1}{n^1}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{1(-1)^n}{n^1}\right)=0.
$$




### Bài D06.07 · Nhận biết

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{4(-1)^n}{n^2}\right)$.


**Lời giải chi tiết**

Mặc dù $(-1)^n$ đổi dấu liên tục, trị tuyệt đối của nó bằng $1$.

$$
0\le\left|\frac{4(-1)^n}{n^2}\right|=\frac{4}{n^2}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{4(-1)^n}{n^2}\right)=0.
$$




### Bài D06.08 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{-3(-1)^n}{n^1}\right)$.


**Lời giải chi tiết**

Mặc dù $(-1)^n$ đổi dấu liên tục, trị tuyệt đối của nó bằng $1$.

$$
0\le\left|\frac{-3(-1)^n}{n^1}\right|=\frac{3}{n^1}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{-3(-1)^n}{n^1}\right)=0.
$$




### Bài D06.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{6(-1)^n}{n^3}\right)$.


**Lời giải chi tiết**

Mặc dù $(-1)^n$ đổi dấu liên tục, trị tuyệt đối của nó bằng $1$.

$$
0\le\left|\frac{6(-1)^n}{n^3}\right|=\frac{6}{n^3}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{6(-1)^n}{n^3}\right)=0.
$$




### Bài D06.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{-7(-1)^n}{n^4}\right)$.


**Lời giải chi tiết**

Mặc dù $(-1)^n$ đổi dấu liên tục, trị tuyệt đối của nó bằng $1$.

$$
0\le\left|\frac{-7(-1)^n}{n^4}\right|=\frac{7}{n^4}\to0\quad\Rightarrow\quad \lim_{n\to +\infty}\left(\frac{-7(-1)^n}{n^4}\right)=0.
$$




### Bài D06.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(2+\frac{1\sin n}{n^1}\right)$.


**Lời giải chi tiết**

Phần chứa $\sin n$ có trị tuyệt đối không vượt quá $|b|/n^p\to0$. Phần còn lại là hằng số.

$$
\lim_{n\to +\infty}\left(2+\frac{1\sin n}{n^1}\right)=2+0=2.
$$




### Bài D06.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(-3+\frac{5\sin n}{n^2}\right)$.


**Lời giải chi tiết**

Phần chứa $\sin n$ có trị tuyệt đối không vượt quá $|b|/n^p\to0$. Phần còn lại là hằng số.

$$
\lim_{n\to +\infty}\left(-3+\frac{5\sin n}{n^2}\right)=-3+0=-3.
$$




### Bài D06.13 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(4+\frac{-2\sin n}{n^3}\right)$.


**Lời giải chi tiết**

Phần chứa $\sin n$ có trị tuyệt đối không vượt quá $|b|/n^p\to0$. Phần còn lại là hằng số.

$$
\lim_{n\to +\infty}\left(4+\frac{-2\sin n}{n^3}\right)=4+0=4.
$$




### Bài D06.14 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(-5+\frac{7\sin n}{n^1}\right)$.


**Lời giải chi tiết**

Phần chứa $\sin n$ có trị tuyệt đối không vượt quá $|b|/n^p\to0$. Phần còn lại là hằng số.

$$
\lim_{n\to +\infty}\left(-5+\frac{7\sin n}{n^1}\right)=-5+0=-5.
$$




### Bài D06.15 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(8+\frac{1\sin n}{n^4}\right)$.


**Lời giải chi tiết**

Phần chứa $\sin n$ có trị tuyệt đối không vượt quá $|b|/n^p\to0$. Phần còn lại là hằng số.

$$
\lim_{n\to +\infty}\left(8+\frac{1\sin n}{n^4}\right)=8+0=8.
$$




### Bài D06.16 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(2(-1)^n+(0)\right)$.


**Lời giải chi tiết**

Xét riêng chỉ số chẵn và lẻ: với $n=2k$, số hạng bằng $2$; với $n=2k+1$, bằng $-2$. Hai giá trị khác nhau nên dãy **không có giới hạn**.

$$
\begin{aligned}u_{2k}&=2,\\u_{2k+1}&=-2.\end{aligned}
$$




### Bài D06.17 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(1(-1)^n+(3)\right)$.


**Lời giải chi tiết**

Xét riêng chỉ số chẵn và lẻ: với $n=2k$, số hạng bằng $4$; với $n=2k+1$, bằng $2$. Hai giá trị khác nhau nên dãy **không có giới hạn**.

$$
\begin{aligned}u_{2k}&=4,\\u_{2k+1}&=2.\end{aligned}
$$




### Bài D06.18 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(-3(-1)^n+(2)\right)$.


**Lời giải chi tiết**

Xét riêng chỉ số chẵn và lẻ: với $n=2k$, số hạng bằng $-1$; với $n=2k+1$, bằng $5$. Hai giá trị khác nhau nên dãy **không có giới hạn**.

$$
\begin{aligned}u_{2k}&=-1,\\u_{2k+1}&=5.\end{aligned}
$$




### Bài D06.19 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(5(-1)^n-1\right)$.


**Lời giải chi tiết**

Xét riêng chỉ số chẵn và lẻ: với $n=2k$, số hạng bằng $4$; với $n=2k+1$, bằng $-6$. Hai giá trị khác nhau nên dãy **không có giới hạn**.

$$
\begin{aligned}u_{2k}&=4,\\u_{2k+1}&=-6.\end{aligned}
$$




### Bài D06.20 · Vận dụng

Tính giới hạn $\lim_{n\to +\infty}\left(-4(-1)^n-2\right)$.


**Lời giải chi tiết**

Xét riêng chỉ số chẵn và lẻ: với $n=2k$, số hạng bằng $-6$; với $n=2k+1$, bằng $2$. Hai giá trị khác nhau nên dãy **không có giới hạn**.

$$
\begin{aligned}u_{2k}&=-6,\\u_{2k+1}&=2.\end{aligned}
$$




---


## Dạng 07. Cấp số nhân lùi vô hạn

> [!tip] Phương pháp trọng tâm
> Tính công bội, kiểm tra |q|<1, rồi sử dụng S=u₁/(1−q).


### Bài D07.01 · Nhận biết

Tính tổng $S=1+1\left(\frac1{2}\right)+1\left(\frac1{2}\right)^2+\cdots$.


**Lời giải chi tiết**

Số hạng đầu $u_1=1$, công bội $q=1/2$ thỏa $|q|<1$. Áp dụng công thức tổng vô hạn:

$$
S=\frac{u_1}{1-q}=\frac{1}{1-\frac1{2}}=2.
$$




### Bài D07.02 · Nhận biết

Tính tổng $S=3+3\left(\frac1{4}\right)+3\left(\frac1{4}\right)^2+\cdots$.


**Lời giải chi tiết**

Số hạng đầu $u_1=3$, công bội $q=1/4$ thỏa $|q|<1$. Áp dụng công thức tổng vô hạn:

$$
S=\frac{u_1}{1-q}=\frac{3}{1-\frac1{4}}=4.
$$




### Bài D07.03 · Nhận biết

Tính tổng $S=5+5\left(\frac1{3}\right)+5\left(\frac1{3}\right)^2+\cdots$.


**Lời giải chi tiết**

Số hạng đầu $u_1=5$, công bội $q=1/3$ thỏa $|q|<1$. Áp dụng công thức tổng vô hạn:

$$
S=\frac{u_1}{1-q}=\frac{5}{1-\frac1{3}}=\frac{15}{2}.
$$




### Bài D07.04 · Nhận biết

Tính tổng $S=2+2\left(\frac1{5}\right)+2\left(\frac1{5}\right)^2+\cdots$.


**Lời giải chi tiết**

Số hạng đầu $u_1=2$, công bội $q=1/5$ thỏa $|q|<1$. Áp dụng công thức tổng vô hạn:

$$
S=\frac{u_1}{1-q}=\frac{2}{1-\frac1{5}}=\frac{5}{2}.
$$




### Bài D07.05 · Nhận biết

Tính tổng $S=7+7\left(\frac1{10}\right)+7\left(\frac1{10}\right)^2+\cdots$.


**Lời giải chi tiết**

Số hạng đầu $u_1=7$, công bội $q=1/10$ thỏa $|q|<1$. Áp dụng công thức tổng vô hạn:

$$
S=\frac{u_1}{1-q}=\frac{7}{1-\frac1{10}}=\frac{70}{9}.
$$




### Bài D07.06 · Nhận biết

Tính tổng luân phiên dấu $S=2-\frac{2}{2}+\frac{2}{4}-\cdots$.


**Lời giải chi tiết**

Công bội $q=-1/2$: dấu âm cho biết các số hạng luân phiên dấu, nhưng $|q|<1$.

$$
S=\frac{2}{1-\left(-\frac1{2}\right)}=\frac{4}{3}.
$$




### Bài D07.07 · Nhận biết

Tính tổng luân phiên dấu $S=3-\frac{3}{3}+\frac{3}{9}-\cdots$.


**Lời giải chi tiết**

Công bội $q=-1/3$: dấu âm cho biết các số hạng luân phiên dấu, nhưng $|q|<1$.

$$
S=\frac{3}{1-\left(-\frac1{3}\right)}=\frac{9}{4}.
$$




### Bài D07.08 · Thông hiểu

Tính tổng luân phiên dấu $S=5-\frac{5}{4}+\frac{5}{16}-\cdots$.


**Lời giải chi tiết**

Công bội $q=-1/4$: dấu âm cho biết các số hạng luân phiên dấu, nhưng $|q|<1$.

$$
S=\frac{5}{1-\left(-\frac1{4}\right)}=4.
$$




### Bài D07.09 · Thông hiểu

Tính tổng luân phiên dấu $S=4-\frac{4}{5}+\frac{4}{25}-\cdots$.


**Lời giải chi tiết**

Công bội $q=-1/5$: dấu âm cho biết các số hạng luân phiên dấu, nhưng $|q|<1$.

$$
S=\frac{4}{1-\left(-\frac1{5}\right)}=\frac{10}{3}.
$$




### Bài D07.10 · Thông hiểu

Tính tổng luân phiên dấu $S=7-\frac{7}{6}+\frac{7}{36}-\cdots$.


**Lời giải chi tiết**

Công bội $q=-1/6$: dấu âm cho biết các số hạng luân phiên dấu, nhưng $|q|<1$.

$$
S=\frac{7}{1-\left(-\frac1{6}\right)}=6.
$$




### Bài D07.11 · Thông hiểu

Viết số thập phân vô hạn tuần hoàn $0,\overline{12}$ dưới dạng phân số tối giản.


**Lời giải chi tiết**

Mỗi chu kì gồm hai chữ số nên

$$
\begin{aligned}S&=\frac{12}{100}+\frac{12}{100^2}+\cdots\\&=\frac{\frac{12}{100}}{1-\frac1{100}}=\frac{12}{99}=\frac{4}{33}.\end{aligned}
$$




### Bài D07.12 · Thông hiểu

Viết số thập phân vô hạn tuần hoàn $0,\overline{27}$ dưới dạng phân số tối giản.


**Lời giải chi tiết**

Mỗi chu kì gồm hai chữ số nên

$$
\begin{aligned}S&=\frac{27}{100}+\frac{27}{100^2}+\cdots\\&=\frac{\frac{27}{100}}{1-\frac1{100}}=\frac{27}{99}=\frac{3}{11}.\end{aligned}
$$




### Bài D07.13 · Thông hiểu

Viết số thập phân vô hạn tuần hoàn $0,\overline{36}$ dưới dạng phân số tối giản.


**Lời giải chi tiết**

Mỗi chu kì gồm hai chữ số nên

$$
\begin{aligned}S&=\frac{36}{100}+\frac{36}{100^2}+\cdots\\&=\frac{\frac{36}{100}}{1-\frac1{100}}=\frac{36}{99}=\frac{4}{11}.\end{aligned}
$$




### Bài D07.14 · Thông hiểu

Viết số thập phân vô hạn tuần hoàn $0,\overline{45}$ dưới dạng phân số tối giản.


**Lời giải chi tiết**

Mỗi chu kì gồm hai chữ số nên

$$
\begin{aligned}S&=\frac{45}{100}+\frac{45}{100^2}+\cdots\\&=\frac{\frac{45}{100}}{1-\frac1{100}}=\frac{45}{99}=\frac{5}{11}.\end{aligned}
$$




### Bài D07.15 · Vận dụng

Viết số thập phân vô hạn tuần hoàn $0,\overline{81}$ dưới dạng phân số tối giản.


**Lời giải chi tiết**

Mỗi chu kì gồm hai chữ số nên

$$
\begin{aligned}S&=\frac{81}{100}+\frac{81}{100^2}+\cdots\\&=\frac{\frac{81}{100}}{1-\frac1{100}}=\frac{81}{99}=\frac{9}{11}.\end{aligned}
$$




### Bài D07.16 · Vận dụng

Tính tổng cấp số nhân $S=3+3\left(\frac{2}{5}\right)+3\left(\frac{2}{5}\right)^2+\cdots$.


**Lời giải chi tiết**

Đọc từ biểu thức $u_1=3$ và $q=\frac{2}{5}$, có $|q|<1$.

$$
S=\frac{u_1}{1-q}=\frac{3}{1-\left(\frac{2}{5}\right)}=5.
$$




### Bài D07.17 · Vận dụng

Tính tổng cấp số nhân $S=5+5\left(\frac{3}{4}\right)+5\left(\frac{3}{4}\right)^2+\cdots$.


**Lời giải chi tiết**

Đọc từ biểu thức $u_1=5$ và $q=\frac{3}{4}$, có $|q|<1$.

$$
S=\frac{u_1}{1-q}=\frac{5}{1-\left(\frac{3}{4}\right)}=20.
$$




### Bài D07.18 · Vận dụng

Tính tổng cấp số nhân $S=2+2\left(\frac{1}{3}\right)+2\left(\frac{1}{3}\right)^2+\cdots$.


**Lời giải chi tiết**

Đọc từ biểu thức $u_1=2$ và $q=\frac{1}{3}$, có $|q|<1$.

$$
S=\frac{u_1}{1-q}=\frac{2}{1-\left(\frac{1}{3}\right)}=3.
$$




### Bài D07.19 · Vận dụng

Tính tổng cấp số nhân $S=7+7\left(- \frac{2}{3}\right)+7\left(- \frac{2}{3}\right)^2+\cdots$.


**Lời giải chi tiết**

Đọc từ biểu thức $u_1=7$ và $q=- \frac{2}{3}$, có $|q|<1$.

$$
S=\frac{u_1}{1-q}=\frac{7}{1-\left(- \frac{2}{3}\right)}=\frac{21}{5}.
$$




### Bài D07.20 · Vận dụng

Tính tổng cấp số nhân $S=6+6\left(- \frac{3}{5}\right)+6\left(- \frac{3}{5}\right)^2+\cdots$.


**Lời giải chi tiết**

Đọc từ biểu thức $u_1=6$ và $q=- \frac{3}{5}$, có $|q|<1$.

$$
S=\frac{u_1}{1-q}=\frac{6}{1-\left(- \frac{3}{5}\right)}=\frac{15}{4}.
$$




---


## Dạng 08. Tổng dãy số và dãy truy hồi

> [!tip] Phương pháp trọng tâm
> Biến đổi tổng rút gọn, hoặc tìm điểm bất động của công thức truy hồi.


### Bài D08.01 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{1}{(k+1)(k+2)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{1}{(k+1)(k+2)}=\left(\frac1{k+1}-\frac1{k+2}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=\left(\frac1{2}-\frac1{n+2}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{1}{2}.
$$




### Bài D08.02 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{2}{(k+2)(k+3)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{2}{(k+2)(k+3)}=2\left(\frac1{k+2}-\frac1{k+3}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=2\left(\frac1{3}-\frac1{n+3}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{2}{3}.
$$




### Bài D08.03 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{2}{(k+3)(k+4)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{2}{(k+3)(k+4)}=2\left(\frac1{k+3}-\frac1{k+4}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=2\left(\frac1{4}-\frac1{n+4}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{1}{2}.
$$




### Bài D08.04 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{1}{(k+4)(k+5)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{1}{(k+4)(k+5)}=\left(\frac1{k+4}-\frac1{k+5}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=\left(\frac1{5}-\frac1{n+5}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{1}{5}.
$$




### Bài D08.05 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{4}{(k+5)(k+6)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{4}{(k+5)(k+6)}=4\left(\frac1{k+5}-\frac1{k+6}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=4\left(\frac1{6}-\frac1{n+6}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{2}{3}.
$$




### Bài D08.06 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{1}{(k+2)(k+3)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{1}{(k+2)(k+3)}=\left(\frac1{k+2}-\frac1{k+3}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=\left(\frac1{3}-\frac1{n+3}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{1}{3}.
$$




### Bài D08.07 · Nhận biết

Cho $S_n=\sum_{k=1}^n\frac{6}{(k+3)(k+4)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{6}{(k+3)(k+4)}=6\left(\frac1{k+3}-\frac1{k+4}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=6\left(\frac1{4}-\frac1{n+4}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{3}{2}.
$$




### Bài D08.08 · Thông hiểu

Cho $S_n=\sum_{k=1}^n\frac{1}{(k+6)(k+7)}$. Tính $\lim_{n\to +\infty}\left(S_n\right)$.


**Lời giải chi tiết**

Tách phân thức theo hiệu hai phân thức liên tiếp:

$$
\frac{1}{(k+6)(k+7)}=\left(\frac1{k+6}-\frac1{k+7}\right).
$$

Khi cộng từ $k=1$ đến $n$, các số hạng giữa triệt tiêu:

$$
S_n=\left(\frac1{7}-\frac1{n+7}\right)\quad\Rightarrow\quad\lim_{n\to+\infty}S_n=\frac{1}{7}.
$$




### Bài D08.09 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+2)}{n^2}\right)$.


**Lời giải chi tiết**

Dùng công thức $1+2+\cdots+n=n(n+1)/2$, sau đó chia cho $n^2$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+2)}{n^2}\right)&=\lim_{n\to+\infty}\frac{\frac{n(n+1)}2+2n}{n^2}\\&=\lim_{n\to+\infty}\left(\frac12+\frac{2+\frac12}n\right)=\frac12.\end{aligned}
$$




### Bài D08.10 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+3)}{n^2}\right)$.


**Lời giải chi tiết**

Dùng công thức $1+2+\cdots+n=n(n+1)/2$, sau đó chia cho $n^2$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+3)}{n^2}\right)&=\lim_{n\to+\infty}\frac{\frac{n(n+1)}2+3n}{n^2}\\&=\lim_{n\to+\infty}\left(\frac12+\frac{3+\frac12}n\right)=\frac12.\end{aligned}
$$




### Bài D08.11 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+4)}{n^2}\right)$.


**Lời giải chi tiết**

Dùng công thức $1+2+\cdots+n=n(n+1)/2$, sau đó chia cho $n^2$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+4)}{n^2}\right)&=\lim_{n\to+\infty}\frac{\frac{n(n+1)}2+4n}{n^2}\\&=\lim_{n\to+\infty}\left(\frac12+\frac{4+\frac12}n\right)=\frac12.\end{aligned}
$$




### Bài D08.12 · Thông hiểu

Tính giới hạn $\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+5)}{n^2}\right)$.


**Lời giải chi tiết**

Dùng công thức $1+2+\cdots+n=n(n+1)/2$, sau đó chia cho $n^2$.

$$
\begin{aligned}\lim_{n\to +\infty}\left(\frac{\sum_{k=1}^n(k+5)}{n^2}\right)&=\lim_{n\to+\infty}\frac{\frac{n(n+1)}2+5n}{n^2}\\&=\lim_{n\to+\infty}\left(\frac12+\frac{5+\frac12}n\right)=\frac12.\end{aligned}
$$




### Bài D08.13 · Thông hiểu

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=0,\\u_{n+1}=\frac{1}{2}u_n+(\frac{3}{2}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=\frac{1}{2}L+(\frac{3}{2})$, giải được $L=3$. Đặt $v_n=u_n-(3)$, suy ra $v_{n+1}=\frac{1}{2}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1-(3))\left(\frac{1}{2}\right)^{n-1}\\u_n&=3+(0-(3))\left(\frac{1}{2}\right)^{n-1}\longrightarrow 3\end{aligned}
$$

Vì $|q|=\frac{1}{2}<1$, kết quả là $\boxed{3}$.


### Bài D08.14 · Thông hiểu

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=2,\\u_{n+1}=\frac{1}{3}u_n+(\frac{8}{3}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=\frac{1}{3}L+(\frac{8}{3})$, giải được $L=4$. Đặt $v_n=u_n-(4)$, suy ra $v_{n+1}=\frac{1}{3}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1-(4))\left(\frac{1}{3}\right)^{n-1}\\u_n&=4+(2-(4))\left(\frac{1}{3}\right)^{n-1}\longrightarrow 4\end{aligned}
$$

Vì $|q|=\frac{1}{3}<1$, kết quả là $\boxed{4}$.


### Bài D08.15 · Vận dụng

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=-1,\\u_{n+1}=\frac{2}{3}u_n+(\frac{5}{3}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=\frac{2}{3}L+(\frac{5}{3})$, giải được $L=5$. Đặt $v_n=u_n-(5)$, suy ra $v_{n+1}=\frac{2}{3}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1-(5))\left(\frac{2}{3}\right)^{n-1}\\u_n&=5+(-1-(5))\left(\frac{2}{3}\right)^{n-1}\longrightarrow 5\end{aligned}
$$

Vì $|q|=\frac{2}{3}<1$, kết quả là $\boxed{5}$.


### Bài D08.16 · Vận dụng

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=10,\\u_{n+1}=- \frac{1}{2}u_n+(3),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=- \frac{1}{2}L+(3)$, giải được $L=2$. Đặt $v_n=u_n-(2)$, suy ra $v_{n+1}=- \frac{1}{2}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1-(2))\left(- \frac{1}{2}\right)^{n-1}\\u_n&=2+(10-(2))\left(- \frac{1}{2}\right)^{n-1}\longrightarrow 2\end{aligned}
$$

Vì $|q|=\frac{1}{2}<1$, kết quả là $\boxed{2}$.


### Bài D08.17 · Vận dụng

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=0,\\u_{n+1}=\frac{1}{4}u_n+(- \frac{9}{4}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=\frac{1}{4}L+(- \frac{9}{4})$, giải được $L=-3$. Đặt $v_n=u_n+3$, suy ra $v_{n+1}=\frac{1}{4}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1+3)\left(\frac{1}{4}\right)^{n-1}\\u_n&=-3+(0+3)\left(\frac{1}{4}\right)^{n-1}\longrightarrow -3\end{aligned}
$$

Vì $|q|=\frac{1}{4}<1$, kết quả là $\boxed{-3}$.


### Bài D08.18 · Vận dụng

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=1,\\u_{n+1}=- \frac{1}{3}u_n+(\frac{28}{3}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=- \frac{1}{3}L+(\frac{28}{3})$, giải được $L=7$. Đặt $v_n=u_n-(7)$, suy ra $v_{n+1}=- \frac{1}{3}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1-(7))\left(- \frac{1}{3}\right)^{n-1}\\u_n&=7+(1-(7))\left(- \frac{1}{3}\right)^{n-1}\longrightarrow 7\end{aligned}
$$

Vì $|q|=\frac{1}{3}<1$, kết quả là $\boxed{7}$.


### Bài D08.19 · Vận dụng

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=5,\\u_{n+1}=\frac{2}{5}u_n+(- \frac{6}{5}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=\frac{2}{5}L+(- \frac{6}{5})$, giải được $L=-2$. Đặt $v_n=u_n+2$, suy ra $v_{n+1}=\frac{2}{5}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1+2)\left(\frac{2}{5}\right)^{n-1}\\u_n&=-2+(5+2)\left(\frac{2}{5}\right)^{n-1}\longrightarrow -2\end{aligned}
$$

Vì $|q|=\frac{2}{5}<1$, kết quả là $\boxed{-2}$.


### Bài D08.20 · Vận dụng

Cho dãy số $(u_n)$ xác định bởi 
$$
\begin{cases}u_1=0,\\u_{n+1}=\frac{3}{4}u_n+(\frac{3}{2}),\ n\ge1.\end{cases}
$$

Tính $\lim_{n\to+\infty}u_n$.


**Lời giải chi tiết**

Tìm điểm bất động: nếu $u_n$ tiến tới $L$ thì $L=\frac{3}{4}L+(\frac{3}{2})$, giải được $L=6$. Đặt $v_n=u_n-(6)$, suy ra $v_{n+1}=\frac{3}{4}v_n$. Do đó

$$
\begin{aligned}v_n&=(u_1-(6))\left(\frac{3}{4}\right)^{n-1}\\u_n&=6+(0-(6))\left(\frac{3}{4}\right)^{n-1}\longrightarrow 6\end{aligned}
$$

Vì $|q|=\frac{3}{4}<1$, kết quả là $\boxed{6}$.


---


# PHẦN B · GIỚI HẠN HÀM SỐ


## Dạng 09. Thay trực tiếp và định lí giới hạn

> [!tip] Phương pháp trọng tâm
> Chỉ thay trực tiếp khi biểu thức xác định và không tạo dạng vô định.


### Bài D09.01 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(x^{2} + 2 \cdot x + 3\right)$.


**Lời giải chi tiết**

Đa thức liên tục tại mọi điểm. Thay $x=1$ trực tiếp:

$$
\lim_{x\to 1}\left(x^{2} + 2 \cdot x + 3\right)=1^2+(2)\cdot(1)+(3)=6.
$$




### Bài D09.02 · Nhận biết

Tính giới hạn $\lim_{x\to -1}\left(x^{2} + 3 \cdot x + 1\right)$.


**Lời giải chi tiết**

Đa thức liên tục tại mọi điểm. Thay $x=-1$ trực tiếp:

$$
\lim_{x\to -1}\left(x^{2} + 3 \cdot x + 1\right)=-1^2+(3)\cdot(-1)+(1)=-1.
$$




### Bài D09.03 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(x^{2} - 2 \cdot x + 4\right)$.


**Lời giải chi tiết**

Đa thức liên tục tại mọi điểm. Thay $x=2$ trực tiếp:

$$
\lim_{x\to 2}\left(x^{2} - 2 \cdot x + 4\right)=2^2-2\cdot(2)+(4)=4.
$$




### Bài D09.04 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(x^{2} + 5 \cdot x - 2\right)$.


**Lời giải chi tiết**

Đa thức liên tục tại mọi điểm. Thay $x=0$ trực tiếp:

$$
\lim_{x\to 0}\left(x^{2} + 5 \cdot x - 2\right)=0^2+(5)\cdot(0)-2=-2.
$$




### Bài D09.05 · Nhận biết

Tính giới hạn $\lim_{x\to -2}\left(x^{2} + 4 \cdot x + 3\right)$.


**Lời giải chi tiết**

Đa thức liên tục tại mọi điểm. Thay $x=-2$ trực tiếp:

$$
\lim_{x\to -2}\left(x^{2} + 4 \cdot x + 3\right)=-2^2+(4)\cdot(-2)+(3)=-1.
$$




### Bài D09.06 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{2 \cdot x + 3}{x^{2} + 1}\right)$.


**Lời giải chi tiết**

Tại $x=1$, mẫu $a^2+1=2\ne0$ nên thay trực tiếp được.

$$
\lim_{x\to 1}\left(\frac{2 \cdot x + 3}{x^{2} + 1}\right)=\frac{2\cdot(1)+3}{1^2+1}=\frac{5}{2}.
$$




### Bài D09.07 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{x + 5}{x^{2} + 3}\right)$.


**Lời giải chi tiết**

Tại $x=2$, mẫu $a^2+3=7\ne0$ nên thay trực tiếp được.

$$
\lim_{x\to 2}\left(\frac{x + 5}{x^{2} + 3}\right)=\frac{1\cdot(2)+5}{2^2+3}=1.
$$




### Bài D09.08 · Thông hiểu

Tính giới hạn $\lim_{x\to -1}\left(\frac{4 \cdot x + 2}{x^{2} + 5}\right)$.


**Lời giải chi tiết**

Tại $x=-1$, mẫu $a^2+5=6\ne0$ nên thay trực tiếp được.

$$
\lim_{x\to -1}\left(\frac{4 \cdot x + 2}{x^{2} + 5}\right)=\frac{4\cdot(-1)+2}{-1^2+5}=- \frac{1}{3}.
$$




### Bài D09.09 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\frac{1 - 3 \cdot x}{x^{2} + 2}\right)$.


**Lời giải chi tiết**

Tại $x=0$, mẫu $a^2+2=2\ne0$ nên thay trực tiếp được.

$$
\lim_{x\to 0}\left(\frac{1 - 3 \cdot x}{x^{2} + 2}\right)=\frac{-3\cdot(0)+1}{0^2+2}=\frac{1}{2}.
$$




### Bài D09.10 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{2 \cdot x - 1}{x^{2} + 4}\right)$.


**Lời giải chi tiết**

Tại $x=3$, mẫu $a^2+4=13\ne0$ nên thay trực tiếp được.

$$
\lim_{x\to 3}\left(\frac{2 \cdot x - 1}{x^{2} + 4}\right)=\frac{2\cdot(3)-1}{3^2+4}=\frac{5}{13}.
$$




### Bài D09.11 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\sqrt{4 \cdot x + 3}\right)$.


**Lời giải chi tiết**

Biểu thức trong căn tại $x=0$ bằng $3>0$, căn bậc hai liên tục nên thay trực tiếp:

$$
\lim_{x\to 0}\left(\sqrt{4 \cdot x + 3}\right)=\sqrt{3}=\sqrt{3}.
$$




### Bài D09.12 · Thông hiểu

Tính giới hạn $\lim_{x\to 1}\left(\sqrt{3 \cdot x + 12}\right)$.


**Lời giải chi tiết**

Biểu thức trong căn tại $x=1$ bằng $15>0$, căn bậc hai liên tục nên thay trực tiếp:

$$
\lim_{x\to 1}\left(\sqrt{3 \cdot x + 12}\right)=\sqrt{15}=\sqrt{15}.
$$




### Bài D09.13 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\sqrt{2 \cdot x + 9}\right)$.


**Lời giải chi tiết**

Biểu thức trong căn tại $x=2$ bằng $13>0$, căn bậc hai liên tục nên thay trực tiếp:

$$
\lim_{x\to 2}\left(\sqrt{2 \cdot x + 9}\right)=\sqrt{13}=\sqrt{13}.
$$




### Bài D09.14 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\sqrt{x + 14}\right)$.


**Lời giải chi tiết**

Biểu thức trong căn tại $x=3$ bằng $17>0$, căn bậc hai liên tục nên thay trực tiếp:

$$
\lim_{x\to 3}\left(\sqrt{x + 14}\right)=\sqrt{17}=\sqrt{17}.
$$




### Bài D09.15 · Vận dụng

Tính giới hạn $\lim_{x\to 4}\left(\sqrt{2 \cdot x + 15}\right)$.


**Lời giải chi tiết**

Biểu thức trong căn tại $x=4$ bằng $23>0$, căn bậc hai liên tục nên thay trực tiếp:

$$
\lim_{x\to 4}\left(\sqrt{2 \cdot x + 15}\right)=\sqrt{23}=\sqrt{23}.
$$




### Bài D09.16 · Vận dụng

Tính giới hạn $\lim_{x\to 0}\left(\frac{x^{2} + 2}{x^{2} + x + 7}\right)$.


**Lời giải chi tiết**

Kiểm tra mẫu khi $x=0$: $a^2+ba+c+5=7\ne0$. Dùng định lí thương của các hàm liên tục:

$$
\lim_{x\to 0}\left(\frac{x^{2} + 2}{x^{2} + x + 7}\right)=\frac{2}{7}.
$$




### Bài D09.17 · Vận dụng

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{2} + 3}{x^{2} + 2 \cdot x + 8}\right)$.


**Lời giải chi tiết**

Kiểm tra mẫu khi $x=1$: $a^2+ba+c+5=11\ne0$. Dùng định lí thương của các hàm liên tục:

$$
\lim_{x\to 1}\left(\frac{x^{2} + 3}{x^{2} + 2 \cdot x + 8}\right)=\frac{4}{11}.
$$




### Bài D09.18 · Vận dụng

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{2} + 4}{x^{2} + x + 9}\right)$.


**Lời giải chi tiết**

Kiểm tra mẫu khi $x=-1$: $a^2+ba+c+5=9\ne0$. Dùng định lí thương của các hàm liên tục:

$$
\lim_{x\to -1}\left(\frac{x^{2} + 4}{x^{2} + x + 9}\right)=\frac{5}{9}.
$$




### Bài D09.19 · Vận dụng

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{2} + 2}{x^{2} - x + 7}\right)$.


**Lời giải chi tiết**

Kiểm tra mẫu khi $x=2$: $a^2+ba+c+5=9\ne0$. Dùng định lí thương của các hàm liên tục:

$$
\lim_{x\to 2}\left(\frac{x^{2} + 2}{x^{2} - x + 7}\right)=\frac{2}{3}.
$$




### Bài D09.20 · Vận dụng

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{2} + 5}{x^{2} + 2 \cdot x + 10}\right)$.


**Lời giải chi tiết**

Kiểm tra mẫu khi $x=3$: $a^2+ba+c+5=25\ne0$. Dùng định lí thương của các hàm liên tục:

$$
\lim_{x\to 3}\left(\frac{x^{2} + 5}{x^{2} + 2 \cdot x + 10}\right)=\frac{14}{25}.
$$




---


## Dạng 10. Khử 0/0: phân tích nhân tử bậc hai

> [!tip] Phương pháp trọng tâm
> Phân tích tử và mẫu thành nhân tử rồi khử x−a (với x≠a).


### Bài D10.01 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{2} - 1}{x - 1}\right)$.


**Lời giải chi tiết**

Thay trực tiếp được $0/0$ nên không kết luận. Dùng hiệu hai bình phương: $x^2-1=(x-1)(x+1)$. Với $x\ne1$ rút gọn $x-1$.

$$
\lim_{x\to 1}\left(\frac{x^{2} - 1}{x - 1}\right)=\lim_{x\to 1}(x+1)=2.
$$




### Bài D10.02 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{2} - 4}{x - 2}\right)$.


**Lời giải chi tiết**

Thay trực tiếp được $0/0$ nên không kết luận. Dùng hiệu hai bình phương: $x^2-4=(x-2)(x+2)$. Với $x\ne2$ rút gọn $x-2$.

$$
\lim_{x\to 2}\left(\frac{x^{2} - 4}{x - 2}\right)=\lim_{x\to 2}(x+2)=4.
$$




### Bài D10.03 · Nhận biết

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{2} - 1}{x + 1}\right)$.


**Lời giải chi tiết**

Thay trực tiếp được $0/0$ nên không kết luận. Dùng hiệu hai bình phương: $x^2-1=(x+1)(x-1)$. Với $x\ne-1$ rút gọn $x+1$.

$$
\lim_{x\to -1}\left(\frac{x^{2} - 1}{x + 1}\right)=\lim_{x\to -1}(x-1)=-2.
$$




### Bài D10.04 · Nhận biết

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{2} - 9}{x - 3}\right)$.


**Lời giải chi tiết**

Thay trực tiếp được $0/0$ nên không kết luận. Dùng hiệu hai bình phương: $x^2-9=(x-3)(x+3)$. Với $x\ne3$ rút gọn $x-3$.

$$
\lim_{x\to 3}\left(\frac{x^{2} - 9}{x - 3}\right)=\lim_{x\to 3}(x+3)=6.
$$




### Bài D10.05 · Nhận biết

Tính giới hạn $\lim_{x\to -2}\left(\frac{x^{2} - 4}{x + 2}\right)$.


**Lời giải chi tiết**

Thay trực tiếp được $0/0$ nên không kết luận. Dùng hiệu hai bình phương: $x^2-4=(x+2)(x-2)$. Với $x\ne-2$ rút gọn $x+2$.

$$
\lim_{x\to -2}\left(\frac{x^{2} - 4}{x + 2}\right)=\lim_{x\to -2}(x-2)=-4.
$$




### Bài D10.06 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{2} - 4 \cdot x + 3}{x - 1}\right)$.


**Lời giải chi tiết**

Phân tích tử thành $(x-1)(x-3)$. Khi $x\ne1$, khử nhân tử $x-1$:

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{x^{2} - 4 \cdot x + 3}{x - 1}\right)&=\lim_{x\to 1}\frac{(x-(1))(x-(3))}{x-(1)}\\&=1-(3)=-2.\end{aligned}
$$




### Bài D10.07 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{2} - x - 2}{x - 2}\right)$.


**Lời giải chi tiết**

Phân tích tử thành $(x-2)(x+1)$. Khi $x\ne2$, khử nhân tử $x-2$:

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{x^{2} - x - 2}{x - 2}\right)&=\lim_{x\to 2}\frac{(x-(2))(x+1)}{x-(2)}\\&=2+1=3.\end{aligned}
$$




### Bài D10.08 · Thông hiểu

Tính giới hạn $\lim_{x\to -2}\left(\frac{x^{2} - 2 \cdot x - 8}{x + 2}\right)$.


**Lời giải chi tiết**

Phân tích tử thành $(x+2)(x-4)$. Khi $x\ne-2$, khử nhân tử $x+2$:

$$
\begin{aligned}\lim_{x\to -2}\left(\frac{x^{2} - 2 \cdot x - 8}{x + 2}\right)&=\lim_{x\to -2}\frac{(x+2)(x-(4))}{x+2}\\&=-2-(4)=-6.\end{aligned}
$$




### Bài D10.09 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{2} - 4 \cdot x + 3}{x - 3}\right)$.


**Lời giải chi tiết**

Phân tích tử thành $(x-3)(x-1)$. Khi $x\ne3$, khử nhân tử $x-3$:

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{x^{2} - 4 \cdot x + 3}{x - 3}\right)&=\lim_{x\to 3}\frac{(x-(3))(x-(1))}{x-(3)}\\&=3-(1)=2.\end{aligned}
$$




### Bài D10.10 · Thông hiểu

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{2} + 4 \cdot x + 3}{x + 1}\right)$.


**Lời giải chi tiết**

Phân tích tử thành $(x+1)(x+3)$. Khi $x\ne-1$, khử nhân tử $x+1$:

$$
\begin{aligned}\lim_{x\to -1}\left(\frac{x^{2} + 4 \cdot x + 3}{x + 1}\right)&=\lim_{x\to -1}\frac{(x+1)(x+3)}{x+1}\\&=-1+3=2.\end{aligned}
$$




### Bài D10.11 · Thông hiểu

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{2} - 1}{\left(x - 1\right) \cdot \left(x + 2\right)}\right)$.


**Lời giải chi tiết**

Dùng $x^2-a^2=(x-a)(x+a)$ và khử $x-1$, do $b a+c=3\ne0$.

$$
\lim_{x\to 1}\left(\frac{x^{2} - 1}{\left(x - 1\right) \cdot \left(x + 2\right)}\right)=\lim_{x\to1}\frac{x+(1)}{1x+(2)}=\frac{2}{3}=\frac{2}{3}.
$$




### Bài D10.12 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{2} - 4}{\left(x - 2\right) \cdot \left(3 \cdot x + 1\right)}\right)$.


**Lời giải chi tiết**

Dùng $x^2-a^2=(x-a)(x+a)$ và khử $x-2$, do $b a+c=7\ne0$.

$$
\lim_{x\to 2}\left(\frac{x^{2} - 4}{\left(x - 2\right) \cdot \left(3 \cdot x + 1\right)}\right)=\lim_{x\to2}\frac{x+(2)}{3x+(1)}=\frac{4}{7}=\frac{4}{7}.
$$




### Bài D10.13 · Thông hiểu

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{2} - 1}{\left(x + 1\right) \cdot \left(2 \cdot x + 4\right)}\right)$.


**Lời giải chi tiết**

Dùng $x^2-a^2=(x-a)(x+a)$ và khử $x+1$, do $b a+c=2\ne0$.

$$
\lim_{x\to -1}\left(\frac{x^{2} - 1}{\left(x + 1\right) \cdot \left(2 \cdot x + 4\right)}\right)=\lim_{x\to-1}\frac{x-1}{2x+(4)}=\frac{-2}{2}=-1.
$$




### Bài D10.14 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{2} - 9}{\left(x - 3\right) \cdot \left(4 \cdot x + 2\right)}\right)$.


**Lời giải chi tiết**

Dùng $x^2-a^2=(x-a)(x+a)$ và khử $x-3$, do $b a+c=14\ne0$.

$$
\lim_{x\to 3}\left(\frac{x^{2} - 9}{\left(x - 3\right) \cdot \left(4 \cdot x + 2\right)}\right)=\lim_{x\to3}\frac{x+(3)}{4x+(2)}=\frac{6}{14}=\frac{3}{7}.
$$




### Bài D10.15 · Vận dụng

Tính giới hạn $\lim_{x\to -2}\left(\frac{x^{2} - 4}{\left(x + 2\right) \cdot \left(5 \cdot x + 3\right)}\right)$.


**Lời giải chi tiết**

Dùng $x^2-a^2=(x-a)(x+a)$ và khử $x+2$, do $b a+c=-7\ne0$.

$$
\lim_{x\to -2}\left(\frac{x^{2} - 4}{\left(x + 2\right) \cdot \left(5 \cdot x + 3\right)}\right)=\lim_{x\to-2}\frac{x-2}{5x+(3)}=\frac{-4}{-7}=\frac{4}{7}.
$$




### Bài D10.16 · Vận dụng

Tính giới hạn $\lim_{x\to 1}\left(\frac{\left(x - 1\right) \cdot \left(x + 2\right)}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Tử có $x-1$, mẫu là $(x-1)(x+1)$. Với $x\ne1$, rút gọn và thay giới hạn: 

$$
\lim_{x\to 1}\left(\frac{\left(x - 1\right) \cdot \left(x + 2\right)}{x^{2} - 1}\right)=\lim_{x\to1}\frac{x+2}{x+(1)}=\frac{3}{2}.
$$




### Bài D10.17 · Vận dụng

Tính giới hạn $\lim_{x\to 2}\left(\frac{\left(x - 2\right) \cdot \left(x + 1\right)}{x^{2} - 4}\right)$.


**Lời giải chi tiết**

Tử có $x-2$, mẫu là $(x-2)(x+2)$. Với $x\ne2$, rút gọn và thay giới hạn: 

$$
\lim_{x\to 2}\left(\frac{\left(x - 2\right) \cdot \left(x + 1\right)}{x^{2} - 4}\right)=\lim_{x\to2}\frac{x+1}{x+(2)}=\frac{3}{4}.
$$




### Bài D10.18 · Vận dụng

Tính giới hạn $\lim_{x\to 3}\left(\frac{\left(x - 3\right) \cdot \left(x + 4\right)}{x^{2} - 9}\right)$.


**Lời giải chi tiết**

Tử có $x-3$, mẫu là $(x-3)(x+3)$. Với $x\ne3$, rút gọn và thay giới hạn: 

$$
\lim_{x\to 3}\left(\frac{\left(x - 3\right) \cdot \left(x + 4\right)}{x^{2} - 9}\right)=\lim_{x\to3}\frac{x+4}{x+(3)}=\frac{7}{6}.
$$




### Bài D10.19 · Vận dụng

Tính giới hạn $\lim_{x\to -1}\left(\frac{\left(x + 1\right) \cdot \left(x + 3\right)}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Tử có $x+1$, mẫu là $(x+1)(x-1)$. Với $x\ne-1$, rút gọn và thay giới hạn: 

$$
\lim_{x\to -1}\left(\frac{\left(x + 1\right) \cdot \left(x + 3\right)}{x^{2} - 1}\right)=\lim_{x\to-1}\frac{x+3}{x-1}=-1.
$$




### Bài D10.20 · Vận dụng

Tính giới hạn $\lim_{x\to -2}\left(\frac{\left(x + 2\right)^{2}}{x^{2} - 4}\right)$.


**Lời giải chi tiết**

Tử có $x+2$, mẫu là $(x+2)(x-2)$. Với $x\ne-2$, rút gọn và thay giới hạn: 

$$
\lim_{x\to -2}\left(\frac{\left(x + 2\right)^{2}}{x^{2} - 4}\right)=\lim_{x\to-2}\frac{x+2}{x-2}=0.
$$




---


## Dạng 11. Khử 0/0: hằng đẳng thức bậc ba, bậc bốn

> [!tip] Phương pháp trọng tâm
> Dùng A³−B³, A³+B³, A⁴−B⁴ và khử nhân tử chung.


### Bài D11.01 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{3} - 1}{x - 1}\right)$.


**Lời giải chi tiết**

Dùng $x^3-a^3=(x-a)(x^2+ax+a^2)$; khử $x-a$ trước khi thay:

$$
\lim_{x\to 1}\left(\frac{x^{3} - 1}{x - 1}\right)=\lim_{x\to1}(x^2+(1)x+1)=3\cdot 1=3.
$$




### Bài D11.02 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{3} - 8}{x - 2}\right)$.


**Lời giải chi tiết**

Dùng $x^3-a^3=(x-a)(x^2+ax+a^2)$; khử $x-a$ trước khi thay:

$$
\lim_{x\to 2}\left(\frac{x^{3} - 8}{x - 2}\right)=\lim_{x\to2}(x^2+(2)x+4)=3\cdot 4=12.
$$




### Bài D11.03 · Nhận biết

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{3} - 27}{x - 3}\right)$.


**Lời giải chi tiết**

Dùng $x^3-a^3=(x-a)(x^2+ax+a^2)$; khử $x-a$ trước khi thay:

$$
\lim_{x\to 3}\left(\frac{x^{3} - 27}{x - 3}\right)=\lim_{x\to3}(x^2+(3)x+9)=3\cdot 9=27.
$$




### Bài D11.04 · Nhận biết

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{3} + 1}{x + 1}\right)$.


**Lời giải chi tiết**

Dùng $x^3-a^3=(x-a)(x^2+ax+a^2)$; khử $x-a$ trước khi thay:

$$
\lim_{x\to -1}\left(\frac{x^{3} + 1}{x + 1}\right)=\lim_{x\to-1}(x^2-1x+1)=3\cdot 1=3.
$$




### Bài D11.05 · Nhận biết

Tính giới hạn $\lim_{x\to -2}\left(\frac{x^{3} + 8}{x + 2}\right)$.


**Lời giải chi tiết**

Dùng $x^3-a^3=(x-a)(x^2+ax+a^2)$; khử $x-a$ trước khi thay:

$$
\lim_{x\to -2}\left(\frac{x^{3} + 8}{x + 2}\right)=\lim_{x\to-2}(x^2-2x+4)=3\cdot 4=12.
$$




### Bài D11.06 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{3} - 1}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Phân tích cả tử và mẫu; với $x\ne a$, rút gọn $x-a$.

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{x^{3} - 1}{x^{2} - 1}\right)&=\lim_{x\to1}\frac{x^2+(1)x+1}{x+(1)}\\&=\frac{3\cdot1}{2\cdot(1)}=\frac{3}{2}.\end{aligned}
$$




### Bài D11.07 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{3} - 8}{x^{2} - 4}\right)$.


**Lời giải chi tiết**

Phân tích cả tử và mẫu; với $x\ne a$, rút gọn $x-a$.

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{x^{3} - 8}{x^{2} - 4}\right)&=\lim_{x\to2}\frac{x^2+(2)x+4}{x+(2)}\\&=\frac{3\cdot4}{2\cdot(2)}=3.\end{aligned}
$$




### Bài D11.08 · Thông hiểu

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{3} + 1}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Phân tích cả tử và mẫu; với $x\ne a$, rút gọn $x-a$.

$$
\begin{aligned}\lim_{x\to -1}\left(\frac{x^{3} + 1}{x^{2} - 1}\right)&=\lim_{x\to-1}\frac{x^2-1x+1}{x-1}\\&=\frac{3\cdot1}{2\cdot(-1)}=- \frac{3}{2}.\end{aligned}
$$




### Bài D11.09 · Thông hiểu

Tính giới hạn $\lim_{x\to -2}\left(\frac{x^{3} + 8}{x^{2} - 4}\right)$.


**Lời giải chi tiết**

Phân tích cả tử và mẫu; với $x\ne a$, rút gọn $x-a$.

$$
\begin{aligned}\lim_{x\to -2}\left(\frac{x^{3} + 8}{x^{2} - 4}\right)&=\lim_{x\to-2}\frac{x^2-2x+4}{x-2}\\&=\frac{3\cdot4}{2\cdot(-2)}=-3.\end{aligned}
$$




### Bài D11.10 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{3} - 27}{x^{2} - 9}\right)$.


**Lời giải chi tiết**

Phân tích cả tử và mẫu; với $x\ne a$, rút gọn $x-a$.

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{x^{3} - 27}{x^{2} - 9}\right)&=\lim_{x\to3}\frac{x^2+(3)x+9}{x+(3)}\\&=\frac{3\cdot9}{2\cdot(3)}=\frac{9}{2}.\end{aligned}
$$




### Bài D11.11 · Thông hiểu

Tính giới hạn $\lim_{x\to 1}\left(\frac{x^{4} - 1}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Áp dụng $x^4-a^4=(x^2-a^2)(x^2+a^2)$.

$$
\lim_{x\to 1}\left(\frac{x^{4} - 1}{x^{2} - 1}\right)=\lim_{x\to 1}(x^2+1)=2.
$$




### Bài D11.12 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\frac{x^{4} - 16}{x^{2} - 4}\right)$.


**Lời giải chi tiết**

Áp dụng $x^4-a^4=(x^2-a^2)(x^2+a^2)$.

$$
\lim_{x\to 2}\left(\frac{x^{4} - 16}{x^{2} - 4}\right)=\lim_{x\to 2}(x^2+4)=8.
$$




### Bài D11.13 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{x^{4} - 81}{x^{2} - 9}\right)$.


**Lời giải chi tiết**

Áp dụng $x^4-a^4=(x^2-a^2)(x^2+a^2)$.

$$
\lim_{x\to 3}\left(\frac{x^{4} - 81}{x^{2} - 9}\right)=\lim_{x\to 3}(x^2+9)=18.
$$




### Bài D11.14 · Thông hiểu

Tính giới hạn $\lim_{x\to -1}\left(\frac{x^{4} - 1}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Áp dụng $x^4-a^4=(x^2-a^2)(x^2+a^2)$.

$$
\lim_{x\to -1}\left(\frac{x^{4} - 1}{x^{2} - 1}\right)=\lim_{x\to -1}(x^2+1)=2.
$$




### Bài D11.15 · Vận dụng

Tính giới hạn $\lim_{x\to -3}\left(\frac{x^{4} - 81}{x^{2} - 9}\right)$.


**Lời giải chi tiết**

Áp dụng $x^4-a^4=(x^2-a^2)(x^2+a^2)$.

$$
\lim_{x\to -3}\left(\frac{x^{4} - 81}{x^{2} - 9}\right)=\lim_{x\to -3}(x^2+9)=18.
$$




### Bài D11.16 · Vận dụng

Tính giới hạn $\lim_{x\to -1}\left(\frac{2 \cdot x^{3} + 2}{x + 1}\right)$.


**Lời giải chi tiết**

Hằng đẳng thức tổng hai lập phương: $2(x^3+1)=2(x+1)\bigl(x^{2} - x + 1\bigr)$.

$$
\lim_{x\to -1}\left(\frac{2 \cdot x^{3} + 2}{x + 1}\right)=2\bigl((-1)^2-1(-1)+1\bigr)=6.
$$




### Bài D11.17 · Vận dụng

Tính giới hạn $\lim_{x\to -2}\left(\frac{2 \cdot x^{3} + 16}{x + 2}\right)$.


**Lời giải chi tiết**

Hằng đẳng thức tổng hai lập phương: $2(x^3+8)=2(x+2)\bigl(x^{2} - 2 \cdot x + 4\bigr)$.

$$
\lim_{x\to -2}\left(\frac{2 \cdot x^{3} + 16}{x + 2}\right)=2\bigl((-2)^2-2(-2)+4\bigr)=24.
$$




### Bài D11.18 · Vận dụng

Tính giới hạn $\lim_{x\to -3}\left(\frac{2 \cdot x^{3} + 54}{x + 3}\right)$.


**Lời giải chi tiết**

Hằng đẳng thức tổng hai lập phương: $2(x^3+27)=2(x+3)\bigl(x^{2} - 3 \cdot x + 9\bigr)$.

$$
\lim_{x\to -3}\left(\frac{2 \cdot x^{3} + 54}{x + 3}\right)=2\bigl((-3)^2-3(-3)+9\bigr)=54.
$$




### Bài D11.19 · Vận dụng

Tính giới hạn $\lim_{x\to -4}\left(\frac{2 \cdot x^{3} + 128}{x + 4}\right)$.


**Lời giải chi tiết**

Hằng đẳng thức tổng hai lập phương: $2(x^3+64)=2(x+4)\bigl(x^{2} - 4 \cdot x + 16\bigr)$.

$$
\lim_{x\to -4}\left(\frac{2 \cdot x^{3} + 128}{x + 4}\right)=2\bigl((-4)^2-4(-4)+16\bigr)=96.
$$




### Bài D11.20 · Vận dụng

Tính giới hạn $\lim_{x\to -5}\left(\frac{2 \cdot x^{3} + 250}{x + 5}\right)$.


**Lời giải chi tiết**

Hằng đẳng thức tổng hai lập phương: $2(x^3+125)=2(x+5)\bigl(x^{2} - 5 \cdot x + 25\bigr)$.

$$
\lim_{x\to -5}\left(\frac{2 \cdot x^{3} + 250}{x + 5}\right)=2\bigl((-5)^2-5(-5)+25\bigr)=150.
$$




---


## Dạng 12. Khử 0/0: nhân liên hợp tại một điểm

> [!tip] Phương pháp trọng tâm
> Khi có hiệu hai căn, nhân liên hợp để bỏ dạng 0/0.


### Bài D12.01 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x + 1} - 1}{x}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với tổng hai căn để xuất hiện $x-a$.

$$
\begin{aligned}\lim_{x\to 0}\left(\frac{\sqrt{x + 1} - 1}{x}\right)&=\lim_{x\to 0}\frac{(x+1)-1}{(x-0)(\sqrt{x+1}+\sqrt{1})}\\&=\lim_{x\to0}\frac1{\sqrt{x+1}+\sqrt{1}}=\frac{1}{2}.\end{aligned}
$$




### Bài D12.02 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{\sqrt{x + 4} - \sqrt{5}}{x - 1}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với tổng hai căn để xuất hiện $x-a$.

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{\sqrt{x + 4} - \sqrt{5}}{x - 1}\right)&=\lim_{x\to 1}\frac{(x+4)-5}{(x-1)(\sqrt{x+4}+\sqrt{5})}\\&=\lim_{x\to1}\frac1{\sqrt{x+4}+\sqrt{5}}=\frac{\sqrt{5}}{10}.\end{aligned}
$$




### Bài D12.03 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{\sqrt{x + 5} - \sqrt{7}}{x - 2}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với tổng hai căn để xuất hiện $x-a$.

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{\sqrt{x + 5} - \sqrt{7}}{x - 2}\right)&=\lim_{x\to 2}\frac{(x+5)-7}{(x-2)(\sqrt{x+5}+\sqrt{7})}\\&=\lim_{x\to2}\frac1{\sqrt{x+5}+\sqrt{7}}=\frac{\sqrt{7}}{14}.\end{aligned}
$$




### Bài D12.04 · Nhận biết

Tính giới hạn $\lim_{x\to 3}\left(\frac{\sqrt{x + 1} - 2}{x - 3}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với tổng hai căn để xuất hiện $x-a$.

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{\sqrt{x + 1} - 2}{x - 3}\right)&=\lim_{x\to 3}\frac{(x+1)-4}{(x-3)(\sqrt{x+1}+\sqrt{4})}\\&=\lim_{x\to3}\frac1{\sqrt{x+1}+\sqrt{4}}=\frac{1}{4}.\end{aligned}
$$




### Bài D12.05 · Nhận biết

Tính giới hạn $\lim_{x\to 4}\left(\frac{\sqrt{x + 9} - \sqrt{13}}{x - 4}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với tổng hai căn để xuất hiện $x-a$.

$$
\begin{aligned}\lim_{x\to 4}\left(\frac{\sqrt{x + 9} - \sqrt{13}}{x - 4}\right)&=\lim_{x\to 4}\frac{(x+9)-13}{(x-4)(\sqrt{x+9}+\sqrt{13})}\\&=\lim_{x\to4}\frac1{\sqrt{x+9}+\sqrt{13}}=\frac{\sqrt{13}}{26}.\end{aligned}
$$




### Bài D12.06 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{x - 1}{\sqrt{x + 2} - \sqrt{3}}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với $\sqrt{x+c}+\sqrt{a+c}$; mẫu trở thành $x-a$ và rút gọn.

$$
\lim_{x\to 1}\left(\frac{x - 1}{\sqrt{x + 2} - \sqrt{3}}\right)=\lim_{x\to1}(\sqrt{x+2}+\sqrt{3})=2\sqrt{3}.
$$




### Bài D12.07 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{x - 2}{\sqrt{x + 3} - \sqrt{5}}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với $\sqrt{x+c}+\sqrt{a+c}$; mẫu trở thành $x-a$ và rút gọn.

$$
\lim_{x\to 2}\left(\frac{x - 2}{\sqrt{x + 3} - \sqrt{5}}\right)=\lim_{x\to2}(\sqrt{x+3}+\sqrt{5})=2\sqrt{5}.
$$




### Bài D12.08 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{x - 3}{\sqrt{x + 4} - \sqrt{7}}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với $\sqrt{x+c}+\sqrt{a+c}$; mẫu trở thành $x-a$ và rút gọn.

$$
\lim_{x\to 3}\left(\frac{x - 3}{\sqrt{x + 4} - \sqrt{7}}\right)=\lim_{x\to3}(\sqrt{x+4}+\sqrt{7})=2\sqrt{7}.
$$




### Bài D12.09 · Thông hiểu

Tính giới hạn $\lim_{x\to 4}\left(\frac{x - 4}{\sqrt{x + 5} - 3}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với $\sqrt{x+c}+\sqrt{a+c}$; mẫu trở thành $x-a$ và rút gọn.

$$
\lim_{x\to 4}\left(\frac{x - 4}{\sqrt{x + 5} - 3}\right)=\lim_{x\to4}(\sqrt{x+5}+\sqrt{9})=2\sqrt{9}.
$$




### Bài D12.10 · Thông hiểu

Tính giới hạn $\lim_{x\to 5}\left(\frac{x - 5}{\sqrt{x + 6} - \sqrt{11}}\right)$.


**Lời giải chi tiết**

Nhân cả tử và mẫu với $\sqrt{x+c}+\sqrt{a+c}$; mẫu trở thành $x-a$ và rút gọn.

$$
\lim_{x\to 5}\left(\frac{x - 5}{\sqrt{x + 6} - \sqrt{11}}\right)=\lim_{x\to5}(\sqrt{x+6}+\sqrt{11})=2\sqrt{11}.
$$




### Bài D12.11 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x^{2} + 4} - 2}{x}\right)$.


**Lời giải chi tiết**

Nhân liên hợp, tử sau khi nhân là $x^2-0=(x-0)(x+0)$.

$$
\begin{aligned}\lim_{x\to 0}\left(\frac{\sqrt{x^{2} + 4} - 2}{x}\right)&=\lim_{x\to0}\frac{x+(0)}{\sqrt{x^2+4}+\sqrt{4}}\\&=\frac{0}{2\sqrt{4}}=0.\end{aligned}
$$




### Bài D12.12 · Thông hiểu

Tính giới hạn $\lim_{x\to 1}\left(\frac{\sqrt{x^{2} + 1} - \sqrt{2}}{x - 1}\right)$.


**Lời giải chi tiết**

Nhân liên hợp, tử sau khi nhân là $x^2-1=(x-1)(x+1)$.

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{\sqrt{x^{2} + 1} - \sqrt{2}}{x - 1}\right)&=\lim_{x\to1}\frac{x+(1)}{\sqrt{x^2+1}+\sqrt{2}}\\&=\frac{2}{2\sqrt{2}}=\frac{\sqrt{2}}{2}.\end{aligned}
$$




### Bài D12.13 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\frac{\sqrt{x^{2} + 1} - \sqrt{5}}{x - 2}\right)$.


**Lời giải chi tiết**

Nhân liên hợp, tử sau khi nhân là $x^2-4=(x-2)(x+2)$.

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{\sqrt{x^{2} + 1} - \sqrt{5}}{x - 2}\right)&=\lim_{x\to2}\frac{x+(2)}{\sqrt{x^2+1}+\sqrt{5}}\\&=\frac{4}{2\sqrt{5}}=\frac{2 \cdot \sqrt{5}}{5}.\end{aligned}
$$




### Bài D12.14 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{\sqrt{x^{2} + 5} - \sqrt{14}}{x - 3}\right)$.


**Lời giải chi tiết**

Nhân liên hợp, tử sau khi nhân là $x^2-9=(x-3)(x+3)$.

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{\sqrt{x^{2} + 5} - \sqrt{14}}{x - 3}\right)&=\lim_{x\to3}\frac{x+(3)}{\sqrt{x^2+5}+\sqrt{14}}\\&=\frac{6}{2\sqrt{14}}=\frac{3 \cdot \sqrt{14}}{14}.\end{aligned}
$$




### Bài D12.15 · Vận dụng

Tính giới hạn $\lim_{x\to 4}\left(\frac{\sqrt{x^{2} + 2} - 3 \cdot \sqrt{2}}{x - 4}\right)$.


**Lời giải chi tiết**

Nhân liên hợp, tử sau khi nhân là $x^2-16=(x-4)(x+4)$.

$$
\begin{aligned}\lim_{x\to 4}\left(\frac{\sqrt{x^{2} + 2} - 3 \cdot \sqrt{2}}{x - 4}\right)&=\lim_{x\to4}\frac{x+(4)}{\sqrt{x^2+2}+\sqrt{18}}\\&=\frac{8}{2\sqrt{18}}=\frac{2 \cdot \sqrt{2}}{3}.\end{aligned}
$$




### Bài D12.16 · Vận dụng

Tính giới hạn $\lim_{x\to 1}\left(\frac{\sqrt{2 \cdot x + 3} - \sqrt{5}}{x - 1}\right)$.


**Lời giải chi tiết**

Nhân liên hợp; phần chênh lệch dưới hai dấu căn là $2(x-1)$.

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{\sqrt{2 \cdot x + 3} - \sqrt{5}}{x - 1}\right)&=\lim_{x\to1}\frac{2 \cdot x - 2}{(x-1)(\sqrt{2 \cdot x + 3}+\sqrt{5})}\\&=\frac{\sqrt{5}}{5}.\end{aligned}
$$




### Bài D12.17 · Vận dụng

Tính giới hạn $\lim_{x\to 2}\left(\frac{\sqrt{x + 4} - \sqrt{6}}{x - 2}\right)$.


**Lời giải chi tiết**

Nhân liên hợp; phần chênh lệch dưới hai dấu căn là $1(x-2)$.

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{\sqrt{x + 4} - \sqrt{6}}{x - 2}\right)&=\lim_{x\to2}\frac{x - 2}{(x-2)(\sqrt{x + 4}+\sqrt{6})}\\&=\frac{\sqrt{6}}{12}.\end{aligned}
$$




### Bài D12.18 · Vận dụng

Tính giới hạn $\lim_{x\to 3}\left(\frac{\sqrt{3 \cdot x + 5} - \sqrt{14}}{x - 3}\right)$.


**Lời giải chi tiết**

Nhân liên hợp; phần chênh lệch dưới hai dấu căn là $3(x-3)$.

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{\sqrt{3 \cdot x + 5} - \sqrt{14}}{x - 3}\right)&=\lim_{x\to3}\frac{3 \cdot x - 9}{(x-3)(\sqrt{3 \cdot x + 5}+\sqrt{14})}\\&=\frac{3 \cdot \sqrt{14}}{28}.\end{aligned}
$$




### Bài D12.19 · Vận dụng

Tính giới hạn $\lim_{x\to 4}\left(\frac{\sqrt{2 \cdot x + 7} - \sqrt{15}}{x - 4}\right)$.


**Lời giải chi tiết**

Nhân liên hợp; phần chênh lệch dưới hai dấu căn là $2(x-4)$.

$$
\begin{aligned}\lim_{x\to 4}\left(\frac{\sqrt{2 \cdot x + 7} - \sqrt{15}}{x - 4}\right)&=\lim_{x\to4}\frac{2 \cdot x - 8}{(x-4)(\sqrt{2 \cdot x + 7}+\sqrt{15})}\\&=\frac{\sqrt{15}}{15}.\end{aligned}
$$




### Bài D12.20 · Vận dụng

Tính giới hạn $\lim_{x\to 5}\left(\frac{\sqrt{x + 8} - \sqrt{13}}{x - 5}\right)$.


**Lời giải chi tiết**

Nhân liên hợp; phần chênh lệch dưới hai dấu căn là $1(x-5)$.

$$
\begin{aligned}\lim_{x\to 5}\left(\frac{\sqrt{x + 8} - \sqrt{13}}{x - 5}\right)&=\lim_{x\to5}\frac{x - 5}{(x-5)(\sqrt{x + 8}+\sqrt{13})}\\&=\frac{\sqrt{13}}{26}.\end{aligned}
$$




---


## Dạng 13. Khử 0/0: quy đồng phân thức

> [!tip] Phương pháp trọng tâm
> Quy đồng các phân thức trong tử trước khi chia cho x−a.


### Bài D13.01 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{-1 + \frac{1}{x}}{x - 1}\right)$.


**Lời giải chi tiết**

Quy đồng tử: $\frac1x-\frac1{1}=\frac{1-x}{1x}=\frac{-(x-1)}{1x}$.

$$
\lim_{x\to 1}\left(\frac{-1 + \frac{1}{x}}{x - 1}\right)=\lim_{x\to1}\frac{-1}{1x}=-\frac1{1}.
$$




### Bài D13.02 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{- \frac{1}{2} + \frac{1}{x}}{x - 2}\right)$.


**Lời giải chi tiết**

Quy đồng tử: $\frac1x-\frac1{2}=\frac{2-x}{2x}=\frac{-(x-2)}{2x}$.

$$
\lim_{x\to 2}\left(\frac{- \frac{1}{2} + \frac{1}{x}}{x - 2}\right)=\lim_{x\to2}\frac{-1}{2x}=-\frac1{4}.
$$




### Bài D13.03 · Nhận biết

Tính giới hạn $\lim_{x\to 3}\left(\frac{- \frac{1}{3} + \frac{1}{x}}{x - 3}\right)$.


**Lời giải chi tiết**

Quy đồng tử: $\frac1x-\frac1{3}=\frac{3-x}{3x}=\frac{-(x-3)}{3x}$.

$$
\lim_{x\to 3}\left(\frac{- \frac{1}{3} + \frac{1}{x}}{x - 3}\right)=\lim_{x\to3}\frac{-1}{3x}=-\frac1{9}.
$$




### Bài D13.04 · Nhận biết

Tính giới hạn $\lim_{x\to 4}\left(\frac{- \frac{1}{4} + \frac{1}{x}}{x - 4}\right)$.


**Lời giải chi tiết**

Quy đồng tử: $\frac1x-\frac1{4}=\frac{4-x}{4x}=\frac{-(x-4)}{4x}$.

$$
\lim_{x\to 4}\left(\frac{- \frac{1}{4} + \frac{1}{x}}{x - 4}\right)=\lim_{x\to4}\frac{-1}{4x}=-\frac1{16}.
$$




### Bài D13.05 · Nhận biết

Tính giới hạn $\lim_{x\to 5}\left(\frac{- \frac{1}{5} + \frac{1}{x}}{x - 5}\right)$.


**Lời giải chi tiết**

Quy đồng tử: $\frac1x-\frac1{5}=\frac{5-x}{5x}=\frac{-(x-5)}{5x}$.

$$
\lim_{x\to 5}\left(\frac{- \frac{1}{5} + \frac{1}{x}}{x - 5}\right)=\lim_{x\to5}\frac{-1}{5x}=-\frac1{25}.
$$




### Bài D13.06 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(\frac{- \frac{1}{2} + \frac{1}{x + 2}}{x}\right)$.


**Lời giải chi tiết**

Lấy mẫu chung $(x+2)2$ của hai phân thức ở tử.

$$
\begin{aligned}\lim_{x\to 0}\left(\frac{- \frac{1}{2} + \frac{1}{x + 2}}{x}\right)&=\lim_{x\to0}\frac{2-(x+2)}{2(x+2)(x-0)}\\&=\lim_{x\to0}\frac{-1}{2(x+2)}=-\frac1{4}.\end{aligned}
$$




### Bài D13.07 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{- \frac{1}{4} + \frac{1}{x + 3}}{x - 1}\right)$.


**Lời giải chi tiết**

Lấy mẫu chung $(x+3)4$ của hai phân thức ở tử.

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{- \frac{1}{4} + \frac{1}{x + 3}}{x - 1}\right)&=\lim_{x\to1}\frac{4-(x+3)}{4(x+3)(x-1)}\\&=\lim_{x\to1}\frac{-1}{4(x+3)}=-\frac1{16}.\end{aligned}
$$




### Bài D13.08 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\frac{- \frac{1}{4} + \frac{1}{x + 2}}{x - 2}\right)$.


**Lời giải chi tiết**

Lấy mẫu chung $(x+2)4$ của hai phân thức ở tử.

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{- \frac{1}{4} + \frac{1}{x + 2}}{x - 2}\right)&=\lim_{x\to2}\frac{4-(x+2)}{4(x+2)(x-2)}\\&=\lim_{x\to2}\frac{-1}{4(x+2)}=-\frac1{16}.\end{aligned}
$$




### Bài D13.09 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{- \frac{1}{7} + \frac{1}{x + 4}}{x - 3}\right)$.


**Lời giải chi tiết**

Lấy mẫu chung $(x+4)7$ của hai phân thức ở tử.

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{- \frac{1}{7} + \frac{1}{x + 4}}{x - 3}\right)&=\lim_{x\to3}\frac{7-(x+4)}{7(x+4)(x-3)}\\&=\lim_{x\to3}\frac{-1}{7(x+4)}=-\frac1{49}.\end{aligned}
$$




### Bài D13.10 · Thông hiểu

Tính giới hạn $\lim_{x\to 4}\left(\frac{- \frac{1}{9} + \frac{1}{x + 5}}{x - 4}\right)$.


**Lời giải chi tiết**

Lấy mẫu chung $(x+5)9$ của hai phân thức ở tử.

$$
\begin{aligned}\lim_{x\to 4}\left(\frac{- \frac{1}{9} + \frac{1}{x + 5}}{x - 4}\right)&=\lim_{x\to4}\frac{9-(x+5)}{9(x+5)(x-4)}\\&=\lim_{x\to4}\frac{-1}{9(x+5)}=-\frac1{81}.\end{aligned}
$$




### Bài D13.11 · Thông hiểu

Tính giới hạn $\lim_{x\to 1}\left(\frac{- \frac{1}{3} + \frac{1}{x + 2}}{x - 1}\right)$.


**Lời giải chi tiết**

Quy đồng ở tử rồi khử $x-1$; điều kiện gần $x=1$ là $x+2\ne0$.

$$
\lim_{x\to 1}\left(\frac{- \frac{1}{3} + \frac{1}{x + 2}}{x - 1}\right)=\lim_{x\to1}\frac{(1+2)-(x+2)}{(1+2)(x+2)(x-1)}=-\frac1{9}.
$$




### Bài D13.12 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\frac{- \frac{1}{5} + \frac{1}{x + 3}}{x - 2}\right)$.


**Lời giải chi tiết**

Quy đồng ở tử rồi khử $x-2$; điều kiện gần $x=2$ là $x+3\ne0$.

$$
\lim_{x\to 2}\left(\frac{- \frac{1}{5} + \frac{1}{x + 3}}{x - 2}\right)=\lim_{x\to2}\frac{(2+3)-(x+3)}{(2+3)(x+3)(x-2)}=-\frac1{25}.
$$




### Bài D13.13 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(\frac{- \frac{1}{5} + \frac{1}{x + 2}}{x - 3}\right)$.


**Lời giải chi tiết**

Quy đồng ở tử rồi khử $x-3$; điều kiện gần $x=3$ là $x+2\ne0$.

$$
\lim_{x\to 3}\left(\frac{- \frac{1}{5} + \frac{1}{x + 2}}{x - 3}\right)=\lim_{x\to3}\frac{(3+2)-(x+2)}{(3+2)(x+2)(x-3)}=-\frac1{25}.
$$




### Bài D13.14 · Thông hiểu

Tính giới hạn $\lim_{x\to 4}\left(\frac{- \frac{1}{5} + \frac{1}{x + 1}}{x - 4}\right)$.


**Lời giải chi tiết**

Quy đồng ở tử rồi khử $x-4$; điều kiện gần $x=4$ là $x+1\ne0$.

$$
\lim_{x\to 4}\left(\frac{- \frac{1}{5} + \frac{1}{x + 1}}{x - 4}\right)=\lim_{x\to4}\frac{(4+1)-(x+1)}{(4+1)(x+1)(x-4)}=-\frac1{25}.
$$




### Bài D13.15 · Vận dụng

Tính giới hạn $\lim_{x\to 5}\left(\frac{- \frac{1}{9} + \frac{1}{x + 4}}{x - 5}\right)$.


**Lời giải chi tiết**

Quy đồng ở tử rồi khử $x-5$; điều kiện gần $x=5$ là $x+4\ne0$.

$$
\lim_{x\to 5}\left(\frac{- \frac{1}{9} + \frac{1}{x + 4}}{x - 5}\right)=\lim_{x\to5}\frac{(5+4)-(x+4)}{(5+4)(x+4)(x-5)}=-\frac1{81}.
$$




### Bài D13.16 · Vận dụng

Tính giới hạn $\lim_{x\to 1}\left(\frac{-0.5 + \frac{1}{x + 1}}{x^{2} - 1}\right)$.


**Lời giải chi tiết**

Quy đồng tử rồi dùng $x^2-1=(x-1)(x+1)$.

$$
\begin{aligned}\lim_{x\to 1}\left(\frac{-0.5 + \frac{1}{x + 1}}{x^{2} - 1}\right)&=\lim_{x\to1}\frac{2\cdot1-(x+1)}{2\cdot1(x+1)(x-1)(x+1)}\\&=\lim_{x\to1}\frac{-1}{2\cdot1(x+1)^2}=-\frac1{8}.\end{aligned}
$$




### Bài D13.17 · Vận dụng

Tính giới hạn $\lim_{x\to 2}\left(\frac{-0.25 + \frac{1}{x + 2}}{x^{2} - 4}\right)$.


**Lời giải chi tiết**

Quy đồng tử rồi dùng $x^2-4=(x-2)(x+2)$.

$$
\begin{aligned}\lim_{x\to 2}\left(\frac{-0.25 + \frac{1}{x + 2}}{x^{2} - 4}\right)&=\lim_{x\to2}\frac{2\cdot2-(x+2)}{2\cdot2(x+2)(x-2)(x+2)}\\&=\lim_{x\to2}\frac{-1}{2\cdot2(x+2)^2}=-\frac1{64}.\end{aligned}
$$




### Bài D13.18 · Vận dụng

Tính giới hạn $\lim_{x\to 3}\left(\frac{-0.166666666666667 + \frac{1}{x + 3}}{x^{2} - 9}\right)$.


**Lời giải chi tiết**

Quy đồng tử rồi dùng $x^2-9=(x-3)(x+3)$.

$$
\begin{aligned}\lim_{x\to 3}\left(\frac{-0.166666666666667 + \frac{1}{x + 3}}{x^{2} - 9}\right)&=\lim_{x\to3}\frac{2\cdot3-(x+3)}{2\cdot3(x+3)(x-3)(x+3)}\\&=\lim_{x\to3}\frac{-1}{2\cdot3(x+3)^2}=-\frac1{216}.\end{aligned}
$$




### Bài D13.19 · Vận dụng

Tính giới hạn $\lim_{x\to 4}\left(\frac{-0.125 + \frac{1}{x + 4}}{x^{2} - 16}\right)$.


**Lời giải chi tiết**

Quy đồng tử rồi dùng $x^2-16=(x-4)(x+4)$.

$$
\begin{aligned}\lim_{x\to 4}\left(\frac{-0.125 + \frac{1}{x + 4}}{x^{2} - 16}\right)&=\lim_{x\to4}\frac{2\cdot4-(x+4)}{2\cdot4(x+4)(x-4)(x+4)}\\&=\lim_{x\to4}\frac{-1}{2\cdot4(x+4)^2}=-\frac1{512}.\end{aligned}
$$




### Bài D13.20 · Vận dụng

Tính giới hạn $\lim_{x\to 5}\left(\frac{-0.1 + \frac{1}{x + 5}}{x^{2} - 25}\right)$.


**Lời giải chi tiết**

Quy đồng tử rồi dùng $x^2-25=(x-5)(x+5)$.

$$
\begin{aligned}\lim_{x\to 5}\left(\frac{-0.1 + \frac{1}{x + 5}}{x^{2} - 25}\right)&=\lim_{x\to5}\frac{2\cdot5-(x+5)}{2\cdot5(x+5)(x-5)(x+5)}\\&=\lim_{x\to5}\frac{-1}{2\cdot5(x+5)^2}=-\frac1{1000}.\end{aligned}
$$




---


## Dạng 14. Giới hạn một bên và hàm số từng đoạn

> [!tip] Phương pháp trọng tâm
> Xét x→a⁻ và x→a⁺; hai giới hạn phải bằng nhau để giới hạn hai phía tồn tại.


### Bài D14.01 · Nhận biết

Cho hàm số 
$$
f(x)=\begin{cases}x,&x<2,\\1,&x\ge 2.\end{cases}
$$

Tính hai giới hạn một bên tại $x=2$ và kết luận về $\lim_{x\to 2}f(x)$.


**Lời giải chi tiết**

Theo công thức áp dụng ở mỗi phía của $x=2$:

$$
\lim_{x\to 2^-}f(x)=1\cdot(2)+(0)=2,\quad \lim_{x\to 2^+}f(x)=0\cdot(2)+(1)=1.
$$

Hai giới hạn một bên khác nhau nên giới hạn hai phía **không tồn tại**.


### Bài D14.02 · Nhận biết

Cho hàm số 
$$
f(x)=\begin{cases}2 \cdot x + 1,&x<3,\\x + 2,&x\ge 3.\end{cases}
$$

Tính hai giới hạn một bên tại $x=3$ và kết luận về $\lim_{x\to 3}f(x)$.


**Lời giải chi tiết**

Theo công thức áp dụng ở mỗi phía của $x=3$:

$$
\lim_{x\to 3^-}f(x)=2\cdot(3)+(1)=7,\quad \lim_{x\to 3^+}f(x)=1\cdot(3)+(2)=5.
$$

Hai giới hạn một bên khác nhau nên giới hạn hai phía **không tồn tại**.


### Bài D14.03 · Nhận biết

Cho hàm số 
$$
f(x)=\begin{cases}2 - x,&x<3,\\2 \cdot x - 1,&x\ge 3.\end{cases}
$$

Tính hai giới hạn một bên tại $x=3$ và kết luận về $\lim_{x\to 3}f(x)$.


**Lời giải chi tiết**

Theo công thức áp dụng ở mỗi phía của $x=3$:

$$
\lim_{x\to 3^-}f(x)=-1\cdot(3)+(2)=-1,\quad \lim_{x\to 3^+}f(x)=2\cdot(3)-1=5.
$$

Hai giới hạn một bên khác nhau nên giới hạn hai phía **không tồn tại**.


### Bài D14.04 · Nhận biết

Cho hàm số 
$$
f(x)=\begin{cases}2 \cdot x + 3,&x<-1,\\3 \cdot x + 2,&x\ge -1.\end{cases}
$$

Tính hai giới hạn một bên tại $x=-1$ và kết luận về $\lim_{x\to -1}f(x)$.


**Lời giải chi tiết**

Theo công thức áp dụng ở mỗi phía của $x=-1$:

$$
\lim_{x\to -1^-}f(x)=2\cdot(-1)+(3)=1,\quad \lim_{x\to -1^+}f(x)=3\cdot(-1)+(2)=-1.
$$

Hai giới hạn một bên khác nhau nên giới hạn hai phía **không tồn tại**.


### Bài D14.05 · Nhận biết

Cho hàm số 
$$
f(x)=\begin{cases}3 \cdot x - 1,&x<2,\\3 - x,&x\ge 2.\end{cases}
$$

Tính hai giới hạn một bên tại $x=2$ và kết luận về $\lim_{x\to 2}f(x)$.


**Lời giải chi tiết**

Theo công thức áp dụng ở mỗi phía của $x=2$:

$$
\lim_{x\to 2^-}f(x)=3\cdot(2)-1=5,\quad \lim_{x\to 2^+}f(x)=-1\cdot(2)+(3)=1.
$$

Hai giới hạn một bên khác nhau nên giới hạn hai phía **không tồn tại**.


### Bài D14.06 · Nhận biết

Tính $\lim_{x\to 0^-}\left(\frac{\left|{x}\right|}{x}\right)$ và $\lim_{x\to 0^+}\left(\frac{\left|{x}\right|}{x}\right)$. Giới hạn hai phía có tồn tại không?


**Lời giải chi tiết**

Với $x<0$, $|x-0|=-(x-0)$; với $x>0$, $|x-0|=x-0$.

$$
\lim_{x\to 0^-}\frac{\left|{x}\right|}{x}=-1,\qquad \lim_{x\to 0^+}\frac{\left|{x}\right|}{x}=1.
$$

Vì $-1\ne1$, giới hạn hai phía không tồn tại.


### Bài D14.07 · Nhận biết

Tính $\lim_{x\to 1^-}\left(\frac{\left|{x - 1}\right|}{x - 1}\right)$ và $\lim_{x\to 1^+}\left(\frac{\left|{x - 1}\right|}{x - 1}\right)$. Giới hạn hai phía có tồn tại không?


**Lời giải chi tiết**

Với $x<1$, $|x-1|=-(x-1)$; với $x>1$, $|x-1|=x-1$.

$$
\lim_{x\to 1^-}\frac{\left|{x - 1}\right|}{x - 1}=-1,\qquad \lim_{x\to 1^+}\frac{\left|{x - 1}\right|}{x - 1}=1.
$$

Vì $-1\ne1$, giới hạn hai phía không tồn tại.


### Bài D14.08 · Thông hiểu

Tính $\lim_{x\to 2^-}\left(\frac{\left|{x - 2}\right|}{x - 2}\right)$ và $\lim_{x\to 2^+}\left(\frac{\left|{x - 2}\right|}{x - 2}\right)$. Giới hạn hai phía có tồn tại không?


**Lời giải chi tiết**

Với $x<2$, $|x-2|=-(x-2)$; với $x>2$, $|x-2|=x-2$.

$$
\lim_{x\to 2^-}\frac{\left|{x - 2}\right|}{x - 2}=-1,\qquad \lim_{x\to 2^+}\frac{\left|{x - 2}\right|}{x - 2}=1.
$$

Vì $-1\ne1$, giới hạn hai phía không tồn tại.


### Bài D14.09 · Thông hiểu

Tính $\lim_{x\to -1^-}\left(\frac{\left|{x + 1}\right|}{x + 1}\right)$ và $\lim_{x\to -1^+}\left(\frac{\left|{x + 1}\right|}{x + 1}\right)$. Giới hạn hai phía có tồn tại không?


**Lời giải chi tiết**

Với $x<-1$, $|x+1|=-(x+1)$; với $x>-1$, $|x+1|=x+1$.

$$
\lim_{x\to -1^-}\frac{\left|{x + 1}\right|}{x + 1}=-1,\qquad \lim_{x\to -1^+}\frac{\left|{x + 1}\right|}{x + 1}=1.
$$

Vì $-1\ne1$, giới hạn hai phía không tồn tại.


### Bài D14.10 · Thông hiểu

Tính $\lim_{x\to -2^-}\left(\frac{\left|{x + 2}\right|}{x + 2}\right)$ và $\lim_{x\to -2^+}\left(\frac{\left|{x + 2}\right|}{x + 2}\right)$. Giới hạn hai phía có tồn tại không?


**Lời giải chi tiết**

Với $x<-2$, $|x+2|=-(x+2)$; với $x>-2$, $|x+2|=x+2$.

$$
\lim_{x\to -2^-}\frac{\left|{x + 2}\right|}{x + 2}=-1,\qquad \lim_{x\to -2^+}\frac{\left|{x + 2}\right|}{x + 2}=1.
$$

Vì $-1\ne1$, giới hạn hai phía không tồn tại.


### Bài D14.11 · Thông hiểu

Cho hàm 
$$
f(x)=\begin{cases}x^{2} + 1,&x\le 2,\\2 \cdot x + 1,&x>2.\end{cases}
$$

Tính $\lim_{x\to 2}f(x)$.


**Lời giải chi tiết**

Không dùng duy nhất công thức tại $x=2$ để kết luận. Tính cả hai phía:

$$
\lim_{x\to 2^-}f(x)=2^2+1=5,\qquad \lim_{x\to 2^+}f(x)=2\cdot2+1=5.
$$

Hai giới hạn bằng nhau, vậy $\boxed{\lim_{x\to 2}f(x)=5}$.


### Bài D14.12 · Thông hiểu

Cho hàm 
$$
f(x)=\begin{cases}x^{2} + 2,&x\le 3,\\3 \cdot x + 2,&x>3.\end{cases}
$$

Tính $\lim_{x\to 3}f(x)$.


**Lời giải chi tiết**

Không dùng duy nhất công thức tại $x=3$ để kết luận. Tính cả hai phía:

$$
\lim_{x\to 3^-}f(x)=3^2+2=11,\qquad \lim_{x\to 3^+}f(x)=3\cdot3+2=11.
$$

Hai giới hạn bằng nhau, vậy $\boxed{\lim_{x\to 3}f(x)=11}$.


### Bài D14.13 · Thông hiểu

Cho hàm 
$$
f(x)=\begin{cases}x^{2},&x\le 4,\\4 \cdot x,&x>4.\end{cases}
$$

Tính $\lim_{x\to 4}f(x)$.


**Lời giải chi tiết**

Không dùng duy nhất công thức tại $x=4$ để kết luận. Tính cả hai phía:

$$
\lim_{x\to 4^-}f(x)=4^2+0=16,\qquad \lim_{x\to 4^+}f(x)=4\cdot4+0=16.
$$

Hai giới hạn bằng nhau, vậy $\boxed{\lim_{x\to 4}f(x)=16}$.


### Bài D14.14 · Thông hiểu

Cho hàm 
$$
f(x)=\begin{cases}x^{2} - 1,&x\le 5,\\5 \cdot x - 1,&x>5.\end{cases}
$$

Tính $\lim_{x\to 5}f(x)$.


**Lời giải chi tiết**

Không dùng duy nhất công thức tại $x=5$ để kết luận. Tính cả hai phía:

$$
\lim_{x\to 5^-}f(x)=5^2-1=24,\qquad \lim_{x\to 5^+}f(x)=5\cdot5-1=24.
$$

Hai giới hạn bằng nhau, vậy $\boxed{\lim_{x\to 5}f(x)=24}$.


### Bài D14.15 · Vận dụng

Cho hàm 
$$
f(x)=\begin{cases}x^{2} + 3,&x\le 2,\\2 \cdot x + 3,&x>2.\end{cases}
$$

Tính $\lim_{x\to 2}f(x)$.


**Lời giải chi tiết**

Không dùng duy nhất công thức tại $x=2$ để kết luận. Tính cả hai phía:

$$
\lim_{x\to 2^-}f(x)=2^2+3=7,\qquad \lim_{x\to 2^+}f(x)=2\cdot2+3=7.
$$

Hai giới hạn bằng nhau, vậy $\boxed{\lim_{x\to 2}f(x)=7}$.


### Bài D14.16 · Vận dụng

Cho hàm 
$$
f(x)=\begin{cases}x,&x<1,\\x + 1,&x\ge1.\end{cases}
$$

Hỏi $\lim_{x\to1}f(x)$ có tồn tại không?


**Lời giải chi tiết**

Xét độc lập từng phía:

$$
\lim_{x\to1^-}f(x)=1+(0)=1,\qquad\lim_{x\to1^+}f(x)=1+(1)=2.
$$

Hai giá trị khác nhau, do đó giới hạn hai phía **không tồn tại**.


### Bài D14.17 · Vận dụng

Cho hàm 
$$
f(x)=\begin{cases}x + 1,&x<1,\\x + 2,&x\ge1.\end{cases}
$$

Hỏi $\lim_{x\to1}f(x)$ có tồn tại không?


**Lời giải chi tiết**

Xét độc lập từng phía:

$$
\lim_{x\to1^-}f(x)=1+(1)=2,\qquad\lim_{x\to1^+}f(x)=1+(2)=3.
$$

Hai giá trị khác nhau, do đó giới hạn hai phía **không tồn tại**.


### Bài D14.18 · Vận dụng

Cho hàm 
$$
f(x)=\begin{cases}x + 2,&x<1,\\x + 3,&x\ge1.\end{cases}
$$

Hỏi $\lim_{x\to1}f(x)$ có tồn tại không?


**Lời giải chi tiết**

Xét độc lập từng phía:

$$
\lim_{x\to1^-}f(x)=1+(2)=3,\qquad\lim_{x\to1^+}f(x)=1+(3)=4.
$$

Hai giá trị khác nhau, do đó giới hạn hai phía **không tồn tại**.


### Bài D14.19 · Vận dụng

Cho hàm 
$$
f(x)=\begin{cases}x - 1,&x<1,\\x + 4,&x\ge1.\end{cases}
$$

Hỏi $\lim_{x\to1}f(x)$ có tồn tại không?


**Lời giải chi tiết**

Xét độc lập từng phía:

$$
\lim_{x\to1^-}f(x)=1-1=0,\qquad\lim_{x\to1^+}f(x)=1+(4)=5.
$$

Hai giá trị khác nhau, do đó giới hạn hai phía **không tồn tại**.


### Bài D14.20 · Vận dụng

Cho hàm 
$$
f(x)=\begin{cases}x + 3,&x<1,\\x + 5,&x\ge1.\end{cases}
$$

Hỏi $\lim_{x\to1}f(x)$ có tồn tại không?


**Lời giải chi tiết**

Xét độc lập từng phía:

$$
\lim_{x\to1^-}f(x)=1+(3)=4,\qquad\lim_{x\to1^+}f(x)=1+(5)=6.
$$

Hai giá trị khác nhau, do đó giới hạn hai phía **không tồn tại**.


---


## Dạng 15. Giới hạn vô cực tại một điểm và xét dấu

> [!tip] Phương pháp trọng tâm
> Xác định dấu tử gần a và dấu mẫu ở từng phía; không chia máy móc cho 0.


### Bài D15.01 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(\frac{1}{(x-(0))^2}\right)$.


**Lời giải chi tiết**

Khi $x\to0$, mẫu $(x-0)^2>0$ và tiến về $0$, tử bằng $1>0$. Vì vậy phân thức tăng không bị chặn:

$$
\lim_{x\to 0}\left(\frac{1}{(x-(0))^2}\right)=+\infty.
$$




### Bài D15.02 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{1}{(x-(1))^2}\right)$.


**Lời giải chi tiết**

Khi $x\to1$, mẫu $(x-1)^2>0$ và tiến về $0$, tử bằng $1>0$. Vì vậy phân thức tăng không bị chặn:

$$
\lim_{x\to 1}\left(\frac{1}{(x-(1))^2}\right)=+\infty.
$$




### Bài D15.03 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(\frac{1}{(x-(2))^2}\right)$.


**Lời giải chi tiết**

Khi $x\to2$, mẫu $(x-2)^2>0$ và tiến về $0$, tử bằng $1>0$. Vì vậy phân thức tăng không bị chặn:

$$
\lim_{x\to 2}\left(\frac{1}{(x-(2))^2}\right)=+\infty.
$$




### Bài D15.04 · Nhận biết

Tính giới hạn $\lim_{x\to -1}\left(\frac{1}{(x+1)^2}\right)$.


**Lời giải chi tiết**

Khi $x\to-1$, mẫu $(x+1)^2>0$ và tiến về $0$, tử bằng $1>0$. Vì vậy phân thức tăng không bị chặn:

$$
\lim_{x\to -1}\left(\frac{1}{(x+1)^2}\right)=+\infty.
$$




### Bài D15.05 · Nhận biết

Tính giới hạn $\lim_{x\to -2}\left(\frac{1}{(x+2)^2}\right)$.


**Lời giải chi tiết**

Khi $x\to-2$, mẫu $(x+2)^2>0$ và tiến về $0$, tử bằng $1>0$. Vì vậy phân thức tăng không bị chặn:

$$
\lim_{x\to -2}\left(\frac{1}{(x+2)^2}\right)=+\infty.
$$




### Bài D15.06 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(\frac{-3}{(x-(0))^2}\right)$.


**Lời giải chi tiết**

Mẫu là bình phương dương tiến về $0^+$, còn tử là số âm $-3$.

$$
\lim_{x\to 0}\left(\frac{-3}{(x-(0))^2}\right)=-\infty.
$$




### Bài D15.07 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(\frac{-3}{(x-(1))^2}\right)$.


**Lời giải chi tiết**

Mẫu là bình phương dương tiến về $0^+$, còn tử là số âm $-3$.

$$
\lim_{x\to 1}\left(\frac{-3}{(x-(1))^2}\right)=-\infty.
$$




### Bài D15.08 · Thông hiểu

Tính giới hạn $\lim_{x\to 2}\left(\frac{-3}{(x-(2))^2}\right)$.


**Lời giải chi tiết**

Mẫu là bình phương dương tiến về $0^+$, còn tử là số âm $-3$.

$$
\lim_{x\to 2}\left(\frac{-3}{(x-(2))^2}\right)=-\infty.
$$




### Bài D15.09 · Thông hiểu

Tính giới hạn $\lim_{x\to -1}\left(\frac{-3}{(x+1)^2}\right)$.


**Lời giải chi tiết**

Mẫu là bình phương dương tiến về $0^+$, còn tử là số âm $-3$.

$$
\lim_{x\to -1}\left(\frac{-3}{(x+1)^2}\right)=-\infty.
$$




### Bài D15.10 · Thông hiểu

Tính giới hạn $\lim_{x\to -2}\left(\frac{-3}{(x+2)^2}\right)$.


**Lời giải chi tiết**

Mẫu là bình phương dương tiến về $0^+$, còn tử là số âm $-3$.

$$
\lim_{x\to -2}\left(\frac{-3}{(x+2)^2}\right)=-\infty.
$$




### Bài D15.11 · Thông hiểu

Tính hai giới hạn $\lim_{x\to 1^-}\frac{2}{x-(1)}$ và $\lim_{x\to 1^+}\frac{2}{x-(1)}$.


**Lời giải chi tiết**

Gần $x=1$, tử $2>0$. Ở bên trái $x-1<0$ còn bên phải $x-1>0$.

$$
\lim_{x\to 1^-}\frac{2}{x-(1)}=-\infty,\qquad\lim_{x\to 1^+}\frac{2}{x-(1)}=+\infty.
$$

Do hai phía có dấu vô cực khác nhau nên giới hạn hai phía không tồn tại.


### Bài D15.12 · Thông hiểu

Tính hai giới hạn $\lim_{x\to 2^-}\frac{3}{x-(2)}$ và $\lim_{x\to 2^+}\frac{3}{x-(2)}$.


**Lời giải chi tiết**

Gần $x=2$, tử $3>0$. Ở bên trái $x-2<0$ còn bên phải $x-2>0$.

$$
\lim_{x\to 2^-}\frac{3}{x-(2)}=-\infty,\qquad\lim_{x\to 2^+}\frac{3}{x-(2)}=+\infty.
$$

Do hai phía có dấu vô cực khác nhau nên giới hạn hai phía không tồn tại.


### Bài D15.13 · Thông hiểu

Tính hai giới hạn $\lim_{x\to 0^-}\frac{5}{x-(0)}$ và $\lim_{x\to 0^+}\frac{5}{x-(0)}$.


**Lời giải chi tiết**

Gần $x=0$, tử $5>0$. Ở bên trái $x-0<0$ còn bên phải $x-0>0$.

$$
\lim_{x\to 0^-}\frac{5}{x-(0)}=-\infty,\qquad\lim_{x\to 0^+}\frac{5}{x-(0)}=+\infty.
$$

Do hai phía có dấu vô cực khác nhau nên giới hạn hai phía không tồn tại.


### Bài D15.14 · Thông hiểu

Tính hai giới hạn $\lim_{x\to -1^-}\frac{4}{x+1}$ và $\lim_{x\to -1^+}\frac{4}{x+1}$.


**Lời giải chi tiết**

Gần $x=-1$, tử $4>0$. Ở bên trái $x+1<0$ còn bên phải $x+1>0$.

$$
\lim_{x\to -1^-}\frac{4}{x+1}=-\infty,\qquad\lim_{x\to -1^+}\frac{4}{x+1}=+\infty.
$$

Do hai phía có dấu vô cực khác nhau nên giới hạn hai phía không tồn tại.


### Bài D15.15 · Vận dụng

Tính hai giới hạn $\lim_{x\to 3^-}\frac{2}{x-(3)}$ và $\lim_{x\to 3^+}\frac{2}{x-(3)}$.


**Lời giải chi tiết**

Gần $x=3$, tử $2>0$. Ở bên trái $x-3<0$ còn bên phải $x-3>0$.

$$
\lim_{x\to 3^-}\frac{2}{x-(3)}=-\infty,\qquad\lim_{x\to 3^+}\frac{2}{x-(3)}=+\infty.
$$

Do hai phía có dấu vô cực khác nhau nên giới hạn hai phía không tồn tại.


### Bài D15.16 · Vận dụng

Tính $\lim_{x\to 1^-}\frac{2x+1}{(x-(1))^3}$ và $\lim_{x\to 1^+}\frac{2x+1}{(x-(1))^3}$.


**Lời giải chi tiết**

Tử tiến tới $3\ne0$ và giữ nguyên dấu gần $x=1$. Lũy thừa ba của $(x-1)$ âm bên trái, dương bên phải.

$$
\lim_{x\to 1^-}\frac{2x+1}{(x-(1))^3}=-\infty,\qquad\lim_{x\to 1^+}\frac{2x+1}{(x-(1))^3}=+\infty.
$$

Vì hai phía không cùng một giới hạn nên giới hạn hai phía không tồn tại.


### Bài D15.17 · Vận dụng

Tính $\lim_{x\to 2^-}\frac{-3x+1}{(x-(2))^3}$ và $\lim_{x\to 2^+}\frac{-3x+1}{(x-(2))^3}$.


**Lời giải chi tiết**

Tử tiến tới $-5\ne0$ và giữ nguyên dấu gần $x=2$. Lũy thừa ba của $(x-2)$ âm bên trái, dương bên phải.

$$
\lim_{x\to 2^-}\frac{-3x+1}{(x-(2))^3}=+\infty,\qquad\lim_{x\to 2^+}\frac{-3x+1}{(x-(2))^3}=-\infty.
$$

Vì hai phía không cùng một giới hạn nên giới hạn hai phía không tồn tại.


### Bài D15.18 · Vận dụng

Tính $\lim_{x\to 3^-}\frac{4x+1}{(x-(3))^3}$ và $\lim_{x\to 3^+}\frac{4x+1}{(x-(3))^3}$.


**Lời giải chi tiết**

Tử tiến tới $13\ne0$ và giữ nguyên dấu gần $x=3$. Lũy thừa ba của $(x-3)$ âm bên trái, dương bên phải.

$$
\lim_{x\to 3^-}\frac{4x+1}{(x-(3))^3}=-\infty,\qquad\lim_{x\to 3^+}\frac{4x+1}{(x-(3))^3}=+\infty.
$$

Vì hai phía không cùng một giới hạn nên giới hạn hai phía không tồn tại.


### Bài D15.19 · Vận dụng

Tính $\lim_{x\to -1^-}\frac{-2x+1}{(x+1)^3}$ và $\lim_{x\to -1^+}\frac{-2x+1}{(x+1)^3}$.


**Lời giải chi tiết**

Tử tiến tới $3\ne0$ và giữ nguyên dấu gần $x=-1$. Lũy thừa ba của $(x+1)$ âm bên trái, dương bên phải.

$$
\lim_{x\to -1^-}\frac{-2x+1}{(x+1)^3}=-\infty,\qquad\lim_{x\to -1^+}\frac{-2x+1}{(x+1)^3}=+\infty.
$$

Vì hai phía không cùng một giới hạn nên giới hạn hai phía không tồn tại.


### Bài D15.20 · Vận dụng

Tính $\lim_{x\to -2^-}\frac{5x+1}{(x+2)^3}$ và $\lim_{x\to -2^+}\frac{5x+1}{(x+2)^3}$.


**Lời giải chi tiết**

Tử tiến tới $-9\ne0$ và giữ nguyên dấu gần $x=-2$. Lũy thừa ba của $(x+2)$ âm bên trái, dương bên phải.

$$
\lim_{x\to -2^-}\frac{5x+1}{(x+2)^3}=+\infty,\qquad\lim_{x\to -2^+}\frac{5x+1}{(x+2)^3}=-\infty.
$$

Vì hai phía không cùng một giới hạn nên giới hạn hai phía không tồn tại.


---


## Dạng 16. Phân thức đa thức khi x→±∞

> [!tip] Phương pháp trọng tâm
> Chia cho lũy thừa x thích hợp và lưu ý xᵏ có thể âm khi x→−∞.


### Bài D16.01 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{3 \cdot x^{2} + 2 \cdot x + 1}{2 \cdot x^{2} + x + 3}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $x^2$. Mọi số hạng $1/x$, $1/x^2$ tiến về $0$.

$$
\lim_{x\to +\infty}\left(\frac{3 \cdot x^{2} + 2 \cdot x + 1}{2 \cdot x^{2} + x + 3}\right)=\frac{3}{2}.
$$




### Bài D16.02 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{- 4 \cdot x^{2} + 3 \cdot x + 1}{5 \cdot x^{2} - 2 \cdot x + 3}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $x^2$. Mọi số hạng $1/x$, $1/x^2$ tiến về $0$.

$$
\lim_{x\to +\infty}\left(\frac{- 4 \cdot x^{2} + 3 \cdot x + 1}{5 \cdot x^{2} - 2 \cdot x + 3}\right)=- \frac{4}{5}.
$$




### Bài D16.03 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{6 \cdot x^{2} - x + 1}{- 3 \cdot x^{2} + 4 \cdot x + 3}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $x^2$. Mọi số hạng $1/x$, $1/x^2$ tiến về $0$.

$$
\lim_{x\to +\infty}\left(\frac{6 \cdot x^{2} - x + 1}{- 3 \cdot x^{2} + 4 \cdot x + 3}\right)=-2.
$$




### Bài D16.04 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{2 \cdot x^{2} + 5 \cdot x + 1}{7 \cdot x^{2} + x + 3}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $x^2$. Mọi số hạng $1/x$, $1/x^2$ tiến về $0$.

$$
\lim_{x\to +\infty}\left(\frac{2 \cdot x^{2} + 5 \cdot x + 1}{7 \cdot x^{2} + x + 3}\right)=\frac{2}{7}.
$$




### Bài D16.05 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{9 \cdot x^{2} - 3 \cdot x + 1}{4 \cdot x^{2} + 2 \cdot x + 3}\right)$.


**Lời giải chi tiết**

Chia tử và mẫu cho $x^2$. Mọi số hạng $1/x$, $1/x^2$ tiến về $0$.

$$
\lim_{x\to +\infty}\left(\frac{9 \cdot x^{2} - 3 \cdot x + 1}{4 \cdot x^{2} + 2 \cdot x + 3}\right)=\frac{9}{4}.
$$




### Bài D16.06 · Nhận biết

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{x + 2}{3 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc mẫu lớn hơn bậc tử; chia cho $x^2$ rồi dùng $1/x\to0$, $1/x^2\to0$ khi $x\to-\infty$.

$$
\lim_{x\to -\infty}\left(\frac{x + 2}{3 \cdot x^{2} + 1}\right)=\lim_{x\to-\infty}\frac{1/x+2/x^2}{3+1/x^2}=0.
$$




### Bài D16.07 · Nhận biết

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{2 \cdot x - 1}{5 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc mẫu lớn hơn bậc tử; chia cho $x^2$ rồi dùng $1/x\to0$, $1/x^2\to0$ khi $x\to-\infty$.

$$
\lim_{x\to -\infty}\left(\frac{2 \cdot x - 1}{5 \cdot x^{2} + 1}\right)=\lim_{x\to-\infty}\frac{2/x-1/x^2}{5+1/x^2}=0.
$$




### Bài D16.08 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{4 - 3 \cdot x}{7 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc mẫu lớn hơn bậc tử; chia cho $x^2$ rồi dùng $1/x\to0$, $1/x^2\to0$ khi $x\to-\infty$.

$$
\lim_{x\to -\infty}\left(\frac{4 - 3 \cdot x}{7 \cdot x^{2} + 1}\right)=\lim_{x\to-\infty}\frac{-3/x+4/x^2}{7+1/x^2}=0.
$$




### Bài D16.09 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{4 \cdot x + 2}{x^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc mẫu lớn hơn bậc tử; chia cho $x^2$ rồi dùng $1/x\to0$, $1/x^2\to0$ khi $x\to-\infty$.

$$
\lim_{x\to -\infty}\left(\frac{4 \cdot x + 2}{x^{2} + 1}\right)=\lim_{x\to-\infty}\frac{4/x+2/x^2}{1+1/x^2}=0.
$$




### Bài D16.10 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{3 - 5 \cdot x}{2 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Bậc mẫu lớn hơn bậc tử; chia cho $x^2$ rồi dùng $1/x\to0$, $1/x^2\to0$ khi $x\to-\infty$.

$$
\lim_{x\to -\infty}\left(\frac{3 - 5 \cdot x}{2 \cdot x^{2} + 1}\right)=\lim_{x\to-\infty}\frac{-5/x+3/x^2}{2+1/x^2}=0.
$$




### Bài D16.11 · Thông hiểu

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{2 \cdot x^{3} + 1}{x^{2} + 2}\right)$.


**Lời giải chi tiết**

Bậc tử lớn hơn bậc mẫu một đơn vị. Chia cho $x^2$ ta thu được biểu thức có dạng gần $(2/1)x$. Vì $x\to+\infty$, dấu xác định bởi hệ số đầu.

$$
\lim_{x\to +\infty}\left(\frac{2 \cdot x^{3} + 1}{x^{2} + 2}\right)=+\infty.
$$




### Bài D16.12 · Thông hiểu

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{1 - 3 \cdot x^{3}}{4 \cdot x^{2} + 2}\right)$.


**Lời giải chi tiết**

Bậc tử lớn hơn bậc mẫu một đơn vị. Chia cho $x^2$ ta thu được biểu thức có dạng gần $(-3/4)x$. Vì $x\to+\infty$, dấu xác định bởi hệ số đầu.

$$
\lim_{x\to +\infty}\left(\frac{1 - 3 \cdot x^{3}}{4 \cdot x^{2} + 2}\right)=-\infty.
$$




### Bài D16.13 · Thông hiểu

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{4 \cdot x^{3} + 1}{2 - 5 \cdot x^{2}}\right)$.


**Lời giải chi tiết**

Bậc tử lớn hơn bậc mẫu một đơn vị. Chia cho $x^2$ ta thu được biểu thức có dạng gần $(4/-5)x$. Vì $x\to+\infty$, dấu xác định bởi hệ số đầu.

$$
\lim_{x\to +\infty}\left(\frac{4 \cdot x^{3} + 1}{2 - 5 \cdot x^{2}}\right)=-\infty.
$$




### Bài D16.14 · Thông hiểu

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{1 - 2 \cdot x^{3}}{2 - 3 \cdot x^{2}}\right)$.


**Lời giải chi tiết**

Bậc tử lớn hơn bậc mẫu một đơn vị. Chia cho $x^2$ ta thu được biểu thức có dạng gần $(-2/-3)x$. Vì $x\to+\infty$, dấu xác định bởi hệ số đầu.

$$
\lim_{x\to +\infty}\left(\frac{1 - 2 \cdot x^{3}}{2 - 3 \cdot x^{2}}\right)=+\infty.
$$




### Bài D16.15 · Vận dụng

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{5 \cdot x^{3} + 1}{x^{2} + 2}\right)$.


**Lời giải chi tiết**

Bậc tử lớn hơn bậc mẫu một đơn vị. Chia cho $x^2$ ta thu được biểu thức có dạng gần $(5/1)x$. Vì $x\to+\infty$, dấu xác định bởi hệ số đầu.

$$
\lim_{x\to +\infty}\left(\frac{5 \cdot x^{3} + 1}{x^{2} + 2}\right)=+\infty.
$$




### Bài D16.16 · Vận dụng

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{x^{3} + 2 \cdot x}{2 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Sau khi chia cho $x^2$, biểu thức có dạng gần $(1/2)x$. Vì $x\to-\infty$, dấu bị đảo so với hệ số $a/b$.

$$
\lim_{x\to -\infty}\left(\frac{x^{3} + 2 \cdot x}{2 \cdot x^{2} + 1}\right)=-\infty.
$$




### Bài D16.17 · Vận dụng

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{- 2 \cdot x^{3} + 2 \cdot x}{3 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Sau khi chia cho $x^2$, biểu thức có dạng gần $(-2/3)x$. Vì $x\to-\infty$, dấu bị đảo so với hệ số $a/b$.

$$
\lim_{x\to -\infty}\left(\frac{- 2 \cdot x^{3} + 2 \cdot x}{3 \cdot x^{2} + 1}\right)=+\infty.
$$




### Bài D16.18 · Vận dụng

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{3 \cdot x^{3} + 2 \cdot x}{1 - 4 \cdot x^{2}}\right)$.


**Lời giải chi tiết**

Sau khi chia cho $x^2$, biểu thức có dạng gần $(3/-4)x$. Vì $x\to-\infty$, dấu bị đảo so với hệ số $a/b$.

$$
\lim_{x\to -\infty}\left(\frac{3 \cdot x^{3} + 2 \cdot x}{1 - 4 \cdot x^{2}}\right)=+\infty.
$$




### Bài D16.19 · Vận dụng

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{- 4 \cdot x^{3} + 2 \cdot x}{1 - 5 \cdot x^{2}}\right)$.


**Lời giải chi tiết**

Sau khi chia cho $x^2$, biểu thức có dạng gần $(-4/-5)x$. Vì $x\to-\infty$, dấu bị đảo so với hệ số $a/b$.

$$
\lim_{x\to -\infty}\left(\frac{- 4 \cdot x^{3} + 2 \cdot x}{1 - 5 \cdot x^{2}}\right)=-\infty.
$$




### Bài D16.20 · Vận dụng

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{5 \cdot x^{3} + 2 \cdot x}{7 \cdot x^{2} + 1}\right)$.


**Lời giải chi tiết**

Sau khi chia cho $x^2$, biểu thức có dạng gần $(5/7)x$. Vì $x\to-\infty$, dấu bị đảo so với hệ số $a/b$.

$$
\lim_{x\to -\infty}\left(\frac{5 \cdot x^{3} + 2 \cdot x}{7 \cdot x^{2} + 1}\right)=-\infty.
$$




---


## Dạng 17. Căn thức khi x→±∞

> [!tip] Phương pháp trọng tâm
> Ở x→−∞ cần nhớ √(x²)=|x|=−x; có thể kết hợp liên hợp.


### Bài D17.01 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} + 2 \cdot x + 1}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp rồi chia cho $x>0$: 

$$
\begin{aligned}\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} + 2 \cdot x + 1}\right)&=\lim_{x\to+\infty}\frac{2x+1}{\sqrt{x^2+2x+1}+x}\\&=\lim_{x\to+\infty}\frac{2+1/x}{\sqrt{1+2/x+1/x^2}+1}=1.\end{aligned}
$$




### Bài D17.02 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} + 4 \cdot x + 3}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp rồi chia cho $x>0$: 

$$
\begin{aligned}\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} + 4 \cdot x + 3}\right)&=\lim_{x\to+\infty}\frac{4x+3}{\sqrt{x^2+4x+3}+x}\\&=\lim_{x\to+\infty}\frac{4+3/x}{\sqrt{1+4/x+3/x^2}+1}=2.\end{aligned}
$$




### Bài D17.03 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} - 2 \cdot x + 5}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp rồi chia cho $x>0$: 

$$
\begin{aligned}\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} - 2 \cdot x + 5}\right)&=\lim_{x\to+\infty}\frac{-2x+5}{\sqrt{x^2-2x+5}+x}\\&=\lim_{x\to+\infty}\frac{-2+5/x}{\sqrt{1-2/x+5/x^2}+1}=-1.\end{aligned}
$$




### Bài D17.04 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} + 6 \cdot x + 7}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp rồi chia cho $x>0$: 

$$
\begin{aligned}\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} + 6 \cdot x + 7}\right)&=\lim_{x\to+\infty}\frac{6x+7}{\sqrt{x^2+6x+7}+x}\\&=\lim_{x\to+\infty}\frac{6+7/x}{\sqrt{1+6/x+7/x^2}+1}=3.\end{aligned}
$$




### Bài D17.05 · Nhận biết

Tính giới hạn $\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} - 4 \cdot x + 10}\right)$.


**Lời giải chi tiết**

Đây là dạng $\infty-\infty$. Nhân liên hợp rồi chia cho $x>0$: 

$$
\begin{aligned}\lim_{x\to +\infty}\left(- x + \sqrt{x^{2} - 4 \cdot x + 10}\right)&=\lim_{x\to+\infty}\frac{-4x+10}{\sqrt{x^2-4x+10}+x}\\&=\lim_{x\to+\infty}\frac{-4+10/x}{\sqrt{1-4/x+10/x^2}+1}=-2.\end{aligned}
$$




### Bài D17.06 · Nhận biết

Tính giới hạn $\lim_{x\to -\infty}\left(x + \sqrt{x^{2} + 2 \cdot x + 5}\right)$.


**Lời giải chi tiết**

Lưu ý $x<0$, nên $\sqrt{x^2}=|x|=-x$. Nhân liên hợp với $\sqrt{x^2+ax+b}-x$.

$$
\begin{aligned}\lim_{x\to -\infty}\left(x + \sqrt{x^{2} + 2 \cdot x + 5}\right)&=\lim_{x\to-\infty}\frac{2x+5}{\sqrt{x^2+2x+5}-x}\\&=\lim_{x\to-\infty}\frac{2+5/x}{-\sqrt{1+2/x+5/x^2}-1}=-1.\end{aligned}
$$




### Bài D17.07 · Nhận biết

Tính giới hạn $\lim_{x\to -\infty}\left(x + \sqrt{x^{2} + 4 \cdot x + 7}\right)$.


**Lời giải chi tiết**

Lưu ý $x<0$, nên $\sqrt{x^2}=|x|=-x$. Nhân liên hợp với $\sqrt{x^2+ax+b}-x$.

$$
\begin{aligned}\lim_{x\to -\infty}\left(x + \sqrt{x^{2} + 4 \cdot x + 7}\right)&=\lim_{x\to-\infty}\frac{4x+7}{\sqrt{x^2+4x+7}-x}\\&=\lim_{x\to-\infty}\frac{4+7/x}{-\sqrt{1+4/x+7/x^2}-1}=-2.\end{aligned}
$$




### Bài D17.08 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(x + \sqrt{x^{2} - 2 \cdot x + 9}\right)$.


**Lời giải chi tiết**

Lưu ý $x<0$, nên $\sqrt{x^2}=|x|=-x$. Nhân liên hợp với $\sqrt{x^2+ax+b}-x$.

$$
\begin{aligned}\lim_{x\to -\infty}\left(x + \sqrt{x^{2} - 2 \cdot x + 9}\right)&=\lim_{x\to-\infty}\frac{-2x+9}{\sqrt{x^2-2x+9}-x}\\&=\lim_{x\to-\infty}\frac{-2+9/x}{-\sqrt{1-2/x+9/x^2}-1}=1.\end{aligned}
$$




### Bài D17.09 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(x + \sqrt{x^{2} + 6 \cdot x + 12}\right)$.


**Lời giải chi tiết**

Lưu ý $x<0$, nên $\sqrt{x^2}=|x|=-x$. Nhân liên hợp với $\sqrt{x^2+ax+b}-x$.

$$
\begin{aligned}\lim_{x\to -\infty}\left(x + \sqrt{x^{2} + 6 \cdot x + 12}\right)&=\lim_{x\to-\infty}\frac{6x+12}{\sqrt{x^2+6x+12}-x}\\&=\lim_{x\to-\infty}\frac{6+12/x}{-\sqrt{1+6/x+12/x^2}-1}=-3.\end{aligned}
$$




### Bài D17.10 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(x + \sqrt{x^{2} - 4 \cdot x + 14}\right)$.


**Lời giải chi tiết**

Lưu ý $x<0$, nên $\sqrt{x^2}=|x|=-x$. Nhân liên hợp với $\sqrt{x^2+ax+b}-x$.

$$
\begin{aligned}\lim_{x\to -\infty}\left(x + \sqrt{x^{2} - 4 \cdot x + 14}\right)&=\lim_{x\to-\infty}\frac{-4x+14}{\sqrt{x^2-4x+14}-x}\\&=\lim_{x\to-\infty}\frac{-4+14/x}{-\sqrt{1-4/x+14/x^2}-1}=2.\end{aligned}
$$




### Bài D17.11 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + x + 2}}{x}\right)$.


**Lời giải chi tiết**

Đưa $x^2$ ra khỏi căn, nhưng $\sqrt{x^2}=-x$ do $x<0$.

$$
\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + x + 2}}{x}\right)=\lim_{x\to-\infty}\frac{-x\sqrt{1+1/x+2/x^2}}{x}=-1.
$$




### Bài D17.12 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 4 \cdot x + 3}}{x}\right)$.


**Lời giải chi tiết**

Đưa $x^2$ ra khỏi căn, nhưng $\sqrt{x^2}=-x$ do $x<0$.

$$
\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 4 \cdot x + 3}}{x}\right)=\lim_{x\to-\infty}\frac{-x\sqrt{1+4/x+3/x^2}}{x}=-1.
$$




### Bài D17.13 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 9 \cdot x + 5}}{x}\right)$.


**Lời giải chi tiết**

Đưa $x^2$ ra khỏi căn, nhưng $\sqrt{x^2}=-x$ do $x<0$.

$$
\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 9 \cdot x + 5}}{x}\right)=\lim_{x\to-\infty}\frac{-x\sqrt{1+9/x+5/x^2}}{x}=-1.
$$




### Bài D17.14 · Thông hiểu

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 16 \cdot x + 7}}{x}\right)$.


**Lời giải chi tiết**

Đưa $x^2$ ra khỏi căn, nhưng $\sqrt{x^2}=-x$ do $x<0$.

$$
\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 16 \cdot x + 7}}{x}\right)=\lim_{x\to-\infty}\frac{-x\sqrt{1+16/x+7/x^2}}{x}=-1.
$$




### Bài D17.15 · Vận dụng

Tính giới hạn $\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 25 \cdot x + 11}}{x}\right)$.


**Lời giải chi tiết**

Đưa $x^2$ ra khỏi căn, nhưng $\sqrt{x^2}=-x$ do $x<0$.

$$
\lim_{x\to -\infty}\left(\frac{\sqrt{x^{2} + 25 \cdot x + 11}}{x}\right)=\lim_{x\to-\infty}\frac{-x\sqrt{1+25/x+11/x^2}}{x}=-1.
$$




### Bài D17.16 · Vận dụng

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{\sqrt{x^{2} + x + 1}}{x}\right)$.


**Lời giải chi tiết**

Vì $x>0$ khi $x\to+\infty$, ta có $\sqrt{x^2}=x$ nên

$$
\lim_{x\to +\infty}\left(\frac{\sqrt{x^{2} + x + 1}}{x}\right)=\lim_{x\to+\infty}\sqrt{1+1/x+1/x^2}=1.
$$




### Bài D17.17 · Vận dụng

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{\sqrt{4 \cdot x^{2} + 2 \cdot x + 1}}{x}\right)$.


**Lời giải chi tiết**

Vì $x>0$ khi $x\to+\infty$, ta có $\sqrt{x^2}=x$ nên

$$
\lim_{x\to +\infty}\left(\frac{\sqrt{4 \cdot x^{2} + 2 \cdot x + 1}}{x}\right)=\lim_{x\to+\infty}\sqrt{4+2/x+1/x^2}=2.
$$




### Bài D17.18 · Vận dụng

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{\sqrt{9 \cdot x^{2} + 3 \cdot x + 1}}{x}\right)$.


**Lời giải chi tiết**

Vì $x>0$ khi $x\to+\infty$, ta có $\sqrt{x^2}=x$ nên

$$
\lim_{x\to +\infty}\left(\frac{\sqrt{9 \cdot x^{2} + 3 \cdot x + 1}}{x}\right)=\lim_{x\to+\infty}\sqrt{9+3/x+1/x^2}=3.
$$




### Bài D17.19 · Vận dụng

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{\sqrt{16 \cdot x^{2} + 4 \cdot x + 1}}{x}\right)$.


**Lời giải chi tiết**

Vì $x>0$ khi $x\to+\infty$, ta có $\sqrt{x^2}=x$ nên

$$
\lim_{x\to +\infty}\left(\frac{\sqrt{16 \cdot x^{2} + 4 \cdot x + 1}}{x}\right)=\lim_{x\to+\infty}\sqrt{16+4/x+1/x^2}=4.
$$




### Bài D17.20 · Vận dụng

Tính giới hạn $\lim_{x\to +\infty}\left(\frac{\sqrt{25 \cdot x^{2} + 5 \cdot x + 1}}{x}\right)$.


**Lời giải chi tiết**

Vì $x>0$ khi $x\to+\infty$, ta có $\sqrt{x^2}=x$ nên

$$
\lim_{x\to +\infty}\left(\frac{\sqrt{25 \cdot x^{2} + 5 \cdot x + 1}}{x}\right)=\lim_{x\to+\infty}\sqrt{25+5/x+1/x^2}=5.
$$




---


## Dạng 18. Bài toán tổng hợp, kẹp và dao động

> [!tip] Phương pháp trọng tâm
> Dùng giới hạn từng phần, kẹp và nhận diện các dạng vô định 0·∞, ∞−∞.


### Bài D18.01 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(1x^1\sin\frac1x\right)$.


**Lời giải chi tiết**

Vì $|\sin(1/x)|\le1$ nên $|1x^1\sin(1/x)|\le1|x|^1$. Suy ra

$$
-1|x|^1\le 1x^1\sin\frac1x\le1|x|^1\quad\Rightarrow\quad \lim_{x\to 0}\left(1x^1\sin\frac1x\right)=0.
$$




### Bài D18.02 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(2x^1\sin\frac1x\right)$.


**Lời giải chi tiết**

Vì $|\sin(1/x)|\le1$ nên $|2x^1\sin(1/x)|\le2|x|^1$. Suy ra

$$
-2|x|^1\le 2x^1\sin\frac1x\le2|x|^1\quad\Rightarrow\quad \lim_{x\to 0}\left(2x^1\sin\frac1x\right)=0.
$$




### Bài D18.03 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(3x^1\sin\frac1x\right)$.


**Lời giải chi tiết**

Vì $|\sin(1/x)|\le1$ nên $|3x^1\sin(1/x)|\le3|x|^1$. Suy ra

$$
-3|x|^1\le 3x^1\sin\frac1x\le3|x|^1\quad\Rightarrow\quad \lim_{x\to 0}\left(3x^1\sin\frac1x\right)=0.
$$




### Bài D18.04 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(4x^2\sin\frac1x\right)$.


**Lời giải chi tiết**

Vì $|\sin(1/x)|\le1$ nên $|4x^2\sin(1/x)|\le4|x|^2$. Suy ra

$$
-4|x|^2\le 4x^2\sin\frac1x\le4|x|^2\quad\Rightarrow\quad \lim_{x\to 0}\left(4x^2\sin\frac1x\right)=0.
$$




### Bài D18.05 · Nhận biết

Tính giới hạn $\lim_{x\to 0}\left(5x^2\sin\frac1x\right)$.


**Lời giải chi tiết**

Vì $|\sin(1/x)|\le1$ nên $|5x^2\sin(1/x)|\le5|x|^2$. Suy ra

$$
-5|x|^2\le 5x^2\sin\frac1x\le5|x|^2\quad\Rightarrow\quad \lim_{x\to 0}\left(5x^2\sin\frac1x\right)=0.
$$




### Bài D18.06 · Nhận biết

Tính giới hạn $\lim_{x\to 1}\left(2(x-1)^1\cos\frac1{x-1}\right)$.


**Lời giải chi tiết**

Với mọi $x\ne1$, có $|\cos(1/(x-1))|\le1$.

$$
\left|2(x-1)^1\cos\frac1{x-1}\right|\le2|x-1|^1\to0\quad\Rightarrow\quad \lim_{x\to 1}\left(2(x-1)^1\cos\frac1{x-1}\right)=0.
$$




### Bài D18.07 · Nhận biết

Tính giới hạn $\lim_{x\to 2}\left(3(x-2)^1\cos\frac1{x-2}\right)$.


**Lời giải chi tiết**

Với mọi $x\ne2$, có $|\cos(1/(x-2))|\le1$.

$$
\left|3(x-2)^1\cos\frac1{x-2}\right|\le3|x-2|^1\to0\quad\Rightarrow\quad \lim_{x\to 2}\left(3(x-2)^1\cos\frac1{x-2}\right)=0.
$$




### Bài D18.08 · Thông hiểu

Tính giới hạn $\lim_{x\to 3}\left(4(x-3)^1\cos\frac1{x-3}\right)$.


**Lời giải chi tiết**

Với mọi $x\ne3$, có $|\cos(1/(x-3))|\le1$.

$$
\left|4(x-3)^1\cos\frac1{x-3}\right|\le4|x-3|^1\to0\quad\Rightarrow\quad \lim_{x\to 3}\left(4(x-3)^1\cos\frac1{x-3}\right)=0.
$$




### Bài D18.09 · Thông hiểu

Tính giới hạn $\lim_{x\to 4}\left(5(x-4)^2\cos\frac1{x-4}\right)$.


**Lời giải chi tiết**

Với mọi $x\ne4$, có $|\cos(1/(x-4))|\le1$.

$$
\left|5(x-4)^2\cos\frac1{x-4}\right|\le5|x-4|^2\to0\quad\Rightarrow\quad \lim_{x\to 4}\left(5(x-4)^2\cos\frac1{x-4}\right)=0.
$$




### Bài D18.10 · Thông hiểu

Tính giới hạn $\lim_{x\to 5}\left(6(x-5)^2\cos\frac1{x-5}\right)$.


**Lời giải chi tiết**

Với mọi $x\ne5$, có $|\cos(1/(x-5))|\le1$.

$$
\left|6(x-5)^2\cos\frac1{x-5}\right|\le6|x-5|^2\to0\quad\Rightarrow\quad \lim_{x\to 5}\left(6(x-5)^2\cos\frac1{x-5}\right)=0.
$$




### Bài D18.11 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x+1}-\sqrt{1}}{x}\cdot\left(\sqrt{x+1}+\sqrt{1}\right)\right)$.


**Lời giải chi tiết**

Tích gồm thừa số có căn và liên hợp. Nhân tử số với thừa số liên hợp: $(1+x)-1=x$. Với $x\ne0$, tích bằng $1$.

$$
\lim_{x\to 0}\left(\frac{\sqrt{x+1}-\sqrt{1}}{x}\cdot\left(\sqrt{x+1}+\sqrt{1}\right)\right)=\lim_{x\to0}\frac{x}{x}=1.
$$




### Bài D18.12 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x+2}-\sqrt{2}}{x}\cdot\left(\sqrt{x+2}+\sqrt{2}\right)\right)$.


**Lời giải chi tiết**

Tích gồm thừa số có căn và liên hợp. Nhân tử số với thừa số liên hợp: $(2+x)-2=x$. Với $x\ne0$, tích bằng $1$.

$$
\lim_{x\to 0}\left(\frac{\sqrt{x+2}-\sqrt{2}}{x}\cdot\left(\sqrt{x+2}+\sqrt{2}\right)\right)=\lim_{x\to0}\frac{x}{x}=1.
$$




### Bài D18.13 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x+3}-\sqrt{3}}{x}\cdot\left(\sqrt{x+3}+\sqrt{3}\right)\right)$.


**Lời giải chi tiết**

Tích gồm thừa số có căn và liên hợp. Nhân tử số với thừa số liên hợp: $(3+x)-3=x$. Với $x\ne0$, tích bằng $1$.

$$
\lim_{x\to 0}\left(\frac{\sqrt{x+3}-\sqrt{3}}{x}\cdot\left(\sqrt{x+3}+\sqrt{3}\right)\right)=\lim_{x\to0}\frac{x}{x}=1.
$$




### Bài D18.14 · Thông hiểu

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x+4}-\sqrt{4}}{x}\cdot\left(\sqrt{x+4}+\sqrt{4}\right)\right)$.


**Lời giải chi tiết**

Tích gồm thừa số có căn và liên hợp. Nhân tử số với thừa số liên hợp: $(4+x)-4=x$. Với $x\ne0$, tích bằng $1$.

$$
\lim_{x\to 0}\left(\frac{\sqrt{x+4}-\sqrt{4}}{x}\cdot\left(\sqrt{x+4}+\sqrt{4}\right)\right)=\lim_{x\to0}\frac{x}{x}=1.
$$




### Bài D18.15 · Vận dụng

Tính giới hạn $\lim_{x\to 0}\left(\frac{\sqrt{x+5}-\sqrt{5}}{x}\cdot\left(\sqrt{x+5}+\sqrt{5}\right)\right)$.


**Lời giải chi tiết**

Tích gồm thừa số có căn và liên hợp. Nhân tử số với thừa số liên hợp: $(5+x)-5=x$. Với $x\ne0$, tích bằng $1$.

$$
\lim_{x\to 0}\left(\frac{\sqrt{x+5}-\sqrt{5}}{x}\cdot\left(\sqrt{x+5}+\sqrt{5}\right)\right)=\lim_{x\to0}\frac{x}{x}=1.
$$




### Bài D18.16 · Vận dụng

Xét sự tồn tại của $\lim_{x\to 0}\left(1+\sin\frac1x\right)$.


**Lời giải chi tiết**

Chọn hai dãy $x_k=\dfrac1{\frac\pi2+2k\pi}$ và $y_k=\dfrac1{\frac{3\pi}2+2k\pi}$, đều tiến về $0^+$. Khi đó $\sin(1/x_k)=1$ nhưng $\sin(1/y_k)=-1$.

$$
\lim_{k\to+\infty}\left(1+\sin\frac1{x_k}\right)=2,\qquad\lim_{k\to+\infty}\left(1+\sin\frac1{y_k}\right)=0.
$$

Hai kết quả khác nhau; **giới hạn không tồn tại**.


### Bài D18.17 · Vận dụng

Xét sự tồn tại của $\lim_{x\to 0}\left(2+\sin\frac1x\right)$.


**Lời giải chi tiết**

Chọn hai dãy $x_k=\dfrac1{\frac\pi2+2k\pi}$ và $y_k=\dfrac1{\frac{3\pi}2+2k\pi}$, đều tiến về $0^+$. Khi đó $\sin(1/x_k)=1$ nhưng $\sin(1/y_k)=-1$.

$$
\lim_{k\to+\infty}\left(2+\sin\frac1{x_k}\right)=3,\qquad\lim_{k\to+\infty}\left(2+\sin\frac1{y_k}\right)=1.
$$

Hai kết quả khác nhau; **giới hạn không tồn tại**.


### Bài D18.18 · Vận dụng

Xét sự tồn tại của $\lim_{x\to 0}\left(3+\sin\frac1x\right)$.


**Lời giải chi tiết**

Chọn hai dãy $x_k=\dfrac1{\frac\pi2+2k\pi}$ và $y_k=\dfrac1{\frac{3\pi}2+2k\pi}$, đều tiến về $0^+$. Khi đó $\sin(1/x_k)=1$ nhưng $\sin(1/y_k)=-1$.

$$
\lim_{k\to+\infty}\left(3+\sin\frac1{x_k}\right)=4,\qquad\lim_{k\to+\infty}\left(3+\sin\frac1{y_k}\right)=2.
$$

Hai kết quả khác nhau; **giới hạn không tồn tại**.


### Bài D18.19 · Vận dụng

Xét sự tồn tại của $\lim_{x\to 0}\left(4+\sin\frac1x\right)$.


**Lời giải chi tiết**

Chọn hai dãy $x_k=\dfrac1{\frac\pi2+2k\pi}$ và $y_k=\dfrac1{\frac{3\pi}2+2k\pi}$, đều tiến về $0^+$. Khi đó $\sin(1/x_k)=1$ nhưng $\sin(1/y_k)=-1$.

$$
\lim_{k\to+\infty}\left(4+\sin\frac1{x_k}\right)=5,\qquad\lim_{k\to+\infty}\left(4+\sin\frac1{y_k}\right)=3.
$$

Hai kết quả khác nhau; **giới hạn không tồn tại**.


### Bài D18.20 · Vận dụng

Xét sự tồn tại của $\lim_{x\to 0}\left(5+\sin\frac1x\right)$.


**Lời giải chi tiết**

Chọn hai dãy $x_k=\dfrac1{\frac\pi2+2k\pi}$ và $y_k=\dfrac1{\frac{3\pi}2+2k\pi}$, đều tiến về $0^+$. Khi đó $\sin(1/x_k)=1$ nhưng $\sin(1/y_k)=-1$.

$$
\lim_{k\to+\infty}\left(5+\sin\frac1{x_k}\right)=6,\qquad\lim_{k\to+\infty}\left(5+\sin\frac1{y_k}\right)=4.
$$

Hai kết quả khác nhau; **giới hạn không tồn tại**.


---


# PHẦN C · HÀM SỐ LIÊN TỤC


## Dạng 19. Tính liên tục tại một điểm và tìm tham số

> [!tip] Phương pháp trọng tâm
> So sánh limₓ→ₐ f(x) với f(a); ở hàm ghép xét hai giới hạn một bên.


### Bài D19.01 · Nhận biết

Tìm $m$ để hàm số 
$$
f(x)=\begin{cases}\frac{x^2-1}{x-(1)},&x\ne1,\\m,&x=1.\end{cases}
$$

 liên tục tại $x=1$.


**Lời giải chi tiết**

Điều kiện liên tục là $f(1)=\lim_{x\to1}f(x)$. Với $x\ne1$, dùng hiệu hai bình phương:

$$
\lim_{x\to1}\frac{x^2-1}{x-(1)}=\lim_{x\to1}(x+1)=2.
$$

Vì $f(1)=m$, giá trị cần tìm là $\boxed{m=2}$.


### Bài D19.02 · Nhận biết

Tìm $m$ để hàm số 
$$
f(x)=\begin{cases}\frac{x^2-4}{x-(2)},&x\ne2,\\m,&x=2.\end{cases}
$$

 liên tục tại $x=2$.


**Lời giải chi tiết**

Điều kiện liên tục là $f(2)=\lim_{x\to2}f(x)$. Với $x\ne2$, dùng hiệu hai bình phương:

$$
\lim_{x\to2}\frac{x^2-4}{x-(2)}=\lim_{x\to2}(x+2)=4.
$$

Vì $f(2)=m$, giá trị cần tìm là $\boxed{m=4}$.


### Bài D19.03 · Nhận biết

Tìm $m$ để hàm số 
$$
f(x)=\begin{cases}\frac{x^2-9}{x-(3)},&x\ne3,\\m,&x=3.\end{cases}
$$

 liên tục tại $x=3$.


**Lời giải chi tiết**

Điều kiện liên tục là $f(3)=\lim_{x\to3}f(x)$. Với $x\ne3$, dùng hiệu hai bình phương:

$$
\lim_{x\to3}\frac{x^2-9}{x-(3)}=\lim_{x\to3}(x+3)=6.
$$

Vì $f(3)=m$, giá trị cần tìm là $\boxed{m=6}$.


### Bài D19.04 · Nhận biết

Tìm $m$ để hàm số 
$$
f(x)=\begin{cases}\frac{x^2-1}{x+1},&x\ne-1,\\m,&x=-1.\end{cases}
$$

 liên tục tại $x=-1$.


**Lời giải chi tiết**

Điều kiện liên tục là $f(-1)=\lim_{x\to-1}f(x)$. Với $x\ne-1$, dùng hiệu hai bình phương:

$$
\lim_{x\to-1}\frac{x^2-1}{x+1}=\lim_{x\to-1}(x-1)=-2.
$$

Vì $f(-1)=m$, giá trị cần tìm là $\boxed{m=-2}$.


### Bài D19.05 · Nhận biết

Tìm $m$ để hàm số 
$$
f(x)=\begin{cases}\frac{x^2-4}{x+2},&x\ne-2,\\m,&x=-2.\end{cases}
$$

 liên tục tại $x=-2$.


**Lời giải chi tiết**

Điều kiện liên tục là $f(-2)=\lim_{x\to-2}f(x)$. Với $x\ne-2$, dùng hiệu hai bình phương:

$$
\lim_{x\to-2}\frac{x^2-4}{x+2}=\lim_{x\to-2}(x-2)=-4.
$$

Vì $f(-2)=m$, giá trị cần tìm là $\boxed{m=-4}$.


### Bài D19.06 · Nhận biết

Tìm $m$ để hàm số sau liên tục tại $x=0$:
$$
f(x)=\begin{cases}x^{2} + 2 \cdot x + 1,&x<0,\\m,&x=0,\\2 \cdot x + 1,&x>0.\end{cases}
$$




**Lời giải chi tiết**

Tính giới hạn hai phía (không được thay nhánh giữa để lấy giới hạn):

$$
\lim_{x\to0^-}f(x)=0+(2)\cdot(0)+1=1,\quad\lim_{x\to0^+}f(x)=(2)(0)+1-0=1.
$$

Hai phía bằng nhau, nên $\lim_{x\to0}f(x)=1$. Hàm liên tục khi $m=1$.


### Bài D19.07 · Nhận biết

Tìm $m$ để hàm số sau liên tục tại $x=1$:
$$
f(x)=\begin{cases}x^{2} + 3 \cdot x + 1,&x<1,\\m,&x=1,\\5 \cdot x,&x>1.\end{cases}
$$




**Lời giải chi tiết**

Tính giới hạn hai phía (không được thay nhánh giữa để lấy giới hạn):

$$
\lim_{x\to1^-}f(x)=1+(3)\cdot(1)+1=5,\quad\lim_{x\to1^+}f(x)=(5)(1)+1-1=5.
$$

Hai phía bằng nhau, nên $\lim_{x\to1}f(x)=5$. Hàm liên tục khi $m=5$.


### Bài D19.08 · Thông hiểu

Tìm $m$ để hàm số sau liên tục tại $x=2$:
$$
f(x)=\begin{cases}x^{2} + 4 \cdot x + 1,&x<2,\\m,&x=2,\\8 \cdot x - 3,&x>2.\end{cases}
$$




**Lời giải chi tiết**

Tính giới hạn hai phía (không được thay nhánh giữa để lấy giới hạn):

$$
\lim_{x\to2^-}f(x)=4+(4)\cdot(2)+1=13,\quad\lim_{x\to2^+}f(x)=(8)(2)+1-4=13.
$$

Hai phía bằng nhau, nên $\lim_{x\to2}f(x)=13$. Hàm liên tục khi $m=13$.


### Bài D19.09 · Thông hiểu

Tìm $m$ để hàm số sau liên tục tại $x=3$:
$$
f(x)=\begin{cases}x^{2} - x + 1,&x<3,\\m,&x=3,\\5 \cdot x - 8,&x>3.\end{cases}
$$




**Lời giải chi tiết**

Tính giới hạn hai phía (không được thay nhánh giữa để lấy giới hạn):

$$
\lim_{x\to3^-}f(x)=9-1\cdot(3)+1=7,\quad\lim_{x\to3^+}f(x)=(5)(3)+1-9=7.
$$

Hai phía bằng nhau, nên $\lim_{x\to3}f(x)=7$. Hàm liên tục khi $m=7$.


### Bài D19.10 · Thông hiểu

Tìm $m$ để hàm số sau liên tục tại $x=-1$:
$$
f(x)=\begin{cases}x^{2} + 5 \cdot x + 1,&x<-1,\\m,&x=-1,\\3 \cdot x,&x>-1.\end{cases}
$$




**Lời giải chi tiết**

Tính giới hạn hai phía (không được thay nhánh giữa để lấy giới hạn):

$$
\lim_{x\to-1^-}f(x)=1+(5)\cdot(-1)+1=-3,\quad\lim_{x\to-1^+}f(x)=(3)(-1)+1-1=-3.
$$

Hai phía bằng nhau, nên $\lim_{x\to-1}f(x)=-3$. Hàm liên tục khi $m=-3$.


### Bài D19.11 · Thông hiểu

Tìm $m$ để hàm 
$$
f(x)=\begin{cases}x^2+2,&x<1,\\m x+2,&x\ge1.\end{cases}
$$

 liên tục tại $x=1$.


**Lời giải chi tiết**

Hai nhánh là đa thức nên chỉ cần nối khớp tại điểm ghép:

$$
\lim_{x\to1^-}f(x)=1^2+2=3,\qquad\lim_{x\to1^+}f(x)=m(1)+2.
$$

Đặt $1m+2=3$, vì $1\ne0$ suy ra $\boxed{m=1}$. Giá trị này bảo đảm giới hạn bằng giá trị hàm tại điểm ghép.


### Bài D19.12 · Thông hiểu

Tìm $m$ để hàm 
$$
f(x)=\begin{cases}x^2+3,&x<2,\\m x+3,&x\ge2.\end{cases}
$$

 liên tục tại $x=2$.


**Lời giải chi tiết**

Hai nhánh là đa thức nên chỉ cần nối khớp tại điểm ghép:

$$
\lim_{x\to2^-}f(x)=2^2+3=7,\qquad\lim_{x\to2^+}f(x)=m(2)+3.
$$

Đặt $2m+3=7$, vì $2\ne0$ suy ra $\boxed{m=2}$. Giá trị này bảo đảm giới hạn bằng giá trị hàm tại điểm ghép.


### Bài D19.13 · Thông hiểu

Tìm $m$ để hàm 
$$
f(x)=\begin{cases}x^2+4,&x<3,\\m x+4,&x\ge3.\end{cases}
$$

 liên tục tại $x=3$.


**Lời giải chi tiết**

Hai nhánh là đa thức nên chỉ cần nối khớp tại điểm ghép:

$$
\lim_{x\to3^-}f(x)=3^2+4=13,\qquad\lim_{x\to3^+}f(x)=m(3)+4.
$$

Đặt $3m+4=13$, vì $3\ne0$ suy ra $\boxed{m=3}$. Giá trị này bảo đảm giới hạn bằng giá trị hàm tại điểm ghép.


### Bài D19.14 · Thông hiểu

Tìm $m$ để hàm 
$$
f(x)=\begin{cases}x^2+5,&x<-1,\\m x+5,&x\ge-1.\end{cases}
$$

 liên tục tại $x=-1$.


**Lời giải chi tiết**

Hai nhánh là đa thức nên chỉ cần nối khớp tại điểm ghép:

$$
\lim_{x\to-1^-}f(x)=-1^2+5=6,\qquad\lim_{x\to-1^+}f(x)=m(-1)+5.
$$

Đặt $-1m+5=6$, vì $-1\ne0$ suy ra $\boxed{m=-1}$. Giá trị này bảo đảm giới hạn bằng giá trị hàm tại điểm ghép.


### Bài D19.15 · Vận dụng

Tìm $m$ để hàm 
$$
f(x)=\begin{cases}x^2+4,&x<-2,\\m x+4,&x\ge-2.\end{cases}
$$

 liên tục tại $x=-2$.


**Lời giải chi tiết**

Hai nhánh là đa thức nên chỉ cần nối khớp tại điểm ghép:

$$
\lim_{x\to-2^-}f(x)=-2^2+4=8,\qquad\lim_{x\to-2^+}f(x)=m(-2)+4.
$$

Đặt $-2m+4=8$, vì $-2\ne0$ suy ra $\boxed{m=-2}$. Giá trị này bảo đảm giới hạn bằng giá trị hàm tại điểm ghép.


### Bài D19.16 · Vận dụng

Xét tính liên tục tại $x=1$ của hàm số 
$$
f(x)=\begin{cases}\frac{x^2-1}{x-1},&x\ne 1,\\5,&x=1.\end{cases}
$$




**Lời giải chi tiết**

Với $x\ne1$, rút gọn phân thức được $x+1$ nên

$$
\lim_{x\to1}f(x)=\lim_{x\to1}(x+1)=2.
$$

Tuy nhiên $f(1)=5\ne 2$. Do đó hàm **không liên tục tại $x=1$** (gián đoạn có thể khử).


### Bài D19.17 · Vận dụng

Xét tính liên tục tại $x=2$ của hàm số 
$$
f(x)=\begin{cases}\frac{x^2-4}{x-2},&x\ne 2,\\8,&x=2.\end{cases}
$$




**Lời giải chi tiết**

Với $x\ne2$, rút gọn phân thức được $x+2$ nên

$$
\lim_{x\to2}f(x)=\lim_{x\to2}(x+2)=4.
$$

Tuy nhiên $f(2)=8\ne 4$. Do đó hàm **không liên tục tại $x=2$** (gián đoạn có thể khử).


### Bài D19.18 · Vận dụng

Xét tính liên tục tại $x=3$ của hàm số 
$$
f(x)=\begin{cases}\frac{x^2-9}{x-3},&x\ne 3,\\11,&x=3.\end{cases}
$$




**Lời giải chi tiết**

Với $x\ne3$, rút gọn phân thức được $x+3$ nên

$$
\lim_{x\to3}f(x)=\lim_{x\to3}(x+3)=6.
$$

Tuy nhiên $f(3)=11\ne 6$. Do đó hàm **không liên tục tại $x=3$** (gián đoạn có thể khử).


### Bài D19.19 · Vận dụng

Xét tính liên tục tại $x=-1$ của hàm số 
$$
f(x)=\begin{cases}\frac{x^2-1}{x+1},&x\ne -1,\\2,&x=-1.\end{cases}
$$




**Lời giải chi tiết**

Với $x\ne-1$, rút gọn phân thức được $x-1$ nên

$$
\lim_{x\to-1}f(x)=\lim_{x\to-1}(x-1)=-2.
$$

Tuy nhiên $f(-1)=2\ne -2$. Do đó hàm **không liên tục tại $x=-1$** (gián đoạn có thể khử).


### Bài D19.20 · Vận dụng

Xét tính liên tục tại $x=-2$ của hàm số 
$$
f(x)=\begin{cases}\frac{x^2-4}{x+2},&x\ne -2,\\1,&x=-2.\end{cases}
$$




**Lời giải chi tiết**

Với $x\ne-2$, rút gọn phân thức được $x-2$ nên

$$
\lim_{x\to-2}f(x)=\lim_{x\to-2}(x-2)=-4.
$$

Tuy nhiên $f(-2)=1\ne -4$. Do đó hàm **không liên tục tại $x=-2$** (gián đoạn có thể khử).


---


## Dạng 20. Liên tục trên khoảng, đoạn và tồn tại nghiệm

> [!tip] Phương pháp trọng tâm
> Xác định khoảng liên tục; áp dụng định lí giá trị trung gian khi f(a)f(b)<0.


### Bài D20.01 · Nhận biết

Xác định các khoảng liên tục của hàm số $f(x)=\frac{1}{x - 1}$.


**Lời giải chi tiết**

Thương hai đa thức liên tục tại mọi điểm mà mẫu khác $0$. Mẫu bằng $0$ khi $x=1$, nên miền xác định $D=\mathbb R\setminus\{1\}$.

$$
f\text{ liên tục trên }(-\infty,1)\text{ và }(1,+\infty).
$$




### Bài D20.02 · Nhận biết

Xác định các khoảng liên tục của hàm số $f(x)=\frac{1}{x - 2}$.


**Lời giải chi tiết**

Thương hai đa thức liên tục tại mọi điểm mà mẫu khác $0$. Mẫu bằng $0$ khi $x=2$, nên miền xác định $D=\mathbb R\setminus\{2\}$.

$$
f\text{ liên tục trên }(-\infty,2)\text{ và }(2,+\infty).
$$




### Bài D20.03 · Nhận biết

Xác định các khoảng liên tục của hàm số $f(x)=\frac{1}{x - 3}$.


**Lời giải chi tiết**

Thương hai đa thức liên tục tại mọi điểm mà mẫu khác $0$. Mẫu bằng $0$ khi $x=3$, nên miền xác định $D=\mathbb R\setminus\{3\}$.

$$
f\text{ liên tục trên }(-\infty,3)\text{ và }(3,+\infty).
$$




### Bài D20.04 · Nhận biết

Xác định các khoảng liên tục của hàm số $f(x)=\frac{1}{x + 1}$.


**Lời giải chi tiết**

Thương hai đa thức liên tục tại mọi điểm mà mẫu khác $0$. Mẫu bằng $0$ khi $x=-1$, nên miền xác định $D=\mathbb R\setminus\{-1\}$.

$$
f\text{ liên tục trên }(-\infty,-1)\text{ và }(-1,+\infty).
$$




### Bài D20.05 · Nhận biết

Xác định các khoảng liên tục của hàm số $f(x)=\frac{1}{x + 2}$.


**Lời giải chi tiết**

Thương hai đa thức liên tục tại mọi điểm mà mẫu khác $0$. Mẫu bằng $0$ khi $x=-2$, nên miền xác định $D=\mathbb R\setminus\{-2\}$.

$$
f\text{ liên tục trên }(-\infty,-2)\text{ và }(-2,+\infty).
$$




### Bài D20.06 · Nhận biết

Xác định miền liên tục của hàm số $f(x)=\sqrt{x - 1}$ và xét tính liên tục tại đầu mút miền xác định.


**Lời giải chi tiết**

Điều kiện căn bậc hai là $x-1\ge0$, tức $x\ge1$. Hàm căn liên tục trên miền xác định và tại đầu mút xét giới hạn phải:

$$
\lim_{x\to 1^+}\sqrt{x-1}=0=f(1).
$$

Vì vậy hàm liên tục trên $[1,+\infty)$ (hiểu liên tục tại đầu mút theo phía thuộc miền xác định).


### Bài D20.07 · Nhận biết

Xác định miền liên tục của hàm số $f(x)=\sqrt{x - 2}$ và xét tính liên tục tại đầu mút miền xác định.


**Lời giải chi tiết**

Điều kiện căn bậc hai là $x-2\ge0$, tức $x\ge2$. Hàm căn liên tục trên miền xác định và tại đầu mút xét giới hạn phải:

$$
\lim_{x\to 2^+}\sqrt{x-2}=0=f(2).
$$

Vì vậy hàm liên tục trên $[2,+\infty)$ (hiểu liên tục tại đầu mút theo phía thuộc miền xác định).


### Bài D20.08 · Thông hiểu

Xác định miền liên tục của hàm số $f(x)=\sqrt{x - 3}$ và xét tính liên tục tại đầu mút miền xác định.


**Lời giải chi tiết**

Điều kiện căn bậc hai là $x-3\ge0$, tức $x\ge3$. Hàm căn liên tục trên miền xác định và tại đầu mút xét giới hạn phải:

$$
\lim_{x\to 3^+}\sqrt{x-3}=0=f(3).
$$

Vì vậy hàm liên tục trên $[3,+\infty)$ (hiểu liên tục tại đầu mút theo phía thuộc miền xác định).


### Bài D20.09 · Thông hiểu

Xác định miền liên tục của hàm số $f(x)=\sqrt{x - 4}$ và xét tính liên tục tại đầu mút miền xác định.


**Lời giải chi tiết**

Điều kiện căn bậc hai là $x-4\ge0$, tức $x\ge4$. Hàm căn liên tục trên miền xác định và tại đầu mút xét giới hạn phải:

$$
\lim_{x\to 4^+}\sqrt{x-4}=0=f(4).
$$

Vì vậy hàm liên tục trên $[4,+\infty)$ (hiểu liên tục tại đầu mút theo phía thuộc miền xác định).


### Bài D20.10 · Thông hiểu

Xác định miền liên tục của hàm số $f(x)=\sqrt{x - 5}$ và xét tính liên tục tại đầu mút miền xác định.


**Lời giải chi tiết**

Điều kiện căn bậc hai là $x-5\ge0$, tức $x\ge5$. Hàm căn liên tục trên miền xác định và tại đầu mút xét giới hạn phải:

$$
\lim_{x\to 5^+}\sqrt{x-5}=0=f(5).
$$

Vì vậy hàm liên tục trên $[5,+\infty)$ (hiểu liên tục tại đầu mút theo phía thuộc miền xác định).


### Bài D20.11 · Thông hiểu

Chứng minh phương trình $x^2-2=0$ có ít nhất một nghiệm trên khoảng $(0,2)$ bằng định lí liên tục.


**Lời giải chi tiết**

Xét $f(x)=x^2-2$ liên tục trên $[0,2]$ vì là đa thức. Tính:

$$
f(0)=-2<0,\qquad f(2)=2>0.
$$

Do $f(0)f(2)<0$, theo định lí giá trị trung gian tồn tại $c\in(0,2)$ sao cho $f(c)=0$.


### Bài D20.12 · Thông hiểu

Chứng minh phương trình $x^2-3=0$ có ít nhất một nghiệm trên khoảng $(0,3)$ bằng định lí liên tục.


**Lời giải chi tiết**

Xét $f(x)=x^2-3$ liên tục trên $[0,3]$ vì là đa thức. Tính:

$$
f(0)=-3<0,\qquad f(3)=6>0.
$$

Do $f(0)f(3)<0$, theo định lí giá trị trung gian tồn tại $c\in(0,3)$ sao cho $f(c)=0$.


### Bài D20.13 · Thông hiểu

Chứng minh phương trình $x^2-4=0$ có ít nhất một nghiệm trên khoảng $(0,4)$ bằng định lí liên tục.


**Lời giải chi tiết**

Xét $f(x)=x^2-4$ liên tục trên $[0,4]$ vì là đa thức. Tính:

$$
f(0)=-4<0,\qquad f(4)=12>0.
$$

Do $f(0)f(4)<0$, theo định lí giá trị trung gian tồn tại $c\in(0,4)$ sao cho $f(c)=0$.


### Bài D20.14 · Thông hiểu

Chứng minh phương trình $x^2-5=0$ có ít nhất một nghiệm trên khoảng $(0,5)$ bằng định lí liên tục.


**Lời giải chi tiết**

Xét $f(x)=x^2-5$ liên tục trên $[0,5]$ vì là đa thức. Tính:

$$
f(0)=-5<0,\qquad f(5)=20>0.
$$

Do $f(0)f(5)<0$, theo định lí giá trị trung gian tồn tại $c\in(0,5)$ sao cho $f(c)=0$.


### Bài D20.15 · Vận dụng

Chứng minh phương trình $x^2-6=0$ có ít nhất một nghiệm trên khoảng $(0,6)$ bằng định lí liên tục.


**Lời giải chi tiết**

Xét $f(x)=x^2-6$ liên tục trên $[0,6]$ vì là đa thức. Tính:

$$
f(0)=-6<0,\qquad f(6)=30>0.
$$

Do $f(0)f(6)<0$, theo định lí giá trị trung gian tồn tại $c\in(0,6)$ sao cho $f(c)=0$.


### Bài D20.16 · Vận dụng

Dùng định lí giá trị trung gian để chứng minh phương trình $x^3-8=0$ có nghiệm trong $(1,3)$.


**Lời giải chi tiết**

Đặt $f(x)=x^3-8$ là đa thức liên tục trên $[1,3]$. Giá trị ở hai đầu:

$$
f(1)=1^3-8=-7<0,\qquad f(3)=3^3-8=19>0.
$$

Theo định lí giá trị trung gian, có $c\in(1,3)$ sao cho $f(c)=0$. (Thật vậy, nghiệm cụ thể là $c=2$.)


### Bài D20.17 · Vận dụng

Dùng định lí giá trị trung gian để chứng minh phương trình $x^3-27=0$ có nghiệm trong $(2,4)$.


**Lời giải chi tiết**

Đặt $f(x)=x^3-27$ là đa thức liên tục trên $[2,4]$. Giá trị ở hai đầu:

$$
f(2)=2^3-27=-19<0,\qquad f(4)=4^3-27=37>0.
$$

Theo định lí giá trị trung gian, có $c\in(2,4)$ sao cho $f(c)=0$. (Thật vậy, nghiệm cụ thể là $c=3$.)


### Bài D20.18 · Vận dụng

Dùng định lí giá trị trung gian để chứng minh phương trình $x^3-64=0$ có nghiệm trong $(3,5)$.


**Lời giải chi tiết**

Đặt $f(x)=x^3-64$ là đa thức liên tục trên $[3,5]$. Giá trị ở hai đầu:

$$
f(3)=3^3-64=-37<0,\qquad f(5)=5^3-64=61>0.
$$

Theo định lí giá trị trung gian, có $c\in(3,5)$ sao cho $f(c)=0$. (Thật vậy, nghiệm cụ thể là $c=4$.)


### Bài D20.19 · Vận dụng

Dùng định lí giá trị trung gian để chứng minh phương trình $x^3-125=0$ có nghiệm trong $(4,6)$.


**Lời giải chi tiết**

Đặt $f(x)=x^3-125$ là đa thức liên tục trên $[4,6]$. Giá trị ở hai đầu:

$$
f(4)=4^3-125=-61<0,\qquad f(6)=6^3-125=91>0.
$$

Theo định lí giá trị trung gian, có $c\in(4,6)$ sao cho $f(c)=0$. (Thật vậy, nghiệm cụ thể là $c=5$.)


### Bài D20.20 · Vận dụng

Dùng định lí giá trị trung gian để chứng minh phương trình $x^3-216=0$ có nghiệm trong $(5,7)$.


**Lời giải chi tiết**

Đặt $f(x)=x^3-216$ là đa thức liên tục trên $[5,7]$. Giá trị ở hai đầu:

$$
f(5)=5^3-216=-91<0,\qquad f(7)=7^3-216=127>0.
$$

Theo định lí giá trị trung gian, có $c\in(5,7)$ sao cho $f(c)=0$. (Thật vậy, nghiệm cụ thể là $c=6$.)


---


## Gợi ý phân phối dạy học

- **Bài 01–07:** kiểm tra ngay sau khi học lý thuyết; tập trung nhận dạng và phép biến đổi cơ bản.
- **Bài 08–14:** luyện thành thạo trên lớp và ở nhà; học sinh cần trình bày lời giải có giải thích.
- **Bài 15–20:** củng cố và luyện tập tổng hợp, có thể dùng cho bài kiểm tra.

> [!warning] Những lưu ý bắt buộc
> - Dạng $0/0$, $\infty/\infty$, $\infty-\infty$ **chưa phải đáp án**.
> - Nếu hai giới hạn một bên khác nhau thì giới hạn hai phía không tồn tại.
> - Khi $x\to-\infty$, phải dùng $\sqrt{x^2}=|x|=-x$.
> - Tổng cấp số nhân vô hạn chỉ có công thức $S=u_1/(1-q)$ khi $|q|<1$.
> - Tính liên tục tại $x=a$ đòi hỏi cả $f(a)$ tồn tại và $\lim_{x\to a}f(x)=f(a)$.
