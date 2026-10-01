# ai-tools-lab
AI Tools Lab is a Python project that provides simple implementations of common **sorting algorithms** and **utility functions**. The project is designed for learning, experimentation, and practicing Python development with Git and GitHub.

## 📌 Project Description

The project currently includes:

* Bubble Sort algorithm for sorting lists.
* Utility functions for common operations.
* Palindrome checking.
* Word counting.
* Celsius-to-Fahrenheit temperature conversion.

The project is organized into separate Python modules so that the functions can be easily reused in other programs.

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-tools-lab.git
```

### 2. Navigate to the project directory

```bash
cd ai-tools-lab
```

### 3. Run the Python files

Make sure Python 3 is installed on your system.

```bash
python sorting.py
```

or:

```bash
python utils.py
```

No external Python packages are required.

## 💻 Usage

### Bubble Sort

Import the `bubble_sort` function from `sorting.py`:

```python
from sorting import bubble_sort

numbers = [64, 34, 25, 12, 22, 11, 90]

result = bubble_sort(numbers)

print(result)
```

Output:

```text
[11, 12, 22, 25, 34, 64, 90]
```

### Utility Functions

Import the functions from `utils.py`:

```python
from utils import is_palindrome, count_words, celsius_to_fahrenheit

print(is_palindrome("Madam"))
print(count_words("Hello World Python"))
print(celsius_to_fahrenheit(25))
```

Output:

```text
True
3
77.0
```

## 👥 Contributors

* **Project Contributors** — Development, testing, documentation, and improvements.

Contributions are welcome! To contribute, create a new branch, make your changes, commit them, and open a Pull Request.

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this software according to the terms of the MIT License.

See the `LICENSE` file for the complete license text.

---

**AI Tools Lab** — A simple Python project for learning algorithms, utilities, and collaborative development with GitHub.
