# Power of Two Checker 🚀

A high-performance C implementation to determine if a given integer is a power of two using efficient bitwise operations.

## 📝 Description

This project provides a simple yet powerful solution for checking if a number is a power of two. Instead of using loops or recursion, it utilizes bitwise logic for $O(1)$ time complexity.

### How it Works
A number $n$ that is a power of two has exactly one bit set in its binary representation. 
Example: 
- `4` in binary is `0100`
- `3` in binary is `0011`
- `4 & 3` (bitwise AND) results in `0000` (0)

The formula `(n > 0) && ((n & (n - 1)) == 0)` perfectly identifies these numbers.

## 🛠️ Features
- **Fast**: Constant time complexity $O(1)$.
- **Lightweight**: Zero external dependencies (uses standard library).
- **Clean Code**: Well-structured and easy to understand.

## 🚀 Getting Started

### Prerequisites
- GCC or any C compiler installed on your system.

### Compilation
Run the following command in your terminal:
```bash
gcc pot.c -o pot
```

### Usage
Run the compiled executable and enter an integer:
```bash
./pot
```
**Input:** `16`  
**Output:** `true`

## 📂 Project Structure
- `pot.c`: The core source code containing the `isPowerOfTwo` function and main entry point.

---
Created with ❤️ by [Aritrathecoder](https://github.com/Aritrathecoder)
