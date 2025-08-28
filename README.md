# 🔄 EXP-10: Call by Value and Call by Reference in C++

## 🎯 Aim

To understand the concepts of **call by value** and **call by reference** in C++ by writing programs that demonstrate the difference in parameter passing techniques.

---

## 📚 Theory

When functions are called in C++, arguments can be passed in different ways:

1. **Call by Value**
   - A copy of the actual value is passed to the function.
   - Changes made inside the function do not affect the original variable.
   - Example:  
     ```cpp
     void func(int x) { x = x + 10; }
     ```

2. **Call by Reference**
   - The actual address (reference) of the variable is passed to the function.
   - Changes inside the function directly affect the original variable.
   - Example:  
     ```cpp
     void func(int &x) { x = x + 10; }
     ```

3. **Pass by Reference (using pointers)**
   - Function accepts pointer parameters.
   - Addresses are passed, and dereferencing allows modification of original values.

---

## 🧮 Algorithms / Steps

### 1. **Call by Value (`call_by_value.cpp`)**
- Define a function that takes parameters normally.
- Modify the parameters inside the function.
- Print results to show original variables remain unchanged.

### 2. **Call by Reference (`call_by_reference.cpp`)**
- Define a function that takes parameters as references (`int &a`).
- Modify parameters inside the function.
- Print results to show that original variables are updated.

### 3. **Pass by Reference using Pointers (`pass_by_reference.cpp`)**
- Define a function that accepts pointer parameters.
- Pass the address of variables while calling the function.
- Modify values using dereferencing inside the function.
- Print results to show updated values.

---

## ✅ Conclusion

This experiment clarifies the difference between **call by value** and **call by reference**:
- **Call by Value** → Original values are unchanged.  
- **Call by Reference / Pass by Reference** → Original values are modified.  

Understanding these concepts is essential for efficient memory usage and control over variable manipulation in C++.

---

## 🧵 Topics Covered

- Function parameter passing techniques in C++  
- Call by Value  
- Call by Reference  
- Pass by Reference using pointers  
- Use cases of each method in programming  
