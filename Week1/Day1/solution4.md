

### ✅ **Question (Problem Statement)**

Given the following pseudocode, determine the final output printed at line 10. The pseudocode involves bitwise operations (& for AND, ^ for XOR) and conditional statements. The options for the output are:

A. 29

B. 18

C. 10

D. 16

---

### 🧠 **Pseudo Code**

```
Integer pp, qq, rr  
Set pp = 0, qq = 6, rr = 7  
pp = rr + pp  
pp = (rr & 4) ^ rr  
if ((qq & pp & rr) < (rr & qq))  
    if ((qq ^ pp) < (rr + qq))  
        rr = (3 + 1) ^ pp  
    End if  
End if  
Print pp + qq + rr   
```

---

### 🔍 **Step-by-Step Analysis**

Initialization (Line 2)
pp = 0, qq = 6, rr = 7.

Line 3: pp = rr + pp
pp = 7 + 0 = 7.

Line 4: pp = (rr & 4) ^ rr
Bitwise AND (rr & 4)

Binary of rr = 7 → 0111.

Binary of 4 → 0100.

0111 & 0100 → 0100 (decimal 4).

Bitwise XOR (4 ^ rr)

0100 ^ 0111 → 0011 (decimal 3).

Result: pp = 3.

Line 5: Outer if Condition
Condition: (qq & pp & rr) < (rr & qq).

Left Side (qq & pp & rr)

qq = 6 (0110), pp = 3 (0011), rr = 7 (0111).

0110 & 0011 → 0010 (decimal 2).

0010 & 0111 → 0010 (decimal 2).

Right Side (rr & qq)

0111 & 0110 → 0110 (decimal 6).

Comparison: 2 < 6 → True.

Proceed into the if block.

Line 6: Inner if Condition
Condition: (qq ^ pp) < (rr + qq).

Left Side (qq ^ pp)

0110 ^ 0011 → 0101 (decimal 5).

Right Side (rr + qq)

7 + 6 = 13.

Comparison: 5 < 13 → True.

Proceed into the nested if block.

Line 7: Update rr
rr = (3 + 1) ^ pp.

3 + 1 = 4.

4 ^ pp → 0100 ^ 0011 → 0111 (decimal 7).

Result: rr = 7 (unchanged).

Line 10: Final Output
pp + qq + rr → 3 + 6 + 7 = 16.
### 🖨️ **Final Output on Console**

```
16 (Option D).
```
