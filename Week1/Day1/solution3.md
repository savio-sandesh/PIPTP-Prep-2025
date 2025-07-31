### ✅ **Question (Problem Statement)**

What will be the output of the following pseudocode for `a = 0`, `b = 2`, `c = 10`?

Integer funn(Integer a, Integer b, Integer c)

b = 7 + a

a = (a + c) + a

b = (b + b) + c

c = 1 + b

return a + b + c


---

### 🧠 **Pseudo Code**

FUNCTION funn(a, b, c)

SET b = 7 + a

SET a = (a + c) + a

SET b = (b + b) + c

SET c = 1 + b

RETURN a + b + c

END FUNCTION

CALL funn(0, 2, 10)

---

### 🔍 **Step-by-Step Analysis**

Initial values:
- `a = 0`
- `b = 2`
- `c = 10`

**Line-by-line execution:**

1. `b = 7 + a` → `b = 7 + 0 = 7`
2. `a = (a + c) + a` → `a = (0 + 10) + 0 = 10`
3. `b = (b + b) + c` → `b = (7 + 7) + 10 = 24`
4. `c = 1 + b` → `c = 1 + 24 = 25`
5. `return a + b + c` → `10 + 24 + 25 = 59`

---

### 🖨️ **Final Output**


✅ **Correct Answer: A**
