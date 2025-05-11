# Test Cases for Simple Calculator Application

## Test Case 01: Addition with Positive Numbers
**Test Case ID**: TC_01_Add_Positive_Numbers  
**Test Description**: Verify that the calculator correctly adds two positive integers.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `10` in the first input field.  
2. Enter `20` in the second input field.  
3. Select the `+` (addition) operation.  
4. Click the `=` button to calculate.  
**Expected Results**:  
The result displayed should be `30`.  

---

## Test Case 02: Subtraction with Negative Numbers
**Test Case ID**: TC_02_Sub_Negative_Numbers  
**Test Description**: Verify the subtraction operation with two negative integers.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `-15` in the first input field.  
2. Enter `-5` in the second input field.  
3. Select the `-` (subtraction) operation.  
4. Click the `=` button to calculate.  
**Expected Results**:  
The result displayed should be `-10`.  

---

## Test Case 03: Multiplication with Decimals
**Test Case ID**: TC_03_Mul_Decimals  
**Test Description**: Verify that the calculator correctly multiplies two decimal numbers.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `2.5` in the first input field.  
2. Enter `4.2` in the second input field.  
3. Select the `*` (multiplication) operation.  
4. Click the `=` button to calculate.  
**Expected Results**:  
The result displayed should be `10.5`.  

---

## Test Case 04: Division by Zero
**Test Case ID**: TC_04_Div_By_Zero  
**Test Description**: Verify that the calculator handles division by zero gracefully.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `50` in the first input field.  
2. Enter `0` in the second input field.  
3. Select the `/` (division) operation.  
4. Click the `=` button to calculate.  
**Expected Results**:  
An error message such as "Division by zero is not allowed" should be displayed.  

---

## Test Case 05: Non-Numeric Input
**Test Case ID**: TC_05_Non_Numeric_Input  
**Test Description**: Verify that the calculator does not accept non-numeric inputs.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `abc` in the first input field.  
2. Enter `10` in the second input field.  
3. Select the `+` (addition) operation.  
4. Click the `=` button to calculate.  
**Expected Results**:  
An error message such as "Invalid input" should be displayed.

---

## Test Case 06: BODMAS Operation
**Test Case ID**: TC_06_BODMAS  
**Test Description**: Verify that the calculator follows the BODMAS rule correctly.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `10 + 20 * 3` in the input field (if single input is allowed).  
2. Click the `=` button to calculate.  
**Expected Results**:  
The result displayed should be `70` (as per BODMAS: multiplication is performed first).  

---

## Test Case 07: Clear Functionality
**Test Case ID**: TC_07_Clear_Button  
**Test Description**: Verify that the `C` or `Clear` button resets the input fields and result.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `100` in the first input field.  
2. Enter `50` in the second input field.  
3. Click the `C` or `Clear` button.  
**Expected Results**:  
All fields should be cleared, and the result field should display nothing or `0`.

---

## Test Case 08: Large Numbers
**Test Case ID**: TC_08_Large_Numbers  
**Test Description**: Verify the calculator's functionality with very large numbers.  
**Preconditions**: The calculator application is open and ready for input.  
**Test Steps**:  
1. Enter `9999999999` in the first input field.  
2. Enter `8888888888` in the second input field.  
3. Select the `+` (addition) operation.  
4. Click the `=` button to calculate.  
**Expected Results**:  
The result displayed should be `18888888887`.

---

