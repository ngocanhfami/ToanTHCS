
Ngày 12,13/5/2026
# 🎯 I. Kiến thức cơ bản về đa thức

## 1. Khái niệm

- Đa thức:
  $P(x)=a_nx^n+a_{n-1}x^{n-1}+\cdots+a_0$
- Bậc: số mũ lớn nhất (nếu hệ số ≠ 0)

👉 Ví dụ:

- $2x+1$  
- $x^2+3x+2$  
- $x^3-x$

---

## 📌 Thành phần

| Thành phần | Ý nghĩa        |
| ---------- | -------------- |
| $x$        | biến           |
| hệ số      | số đứng trước  |
| bậc        | số mũ lớn nhất |

👉 Ví dụ:

$P(x)=3x^2+2x+1$

- bậc = 2  
- hệ số cao nhất = 3  

---

# 🔥 2. Giá trị của đa thức

## 📌 Cách làm

Thay $x=a$:

$P(a)$

👉 Ví dụ:

$P(x)=x^2+1$

$P(2)=2^2+1=5$


## 🎯 Ý nghĩa

👉 giống như “cho input → ra output”

---

# ⚡ 3. Phép toán với đa thức

---

## 🟢 Cộng trừ

Cộng các hạng tử cùng loại:

$(2x^2+3x)+(x^2-x)=3x^2+2x$

---

## 🔵 Nhân

$(x+1)(x+2)=x^2+3x+2$

👉 quy tắc: **nhân từng phần**

---

## 🔴 Chia (quan trọng)

Ví dụ:

$\frac{x^2-1}{x-1}$

👉 làm bằng cách **phân tích nhân tử trước**

---

# 🚀 4. Hằng đẳng thức (phải thuộc)

## 📌 Quan trọng nhất

$a^2-b^2=(a-b)(a+b)$  

$a^3-b^3=(a-b)(a^2+ab+b^2)$  

$a^3+b^3=(a+b)(a^2-ab+b^2)$  

---

## 🎯 Ví dụ

$x^2-4=(x-2)(x+2)$

---

# 🌱 5. Phân tích đa thức thành nhân tử

## 📌 Các cách

### 1. Đặt nhân tử chung

$2x+2=2(x+1)$

---

### 2. Nhóm hạng tử

$x^2+x+2x+2=(x^2+x)+(2x+2)$  

$=x(x+1)+2(x+1)$  

$=(x+2)(x+1)$  

---

### 3. Hằng đẳng thức

$x^2-1=(x-1)(x+1)$

---

# 🎯 6. Chia hết đa thức (cực quan trọng)

## 🔥 Quy tắc vàng

$P(x) \text{ chia hết cho } (x-a) \Leftrightarrow P(a)=0$

---

## 🎯 Ví dụ

$P(x)=x^2-1$

$P(1)=0 \Rightarrow \text{chia hết cho } x-1$

---

# ⚡ 7. Số dư khi chia

## 📌 Quy tắc

Số dư khi chia $P(x)$ cho $(x-a)$ là:

$P(a)$

---

## 🎯 Ví dụ

$x^{100}+1 \div (x-1)$  

$P(1)=2$  

👉 số dư = 2  

---

# 🔥 8. Mod đa thức (ý tưởng nâng cao)

Nếu:

$x^2+x+1=0$

👉 ta có:

$x^2=-x-1$

👉 dùng để **giảm bậc**

---

## 🎯 Ví dụ

$x^3 = x\cdot x^2 = x(-x-1)$

👉 tiếp tục thay



## Bài tập có lời giải 
## Bài 1

$A=\frac{x^3-1}{x^2-1}-\frac{x^2+x+1}{x+1}$

Điều kiện:

$x\ne 1,\quad x\ne -1$

Ta có:

$x^3-1=(x-1)(x^2+x+1)$

$x^2-1=(x-1)(x+1)$

Do đó:

$\frac{x^3-1}{x^2-1}=\frac{(x-1)(x^2+x+1)}{(x-1)(x+1)}=\frac{x^2+x+1}{x+1}$

Suy ra:

$A=\frac{x^2+x+1}{x+1}-\frac{x^2+x+1}{x+1}=0$

$\boxed{A=0}$

---

## Bài 2

Tìm $m$ để:

$P(x)=x^3+mx^2+(m-2)x-2$

chia hết cho $x-1$.

Theo định lý dư:

$P(x)\vdots x-1 \Longleftrightarrow P(1)=0$

Ta tính:

$P(1)=1+m+(m-2)-2=2m-3$

Điều kiện:

$2m-3=0$

$\boxed{m=\frac32}$

---

## Bài 3

Tìm số dư khi chia:

$P(x)=x^{2026}+x^{2025}+x+1$

cho $x+1$.

Theo định lý dư:

$P(-1)=(-1)^{2026}+(-1)^{2025}+(-1)+1=1-1-1+1=0$

Vậy:

$\boxed{0}$

---

## Bài 4

Chứng minh:

$n^5-n \vdots 30$

Ta có:

$n^5-n=n(n^4-1)=n(n^2-1)(n^2+1)=n(n-1)(n+1)(n^2+1)$

Vì ba số liên tiếp $n-1,n,n+1$ luôn chia hết cho 2 và 3, nên:

$n^5-n\vdots 2,\quad n^5-n\vdots 3$

Xét mod 5:

- $n\equiv 0 \Rightarrow n^5-n\vdots 5$
- $n\equiv \pm1 \Rightarrow n^2-1\vdots 5$
- $n\equiv \pm2 \Rightarrow n^2+1\vdots 5$

Suy ra:

$n^5-n\vdots 5$

Do đó:

$\boxed{n^5-n\vdots 30}$

---

## Bài 5

Tìm $m$ để:

$P(x)=x^4+mx^3+3x^2+mx+1$

chia hết cho $x^2+x+1$.

Ta có:

$x^2+x+1=0 \Rightarrow x^2=-x-1$

Suy ra:

$x^3=1,\quad x^4=x$

Thay vào:

$P(x)\equiv x+m+3(-x-1)+mx+1$

$=x+m-3x-3+mx+1=(m-2)x+(m-2)$

$=(m-2)(x+1)$

Điều kiện:

$m-2=0$

$\boxed{m=2}$

---

## Bài 6

Tìm $x\in\mathbb Z$ để:

$A=\frac{x^2+5x+7}{x+2}$

là số nguyên.

Điều kiện:

$x\ne -2$

Ta có:

$x^2+5x+7=(x+2)(x+3)+1$

Suy ra:

$A=x+3+\frac{1}{x+2}$

Để $A\in\mathbb Z$:

$x+2\mid 1$

$\Rightarrow x+2=\pm1$

$\Rightarrow x=-1,\,-3$

$\boxed{x\in\{-3,-1\}}$

---

## Bài 7

Phân tích:

$x^4+4$

Ta thêm bớt:

$x^4+4=x^4+4x^2+4-4x^2=(x^2+2)^2-(2x)^2$

$=(x^2-2x+2)(x^2+2x+2)$

$\boxed{x^4+4=(x^2-2x+2)(x^2+2x+2)}$

---

## Bài 8

Cho:

$P(x)=x^4+ax^3+bx^2+ax+1$

chia hết cho $x^2+x+1$.

Ta có:

$x^2=-x-1,\quad x^3=1,\quad x^4=x$

Thay vào:

$P(x)\equiv x+a+b(-x-1)+ax+1$

$=x+a-bx-b+ax+1=(a+1-b)x+(a+1-b)$

$=(a+1-b)(x+1)$

Điều kiện:

$a+1-b=0$

$\boxed{b=a+1}$

---

## Bài 9

Tìm $m\in\mathbb Z$ để:

$P(x)=x^3+mx^2+(m+1)x+1$

chia hết cho $x+1$.

Ta có:

$P(-1)=-1+m-m-1+1=-1\ne 0$

$\boxed{\text{Không tồn tại }m}$

---

## Bài 10

Chứng minh:

$\frac{x^6-1}{x^2-1}$ là số nguyên.

Ta có:

$x^6-1=(x^2)^3-1=(x^2-1)(x^4+x^2+1)$

Suy ra:

$\frac{x^6-1}{x^2-1}=x^4+x^2+1$

Vì $x\in\mathbb Z$ nên:

$x^4+x^2+1\in\mathbb Z$
# 🎲 Bài tập tự giải cơ bản

## Bài 1

Rút gọn:  
$\frac{x^2-4}{x-2}$  

---

## Bài 2

Tìm $m$:  
$x^2+mx+1 \text{ chia hết cho } x-1$  

---

## Bài 3

Tính số dư:  
$x^{50}+1 \div (x-1)$  

---

## Bài 4

Phân tích:  
$x^2+3x+2$  
