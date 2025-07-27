## ✅ **Experiment 2: Exploring Data Types and Storage Classes in C++**

---

### 🎯 **Aim**

To understand different **data types** and **storage classes** in C++, and observe their behavior and memory usage using simple programs.

---

### 🛠️ **Tool Used**

* Visual Studio Code (VS Code)

---

### 🎯 **Objectives**

* Learn about **basic data types** and how much memory they use
* Understand the use of **auto, register, static, and extern** storage classes
* Use the `sizeof()` operator to check memory size
* Observe how variable values change or stay the same in repeated function calls

---

### 📘 **Theory**

#### ✅ Data Types:

Common data types in C++ include:

* `int` – whole numbers (e.g., 1, 2, 100)
* `float` – decimal numbers (e.g., 3.14)
* `double` – more precise decimal numbers
* `char` – single characters (e.g., 'A')
* `bool` – true or false
* `short`, `long` – smaller or larger integers

Use `sizeof()` to check how much memory each type uses.

#### ✅ Storage Classes:

| Storage Class | Behavior                                                               |
| ------------- | ---------------------------------------------------------------------- |
| `auto`        | Default for local variables; value resets each time function runs      |
| `register`    | Tries to store variable in CPU register for fast access (no address)   |
| `static`      | Keeps its value between function calls                                 |
| `extern`      | Used to declare a global variable from another file (optional for now) |

---

### 🧾 **Algorithm**

**Step 1:** Start the program
**Step 2:** Declare variables of types: `int`, `float`, `char`, `double`, `bool`
**Step 3:** Use `sizeof()` to display the memory size of each type
**Step 4:** Write a function to demonstrate `auto` and `static` variables
**Step 5:** Call the function multiple times to see the value change or reset
**Step 6:** Declare a `register` variable and show its usage
**Step 7:** End the program

---

### 🔎 **Sample Output**


Enter an Integer Number: 10
Integer: 10 | Size: 4 bytes

Enter a Float Number: 3.14
Float: 3.14 | Size: 4 bytes

Enter a Double Number: 3.14159
Double: 3.14159 | Size: 8 bytes

Enter a Character: A
Character: A | Size: 1 byte

Enter a String (one word): Hello
String: Hello | Size (object): 32 bytes

Enter a Boolean Value (1 for true, 0 for false): 1
Boolean: 1 | Size: 1 byte

Enter a Short Integer: 100
Short: 100 | Size: 2 bytes

Enter a Long Integer: 999999999
Long: 999999999 | Size: 8 bytes




### ✅ **Conclusion**

From this experiment, you learned:

* How much memory common data types use
* How `auto` variables reset every time
* How `static` variables keep their values
* How `register` variables help in fast access
* What `extern` variables are used for (advanced)

