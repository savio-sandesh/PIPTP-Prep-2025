### ✅ **Question (Problem Statement)**

What will be the output of the following pseudocode?

Integer p, q, r

Set p = 9, q = 6, r = 10

if ((q ^ p ^ r) > (r ^ q))

r = (11 & 12) + q

End if

if ((q ^ 6 ^ 8) > (p ^ 4))

p = (r + 3) & r

End if

Print p + q + r


---

### 🧠 **Pseudo Code**
FUNCTION main()

SET p = 9, q = 6, r = 10

IF ((q XOR p XOR r) > (r XOR q))

    r = (11 AND 12) + q
END IF

IF ((q XOR 6 XOR 8) > (p XOR 4))

    p = (r + 3) AND r
END IF

PRINT p + q + r


---

### 🔍 **Step-by-Step Analysis**

#### Initialization:

p = 9, q = 6, r = 10


---

#### Line 3: First If Condition  
Condition: `(q ^ p ^ r) > (r ^ q)`

- `q ^ p ^ r = 6 ^ 9 ^ 10`
  - `6 ^ 9 = 15`
  - `15 ^ 10 = 5`
- `r ^ q = 10 ^ 6 = 12`

**Comparison**: `5 > 12` → ❌ False  
→ Skip this block, `r` remains `10`

---

#### Line 6: Second If Condition  
Condition: `(q ^ 6 ^ 8) > (p ^ 4)`

- `q ^ 6 ^ 8 = 6 ^ 6 ^ 8`
  - `6 ^ 6 = 0`
  - `0 ^ 8 = 8`
- `p ^ 4 = 9 ^ 4 = 13`

**Comparison**: `8 > 13` → ❌ False  
→ Skip this block, `p` remains `9`

---

### Final Values:
- `p = 9`  
- `q = 6`  
- `r = 10`  

Sum = `p + q + r = 9 + 6 + 10 = 25`

---

### 🖨️ **Final Output on Console**


✅ **Correct Answer: 25**



