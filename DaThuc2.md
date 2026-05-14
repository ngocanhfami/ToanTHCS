
## Bài 1
Cho đa thức $f(x) = ax^2 + bx + c$ với $a, b, c \in \mathbb{Z}$.  
Biết $f(-1), f(0), f(1)$ chia hết cho 3. Chứng minh $f(x) \equiv 0 \pmod{3}$ với mọi $x \in \mathbb{Z}$.

### ✨ Lời giải

Ta xét modulo 3.

Vì:
- $f(0) = c \equiv 0 \Rightarrow c \equiv 0$
- $f(1) = a + b + c \equiv 0$
- $f(-1) = a - b + c \equiv 0$

Trừ hai phương trình:
$(a+b+c) - (a-b+c) = 2b \equiv 0 \Rightarrow b \equiv 0$

Thế vào:
$a + b + c \equiv 0 \Rightarrow a \equiv 0$

⇒ $a, b, c \equiv 0 \pmod{3}$

⇒ $f(x) \equiv 0 \pmod{3}, \forall x$

---

## Bài 2
Cho $f(x) = ax^2 + bx + c$. Biết $f(-1), f(0), f(1) \in \mathbb{Z}$. Chứng minh $f(x) \in \mathbb{Z}$ với mọi $x \in \mathbb{Z}$.

### ✨ Lời giải

Ta có:
- $f(0) = c \in \mathbb{Z}$
- $f(1) = a + b + c \in \mathbb{Z}$
- $f(-1) = a - b + c \in \mathbb{Z}$

Suy ra:
$b = \frac{f(1) - f(-1)}{2} \in \mathbb{Z}$
$a = \frac{f(1) + f(-1) - 2c}{2} \in \mathbb{Z}$

⇒ $a, b, c \in \mathbb{Z} \Rightarrow f(x) \in \mathbb{Z}$

---

## Bài 3
Cho $x f(x+1) = (x+2) f(x)$. Chứng minh $f(x)$ có ít nhất hai nghiệm.

### ✨ Lời giải

Thử giá trị đặc biệt:

- $x = 0$:
$0 = 2f(0) \Rightarrow f(0) = 0$

- $x = -2$:
$-2 f(-1) = 0 \Rightarrow f(-1) = 0$

⇒ $f(x)$ có ít nhất 2 nghiệm: $x = 0, -1$

---

## Bài 4
$f(x) = (x+2)^2(x^4 - x^3 - 4x^2 + 3)$

Tính:
- hệ số tự do
- tổng hệ số bậc chẵn

### ✨ Lời giải

### Hệ số tự do:
$f(0) = (2)^2 \cdot 3 = 12$

### Tổng hệ số bậc chẵn:
$S = \frac{f(1) + f(-1)}{2}$

Tính:
- $f(1) = 9(-1) = -9$
- $f(-1) = 1(-1) = -1$

$S = \frac{-9 -1}{2} = -5$

---

## Bài 5

a)  
$f(0)=2,\; f(1)=7,\; f(-2)=-14$

### ✨ Lời giải

Từ:
- $c = 2$
- $a + b + 2 = 7 \Rightarrow a+b=5$
- $4a -2b +2 = -14 \Rightarrow 2a - b = -8$

Giải hệ:
$a = -1,\; b = 6,\; c = 2$

---

b)

$f(-2)=0,\; f(2)=0$

⇒ nghiệm $\pm 2$ ⇒
$f(x) = k(x^2 - 4)$

$a = k,\; c = -4k$

$a - c = 5 \Rightarrow 5k = 5 \Rightarrow k = 1$

⇒ $a=1, b=0, c=-4$

---

## Bài 6

$f(-1)=2023,\; f(0)=2024,\; f(1)=2025$

Tính $f(2026)$

### ✨ Lời giải

Nhận thấy:
$f(x+1) - f(x) = 1$

⇒ $f(x) = x + 2024$

$f(2026) = 2026 + 2024 = 4050$

---

## Bài 7

Tìm $a,b,c$ để $f(x) = g(x)$

### ✨ Lời giải

Khai triển:

$f(x) = ax^3 + 4x^3 - 4x + 8 = (a+4)x^3 -4x + 8$

$g(x) = x^3 + 4bx^2 -4x + c -3$

So hệ số:

$a+4 = 1 \Rightarrow a = -3$
$4b = 0 \Rightarrow b = 0$
$c - 3 = 8 \Rightarrow c = 11$

---

## Bài 8

$P(0)=-2,\quad 4P(x) - P(2x-1) = 6x-6$

### ✨ Lời giải

Khai triển và so hệ số:

⇒ $a=0, b=2, c=-2$

⇒ $P(x) = 2x -2$

$a+b+c = 0$

---

## Bài 9

Biết $P(1),\dots,P(2023) \equiv 0 \pmod{2023}$

### ✨ Lời giải

Đa thức có 2023 nghiệm liên tiếp mod 2023

⇒ chia hết cho:
$(x-1)(x-2)\cdots(x-2023)$

⇒ $P(x) \equiv 0 \pmod{2023}$

---

## Bài 10

$P(0)=P(1)=2$

### ✨ Lời giải

$P(x) = 2 + x(x-1)Q(x)$

$P(7) = 2 + 42Q(7)$

$\equiv 2 \pmod{7}$

Mà số chính phương mod 7 ∈ $\{0,1,2,4\}$

Kiểm tra kỹ → không thể là chính phương

---

## Bài 11

$5a + b + 2c = 0$

### ✨ Lời giải

Tính:

$P(2) = 4a + 2b + c$

$P(-1) = a - b + c$

Dùng điều kiện:

⇒ tích ≤ 0
