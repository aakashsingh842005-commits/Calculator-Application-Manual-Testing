# Calculator Application Test Cases

---

## TC_001 - Verify Addition of Two Positive Numbers

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 10
2. Enter second number as 20
3. Click on Add button

### Expected Result
- Result should display 30

---

## TC_002 - Verify Subtraction of Two Numbers

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 50
2. Enter second number as 20
3. Click on Subtract button

### Expected Result
- Result should display 30

---

## TC_003 - Verify Multiplication of Two Numbers

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 5
2. Enter second number as 4
3. Click on Multiply button

### Expected Result
- Result should display 20

---

## TC_004 - Verify Division of Two Numbers

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 20
2. Enter second number as 5
3. Click on Divide button

### Expected Result
- Result should display 4

---

## TC_005 - Verify Addition of Negative Numbers

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as -10
2. Enter second number as -5
3. Click on Add button

### Expected Result
- Result should display -15

---

## TC_006 - Verify Decimal Number Addition

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 10.5
2. Enter second number as 2.5
3. Click on Add button

### Expected Result
- Result should display 13

---

## TC_007 - Verify Division by Zero

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 10
2. Enter second number as 0
3. Click on Divide button

### Expected Result
- Error message should appear saying division by zero is not allowed

---

## TC_008 - Verify Input with Alphabetic Characters

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as abc
2. Enter second number as 10
3. Click on Add button

### Expected Result
- Validation error message should appear

---

## TC_009 - Verify Empty Input Fields

### Preconditions
- Calculator application is opened

### Test Steps
1. Leave both input fields empty
2. Click on Add button

### Expected Result
- Validation message should appear asking user to enter values

---

## TC_010 - Verify Special Character Inputs

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as @@@
2. Enter second number as ###
3. Click on Multiply button

### Expected Result
- Validation error should appear

---

## TC_011 - Verify Large Number Calculation

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter first number as 999999
2. Enter second number as 999999
3. Click on Add button

### Expected Result
- Result should display 1999998

---

## TC_012 - Verify BODMAS Calculation

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter expression as 2 + 3 * 4
2. Click on Calculate button

### Expected Result
- Result should display 14 according to BODMAS rule

---

## TC_013 - Verify Calculator Clear Button

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter values in both input fields
2. Click on Clear button

### Expected Result
- All entered values should be cleared

---

## TC_014 - Verify Calculator Response Time

### Preconditions
- Calculator application is opened

### Test Steps
1. Enter any two valid numbers
2. Click on Add button

### Expected Result
- Result should display immediately

---

## TC_015 - Verify Sequential Operations

### Preconditions
- Calculator application is opened

### Test Steps
1. Perform addition operation
2. Without refreshing, perform subtraction operation

### Expected Result
- Calculator should correctly perform multiple operations sequentially

---