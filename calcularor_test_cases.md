# Task-01: Write a test case for a simple calculator Application 
**Application teste**:https://dunizb.github.io/sCalc/ 
### **Test Case 1**

**Test Case ID:** TC_CALC_001
**Description:** Verify addition of two positive integers
**Precondition:** Calculator is open
**Test Steps:**

1. Enter `5`
2. Press `+`
3. Enter `3`
4. Press `=`
   **Expected Result:** Display shows `8`


### **Test Case 2**

**Test Case ID:** TC_CALC_002
**Description:** Verify subtraction of two numbers
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `9`
2. Press `–`
3. Enter `4`
4. Press `=`
   **Expected Result:** Display shows `5`

### **Test Case 3**

**Test Case ID:** TC_CALC_003
**Description:** Verify multiplication of two numbers
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `6`
2. Press `×`
3. Enter `3`
4. Press `=`
   **Expected Result:** Display shows `18`

### **Test Case 4**

**Test Case ID:** TC_CALC_004
**Description:** Verify division of two numbers
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `8`
2. Press `÷`
3. Enter `2`
4. Press `=`
   **Expected Result:** Display shows `4`


### **Test Case 5**

**Test Case ID:** TC_CALC_005
**Description:** Verify operation with negative numbers
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `-5`
2. Press `×`
3. Enter `3`
4. Press `=`
   **Expected Result:** Display shows `-15`


### **Test Case 6**

**Test Case ID:** TC_CALC_006
**Description:** Verify decimal number calculation
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `2.5`
2. Press `+`
3. Enter `3.2`
4. Press `=`
   **Expected Result:** Display shows `5.7`


### **Test Case 7**

**Test Case ID:** TC_CALC_007
**Description:** Verify BODMAS rule (operator precedence)
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `5 + 3 × 2`
2. Press `=`
   **Expected Result:** Multiplication should occur before addition.
   `3 × 2 = 6`, then `5 + 6 = 11`
   ✅ Display shows `11`


## **❌ Invalid Input Test Cases**

### **Test Case 8**

**Test Case ID:** TC_CALC_008
**Description:** Verify division by zero handling
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `9`
2. Press `÷`
3. Enter `0`
4. Press `=`
   **Expected Result:** Display shows error message or `Infinity`


### **Test Case 9**

**Test Case ID:** TC_CALC_009
**Description:** Verify non-numeric input handling
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `A + 5`
   **Expected Result:** Calculator should reject non-numeric input and show an error or ignore invalid character

### **Test Case 10**

**Test Case ID:** TC_CALC_010
**Description:** Verify invalid sequence of operators
**Precondition:** Calculator app open
**Test Steps:**

1. Enter `5 ++ 3`
2. Press `=`
   **Expected Result:** Calculator should handle invalid operator sequence gracefully and show an error or correct expression automatically

