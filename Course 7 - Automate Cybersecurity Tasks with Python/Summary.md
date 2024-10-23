# Python Concepts and Feedback

---

## **Advantages of Python**

- Resembles **human language** for easier comprehension.
- Requires **less code** to accomplish tasks.
- **Easy to read** with clear syntax.
- Follows **standard guidelines** (PEP 8).
- Large **online community** for support.
- Comes with **built-in standard libraries** for various tasks.

---

## **Python Commands**

- `type(x)`: Returns the data type of a variable.
- `for i in range(10)`: Repeats the action 10 times.
- `while x <= 10`: Repeats until `x > 10`.

---

## **Feedback on Python Labs**

- **Jupyter Notebooks** are useful but not ideal compared to dedicated IDEs.
- **Linux labs** felt more effective for learning.

---

## **Unusual Aspects in Python**

- `def`: Equivalent to function definition (`fun`).
- `sorted(list)`: Sorts items **alphabetically**.
- `print("hello this is day", 5, "today")`: Demonstrates **string formatting**.
- **Module:** Similar to a package.  
  **Library:** A collection of multiple modules.

### **Common Python Modules**
- **`re`**: Regular expressions (regex).
- **`csv`**: CSV file utilities.
- **`glob`, `os`**: Command-line helpers.
- **`time`, `datetime`**: Date and time utilities.
- **`statistics`**: Mean, median, and other statistical functions.

- **PEP 8:** Official **style guide** (Python Enhancement Proposals) for Python code.

---

## **Working with Strings**

- `"HELLO"[1]` → Extracts `'E'`.
- `"HELLO"[-1]` → Extracts `'O'`.
- `"HELLO"[1:4]` → Slices `'ELL'` (from position 1 to 3).
- `"HELLO".index("E")` → Returns the index `1`.
- **Immutable strings:** Strings can’t be modified directly.

---

## **Working with Lists**

Similar to strings, since they behave as **lists of characters**.

- **`list + list2`** → Combines two lists.
- **Lists are mutable**: You can modify values using `list[2] = X`.
- `list.insert(a, x)`: Inserts item `x` at position `a`.
- `list.remove(x)`: Removes the element `x`.
- `list.append(x)`: Adds item `x` to the end of the list.

---

## **Reminders for Loops and Slicing**

- `for x in list`: Iterates over the items in the list.
- `string[0:3]`: Extracts elements at positions 0, 1, and 2.

---

## **Regex (Regular Expressions)**

- `+`: One or more characters (e.g., `a+` matches `'a'`, `'aaa'`).
- `*`: Zero or more characters.
- `{2}`: Exactly two occurrences (e.g., `a{2}` matches `'baad'`).
- `{2,4}`: Between 2 and 4 occurrences.
- `\w`: Alphanumeric character (e.g., `\w+` matches `'abc'`, `'199d9'`).
- `\w+@\w+\.\w+`: Basic email format.
- `re.findall("\w+@\w+\.\w+", "mystring")`: Finds all matches for the email pattern.
- `\d`: Matches a **digit**.
- `\s`: Matches a **space**.
- `\.`: Matches a **literal dot**.
- `.`: Matches **any character** (including symbols).

---

## **Working with Files**

### **Opening Files**

```python
with open("myfile.txt", "r") as file:

