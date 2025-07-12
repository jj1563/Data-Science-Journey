# 🧮 Python Operators Reference Guide

A beginner-friendly reference to all major Python operators, including examples and code variables.

---

## ➕ Arithmetic Operators

| Symbol | Name           | Example   | Code Variable |
|--------|----------------|-----------|---------------|
| `+`    | Addition       | `10 + 5`  | `A`           |
| `-`    | Subtraction    | `10 - 5`  | `B`           |
| `*`    | Multiplication | `10 * 5`  | `C`           |
| `/`    | Division       | `10 / 5`  | `D`           |
| `%`    | Modulus        | `10 % 5`  | `E`           |
| `**`   | Exponentiation | `10 ** 5` | `F`           |
| `//`   | Floor Division | `10 // 5` | `G`           |

---

## 📝 Assignment Operators

| Symbol | Meaning                 | Equivalent         | Example     |
|--------|--------------------------|---------------------|-------------|
| `=`    | Assign                  | `x = 5`            | `x = 5`     |
| `+=`   | Add and assign          | `x = x + 3`        | `x += 3`    |
| `-=`   | Subtract and assign     | `x = x - 3`        | `x -= 3`    |
| `*=`   | Multiply and assign     | `x = x * 3`        | `x *= 3`    |
| `/=`   | Divide and assign       | `x = x / 3`        | `x /= 3`    |
| `%=`   | Modulus and assign      | `x = x % 3`        | `x %= 3`    |
| `//=`  | Floor divide and assign | `x = x // 3`       | `x //= 3`   |
| `**=`  | Power and assign        | `x = x ** 3`       | `x **= 3`   |
| `&=`   | Bitwise AND and assign  | `x = x & 3`        | `x &= 3`    |
| `|=`   | Bitwise OR and assign   | `x = x | 3`        | `x |= 3`    |
| `^=`   | Bitwise XOR and assign  | `x = x ^ 3`        | `x ^= 3`    |
| `>>=`  | Right shift and assign  | `x = x >> 3`       | `x >>= 3`   |
| `<<=`  | Left shift and assign   | `x = x << 3`       | `x <<= 3`   |
| `:=`   | Assignment expression   | `x = 3` (inside print) | `print(x := 3)` |

---

## 🧮 Comparison Operators

| Symbol | Name                      | Example        | Output    |
|--------|---------------------------|----------------|-----------|
| `==`   | Equal to                  | `x == y`       | `True/False` |
| `!=`   | Not equal to              | `x != y`       | `True/False` |
| `>`    | Greater than              | `x > y`        | `True/False` |
| `<`    | Less than                 | `x < y`        | `True/False` |
| `>=`   | Greater than or equal to | `x >= y`       | `True/False` |
| `<=`   | Less than or equal to    | `x <= y`       | `True/False` |

---

## 🤔 Logical Operators

| Concept  | Operator | Example                  | Output    |
|----------|----------|--------------------------|-----------|
| AND      | `and`    | `True and False`         | `False`   |
| OR       | `or`     | `True or False`          | `True`    |
| NOT      | `not`    | `not(True)`              | `False`   |
| Combined | -        | `x > 5 and x < 10`       | `True`    |
| Real-world | -      | `temperature > 30 or rain` | depends on values |

---

## 🪪 Identity Operators

| Operator | Description                               | Example     | Output    |
|----------|-------------------------------------------|-------------|-----------|
| `is`     | True if both variables point to same object | `x is y`   | `True/False` |
| `is not` | True if variables do not point to same object | `x is not y` | `True/False` |

---

## 📦 Membership Operators

| Operator   | Description                                         | Example     | Output    |
|------------|-----------------------------------------------------|-------------|-----------|
| `in`       | True if value exists in a sequence                  | `x in y`    | `True/False` |
| `not in`   | True if value does NOT exist in a sequence          | `x not in y`| `True/False` |

---

## ⚙️ Bitwise Operators

| Operator | Name         | Description                              | Example     |
|----------|--------------|------------------------------------------|-------------|
| `&`      | AND          | Sets bit to 1 if both bits are 1         | `x & y`     |
| `|`      | OR           | Sets bit to 1 if at least one bit is 1   | `x | y`     |
| `^`      | XOR          | Sets bit to 1 if one of two bits is 1    | `x ^ y`     |
| `~`      | NOT          | Inverts all bits                         | `~x`        |
| `<<`     | Left Shift   | Shifts bits left                         | `x << 2`    |
| `>>`     | Right Shift  | Shifts bits right                        | `x >> 2`    |

---

## 🔢 Operator Precedence (From Highest to Lowest)

| Code | Operator(s)                               | Description                                    |
|------|--------------------------------------------|------------------------------------------------|
| A    | `()`                                       | Parentheses                                    |
| B    | `**`                                       | Exponentiation                                 |
| C    | `+x`, `-x`, `~x`                           | Unary plus/minus, bitwise NOT                  |
| D    | `*`, `/`, `//`, `%`                        | Multiplication, division, modulus, floor div   |
| E    | `+`, `-`                                   | Addition and subtraction                       |
| F    | `<<`, `>>`                                 | Bitwise shift operators                        |
| G    | `&`                                        | Bitwise AND                                    |
| H    | `^`                                        | Bitwise XOR                                    |
| I    | `|`                                        | Bitwise OR                                     |
| J    | `==`, `!=`, `>`, `<`, `>=`, `<=`, `is`, `in`, `not in`, `is not` | Comparisons, identity, membership |
| K    | `not`                                      | Logical NOT                                    |
| L    | `and`, `or`                                | Logical AND / OR                               |

---

📌 **Note**: When two operators have the same precedence, expressions are evaluated from **left to right** (except for exponentiation `**`, which is right to left).

---

✅ This file serves as a complete reference while learning or revising Python operators for data science, automation, or general development.
