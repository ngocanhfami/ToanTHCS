

Phần I - Lời giải chi tiết: Khai triển tỉ mỉ từng bài toán, cung cấp các mẹo đổi biến (đặt ẩn phụ), thiết lập hệ thức phụ giữa tổng - tích giúp tối ưu thời gian làm bài thi chuyên.

Phần II - Bài tập tự luyện: Các dạng bài chọn lọc từ đề thi Học sinh giỏi và đề tuyển sinh lớp 10 chuyên Toán 



# CHUYÊN ĐỀ LUYỆN THI CHUYÊN TOÁN: HẰNG ĐẲNG THỨC ĐÁNG NHỚ


---

## PHẦN I: LỜI GIẢI CHI TIẾT 10 BÀI TOÁN TRỌNG TÂM

### Bài 1: Tính giá trị biểu thức bậc ba
**Đề bài:** Cho hai số $a, b$ thỏa mãn $a + b = 5$ và $ab = 3$. Tính giá trị của biểu thức $P = a^3 + b^3$.

**Lời giải:**
Ta có hằng đẳng thức hệ quả (biến đổi từ lập phương của một tổng):
$a^3 + b^3 = (a + b)^3 - 3ab(a + b)$

Thay các giá trị $a + b = 5$ và $ab = 3$ vào biểu thức trên, ta được:
$P = 5^3 - 3 \cdot 3 \cdot 5$
$P = 125 - 45 = 80$

**Đáp số:** $P = 80$.

---

### Bài 2: Rút gọn biểu thức bằng cách đặt ẩn phụ
**Đề bài:** Rút gọn biểu thức $A = (x - 1)^3 - (x + 1)^3 + 6(x - 1)(x + 1)$.

**Lời giải:**
*Cách 1: Khai triển trực tiếp (Thông thường)*
$A = (x^3 - 3x^2 + 3x - 1) - (x^3 + 3x^2 + 3x + 1) + 6(x^2 - 1)$

$A = x^3 - 3x^2 + 3x - 1 - x^3 - 3x^2 - 3x - 1 + 6x^2 - 6$

$A = (-3x^2 - 3x^2 + 6x^2) + (3x - 3x) + (-1 - 1 - 6)$

$A = -8$

*Cách 2: Đặt ẩn phụ tạo hằng đẳng thức (Tư duy chuyên)*
Đặt $u = x - 1$ và $v = x + 1$. Ta có: $u - v = (x - 1) - (x + 1) = -2$.
Biểu thức $A$ trở thành:
$A = u^3 - v^3 + 6uv$

$A = (u - v)(u^2 + uv + v^2) + 6uv$

Thay $u - v = -2$ vào:

$A = -2(u^2 + uv + v^2) + 6uv$

$A = -2u^2 - 2uv - 2v^2 + 6uv$

$A = -2u^2 + 4uv - 2v^2$

$A = -2(u^2 - 2uv + v^2)$

$A = -2(u - v)^2$

Thay tiếp $u - v = -2$:

$A = -2 \cdot (-2)^2 = -2 \cdot 4 = -8$

**Đáp số:** $A = -8$.

---

### Bài 3: Tính tổng bình phương nghịch đảo
**Đề bài:** Cho $x + \frac{1}{x} = 3$. Tính giá trị của biểu thức $B = x^2 + \frac{1}{x^2}$.

**Lời giải:**
Bình phương hai vế của giả thiết $x + \frac{1}{x} = 3$, ta được:
$(x + \frac{1}{x})^2 = 3^2$

$x^2 + 2 \cdot x \cdot \frac{1}{x} + \frac{1}{x^2} = 9$

Vì $x \cdot \frac{1}{x} = 1$, phương trình tương đương:
$x^2 + 2 + \frac{1}{x^2} = 9$

$x^2 + \frac{1}{x^2} = 9 - 2 = 7$

**Đáp số:** $B = 7$.

---

### Bài 4: Tính tổng lập phương nghịch đảo
**Đề bài:** Cho $x + rac{1}{x} = 3$. Tính giá trị của biểu thức $C = x^3 + rac{1}{x^3}$.

**Lời giải:**
Sử dụng hằng đẳng thức biến đổi tổng hai lập phương:
$C = x^3 + \frac{1}{x^3} = (x + \frac{1}{x}
)^3 - 3 \cdot x \cdot \frac{1}{x} \cdot (x + \frac{1}{x}
)$

$C = (x + rac{1}{x}
)^3 - 3(x + rac{1}{x}
)$

Thay số $x + \frac{1}{x} = 3$ vào ta được:
$C = 3^3 - 3 \cdot 3 = 27 - 9 = 18$

**Đáp số:** $C = 18$.

---

### Bài 5: Cực trị của đại lượng bậc hai (GTNN)
**Đề bài:** Tìm giá trị nhỏ nhất của biểu thức $M = x^2 - 4x + 9$.

**Lời giải:**
Ta biến đổi biểu thức $M$ bằng cách thêm bớt để xuất hiện hằng đẳng thức dạng $(a-b)^2$:
$M = x^2 - 2 \cdot x \cdot 2 + 4 + 5$

$M = (x - 2)^2 + 5$

Vì $(x - 2)^2 \ge 0$ với mọi $x \in \mathbb{R}$, nên:

$(x - 2)^2 + 5 \ge 5 \quad \Rightarrow \quad M \ge 5$

Dấu "=" xảy ra khi và chỉ khi:

$x - 2 = 0 \quad \Leftrightarrow \quad x = 2$

**Kết luận:** Giá trị nhỏ nhất của $M$ là $5$, đạt được tại $x = 2$.

---

### Bài 6: Phân tích đa thức bậc bốn trùng phương
**Đề bài:** Phân tích đa thức sau thành nhân tử: $D = x^4 - 4x^2 + 3$.

**Lời giải:**
Ta tách hạng tử $-4x^2$ để nhóm nhân tử chung hoặc dùng hằng đẳng thức hiệu hai bình phương:
$D = x^4 - x^2 - 3x^2 + 3$

$D = x^2(x^2 - 1) - 3(x^2 - 1)$

$D = (x^2 - 1)(x^2 - 3)$

Tiếp tục áp dụng hằng đẳng thức $a^2 - b^2 = (a-b)(a+b)$ cho đa thức $x^2 - 1$:

$x^2 - 1 = (x - 1)(x + 1)$

Do đó:
$D = (x - 1)(x + 1)(x^2 - 3)$

**Đáp số:** $D = (x - 1)(x + 1)(x^2 - 3)$.

---

### Bài 7: Tính hiệu hai bình phương qua hệ phương trình
**Đề bài:** Cho $a - b = 4$ và $ab = 21$. Tính giá trị của biểu thức $E = a^2 - b^2$ biết rằng $a, b > 0$.

**Lời giải:**
Ta có hằng đẳng thức: $E = a^2 - b^2 = (a - b)(a + b)$. Đã biết $a - b = 4$, cần tìm $a + b$.
Mối liên hệ giữa $(a+b)^2$ và $(a-b)^2$ qua $ab$ là:
$(a + b)^2 = (a - b)^2 + 4ab$

Thay số vào:
$(a + b)^2 = 4^2 + 4 \cdot 21 = 16 + 84 = 100$

Vì $a, b > 0$ nên $a + b > 0$, lấy căn bậc hai hai vế ta được:

$a + b = \sqrt{100} = 10$

Từ đó tính được giá trị của $E$:

$E = (a - b)(a + b) = 4 \cdot 10 = 40$

**Đáp số:** $E = 40$.

---

### Bài 8: Chứng minh bài toán chia hết
**Đề bài:** Chứng minh rằng biểu thức $N = (2n + 1)^2 - 1$ luôn chia hết cho 8 với mọi số nguyên $n$.

**Lời giải:**
Áp dụng hằng đẳng thức hiệu hai bình phương $a^2 - b^2$ với $a = 2n + 1$ và $b = 1$:
$N = [(2n + 1) - 1][(2n + 1) + 1]$
$N = (2n) \cdot (2n + 2)$
$N = 2n \cdot 2(n + 1) = 4n(n + 1)$
Xét tích $n(n + 1)$: Vì $n$ và $n + 1$ là hai số nguyên liên tiếp nên trong hai số luôn có một số chẵn (chia hết cho 2).
Do đó, $n(n + 1) \  dots \ 2$.
Suy ra $4n(n + 1) \  dots \ (4 \cdot 2) \Rightarrow N \  dots \ 8$.

**Kết luận:** Biểu thức $N$ luôn chia hết cho 8 với mọi số nguyên $n$.

---

### Bài 9: Hằng đẳng thức điều kiện đẳng thức nâng cao
**Đề bài:** Cho $x + y + z = 0$. Rút gọn biểu thức $Q = x^3 + y^3 + z^3$.

**Lời giải:**
Từ giả thiết $x + y + z = 0 \Rightarrow x + y = -z$.
Lập phương cả hai vế ta được:
$(x + y)^3 = (-z)^3$

$x^3 + 3x^2y + 3xy^2 + y^3 = -z^3$

$x^3 + y^3 + 3xy(x + y) = -z^3$

Thay $x + y = -z$ vào nhóm hạng tử trung gian:
$x^3 + y^3 + 3xy(-z) = -z^3$

$x^3 + y^3 - 3xyz = -z^3$

Chuyển vế $-z^3$ và $-3xyz$, ta thu được:

$x^3 + y^3 + z^3 = 3xyz$

**Đáp số:** $Q = 3xyz$.

---

### Bài 10: Cực trị của đại lượng bậc hai (GTLN)
**Đề bài:** Tìm giá trị lớn nhất của biểu thức $K = 5 + 6x - x^2$.

**Lời giải:**
Ta nhóm các hạng tử chứa biến $x$ và đặt dấu trừ ra ngoài:
$K = 5 - (x^2 - 6x)$
Thêm bớt số 9 vào trong ngoặc để tạo thành hằng đẳng thức $(a-b)^2$:
$K = 5 - (x^2 - 6x + 9 - 9)$
$K = 5 - \left[(x - 3)^2 - 9
ight]$
$K = 5 - (x - 3)^2 + 9$
$K = 14 - (x - 3)^2$
Vì $(x - 3)^2 \ge 0$ với mọi $x \in \mathbb{R}$ nên $-(x - 3)^2 \le 0$.
Do đó:
$K = 14 - (x - 3)^2 \le 14$
Dấu "=" xảy ra khi và chỉ khi:
$x - 3 = 0 \quad \Leftrightarrow \quad x = 3$

**Kết luận:** Giá trị lớn nhất của $K$ là $14$, đạt được tại $x = 3$.

---

## PHẦN II: BÀI TẬP TỰ LUYỆN NÂNG CAO (CÓ ĐÁP SỐ ĐỂ ĐỐI CHIẾU)

Dưới đây là các bài toán chọn lọc từ các đề thi học sinh giỏi và thi chuyên lớp 9 để các em học sinh tự rèn luyện kỹ năng biến đổi.

**Bài 1 (Tính giá trị):**
Cho $x - y = 5$ và $xy = 6$. Không tìm $x, y$, hãy tính giá trị biểu thức:
a) $P = x^2 + y^2$

b) $Q = x^3 - y^3$
*Đáp số: a) $P = 37$; b) $Q = 215$.*

**Bài 2 (Chứng minh bất đẳng thức/Cực trị):**
Cho hai số thực $x, y$ thỏa mãn $x + y = 2$. Tìm giá trị nhỏ nhất của biểu thức $H = x^2 + y^2$.

*Gợi ý: Biến đổi $y = 2 - x$ thế vào biểu thức hoặc dùng hằng đẳng thức thông qua $(x+y)^2$.*
*Đáp số: $H_{\min} = 2$ khi $x = y = 1$.*

**Bài 3 (Phân tích đa thức thành nhân tử):**
Phân tích đa thức sau thành nhân tử bằng cách thêm bớt để tạo hiệu hai bình phương:
$A = x^4 + 4$

*Gợi ý: Thêm và bớt $4x^2$ để nhóm hằng đẳng thức $(x^2+2)^2$.*
*Đáp số: $A = (x^2 - 2x + 2)(x^2 + 2x + 2)$.*

**Bài 4 (Nâng cao hệ thức nghịch đảo):**
Cho $x - rac{1}{x} = 2$. Tính giá trị của biểu thức $K = x^4 + rac{1}{x^4}$.
*Đáp số: $K = 34$.*

**Bài 5 (Bổ đề Chuyên Toán):**
Chứng minh rằng nếu $a^2 + b^2 + c^2 = ab + bc + ca$ thì $a = b = c$.
*Gợi ý: Nhân cả hai vế với 2, chuyển tất cả sang một vế rồi nhóm thành tổng của 3 hằng đẳng thức bình phương một hiệu.*
Hang_Dang_Thuc_On_Thi_Chuyen.md
Đang hiển thị Hang_Dang_Thuc_On_Thi_Chuyen.md.
