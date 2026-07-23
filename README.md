# 🔐 Password Strength Checker

A simple and efficient Python application that evaluates the strength of a password based on common security best practices. This tool helps users create stronger passwords by analyzing different password characteristics and providing instant feedback.

## 🚀 Features

- ✅ Checks minimum password length
- 🔠 Detects uppercase and lowercase letters
- 🔢 Verifies the presence of numeric digits
- 🔣 Checks for special characters
- 📊 Classifies password strength (Weak, Medium, Strong)
- 💡 Provides suggestions to improve weak passwords
- ⚡ Lightweight and easy to use

---

## 📂 Project Structure

```
password-strength-checker/
│
├── password_strength_checker.py
├── README.md
└── LICENSE (optional)
```

---

## 🛠️ Requirements

- Python 3.8 or higher

No external libraries are required.

---

## 📥 Installation

Clone this repository:

```bash
git clone https://github.com/Levin-efron/password-strength-checker.git
```

Navigate to the project directory:

```bash
cd password-strength-checker
```

---

## ▶️ Usage

Run the Python script:

```bash
python password_strength_checker.py
```

Enter a password when prompted.

Example:

```
Enter your password:
MyPassword@123

Password Strength: Strong

✔ Contains uppercase letters
✔ Contains lowercase letters
✔ Contains numbers
✔ Contains special characters
✔ Password length is sufficient
```

---

## 📈 Password Evaluation Criteria

The password is evaluated based on the following factors:

- Minimum length (8+ characters)
- Uppercase letters (A-Z)
- Lowercase letters (a-z)
- Numbers (0-9)
- Special characters (!@#$%^&* etc.)

Depending on how many criteria are satisfied, the password is rated as:

| Score | Strength |
|--------|----------|
| 0–2 | Weak |
| 3–4 | Medium |
| 5 | Strong |

---

## 💻 Technologies Used

- Python 3
- Regular Expressions (Regex)
- String Processing

---

## 📚 Learning Objectives

This project was created to practice:

- Python programming
- Conditional statements
- Regular Expressions
- Functions
- User input handling
- Password validation logic

---

## 🔒 Why Password Strength Matters

Weak passwords are one of the most common causes of security breaches. A strong password significantly reduces the risk of:

- Brute-force attacks
- Dictionary attacks
- Credential stuffing
- Unauthorized account access

This project demonstrates the basic principles behind password validation used in many authentication systems.

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## ⭐ Future Improvements

- Password entropy calculation
- Password generator
- GUI version using Tkinter
- Web version using Flask
- Dark mode interface
- Check against common leaked passwords
- Export password analysis report

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Levin Efron**

- GitHub: https://github.com/Levin-efron

If you found this project helpful, consider giving it a ⭐ on GitHub!
