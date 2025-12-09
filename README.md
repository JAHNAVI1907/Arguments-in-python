# Python Function Arguments

This repository contains a detailed guide on **Python function arguments**. It covers all types of arguments, rules, and examples for professional learning and reference.

---

## Table of Contents
- [1. Positional Arguments](#1-positional-arguments)
- [2. Keyword Arguments](#2-keyword-arguments)
- [3. Default Arguments](#3-default-arguments)
- [4. Variable-Length Arguments](#4-variable-length-arguments)
  - [4.1 *args](#41-args)
  - [4.2 **kwargs](#42-kwargs)
- [5. Keyword-Only Arguments](#5-keyword-only-arguments)
- [6. Positional-Only Arguments](#6-positional-only-arguments)
---

## 1. Positional Arguments
Arguments passed **based on their position**. The order matters and must match the function definition.

```python
def greet(name, age):
    print(f"Hello {name}, you are {age} years old.")

greet("Alice", 25)
