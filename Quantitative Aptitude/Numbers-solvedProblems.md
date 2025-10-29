
#  Numbers (Solved Problems)

> *“Numbers are not just math — they’re puzzles waiting to be solved.”*   

---

## 🧮 **Question 1**

**Q:** When a number is successively divided by 35, 45, and 55, we get 18, 28, and 38 as remainders. Find the smallest such number.

**Solution:**
- LCM(35, 45, 55) = **3465**
- Find common remainder:
  - 35 − 18 = 17  
  - 45 − 28 = 17  
  - 55 − 38 = 17  
- Common remainder = **17**  
✅ Smallest number = 3465 − 17 = **3448**

---

## 🔢 **Question 2**

**Q:** How many four-digit numbers are divisible by 7?

**Solution:**
- First multiple: 1001 (7 × 143)  
- Last multiple: 9996 (7 × 1428)  
- Formula:  
  \( n = \frac{9996 - 1001}{7} + 1 = 1286 \)  
✅ **1286 four-digit numbers** are divisible by 7.

---

## 🧩 **Question 3**

**Q:** What is the maximum value of **B** in:

```

1 2 B

* B 4 C
* C 6 7

---

1 0 3 5

```

**Solution:**
- \( B + C = 8 \)
- For max B → set C = 0 → B = 8  
✅ Verify:  
```

128
+840
+067
----

1035 ✅

```
✅ **B = 8**

---

## 🧮 **Question 4**

**Q:** Which are prime numbers?  
(i) 247 (ii) 397 (iii) 423  

**Solution:**
- (i) 247 → divisible by 13 → ❌ Composite  
- (ii) 397 → not divisible by primes ≤ 19 → ✅ Prime  
- (iii) 423 → divisible by 3 → ❌ Composite  
✅ **Answer:** Only **397** is prime.

---

## 🔢 **Question 5**

**Q:** Find the unit’s digit of \( (17)^{153} × (31)^{62} \)

**Solution:**
- Pattern of 7 → 7, 9, 3, 1 (4-cycle)
- \( 153 = 4×38 + 1 \Rightarrow \) unit = 7  
- \( (31)^{62} \Rightarrow \) unit = 1  
✅ Unit digit = **7 × 1 = 7**

---

## 🔢 **Question 6**

**Q:** Find the unit’s digit of \( (17)^{153} + (31)^{62} \)

**Solution:**
- From above: \( (17)^{153} → 7 \), \( (31)^{62} → 1 \)
✅ Unit digit = **7 + 1 = 8**

---

## 🧠 **Question 7**

**Q:** Find total number of prime factors in \( (14)^{11} × (7)^{2} × (11)^{3} \)

**Solution:**
\[
(14)^{11} × (7)^{2} × (11)^{3} = (2 × 7)^{11} × 7^{2} × 11^{3} = 2^{11} × 7^{13} × 11^{3}
\]
✅ Total = 11 + 13 + 3 = **27 prime factors**

---

## 🔢 **Question 8**

**Q:** Which digits replace * and # in 12386*# if it’s divisible by both 8 and 5?

**Solution:**
- Divisible by 5 → last digit (#) = 0 ✅  
- Divisible by 8 → last 3 digits (6*0) divisible by 8 → * = 0, 4, or 8 ✅  
✅ **Answers:** * = 0 / 4 / 8 and # = 0

---

## 🔢 **Question 9**

**Q:** What is the least number to subtract from 9999 to make it divisible by 19?

**Solution:**
- 9999 ÷ 19 → remainder = 5  
✅ Subtract **5**

---

## 🔢 **Question 10**

**Q:** What is the least number to add to 9999 to make it divisible by 19?

**Solution:**
- Remainder = 5  
✅ Add \( 19 - 5 = 14 \)

---

## 🧩 **Question 11**

**Q:** A number when divided by 340 gives remainder 47. What is remainder when divided by 17?

**Solution:**
\[
340a + 47 = 17(20a + 2) + 13
\]
✅ Remainder = **13**

---

## 🔢 **Question 12**

**Q:** Find remainder when \( 3^{21} \) is divided by 5.

**Solution:**
- Pattern of \( 3^n \): 3, 4, 2, 1 (4-cycle)  
- \( 21 = 4×5 + 1 → \) remainder pattern index = 1  
✅ \( 3^{21} \) gives **3** as remainder when divided by 5.

---

### 🏁 **Summary**
| Concept | Key Formula / Trick |
|----------|---------------------|
| LCM-based remainders | Common remainder = Divisor − Given remainder |
| Unit digit | Use cyclicity (4-cycle or similar) |
| Divisibility by 8 | Last 3 digits rule |
| Prime factors | Add all exponents |
| Division remainder | Reduce with modulo |


