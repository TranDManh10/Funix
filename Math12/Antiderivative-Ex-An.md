# LỜI GIẢI CHI TIẾT 60 BÀI TẬP NGUYÊN HÀM

**Toán 12 – Kết nối tri thức với cuộc sống**  
**Cấu trúc:** Nhắc đề → Công thức áp dụng → Triển khai → Kết luận.  
**Lưu ý:** Với nguyên hàm bất định, $C$ là hằng số tùy ý **trên từng khoảng xác định**. Các bài thực tế dùng $t\ge0$.

---

# PHẦN A. NHẬN BIẾT

## Dạng 1. Nhận biết nguyên hàm

### Bài 1

**Đề:** Kiểm tra $F$ có là nguyên hàm của $f$ trên $\mathbb R$ không:

$$\begin{aligned}
\text{a)}\;&F=x^3+2x,\ f=3x^2+2; &\text{b)}\;&F=x^4-3x^2+1,\ f=4x^3-6x;\\
\text{c)}\;&F=e^x+3,\ f=e^x+3; &\text{d)}\;&F=\sin x+\cos x,\ f=\cos x-\sin x.
\end{aligned}$$

**Công thức:** $F$ là nguyên hàm của $f$ khi và chỉ khi $F'(x)=f(x)$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\quad&F'=3x^2+2=f &&\Rightarrow \text{Đúng}.\\
\text{b)}\quad&F'=4x^3-6x=f &&\Rightarrow \text{Đúng}.\\
\text{c)}\quad&F'=e^x\ne e^x+3 &&\Rightarrow \text{Sai}.\\
\text{d)}\quad&F'=\cos x-\sin x=f &&\Rightarrow \text{Đúng}.
\end{aligned}$$

### Bài 2

**Đề:** Với $f(x)=6x^2-4x$, xác định các nguyên hàm trong bốn hàm $F_1=2x^3-2x^2+1$, $F_2=2x^3+2x^2-1$, $F_3=3x^3-2x^2$, $F_4=2x^3-2x^2-5$.

**Công thức:** $F'=f$.

**Lời giải:**

$$\begin{aligned}
F_1'&=6x^2-4x=f,&F_2'&=6x^2+4x\ne f,\\
F_3'&=9x^2-4x\ne f,&F_4'&=6x^2-4x=f.
\end{aligned}$$

**Kết luận:** $F_1,F_4$.

### Bài 3

**Đề:** $F$ là nguyên hàm của $f(x)=3x^2+1$. (a) Chứng minh $G=F+5$ cũng là nguyên hàm; (b) tính $F'(2),G'(3)$.

**Công thức:** $(F+C)'=F'$.

**Lời giải:** $G'(x)=F'(x)+(5)'=f(x)$. Do đó $G$ là nguyên hàm. Mặt khác,

$$F'(2)=3\cdot2^2+1=13,\qquad G'(3)=3\cdot3^2+1=28.$$

### Bài 4

**Đề:** Tìm $f$ biết $F$ là nguyên hàm:

$$\begin{aligned}
\text{a)}\;&F=x^5-3x^2+4;&\text{b)}\;&F=\sqrt x+2x\ (x>0);\\
\text{c)}\;&F=e^{2x}-\sin x;&\text{d)}\;&F=\ln x+x^3\ (x>0).
\end{aligned}$$

**Công thức:** $f=F'$; $(x^\alpha)'=\alpha x^{\alpha-1}$; $(e^{u})'=u'e^u$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&f=5x^4-6x; &\text{b)}\;&f=\frac{1}{2\sqrt x}+2;\\
\text{c)}\;&f=2e^{2x}-\cos x;&\text{d)}\;&f=\frac1x+3x^2.
\end{aligned}$$

### Bài 5

**Đề:** Tìm $m$ để $F=mx^3+(m+1)x^2-4x+2$ là nguyên hàm của $f=6x^2+6x-4$.

**Công thức:** $F'=f$; đồng nhất hệ số đa thức.

**Lời giải:**

$$F'=3mx^2+2(m+1)x-4.$$

So sánh với $6x^2+6x-4$: $3m=6$ và $2(m+1)=6$. Cả hai cho **$m=2$**.

## Dạng 2. Nguyên hàm hàm lũy thừa

### Bài 6

**Đề:** Tìm $\int x^2dx$, $\int x^5dx$, $\int x^{10}dx$, $\int x^{2025}dx$.

**Công thức:** $\displaystyle\int x^\alpha dx=\frac{x^{\alpha+1}}{\alpha+1}+C$ với $\alpha\ne-1$.

**Lời giải:** Tăng số mũ thêm $1$, rồi chia cho số mũ mới:

$$\begin{aligned}
\text{a)}\;&\int x^2dx=\frac{x^3}{3}+C;&\text{b)}\;&\int x^5dx=\frac{x^6}{6}+C;\\
\text{c)}\;&\int x^{10}dx=\frac{x^{11}}{11}+C;&\text{d)}\;&\int x^{2025}dx=\frac{x^{2026}}{2026}+C.
\end{aligned}$$

### Bài 7

**Đề:** Tính $\int\frac{dx}{x^2}$, $\int\frac{dx}{x^4}$, $\int\frac{dx}{x^7}$, $\int\frac{dx}{x}$.

**Công thức:** $\int x^{-n}dx=\frac{x^{1-n}}{1-n}+C$ ($n\ne1$); riêng $\int\frac{dx}{x}=\ln|x|+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\int x^{-2}dx=-x^{-1}+C=-\frac1x+C;\\
\text{b)}\;&\int x^{-4}dx=-\frac{x^{-3}}3+C=-\frac1{3x^3}+C;\\
\text{c)}\;&\int x^{-7}dx=-\frac{x^{-6}}6+C=-\frac1{6x^6}+C;\\
\text{d)}\;&\int\frac{dx}{x}=\ln|x|+C.
\end{aligned}$$

### Bài 8

**Đề:** Tính $\int\sqrt x\,dx$, $\int\frac{dx}{\sqrt x}$, $\int x\sqrt x\,dx$, $\int\sqrt{x^3}\,dx$ ($x>0$).

**Công thức:** $\sqrt x=x^{1/2}$, $1/\sqrt x=x^{-1/2}$; dùng quy tắc nguyên hàm lũy thừa.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\int x^{1/2}dx=\frac{x^{3/2}}{3/2}+C=\frac23x^{3/2}+C;\\
\text{b)}\;&\int x^{-1/2}dx=\frac{x^{1/2}}{1/2}+C=2\sqrt x+C;\\
\text{c)}\;&\int x^{3/2}dx=\frac25x^{5/2}+C;\\
\text{d)}\;&\int\sqrt{x^3}\,dx=\int x^{3/2}dx=\frac25x^{5/2}+C.
\end{aligned}$$

### Bài 9

**Đề:** Tính:

$$\begin{aligned}
\text{a)}\;&\int(3x^2-4x+5)dx;&\text{b)}\;&\int(2x^3+5x^2-7)dx;\\
\text{c)}\;&\int(x^4-3/x^2)dx;&\text{d)}\;&\int(2\sqrt x+3/x)dx.
\end{aligned}$$

**Công thức:** Tính tuyến tính $\int(af+bg)=a\int f+b\int g$ và bảng lũy thừa, logarit.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&3\frac{x^3}{3}-4\frac{x^2}{2}+5x+C=x^3-2x^2+5x+C;\\
\text{b)}\;&2\frac{x^4}{4}+5\frac{x^3}{3}-7x+C=\frac{x^4}{2}+\frac{5x^3}{3}-7x+C;\\
\text{c)}\;&\frac{x^5}{5}-3(-x^{-1})+C=\frac{x^5}{5}+\frac3x+C;\\
\text{d)}\;&2\frac23x^{3/2}+3\ln x+C=\frac43x^{3/2}+3\ln x+C.
\end{aligned}$$

### Bài 10

**Đề:** Tính $\int(2x+1)^2dx$, $\int x(x^2+3)dx$, $\int\frac{x^4+2x^2+1}{x^2}dx$, $\int\frac{(x+1)(x-2)}x dx$.

**Công thức:** Khai triển/chia từng hạng tử trước khi áp dụng bảng nguyên hàm.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\int(4x^2+4x+1)dx=\frac43x^3+2x^2+x+C;\\
\text{b)}\;&\int(x^3+3x)dx=\frac{x^4}{4}+\frac32x^2+C;\\
\text{c)}\;&\int(x^2+2+x^{-2})dx=\frac{x^3}{3}+2x-\frac1x+C;\\
\text{d)}\;&\int(x-1-2/x)dx=\frac{x^2}{2}-x-2\ln|x|+C.
\end{aligned}$$

## Dạng 3. Nguyên hàm hàm lượng giác

### Bài 11

**Đề:** Tính $\int\sin xdx$, $\int\cos xdx$, $\int\frac{dx}{\cos^2 x}$, $\int\frac{dx}{\sin^2 x}$.

**Công thức:** $\int\sin x=-\cos x+C$, $\int\cos x=\sin x+C$, $\int\sec^2x=\tan x+C$, $\int\csc^2x=-\cot x+C$.

**Lời giải:** Áp dụng trực tiếp:

$$\begin{aligned}
\text{a)}\;&-\cos x+C;&\text{b)}\;&\sin x+C;\\
\text{c)}\;&\tan x+C;&\text{d)}\;&-\cot x+C.
\end{aligned}$$

### Bài 12

**Đề:** Tính $\int(3\sin x-2\cos x)dx$, $\int(5\cos x+4\sin x)dx$, $\int(2+3/\cos^2x)dx$, $\int(\sin x-2/\sin^2x)dx$.

**Công thức:** Tính tuyến tính và bảng lượng giác Bài 11.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&3(-\cos x)-2\sin x+C=-3\cos x-2\sin x+C;\\
\text{b)}\;&5\sin x+4(-\cos x)+C=5\sin x-4\cos x+C;\\
\text{c)}\;&2x+3\tan x+C;\\
\text{d)}\;&-\cos x-2(-\cot x)+C=-\cos x+2\cot x+C.
\end{aligned}$$

### Bài 13

**Đề:** Tính $\int\sin2x\,dx$, $\int\cos3x\,dx$, $\int\sin(4x+1)dx$, $\int\cos(5x-2)dx$.

**Công thức:** $\int\sin(ax+b)dx=-\cos(ax+b)/a+C$; $\int\cos(ax+b)dx=\sin(ax+b)/a+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&-\frac12\cos2x+C;&\text{b)}\;&\frac13\sin3x+C;\\
\text{c)}\;&-\frac14\cos(4x+1)+C;&\text{d)}\;&\frac15\sin(5x-2)+C.
\end{aligned}$$

### Bài 14

**Đề:** Tính $\int\frac{dx}{\cos^2(2x)}$, $\int\frac{dx}{\sin^2(3x)}$, $\int(2\sin3x-3\cos2x)dx$, $\int(4\cos(2x+1)+2/\cos^2x)dx$.

**Công thức:** $\int\frac{dx}{\cos^2(ax+b)}=\tan(ax+b)/a+C$, $\int\frac{dx}{\sin^2(ax+b)}=-\cot(ax+b)/a+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\frac12\tan2x+C;\\
\text{b)}\;&-\frac13\cot3x+C;\\
\text{c)}\;&-\frac23\cos3x-\frac32\sin2x+C;\\
\text{d)}\;&2\sin(2x+1)+2\tan x+C.
\end{aligned}$$

### Bài 15

**Đề:** Tính $\int\sin^2x dx$, $\int\cos^2x dx$, $\int\sin x\cos xdx$, $\int\sin^3x\cos xdx$.

**Công thức:** $\sin^2x=(1-\cos2x)/2$, $\cos^2x=(1+\cos2x)/2$, $(\sin^n x)'=n\sin^{n-1}x\cos x$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\frac12\int(1-\cos2x)dx=\frac x2-\frac{\sin2x}{4}+C;\\
\text{b)}\;&\frac12\int(1+\cos2x)dx=\frac x2+\frac{\sin2x}{4}+C;\\
\text{c)}\;&\frac12\int2\sin x\cos xdx=\frac{\sin^2x}{2}+C;\\
\text{d)}\;&\frac14\int4\sin^3x\cos xdx=\frac{\sin^4x}{4}+C.
\end{aligned}$$

---
# PHẦN B. THÔNG HIỂU

## Dạng 4. Nguyên hàm hàm số mũ

### Bài 16

**Đề:** Tính $\int e^xdx$, $\int2^xdx$, $\int5^xdx$, $\int(3e^x-2^x)dx$.

**Công thức:** $\int e^xdx=e^x+C$; $\int a^xdx=a^x/\ln a+C$ ($a>0$, $a\ne1$).

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&e^x+C;&\text{b)}\;&\frac{2^x}{\ln2}+C;\\
\text{c)}\;&\frac{5^x}{\ln5}+C;&\text{d)}\;&3e^x-\frac{2^x}{\ln2}+C.
\end{aligned}$$

### Bài 17

**Đề:** Tính $\int e^{2x}dx$, $\int e^{-3x}dx$, $\int2^{3x}dx$, $\int5^{2x-1}dx$.

**Công thức:** $\int e^{ax+b}dx=e^{ax+b}/a+C$; $\int q^{ax+b}dx=q^{ax+b}/(a\ln q)+C$.

**Lời giải:** Chia thêm cho đạo hàm của số mũ:

$$\begin{aligned}
\text{a)}\;&\frac12e^{2x}+C;&\text{b)}\;&-\frac13e^{-3x}+C;\\
\text{c)}\;&\frac{2^{3x}}{3\ln2}+C;&\text{d)}\;&\frac{5^{2x-1}}{2\ln5}+C.
\end{aligned}$$

### Bài 18

**Đề:** Tính $\int(e^{2x}+3e^{-x})dx$, $\int(2^x+3^x)dx$, $\int(4e^{3x}-2e^{-2x})dx$, $\int(3^{x+1}-2^{2x})dx$.

**Công thức:** Tính tuyến tính và công thức nguyên hàm mũ hợp tuyến tính.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\frac12e^{2x}+3(-e^{-x})+C=\frac12e^{2x}-3e^{-x}+C;\\
\text{b)}\;&\frac{2^x}{\ln2}+\frac{3^x}{\ln3}+C;\\
\text{c)}\;&4\frac{e^{3x}}3-2\left(-\frac{e^{-2x}}2\right)+C=\frac43e^{3x}+e^{-2x}+C;\\
\text{d)}\;&\frac{3^{x+1}}{\ln3}-\frac{2^{2x}}{2\ln2}+C.
\end{aligned}$$

### Bài 19

**Đề:** Rút gọn và tìm $\int2^x4^xdx$, $\int8^x/2^xdx$, $\int e^{2x}e^{3x}dx$, $\int3^{2x}/3^xdx$.

**Công thức:** $a^ma^n=a^{m+n}$; $a^m/a^n=a^{m-n}$; $\int a^xdx=a^x/\ln a+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&2^x4^x=8^x\Rightarrow\int\cdots dx=\frac{8^x}{\ln8}+C;\\
\text{b)}\;&8^x/2^x=4^x\Rightarrow\int\cdots dx=\frac{4^x}{\ln4}+C;\\
\text{c)}\;&e^{2x}e^{3x}=e^{5x}\Rightarrow\int\cdots dx=\frac15e^{5x}+C;\\
\text{d)}\;&3^{2x}/3^x=3^x\Rightarrow\int\cdots dx=\frac{3^x}{\ln3}+C.
\end{aligned}$$

### Bài 20

**Đề:** Tính $\int(e^x+1)^2dx$, $\int(2^x+1)^2dx$, $\int(e^x-e^{-x})^2dx$, $\int(3^x-3^{-x})^2dx$.

**Công thức:** $(a\pm b)^2=a^2\pm2ab+b^2$ rồi nguyên hàm từng số hạng.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\int(e^{2x}+2e^x+1)dx=\frac12e^{2x}+2e^x+x+C;\\
\text{b)}\;&\int(4^x+2\cdot2^x+1)dx=\frac{4^x}{\ln4}+\frac{2^{x+1}}{\ln2}+x+C;\\
\text{c)}\;&\int(e^{2x}-2+e^{-2x})dx=\frac12e^{2x}-2x-\frac12e^{-2x}+C;\\
\text{d)}\;&\int(9^x-2+9^{-x})dx=\frac{9^x}{\ln9}-2x-\frac{9^{-x}}{\ln9}+C.
\end{aligned}$$

## Dạng 5. Nguyên hàm hàm hợp tuyến tính

### Bài 21

**Đề:** Tính $\int(2x+3)^4dx$, $\int(3x-1)^5dx$, $\int\sqrt{2x+1}dx$, $\int dx/(3x+2)^2$.

**Công thức:** $\int(ax+b)^ndx=(ax+b)^{n+1}/[a(n+1)]+C$ ($n\ne-1$).

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\frac{(2x+3)^5}{2\cdot5}+C=\frac{(2x+3)^5}{10}+C;\\
\text{b)}\;&\frac{(3x-1)^6}{3\cdot6}+C=\frac{(3x-1)^6}{18}+C;\\
\text{c)}\;&\frac{(2x+1)^{3/2}}{2\cdot(3/2)}+C=\frac{(2x+1)^{3/2}}3+C;\\
\text{d)}\;&\frac{(3x+2)^{-1}}{3(-1)}+C=-\frac1{3(3x+2)}+C.
\end{aligned}$$

### Bài 22

**Đề:** Tính $\int dx/(2x+1)$, $\int3dx/(4x-1)$, $\int2dx/(5-3x)$, $\int(6x+2)/(3x+1)dx$.

**Công thức:** $\int dx/(ax+b)=\ln|ax+b|/a+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\frac12\ln|2x+1|+C;\\
\text{b)}\;&\frac34\ln|4x-1|+C;\\
\text{c)}\;&-\frac23\ln|5-3x|+C;\\
\text{d)}\;&\frac{6x+2}{3x+1}=2\Rightarrow\int2dx=2x+C.
\end{aligned}$$

### Bài 23

**Đề:** Tính $\int e^{4x+1}dx$, $\int2^{3x-2}dx$, $\int\sin(5x+1)dx$, $\int\cos(2-3x)dx$.

**Công thức:** $\int e^{ax+b}dx=e^{ax+b}/a+C$, $\int\sin(ax+b)dx=-\cos(ax+b)/a+C$, tương tự đối với cos.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\frac14e^{4x+1}+C; &\text{b)}\;&\frac{2^{3x-2}}{3\ln2}+C;\\
\text{c)}\;&-\frac15\cos(5x+1)+C;&\text{d)}\;&-\frac13\sin(2-3x)+C.
\end{aligned}$$

Ở ý (d), hệ số $-1/3$ xuất hiện vì $(2-3x)'=-3$.

### Bài 24

**Đề:** Tính $\int[2(3x+1)^2-4]dx$, $\int[e^{2x}+2/(3x+1)]dx$, $\int[3\sin2x+2\cos3x]dx$, $\int[2^{x+1}+1/(x+2)]dx$.

**Công thức:** Tính tuyến tính kết hợp nguyên hàm hàm hợp tuyến tính.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&2\frac{(3x+1)^3}{3\cdot3}-4x+C=\frac29(3x+1)^3-4x+C;\\
\text{b)}\;&\frac12e^{2x}+\frac23\ln|3x+1|+C;\\
\text{c)}\;&-\frac32\cos2x+\frac23\sin3x+C;\\
\text{d)}\;&\frac{2^{x+1}}{\ln2}+\ln|x+2|+C.
\end{aligned}$$

### Bài 25

**Đề:** Tính $\int(2x-1)(x-3)dx$, $\int(x+2)^3dx$, $\int(x+1)^2/x^2dx$, $\int(x^2+4x+5)/(x+2)dx$.

**Công thức:** Khai triển, chia đa thức hoặc dùng công thức hàm hợp tuyến tính.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&\int(2x^2-7x+3)dx=\frac23x^3-\frac72x^2+3x+C;\\
\text{b)}\;&\int(x+2)^3dx=\frac{(x+2)^4}{4}+C;\\
\text{c)}\;&\int(1+2/x+1/x^2)dx=x+2\ln|x|-\frac1x+C;\\
\text{d)}\;&\frac{x^2+4x+5}{x+2}=x+2+\frac1{x+2}\\
&\Rightarrow \int\cdots dx=\frac{x^2}{2}+2x+\ln|x+2|+C.
\end{aligned}$$

## Dạng 6. Nguyên hàm hàm hợp tổng quát (mở rộng)

### Bài 26

**Đề:** Tính $\int2x(x^2+1)^4dx$, $\int3x^2(x^3-2)^5dx$, $\int(2x+1)(x^2+x+3)^3dx$, $\int x/(x^2+4)^2dx$.

**Công thức:** $\int u'(x)[u(x)]^n dx=[u(x)]^{n+1}/(n+1)+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&u=x^2+1,\ u'=2x\Rightarrow\frac{(x^2+1)^5}{5}+C;\\
\text{b)}\;&u=x^3-2,\ u'=3x^2\Rightarrow\frac{(x^3-2)^6}{6}+C;\\
\text{c)}\;&u=x^2+x+3,\ u'=2x+1\Rightarrow\frac{(x^2+x+3)^4}{4}+C;\\
\text{d)}\;&u=x^2+4,\ du=2x\,dx,\\
&\frac12\int u^{-2}du=-\frac1{2u}+C=-\frac1{2(x^2+4)}+C.
\end{aligned}$$

### Bài 27

**Đề:** Tính $\int2x/(x^2+1)dx$, $\int3x^2/(x^3+2)dx$, $\int(2x+3)/(x^2+3x+5)dx$, $\int e^x/(e^x+1)dx$.

**Công thức:** $\int\frac{u'(x)}{u(x)}dx=\ln|u(x)|+C$ ($u\ne0$).

**Lời giải:** Chọn mẫu số làm $u$, tử số là $u'$:

$$\begin{aligned}
\text{a)}\;&u=x^2+1\Rightarrow\ln(x^2+1)+C;\\
\text{b)}\;&u=x^3+2\Rightarrow\ln|x^3+2|+C;\\
\text{c)}\;&u=x^2+3x+5\Rightarrow\ln(x^2+3x+5)+C;\\
\text{d)}\;&u=e^x+1\Rightarrow\ln(e^x+1)+C.
\end{aligned}$$

Ở ý (c), $x^2+3x+5=(x+3/2)^2+11/4>0$ nên không cần dấu giá trị tuyệt đối.

### Bài 28

**Đề:** Tính $\int2xe^{x^2}dx$, $\int3x^2e^{x^3+1}dx$, $\int2x\cos(x^2)dx$, $\int3x^2\sin(x^3+2)dx$.

**Công thức:** $\int u'e^u dx=e^u+C$; $\int u'\cos u\,dx=\sin u+C$; $\int u'\sin u\,dx=-\cos u+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&u=x^2,\ du=2x\,dx\Rightarrow e^{x^2}+C;\\
\text{b)}\;&u=x^3+1,\ du=3x^2dx\Rightarrow e^{x^3+1}+C;\\
\text{c)}\;&u=x^2,\ du=2x\,dx\Rightarrow\sin(x^2)+C;\\
\text{d)}\;&u=x^3+2,\ du=3x^2dx\Rightarrow-\cos(x^3+2)+C.
\end{aligned}$$

### Bài 29

**Đề:** Tính $\int\sin x\cos xdx$, $\int\sin^2x\cos xdx$, $\int\cos^3x\sin xdx$, $\int\cos x/(1+\sin x)dx$.

**Công thức:** Đặt $u=\sin x$ hoặc $u=\cos x$; dùng $\int u^ndu=u^{n+1}/(n+1)+C$ và $\int du/u=\ln|u|+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&u=\sin x\Rightarrow\int udu=\frac12\sin^2x+C;\\
\text{b)}\;&u=\sin x\Rightarrow\int u^2du=\frac13\sin^3x+C;\\
\text{c)}\;&u=\cos x,\ du=-\sin xdx\Rightarrow-\int u^3du=-\frac14\cos^4x+C;\\
\text{d)}\;&u=1+\sin x,\ du=\cos xdx\Rightarrow\ln|1+\sin x|+C.
\end{aligned}$$

### Bài 30

**Đề:** Tính $\int x\sqrt{x^2+1}dx$, $\int x/\sqrt{x^2+4}dx$, $\int(2x+1)/\sqrt{x^2+x+1}dx$, $\int x^3/(x^4+1)dx$.

**Công thức:** $\int u'\sqrt u\,dx=\frac23u^{3/2}+C$; $\int u'/\sqrt u\,dx=2\sqrt u+C$; $\int u'/u=\ln|u|+C$.

**Lời giải:**

$$\begin{aligned}
\text{a)}\;&u=x^2+1,\ du=2x\,dx:\quad\frac12\cdot\frac23u^{3/2}=\frac13(x^2+1)^{3/2}+C;\\
\text{b)}\;&u=x^2+4,\ du=2x\,dx:\quad\frac12\cdot2\sqrt u=\sqrt{x^2+4}+C;\\
\text{c)}\;&u=x^2+x+1,\ du=(2x+1)dx:\quad2\sqrt{x^2+x+1}+C;\\
\text{d)}\;&u=x^4+1,\ du=4x^3dx:\quad\frac14\ln(x^4+1)+C.
\end{aligned}$$

---
# PHẦN C. VẬN DỤNG

## Dạng 7. Nguyên hàm thỏa mãn điều kiện

### Bài 31

**Đề:** Tìm $F(x)$ biết $F'(x)=3x^2-4x+2$, $F(1)=5$.

**Công thức:** Nếu $F'=f$ thì $F=\int f(x)dx$; thay điều kiện tìm $C$.

**Lời giải:**

$$F(x)=\int(3x^2-4x+2)dx=x^3-2x^2+2x+C.$$

Vì $F(1)=5$ nên $1-2+2+C=5\Rightarrow C=4$.

**Kết luận:** $\boxed{F(x)=x^3-2x^2+2x+4.}$

### Bài 32

**Đề:** Tìm $F$ trên $(0,+\infty)$ biết $F'(x)=2x+1/x$, $F(1)=3$.

**Công thức:** $\int x^n dx=x^{n+1}/(n+1)+C$; $\int dx/x=\ln x+C$ với $x>0$.

**Lời giải:**

$$F(x)=\int(2x+1/x)dx=x^2+\ln x+C.$$

Thay $x=1$: $3=1+0+C\Rightarrow C=2$.

**Kết luận:** $\boxed{F(x)=x^2+\ln x+2.}$

### Bài 33

**Đề:** Tìm $F$ biết $F'(x)=e^{2x}-3\sin x$, $F(0)=2$.

**Công thức:** $\int e^{ax}dx=e^{ax}/a+C$; $\int\sin xdx=-\cos x+C$.

**Lời giải:**

$$F(x)=\frac12e^{2x}+3\cos x+C.$$

$$F(0)=\frac12+3+C=2\Rightarrow C=-\frac32.$$

**Kết luận:** $\boxed{F(x)=\frac12e^{2x}+3\cos x-\frac32.}$

### Bài 34

**Đề:** $F$ là nguyên hàm của $f(x)=2/(2x+1)$ trên $(-1/2,+\infty)$, $F(0)=1$. Tính $F(2)$.

**Công thức:** $\int\frac{u'}u dx=\ln|u|+C$.

**Lời giải:** Với $u=2x+1>0$,

$$F(x)=\ln(2x+1)+C.$$

$F(0)=\ln1+C=1\Rightarrow C=1$. Do đó

$$\boxed{F(2)=\ln5+1.}$$

### Bài 35

**Đề:** $F$ là nguyên hàm của $f(x)=1/x+x^2$ trên $(0,+\infty)$, $F(1)=2$. Tính $F(e)$.

**Công thức:** $\int dx/x=\ln x+C$; $\int x^2dx=x^3/3+C$.

**Lời giải:**

$$F(x)=\ln x+\frac{x^3}{3}+C.$$

$$F(1)=0+\frac13+C=2\Rightarrow C=\frac53.$$

$$F(e)=1+\frac{e^3}{3}+\frac53=\boxed{\frac{e^3+8}{3}}.$$

## Dạng 8. Tìm tham số trong bài toán nguyên hàm

### Bài 36

**Đề:** Tìm $m$ để $F=mx^3+(m+1)x^2+2$ là nguyên hàm của $f=6x^2+6x$.

**Công thức:** $F'=f$ với mọi $x$ nên hệ số các lũy thừa tương ứng bằng nhau.

**Lời giải:**

$$F'=3mx^2+2(m+1)x=6x^2+6x.$$

Suy ra $3m=6$, $2(m+1)=6$. Hai điều kiện đều cho $\boxed{m=2}$.

### Bài 37

**Đề:** Tìm $a,b$ để $F=ax^3+bx^2+5x+1$ là nguyên hàm của $f=6x^2-4x+5$.

**Công thức:** Đồng nhất hệ số trong đẳng thức $F'=f$.

**Lời giải:**

$$F'=3ax^2+2bx+5.$$

$$\begin{cases}3a=6,\\2b=-4.\end{cases}\Rightarrow\boxed{a=2,\quad b=-2.}$$

### Bài 38

**Đề:** $F'=2x+m$ trên $\mathbb R$ và $F(0)=1$, $F(2)=9$. Tìm $m$.

**Công thức:** $F=\int F'dx$; hai giá trị của $F$ xác định $m$.

**Lời giải:**

$$F(x)=x^2+mx+C.$$

$F(0)=1\Rightarrow C=1$. Dùng $F(2)=9$:

$$4+2m+1=9\Rightarrow2m=4\Rightarrow\boxed{m=2.}$$

### Bài 39

**Đề:** Tìm $m$ để $F=mx^3-3mx^2+2x+1$ là nguyên hàm của $f=3x^2-6x+2$.

**Công thức:** $F'=f$.

**Lời giải:**

$$F'=3mx^2-6mx+2.$$

Đồng nhất $3m=3$ và $-6m=-6$, suy ra $\boxed{m=1}$.

### Bài 40

**Đề:** $f(x)=x^2+mx+1$; nguyên hàm $F$ thỏa $F(0)=2$, $F(1)=5$. Tìm $m,F(x)$.

**Công thức:** Nguyên hàm từng số hạng rồi thế điều kiện.

**Lời giải:**

$$F(x)=\frac{x^3}{3}+\frac{mx^2}{2}+x+C.$$

$F(0)=2\Rightarrow C=2$. Khi $x=1$:

$$\frac13+\frac m2+1+2=5\Rightarrow\frac m2=\frac53\Rightarrow m=\frac{10}{3}.$$

**Kết luận:**

$$\boxed{m=\frac{10}{3},\quad F(x)=\frac{x^3}{3}+\frac{5x^2}{3}+x+2.}$$

## Dạng 9. Tìm hàm số từ đạo hàm cấp một, cấp hai

### Bài 41

**Đề:** Tìm $f$ biết $f'(x)=6x^2-4x+1$, $f(0)=3$.

**Công thức:** $f=\int f'dx$.

**Lời giải:**

$$f(x)=2x^3-2x^2+x+C.$$

$f(0)=C=3$. Vậy $\boxed{f(x)=2x^3-2x^2+x+3.}$

### Bài 42

**Đề:** $f''(x)=6x$, $f'(0)=2$, $f(0)=1$. Tìm $f(x)$.

**Công thức:** Nguyên hàm hai lần $f''\rightarrow f'\rightarrow f$.

**Lời giải:**

$$f'(x)=\int6x\,dx=3x^2+C_1.$$

$f'(0)=2\Rightarrow C_1=2$. Tiếp tục:

$$f(x)=\int(3x^2+2)dx=x^3+2x+C_2.$$

$f(0)=1\Rightarrow C_2=1$. Vậy $\boxed{f(x)=x^3+2x+1.}$

### Bài 43

**Đề:** $f''(x)=12x^2-4$, $f'(1)=3$, $f(0)=2$. Tìm $f$.

**Công thức:** Nguyên hàm hai lần, giữ **hai hằng số** $C_1,C_2$.

**Lời giải:**

$$f'(x)=4x^3-4x+C_1.$$

$$f'(1)=4-4+C_1=3\Rightarrow C_1=3.$$

$$f(x)=x^4-2x^2+3x+C_2.$$

$f(0)=2\Rightarrow C_2=2$. Vậy $\boxed{f(x)=x^4-2x^2+3x+2.}$

### Bài 44

**Đề:** $f''(x)=e^x$, $f'(0)=1$, $f(0)=2$. Tìm $f$.

**Công thức:** $\int e^xdx=e^x+C$.

**Lời giải:**

$$f'(x)=e^x+C_1.$$

$f'(0)=1+C_1=1\Rightarrow C_1=0$. Do đó

$$f(x)=e^x+C_2.$$

$f(0)=1+C_2=2\Rightarrow C_2=1$. Vậy $\boxed{f(x)=e^x+1.}$

### Bài 45

**Đề:** $f''(x)=2\cos x$, $f'(0)=3$, $f(0)=1$. Tìm $f$.

**Công thức:** $\int\cos xdx=\sin x+C$; $\int\sin xdx=-\cos x+C$.

**Lời giải:**

$$f'(x)=2\sin x+C_1.$$

$f'(0)=C_1=3$, nên

$$f(x)=-2\cos x+3x+C_2.$$

$f(0)=-2+C_2=1\Rightarrow C_2=3$. Vậy $\boxed{f(x)=-2\cos x+3x+3.}$

## Dạng 10. Nguyên hàm của hàm số từng đoạn

**Nguyên tắc chung:** Tìm nguyên hàm trên từng nhánh; dùng điều kiện đạo hàm $F'=f$, tính liên tục của $F$ tại điểm ghép và điều kiện cho trước để xác định các hằng số. Các hàm $f$ ở Bài 46–50 đều liên tục tại điểm ghép nên có nguyên hàm trên $\mathbb R$.

### Bài 46

**Đề:** Tìm $F$ trên $\mathbb R$, $F'=f$, $F(0)=2$ với $f(x)=\begin{cases}2x,&x<1,\\2,&x\ge1.\end{cases}$

**Công thức:** $\int2xdx=x^2+C$, $\int2dx=2x+C$; $F(1^-)=F(1^+)$.

**Lời giải:**

$$F(x)=\begin{cases}x^2+C_1,&x<1,\\2x+C_2,&x\ge1.\end{cases}$$

Vì $0<1$, $F(0)=C_1=2$. Liên tục tại $1$:

$$1+C_1=2+C_2\Rightarrow3=2+C_2\Rightarrow C_2=1.$$

**Kết luận:**

$$\boxed{F(x)=\begin{cases}x^2+2,&x<1,\\2x+1,&x\ge1.\end{cases}}$$

### Bài 47

**Đề:** Tìm $F$ trên $\mathbb R$, $F'=f$, $F(0)=1$, $f(x)=\begin{cases}3x^2,&x<0,\\2x,&x\ge0.\end{cases}$

**Công thức:** $F$ liên tục tại $0$; $\int3x^2dx=x^3+C$, $\int2xdx=x^2+C$.

**Lời giải:**

$$F(x)=\begin{cases}x^3+C_1,&x<0,\\x^2+C_2,&x\ge0.\end{cases}$$

$F(0)=C_2=1$. Liên tục tại $0$ suy ra $C_1=C_2=1$.

$$\boxed{F(x)=\begin{cases}x^3+1,&x<0,\\x^2+1,&x\ge0.\end{cases}}$$

### Bài 48

**Đề:** $f(x)=\begin{cases}2x+1,&x<1,\\3x,&x\ge1.\end{cases}$ Tìm $F$ trên $\mathbb R$ biết $F'=f$, $F(0)=0$.

**Công thức:** Nguyên hàm theo nhánh; nối liên tục tại $x=1$.

**Lời giải:**

$$F(x)=\begin{cases}x^2+x+C_1,&x<1,\\\frac32x^2+C_2,&x\ge1.\end{cases}$$

$F(0)=C_1=0$. Tại $x=1$:

$$1+1=\frac32+C_2\Rightarrow C_2=\frac12.$$

$$\boxed{F(x)=\begin{cases}x^2+x,&x<1,\\\frac32x^2+\frac12,&x\ge1.\end{cases}}$$

### Bài 49

**Đề:** $f(x)=\begin{cases}x^2,&x<1,\\2x-1,&x\ge1.\end{cases}$ Tìm nguyên hàm $F$ trên $\mathbb R$ biết $F(2)=3$.

**Công thức:** Tính nguyên hàm từng nhánh rồi nối tại $x=1$.

**Lời giải:**

$$F(x)=\begin{cases}\frac{x^3}{3}+C_1,&x<1,\\x^2-x+C_2,&x\ge1.\end{cases}$$

Vì $2\ge1$,

$$F(2)=4-2+C_2=3\Rightarrow C_2=1.$$

Điều kiện liên tục tại $1$:

$$\frac13+C_1=(1-1)+1=1\Rightarrow C_1=\frac23.$$

$$\boxed{F(x)=\begin{cases}\frac{x^3}{3}+\frac23,&x<1,\\x^2-x+1,&x\ge1.\end{cases}}$$

### Bài 50

**Đề:** $f(x)=\begin{cases}2x+2,&x<0,\\e^x+1,&x\ge0.\end{cases}$ Tìm nguyên hàm $F$ trên $\mathbb R$ thỏa $F(0)=2$.

**Công thức:** $\int(2x+2)dx=x^2+2x+C$, $\int(e^x+1)dx=e^x+x+C$; nối liên tục tại $0$.

**Lời giải:**

$$F(x)=\begin{cases}x^2+2x+C_1,&x<0,\\e^x+x+C_2,&x\ge0.\end{cases}$$

$F(0)=1+C_2=2\Rightarrow C_2=1$.

$$F(0^-)=C_1=F(0)=2\Rightarrow C_1=2.$$

$$\boxed{F(x)=\begin{cases}x^2+2x+2,&x<0,\\e^x+x+1,&x\ge0.\end{cases}}$$

---
# PHẦN D. VẬN DỤNG CAO VÀ THỰC TẾ

## Dạng 11. Bài toán nguyên hàm tổng hợp

### Bài 51

**Đề:** Cho $F$ là nguyên hàm của $f(x)=2x+1/x$ trên $(0,+\infty)$, thỏa mãn $F(1)=3$. Giải phương trình $F(x)=4+\ln x$.

**Công thức:** $F=\int fdx$; sau khi xác định $C$, giải phương trình theo $x>0$.

**Lời giải:**

$$F(x)=x^2+\ln x+C,\qquad F(1)=1+C=3\Rightarrow C=2.$$

Do đó

$$\begin{aligned}
F(x)=4+\ln x&\iff x^2+\ln x+2=4+\ln x\\
&\iff x^2=2.
\end{aligned}$$

Vì $x>0$, **$\boxed{x=\sqrt2}$**.

### Bài 52

**Đề:** Cho $F'(x)=3x^2-6x+2$ trên $\mathbb R$, $F(1)=4$. Tìm giá trị nhỏ nhất của $F$ trên $[0,3]$.

**Công thức:** $F=\int F'dx$; xét các điểm $F'=0$ trong $[0,3]$ cùng hai đầu mút.

**Lời giải:**

$$F(x)=x^3-3x^2+2x+C.$$

$F(1)=1-3+2+C=4\Rightarrow C=4$, vậy

$$F(x)=x^3-3x^2+2x+4.$$

Giải $F'=0$:

$$3x^2-6x+2=0\iff x=1\pm\frac{\sqrt3}{3}.$$

Cả hai điểm đều thuộc $[0,3]$. Tính giá trị:

$$\begin{aligned}
F(0)&=4, & F(3)&=10,\\
F\left(1-\frac{\sqrt3}{3}\right)&=4+\frac{2\sqrt3}{9},
&F\left(1+\frac{\sqrt3}{3}\right)&=4-\frac{2\sqrt3}{9}.
\end{aligned}$$

**Kết luận:**

$$\boxed{\min_{[0,3]}F=4-\frac{2\sqrt3}{9}}$$

đạt tại $x=1+\frac{\sqrt3}{3}$.

### Bài 53

**Đề:** $F'(x)=2x-4$ trên $\mathbb R$, $F(0)=5$. Giải bất phương trình $F(x)\le1$.

**Công thức:** Nguyên hàm $F'$ rồi hoàn thành bình phương.

**Lời giải:**

$$F(x)=x^2-4x+C,\quad F(0)=5\Rightarrow C=5.$$

$$\begin{aligned}
F(x)\le1&\iff x^2-4x+5\le1\\
&\iff x^2-4x+4\le0\\
&\iff(x-2)^2\le0.
\end{aligned}$$

Bình phương chỉ không dương khi bằng $0$, nên **$\boxed{x=2}$**.

### Bài 54

**Đề:** $F$ là nguyên hàm của $f=x^2-2x+1$ trên $\mathbb R$, $F(0)=0$. Chứng minh $F(3)>F(2)>F(1)$.

**Công thức:** $F=\int fdx$; tính giá trị tại ba điểm.

**Lời giải:**

$$F(x)=\frac{x^3}{3}-x^2+x+C,\quad F(0)=0\Rightarrow C=0.$$

$$\begin{aligned}
F(1)&=\frac13-1+1=\frac13;\\
F(2)&=\frac83-4+2=\frac23;\\
F(3)&=9-9+3=3.
\end{aligned}$$

Do $3>2/3>1/3$, suy ra **$\boxed{F(3)>F(2)>F(1)}$**.

### Bài 55

**Đề:** Hai hàm $F,G$ có cùng đạo hàm $F'=G'=3x^2+2x$ trên $\mathbb R$, biết $F(1)=2$, $G(2)=7$. Tính $F(3)-G(3)$.

**Công thức:** Nếu $F'=G'$ trên cùng một khoảng thì $F-G$ là hằng số.

**Lời giải:** Nguyên hàm chung là $x^3+x^2$, vì vậy

$$F(x)=x^3+x^2+C_1,\qquad G(x)=x^3+x^2+C_2.$$

$$F(1)=1+1+C_1=2\Rightarrow C_1=0.$$

$$G(2)=8+4+C_2=7\Rightarrow C_2=-5.$$

Suy ra

$$F(3)-G(3)=C_1-C_2=0-(-5)=\boxed{5}.$$

## Dạng 12. Ứng dụng nguyên hàm trong thực tế

### Bài 56. Chuyển động thẳng

**Đề:** Một vật chuyển động trên trục $Ox$ với vận tốc $v(t)=3t^2-4t+5$ (m/s), $t$ tính bằng giây. Tọa độ ban đầu $s(0)=2$ m. (a) Tìm $s(t)$; (b) tính tọa độ sau $3$ giây.

**Công thức:** $s'(t)=v(t)$, nên $s(t)=\int v(t)dt$.

**Lời giải:**

$$s(t)=\int(3t^2-4t+5)dt=t^3-2t^2+5t+C.$$

Từ $s(0)=2$ suy ra $C=2$. Vậy

$$\boxed{s(t)=t^3-2t^2+5t+2\quad(\mathrm m).}$$

$$s(3)=27-18+15+2=\boxed{26\ \mathrm m}.$$

### Bài 57. Chuyển động có gia tốc

**Đề:** Ô tô chuyển động thẳng có gia tốc $a(t)=6t-2$ (m/s²), $v(0)=4$ m/s, $s(0)=0$ m. (a) Tìm $v(t)$; (b) tìm $s(t)$; (c) tính $s(3)$.

**Công thức:** $a=v'$, $v=s'$, nên nguyên hàm hai lần.

**Lời giải:**

$$v(t)=\int(6t-2)dt=3t^2-2t+C_1.$$

$v(0)=4\Rightarrow C_1=4$; do đó

$$\boxed{v(t)=3t^2-2t+4\quad(\mathrm{m/s}).}$$

Tiếp tục

$$s(t)=\int(3t^2-2t+4)dt=t^3-t^2+4t+C_2.$$

$s(0)=0\Rightarrow C_2=0$, vậy

$$\boxed{s(t)=t^3-t^2+4t\quad(\mathrm m),}\qquad
s(3)=27-9+12=\boxed{30\ \mathrm m}.$$

### Bài 58. Tăng trưởng vi khuẩn

**Đề:** Quần thể vi khuẩn có tốc độ thay đổi $N'(t)=200t+100$ (con/giờ), với $t$ tính bằng giờ. Ban đầu có $N(0)=500$ con. (a) Tìm $N(t)$; (b) tính $N(4)$.

**Công thức:** $N(t)=\int N'(t)dt$.

**Lời giải:**

$$N(t)=\int(200t+100)dt=100t^2+100t+C.$$

$N(0)=500\Rightarrow C=500$, do đó

$$\boxed{N(t)=100t^2+100t+500.}$$

$$N(4)=100\cdot16+100\cdot4+500=\boxed{2500\ \text{con}}.$$

### Bài 59. Chi phí sản xuất

**Đề:** Chi phí biên $C'(x)=3x^2-12x+20$ (nghìn đồng/sản phẩm); $x$ là số sản phẩm, $C(x)$ là tổng chi phí tính bằng nghìn đồng. Chi phí cố định $C(0)=500$ nghìn đồng. (a) Tìm $C(x)$; (b) tính $C(10)$.

**Công thức:** Tổng chi phí là nguyên hàm của chi phí biên: $C(x)=\int C'(x)dx$.

**Lời giải:**

$$C(x)=\int(3x^2-12x+20)dx=x^3-6x^2+20x+K.$$

$C(0)=500\Rightarrow K=500$, nên

$$\boxed{C(x)=x^3-6x^2+20x+500\quad\text{(nghìn đồng)}.}$$

$$C(10)=1000-600+200+500=\boxed{1100\ \text{nghìn đồng}}.$$

### Bài 60. Chuyển động từ gia tốc đến tọa độ

**Đề:** Một vật chuyển động thẳng có gia tốc $a(t)=12t^2-6t+2$ (m/s²), thời gian $t$ tính bằng giây. Vận tốc và tọa độ ban đầu lần lượt là $v(0)=3$ m/s, $s(0)=5$ m. (a) Tìm $v(t)$; (b) tìm $s(t)$; (c) tính tọa độ tại $t=2$ giây.

**Công thức:** $a(t)=v'(t)=s''(t)$; nguyên hàm lần một tìm $v$, lần hai tìm $s$; mỗi lần dùng một điều kiện đầu.

**Lời giải:**

**a) Vận tốc:**

$$v(t)=\int(12t^2-6t+2)dt=4t^3-3t^2+2t+C_1.$$

$v(0)=3\Rightarrow C_1=3$. Vậy

$$\boxed{v(t)=4t^3-3t^2+2t+3\quad(\mathrm{m/s}).}$$

**b) Tọa độ:**

$$s(t)=\int(4t^3-3t^2+2t+3)dt=t^4-t^3+t^2+3t+C_2.$$

$s(0)=5\Rightarrow C_2=5$. Vậy

$$\boxed{s(t)=t^4-t^3+t^2+3t+5\quad(\mathrm m).}$$

**c) Tại $t=2$:**

$$s(2)=16-8+4+6+5=\boxed{23\ \mathrm m}.$$

---

## Ghi nhớ khi làm bài

- **Nguyên hàm bất định:** luôn ghi $+C$ và xét trên từng khoảng xác định.
- **Nguyên hàm có điều kiện:** tính $F(x)$ trước, sau đó mới dùng điều kiện tìm $C$.
- **Đạo hàm cấp hai:** lấy nguyên hàm hai lần và có hai hằng số cần xác định.
- **Hàm từng đoạn:** phải ghép các công thức để nguyên hàm liên tục (và khả vi) tại điểm chuyển nhánh.
- **Ứng dụng:** $a=v'$, $v=s'$; kiểm tra đơn vị đại lượng sau tính toán.

**HẾT – 60/60 BÀI GIẢI.**