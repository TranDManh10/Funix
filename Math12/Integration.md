# Khái niệm tích phân
## Khái niệm tích phân

![[Integration-1.png]]

**Bài toán:** Làm thế nào để tính chính xác diện tích hình phẳng giới hạn bởi đường cong $y=f(x)$, trục $Ox$ và hai đường thẳng $x=a,\ x=b$?

### 1. Ý tưởng hình thành tích phân

Ta chia đoạn $[a,b]$ thành $n$ khoảng nhỏ, mỗi khoảng có độ rộng:

$$
\Delta x=\frac{b-a}{n}.
$$

Diện tích của mỗi hình chữ nhật xấp xỉ:

$$
\Delta S_i=f(x_i)\Delta x.
$$

Cộng tất cả hình chữ nhật:

$$
S_n=\sum_{i=1}^{n}f(x_i)\Delta x.
$$
![[Integration-2.png]]
![[Integration-3.png]]
![[Integration-4.png]]
![[Integration-5.png]]
Khi $n\to\infty$, các hình chữ nhật ngày càng hẹp và tổng diện tích tiến đến diện tích chính xác.

### 2. Ký hiệu tích phân

Với $f(x)\ge0$ trên $[a,b]$:

$$
\boxed{
S=\int_a^b f(x)\,dx
=\lim_{n\to\infty}
\sum_{i=1}^{n}f(x_i)\Delta x.
}
$$

Đây là cách xây dựng tích phân bằng tổng Riemann, với các điểm $x_i$ được chọn thích hợp trên từng khoảng chia.

Trong ký hiệu $\int_a^b f(x)\,dx$:

- $\int$: biểu thị phép cộng tích lũy.
- $f(x)$: chiều cao của mỗi hình chữ nhật.
- $dx$: ký hiệu vi phân, gắn với độ rộng rất nhỏ theo phương $x$.
- $a,b$: cận dưới và cận trên.

### 3. Ý nghĩa

Tích phân xác định biểu diễn sự tích lũy có dấu của một đại lượng trên một khoảng. Khi $f(x)\ge0$, tích phân bằng diện tích dưới đồ thị.

Nếu $f(x)$ âm trên một phần của khoảng, phần đó đóng góp giá trị âm vào tích phân.

### 4. Câu hỏi dẫn sang nguyên hàm

Ta đã biết tích phân có thể được hình thành bằng việc cộng vô số phần diện tích rất nhỏ.

Nhưng làm thế nào tính chính xác tổng đó mà không phải thực hiện phép cộng vô hạn?

Câu trả lời nằm ở nguyên hàm và Định lý cơ bản của Giải tích.


### 5. Từ tích phân đến nguyên hàm

Thay vì tính diện tích từ $a$ đến $b$ cố định, ta xét **hàm diện tích tích lũy** từ $a$ đến một vị trí $x$ thay đổi:

$$
S(x)=\int_a^x f(t)\,dt,\qquad f(t)\ge0.
$$

Khi $x$ tăng thêm một lượng rất nhỏ $\Delta x$, phần diện tích tăng thêm xấp xỉ một hình chữ nhật:

$$
\Delta S\approx f(x)\Delta x.
$$

Do đó:

$$
\frac{\Delta S}{\Delta x}\approx f(x).
$$

Khi $\Delta x\to0$, nếu $f$ liên tục, ta thu được:

$$
\boxed{S'(x)=f(x).}
$$

**Nhận xét:** Đạo hàm của hàm diện tích tích lũy chính là hàm số $f(x)$. Vì vậy, muốn tìm hàm diện tích $S(x)$, ta cần thực hiện phép toán ngược của đạo hàm.

Phép toán này được gọi là **tìm nguyên hàm**.

### 6. Định nghĩa nguyên hàm

Hàm số $F(x)$ được gọi là một nguyên hàm của $f(x)$ trên khoảng $K$ nếu:

$$
\boxed{F'(x)=f(x),\qquad \forall x\in K.}
$$

Ví dụ:

$$
f(x)=x^2
\quad\Longrightarrow\quad
F(x)=\frac{x^3}{3},
$$

vì:

$$
\left(\frac{x^3}{3}\right)'=x^2.
$$

### 7. Mối liên hệ giữa tích phân và nguyên hàm

Theo **Định lý cơ bản của Giải tích**, nếu $F'(x)=f(x)$ và $f$ liên tục trên $[a,b]$ thì:

$$
\boxed{
\int_a^b f(x)\,dx=F(b)-F(a).
}
$$

Như vậy, thay vì cộng vô số hình chữ nhật để tính tích phân, ta chỉ cần tìm một nguyên hàm $F(x)$ rồi lấy hiệu giá trị tại hai cận.

**Kết luận:** Tích phân xuất phát từ bài toán tích lũy diện tích, còn nguyên hàm là công cụ giúp tính chính xác tích phân.

# Các dạng tích phân

## 1. Công thức Newton–Leibniz

Cho $f$ liên tục trên $[a,b]$ và $F'(x)=f(x)$. Khi đó:

$$
\boxed{\int_a^b f(x)\,dx=\left.F(x)\right|_a^b=F(b)-F(a).}
$$

**Cách tính:** Tìm nguyên hàm $F$ → thế cận trên $b$ → trừ giá trị tại cận dưới $a$.

**Ví dụ:**

$$
\int_1^2 2x\,dx=\left.x^2\right|_1^2=4-1=3.
$$

**Lưu ý:** Tích phân xác định là **một số**, không có hằng số $+C$; biến lấy tích phân là biến giả:

$$
\int_a^b f(x)\,dx=\int_a^b f(t)\,dt.
$$

## 2. Các tính chất của tích phân

Giả sử $f,g$ liên tục trên đoạn đang xét, $k$ là hằng số.

| Tính chất | Công thức |
|---|---|
| Cận trùng nhau | $\displaystyle\int_a^a f(x)\,dx=0$ |
| Đổi cận | $\displaystyle\int_a^b f(x)\,dx=-\int_b^a f(x)\,dx$ |
| Chia khoảng | $\displaystyle\int_a^b f(x)\,dx=\int_a^c f(x)\,dx+\int_c^b f(x)\,dx$ |
| Nhân hằng số | $\displaystyle\int_a^b kf(x)\,dx=k\int_a^b f(x)\,dx$ |
| Tổng và hiệu | $\displaystyle\int_a^b(f\pm g)\,dx=\int_a^b f\,dx\pm\int_a^b g\,dx$ |

**Ví dụ 1 (đổi cận):** Nếu $\displaystyle\int_1^3 f(x)\,dx=5$ thì

$$
\int_3^1 2f(x)\,dx=-2\int_1^3 f(x)\,dx=-10.
$$

**Ví dụ 2 (chia khoảng):** Nếu $\displaystyle\int_0^1 f(x)\,dx=2$ và $\displaystyle\int_1^3 f(x)\,dx=4$ thì

$$
\int_0^3 f(x)\,dx=2+4=6.
$$

### Tính chất so sánh

Nếu $f(x)\ge0$ trên $[a,b]$ với $a<b$ thì $\displaystyle\int_a^b f(x)\,dx\ge0$.

Nếu $f(x)\ge g(x)$ trên $[a,b]$ với $a<b$ thì

$$
\int_a^b f(x)\,dx\ge\int_a^b g(x)\,dx.
$$

Nếu $m\le f(x)\le M$ trên $[a,b]$ thì

$$
\boxed{m(b-a)\le\int_a^b f(x)\,dx\le M(b-a).}
$$

## 3. Tính tích phân trực tiếp

**Phương pháp:** Dùng tính tuyến tính → tìm nguyên hàm từng hạng tử → áp dụng Newton–Leibniz.

**Ví dụ 1 (đa thức):**

$$
\begin{aligned}
\int_0^2(3x^2+2x)\,dx
&=\left.(x^3+x^2)\right|_0^2\\
&=8+4=12.
\end{aligned}
$$

**Ví dụ 2 (mũ, lượng giác):**

$$
\begin{aligned}
\int_0^{\pi/2}(e^x+\sin x)\,dx
&=\left.(e^x-\cos x)\right|_0^{\pi/2}\\
&=e^{\pi/2}.
\end{aligned}
$$

**Ghi nhớ:** Tích phân có thể âm; không tự thêm dấu giá trị tuyệt đối khi tính $\int_a^b f(x)\,dx$.

## 4. Tích phân của hàm hợp

### 4.1. Hàm hợp tuyến tính $u=ax+b$

Với $a\ne0$, nếu $F'(u)=f(u)$ thì

$$
\boxed{\int_\alpha^\beta f(ax+b)\,dx=\left.\frac{F(ax+b)}a\right|_\alpha^\beta.}
$$

**Ví dụ:**

$$
\int_0^1(2x+1)^2\,dx
=\left.\frac{(2x+1)^3}{6}\right|_0^1
=\frac{13}{3}.
$$

### 4.2. Nhận dạng $u'(x)f(u(x))$

Nếu $F'=f$ thì

$$
\boxed{\int_a^b u'(x)f(u(x))\,dx=F(u(b))-F(u(a)).}
$$

**Ví dụ:**

$$
\int_0^1 2xe^{x^2}\,dx=\left.e^{x^2}\right|_0^1=e-1.
$$

**Lưu ý:** Không phải cứ có hàm hợp là được “chia cho đạo hàm bên trong”; cần đúng dạng nhận biết ở trên. *Phép đổi biến tổng quát là kiến thức mở rộng*, không bắt buộc với các ví dụ cơ bản này.

## 5. Tích phân chứa giá trị tuyệt đối

**Quy tắc:** Tìm nghiệm $f(x)=0$ trong $(a,b)$ → xét dấu $f$ → bỏ dấu $|\cdot|$ trên từng khoảng → tính.

$$
|f(x)|=\begin{cases}
f(x),&f(x)\ge0,\\
-f(x),&f(x)<0.
\end{cases}
$$

**Ví dụ:** Tính $\displaystyle\int_{-1}^{2}|x-1|\,dx$.

Vì $x-1<0$ khi $x<1$ và $x-1\ge0$ khi $x\ge1$ nên

$$
\begin{aligned}
\int_{-1}^{2}|x-1|\,dx
&=\int_{-1}^{1}(1-x)\,dx+\int_1^2(x-1)\,dx\\
&=2+\frac12=\boxed{\frac52}.
\end{aligned}
$$

## 6. Tích phân của hàm số từng đoạn

**Quy tắc:** Chia tích phân tại tất cả điểm đổi công thức nằm trong khoảng lấy tích phân.

Nếu $a<c<b$ và $f(x)=\begin{cases}f_1(x),&x<c,\\f_2(x),&x\ge c,\end{cases}$ thì

$$
\int_a^b f(x)\,dx=\int_a^c f_1(x)\,dx+\int_c^b f_2(x)\,dx.
$$

**Ví dụ:** Cho

$$
f(x)=\begin{cases}x^2,&x<0,\\2x,&x\ge0.\end{cases}
$$

Khi đó

$$
\begin{aligned}
\int_{-1}^{2}f(x)\,dx
&=\int_{-1}^0x^2\,dx+\int_0^2 2x\,dx\\
&=\frac13+4=\boxed{\frac{13}{3}}.
\end{aligned}
$$

## 7. Bài toán tìm tham số và giá trị chưa biết

**Phương pháp:** Tính tích phân (hoặc dùng tính chất) → lập phương trình theo tham số → giải.

**Ví dụ 1 (tìm $m$):** Tìm $m$ biết

$$
\int_0^1(2x+m)\,dx=3.
$$

Ta có $\left.(x^2+mx)\right|_0^1=1+m=3$, suy ra $\boxed{m=2}$.

**Ví dụ 2 (tính tích phân chưa biết):** Biết $\displaystyle\int_0^2 f(x)\,dx=5$ và $\displaystyle\int_0^2 g(x)\,dx=2$. Tính

$$
I=\int_0^2[3f(x)-2g(x)]\,dx=3\cdot5-2\cdot2=\boxed{11}.
$$

## 8. Ứng dụng tích phân (học thành bài riêng)

| Bài toán | Công thức |
|---|---|
| Diện tích với trục $Ox$ | $\displaystyle S=\int_a^b \lvert f(x)\rvert\,dx$ |
| Diện tích giữa hai đồ thị | $\displaystyle S=\int_a^b \lvert f(x)-g(x)\rvert\,dx$ |
| Thể tích theo mặt cắt | $\displaystyle V=\int_a^b A(x)\,dx$ |
| Thể tích tròn xoay quanh $Ox$ | $\displaystyle V=\pi\int_a^b[f(x)]^2\,dx$ |
| Thể tích tròn xoay quanh $Oy$ (dùng lát cắt ngang) | $\displaystyle V=\pi\int_c^d[g(y)]^2\,dy$ |

**Lưu ý:** Hai công thức tròn xoay ở trên dành cho miền nằm giữa đồ thị và trục quay; nếu miền có lỗ rỗng, sử dụng hiệu bình phương bán kính ngoài và trong. Đây là nội dung học kỹ trong bài *Ứng dụng tích phân*.

---

# PHẦN MỞ RỘNG – PHƯƠNG PHÁP TÍNH TÍCH PHÂN

*Các mục sau bổ sung để học toàn diện hơn; không đồng nghĩa tất cả đều là kiến thức bắt buộc của SGK Toán 12 Kết nối tri thức.*

## 9. Đổi biến số (đặt biến phụ)

### 9.1. Đặt $u=g(x)$ và đổi cận

Với $u=g(x)$, $du=g'(x)\,dx$, ta có (khi các hàm liên tục và phép thế hợp lệ):

$$
\boxed{\int_a^b f(g(x))g'(x)\,dx=\int_{g(a)}^{g(b)}f(u)\,du.}
$$

**Các bước:** Đặt $u$ → tính $du$ → **đổi cả hai cận** → tính theo $u$.

**Ví dụ:**

$$
\begin{aligned}
I&=\int_0^1 2x(x^2+1)^3\,dx,\\
u&=x^2+1,\quad du=2x\,dx,\\
x=0&\Rightarrow u=1,\qquad x=1\Rightarrow u=2,\\
I&=\int_1^2u^3\,du=\left.\frac{u^4}{4}\right|_1^2=\frac{15}{4}.
\end{aligned}
$$

**Chú ý:** Cận được đổi theo đúng biểu thức của $u$; nếu đã đổi cận thì không cần quay về biến $x$ khi thế cận.

### 9.2. Đặt $x=\varphi(t)$

Nếu $x=\varphi(t)$, $dx=\varphi'(t)\,dt$, và $\varphi(\alpha)=a$, $\varphi(\beta)=b$, thì:

$$
\boxed{\int_a^b f(x)\,dx=\int_\alpha^\beta f(\varphi(t))\varphi'(t)\,dt.}
$$

**Ví dụ:** Với $x=t^2$ ($t\in[0,1]$), $dx=2t\,dt$:

$$
\int_0^1\sqrt{x}\,dx=\int_0^1 t\cdot2t\,dt=\frac23.
$$

### 9.3. Đổi biến tuyến tính (nhớ nhanh)

$$
\boxed{\int_a^b f(mx+n)\,dx=\frac1m\int_{ma+n}^{mb+n}f(u)\,du,\quad m\ne0.}
$$

**Ví dụ:**

$$
\int_0^1(2x+1)^2\,dx=\frac12\int_1^3u^2\,du=\frac{13}{3}.
$$

---

## 10. Tích phân từng phần

Từ $(uv)'=u'v+uv'$:

$$
\boxed{\int_a^b u(x)v'(x)\,dx=\left.u(x)v(x)\right|_a^b-\int_a^b u'(x)v(x)\,dx.}
$$

Viết gọn: $\displaystyle\int_a^b u\,dv=\left.uv\right|_a^b-\int_a^b v\,du$.

**Cách làm:** Chọn $u$ để đạo hàm đơn giản hơn; chọn $dv$ dễ tìm nguyên hàm.

**Ví dụ 1:** $u=x,\ dv=e^x\,dx\Rightarrow du=dx,\ v=e^x$:

$$
\begin{aligned}
\int_0^1xe^x\,dx
&=\left.xe^x\right|_0^1-\int_0^1e^x\,dx\\
&=e-(e-1)=1.
\end{aligned}
$$

**Ví dụ 2:** $u=x,\ dv=\sin x\,dx\Rightarrow du=dx,\ v=-\cos x$:

$$
\int_0^{\pi/2}x\sin x\,dx
=\left.-x\cos x\right|_0^{\pi/2}+\int_0^{\pi/2}\cos x\,dx=1.
$$

**Thường gặp:** $x e^x$, $x\sin x$, $x\cos x$, $\ln x$, tích đa thức với hàm mũ hoặc lượng giác.

---

## 11. Phân tích phân thức hữu tỉ

### 11.1. Chia đa thức trước khi lấy tích phân

Nếu bậc tử số không nhỏ hơn bậc mẫu số, hãy **chia đa thức**.

**Ví dụ:**

$$
\begin{aligned}
\int_1^2\frac{x^2+1}{x}\,dx
&=\int_1^2\left(x+\frac1x\right)dx\\
&=\left.\left(\frac{x^2}{2}+\ln x\right)\right|_1^2
=\frac32+\ln2.
\end{aligned}
$$

### 11.2. Phân tích thành phân thức đơn giản

Ví dụ dạng hai nhân tử tuyến tính:

$$
\frac1{x(x+1)}=\frac1x-\frac1{x+1}.
$$

Suy ra:

$$
\begin{aligned}
\int_1^2\frac{dx}{x(x+1)}
&=\left.\ln\left|\frac{x}{x+1}\right|\right|_1^2
=\ln\frac43.
\end{aligned}
$$

**Ghi nhớ:** Cách tách $\frac{P(x)}{Q(x)}$ tổng quát là phần mở rộng; các phân thức đơn giản thường chỉ cần biến đổi đại số.

---

## 12. Tích phân lượng giác mở rộng

| Công thức biến đổi | Kết quả |
|---|---|
| $\sin^2x$ | $\dfrac{1-\cos2x}{2}$ |
| $\cos^2x$ | $\dfrac{1+\cos2x}{2}$ |
| $\sin x\cos x$ | $\dfrac{\sin2x}{2}$ |
| $\sin A\cos B$ | $\dfrac{\sin(A+B)+\sin(A-B)}2$ |

**Ví dụ:**

$$
\int_0^{\pi/2}\sin^2x\,dx
=\frac12\int_0^{\pi/2}(1-\cos2x)\,dx
=\frac\pi4.
$$

### Phép thế lượng giác (nâng cao)

| Biểu thức | Phép thế thường dùng |
|---|---|
| $\sqrt{a^2-x^2}$ | $x=a\sin t$ |
| $\sqrt{a^2+x^2}$ | $x=a\tan t$ (một lựa chọn) |
| $\sqrt{x^2-a^2}$ | $x=a\sec t$ trên miền thích hợp |

**Ví dụ:** Đặt $x=\sin t$, $dx=\cos t\,dt$; cận $0\mapsto0$, $1\mapsto\pi/2$:

$$
\int_0^1\sqrt{1-x^2}\,dx
=\int_0^{\pi/2}\cos^2t\,dt=\frac\pi4.
$$

---

## 13. Các tính chất đối xứng và tuần hoàn

### 13.1. Hàm chẵn, hàm lẻ trên $[-a,a]$

$$
\boxed{\begin{aligned}
f(-x)=f(x)&\Rightarrow\int_{-a}^a f(x)\,dx=2\int_0^a f(x)\,dx,\\
f(-x)=-f(x)&\Rightarrow\int_{-a}^a f(x)\,dx=0.
\end{aligned}}
$$

**Ví dụ:**

$$
\int_{-1}^1(x^3+x^2)\,dx
=0+2\int_0^1x^2\,dx=\frac23.
$$

### 13.2. Phép đổi $x\mapsto a+b-x$

$$
\boxed{\int_a^b f(x)\,dx=\int_a^b f(a+b-x)\,dx.}
$$

**Ví dụ:** Đặt $I=\displaystyle\int_0^{\pi/2}\frac{\sin x}{\sin x+\cos x}\,dx$.

Đổi $x\mapsto\frac\pi2-x$:

$$
I=\int_0^{\pi/2}\frac{\cos x}{\sin x+\cos x}\,dx,
\quad 2I=\int_0^{\pi/2}1\,dx=\frac\pi2
\Rightarrow\boxed{I=\frac\pi4}.
$$

### 13.3. Hàm tuần hoàn

Nếu $f(x+T)=f(x)$ thì:

$$
\boxed{\int_a^{a+T}f(x)\,dx=\int_0^T f(x)\,dx.}
$$

**Ví dụ:** $\displaystyle\int_1^{1+2\pi}\sin x\,dx=0$.

---

## 14. Tích phân có tham số và công thức truy hồi (nâng cao)

### 14.1. Tích phân chứa tham số

**Ví dụ:** Tìm $m$ nếu $\displaystyle\int_0^1(mx+2)\,dx=5$.

$$
\frac m2+2=5\Rightarrow\boxed{m=6}.
$$

### 14.2. Truy hồi dạng lũy thừa lượng giác

Đặt $\displaystyle I_n=\int_0^{\pi/2}\sin^n x\,dx$, $n\ge2$. Từ tích phân từng phần:

$$
\boxed{I_n=\frac{n-1}{n}I_{n-2},\qquad I_0=\frac\pi2,\quad I_1=1.}
$$

**Ví dụ:** $\displaystyle I_2=\frac12I_0=\frac\pi4$.

---

## 15. Tích phân suy rộng (mở rộng ngoài chương trình phổ thông cơ bản)

Tích phân suy rộng xuất hiện khi **cận vô hạn** hoặc **hàm không bị chặn** tại cận. Giá trị được định nghĩa thông qua giới hạn.

$$
\boxed{\int_a^{+\infty}f(x)\,dx=\lim_{b\to+\infty}\int_a^b f(x)\,dx}
$$

Ví dụ:

$$
\int_1^{+\infty}\frac{dx}{x^2}
=\lim_{b\to+\infty}\left(1-\frac1b\right)=1.
$$

Tích phân không nhất thiết hội tụ: $\displaystyle\int_1^{+\infty}\frac{dx}{x}$ phân kỳ.

---

## 16. Xấp xỉ tích phân bằng phương pháp số (mở rộng)

Chia $[a,b]$ thành $n$ phần, $h=(b-a)/n$, $x_i=a+ih$.

| Phương pháp | Công thức |
|---|---|
| Hình chữ nhật trái | $\displaystyle L_n=h\sum_{i=0}^{n-1}f(x_i)$ |
| Trung điểm | $\displaystyle M_n=h\sum_{i=0}^{n-1}f\!\left(\frac{x_i+x_{i+1}}2\right)$ |
| Hình thang | $\displaystyle T_n=h\left[\frac{f(a)+f(b)}2+\sum_{i=1}^{n-1}f(x_i)\right]$ |

**Ví dụ:** $\displaystyle\int_0^1x^2\,dx$ với $n=2$, $h=\frac12$:

$$
L_2=\frac18,\qquad T_2=\frac38,\qquad \int_0^1x^2\,dx=\frac13.
$$

---

## Ghi nhớ nhanh

| Nhận dạng bài toán | Hướng giải |
|---|---|
| Hàm cơ bản, đa thức | Bảng nguyên hàm + Newton–Leibniz |
| Tổng, hiệu; đổi thứ tự cận | Tính tuyến tính; tính chất cận |
| $f(g(x))g'(x)$ | Đặt $u=g(x)$, đổi cận |
| Tích $x e^x$, $x\sin x$ | Tích phân từng phần |
| Phân thức hữu tỉ | Chia đa thức, phân tích phân thức |
| $|f(x)|$, hàm từng đoạn | Xét dấu, chia khoảng |
| Cận $[-a,a]$ | Kiểm tra chẵn, lẻ |
| $\sqrt{a^2-x^2}$ | Xem xét phép thế lượng giác |
| Cận vô hạn hoặc điểm kỳ dị | Xét giới hạn (tích phân suy rộng) |

**Phân biệt:** $\displaystyle\int f(x)\,dx=F(x)+C$ là họ nguyên hàm; $\displaystyle\int_a^b f(x)\,dx=F(b)-F(a)$ là một giá trị số.