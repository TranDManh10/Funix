## CHỦ ĐỀ 1: HÀM SỐ LƯỢNG GIÁC VÀ PHƯƠNG TRÌNH LƯỢNG GIÁC

### 1. Giá trị lượng giác của góc lượng giác

**Bảng 1.1: Công thức độ dài cung tròn và hệ thức lượng giác cơ bản**

| **Nội dung**                      | **Công thức**                                | **Điều kiện / Ghi chú**                                  |
| --------------------------------- | -------------------------------------------- | -------------------------------------------------------- |
| **Độ dài cung tròn bán kính $R$** | $l = R \cdot \alpha$                         | $\alpha$ tính bằng radian ($0 \le \alpha \le 2\pi$)      |
|                                   | $l = \dfrac{\pi a}{180} R$                   | $a$ tính bằng độ ($0^\circ \le a \le 360^\circ$)         |
| **Hệ thức cơ bản 1**              | $\sin^2\alpha + \cos^2\alpha = 1$            | $\forall \alpha \in \mathbb{R}$                          |
| **Hệ thức cơ bản 2**              | $1 + \tan^2\alpha = \dfrac{1}{\cos^2\alpha}$ | $\alpha \neq \dfrac{\pi}{2} + k\pi \ (k \in \mathbb{Z})$ |
| **Hệ thức cơ bản 3**              | $1 + \cot^2\alpha = \dfrac{1}{\sin^2\alpha}$ | $\alpha \neq k\pi \ (k \in \mathbb{Z})$                  |
| **Hệ thức cơ bản 4**              | $\tan\alpha \cdot \cot\alpha = 1$            | $\alpha \neq \dfrac{k\pi}{2} \ (k \in \mathbb{Z})$       |
**Bảng 1.2: Dấu của các giá trị lượng giác theo góc phần tư**

| **Giá trị lượng giác** | Góc phần tư I<br>$\left(0 < \alpha < \dfrac{\pi}{2}\right)$ | Góc phần tư II<br>$\left(\dfrac{\pi}{2} < \alpha < \pi\right)$ | Góc phần tư III<br>$\left(\pi < \alpha < \dfrac{3\pi}{2}\right)$ | Góc phần tư IV<br>$\left(\dfrac{3\pi}{2} < \alpha < 2\pi\right)$ |
| ---------------------- | ----------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------------------------------------------------- |
| $\cos\alpha$           | $+$                                                         | $-$                                                            | $-$                                                              | $+$                                                              |
| $\sin\alpha$           | $+$                                                         | $+$                                                            | $-$                                                              | $-$                                                              |
| $\tan\alpha$           | $+$                                                         | $-$                                                            | $+$                                                              | $-$                                                              |
| $\cot\alpha$           | $+$                                                         | $-$                                                            | $+$                                                              | $-$                                                              |

**Bảng 1.3: Giá trị lượng giác của các góc đặc biệt**

| Góc $\alpha$ (rad / độ) | $0$ / $0^\circ$ | $\dfrac{\pi}{6}$ / $30^\circ$ | $\dfrac{\pi}{4}$ / $45^\circ$ | $\dfrac{\pi}{3}$ / $60^\circ$ | $\dfrac{\pi}{2}$ / $90^\circ$ |
| ----------------------- | --------------- | ----------------------------- | ----------------------------- | ----------------------------- | ----------------------------- |
| $\sin\alpha$            | $0$             | $\dfrac{1}{2}$                | $\dfrac{\sqrt{2}}{2}$         | $\dfrac{\sqrt{3}}{2}$         | $1$                           |
| $\cos\alpha$            | $1$             | $\dfrac{\sqrt{3}}{2}$         | $\dfrac{\sqrt{2}}{2}$         | $\dfrac{1}{2}$                | $0$                           |
| $\tan\alpha$            | $0$             | $\dfrac{1}{\sqrt{3}}$         | $1$                           | $\sqrt{3}$                    | Không xác định                |
| $\cot\alpha$            | Không xác định  | $\sqrt{3}$                    | $1$                           | $\dfrac{1}{\sqrt{3}}$         | $0$                           |

**Bảng 1.4: Giá trị lượng giác của các góc có liên quan đặc biệt**

| **Hệ thức** | Góc đối nhau<br>($\alpha$ và $-\alpha$) | Góc bù nhau<br>($\alpha$ và $\pi - \alpha$) | Góc phụ nhau<br>$\left(\alpha \text{ và } \dfrac{\pi}{2} - \alpha\right)$ | Góc hơn kém $\pi$<br>($\alpha$ và $\alpha + \pi$) |
| ----------- | --------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------- |
| **$\sin$**  | $\sin(-\alpha) = -\sin\alpha$           | $\sin(\pi - \alpha) = \sin\alpha$           | $\sin\left(\dfrac{\pi}{2} - \alpha\right) = \cos\alpha$                   | $\sin(\alpha + \pi) = -\sin\alpha$                |
| **$\cos$**  | $\cos(-\alpha) = \cos\alpha$            | $\cos(\pi - \alpha) = -\cos\alpha$          | $\cos\left(\dfrac{\pi}{2} - \alpha\right) = \sin\alpha$                   | $\cos(\alpha + \pi) = -\cos\alpha$                |
| **$\tan$**  | $\tan(-\alpha) = -\tan\alpha$           | $\tan(\pi - \alpha) = -\tan\alpha$          | $\tan\left(\dfrac{\pi}{2} - \alpha\right) = \cot\alpha$                   | $\tan(\alpha + \pi) = \tan\alpha$                 |
| **$\cot$**  | $\cot(-\alpha) = -\cot\alpha$           | $\cot(\pi - \alpha) = -\cot\alpha$          | $\cot\left(\dfrac{\pi}{2} - \alpha\right) = \tan\alpha$                   | $\cot(\alpha + \pi) = \cot\alpha$                 |
### 2. Công thức lượng giác

**Bảng 2.1: Công thức cộng, công thức nhân đôi và công thức hạ bậc**

| **Phân loại**          | **Công thức**                                                                                                                                                                                                                                                                                                                |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Công thức cộng**     | $\cos(a - b) = \cos a \cos b + \sin a \sin b$<br>$\cos(a + b) = \cos a \cos b - \sin a \sin b$<br>$\sin(a - b) = \sin a \cos b - \cos a \sin b$<br>$\sin(a + b) = \sin a \cos b + \cos a \sin b$<br>$\tan(a - b) = \dfrac{\tan a - \tan b}{1 + \tan a \tan b}$<br>$\tan(a + b) = \dfrac{\tan a + \tan b}{1 - \tan a \tan b}$ |
| **Công thức nhân đôi** | $\sin 2a = 2\sin a \cos a$<br>$\cos 2a = \cos^2 a - \sin^2 a = 2\cos^2 a - 1 = 1 - 2\sin^2 a$<br>$\tan 2a = \dfrac{2\tan a}{1 - \tan^2 a}$                                                                                                                                                                                   |
| **Công thức hạ bậc**   | $\sin^2 a = \dfrac{1 - \cos 2a}{2}$<br>$\cos^2 a = \dfrac{1 + \cos 2a}{2}$<br>$\tan^2 a = \dfrac{1 - \cos 2a}{1 + \cos 2a}$                                                                                                                                                                                                  |

**Bảng 2.2: Công thức biến đổi tích thành tổng và tổng thành tích**

|**Biến đổi tích thành tổng**|**Biến đổi tổng thành tích**|
|---|---|
|$\cos a \cos b = \dfrac{1}{2}[\cos(a - b) + \cos(a + b)]$|$\cos u + \cos v = 2\cos\dfrac{u + v}{2} \cos\dfrac{u - v}{2}$|
|$\sin a \sin b = \dfrac{1}{2}[\cos(a - b) - \cos(a + b)]$|$\cos u - \cos v = -2\sin\dfrac{u + v}{2} \sin\dfrac{u - v}{2}$|
|$\sin a \cos b = \dfrac{1}{2}[\sin(a + b) + \sin(a - b)]$|$\sin u + \sin v = 2\sin\dfrac{u + v}{2} \cos\dfrac{u - v}{2}$|
||$\sin u - \sin v = 2\cos\dfrac{u + v}{2} \sin\dfrac{u - v}{2}$|

### 3. Hàm số lượng giác

**Bảng 3.1: Tập xác định và tính chất của các hàm số lượng giác**

|**Hàm số**|**Tập xác định (D)**|**Tập giá trị (T)**|**Tính chẵn / lẻ**|**Chu kì tuần hoàn (T0​)**|
|---|---|---|---|---|
|$y = \sin x$|$D = \mathbb{R}$|$[-1; 1]$|Hàm số lẻ|$T_0 = 2\pi$|
|$y = \cos x$|$D = \mathbb{R}$|$[-1; 1]$|Hàm số chẵn|$T_0 = 2\pi$|
|$y = \tan x$|$D = \mathbb{R} \setminus \left\{\dfrac{\pi}{2} + k\pi \ \middle\vert{} \ k \in \mathbb{Z}\right\}$|$\mathbb{R}$|Hàm số lẻ|$T_0 = \pi$|
|$y = \cot x$|$D = \mathbb{R} \setminus \left\{k\pi \ \middle\vert{} \ k \in \mathbb{Z}\right\}$|$\mathbb{R}$|Hàm số lẻ|$T_0 = \pi$|

### 4. Phương trình lượng giác cơ bản

**Bảng 4.1: Công thức nghiệm của phương trình lượng giác cơ bản ($k \in \mathbb{Z}$)**

| **Phương trình** | **Điều kiện có nghiệm**                                | **Công thức nghiệm (Radian)**                                                              | **Công thức nghiệm (Độ)**                                                                                    |
| ---------------- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| **$\sin x = m$** | $\vert{}m\vert{} \le 1$<br>_(Đặt $m = \sin\alpha$)_    | $\left[\begin{array}{l} x = \alpha + k2\pi \\ x = \pi - \alpha + k2\pi \end{array}\right.$ | $\left[\begin{array}{l} x = a^\circ + k360^\circ \\ x = 180^\circ - a^\circ + k360^\circ \end{array}\right.$ |
| **$\cos x = m$** | $\vert{}m\vert{} \le 1$<br>_(Đặt $m = \cos\alpha$)_    | $x = \pm\alpha + k2\pi$                                                                    | $x = \pm a^\circ + k360^\circ$                                                                               |
| **$\tan x = m$** | $\forall m \in \mathbb{R}$<br>_(Đặt $m = \tan\alpha$)_ | $x = \alpha + k\pi$                                                                        | $x = a^\circ + k180^\circ$                                                                                   |
| **$\cot x = m$** | $\forall m \in \mathbb{R}$<br>_(Đặt $m = \cot\alpha$)_ | $x = \alpha + k\pi$                                                                        | $x = a^\circ + k180^\circ$                                                                                   |

**Bảng 4.2: Các trường hợp phương trình lượng giác đặc biệt ($k \in \mathbb{Z}$)**

| Phương trình $\sin x$ | Nghiệm ($k \in \mathbb{Z}$)   | Phương trình $\cos x$ | Nghiệm ($k \in \mathbb{Z}$) |
| --------------------- | ----------------------------- | --------------------- | --------------------------- |
| $\sin x = 0$          | $x = k\pi$                    | $\cos x = 0$          | $x = \dfrac{\pi}{2} + k\pi$ |
| $\sin x = 1$          | $x = \dfrac{\pi}{2} + k2\pi$  | $\cos x = 1$          | $x = k2\pi$                 |
| $\sin x = -1$         | $x = -\dfrac{\pi}{2} + k2\pi$ | $\cos x = -1$         | $x = \pi + k2\pi$           |

## CHỦ ĐỀ 2: DÃY SỐ. CẤP SỐ CỘNG VÀ CẤP SỐ NHÂN

### 1. Dãy số

**Bảng 5.1: Tính tăng, giảm và bị chặn của dãy số $(u_n)$**

| **Tính chất**                   | **Phân loại** | Điều kiện tương đương ($\forall n \in \mathbb{N}^*$)                                                  |
| ------------------------------- | ------------- | ----------------------------------------------------------------------------------------------------- |
| **Tính đơn điệu (Tăng / Giảm)** | Dãy số tăng   | $u_{n+1} > u_n \Longleftrightarrow u_{n+1} - u_n > 0$ (hoặc $\dfrac{u_{n+1}}{u_n} > 1$ nếu $u_n > 0$) |
|                                 | Dãy số giảm   | $u_{n+1} < u_n \Longleftrightarrow u_{n+1} - u_n < 0$ (hoặc $\dfrac{u_{n+1}}{u_n} < 1$ nếu $u_n > 0$) |
| **Tính bị chặn**                | Bị chặn trên  | $\exists M \in \mathbb{R} : u_n \le M$                                                                |
|                                 | Bị chặn dưới  | $\exists m \in \mathbb{R} : u_n \ge m$                                                                |
|                                 | Bị chặn       | $\exists m, M \in \mathbb{R} : m \le u_n \le M$ _(vừa bị chặn trên, vừa bị chặn dưới)_                |

### 2. Cấp số cộng và Cấp số nhân

**Bảng 5.2: Hệ thống công thức Cấp số cộng (CSC) và Cấp số nhân (CSN)**

| **Nội dung công thức**                  | Cấp số cộng (Công sai $d$)                                                                    | Cấp số nhân (Công bội $q$)                                                                  |
| --------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Định nghĩa (Hệ thức truy hồi)**       | $u_{n+1} = u_n + d \quad (n \in \mathbb{N}^*)$                                                | $u_{n+1} = u_n \cdot q \quad (n \in \mathbb{N}^*)$                                          |
| **Công sai / Công bội**                 | $d = u_{n+1} - u_n$                                                                           | $q = \dfrac{u_{n+1}}{u_n} \quad (u_n \neq 0)$                                               |
| **Số hạng tổng quát ($u_n$)**           | $u_n = u_1 + (n - 1)d \quad (n \ge 2)$                                                        | $u_n = u_1 \cdot q^{n-1} \quad (n \ge 2)$                                                   |
| **Liên hệ giữa số hạng $u_n$ và $u_k$** | $u_n = u_k + (n - k)d$                                                                        | $u_n = u_k \cdot q^{n-k}$                                                                   |
| **Tính chất 3 số hạng liên tiếp**       | $u_k = \dfrac{u_{k-1} + u_{k+1}}{2} \Longleftrightarrow u_{k-1} + u_{k+1} = 2u_k \ (k \ge 2)$ | $u_k^2 = u_{k-1} \cdot u_{k+1} \ (k \ge 2)$                                                 |
| **Tổng $n$ số hạng đầu tiên ($S_n$)**   | $S_n = \dfrac{n(u_1 + u_n)}{2} = \dfrac{n[2u_1 + (n - 1)d]}{2}$                               | • Với $q \neq 1$: $S_n = \dfrac{u_1(1 - q^n)}{1 - q}$<br>• Với $q = 1$: $S_n = n \cdot u_1$ |
