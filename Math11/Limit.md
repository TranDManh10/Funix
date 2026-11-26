---
title: "CHUYÊN ĐỀ GIỚI HẠN – TOÁN 11"
aliases:
  - "Giới hạn Toán 11"
  - "Giới hạn của dãy số và hàm số"
tags:
  - toan-11
  - gioi-han
  - day-so
  - ham-so-lien-tuc
---

# CHUYÊN ĐỀ GIỚI HẠN – TOÁN 11

**Tài liệu học tập từ cơ bản đến vận dụng · Dành cho học sinh trung bình – khá**  
**Theo định hướng sách giáo khoa Toán 11 – Kết nối tri thức với cuộc sống**

> [!abstract] Mục tiêu học tập
> Sau chuyên đề này, học sinh cần:
> 1. Hiểu **giới hạn là xu hướng tiến gần**, không phải chỉ là phép thay số.
> 2. Tính được giới hạn của **dãy số** và **hàm số** bằng các quy tắc cơ bản.
> 3. Nhận diện và khử được các **dạng vô định thường gặp** trong chương trình lớp 11.
> 4. Phân biệt **giới hạn bên trái, bên phải**, giới hạn hữu hạn và giới hạn vô cực.
> 5. Hiểu bản chất của **tính liên tục** và vận dụng trong các bài toán có tham số.

## Hướng dẫn sử dụng tài liệu

- Các mục **Hiểu bản chất** giúp học sinh hình dung trước khi học công thức.
- Các mục **Quy tắc** là kiến thức phải nhớ.
- Các **ví dụ mẫu** trình bày đủ bước, thích hợp cho học sinh tự học.
- Các mục **Lỗi thường gặp** dùng để kiểm tra khả năng hiểu, tránh giải máy móc.
- Phần **Tự luyện** nên làm trước khi xem đáp số ở cuối tài liệu.

## Lộ trình kiến thức

| Phần | Nội dung | Câu hỏi trọng tâm |
|---|---|---|
| I | Bản chất của giới hạn | “Tiến gần” khác “bằng” như thế nào? |
| II | Giới hạn của dãy số | Khi $n$ càng lớn, $u_n$ đi về đâu? |
| III | Phương pháp tính giới hạn dãy số | Chọn chia bậc, lũy thừa trội hay liên hợp? |
| IV | Tổng cấp số nhân lùi vô hạn | Cộng vô hạn số hạng có thể ra số hữu hạn không? |
| V | Giới hạn của hàm số | Khi $x$ tiến gần một giá trị, $f(x)$ thay đổi ra sao? |
| VI | Phương pháp tính giới hạn hàm số | Khi thay số bị $0/0$, cần xử lí thế nào? |
| VII | Hàm số liên tục | Khi nào đồ thị “không bị đứt” tại một điểm? |
| VIII–X | Nhận dạng, lỗi sai, bài tập và dạy học | Làm sao chọn đúng phương pháp và tự kiểm tra? |

---

# PHẦN I. BẢN CHẤT CỦA GIỚI HẠN

## 1. Giới hạn là gì?

Hãy xét các số sau:

$$
0{,}9;\quad 0{,}99;\quad 0{,}999;\quad 0{,}9999;\quad \ldots
$$

Các số này **chưa bằng $1$**, nhưng ngày càng **gần $1$**. Ta nói giá trị của chúng *tiến tới* $1$.

Tương tự, xét dãy số:

$$
u_n=\frac{1}{n},\qquad n=1,2,3,\ldots
$$

| $n$ | $1$ | $2$ | $10$ | $100$ | $1000$ |
|---:|---:|---:|---:|---:|---:|
| $u_n=1/n$ | $1$ | $0{,}5$ | $0{,}1$ | $0{,}01$ | $0{,}001$ |

Khi $n$ càng lớn, $u_n$ càng gần $0$. Kí hiệu:

$$
\boxed{\lim_{n\to+\infty}\frac{1}{n}=0.}
$$

Đọc là: “Giới hạn của $1/n$ khi $n$ tiến tới dương vô cực bằng $0$.”

> [!important] Ý nghĩa cốt lõi
> Giới hạn trả lời câu hỏi **“giá trị đang tiến gần đến đâu?”**, chứ không nhất thiết hỏi **“giá trị ngay tại điểm đó bằng bao nhiêu?”**.

## 2. Ba trường hợp cần phân biệt

**Trường hợp 1 – Tiến tới một số hữu hạn.**

$$
\frac1n\to0,\qquad 2+\frac1n\to2.
$$

**Trường hợp 2 – Tăng hoặc giảm không bị chặn.**

$$
n^2\to+\infty,\qquad -n\to-\infty.
$$

**Trường hợp 3 – Không có một xu hướng giới hạn duy nhất.**

$$
u_n=(-1)^n=-1,1,-1,1,\ldots
$$

Dãy liên tục đổi giữa $-1$ và $1$, nên **không có giới hạn** khi $n\to+\infty$.

> [!warning] Đừng nhầm
> $+\infty$ và $-\infty$ **không phải các số thực** để thay vào biểu thức. Chúng mô tả xu hướng tăng hoặc giảm không bị chặn.

## 3. Bốn kí hiệu phải hiểu đúng

| Kí hiệu | Ý nghĩa |
|---|---|
| $n\to+\infty$ | Chỉ số $n$ là số nguyên dương và tăng mãi. |
| $x\to a$ | $x$ tiến gần $a$ từ cả hai phía (nếu xét được cả hai). |
| $x\to a^-$ | $x$ tiến gần $a$ từ phía **nhỏ hơn $a$**. |
| $x\to a^+$ | $x$ tiến gần $a$ từ phía **lớn hơn $a$**. |

Ở kí hiệu $x\to a^+$, dấu $+$ **không có nghĩa là $x$ dương**. Nó chỉ nói rằng $x>a$.

---

# PHẦN II. GIỚI HẠN CỦA DÃY SỐ

## 1. Khái niệm giới hạn hữu hạn

### 1.1. Dãy số có giới hạn bằng $0$

Dãy $(u_n)$ có giới hạn bằng $0$ nếu, khi $n$ đủ lớn, **khoảng cách từ $u_n$ đến $0$ nhỏ hơn bất cứ độ chính xác dương nào ta chọn**.

$$
\boxed{\lim_{n\to+\infty}u_n=0.}
$$

Ví dụ:

$$
\lim_{n\to+\infty}\frac{3}{n}=0,\qquad
\lim_{n\to+\infty}\frac{-5}{n^2}=0.
$$

> [!note] Vì sao dùng dấu giá trị tuyệt đối?
> Khoảng cách từ $u_n$ đến $0$ là $|u_n|$. Một số âm rất lớn về độ lớn, ví dụ $-100$, tuy **nhỏ hơn** $0{,}01$ nhưng lại **không gần** $0$. Vì vậy phải xét $|u_n|$, không chỉ xét $u_n<0{,}01$.

**Diễn đạt chính xác (để hiểu sâu hơn, không bắt buộc học thuộc):** Với mọi $\varepsilon>0$, tồn tại số nguyên $N$ sao cho

$$
n\ge N\quad\Longrightarrow\quad |u_n|<\varepsilon.
$$

Ở đây $\varepsilon$ là độ sai lệch dương nhỏ tùy ý.

### 1.2. Dãy số có giới hạn bằng số thực $a$

Dãy $(u_n)$ có giới hạn là $a$ nếu **độ chênh lệch** $u_n-a$ tiến về $0$:

$$
\boxed{\lim_{n\to+\infty}u_n=a
\iff
\lim_{n\to+\infty}(u_n-a)=0.}
$$

**Ví dụ 1.** Tìm giới hạn của $u_n=5+\dfrac2n$.

*Giải.* Ta có:

$$
u_n-5=\frac2n\to0.
$$

Do đó:

$$
\boxed{\lim_{n\to+\infty}\left(5+\frac2n\right)=5.}
$$

**Hiểu bản chất:** phần $2/n$ ngày càng nhỏ; dãy số chỉ còn “tiến sát” số $5$.

## 2. Các giới hạn cơ bản phải nhớ

Với $k$ là số nguyên dương và $c$ là hằng số thực:

$$
\boxed{\lim_{n\to+\infty}c=c,\qquad
\lim_{n\to+\infty}\frac1{n^k}=0,\qquad
\lim_{n\to+\infty}n^k=+\infty.}
$$

Với cấp số nhân:

$$
\boxed{\lim_{n\to+\infty}q^n=0\quad\text{khi }|q|<1.}
$$

Nếu $q>1$ thì $q^n\to+\infty$.

| Dãy số | Xu hướng | Kết luận |
|---|---|---|
| $(1/3)^n$ | Nhỏ dần về $0$ | Giới hạn $0$ |
| $(-1/2)^n$ | Đổi dấu nhưng độ lớn nhỏ về $0$ | Giới hạn $0$ |
| $1^n$ | Luôn bằng $1$ | Giới hạn $1$ |
| $2^n$ | Tăng không bị chặn | Giới hạn $+\infty$ |
| $(-1)^n$ | Luân phiên $-1,1$ | Không có giới hạn |
| $(-2)^n$ | Đổi dấu, độ lớn tăng | Không có giới hạn |

> [!tip] Mẹo ghi nhớ
> Đối với $q^n$, điều cần xét là **trị tuyệt đối $|q|$** khi muốn kết luận về giới hạn $0$. Chỉ viết “$q<1$ thì $q^n\to0$” là sai, vì $q=-2<1$ nhưng $(-2)^n$ không tiến về $0$.

## 3. Các phép toán với giới hạn hữu hạn

Giả sử:

$$
\lim_{n\to+\infty}u_n=a,\qquad
\lim_{n\to+\infty}v_n=b.
$$

Khi đó:

$$
\begin{aligned}
\lim(u_n+v_n)&=a+b,\\
\lim(u_n-v_n)&=a-b,\\
\lim(u_nv_n)&=ab,\\
\lim\frac{u_n}{v_n}&=\frac ab\quad(b\ne0).
\end{aligned}
$$

Nếu $u_n\ge0$ kể từ một số hạng nào đó và $u_n\to a$, thì $a\ge0$ và:

$$
\boxed{\lim\sqrt{u_n}=\sqrt a.}
$$

**Ví dụ 2.**

$$
\begin{aligned}
\lim_{n\to+\infty}\left(3+\frac2n-\frac5{n^2}\right)
&=3+2\cdot0-5\cdot0\\
&=\boxed{3}.
\end{aligned}
$$

**Ví dụ 3.**

$$
\lim_{n\to+\infty}\sqrt{4+\frac3n}
=\sqrt{4+0}=\boxed2.
$$

> [!warning] Điều kiện quan trọng
> Quy tắc **chia giới hạn** chỉ dùng trực tiếp khi giới hạn mẫu khác $0$. Khi mẫu tiến về $0$, phải xét lại dạng biểu thức, không được thay máy móc thành “chia cho $0$”.

## 4. Định lí kẹp – khi không tính trực tiếp được

Nếu kể từ một số hạng nào đó:

$$
a_n\le u_n\le b_n
$$

và

$$
\lim a_n=\lim b_n=L,
$$

thì:

$$
\boxed{\lim u_n=L.}
$$

**Ý tưởng:** Nếu một dãy số luôn nằm giữa **hai dãy cùng tiến đến $L$**, nó cũng phải tiến đến $L$.

**Ví dụ 4.** Tính:

$$
\lim_{n\to+\infty}\frac{\sin n}{n}.
$$

Vì $-1\le\sin n\le1$ và $n>0$, ta được:

$$
-\frac1n\le\frac{\sin n}{n}\le\frac1n.
$$

Hai dãy ở hai đầu đều tiến về $0$; suy ra:

$$
\boxed{\lim_{n\to+\infty}\frac{\sin n}{n}=0.}
$$

> [!important] Cách dùng nhanh
> Nếu $|u_n|\le v_n$ với $v_n\ge0$ và $v_n\to0$, thì $u_n\to0$. Đây là hệ quả của định lí kẹp, rất hữu ích với $(-1)^n$, $\sin n$, $\cos n$.

## 5. Giới hạn vô cực của dãy số

### 5.1. Dãy tiến tới $+\infty$

Ta viết:

$$
\lim_{n\to+\infty}u_n=+\infty
$$

nếu $u_n$ có thể lớn hơn **bất cứ số dương lớn đến đâu** khi $n$ đủ lớn.

Ví dụ:

$$
\lim_{n\to+\infty}(3n+1)=+\infty.
$$

### 5.2. Dãy tiến tới $-\infty$

Ta viết:

$$
\lim_{n\to+\infty}u_n=-\infty
$$

nếu $u_n$ giảm xuống thấp hơn mọi mức âm cho trước khi $n$ đủ lớn.

Ví dụ:

$$
\lim_{n\to+\infty}(-2n^2+5)=-\infty.
$$

### 5.3. Một số quy tắc dấu dễ nhớ

- Một số dương cố định nhân với $+\infty$ cho xu hướng $+\infty$.
- Một số âm cố định nhân với $+\infty$ cho xu hướng $-\infty$.
- Một số hữu hạn chia cho đại lượng có độ lớn tiến đến $+\infty$ hoặc $-\infty$ thì tiến đến $0$.
- Nếu tử tiến về số khác $0$, mẫu tiến về $0$, **phải xét dấu của mẫu** trước khi kết luận $+\infty$ hay $-\infty$.

---

# PHẦN III. CÁCH TÍNH GIỚI HẠN DÃY SỐ

## Dạng 1. Phân thức chứa đa thức theo $n$

Xét:

$$
\lim_{n\to+\infty}\frac{P(n)}{Q(n)},
$$

trong đó $P,Q$ là đa thức. **Nguyên tắc:** Chia tử và mẫu cho lũy thừa $n$ cao nhất thích hợp, rồi dùng $1/n^k\to0$.

### Trường hợp 1: Tử và mẫu cùng bậc

**Ví dụ 5.**

$$
L=\lim_{n\to+\infty}\frac{3n^2+2n-1}{2n^2+5}.
$$

*Bước 1.* Nhận thấy bậc cao nhất của cả tử và mẫu đều là $2$.

*Bước 2.* Chia cả tử và mẫu cho $n^2$:

$$
L=\lim_{n\to+\infty}
\frac{3+\frac2n-\frac1{n^2}}{2+\frac5{n^2}}.
$$

*Bước 3.* Cho $n\to+\infty$:

$$
\boxed{L=\frac32.}
$$

**Kết luận:** Nếu cùng bậc, giới hạn là **tỉ số hai hệ số bậc cao nhất**.

### Trường hợp 2: Bậc tử nhỏ hơn bậc mẫu

**Ví dụ 6.**

$$
\lim_{n\to+\infty}\frac{2n+1}{n^2+3}
=\lim_{n\to+\infty}\frac{\frac2n+\frac1{n^2}}{1+\frac3{n^2}}
=\boxed0.
$$

**Bản chất:** Mẫu lớn nhanh hơn tử, nên tỉ số nhỏ dần về $0$.

### Trường hợp 3: Bậc tử lớn hơn bậc mẫu

**Ví dụ 7.**

$$
\begin{aligned}
\lim_{n\to+\infty}\frac{-2n^3+n}{n^2+1}
&=\lim_{n\to+\infty}n\frac{-2+\frac1{n^2}}{1+\frac1{n^2}}\\
&=\boxed{-\infty}.
\end{aligned}
$$

**Bản chất:** Tỉ số có độ lớn tăng không bị chặn; dấu phụ thuộc hệ số dẫn đầu.

| So sánh bậc | Kết quả điển hình |
|---|---|
| Bậc tử $<$ bậc mẫu | $0$ |
| Bậc tử $=$ bậc mẫu | Tỉ số hệ số dẫn đầu |
| Bậc tử $>$ bậc mẫu | $+\infty$ hoặc $-\infty$, xét dấu |

> [!warning] Điều kiện của bảng
> Bảng này áp dụng cho **tỉ số hai đa thức** khi $n\to+\infty$ (mẫu không đồng nhất bằng $0$); không tự động áp dụng cho mọi biểu thức có căn hoặc lũy thừa mũ $n$.

## Dạng 2. Dãy số chứa lũy thừa $a^n$

**Nguyên tắc:** Với tổng các lũy thừa dương như $2^n,3^n,5^n$, lũy thừa có **cơ số lớn hơn** phát triển nhanh hơn. Ta chia cho lũy thừa có cơ số lớn nhất.

**Ví dụ 8.**

$$
L=\lim_{n\to+\infty}\frac{2\cdot3^n+5^n}{4\cdot5^n-3^n}.
$$

Chia cả tử và mẫu cho $5^n$:

$$
\begin{aligned}
L&=\lim_{n\to+\infty}
\frac{2\left(\frac35\right)^n+1}{4-\left(\frac35\right)^n}\\
&=\frac{2\cdot0+1}{4-0}=\boxed{\frac14}.
\end{aligned}
$$

Vì $\left|\frac35\right|<1$ nên $\left(\frac35\right)^n\to0$.

**Ví dụ 9.**

$$
\lim_{n\to+\infty}\left(\frac{-2}{3}\right)^n=\boxed0
$$

vì $|-2/3|<1$, dù các số hạng có đổi dấu.

> [!tip] Nhận diện nhanh
> Khi nhìn thấy $2^n,3^n,4^n,\ldots$, hãy nghĩ **“chia cho lũy thừa trội”** trước khi nghĩ tới “so sánh bậc đa thức”.

## Dạng 3. Dãy số có căn thức

### 3.1. Đặt lũy thừa $n$ ra khỏi dấu căn

Vì $n>0$:

$$
\sqrt{n^2A_n}=n\sqrt{A_n}.
$$

**Ví dụ 10.**

$$
L=\lim_{n\to+\infty}\frac{\sqrt{4n^2+3n}}{n+1}.
$$

Chia tử và mẫu cho $n$:

$$
\begin{aligned}
L&=\lim_{n\to+\infty}\frac{n\sqrt{4+\frac3n}}{n\left(1+\frac1n\right)}\\
&=\lim_{n\to+\infty}\frac{\sqrt{4+\frac3n}}{1+\frac1n}
=\boxed2.
\end{aligned}
$$

### 3.2. Nhân với biểu thức liên hợp

Nhớ hằng đẳng thức:

$$
(a-b)(a+b)=a^2-b^2.
$$

Vì vậy:

$$
\boxed{\sqrt A-\sqrt B=\frac{A-B}{\sqrt A+\sqrt B}.}
$$

**Ví dụ 11.**

$$
L=\lim_{n\to+\infty}\left(\sqrt{n^2+3n}-n\right).
$$

Nếu nhìn riêng từng phần, ta thấy dạng $\infty-\infty$, **chưa thể kết luận**.

Nhân liên hợp:

$$
\begin{aligned}
\sqrt{n^2+3n}-n
&=\frac{(n^2+3n)-n^2}{\sqrt{n^2+3n}+n}\\
&=\frac{3n}{\sqrt{n^2+3n}+n}\\
&=\frac3{\sqrt{1+\frac3n}+1}.
\end{aligned}
$$

Do đó:

$$
\boxed{L=\frac3{1+1}=\frac32.}
$$

**Bản chất:** Nhân liên hợp giúp tạo phép trừ dưới căn thành dạng đại số dễ rút gọn.

> [!warning] Sai lầm về căn bậc hai
> $\sqrt{n^2}=|n|$, không phải luôn là $n$. Trong giới hạn dãy số có $n\to+\infty$ nên $n>0$ và $|n|=n$. Nhưng khi xét **hàm số với $x\to-\infty$**, phải dùng $\sqrt{x^2}=|x|=-x$.

## Dạng 4. Dãy số dao động nhưng biên độ nhỏ dần

**Ví dụ 12.**

$$
u_n=\frac{(-1)^n}{n}.
$$

Vì $-1\le(-1)^n\le1$ nên:

$$
-\frac1n\le\frac{(-1)^n}{n}\le\frac1n.
$$

Suy ra:

$$
\boxed{\lim_{n\to+\infty}\frac{(-1)^n}{n}=0.}
$$

**Phân biệt:** $(-1)^n$ không có giới hạn, nhưng $\dfrac{(-1)^n}{n}$ có giới hạn bằng $0$ vì **biên độ dao động co về $0$**.

---

# PHẦN IV. TỔNG CỦA CẤP SỐ NHÂN LÙI VÔ HẠN

## 1. Vì sao cộng vô hạn số hạng vẫn có thể ra một số hữu hạn?

Xét:

$$
1+\frac12+\frac14+\frac18+\cdots
$$

Các tổng từng phần là:

$$
1;\quad 1{,}5;\quad 1{,}75;\quad 1{,}875;\quad\ldots
$$

Các tổng này tăng dần, nhưng tiến ngày càng gần $2$.

Ta viết:

$$
1+\frac12+\frac14+\frac18+\cdots=2.
$$

Dấu bằng ở đây có nghĩa: **giới hạn của tổng $n$ số hạng đầu bằng $2$**.

## 2. Công thức

Một cấp số nhân có số hạng đầu $u_1$, công bội $q$ và $|q|<1$ là **cấp số nhân lùi vô hạn**. Tổng của nó:

$$
\boxed{S=u_1+u_1q+u_1q^2+\cdots=\frac{u_1}{1-q},\qquad |q|<1.}
$$

### Vì sao có công thức này?

Tổng $n$ số hạng đầu là:

$$
S_n=\frac{u_1(1-q^n)}{1-q}\quad(q\ne1).
$$

Vì $|q|<1$ nên $q^n\to0$. Do đó:

$$
\lim_{n\to+\infty}S_n=\frac{u_1(1-0)}{1-q}=\frac{u_1}{1-q}.
$$

## 3. Ví dụ minh họa

**Ví dụ 13.** Tính:

$$
S=3+1+\frac13+\frac19+\cdots.
$$

Ta có $u_1=3$, $q=1/3$.

$$
\boxed{S=\frac3{1-\frac13}=\frac92.}
$$

**Ví dụ 14.** Đổi số thập phân vô hạn tuần hoàn $0{,}272727\ldots$ thành phân số.

Ta tách thành:

$$
0{,}272727\ldots
=\frac{27}{100}+\frac{27}{10^4}+\frac{27}{10^6}+\cdots.
$$

Đây là cấp số nhân với $u_1=27/100$ và $q=1/100$. Vì thế:

$$
\boxed{0{,}272727\ldots
=\frac{\frac{27}{100}}{1-\frac1{100}}
=\frac{27}{99}=\frac3{11}.}
$$

> [!warning] Điều kiện bắt buộc
> **Phải có $|q|<1$** mới dùng được công thức tổng cấp số nhân lùi vô hạn. Ví dụ $1+2+4+8+\cdots$ không có tổng hữu hạn.

---
# PHẦN V. GIỚI HẠN CỦA HÀM SỐ

## 1. Bản chất của giới hạn hàm số tại một điểm

Xét hàm số:

$$
f(x)=\frac{x^2-1}{x-1},\qquad x\ne1.
$$

Với $x\ne1$, ta rút gọn:

$$
f(x)=\frac{(x-1)(x+1)}{x-1}=x+1.
$$

Ta có bảng giá trị:

| $x$ | $0{,}9$ | $0{,}99$ | $0{,}999$ | $1{,}001$ | $1{,}01$ | $1{,}1$ |
|---:|---:|---:|---:|---:|---:|---:|
| $f(x)$ | $1{,}9$ | $1{,}99$ | $1{,}999$ | $2{,}001$ | $2{,}01$ | $2{,}1$ |

Khi $x$ tiến gần $1$ từ hai phía, $f(x)$ tiến gần $2$. Vì vậy:

$$
\boxed{\lim_{x\to1}\frac{x^2-1}{x-1}=2.}
$$

**Điểm cần hiểu:** Hàm số này **không xác định tại $x=1$**, nhưng **vẫn có giới hạn tại $x=1$**.

### 1.1. Định nghĩa trực quan

Ta viết:

$$
\lim_{x\to a}f(x)=L
$$

nếu **khi $x$ càng gần $a$ (và $x\ne a$), giá trị $f(x)$ càng gần $L$**.

Định nghĩa chính xác trong sách giáo khoa được diễn đạt bằng dãy số: Với mọi dãy $x_n$ thuộc miền xét, $x_n\ne a$ và $x_n\to a$, ta đều có $f(x_n)\to L$.

### 1.2. Ba sự thật quan trọng

1. Để xét $\lim_{x\to a}f(x)$, ta quan tâm **giá trị $f(x)$ ở gần $a$**, không bắt buộc biết $f(a)$.
2. Hàm số **không xác định tại $a$** vẫn có thể có giới hạn tại $a$.
3. Muốn giới hạn hai phía tồn tại, xu hướng từ bên trái và bên phải **phải trùng nhau**.

> [!important] Phân biệt hai câu hỏi
> - $f(a)$: “Giá trị hàm số **ngay tại** $x=a$ là bao nhiêu?”
> - $\lim_{x\to a}f(x)$: “Khi $x$ **tiến sát** $a$, hàm số tiến sát giá trị nào?”
>
> Hai kết quả **có thể bằng nhau hoặc khác nhau**.

## 2. Giới hạn hữu hạn của hàm số tại một điểm

Giả sử:

$$
\lim_{x\to a}f(x)=L,\qquad
\lim_{x\to a}g(x)=M.
$$

Ta có các quy tắc:

$$
\begin{aligned}
\lim_{x\to a}[f(x)+g(x)]&=L+M,\\
\lim_{x\to a}[f(x)-g(x)]&=L-M,\\
\lim_{x\to a}[f(x)g(x)]&=LM,\\
\lim_{x\to a}\frac{f(x)}{g(x)}&=\frac LM\quad(M\ne0).
\end{aligned}
$$

Đặc biệt:

$$
\lim_{x\to a}x=a,\qquad \lim_{x\to a}c=c.
$$

### Khi nào được thay trực tiếp $x=a$?

- Với **đa thức**: thay trực tiếp.
- Với **phân thức**: thay trực tiếp nếu mẫu tại $a$ **khác $0$**.
- Với **căn thức**: thay trực tiếp nếu biểu thức có nghĩa và việc áp dụng quy tắc giới hạn là hợp lệ.

**Ví dụ 15.**

$$
\lim_{x\to2}(x^2+3x-1)=2^2+3\cdot2-1=\boxed9.
$$

**Ví dụ 16.**

$$
\lim_{x\to1}\frac{x+2}{x^2+1}=\frac{1+2}{1+1}=\boxed{\frac32}.
$$

> [!tip] Quy trình đầu tiên
> 1. **Thử thay giá trị $x=a$ vào biểu thức.**
> 2. Nếu được một số thực hợp lệ: tính ngay.
> 3. Nếu gặp $0/0$, $\infty/\infty$, $\infty-\infty$, ...: **đó chưa phải kết quả**; phải biến đổi.
> 4. Nếu mẫu tiến tới $0$ nhưng tử tiến tới số khác $0$: xét **dấu** và giới hạn vô cực.

## 3. Giới hạn một bên

### 3.1. Giới hạn bên trái

Kí hiệu:

$$
\boxed{\lim_{x\to a^-}f(x)=L.}
$$

Ta chỉ xét các giá trị $x<a$ và cho $x$ tiến gần $a$.

Ví dụ: $x\to2^-$ có thể đi qua $1{,}9;\ 1{,}99;\ 1{,}999;\ldots$

### 3.2. Giới hạn bên phải

Kí hiệu:

$$
\boxed{\lim_{x\to a^+}f(x)=L.}
$$

Ta chỉ xét các giá trị $x>a$ và cho $x$ tiến gần $a$.

Ví dụ: $x\to2^+$ có thể đi qua $2{,}1;\ 2{,}01;\ 2{,}001;\ldots$

### 3.3. Điều kiện để giới hạn hai phía tồn tại

$$
\boxed{\lim_{x\to a}f(x)=L
\iff
\lim_{x\to a^-}f(x)=\lim_{x\to a^+}f(x)=L.}
$$

Đây là **định lí rất quan trọng** trong bài tập hàm số cho theo từng khoảng.

**Ví dụ 17.** Cho:

$$
f(x)=
\begin{cases}
2x+1,&x<1,\\
x+4,&x\ge1.
\end{cases}
$$

Tính giới hạn tại $x=1$.

*Bước 1. Xét bên trái*, $x<1$:

$$
\lim_{x\to1^-}f(x)=\lim_{x\to1^-}(2x+1)=3.
$$

*Bước 2. Xét bên phải*, $x>1$:

$$
\lim_{x\to1^+}f(x)=\lim_{x\to1^+}(x+4)=5.
$$

*Bước 3. So sánh:* $3\ne5$ nên:

$$
\boxed{\lim_{x\to1}f(x)\text{ không tồn tại}.}
$$

> [!warning] Lỗi học sinh hay mắc
> Ở bài trên, $f(1)=5$, nhưng điều đó **không có nghĩa** giới hạn tại $1$ bằng $5$; giới hạn bên trái vẫn là $3$.

### 3.4. Khi nào chỉ có thể xét một bên?

Ví dụ $f(x)=\sqrt{x}$ chỉ xác định khi $x\ge0$. Khi $x\to0$ trong miền xác định, chỉ có thể tiến từ bên phải. Ta viết:

$$
\lim_{x\to0^+}\sqrt{x}=0.
$$

Không được tự ý xét $\lim_{x\to0^-}\sqrt{x}$ trong tập số thực.

## 4. Giới hạn tại $+\infty$ và $-\infty$

### 4.1. Ý nghĩa

- $x\to+\infty$: xét $x$ ngày càng lớn về phía dương.
- $x\to-\infty$: xét $x$ ngày càng lớn về **độ lớn** nhưng mang dấu âm.

Ví dụ:

$$
\lim_{x\to+\infty}\frac1x=0,\qquad
\lim_{x\to-\infty}\frac1x=0.
$$

Dù $1/x$ tiến đến $0$ từ hai phía khác nhau, **giới hạn hữu hạn** đều là $0$.

### 4.2. Một số kết quả cơ bản

Với $k$ nguyên dương:

$$
\lim_{x\to\pm\infty}\frac1{x^k}=0.
$$

$$
\lim_{x\to+\infty}x^k=+\infty.
$$

Khi $x\to-\infty$:

$$
\lim_{x\to-\infty}x^k=
\begin{cases}
+\infty,&k\text{ chẵn},\\
-\infty,&k\text{ lẻ}.
\end{cases}
$$

**Ví dụ 18.**

$$
\lim_{x\to-\infty}\frac{2x^2+1}{x^2-3}
=\lim_{x\to-\infty}\frac{2+\frac1{x^2}}{1-\frac3{x^2}}
=\boxed2.
$$

**Ví dụ 19.**

$$
\lim_{x\to-\infty}\frac{x^3+2x}{x^2+1}
=\lim_{x\to-\infty}x\frac{1+\frac2{x^2}}{1+\frac1{x^2}}
=\boxed{-\infty}.
$$

### 4.3. Căn thức khi $x\to-\infty$

**Ví dụ 20.**

$$
L=\lim_{x\to-\infty}\frac{\sqrt{x^2+1}}{x}.
$$

Vì $x<0$ khi tiến về $-\infty$:

$$
\sqrt{x^2+1}=|x|\sqrt{1+\frac1{x^2}}=-x\sqrt{1+\frac1{x^2}}.
$$

Nên:

$$
L=\lim_{x\to-\infty}\left(-\sqrt{1+\frac1{x^2}}\right)=\boxed{-1}.
$$

> [!important] Nhớ dấu của căn
> $$\sqrt{x^2}=|x|=\begin{cases}x,&x\ge0,\\-x,&x<0.\end{cases}$$
>
> Đây là nguyên nhân khiến giới hạn với $x\to+\infty$ và $x\to-\infty$ có thể khác nhau.

## 5. Giới hạn vô cực của hàm số tại một điểm

Xét:

$$
f(x)=\frac1{x-2}.
$$

- Nếu $x\to2^+$: $x-2>0$ và rất nhỏ, nên $1/(x-2)\to+\infty$.
- Nếu $x\to2^-$: $x-2<0$ và rất nhỏ, nên $1/(x-2)\to-\infty$.

Vì vậy:

$$
\boxed{\lim_{x\to2^+}\frac1{x-2}=+\infty,\qquad
\lim_{x\to2^-}\frac1{x-2}=-\infty.}
$$

Hai giới hạn một bên khác nhau nên giới hạn hai phía **không tồn tại** (kể cả theo nghĩa giới hạn vô cực hai phía).

### 5.1. Vì sao số “gần $0$” có thể làm phân thức rất lớn?

$$
\frac1{0{,}1}=10,\qquad
\frac1{0{,}01}=100,\qquad
\frac1{0{,}001}=1000.
$$

Mẫu **dương và rất nhỏ** thì thương **dương và rất lớn**. Nếu mẫu **âm và rất nhỏ** thì thương **âm và có độ lớn rất lớn**.

### 5.2. Bảng dấu dành cho tử tiến về $A\ne0$

Nếu $f(x)\to A\ne0$ và $g(x)\to0$ với dấu xác định khi $x$ tiến đến điểm đang xét:

| Dấu tử $A$ | Dấu mẫu $g(x)$ | Xu hướng $f(x)/g(x)$ |
|---|---|---|
| $+$ | $0^+$ | $+\infty$ |
| $+$ | $0^-$ | $-\infty$ |
| $-$ | $0^+$ | $-\infty$ |
| $-$ | $0^-$ | $+\infty$ |

Trong bảng, $0^+$ là **tiến về $0$ qua các giá trị dương**, còn $0^-$ là **tiến về $0$ qua các giá trị âm**.

**Ví dụ 21.**

$$
L=\lim_{x\to3^-}\frac{-2}{x-3}.
$$

Với $x<3$, $x-3<0$ và tiến về $0^-$; tử $-2<0$. Vì **âm chia âm là dương** và mẫu có độ lớn tiến về $0$, suy ra:

$$
\boxed{L=+\infty.}
$$

**Ví dụ 22.**

$$
\lim_{x\to1}\frac1{(x-1)^2}=\boxed{+\infty}.
$$

Vì $(x-1)^2>0$ khi $x\ne1$, đồng thời $(x-1)^2\to0$, nên cả **hai phía** đều tiến tới $+\infty$.

> [!tip] Cách xét dấu mẫu
> Nếu mẫu có nhân tử $(x-a)$, hãy xem $x$ đến từ **trái** hay **phải**. Nếu mẫu có nhân tử $(x-a)^2$, bình phương luôn không âm; cần kết hợp với các nhân tử khác để xác định dấu toàn mẫu.

## 6. Nguyên lí kẹp cho hàm số

Nếu khi $x$ ở gần $a$ (khác $a$), ta có:

$$
g(x)\le f(x)\le h(x)
$$

và

$$
\lim_{x\to a}g(x)=\lim_{x\to a}h(x)=L,
$$

thì:

$$
\boxed{\lim_{x\to a}f(x)=L.}
$$

**Ví dụ 23.**

$$
L=\lim_{x\to0}x^2\cos\frac1x.
$$

Vì $-1\le\cos(1/x)\le1$ với $x\ne0$, nhân với $x^2\ge0$:

$$
-x^2\le x^2\cos\frac1x\le x^2.
$$

Mà $-x^2\to0$ và $x^2\to0$, nên:

$$
\boxed{L=0.}
$$

**Bản chất:** Hàm $\cos(1/x)$ dao động, nhưng phần $x^2$ ép biên độ dao động co về $0$.

---

# PHẦN VI. PHƯƠNG PHÁP TÍNH GIỚI HẠN HÀM SỐ

## 1. Quy trình chung: nhìn dạng trước, chọn phép biến đổi sau

| Kết quả khi thay thử | Ý nghĩa | Việc cần làm |
|---|---|---|
| Một số thực hợp lệ | Có thể tính trực tiếp | Thay và kết luận |
| $0/0$ | Dạng vô định | Phân tích nhân tử, rút gọn, liên hợp |
| $\infty/\infty$ | Dạng vô định | Chia cho lũy thừa trội |
| $\infty-\infty$ | Dạng vô định | Quy đồng hoặc nhân liên hợp |
| $0\cdot\infty$ | Dạng vô định | Đưa về thương, rồi xử lí |
| $A/0$ với $A\ne0$ | Có thể là giới hạn vô cực hoặc không có giới hạn hai phía | Xét dấu mẫu, xét một bên |

> [!warning] Một dạng vô định **không phải là kết quả**
> Chẳng hạn, $0/0$ không có nghĩa giới hạn bằng $0$. Nó chỉ báo rằng **cách thay trực tiếp chưa cho đáp án**.

## Dạng 1. Thay trực tiếp

**Ví dụ 24.**

$$
\lim_{x\to-1}(3x^2-2x+5)
=3\cdot1-2\cdot(-1)+5=\boxed{10}.
$$

**Khi dùng:** Biểu thức liên tục tại điểm đang xét, và phép thay không tạo mẫu bằng $0$ hoặc căn không xác định.

## Dạng 2. Phân tích thành nhân tử để khử $0/0$

**Ví dụ 25.**

$$
L=\lim_{x\to3}\frac{x^2-9}{x-3}.
$$

**Bước 1.** Thay $x=3$ được $0/0$, là dạng vô định.

**Bước 2.** Phân tích tử:

$$
x^2-9=(x-3)(x+3).
$$

**Bước 3.** Với $x\ne3$, rút gọn:

$$
\frac{x^2-9}{x-3}=x+3.
$$

**Bước 4.** Lấy giới hạn:

$$
\boxed{L=\lim_{x\to3}(x+3)=6.}
$$

### Các hằng đẳng thức nên nhớ

$$
\begin{aligned}
a^2-b^2&=(a-b)(a+b),\\
a^3-b^3&=(a-b)(a^2+ab+b^2),\\
a^3+b^3&=(a+b)(a^2-ab+b^2).
\end{aligned}
$$

**Ví dụ 26.**

$$
\begin{aligned}
L&=\lim_{x\to1}\frac{x^3-1}{x-1}\\
&=\lim_{x\to1}\frac{(x-1)(x^2+x+1)}{x-1}\\
&=1+1+1=\boxed3.
\end{aligned}
$$

> [!important] Vì sao được rút gọn $(x-3)$?
> Trong bài giới hạn $x\to3$, ta xét **$x$ gần $3$ nhưng $x\ne3$**. Vì vậy phép chia cho $(x-3)$ là hợp lệ trên các điểm đang xét. Điều này **không làm cho hàm ban đầu tự nhiên có giá trị tại $x=3$**.

## Dạng 3. Nhân liên hợp để khử $0/0$

**Ví dụ 27.**

$$
L=\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}.
$$

Thay $x=4$ được $0/0$. Nhân cả tử và mẫu với $\sqrt{x}+2$:

$$
\begin{aligned}
\frac{\sqrt{x}-2}{x-4}
&=\frac{(\sqrt{x}-2)(\sqrt{x}+2)}{(x-4)(\sqrt{x}+2)}\\
&=\frac{x-4}{(x-4)(\sqrt{x}+2)}\\
&=\frac1{\sqrt{x}+2}\qquad(x\ne4).
\end{aligned}
$$

Suy ra:

$$
\boxed{L=\frac1{2+2}=\frac14.}
$$

**Ví dụ 28.**

$$
L=\lim_{x\to0}\frac{\sqrt{1+3x}-1}{x}.
$$

Nhân liên hợp:

$$
\begin{aligned}
L&=\lim_{x\to0}\frac{(1+3x)-1}{x(\sqrt{1+3x}+1)}\\
&=\lim_{x\to0}\frac{3}{\sqrt{1+3x}+1}
=\boxed{\frac32}.
\end{aligned}
$$

> [!tip] Dấu hiệu chọn liên hợp
> Thấy **hiệu hai căn**, hoặc **một căn trừ một số**, và thay trực tiếp được $0/0$ hay $\infty-\infty$ thì nên thử nhân liên hợp.

## Dạng 4. Quy đồng mẫu số

**Ví dụ 29.**

$$
L=\lim_{x\to0}\left(\frac1x-\frac1{x+x^2}\right).
$$

Không thể lấy giới hạn từng phân thức riêng rồi trừ. Quy đồng:

$$
\begin{aligned}
\frac1x-\frac1{x+x^2}
&=\frac{(x+x^2)-x}{x(x+x^2)}\\
&=\frac{x^2}{x^2(1+x)}\\
&=\frac1{1+x}\qquad(x\ne0,-1).
\end{aligned}
$$

Vậy:

$$
\boxed{L=1.}
$$

**Bản chất:** Hai biểu thức riêng có thể tăng vô cực nhưng hiệu của chúng vẫn tiến đến một số hữu hạn.

## Dạng 5. Phân thức khi $x\to\pm\infty$

**Ví dụ 30.**

$$
L=\lim_{x\to+\infty}\frac{4x^3-2x+1}{2x^3+x^2}.
$$

Chia cho $x^3$:

$$
\begin{aligned}
L&=\lim_{x\to+\infty}
\frac{4-\frac2{x^2}+\frac1{x^3}}{2+\frac1x}\\
&=\boxed2.
\end{aligned}
$$

**Ví dụ 31.**

$$
\begin{aligned}
\lim_{x\to-\infty}\frac{3x^2-1}{x+5}
&=\lim_{x\to-\infty}x\frac{3-\frac1{x^2}}{1+\frac5x}\\
&=\boxed{-\infty}.
\end{aligned}
$$

> [!warning] Không dùng máy móc “bậc tử lớn hơn”
> Bậc tử lớn hơn cho biết **độ lớn của thương có thể tăng không bị chặn**, nhưng phải xét dấu để chọn $+\infty$ hay $-\infty$, nhất là khi $x\to-\infty$.

## Dạng 6. Hiệu căn khi $x\to\infty$

**Ví dụ 32.**

$$
L=\lim_{x\to+\infty}\left(\sqrt{x^2+5x}-x\right).
$$

Nhân liên hợp:

$$
\begin{aligned}
L&=\lim_{x\to+\infty}
\frac{(x^2+5x)-x^2}{\sqrt{x^2+5x}+x}\\
&=\lim_{x\to+\infty}\frac5{\sqrt{1+\frac5x}+1}
=\boxed{\frac52}.
\end{aligned}
$$

Đây là một ví dụ điển hình mà việc nhìn $\sqrt{x^2+5x}\sim x$ rồi kết luận hiệu bằng $0$ là **sai**; hai đại lượng rất lớn có thể có hiệu tiến đến số khác $0$.

## Dạng 7. Xét dấu để tìm giới hạn vô cực

**Ví dụ 33.**

$$
L=\lim_{x\to-2^+}\frac{3}{(x+2)(x-1)}.
$$

Khi $x\to-2^+$:

- $x+2\to0^+$;
- $x-1\to-3<0$;
- mẫu $(x+2)(x-1)\to0^-$;
- tử $3>0$.

Suy ra:

$$
\boxed{L=-\infty.}
$$

**Cách kiểm tra:** Thử $x=-1{,}99$; khi đó mẫu âm và rất nhỏ, thương âm có độ lớn rất lớn.

## Dạng 8. Hàm số cho bởi nhiều công thức

**Ví dụ 34.** Cho:

$$
f(x)=
\begin{cases}
x^2+1,&x<2,\\
3x-1,&x\ge2.
\end{cases}
$$

Tính $\lim_{x\to2}f(x)$.

Bên trái:

$$
\lim_{x\to2^-}f(x)=2^2+1=5.
$$

Bên phải:

$$
\lim_{x\to2^+}f(x)=3\cdot2-1=5.
$$

Vì hai kết quả bằng nhau:

$$
\boxed{\lim_{x\to2}f(x)=5.}
$$

Ở bài này $f(2)=5$ nữa, nên hàm số còn **liên tục** tại $x=2$ (sẽ học ở phần tiếp theo).

---
# PHẦN VII. HÀM SỐ LIÊN TỤC – ỨNG DỤNG CỦA GIỚI HẠN

> [!note] Vai trò của phần này
> **Giới hạn** cho biết hàm số tiến đến đâu khi $x$ tiến gần một điểm. **Tính liên tục** kiểm tra xem xu hướng ấy có **khớp với giá trị thực sự của hàm tại điểm đó** hay không.

## 1. Thế nào là liên tục tại một điểm?

Hàm số $f$ được gọi là **liên tục tại $x=a$** nếu:

$$
\boxed{\lim_{x\to a}f(x)=f(a).}
$$

Câu này có ba ý:

1. $f(a)$ **phải xác định**.
2. $\lim_{x\to a}f(x)$ **phải tồn tại và hữu hạn**.
3. Hai giá trị đó **phải bằng nhau**.

Nếu thiếu một trong ba điều kiện thì hàm **không liên tục tại $a$**.

### Cách hiểu trực quan

Nếu đồ thị tiến sát điểm $(a,f(a))$ mà không bị “nhảy” hoặc “thủng” tại đó, ta hình dung hàm liên tục tại $a$. Đây là **hình ảnh trực quan**, không thay thế định nghĩa bằng giới hạn.

**Ví dụ 35.** Hàm $f(x)=x^2+1$ liên tục tại $x=2$ vì:

$$
f(2)=5,
$$

và:

$$
\lim_{x\to2}f(x)=\lim_{x\to2}(x^2+1)=5=f(2).
$$

**Ví dụ 36.** Cho:

$$
f(x)=
\begin{cases}
\dfrac{x^2-1}{x-1},&x\ne1,\\
5,&x=1.
\end{cases}
$$

Ta có $f(1)=5$, nhưng:

$$
\lim_{x\to1}f(x)=\lim_{x\to1}(x+1)=2.
$$

Vì $2\ne5$, hàm **gián đoạn tại $x=1$**.

**Điểm đặc biệt:** Giới hạn tồn tại, nhưng điểm được gán trên đồ thị nằm **sai vị trí** so với xu hướng của đồ thị khi tiến về $1$.

## 2. Quy trình ba bước xét tính liên tục

Cho hàm số $f(x)$, cần xét tại $x=a$.

**Bước 1.** Tính $f(a)$. Nếu $f(a)$ không xác định, kết luận hàm **không liên tục tại $a$**.

**Bước 2.** Tính $\lim_{x\to a}f(x)$, nếu cần thì tính riêng giới hạn bên trái và bên phải.

**Bước 3.** So sánh:

$$
\begin{cases}
\lim_{x\to a}f(x)=f(a)&\Rightarrow\text{liên tục tại }a,\\
\text{không thỏa}&\Rightarrow\text{không liên tục tại }a.
\end{cases}
$$

### Lưu ý với hàm xác định theo từng đoạn

Tại điểm nối $a$ (nằm giữa miền xác định), điều kiện đầy đủ là:

$$
\boxed{\lim_{x\to a^-}f(x)=\lim_{x\to a^+}f(x)=f(a).}
$$

Nếu chỉ có hai giới hạn một bên bằng nhau nhưng **khác** $f(a)$, hàm vẫn **không liên tục**.

## 3. Tìm tham số để hàm số liên tục

**Ví dụ 37.** Tìm $m$ để hàm số:

$$
f(x)=
\begin{cases}
\dfrac{x^2-4}{x-2},&x\ne2,\\
m,&x=2
\end{cases}
$$

liên tục tại $x=2$.

*Bước 1.* Theo định nghĩa, $f(2)=m$.

*Bước 2.* Tính giới hạn khi $x\to2$:

$$
\begin{aligned}
\lim_{x\to2}\frac{x^2-4}{x-2}
&=\lim_{x\to2}\frac{(x-2)(x+2)}{x-2}\\
&=\lim_{x\to2}(x+2)=4.
\end{aligned}
$$

*Bước 3.* Điều kiện liên tục:

$$
\lim_{x\to2}f(x)=f(2)\iff4=m.
$$

Vậy:

$$
\boxed{m=4.}
$$

**Ví dụ 38.** Tìm $m$ để:

$$
f(x)=
\begin{cases}
mx+1,&x<1,\\
x^2+2,&x\ge1
\end{cases}
$$

liên tục tại $x=1$.

*Bên trái:*

$$
\lim_{x\to1^-}f(x)=m+1.
$$

*Bên phải và tại điểm nối:*

$$
\lim_{x\to1^+}f(x)=1^2+2=3,\qquad f(1)=3.
$$

Để liên tục cần:

$$
m+1=3\iff\boxed{m=2}.
$$

> [!tip] Mẹo làm bài có tham số
> **Tìm giới hạn bên trái – bên phải – giá trị tại điểm nối**, rồi lập phương trình cho ba giá trị bằng nhau. Đây là cách chắc chắn, tránh bỏ quên $f(a)$.

## 4. Liên tục trên một khoảng, trên một đoạn

### 4.1. Liên tục trên khoảng $(a,b)$

Hàm số liên tục trên $(a,b)$ nếu liên tục tại **mọi điểm** trong khoảng ấy.

### 4.2. Liên tục trên đoạn $[a,b]$

Hàm số liên tục trên $[a,b]$ nếu:

- Liên tục tại mọi điểm $x\in(a,b)$.
- **Liên tục bên phải** tại đầu mút $a$:

$$
\lim_{x\to a^+}f(x)=f(a).
$$

- **Liên tục bên trái** tại đầu mút $b$:

$$
\lim_{x\to b^-}f(x)=f(b).
$$

> [!note] Vì sao tại đầu mút chỉ cần một phía?
> Trên đoạn $[a,b]$, không có các điểm của đoạn nằm bên trái $a$ hoặc bên phải $b$. Vì vậy chỉ xét phía **nằm trong đoạn**.

## 5. Những hàm số liên tục quen thuộc

- **Hàm đa thức** liên tục trên toàn bộ $\mathbb R$.
- **Hàm phân thức hữu tỉ** liên tục tại những điểm mẫu khác $0$.
- **Các hàm lượng giác** $\sin x,\cos x,\tan x,\cot x$ liên tục trên tập xác định tương ứng.
- **Hàm căn bậc hai** liên tục ở những điểm thuộc tập xác định, xét một phía thích hợp ở đầu mút miền xác định.

Nếu $f$ và $g$ đều liên tục tại $a$, thì tổng, hiệu, tích của chúng liên tục tại $a$; thương $f/g$ liên tục nếu $g(a)\ne0$.

**Ví dụ 39.** Xét hàm:

$$
f(x)=\frac{x+1}{x-3}.
$$

Mẫu bằng $0$ tại $x=3$, nên tập xác định:

$$
D=\mathbb R\setminus\{3\}.
$$

Hàm phân thức liên tục tại **mọi điểm trong $D$**. Tại $x=3$, hàm không xác định, nên không liên tục tại đó.

## 6. Định lí về sự tồn tại nghiệm

Nếu hàm số $f$ **liên tục trên đoạn $[a,b]$** và:

$$
f(a)\cdot f(b)<0,
$$

thì phương trình $f(x)=0$ có **ít nhất một nghiệm** trong khoảng $(a,b)$.

### Hiểu bản chất

Nếu một đường cong liên tục bắt đầu ở dưới trục hoành và kết thúc ở trên trục hoành (hoặc ngược lại), nó **phải cắt trục hoành ít nhất một lần**.

### Ví dụ 40. Chứng minh phương trình có nghiệm

Chứng minh phương trình:

$$
x^3+x-1=0
$$

có ít nhất một nghiệm trong $(0,1)$.

*Bước 1.* Đặt:

$$
f(x)=x^3+x-1.
$$

Đây là đa thức nên liên tục trên $[0,1]$.

*Bước 2.* Tính giá trị tại hai đầu đoạn:

$$
f(0)=-1<0,\qquad f(1)=1>0.
$$

Suy ra:

$$
f(0)f(1)=-1<0.
$$

*Bước 3.* Áp dụng định lí, tồn tại ít nhất một $c\in(0,1)$ sao cho $f(c)=0$.

**Kết luận:** Phương trình đã cho **có ít nhất một nghiệm** trong $(0,1)$.

> [!warning] Điều định lí không khẳng định
> Điều kiện $f(a)f(b)<0$ đảm bảo **ít nhất một nghiệm**, chứ **không tự động đảm bảo nghiệm duy nhất**. Muốn chứng minh duy nhất phải có thêm lập luận khác.

---

# PHẦN VIII. HỆ THỐNG HÓA – NHẬN DẠNG VÀ CHỌN PHƯƠNG PHÁP

## 1. Cây quyết định khi gặp một bài giới hạn

```text
BÀI TOÁN GIỚI HẠN
│
├── Dãy số: n → +∞
│   ├── 1/n^k, q^n, hằng số → công thức cơ bản
│   ├── P(n)/Q(n) → chia theo bậc lớn nhất
│   ├── a^n, b^n → chia cho lũy thừa trội
│   ├── Có căn → đưa n ra khỏi căn hoặc liên hợp
│   ├── Dao động bị chặn × 1/n → nguyên lí kẹp
│   └── Tổng cấp số nhân lùi → u₁/(1 − q), |q| < 1
│
└── Hàm số: x → a hoặc x → ±∞
    ├── x → a
    │   ├── Thay được số hợp lệ → thay trực tiếp
    │   ├── 0/0 → phân tích nhân tử / liên hợp / quy đồng
    │   ├── A/0, A ≠ 0 → xét dấu và xét một bên
    │   └── Hàm từng đoạn → giới hạn trái và phải
    └── x → ±∞
        ├── Phân thức đa thức → chia lũy thừa trội
        ├── Có căn → nhớ √(x²) = |x|
        └── Hiệu vô cực → liên hợp / quy đồng
```

## 2. Bảng so sánh quan trọng

| Vấn đề | Dãy số | Hàm số |
|---|---|---|
| Biến tiến tới đâu? | $n\to+\infty$ | $x\to a$, $x\to\pm\infty$ |
| Biến có nhận giá trị thực liên tục? | $n$ chỉ nhận số nguyên dương | $x$ biến thiên trên miền xác định |
| Có “giới hạn một bên” tại $a$? | Không theo cách xét ở lớp 11 | Có: $a^-$ và $a^+$ |
| Dạng thường gặp | Đa thức theo $n$, $q^n$, căn | $0/0$, $A/0$, hàm từng đoạn, $\infty/\infty$ |
| Ý nghĩa giới hạn hữu hạn | Số hạng càng về sau càng gần $L$ | Giá trị hàm càng gần $L$ khi $x$ tiến gần điểm xét |

## 3. Bốn nhầm lẫn nguy hiểm nhất

### Nhầm lẫn 1. “Thay được $0/0$, vậy giới hạn bằng $0$”

**Sai.** Với:

$$
\lim_{x\to1}\frac{x^2-1}{x-1}=2,
$$

thay trực tiếp là $0/0$, nhưng giới hạn thật sự bằng $2$.

### Nhầm lẫn 2. “Giới hạn bằng vô cực tức là không có giới hạn, nên không cần xét”

**Chưa đủ chính xác.** Trong chương trình lớp 11, ta cần phân biệt:

- **Không có giới hạn hữu hạn.**
- **Có giới hạn vô cực** $+\infty$ hoặc $-\infty$ theo nghĩa mở rộng.
- **Không có giới hạn** vì dao động hoặc do hai phía không cùng xu hướng.

Ví dụ $1/x^2\to+\infty$ khi $x\to0$, còn $1/x$ **không có giới hạn hai phía** tại $0$ do trái và phải trái dấu vô cực.

### Nhầm lẫn 3. “Giới hạn tồn tại thì hàm chắc chắn liên tục”

**Sai.** Hàm liên tục tại $a$ còn phải có **$f(a)$ xác định** và **$f(a)=\lim_{x\to a}f(x)$**.

### Nhầm lẫn 4. “Giới hạn của tích bằng tích giới hạn trong mọi tình huống”

**Sai nếu áp dụng tùy tiện cho các dạng vô định**. Các quy tắc số học giới hạn hữu hạn có điều kiện rõ ràng. Nếu một nhân tử tiến về $0$, nhân tử còn lại tiến về vô cực, không thể kết luận $0\cdot\infty=0$.

Ví dụ:

$$
x\cdot\frac1x=1\quad(x\ne0)
\Longrightarrow
\lim_{x\to0}x\cdot\frac1x=1.
$$

## 4. Các dạng vô định: học sinh cần hiểu “tại sao không đủ thông tin”

| Dạng | Cùng dạng nhưng cho kết quả khác nhau |
|---|---|
| $0/0$ | $\frac{x}{x}\to1$; $\frac{x^2}{x}\to0$ khi $x\to0$ |
| $\infty/\infty$ | $\frac{x}{x}\to1$; $\frac{x}{x^2}\to0$ khi $x\to+\infty$ |
| $\infty-\infty$ | $(x+1)-x\to1$; $(x+5)-x\to5$ |
| $0\cdot\infty$ | $x\cdot\frac1x\to1$; $x^2\cdot\frac1x\to0$ khi $x\to0^+$ |

**Kết luận:** Một dạng vô định chỉ cho biết **phải phân tích thêm tốc độ tiến tới** của các thành phần, không thể suy ra kết quả ngay.

## 5. Bảng tổng kết công thức cốt lõi

| Nhóm | Công thức phải nhớ | Điều kiện |
|---|---|---|
| Dãy cơ bản | $\lim 1/n^k=0$ | $n\to+\infty$, $k\in\mathbb N^*$ |
| Lũy thừa | $\lim q^n=0$ | $n\to+\infty$, $|q|<1$ |
| Đa thức dãy số | $\lim n^k=+\infty$ | $n\to+\infty$, $k\in\mathbb N^*$ |
| Thương giới hạn | $\lim(u/v)=\frac{\lim u}{\lim v}$ | Hai giới hạn hữu hạn, $\lim v\ne0$ |
| Liên hợp | $\sqrt A-\sqrt B=\frac{A-B}{\sqrt A+\sqrt B}$ | Biểu thức có nghĩa, mẫu khác $0$ |
| Tổng CSN lùi | $S=\frac{u_1}{1-q}$ | $|q|<1$ |
| Giới hạn trái/phải | $\lim_{x\to a}f=L\iff\lim_{x\to a^-}f=\lim_{x\to a^+}f=L$ | Xét hai phía |
| Liên tục | $\lim_{x\to a}f(x)=f(a)$ | $a$ là điểm trong miền xác định |
| Có nghiệm | $f(a)f(b)<0\Rightarrow\exists c\in(a,b):f(c)=0$ | $f$ liên tục trên $[a,b]$ |

---

# PHẦN IX. BÀI TẬP TỰ LUYỆN THEO MỨC ĐỘ

> [!tip] Cách làm bài cho học sinh trung bình – khá
> - **Mức A:** ghi công thức sẽ dùng trước khi tính.
> - **Mức B:** chỉ ra vì sao phải phân tích, chia bậc hoặc liên hợp.
> - **Mức C:** viết rõ điều kiện liên tục/giới hạn một bên rồi lập phương trình.
>
> Không nên xem đáp án ngay; sau khi giải hãy **đối chiếu dấu, dạng vô định và điều kiện xác định**.

## Mức A. Nhận biết – Thông hiểu

**Bài A1.** Tính:

$$
\lim_{n\to+\infty}\frac7n.
$$

**Bài A2.** Tính:

$$
\lim_{n\to+\infty}\left(4+\frac3{n^2}\right).
$$

**Bài A3.** Tính:

$$
\lim_{n\to+\infty}\frac{5n+1}{2n-3}.
$$

**Bài A4.** Tính:

$$
\lim_{n\to+\infty}\left(-\frac34\right)^n.
$$

**Bài A5.** Tính tổng:

$$
S=2+1+\frac12+\frac14+\cdots.
$$

**Bài A6.** Tính:

$$
\lim_{x\to3}(x^2-2x+4).
$$

**Bài A7.** Tính:

$$
\lim_{x\to1}\frac{x+3}{x+1}.
$$

**Bài A8.** Tính:

$$
\lim_{x\to2}\frac{x^2-4}{x-2}.
$$

## Mức B. Vận dụng các phương pháp cơ bản

**Bài B1.** Tính:

$$
\lim_{n\to+\infty}\frac{3n^2-n+2}{5n^2+1}.
$$

**Bài B2.** Tính:

$$
\lim_{n\to+\infty}\frac{2^n+3\cdot4^n}{5\cdot4^n-2^n}.
$$

**Bài B3.** Tính:

$$
\lim_{n\to+\infty}\left(\sqrt{n^2+4n}-n\right).
$$

**Bài B4.** Tính:

$$
\lim_{n\to+\infty}\frac{(-1)^n}{n^2}.
$$

**Bài B5.** Tính:

$$
\lim_{x\to9}\frac{\sqrt{x}-3}{x-9}.
$$

**Bài B6.** Tính:

$$
\lim_{x\to0}\frac{\sqrt{1+5x}-1}{x}.
$$

**Bài B7.** Tính:

$$
\lim_{x\to-\infty}\frac{\sqrt{4x^2+1}}{x}.
$$

**Bài B8.** Tính các giới hạn một bên:

$$
\lim_{x\to1^-}\frac2{x-1},\qquad
\lim_{x\to1^+}\frac2{x-1}.
$$

**Bài B9.** Cho:

$$
f(x)=
\begin{cases}
x+2,&x<1,\\
2x+1,&x\ge1.
\end{cases}
$$

Tính $\lim_{x\to1^-}f(x)$, $\lim_{x\to1^+}f(x)$ và $\lim_{x\to1}f(x)$.

## Mức C. Vận dụng tổng hợp

**Bài C1.** Tìm $m$ để hàm số:

$$
f(x)=
\begin{cases}
\dfrac{x^2-9}{x-3},&x\ne3,\\
m,&x=3
\end{cases}
$$

liên tục tại $x=3$.

**Bài C2.** Tìm $m$ để:

$$
f(x)=
\begin{cases}
mx-2,&x<2,\\
x+1,&x\ge2
\end{cases}
$$

liên tục tại $x=2$.

**Bài C3.** Chứng minh phương trình:

$$
x^3-2x-2=0
$$

có ít nhất một nghiệm trong khoảng $(1,2)$.

**Bài C4.** Tính:

$$
\lim_{x\to+\infty}\left(\sqrt{x^2+6x}-x\right).
$$

**Bài C5.** Xét giới hạn hai phía tại $x=0$ của:

$$
f(x)=\frac{|x|}{x}\qquad(x\ne0).
$$

**Bài C6.** Tính:

$$
\lim_{x\to0}\frac{x^2-4x}{x}.
$$

---

## Đáp số và hướng dẫn ngắn

### Mức A

| Bài | Đáp số | Cách làm chính |
|---|---|---|
| A1 | $0$ | $1/n\to0$ |
| A2 | $4$ | $1/n^2\to0$ |
| A3 | $5/2$ | Chia cả tử và mẫu cho $n$ |
| A4 | $0$ | $|-3/4|<1$ |
| A5 | $4$ | $u_1=2$, $q=1/2$ |
| A6 | $7$ | Thay $x=3$ |
| A7 | $2$ | Thay $x=1$ |
| A8 | $4$ | $x^2-4=(x-2)(x+2)$ |

### Mức B

| Bài | Đáp số | Cách làm chính |
|---|---|---|
| B1 | $3/5$ | Hai đa thức cùng bậc $2$ |
| B2 | $3/5$ | Chia cả tử và mẫu cho $4^n$ |
| B3 | $2$ | Nhân liên hợp; chia cho $n$ |
| B4 | $0$ | Kẹp giữa $-1/n^2$ và $1/n^2$ |
| B5 | $1/6$ | Nhân liên hợp $\sqrt x+3$ |
| B6 | $5/2$ | Nhân liên hợp $\sqrt{1+5x}+1$ |
| B7 | $-2$ | Với $x<0$, $\sqrt{x^2}=|x|=-x$ |
| B8 | $-\infty$, $+\infty$ | Xét dấu $x-1$ |
| B9 | $3$, $3$, $3$ | Hai giới hạn một bên trùng nhau |

### Mức C – Hướng dẫn đủ các bước then chốt

**C1.** Với $x\ne3$:

$$
\frac{x^2-9}{x-3}=x+3.
$$

Nên giới hạn tại $3$ bằng $6$. Liên tục khi $m=6$.

$$
\boxed{m=6.}
$$

**C2.** Bên trái giới hạn bằng $2m-2$; bên phải giới hạn bằng $3$ và $f(2)=3$.

$$
2m-2=3\iff\boxed{m=\frac52}.
$$

**C3.** Đặt $f(x)=x^3-2x-2$. Hàm đa thức liên tục trên $[1,2]$. Tính:

$$
f(1)=1-2-2=-3<0,
$$

$$
f(2)=8-4-2=2>0.
$$

Vì $f(1)f(2)<0$, tồn tại ít nhất một nghiệm trong $(1,2)$.

**C4.** Nhân liên hợp:

$$
\begin{aligned}
\sqrt{x^2+6x}-x
&=\frac{6x}{\sqrt{x^2+6x}+x}\\
&=\frac6{\sqrt{1+\frac6x}+1}\qquad(x>0).
\end{aligned}
$$

Do đó giới hạn bằng:

$$
\boxed3.
$$

**C5.** Khi $x<0$, $|x|=-x$ nên $f(x)=-1$; khi $x>0$, $|x|=x$ nên $f(x)=1$.

$$
\lim_{x\to0^-}f(x)=-1\ne1=\lim_{x\to0^+}f(x).
$$

Vậy **giới hạn hai phía không tồn tại**.

**C6.** Với $x\ne0$:

$$
\frac{x^2-4x}{x}=x-4.
$$

Do đó:

$$
\boxed{\lim_{x\to0}\frac{x^2-4x}{x}=-4.}
$$

---

# PHẦN X. GỢI Ý TRIỂN KHAI TRÊN LỚP

## 1. Trình tự dạy nên áp dụng

| Buổi | Nội dung | Trọng tâm sư phạm | Bài luyện phù hợp |
|---|---|---|---|
| 1 | Trực giác giới hạn; dãy số cơ bản | Học sinh hiểu chữ “tiến tới”, phân biệt giới hạn và giá trị | A1–A4 |
| 2 | Phân thức, lũy thừa, căn; định lí kẹp | Dạy cách nhận dạng và viết đủ bước | B1–B4 |
| 3 | Tổng cấp số nhân lùi vô hạn; giới hạn hàm số tại điểm | Liên hệ tổng từng phần, phân biệt $f(a)$ và giới hạn | A5–A8 |
| 4 | $0/0$, liên hợp, giới hạn vô cực và một bên | Khử vô định; xét dấu cẩn thận | B5–B9 |
| 5 | Tính liên tục, tìm tham số, định lí có nghiệm | Ghép 3 điều kiện, phát biểu chính xác “ít nhất một nghiệm” | C1–C6 |

## 2. Ba câu hỏi kiểm tra hiểu bản chất

**Câu 1.** Một hàm không xác định tại $x=2$ có thể có giới hạn tại $x=2$ không?

**Đáp:** Có. Ví dụ $f(x)=(x^2-4)/(x-2)$ với $x\ne2$ có giới hạn bằng $4$ tại $x=2$.

**Câu 2.** Vì sao $0/0$ không được xem là kết quả của giới hạn?

**Đáp:** Vì cùng dạng $0/0$ có thể cho nhiều giới hạn khác nhau sau biến đổi, chẳng hạn $x/x\to1$ còn $x^2/x\to0$ khi $x\to0$.

**Câu 3.** Nếu $\lim_{x\to a^-}f(x)=\lim_{x\to a^+}f(x)=5$, hàm có liên tục tại $a$ không?

**Đáp:** Chưa đủ thông tin. Còn phải biết $f(a)$ xác định và **$f(a)=5$**.

## 3. Phiếu tự kiểm tra sau khi học

- [ ] Tôi giải thích được giới hạn là xu hướng tiến gần, không phải luôn là giá trị tại điểm.
- [ ] Tôi nhớ điều kiện $|q|<1$ cho $q^n\to0$ và tổng cấp số nhân lùi.
- [ ] Tôi tính được giới hạn của phân thức theo $n$ hoặc theo $x\to\pm\infty$.
- [ ] Tôi biết khi nào cần dùng liên hợp.
- [ ] Tôi biết phân biệt $0/0$ và $A/0$ với $A\ne0$.
- [ ] Tôi xét được dấu khi tiến từ trái và từ phải.
- [ ] Tôi nhớ $\sqrt{x^2}=|x|$.
- [ ] Tôi biết ba điều kiện để hàm liên tục tại một điểm.
- [ ] Tôi có thể chứng minh một phương trình có ít nhất một nghiệm bằng định lí liên tục.

---

# PHỤ LỤC. TỜ GHI NHỚ 1 TRANG

> [!summary] Mười điều quan trọng nhất về giới hạn
> **1.** Giới hạn = **xu hướng**, không nhất thiết bằng giá trị tại điểm.  
> **2.** $\lim\limits_{n\to\infty}\frac1{n^k}=0$ với $k\ge1$ nguyên.  
> **3.** $\lim\limits_{n\to\infty}q^n=0$ khi $|q|<1$.  
> **4.** Phân thức đa thức khi biến ra vô cực: **so sánh bậc và xét dấu**.  
> **5.** Hiệu căn: thử **nhân liên hợp**.  
> **6.** Thấy $0/0$: **chưa có kết quả**, cần biến đổi.  
> **7.** Thấy $A/0$ với $A\ne0$: **xét dấu** để tìm giới hạn vô cực.  
> **8.** Giới hạn hai phía tồn tại khi **trái = phải**.  
> **9.** Liên tục tại $a$ khi $\lim\limits_{x\to a}f(x)=f(a)$.  
> **10.** Liên tục trên $[a,b]$ và $f(a)f(b)<0$ $\Rightarrow$ có **ít nhất một nghiệm** trong $(a,b)$.

## Danh sách kí hiệu

| Kí hiệu | Cách đọc |
|---|---|
| $\lim$ | Giới hạn |
| $\to$ | Tiến tới |
| $+\infty$ | Dương vô cực |
| $-\infty$ | Âm vô cực |
| $\lim_{x\to a^-}$ | Giới hạn khi $x$ tiến đến $a$ từ bên trái |
| $\lim_{x\to a^+}$ | Giới hạn khi $x$ tiến đến $a$ từ bên phải |
| $\iff$ | Khi và chỉ khi; hai điều kiện tương đương |
| $\Rightarrow$ | Suy ra |
| $\exists$ | Tồn tại |
| $\forall$ | Với mọi |

## Tài liệu tham khảo và phạm vi

Tài liệu được **biên soạn lại theo hướng giảng dạy** dựa trên:

1. *Toán 11 – Tập một, Kết nối tri thức với cuộc sống*, **Chương V: Giới hạn. Hàm số liên tục**, Bài 15–17 (SGK, trang in 104–123).
2. *Chuyên đề Giới hạn và Hàm số liên tục – Toán 11, chương trình mới* (tài liệu được cung cấp), các phần **Giới hạn của dãy số**, **Giới hạn của hàm số**, **Hàm số liên tục**, cùng hệ thống dạng toán.

**Phạm vi:** Tập trung vào kiến thức và phương pháp thuộc chương Giới hạn – Hàm số liên tục lớp 11. Một số ví dụ phụ với $\sin n$ và $\cos(1/x)$ được thêm để giải thích **nguyên lí kẹp**; đây là ví dụ minh họa bổ sung, không phải yêu cầu phải học thêm các quy tắc đạo hàm hoặc quy tắc L'Hôpital.

---

*Ghi chú sử dụng trong Obsidian: Tài liệu dùng Markdown tiêu chuẩn, công thức nội dòng bằng `$...$`, công thức riêng dòng bằng `$$...$$`, và callout Obsidian dạng `> [!note]`. Có thể lưu trực tiếp tệp `.md` vào vault và mở bằng Reading view hoặc Live Preview.*
