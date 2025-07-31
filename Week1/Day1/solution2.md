### ✅ **Question (Problem Statement)**

Given the following pseudo-code:

Integer a, b, c

Set a = 2, b = 6, c = 8

a = (10 + 9) + c

if ((c + b) > (a - c))

a = b + c  

b = b + b  

End if

Print a + b + c


What will be the output of the program?

**Options:**

A. 23  
B. 41  
C. 48  
D. 58  

---

### 🧠 **Pseudo Code Explanation**

Step 1: Initialize variables
a = 2, b = 6, c = 8

Step 2: Line 3:
a = (10 + 9) + c = 19 + 8 = 27

Step 3: Line 4 (Condition Check):
if (c + b) > (a - c)
→ (8 + 6) > (27 - 8)
→ 14 > 19 → False

Step 4: Since condition is False:
- Skip lines 5 and 6
- Go to line 8

Step 5: Line 8:
Print a + b + c = 27 + 6 + 8 = 41


---

### 🔍 **Step-by-Step Analysis**

- Initial values: `a = 2`, `b = 6`, `c = 8`
- After line 3: `a = (10 + 9) + c = 27`
- Condition check: `(c + b) = 14` vs `(a - c) = 19` → 14 > 19 → ❌ False
- Condition fails → skip the `if` block
- Final output is: `a + b + c = 27 + 6 + 8 = 41`

---

### 🖨️ **Final Output on Console**


✅ **Correct Answer: B**

---


