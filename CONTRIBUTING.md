# 🤝 Contributing to C++ Language Learning

Thank you for your interest in contributing to the **C++ Language Learning** repository! 🚀

This repository is primarily focused on learning **C++ programming, problem solving, and Data Structures & Algorithms (DSA)**. Contributions that improve the learning experience, code quality, documentation, and examples are always welcome.

---

## 📌 How You Can Contribute

You can contribute in several ways:

* 🐛 Fix bugs or incorrect code
* ✨ Improve existing C++ programs
* 📚 Add missing explanations or notes
* 💻 Add useful C++ examples
* 🧩 Add programming practice problems
* 🧠 Add DSA implementations
* 📝 Improve documentation
* 🔍 Fix spelling or formatting mistakes
* 💡 Suggest better approaches or solutions
* 📁 Improve repository organization

---

## 🚀 Getting Started

### 1. Fork the Repository

Click the **Fork** button at the top of the repository to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR-USERNAME/CPP-LANGUAGE-LEARNING.git
```

Move into the project directory:

```bash
cd CPP-LANGUAGE-LEARNING
```

### 3. Create a New Branch

Create a separate branch for your contribution:

```bash
git checkout -b feature/your-contribution
```

For example:

```bash
git checkout -b add-vector-examples
```

---

## 💻 C++ Code Guidelines

Please follow these guidelines when adding C++ code.

### Use Clear Names

Use meaningful variable, function, class, and file names.

**Good:**

```cpp
int studentAge = 20;
```

**Avoid:**

```cpp
int x = 20;
```

unless the variable is used in a simple mathematical or algorithmic example where `x` is appropriate.

---

### Keep Programs Simple

Since this is a learning repository, code should be easy for beginners to understand.

Prefer:

```cpp
#include <iostream>
using namespace std;

int main() {
    int number;

    cout << "Enter a number: ";
    cin >> number;

    cout << "You entered: " << number << endl;

    return 0;
}
```

over unnecessarily complicated implementations.

---

### Add Comments When Helpful

Use comments to explain important or difficult parts of the code.

```cpp
// Check whether the number is divisible by any value
// between 2 and its square root.
```

Avoid adding comments that simply repeat what the code already says.

---

## 📁 File Organization

Place files in the appropriate directory.

Example:

```text
CPP-LANGUAGE-LEARNING/
│
├── 01-Basics/
├── 02-Control-Flow/
├── 03-Functions/
├── 04-Arrays/
├── 05-Strings/
├── 06-Pointers-References/
├── 07-OOP/
├── 08-STL/
├── 09-Problem-Solving/
└── 10-DSA/
```

Please avoid placing unrelated files in the root directory.

---

## 📝 File Naming

Use descriptive and consistent file names.

### Recommended

```text
PrimeNumber.cpp
BinarySearch.cpp
FunctionOverloading.cpp
StudentClass.cpp
VectorOperations.cpp
```

### Avoid

```text
program1.cpp
test.cpp
new.cpp
abc.cpp
final.cpp
```

unless the name is appropriate for the specific example.

---

## 🧩 Adding Practice Problems

When adding a programming problem, try to include:

1. Problem statement
2. Approach or explanation
3. C++ solution
4. Example input
5. Example output

Example:

```text
Problem:
Check whether a given number is prime.

Input:
17

Output:
Prime
```

Then provide a clean C++ implementation.

---

## 🌳 Adding DSA Implementations

For DSA contributions, include the following whenever possible:

* Problem or concept name
* Short explanation
* Algorithm/approach
* C++ implementation
* Time complexity
* Space complexity
* Example

Example:

```text
Algorithm: Binary Search

Time Complexity: O(log n)
Space Complexity: O(1)
```

---

## 🧪 Test Your Code

Before submitting a contribution, make sure your C++ program:

* Compiles successfully
* Produces the expected output
* Handles common edge cases
* Does not contain unnecessary warnings
* Does not rely on machine-specific paths or settings

Compile using:

```bash
g++ filename.cpp -o program
```

Run using:

```bash
./program
```

On Windows:

```bash
program.exe
```

---

## 🔀 Commit Guidelines

Write clear and meaningful commit messages.

### Good

```text
Add vector examples
Fix binary search implementation
Add recursion notes
Improve OOP documentation
Add prime number practice problem
```

### Avoid

```text
update
changes
fixed
new
asdf
final
```

A good commit message should briefly explain **what changed**.

---

## 📤 Submit a Pull Request

After completing your changes:

### 1. Check Your Changes

```bash
git status
```

### 2. Add Your Files

```bash
git add .
```

### 3. Commit

```bash
git commit -m "Add vector examples"
```

### 4. Push Your Branch

```bash
git push origin feature/your-contribution
```

### 5. Open a Pull Request

Go to your fork on GitHub and click **New Pull Request**.

Explain:

* What you changed
* Why you made the change
* Any important details reviewers should know

---

## 📋 Pull Request Checklist

Before submitting your Pull Request, make sure:

* [ ] The code compiles successfully
* [ ] The solution has been tested
* [ ] The code follows the repository structure
* [ ] File names are descriptive
* [ ] The code is beginner-friendly
* [ ] Comments are used where necessary
* [ ] No unnecessary files were added
* [ ] Commit messages are meaningful
* [ ] Documentation is updated if necessary
* [ ] The Pull Request clearly explains the changes

---

## 🐛 Reporting Bugs

If you find an incorrect program, broken example, typo, or documentation issue, please open an **Issue**.

Include:

* The file or section affected
* Description of the problem
* Expected behavior
* Actual behavior
* Suggested solution, if you have one

For code issues, include the relevant input and output whenever possible.

---

## 💡 Suggesting Improvements

Suggestions are welcome!

Before opening an issue, please check whether a similar issue already exists.

Good suggestions include:

* New learning topics
* Better explanations
* Useful practice problems
* Improved algorithms
* Better repository organization
* Missing C++ concepts

---

## 📚 Contribution Philosophy

The primary goal of this repository is **learning**.

Therefore, contributions should prioritize:

> **Clarity > Complexity**

A simple, understandable solution is generally preferred over a highly optimized solution when the purpose is to teach a programming concept.

For advanced algorithms, however, optimized approaches and complexity analysis are encouraged.

---

## 🤝 Code of Conduct

Please be respectful and constructive when interacting with contributors.

We welcome people of different skill levels, including complete beginners.

Contributions should be:

* Respectful
* Helpful
* Constructive
* Educational
* Relevant to the repository

Please refer to the repository's `CODE_OF_CONDUCT.md` for the complete guidelines.

---

## 🔐 Security

Please do not publicly disclose security vulnerabilities through regular Issues or Pull Requests.

Refer to `SECURITY.md` for information about responsibly reporting security-related issues.

---

## ⭐ Thank You!

Every contribution — whether it's a bug fix, documentation improvement, new example, or helpful suggestion — can make this repository better for other learners.

Thank you for helping improve the **C++ Language Learning** community! ❤️

### Keep Learning. Keep Coding. Keep Improving. 🚀

**C++ → Problem Solving → DSA → Projects → Growth**
