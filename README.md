# Basic Python – Study Notes

## Overview
This section covers fundamental Python concepts such as printing, string formatting, string methods, and basic list operations.  
It serves as an introduction to writing clean, readable Python code.

---

## 1. Printing and f-strings
- `f-strings` allow embedding variables and expressions directly inside string literals.
- `\t` → Adds a tab space.
- `\n` → Moves output to a new line.

---

## 2. String Methods
- `.upper()` / `.lower()` / `.title()` → Change letter casing.
- `.strip()` → Remove leading and trailing spaces.
- `.rstrip()` / `.lstrip()` → Remove spaces only from right or left.
- `.removeprefix()` / `.removesuffix()` → Remove specific text from start/end.

---

## 3. Lists
- **Creation:** Lists store multiple values in a single variable.
- **Accessing elements:** Using index `list[index]`.
- **Modifying elements:** Assign a new value to an index.
- **Adding elements:**
  - `.append(value)` → Add to end.
  - `.insert(index, value)` → Add at a specific position.
- **Removing elements:**
  - `.remove(value)` → Remove by value.
  - `del list[index]` → Remove by index (no return).
  - `.pop()` → Remove last element and return it.
  - `.pop(index)` → Remove specific element and return it.

---

## 4. Sorting and Reversing
- `.sort()` → Permanently sort list in ascending order.
- `.sort(reverse=True)` → Permanently sort in descending order.
- `sorted(list)` → Temporarily returns a sorted version of the list.
- `.reverse()` → Reverse the order of elements.

---

## 5. Length of a List
- `len(list)` → Returns number of elements in the list.

---

## Summary
These basics form the foundation for Python programming:
- String manipulation makes text processing easier.
- Lists allow dynamic storage and modification of data.
- Built-in list methods simplify adding, removing, sorting, and reversing elements.
