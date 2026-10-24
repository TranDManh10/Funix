
# NGUYÊN HÀM

## 1. Định nghĩa nguyên hàm

Hàm số $F(x)$ được gọi là **nguyên hàm** của $f(x)$ trên khoảng $K$ nếu:

$$
\boxed{F'(x)=f(x),\qquad \forall x\in K.}
$$

Nếu $F(x)$ là một nguyên hàm của $f(x)$ thì **họ tất cả các nguyên hàm** trên $K$ là:

$$
\boxed{
\int f(x)\,dx=F(x)+C,\qquad C\in\mathbb R.
}
$$

Trong đó $C$ là hằng số tùy ý.

**Ví dụ:** $F(x)=x^3$ là nguyên hàm của $f(x)=3x^2$ vì $F'(x)=3x^2$.

**Chú ý:**

- Hai nguyên hàm của cùng một hàm số trên một khoảng chỉ khác nhau một hằng số.
- Hàm số liên tục trên một khoảng luôn có nguyên hàm trên khoảng đó.
- Có thể kiểm tra kết quả nguyên hàm bằng cách lấy đạo hàm.

---

## 2. Tính chất của nguyên hàm

Với $k$ là hằng số khác $0$:

| Tính chất | Công thức |
|---|---|
| Đạo hàm của nguyên hàm | $\left(\int f(x)\,dx\right)'=f(x)$ |
| Nhân hằng số | $\int kf(x)\,dx=k\int f(x)\,dx$ |
| Tổng | $\int[f(x)+g(x)]\,dx=\int f(x)\,dx+\int g(x)\,dx$ |
| Hiệu | $\int[f(x)-g(x)]\,dx=\int f(x)\,dx-\int g(x)\,dx$ |

**Tính tuyến tính:**

$$
\boxed{
\int[af(x)+bg(x)]\,dx
=a\int f(x)\,dx+b\int g(x)\,dx.
}
$$

**Ví dụ:** $\displaystyle\int(2x+3)\,dx=x^2+3x+C$.

---

## 3. Bảng nguyên hàm cơ bản

### 3.1. Hàm lũy thừa và logarit

| Hàm số $f(x)$ | Nguyên hàm |
|---|---|
| $1$ | $x+C$ |
| $x^\alpha$, $\alpha\neq-1$ | $\dfrac{x^{\alpha+1}}{\alpha+1}+C$ |
| $\dfrac1x$ | $\ln\lvert x\rvert+C$ |
| $\sqrt{x}$ | $\dfrac23x\sqrt{x}+C$ |
| $\dfrac1{\sqrt{x}}$ | $2\sqrt{x}+C$ |
| $\dfrac1{x^2}$ | $-\dfrac1x+C$ |
| $\dfrac1{x^3}$ | $-\dfrac1{2x^2}+C$ |

**Hai công thức quan trọng:**

$$
\boxed{
\int x^\alpha\,dx
=\frac{x^{\alpha+1}}{\alpha+1}+C,\quad \alpha\neq-1.
}
$$

$$
\boxed{
\int\frac1x\,dx=\ln|x|+C.
}
$$

**Ví dụ:**

$$
\int x^3\,dx=\frac{x^4}{4}+C,\qquad
\int\frac{dx}{x}=\ln|x|+C.
$$

### 3.2. Hàm số mũ

| Hàm số $f(x)$ | Nguyên hàm |
|---|---|
| $e^x$ | $e^x+C$ |
| $a^x$ | $\dfrac{a^x}{\ln a}+C$ |

Điều kiện: $a>0,\ a\neq1$.

**Ví dụ:**

$$
\int e^x\,dx=e^x+C,\qquad
\int 2^x\,dx=\frac{2^x}{\ln2}+C.
$$

### 3.3. Hàm lượng giác

| Hàm số $f(x)$ | Nguyên hàm |
|---|---|
| $\sin x$ | $-\cos x+C$ |
| $\cos x$ | $\sin x+C$ |
| $\dfrac1{\cos^2x}$ | $\tan x+C$ |
| $\dfrac1{\sin^2x}$ | $-\cot x+C$ |

**Ví dụ:**

$$
\int\sin x\,dx=-\cos x+C,\qquad
\int\frac{dx}{\cos^2x}=\tan x+C.
$$

---

## 4. Bảng nguyên hàm mở rộng

### 4.1. Hàm hợp tuyến tính $u=ax+b$

Với $a\neq0$:

| Hàm số $f(x)$ | Nguyên hàm |
|---|---|
| $(ax+b)^\alpha$ | $\dfrac{(ax+b)^{\alpha+1}}{a(\alpha+1)}+C$ |
| $\dfrac1{ax+b}$ | $\dfrac1a\ln\lvert ax+b\rvert+C$ |
| $e^{ax+b}$ | $\dfrac1ae^{ax+b}+C$ |
| $q^{ax+b}$ | $\dfrac{q^{ax+b}}{a\ln q}+C$ |
| $\sin(ax+b)$ | $-\dfrac1a\cos(ax+b)+C$ |
| $\cos(ax+b)$ | $\dfrac1a\sin(ax+b)+C$ |
| $\dfrac1{\cos^2(ax+b)}$ | $\dfrac1a\tan(ax+b)+C$ |
| $\dfrac1{\sin^2(ax+b)}$ | $-\dfrac1a\cot(ax+b)+C$ |

Điều kiện bổ sung: $\alpha\neq-1$ đối với công thức lũy thừa; $q>0,\ q\neq1$ đối với hàm mũ.

**Quy tắc:** Với hàm hợp tuyến tính $ax+b$, chia thêm cho hệ số $a$.

**Ví dụ:**

$$
\int(2x+1)^3\,dx=\frac{(2x+1)^4}{8}+C,
\qquad
\int\cos(3x)\,dx=\frac{\sin(3x)}3+C.
$$

### 4.2. Hàm hợp tổng quát (bổ sung)

Giả sử $u=u(x)$ khả vi và các biểu thức xác định trên khoảng đang xét.

| Dạng nguyên hàm | Công thức |
|---|---|
| $\int u'(x)[u(x)]^\alpha\,dx$ | $\dfrac{[u(x)]^{\alpha+1}}{\alpha+1}+C$ |
| $\int\dfrac{u'(x)}{u(x)}\,dx$ | $\ln\lvert u(x)\rvert+C$ |
| $\int u'(x)e^{u(x)}\,dx$ | $e^{u(x)}+C$ |
| $\int u'(x)\sin[u(x)]\,dx$ | $-\cos[u(x)]+C$ |
| $\int u'(x)\cos[u(x)]\,dx$ | $\sin[u(x)]+C$ |

Với công thức lũy thừa, $\alpha\neq-1$.

**Nhận dạng:** Khi xuất hiện hàm hợp $u(x)$, kiểm tra xem biểu thức có chứa đạo hàm $u'(x)$ hay không.

**Ví dụ:**

$$
\int 2x(x^2+1)^3\,dx=\frac{(x^2+1)^4}{4}+C,
\qquad
\int\frac{2x}{x^2+1}\,dx=\ln(x^2+1)+C.
$$

---

## 5. Các dạng toán nguyên hàm

### Dạng 1. Tìm họ nguyên hàm trực tiếp

**Phương pháp:** Biến đổi về các công thức cơ bản, sau đó áp dụng tính tuyến tính.

Ví dụ:

$$
\begin{aligned}
I&=\int(2x+3)\,dx\\
&=x^2+3x+C.
\end{aligned}
$$

### Dạng 2. Tìm nguyên hàm bằng biến đổi đại số

**Phương pháp:** Khai triển, rút gọn, chia đa thức hoặc chuyển căn thức về lũy thừa.

Ví dụ:

$$
\begin{aligned}
I&=\int\frac{x^2+2x+1}{x+1}\,dx\\
&=\int(x+1)\,dx=\frac{x^2}{2}+x+C.
\end{aligned}
$$

### Dạng 3. Tìm nguyên hàm thỏa mãn điều kiện

Cho:

$$
F'(x)=f(x),\qquad F(x_0)=y_0.
$$

**Phương pháp:**

1. Tìm $F(x)=G(x)+C$.
2. Thay $F(x_0)=y_0$ để xác định $C$.

Ví dụ:

$$
F'(x)=2x+3,\qquad F(1)=5.
$$

Ta có:

$$
F(x)=x^2+3x+C.
$$

Thay điều kiện:

$$
1+3+C=5\Rightarrow C=1.
$$

Vậy:

$$
F(x)=x^2+3x+1.
$$

---

## 6. Những lưu ý quan trọng

| Vấn đề | Ghi nhớ |
|---|---|
| Hằng số nguyên hàm | Luôn có $+C$ khi viết họ nguyên hàm |
| Hàm lũy thừa | Công thức $\int x^\alpha\,dx$ không áp dụng với $\alpha=-1$ |
| Hàm $\dfrac1x$ | Nguyên hàm là $\ln|x|+C$ |
| Hàm $\sin x$ | Nguyên hàm có dấu âm: $-\cos x+C$ |
| Hàm $a^x$ | Phải chia cho $\ln a$ |
| Hàm hợp $ax+b$ | Chú ý hệ số $a$ |
| Miền xác định | Xét nguyên hàm trên từng khoảng xác định |
| Kiểm tra kết quả | Lấy đạo hàm nguyên hàm vừa tìm |

---

## 7. Công thức tổng kết

$$
\boxed{
\begin{gathered}
F'(x)=f(x),\\[6pt]
\int f(x)\,dx=F(x)+C,\\[6pt]
\left(\int f(x)\,dx\right)'=f(x).
\end{gathered}
}
$$

**Nguyên tắc chung:** Tìm nguyên hàm là tìm một hàm số mà đạo hàm của nó bằng hàm số đã cho.