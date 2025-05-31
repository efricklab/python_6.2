## 6.2 Lab – Loops in Python (GitHub Codespaces Version)

### **Introduction**

Loops are a fundamental part of programming that allow us to execute a block of code multiple times. Python supports several types of loops, each suited to different scenarios. In this lab, you will explore `for` loops, `while` loops, nested loops, and the `break` and `continue` statements — all within a cloud-based development environment using GitHub Codespaces.

---

### **Objectives**

By the end of this lab, you will be able to:

1. Use `for` loops to iterate over sequences.
2. Use `while` loops to execute code based on a condition.
3. Implement nested loops for multi-dimensional data structures.
4. Use `break` and `continue` statements to control loop execution.
5. Edit and run Python scripts in GitHub Codespaces.

---

### **Lab Steps**

---

### **Step 1: Launch GitHub Codespaces**

1. Open your browser and go to the repository for this lab.
2. Click the green **“Code”** button.
3. Select the **“Codespaces”** tab and click **“Create codespace on main”**.
4. Wait for the browser-based VS Code environment to load.

---

### **Step 2: Open or Create the Script**

1. In the left file explorer, locate or create the file named `loops_lab.py`.
2. If it does not exist, right-click the repo root and select **New File**, then name it `loops_lab.py`.

---

### **Step 3: Add a `for` Loop**

Open the file in Codespaces`loops_lab.py`:

```python
# For loop example: Iterating through a list of fruits
fruits = ["apple", "banana", "cherry"]
print("For loop: Iterating through a list of fruits")
for fruit in fruits:
    print(fruit)
```

---

### **Step 4: Add a `while` Loop**

Append this code below the previous section:

```python
# While loop example: Counting from 0 to 4
print("\nWhile loop: Counting from 0 to 4")
count = 0
while count < 5:
    print(count)
    count += 1
```

---

### **Step 5: Add a Nested Loop**

Add the following below:

```python
# Nested loop example: Iterating through a 2D list (matrix)
print("\nNested loop: Iterating through a 2D list")
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
for row in matrix:
    for element in row:
        print(element, end=" ")
    print()
```

---

### **Step 6: Add `break` and `continue` Examples**

Append this code to demonstrate `break` and `continue`:

```python
# Break statement example: Exiting the loop when count reaches 3
print("\nBreak statement: Exiting the loop when count reaches 3")
for count in range(5):
    if count == 3:
        break
    print(count)

# Continue statement example: Skipping even numbers
print("\nContinue statement: Skipping even numbers")
for num in range(10):
    if num % 2 == 0:
        continue
    print(num)
```

---

### **Step 7: Run the Python Script**

1. Open a terminal in Codespaces: go to `Terminal > New Terminal` or press **Ctrl + \`**.
2. Run the script:

```bash
python3 loops_lab.py
```

---

### **Step 8: View the Expected Output**

You should see:

```
For loop: Iterating through a list of fruits
apple
banana
cherry

While loop: Counting from 0 to 4
0
1
2
3
4

Nested loop: Iterating through a 2D list
1 2 3 
4 5 6 
7 8 9 

Break statement: Exiting the loop when count reaches 3
0
1
2

Continue statement: Skipping even numbers
1
3
5
7
9
```

---

### **Summary**

In this lab, you learned how to use various types of loops in Python, including `for`, `while`, and nested loops. You also used `break` and `continue` to control the flow of loop execution. Running the lab in **GitHub Codespaces** allowed you to code in the cloud without needing local software — perfect for modern, browser-based development.
