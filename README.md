# Java Do-While Loop

A simple Java program demonstrating how to use a `do-while` loop to repeatedly execute a block of code.

## 📌 Topics Covered

* `do-while` loop
* Loop condition
* Increment operator
* Repeated execution

## 📂 Project Structure

```text id="8p3vkd"
java-do-while-loop/
│
├── DoWhileLoop.java
└── README.md
```

## 💻 Program

The `DoWhileLoop.java` program uses a `do-while` loop to print numbers from `1` to `10`.

## 🔹 Do-While Loop

A `do-while` loop executes the code block **at least once** before checking the condition.

### Syntax

```java id="c6m3nf"
do {
    // code to execute
} while (condition);
```

### Example

```java id="jv9y7q"
int i = 1;

do {
    System.out.println(i);
    i++;
} while (i <= 10);
```

## 🔍 Difference Between While and Do-While

| Loop       | Condition Checked         |
| ---------- | ------------------------- |
| `while`    | Before executing the code |
| `do-while` | After executing the code  |

## ▶️ How to Run

### Compile

```bash id="x3j2yq"
javac DoWhileLoop.java
```

### Run

```bash id="l9jz0x"
java DoWhileLoop
```

## 🖥️ Sample Output

```text id="k5e8y1"
Numbers from 1 to 10:
1
2
3
4
5
6
7
8
9
10
```

## 🎯 Purpose

This project is designed for Java beginners to understand the `do-while` loop and how it differs from the `while` loop.

## 👨‍💻 Author

K.Leelasri

# -java-do-while-loop
