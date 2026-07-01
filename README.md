# python_fundamentals_B102
All Python practice files and coding exercises.


# Python Programming Notes

---

# Rules for Declaring Variables

## Rule No. 1: No Spaces in Variable Names

❌ Incorrect:

```python
first name = 'Faiyaz'

print(first name)
```

**Output:**

```text
Input In [3]
    first name = 'Faiyaz'
         ^
SyntaxError: invalid syntax
```

✅ Correct:

```python
firstname = 'Faiyaz'

print(firstname)
```

**Output:**

```text
Faiyaz
```

---

## Rule No. 2: A Variable Name Should Not Start with a Number

❌ Incorrect:

```python
1name = 'ravi'

print(1name)
```

**Output:**

```text
Input In [5]
    1name = 'ravi'
    ^
SyntaxError: invalid syntax
```

✅ Correct:

```python
name1 = 'ravi'

print(name1)
```

**Output:**

```text
ravi
```

---

## Rule No. 3: A Variable Name Should Not Contain Special Characters

Special characters:

```text
@  #  $  %  &  *
```

❌ Incorrect:

```python
test@ = "navya"

print(test@)
```

**Output:**

```text
Input In [7]
    test@ = "navya"
         ^
SyntaxError: invalid syntax
```

✅ Correct:

```python
test = "navya"

print(test)
```

**Output:**

```text
navya
```

---

# Introduction to Data Types in Python

Python supports the following commonly used data types:

1. **String** → `str`

2. **Numbers**
   - Integer → `int`
   - Float → Decimal values (e.g., `0.1`, `0.2`)

3. **List** → `list`

4. **Tuple** → `tuple`

5. **Dictionary** → `dict`

6. **Set** → `set`

7. **Boolean** → `bool`

---

# Classification of Data Types

Broadly, data types are classified into **two categories**.

## 1. Mutable Data Types

- Can be edited or altered after creation.
- Flexible in nature.

**Examples**

- `list`
- `dict`
- `set`

---

## 2. Immutable Data Types

- Cannot be edited or altered after creation.
- Fixed in nature.

**Examples**

- `int`
- `float`
- `str`
- `tuple`
- `bool`

---

# Summary Table

| Data Type | Python Type | Mutable / Immutable |
|-----------|-------------|---------------------|
| String | `str` | Immutable |
| Integer | `int` | Immutable |
| Float | `float` | Immutable |
| List | `list` | Mutable |
| Tuple | `tuple` | Immutable |
| Dictionary | `dict` | Mutable |
| Set | `set` | Mutable |
| Boolean | `bool` | Immutable |

---

# Strings in Python

## Definition

A **string** is nothing but a sequence of characters enclosed within quotes.

## Classification

A **string** is an **immutable** data type.

## Ways to Define a String

A string can be defined using:

1. **Single Quotes** (`' '`)
2. **Double Quotes** (`" "`)

---

## Example 1: Single Quotes

```python
name = 'asma'      # single quote

print(name)
```

**Output**

```text
asma
```

---

## Example 2: Double Quotes

```python
name2 = "dinesh"      # double quote

print(name2)
```

**Output**

```text
dinesh
```

---

# String Methods in Python

## Example

```python
fullname = 'david jones'

print(fullname)
```

**Output**

```text
david jones
```

---

## `title()` Method

Converts the first letter of every word into uppercase.

```python
print(fullname.title())
```

**Output**

```text
David Jones
```

---

## `upper()` Method

Converts the complete string into uppercase letters.

```python
print(fullname.upper())
```

**Output**

```text
DAVID JONES
```

---

## `lower()` Method

Converts the complete string into lowercase letters.

```python
print(fullname.lower())
```

**Output**

```text
david jones
```

---

## Summary of String Methods

| Method | Description | Example Output |
|---------|-------------|----------------|
| `title()` | Converts the first letter of each word to uppercase | `David Jones` |
| `upper()` | Converts all letters to uppercase | `DAVID JONES` |
| `lower()` | Converts all letters to lowercase | `david jones` |

---

# The Zen of Python

Python follows a set of guiding principles called **The Zen of Python**, written by **Tim Peters**.

To display it, use:

```python
import this
```

**Output**

```text
The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

---

# Key Takeaways from the Zen of Python

- Beautiful code is better than ugly code.
- Explicit code is better than implicit code.
- Simple solutions are preferred over complex ones.
- Readability is very important.
- Avoid unnecessary complexity.
- Handle errors properly.
- Follow one clear and obvious way of solving problems.
- Write code that is easy to understand, explain, and maintain.
