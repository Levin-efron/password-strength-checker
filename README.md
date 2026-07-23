# 🔐 Password Strength Checker (C)

A simple command-line application written in **C** that evaluates the strength of a password based on commonly accepted security practices. The program analyzes different password characteristics and provides feedback to help users create stronger and more secure passwords.

## 📌 Features

- ✅ Checks minimum password length
- 🔠 Detects uppercase letters (A–Z)
- 🔡 Detects lowercase letters (a–z)
- 🔢 Checks for numeric digits (0–9)
- 🔣 Detects special characters
- 📊 Classifies password strength
- 💡 Provides suggestions to improve weak passwords
- ⚡ Lightweight and fast
- 💻 Runs entirely in the terminal

---

## 🛠️ Technologies Used

- C Programming Language
- Standard C Library (`stdio.h`, `string.h`, `ctype.h`)

---

## 📂 Project Structure

```
password-strength-checker/
│
├── password-strength-checker.c
└── README.md
```

---

## ⚙️ Requirements

- GCC Compiler (or any C compiler)
- Linux, Windows (MinGW), or macOS

---

## 🚀 Compilation

Using GCC:

```bash
gcc password-strength-checker.c -o password_checker
```

---

## ▶️ Running the Program

### Linux / macOS

```bash
./password_checker
```

### Windows

```bash
password_checker.exe
```

---

## 💻 Example

### Input

```
Enter your password:
MyPassword@123
```

### Output

```
Password Strength : Strong

✔ Contains uppercase letters
✔ Contains lowercase letters
✔ Contains numbers
✔ Contains special characters
✔ Password length is sufficient
```

---

## 📊 Password Evaluation Criteria

The password is evaluated using the following rules:

| Criteria | Description |
|----------|-------------|
| Length | At least 8 characters |
| Uppercase | Contains one or more uppercase letters |
| Lowercase | Contains one or more lowercase letters |
| Numbers | Contains at least one digit |
| Special Characters | Contains symbols such as !@#$%^&* |

### Strength Levels

| Score | Rating |
|------|--------|
| 0 – 2 | Weak |
| 3 – 4 | Medium |
| 5 | Strong |

---

## 🧠 How It Works

The program reads the password entered by the user and checks each character individually.

It counts whether the password contains:

- Uppercase letters
- Lowercase letters
- Digits
- Special symbols

It also verifies that the password meets the minimum length requirement. Based on the number of satisfied conditions, the program assigns a strength rating and provides feedback.

---

## 🔒 Why Strong Passwords Matter

Strong passwords help protect accounts from attacks such as:

- Brute-force attacks
- Dictionary attacks
- Credential stuffing
- Unauthorized access

Using long passwords with a combination of letters, numbers, and symbols greatly improves security.

---

## 🎯 Learning Objectives

This project demonstrates:

- Character handling in C
- Conditional statements
- Loops
- String manipulation
- Password validation logic
- Command-line application development

---

## 🚀 Future Improvements

Some possible enhancements include:

- Password entropy calculation
- Password generator
- Detection of repeated characters
- Detection of sequential characters (123, abc)
- Detection of common passwords
- Colored terminal output
- Menu-driven interface
- File-based password analysis

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Levin Efron**

- GitHub: https://github.com/Levin-efron

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
