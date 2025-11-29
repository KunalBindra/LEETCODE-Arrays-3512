# LEETCODE-Arrays-3512
Here is the **step-by-step dry run** of the Java code for:

```
nums = [3, 9, 7]
k = 5
```

---

# ✅ **Dry Run**

## **Initial values**

* `nums = [3, 9, 7]`
* `k = 5`
* `n = nums.length = 3`
* `sum = 0`
* `ops = 0`

---

## **For-each loop: calculating sum**

### **Iteration 1**

* `num = 3`
* `sum = sum + 3 = 3`

### **Iteration 2**

* `num = 9`
* `sum = sum + 9 = 12`

### **Iteration 3**

* `num = 7`
* `sum = sum + 7 = 19`

✔ Final **sum = 19**

---

## **Check condition `if (sum < k)`**

* `19 < 5` → **false**

So we go to the **else** block.

---

## **Inside else**

* `ops = sum % k`
* `ops = 19 % 5`

Compute:

```
19 / 5 = 3 remainder 4
```

So:

* `ops = 4`

---

## **Return**

```
return ops → 4
```

---

# ✅ **Final Output: 4**

---
